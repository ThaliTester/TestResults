#### Test 77622416b768259_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-27 15:04:14.037  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 15:04:14.037  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
--------- beginning of system
07-27 15:04:14.037   790  1145 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 15:04:14.037   790  1145 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 15:04:14.037   790  1145 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 15:04:14.037   790  1145 D BatteryService: stay LED for fully charged
07-27 15:04:14.037   790   790 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 15:04:14.037  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-27 15:04:14.037  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 15:04:14.037  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 15:04:14.037  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 15:04:14.037   790   790 I MotionRecognitionService: Plugged
07-27 15:04:14.037   790   790 I MotionRecognitionService: setPowerConnected  = true
07-27 15:04:14.047  3010  3010 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 15:04:14.047  3010  3083 D HeadsetStateMachine: Disconnected process message: 10
,07-27 15:04:14.546  7515  7515 D AndroidRuntime: 
07-27 15:04:14.546  7515  7515 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 15:04:14.556  7515  7515 D AndroidRuntime: CheckJNI is OFF
07-27 15:04:14.556  7515  7515 D AndroidRuntime: readGMSProperty: start
07-27 15:04:14.556  7515  7515 D AndroidRuntime: readGMSProperty: already setted!!
07-27 15:04:14.556  7515  7515 D AndroidRuntime: readGMSProperty: end
07-27 15:04:14.556  7515  7515 D AndroidRuntime: addProductProperty: start
07-27 15:04:14.726  7515  7515 E AffinityControl: AffinityControl: registerfunction enter
07-27 15:04:14.746  7515  7515 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 15:04:14.756   790  1361 E PersonaManagerService: inState():  stateMachine is null !!
07-27 15:04:14.756   790  1361 I PersonaManagerService: PersonaId don't exist
07-27 15:04:14.756   790  1361 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-27 15:04:14.756   790  1361 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-27 15:04:14.756   790  1361 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 15:04:14.756   790  1361 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-27 15:04:14.766   790  1361 W ActivityManager: mDVFSHelper.acquire()
07-27 15:04:14.766   790  1361 D FocusedStackFrame: Set to : 0
07-27 15:04:14.766   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:14.766   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:14.766   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:14.766   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:14.816   790  1361 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7530 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 15:04:14.826   790  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 15:04:14.826   790  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 15:04:14.826   790  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 15:04:14.826   790  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 15:04:14.826  7515  7515 D AndroidRuntime: Shutting down VM
07-27 15:04:14.836  7530  7530 E Zygote  : MountEmulatedStorage()
07-27 15:04:14.836  7530  7530 E Zygote  : v2
07-27 15:04:14.836  7530  7530 I libpersona: KNOX_SDCARD checking this for 10079
07-27 15:04:14.836  7530  7530 I libpersona: KNOX_SDCARD not a persona
07-27 15:04:14.846  7530  7530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:14.846  7530  7530 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:14.846  7530  7530 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-27 15:04:14.876  7530  7530 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 15:04:14.876  7530  7530 D ActivityThread: Added TimaKeyStore provider
07-27 15:04:14.876   790  1686 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 15:04:14.876   790  1686 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 15:04:14.876   790  1686 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 15:04:14.876   790  1686 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 15:04:14.876   790  1686 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 15:04:14.906   790  3089 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:14.906  1443  1443 D SurfaceWidgetView: destroyHardwareResources():289479137
07-27 15:04:14.916  7530  7530 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-27 15:04:14.936   790  3089 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:14.946   266  1460 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-27 15:04:14.946   266  1768 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-27 15:04:14.956  1443  1443 V ActivityThread: updateVisibility : ActivityRecord{336182f3 token=android.os.BinderProxy@379e421 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 15:04:14.956  1762  1779 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-27 15:04:14.956  1443  1443 D Launcher: onTrimMemory. Level: 20
07-27 15:04:15.006   303   303 E SMD     : DCD ON
07-27 15:04:15.016  7530  7530 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-27 15:04:15.016  7530  7530 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-27 15:04:15.026  7530  7530 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1264-1266)
07-27 15:04:15.026  7530  7530 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 15:04:15.066  7530  7530 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a198f30}
07-27 15:04:15.066  7530  7530 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 15:04:15.066  7530  7530 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 15:04:15.086  7530  7530 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 15:04:15.096  7530  7530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 15:04:15.096  7530  7530 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 15:04:15.106  7530  7530 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-27 15:04:15.106  7530  7530 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-27 15:04:15.106  7530  7530 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-27 15:04:15.116  7530  7530 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 15:04:15.116  7530  7530 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 15:04:15.116  7530  7530 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 15:04:15.116  7530  7530 I Adreno-EGL: Local Branch: mybranch5813579
07-27 15:04:15.116  7530  7530 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 15:04:15.116  7530  7530 I Adreno-EGL: Local Patches: NONE
07-27 15:04:15.116  7530  7530 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
07-27 15:04:15.206  7530  7567 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-27 15:04:15.236  7530  7530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 15:04:15.246  7530  7530 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 15:04:15.256  7530  7530 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-27 15:04:15.266  7530  7530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 15:04:15.266  7530  7530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 15:04:15.316  7530  7530 D Activity: performCreate Call secproduct feature valuefalse
07-27 15:04:15.316  7530  7530 D Activity: performCreate Call debug elastic valuetrue
07-27 15:04:15.326  7530  7584 D OpenGLRenderer: Render dirty regions requested: true
07-27 15:04:15.326   790  1686 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 15:04:15.326   790  1686 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 15:04:15.326   790  1686 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-27 15:04:15.326   790   790 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 15:04:15.326   790   790 D PersonaManagerService: getPersonasForUser(): returning null!
07-27 15:04:15.346   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
07-27 15:04:15.346   790  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 15:04:15.346   790  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 15:04:15.376   790  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 15:04:15.376   790  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 15:04:15.376   790  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 15:04:15.376   790  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 15:04:15.376  7530  7584 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 15:04:15.376  7530  7584 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3ca7ec0 ,&mEglDisplay = 1 , &mEglConfig = 8 
07-27 15:04:15.376  7530  7584 D OpenGLRenderer: Enabling debug mode 0
07-27 15:04:15.396  7530  7530 V ActivityThread: updateVisibility : ActivityRecord{3aee1dea token=android.os.BinderProxy@e2a268c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-27 15:04:15.416   790  1267 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-27 15:04:15.426   790  7591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-27 15:04:15.436  7530  7530 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-27 15:04:15.436  7530  7530 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e2a268c time:151672
07-27 15:04:15.436  1739  1739 I SamsungIME: getCurrentCandidateView
07-27 15:04:15.436   790  1059 W ActivityManager: mDVFSHelper.release()
07-27 15:04:15.436   790  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7e6cc5b u0 com.test.thalitest/.MainActivity t99} time:151678
07-27 15:04:15.486  7530  7530 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7530
07-27 15:04:15.506  1739  1739 D SamsungIME: Dismiss ExpandCandiate
07-27 15:04:15.596  1739  1739 I SamsungIME: getDebugLevel  : 0x4f4c
07-27 15:04:15.596  7530  7530 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 15:04:15.626  1739  1739 I SamsungIME: getDebugLevel  : 0x4f4c
07-27 15:04:15.636  1739  1739 I SamsungIME: KeybaordView init() : load resources
07-27 15:04:15.666  1739  1739 I SamsungIME: getCurrentKeyboard
07-27 15:04:15.666  1739  1739 I SamsungIME: getTextKeyboard
07-27 15:04:15.666  7530  7597 D jxcore_app_log: JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359649152
07-27 15:04:15.676  7530  7597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 15:04:15.676  7530  7597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 15:04:15.676  7530  7597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 15:04:15.676  7530  7597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 15:04:15.676  7530  7597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 15:04:15.676  7530  7597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ac1d59a added. We now have 1 listener(s)
07-27 15:04:15.676  1739  1739 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
07-27 15:04:15.686  7530  7597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
07-27 15:04:15.686  7530  7597 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:15.686  7530  7597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:15.686  7530  7597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 15:04:15.686  7530  7597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71f45c1 added. We now have 1 listener(s)
07-27 15:04:15.686  7530  7597 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:15.696  7530  7597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:15.696  7530  7597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 15:04:15.696  7530  7597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 15:04:15.696  7530  7597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 15:04:15.706  7530  7597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:15.706  7530  7597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
07-27 15:04:15.706   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:15.706  7530  7597 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:15.706  7530  7597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:15.706  7530  7597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 15:04:15.706  7530  7597 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:15.706   790  1267 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:15.706  7530  7597 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 15:04:15.706  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:15.716   790  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:15.716  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:15.736  7530  7530 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-27 15:04:16.016  1739  7603 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-27 15:04:16.366  7530  7607 W jxcore-log: Initializing JXcore engine
07-27 15:04:16.366  7530  7607 W jxcore-log: JXcore engine is ready
07-27 15:04:16.416  1800  1800 E audit   : type=1400 msg=audit(1469624656.416:203): avc:  denied  { ioctl } for  pid=7607 comm="Thread-1233" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 15:04:16.416  1800  1800 E auditd  : In denial and Property audit_ondenial is set to 1 
07-27 15:04:16.426  1800  1800 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-27 15:04:16.426  1800  1800 E audit   : 
07-27 15:04:16.426  1800  1800 E audit   : type=1300 msg=audit(1469624656.416:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=983a08d8 items=0 ppid=346 ppcomm=main pid=7607 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1233" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-27 15:04:16.426  1800  1800 E audit   : type=1320 msg=audit(1469624656.416:203): 
07-27 15:04:16.426   790  1055 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-27 15:04:16.426   790  1055 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-27 15:04:16.426   790  1055 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-27 15:04:16.426  7271  7271 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
07-27 15:04:16.426  7271  7271 D SecurityLogAgent:  SeDenialReceiver : File path = null
07-27 15:04:16.436  7530  7607 W jxcore-log: Starting JXcore engine
07-27 15:04:16.536  7530  7607 W jxcore-log: Platform android
07-27 15:04:16.536  7530  7607 W jxcore-log: 
07-27 15:04:16.536  7530  7607 W jxcore-log: Process ARCH arm
07-27 15:04:16.536  7530  7607 W jxcore-log: 
07-27 15:04:16.706  7530  7607 I jxcore-log: JXcore Cordova bridge is ready!
07-27 15:04:16.706  7530  7607 I jxcore-log: 
07-27 15:04:16.706  7530  7607 W jxcore-log: JXcore engine is started
07-27 15:04:16.706  7530  7597 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 15:04:16.706  7530  7530 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 15:04:17.736   790  1061 I PowerManagerService: [PWL] Off : 75s ago
,07-27 15:04:18.006   303   303 E SMD     : DCD ON
,07-27 15:04:20.116   790  3122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 15:04:21.006   303   303 E SMD     : DCD ON
,07-27 15:04:23.106   790  3089 D SSRM:n  : SIOP:: AP = 380, PST = 367, CUR = 450
,07-27 15:04:24.006   303   303 E SMD     : DCD ON
,07-27 15:04:24.116   790  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 15:04:24.116   790  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 15:04:24.126   790  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 15:04:24.126   790  1458 D BatteryService: stay LED for fully charged
,07-27 15:04:24.126   790   790 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 15:04:24.126  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 15:04:24.126  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 15:04:24.136  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 15:04:24.136   790   790 I MotionRecognitionService: Plugged
07-27 15:04:24.136   790   790 I MotionRecognitionService: setPowerConnected  = true
07-27 15:04:24.136  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:24.136  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:24.136  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:24.136  3010  3010 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 15:04:24.136  3010  3083 D HeadsetStateMachine: Disconnected process message: 10
,07-27 15:04:24.356   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:24.776   790  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 15:04:25.356   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:26.356   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:26.736  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 15:04:26.736  7530  7607 I jxcore-log: 
,07-27 15:04:26.736  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 15:04:26.736  7530  7607 I jxcore-log: 
,07-27 15:04:26.736   790  1361 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:26.746  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:26.746  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 15:04:26.746  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 15:04:26.746  7530  7607 I jxcore-log: 
,07-27 15:04:26.746  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 15:04:26.746  7530  7607 I jxcore-log: 
,07-27 15:04:27.016   303   303 E SMD     : DCD ON
,07-27 15:04:27.086  7530  7607 D ExecuteNativeTests: Running unit tests
,07-27 15:04:27.186  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:27.186  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 added. We now have 2 listener(s)
,07-27 15:04:27.186  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 15:04:27.186  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:27.186  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:27.186  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:27.186  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 added. We now have 2 listener(s)
07-27 15:04:27.186  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:27.186  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:27.186  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:27.186   790  1361 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:27.196  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:27.196  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.196  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 15:04:27.196   790  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.196  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.196   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.196  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:27.206  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-27 15:04:27.206  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:27.206  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-27 15:04:27.216  7530  7607 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-27 15:04:27.216  7530  7607 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-27 15:04:27.216  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 15:04:27.216  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:27.216  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 15:04:27.216  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 15:04:27.216  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 15:04:27.216  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 15:04:27.216  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 15:04:27.216  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.216  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 15:04:27.216  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:27.216  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 removed from the list
,07-27 15:04:27.216  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.216  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 removed from the list
07-27 15:04:27.216  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 15:04:27.216  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:27.216  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
,07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-27 15:04:27.226  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.226  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.226  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.226  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.226  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.226  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
,07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 15:04:27.236   790  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 15:04:27.226  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.226  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.226  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.226  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.236   790  3246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.226  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.226  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.226  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.236   790  1267 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.226  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.226  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.226  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.236  7530  7607 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 15:04:27.236  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:27.236  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:27.236  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.236  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:27.236  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.236  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.236  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:27.236  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:27.236  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.236  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:27.246  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 15:04:27.246  7530  7607 E BluetoothAdapter: bluetooth le advertising not supported
07-27 15:04:27.246  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:27.246  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 15:04:27.246  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-27 15:04:27.246  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 15:04:27.246  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:27.246  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:27.256  7530  7607 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:27.256  7530  7607 I io.jxcore.node.ConnectionHelper: start: OK
07-27 15:04:27.256  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.256  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.256  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.256  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.256  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.256  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:27.256  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.256  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.256  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.256  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.256  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.256  7530  7607 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 15:04:27.256  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.256   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:27.256  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:27.256  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.256  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:27.256   790  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.266  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.266   790  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.266  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.266  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:27.266  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:27.266  7530  7607 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:27.266  7530  7607 I io.jxcore.node.ConnectionHelper: start: OK
07-27 15:04:27.266  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.266  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.266  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.266  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.266  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:27.266  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.266  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.266  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.266  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.266  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.266  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.266  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.266  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.266  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.266  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.266  7530  7607 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 15:04:27.276   790  1266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.276  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:27.276  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:27.276  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.276  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:27.276   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.276  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.276   790  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.276  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.276  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:27.276  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:27.276  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.276  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:27.276  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:27.276  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:27.286  7530  7607 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: start: OK
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.286  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.286  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.286  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.286  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 15:04:27.286  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.286  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.286  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.286  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.286  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.286  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.286  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.296  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 15:04:27.296  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 15:04:27.296  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 15:04:27.296  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:27.296  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.296  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.296  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.296  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.296  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.296  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.296  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.296  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.296  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.296  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.296  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.296  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.296  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.296  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.296  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:27.296  7530  7607 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 15:04:27.296  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:27.296  7530  7607 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 15:04:27.296  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 15:04:27.296  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 15:04:27.296  7530  7607 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 15:04:27.296  7530  7607 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 15:04:27.296  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:27.296  7530  7607 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 15:04:27.296  7530  7607 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 15:04:27.296  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:27.296  7530  7607 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 15:04:27.296  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 15:04:27.306  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-27 15:04:27.306  7530  7607 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:27.306  7530  7607 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-27 15:04:27.306  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.306  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.306  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.306  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 15:04:27.306  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.306  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.306  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.306  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.306  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.306  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.306  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.306  7530  7607 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-27 15:04:27.306  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.306  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.306  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.306  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.306  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.306  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.306  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.306  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.306  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.306  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.306  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.306  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.306  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.306  7530  7607 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 15:04:27.306  7530  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1297)
07-27 15:04:27.316  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.316  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.316  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.316  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.316  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.316  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.316  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.316  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.316  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.316  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.316  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.316  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.316  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.316  7530  7614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1297
07-27 15:04:27.316  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.316  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.316  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.316  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.316  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.316  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-27 15:04:27.316  7530  7607 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 15:04:27.316  7530  7607 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 15:04:27.316  7530  7607 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 15:04:27.316  7530  7607 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 15:04:27.316  7530  7607 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 15:04:27.316  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 15:04:27.316  7530  7607 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 15:04:27.316  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.316  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.316  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.326  7530  7613 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
07-27 15:04:27.326  7530  7613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.326  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.326  3010  3329 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:27.326  7530  7613 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.326  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.326  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.326  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.326  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.326  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.326  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.326  3010  3170 D bt_upio : proc btwrite assertion
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.326  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.326  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.326  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.326  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 15:04:27.336  7530  7530 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 15:04:27.336  7530  7530 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 15:04:27.336  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-27 15:04:27.336  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 15:04:27.336  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 15:04:27.336  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.336  7530  7607 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 15:04:27.346  7530  7530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 15:04:27.346  7530  7530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 15:04:27.346  7530  7530 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 15:04:27.346  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.346  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.346  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.346  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.346  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.346  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.346  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.346  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.346  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.346  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.346  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.346  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.346  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.346  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.346  7530  7615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 15:04:27.346  7530  7615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 15:04:27.346  7530  7530 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 15:04:27.346  7530  7607 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-27 15:04:27.346  7530  7607 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 15:04:27.346  7530  7607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:27.346  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.346  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.346  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.346  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.346  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.346  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.346  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.346  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.346  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.346  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.346  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.346  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.346  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.356  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.356  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.356  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.356  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.356  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.356  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.356  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.356  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.356  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.356  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.356  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.356  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.356  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:27.356  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:27.356  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:27.356  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.356  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba91287 not in the list
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.356  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.356  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:27.356  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.356  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:27.356  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:27.356   362   362 I ServiceManager: Waiting for service AtCmdFwd...
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:27.356  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:27.366  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60c35b4 not in the list
07-27 15:04:27.366  7530  7607 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 15:04:27.366  7530  7607 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 15:04:27.366  7530  7607 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-27 15:04:27.366  7530  7607 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 15:04:27.366  7530  7607 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 15:04:27.366  7530  7607 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 15:04:27.366  7530  7607 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 15:04:27.376  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:27.376  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32e6f395 added. We now have 2 listener(s)
07-27 15:04:27.376  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:27.376  7530  7607 D BluetoothAdapter: enable()
07-27 15:04:27.376  7530  7607 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 15:04:27.376  7530  7607 I WifiManager: packageName : com.test.thalitest
07-27 15:04:27.376   790  1267 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 15:04:27.376   790  1267 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 15:04:27.376   790  1267 D SecContentProvider2: mCursor = null
07-27 15:04:27.376   790  1267 D WifiService: setWifiEnabled: true pid=7530, uid=10079
07-27 15:04:27.376   790  1267 W ActivityManager: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:27.376   790  1267 W WifiService: Failed getting userId using ActivityManagerNative
07-27 15:04:27.376   790  1267 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:27.376   790  1267 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 15:04:27.376   790  1267 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 15:04:27.376   790  1267 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 15:04:27.376   790  1267 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 15:04:27.376   790  1267 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 15:04:27.376   790  1267 D SettingsProvider: name = wifi_on
07-27 15:04:27.376  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:27.376  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cb4caa added. We now have 3 listener(s)
07-27 15:04:27.376  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:27.376  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:27.376  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3167a09b added. We now have 4 listener(s)
07-27 15:04:27.376  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:27.386  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:27.386  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ef0cc38 added. We now have 5 listener(s)
07-27 15:04:27.386  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:27.386  7530  7607 I WifiManager: packageName : com.test.thalitest
,07-27 15:04:27.386   790  1266 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 15:04:27.386   790  1266 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 15:04:27.386   790  1266 D SecContentProvider2: mCursor = null
,07-27 15:04:27.386   790  1266 D WifiService: setWifiEnabled: false pid=7530, uid=10079
,07-27 15:04:27.386   790  1266 D SettingsProvider: name = wifi_on
,07-27 15:04:27.386   790  1150 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-27 15:04:27.386  7530  7607 D BluetoothAdapter: disable()
07-27 15:04:27.386  1281  1281 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 15:04:27.386  1281  1281 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 15:04:27.396  1281  1281 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-27 15:04:27.396   790  1267 D SettingsProvider: name = bluetooth_on
,07-27 15:04:27.396   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:27.396  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:27.396   790  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.396  3010  3073 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-27 15:04:27.406  3010  3073 D BluetoothAdapterProperties: Setting state to 13
07-27 15:04:27.406  3010  3073 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 15:04:27.406  3010  3073 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:27.406  3010  3073 D BluetoothAdapterService: updateAdapterState state is 13
,07-27 15:04:27.406   790  1635 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.406   790  1635 D ActivityManager: caller:android.app.ApplicationThreadProxy@3cedcc1b, r.packageName :com.android.bluetooth
,07-27 15:04:27.406  1281  1281 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-27 15:04:27.406  3010  3073 D BluetoothAdapterService: Autoconnection is available 
07-27 15:04:27.406  3010  3073 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-27 15:04:27.406  3010  3073 D BluetoothAdapterService: terminating service from this receiver
07-27 15:04:27.406  3010  3010 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-27 15:04:27.406  3010  3073 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 15:04:27.406  3010  3010 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26289f6d, channel: 19, state: LISTENING
07-27 15:04:27.406  3010  3010 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26289f6d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11304eb5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b2d47a2mSocket: android.net.LocalSocket@27670c33 impl:android.net.LocalSocketImpl@f09ebf0 fd:FileDescriptor[72]
07-27 15:04:27.406  3010  3010 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27670c33 impl:android.net.LocalSocketImpl@f09ebf0 fd:FileDescriptor[72]
07-27 15:04:27.406   790  1377 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-27 15:04:27.406  3010  3073 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 15:04:27.406  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.406  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.406  3010  3076 D BluetoothAdapterProperties: Scan Mode:20
07-27 15:04:27.406  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.406  3010  3170 D bt_upio : BT_WAKE is asserted already
07-27 15:04:27.406  3010  3073 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 15:04:27.406  3010  3073 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-27 15:04:27.406  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.406  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.406  3010  3073 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
07-27 15:04:27.406  3010  3073 E bt-btif : cmd socket is not created
,07-27 15:04:27.406  3010  5655 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-27 15:04:27.406  7530  7613 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ae98976, channel: -1, state: INIT
07-27 15:04:27.406  7530  7613 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ae98976, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2495ab77, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30273e4mSocket: android.net.LocalSocket@db3004d impl:android.net.LocalSocketImpl@27dcc702 fd:FileDescriptor[112]
07-27 15:04:27.406  7530  7613 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@db3004d impl:android.net.LocalSocketImpl@27dcc702 fd:FileDescriptor[112]
07-27 15:04:27.406  7530  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1297)
,07-27 15:04:27.416  3010  3168 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
07-27 15:04:27.416  3010  3168 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-27 15:04:27.416  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:27.416  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:27.416  3010  3168 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:27.416  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.416  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.416  1315  1315 D BluetoothPbap: Proxy object disconnected
07-27 15:04:27.416  1315  1315 D PbapServerProfile: Bluetooth service disconnected
07-27 15:04:27.416  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.416  3010  3170 D bt_upio : BT_WAKE is asserted already
07-27 15:04:27.416  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:27.416  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:27.416  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.416  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.416  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:27.416   790  1264 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.416  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.416  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.416  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.416  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.416  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.416   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.416  3010  3073 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-27 15:04:27.416  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.416  3010  3170 D bt_upio : BT_WAKE is asserted already
07-27 15:04:27.416   790  1150 E native  : do suspend true
,07-27 15:04:27.416  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.416  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.426   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:27.426  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.426  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.426  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:27.426   790  1264 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.426  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.426   790   790 I InputMethodManagerService: [BT Setting State] State =13
07-27 15:04:27.426  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.426  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.426  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.426  3010  3170 D bt_vendor: op for 7
,07-27 15:04:27.426  3010  3170 D bt_upio : BT_WAKE is asserted already
07-27 15:04:27.426  1197  1197 D BluetoothTile:  onBluetoothStateChange:
07-27 15:04:27.426   790  1149 D WifiP2pService: InactiveState{ what=143375 }
07-27 15:04:27.426   790  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 15:04:27.426  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.426  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.426  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.426  3010  3170 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:27.436  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 15:04:27.436  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:27.436  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:27.436  1197  1594 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 15:04:27.436  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:27.436  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:27.436   790  1377 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:27.436   298  1054 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:27.436  1739  1739 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-27 15:04:27.436   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d5251b8, r.packageName :com.google.android.gms
07-27 15:04:27.436  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.436  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 15:04:27.436   790  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.446  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:27.446   790  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.446   790  1458 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:27.446  1197  1594 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 15:04:27.446  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 15:04:27.446   790  3246 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 15:04:27.446  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 15:04:27.446  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.446   790  1635 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.446  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:27.456  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 15:04:27.456  1834  5078 V NativeCrypto: Read error: ssl=0x9b5d1e00: I/O error during system call, Connection timed out
,07-27 15:04:27.456  1834  5078 V NativeCrypto: SSL shutdown failed: ssl=0x9b5d1e00: I/O error during system call, Broken pipe
,07-27 15:04:27.466   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.466  3010  3010 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24bc3bee, channel: 5, state: LISTENING
,07-27 15:04:27.466   790  1686 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-27 15:04:27.466  3010  3010 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24bc3bee, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e8ad94a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@67c388fmSocket: android.net.LocalSocket@29b9d71c impl:android.net.LocalSocketImpl@1f534f25 fd:FileDescriptor[74]
,07-27 15:04:27.466  3010  3010 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29b9d71c impl:android.net.LocalSocketImpl@1f534f25 fd:FileDescriptor[74]
07-27 15:04:27.466  3010  3010 I BtOppRfcommListener: stopping Accept Thread
07-27 15:04:27.466  3010  3010 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@143428fa, channel: 12, state: LISTENING
,07-27 15:04:27.466  3010  3010 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@143428fa, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@209c9b84, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a0dceabmSocket: android.net.LocalSocket@201b4908 impl:android.net.LocalSocketImpl@eb8a1 fd:FileDescriptor[79]
07-27 15:04:27.466  3010  3010 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@201b4908 impl:android.net.LocalSocketImpl@eb8a1 fd:FileDescriptor[79]
07-27 15:04:27.466  3010  5655 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-27 15:04:27.466   790  1686 D ActivityManager: caller:android.app.ApplicationThreadProxy@6384af6, r.packageName :com.android.settings
,07-27 15:04:27.476   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:27.476   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:27.476   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:27.476   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:27.476   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
07-27 15:04:27.476   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:27.486  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 15:04:27.486   790   790 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:27.486  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 15:04:27.486  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 15:04:27.496  1834  5078 E GCM     : Wifi connection closed with errorCode 20
07-27 15:04:27.496   790  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.496   790  3246 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,07-27 15:04:27.496   790  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.496   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:27.496   790  1267 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.496   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:27.496   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-27 15:04:27.496   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:27.496   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-27 15:04:27.496   790  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 15:04:27.496   790  1266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.496   790  1757 I qtaguid : Tagging socket 346 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 790, getuid(): 1000
,07-27 15:04:27.496   790  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 15:04:27.506   790  1150 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 15:04:27.506   790   790 D WifiScanningService: SCAN_AVAILABLE : 1
,07-27 15:04:27.506   790   790 D RttService: SCAN_AVAILABLE : 1
07-27 15:04:27.506   790  1167 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 15:04:27.506   790  1149 D WifiP2pService: InactiveState{ what=131204 }
07-27 15:04:27.506   790  1149 D WifiP2pService: P2pEnabledState{ what=131204 }
07-27 15:04:27.506   790  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 15:04:27.506   790  1149 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-27 15:04:27.506   790  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.506   790  1059 D WifiDisplayAdapter: onP2pDisconnected
07-27 15:04:27.506   790  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 15:04:27.506   790  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 15:04:27.506   790  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-27 15:04:27.506   790   790 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-27 15:04:27.506   790  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-27 15:04:27.506   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-27 15:04:27.506   790  1149 D WifiP2pService: P2pDisablingState
07-27 15:04:27.506   790  1059 D WifiDisplayController: disconnect
07-27 15:04:27.506   790  1059 D WifiDisplayController: updateConnection
07-27 15:04:27.506   790  1149 D WifiP2pService: P2pDisablingState{ what=147458 }
07-27 15:04:27.506   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:27.506   790  1149 D WifiP2pService: p2p socket connection lost
,07-27 15:04:27.516   790  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 15:04:27.516   790  1149 D WifiP2pService: P2pDisabledState
,07-27 15:04:27.516   790  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:27.516   790  1059 D WifiDisplayAdapter: onP2pDisconnected
07-27 15:04:27.516   790  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 15:04:27.516   790  1150 E native  : do suspend true
07-27 15:04:27.516   790  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 15:04:27.516   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.516  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-27 15:04:27.516   790   806 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 15:04:27.516  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 15:04:27.516   790  1149 D WifiP2pService: P2pDisabledState{ what=143375 }
,07-27 15:04:27.526  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:27.526   790  1149 D WifiP2pService: DefaultState{ what=143375 }
07-27 15:04:27.526  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:27.526  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:27.526  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:27.526   790  1704 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.526   790  3246 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-27 15:04:27.526   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:27.526   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:27.526   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:27.526   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:27.536   298  1054 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:27.536   790  1152 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-27 15:04:27.536   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:27.536   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:27.536   790  1058 D EntConnectivity: Not allowed due to - mEnabled false
07-27 15:04:27.536   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-27 15:04:27.536   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-27 15:04:27.536   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:27.546   790  1152 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:27.546   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:27.546  1197  1584 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 15:04:27.546   790  1152 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:27.546   790  1152 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-27 15:04:27.546   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:27.546   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:27.546   790  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 15:04:27.546  4446  7480 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-27 15:04:27.546   790  1152 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:27.546   790  1152 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:27.546  1427  1427 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:27.546   790  1152 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-27 15:04:27.546   790  1152 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,07-27 15:04:27.546   790  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-27 15:04:27.566  7639  7639 E Zygote  : MountEmulatedStorage()
07-27 15:04:27.566  7639  7639 E Zygote  : v2
07-27 15:04:27.566  7639  7639 I libpersona: KNOX_SDCARD checking this for 10140
07-27 15:04:27.566  7639  7639 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:27.576  7639  7639 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 15:04:27.576  7639  7639 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:27.576  7639  7639 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 15:04:27.576   790  3246 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7639 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-27 15:04:27.586  1281  1281 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-27 15:04:27.586   790   790 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:27.586  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 15:04:27.586   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:27.586   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:27.586   790  1152 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:27.586   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:27.586   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:27.586   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:27.586   790  1152 E ConnectivityService: updateNetworkInfo()
,07-27 15:04:27.586   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-27 15:04:27.586   790  1152 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-27 15:04:27.586   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:27.586  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.586  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.596  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:27.596  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,07-27 15:04:27.596  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 15:04:27.596  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:27.596   346   346 I art     : Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 13.357ms
,07-27 15:04:27.596  1197  1197 D HotspotTile: onReceive : 0, 0
,07-27 15:04:27.596   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:27.596   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.596   790  1147 V NetworkStats: updateIfacesLocked()
07-27 15:04:27.596   790  1147 V NetworkStats: performPollLocked(flags=0x1)
,07-27 15:04:27.596   790  1153 D Tethering: MasterInitialState.processMessage what=3
07-27 15:04:27.596   790  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 15:04:27.596   790  1154 D SmartBondingService: getSBEnabled() enabled =false
,07-27 15:04:27.596   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:27.596   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:27.596  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:27.596   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
07-27 15:04:27.596   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.596   790  1147 V NetworkStats: performPollLocked() took 5ms
07-27 15:04:27.596   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:27.596  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: updateDataNetType()
07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 15:04:27.606  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-27 15:04:27.606   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:27.606   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 15:04:27.606   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.618ms
07-27 15:04:27.606   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.606   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.606   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.606   790  1148 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-27 15:04:27.606  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:27.606  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.606  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:27.606  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:27.606  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-27 15:04:27.606   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.606   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 15:04:27.606  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:27.616  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.616  3010  3170 D bt_vendor: op for 6
07-27 15:04:27.616  3010  3170 D bt_vendor: op for 7
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:27.616  3010  3170 D bt_upio : BT_WAKE is asserted already
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:27.616  3010  3168 W bt-btif : ag scb idx 1 not allocated
07-27 15:04:27.616  3010  3168 W bt-btif : ag scb idx 2 not allocated
07-27 15:04:27.616  3010  3168 E bt-btif : BTA AG is already disabled, ignoring ...
,07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.616  3010  3172 D bt_userial: RX termination
07-27 15:04:27.616  3010  3172 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-27 15:04:27.616  3010  3172 D bt_userial: Leaving userial_read_thread()
07-27 15:04:27.616  3010  3076 D bt_userial: userial_close_reader Joined userial reader thread: 0
07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:27.616  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:27.616  3010  3170 D bt_vendor: op for 9
07-27 15:04:27.616  3010  3170 D bt_hwcfg: hw_epilog_process
07-27 15:04:27.616   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 9.730ms
07-27 15:04:27.616  3010  3076 D bt_vendor: op for 4
07-27 15:04:27.616  3010  3076 I bt_userial_vendor: device fd = 65 close
07-27 15:04:27.616  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:27.616  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:27.616   790  1635 I AudioService: getStreamVolume 3 index 0
07-27 15:04:27.616  3010  3076 D bt_vendor: op for 0
07-27 15:04:27.616  3010  3076 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 15:04:27.616  3010  3076 D bt_upio : is_emulator_context : 0
07-27 15:04:27.616  3010  3076 D bt_upio : is_rfkill_disabled ? [0]
,07-27 15:04:27.616  3010  3076 D bt_vendor: cleanup
,07-27 15:04:27.616  3010  3168 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 15:04:27.616  3010  3076 I GKI_LINUX: GKI_exit_task 0 done
07-27 15:04:27.616  3010  3076 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-27 15:04:27.616  3010  3073 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 15:04:27.616  3010  3073 D BtConfig.SecureMode: isSecureModeOn:false
07-27 15:04:27.616  3010  3073 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-27 15:04:27.616  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-27 15:04:27.616  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 15:04:27.616  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-27 15:04:27.616   790  1648 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.616   790  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@14dfa393, r.packageName :com.android.bluetooth
07-27 15:04:27.616  3010  3010 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 15:04:27.626  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 15:04:27.626  3010  3010 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 15:04:27.626  3010  3010 D BtGatt.GattService: stop()
07-27 15:04:27.626  3010  3010 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-27 15:04:27.626   790  1267 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.626   790  1267 D ActivityManager: caller:android.app.ApplicationThreadProxy@1dc19fd0, r.packageName :com.android.bluetooth
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 15:04:27.626  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 15:04:27.626  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-27 15:04:27.626   790  1266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.626   790  1266 D ActivityManager: caller:android.app.ApplicationThreadProxy@15029bc9, r.packageName :com.android.bluetooth
,07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 15:04:27.626  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:27.626  3010  3010 D HeadsetService: Received stop request...Stopping profile...
,07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-27 15:04:27.626  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.626   790   806 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.626   790   806 D ActivityManager: caller:android.app.ApplicationThreadProxy@409c2ce, r.packageName :com.android.bluetooth
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 15:04:27.626  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 15:04:27.626   790  3246 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.626   790  3246 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ad6e5ef, r.packageName :com.android.bluetooth
07-27 15:04:27.626   790   790 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 15:04:27.626  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-27 15:04:27.626   790  1377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.626   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d68e8fc, r.packageName :com.android.bluetooth
07-27 15:04:27.626  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.626  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.636   790  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.636  1315  1315 D HeadsetProfile: Bluetooth service disconnected
07-27 15:04:27.636   790  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@b902b85, r.packageName :com.android.bluetooth
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 15:04:27.636  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-27 15:04:27.636   790  1377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:27.636   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@7833dda, r.packageName :com.android.bluetooth
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:27.636  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:27.636  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 15:04:27.636  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 15:04:27.636  3010  3073 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 15:04:27.636  3010  3073 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 15:04:27.646  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-27 15:04:27.646  3010  3073 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 15:04:27.646  3010  3010 D A2dpService: Received stop request...Stopping profile...
07-27 15:04:27.646  3010  3085 D A2dpStateMachine: Exit Disconnected: -1
07-27 15:04:27.646  3010  3010 V Avrcp   : doQuit
07-27 15:04:27.646  3010  3010 D Avrcp   : Unregistering previous receiver
07-27 15:04:27.646  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.646  3186  3186 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:27.646  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-27 15:04:27.646  3010  3010 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:27.646  3010  3010 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-27 15:04:27.646  3010  3010 D HidService: Received stop request...Stopping profile...
07-27 15:04:27.646  3010  3010 D HidService: Stopping Bluetooth HidService
07-27 15:04:27.646  3010  3010 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 15:04:27.646  3010  3010 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-27 15:04:27.646  3010  3010 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 15:04:27.646  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.646   790   790 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:27.646   790   790 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 15:04:27.646  1315  1315 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:27.646  1315  1315 D A2dpProfile: Bluetooth service disconnected
07-27 15:04:27.646  1315  1315 D BluetoothInputDevice: Proxy object disconnected
07-27 15:04:27.646  1315  1315 D HidProfile: Bluetooth service disconnected
07-27 15:04:27.646  3010  3010 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 15:04:27.646  3010  3010 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:27.646  3010  3010 D HealthService: Received stop request...Stopping profile...
07-27 15:04:27.646  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.646  3010  3010 D PanService: Received stop request...Stopping profile...
07-27 15:04:27.646  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.646  7639  7639 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 15:04:27.646  3010  3010 D BluetoothMapService: Received stop request...Stopping profile...
07-27 15:04:27.656   790   790 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 15:04:27.656  7639  7639 D ActivityThread: Added TimaKeyStore provider
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.656  1315  1315 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 15:04:27.656  1315  1315 D PanProfile: Bluetooth service disconnected
07-27 15:04:27.656  3010  3010 D SapService: Received stop request...Stopping profile...
07-27 15:04:27.656  3010  3010 D SapService: Stopping Bluetooth SapService
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:27.656  1315  1315 D BluetoothMap: Proxy object disconnected
07-27 15:04:27.656  1315  1315 D MapProfile: Bluetooth service disconnected
07-27 15:04:27.656  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-27 15:04:27.656  3010  3010 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-27 15:04:27.656  3010  3010 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-27 15:04:27.656  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-27 15:04:27.656  1315  1315 D SapProfile: Bluetooth service disconnected
07-27 15:04:27.656  3010  3087 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 15:04:27.656  3010  3010 I GKI_LINUX: GKI_exit_task 2 done
07-27 15:04:27.656  3010  3010 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 15:04:27.656  3010  3010 V Avrcp   : cleanup
07-27 15:04:27.656  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-27 15:04:27.656  3010  3010 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.656  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-27 15:04:27.656  3010  3010 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.656  3010  3010 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 15:04:27.656  3010  3010 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 15:04:27.656  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-27 15:04:27.656  3010  3010 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:27.656  3010  3010 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 15:04:27.656  3010  3010 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 15:04:27.656  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-27 15:04:27.656  3010  3010 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 15:04:27.656  3010  3010 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-27 15:04:27.656  3010  3010 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-27 15:04:27.656  3010  3010 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-27 15:04:27.656  3010  3010 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-27 15:04:27.656  3010  3073 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-27 15:04:27.656  3010  3073 D BluetoothAdapterProperties: Setting state to 10
07-27 15:04:27.656  3010  3073 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 15:04:27.656  3010  3073 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:27.656  3010  3073 D BluetoothAdapterService: updateAdapterState state is 10
07-27 15:04:27.666  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
07-27 15:04:27.666  1315  1328 D BluetoothMap: onBluetoothStateChange: up=false
07-27 15:04:27.666  3010  3073 D BluetoothAdapterService: Autoconnection is available 
07-27 15:04:27.666  3010  3073 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-27 15:04:27.666  3010  3073 I BluetoothAdapterState: Entering OffState
07-27 15:04:27.666  3010  3329 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:27.666   790  1058 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:27.676  1315  1336 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 15:04:27.676  3186  3202 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:27.676  1315  1328 D Bluetoothsap: onBluetoothStateChange: up=false
07-27 15:04:27.676  1315  1328 D Bluetoothsap: Unbinding service...
07-27 15:04:27.676  1315  1336 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:27.676  7639  7639 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
07-27 15:04:27.676  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 15:04:27.676  1315  1328 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 15:04:27.676  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.676   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
,07-27 15:04:27.686  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.686  1281  1281 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-27 15:04:27.686  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 15:04:27.686   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 15:04:27.686  1281  1281 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-27 15:04:27.686  1281  1281 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-27 15:04:27.686  1281  1281 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-27 15:04:27.686  1281  1281 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-27 15:04:27.686   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:27.686  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:27.686  1197  1197 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:27.686  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 15:04:27.686  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:27.686  1197  1197 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:27.686  1197  1197 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:27.686  1197  1594 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:27.686   790   790 I InputMethodManagerService: [BT Setting State] State =10
,07-27 15:04:27.696   790  1576 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 15:04:27.696  1197  1594 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:27.696   790   790 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-27 15:04:27.696  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 15:04:27.696  1834  2327 D BluetoothAdapter: 135578864: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:27.696   790   805 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-27 15:04:27.696  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:27.696  1834  2327 D BluetoothAdapter: 135578864: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:27.696  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 15:04:27.696  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:27.696  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.696  1739  1739 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 15:04:27.696  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.696  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.696  3010  3076 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-27 15:04:27.696  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.706  3010  3010 I GKI_LINUX: GKI_exit_task 1 done
,07-27 15:04:27.706  3010  3010 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-27 15:04:27.706  3010  3010 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 15:04:27.706  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.706  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.716  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 15:04:27.716  3010  3010 I art     : System.exit called, status: 0
07-27 15:04:27.716  3010  3010 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 15:04:27.716  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.716  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.716  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 15:04:27.756   790  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:27.756   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@10e75da6, r.packageName :com.google.android.gms
,07-27 15:04:27.766  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:27.766   790   805 I ActivityManager: Process com.android.bluetooth (pid 3010)(adj 0) has died(211,1562)
,07-27 15:04:27.786   790  1377 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:27.786   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@235b94, r.packageName :com.google.android.gms
,07-27 15:04:27.916   790  1153 D Tethering: InitialState.processMessage what=4
07-27 15:04:27.916  1281  1281 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-27 15:04:27.926   790  1153 E Tethering: No numeric data
,07-27 15:04:27.926   790  1153 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-27 15:04:27.926   790  1147 V NetworkStats: performPollLocked(flags=0x1)
07-27 15:04:27.926   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:27.926  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:27.926  1197  1197 D HotspotTile: updateTetherState():false, false
,07-27 15:04:27.926   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 15:04:27.926   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:27.926   790  1147 V NetworkStats: performPollLocked() took 5ms
07-27 15:04:27.926   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:27.926   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:27.926   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.File.exists(File.java:363)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956   790  1458 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.k.c(PG:583)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.956  7639  7639 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.io.File.exists(File.java:363)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:27.956  7639  7639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:27.966  1834  1834 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 15:04:27.966  1834  1834 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 15:04:27.976  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:27.976  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-27 15:04:27.976   790  1377 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-27 15:04:27.986   790  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:27.986   790  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:27.986   790  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:27.986   790  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:28.016  7639  7676 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-27 15:04:28.016   790  1377 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7686 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-27 15:04:28.026  7686  7686 E Zygote  : MountEmulatedStorage()
07-27 15:04:28.026  7686  7686 E Zygote  : v2
07-27 15:04:28.026  7686  7686 I libpersona: KNOX_SDCARD checking this for 10038
07-27 15:04:28.026  7686  7686 I libpersona: KNOX_SDCARD not a persona
07-27 15:04:28.026   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-27 15:04:28.026   790  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-27 15:04:28.026   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:28.056  7686  7686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:28.056  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:28.056  7686  7686 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:28.056  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 15:04:28.056  1834  2327 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:28.056   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 15:04:28.056  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:28.056  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 15:04:28.056  1197  1197 D HotspotTile: onReceive : 1, 0
07-27 15:04:28.056  7686  7686 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-27 15:04:28.056  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:28.056  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,07-27 15:04:28.056  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:28.056  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:28.056  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:28.086   790  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:28.096   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:28.096   790   790 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.096   790  1018 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:28.096   790   790 I ApplicationPolicy: updateDataUsageMap
07-27 15:04:28.096   790  1018 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:28.096   790  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,07-27 15:04:28.096   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:28.096   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:28.096   790  1154 D SmartBondingService: getSBEnabled() enabled =false
,07-27 15:04:28.096  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:28.106  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:28.106  1497  1497 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-27 15:04:28.106   790  1267 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.106   790  1264 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.106  7686  7686 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 15:04:28.106   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 15:04:28.106  7686  7686 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:28.116  7686  7686 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-27 15:04:28.126  7686  7686 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-27 15:04:28.126  1834  1901 I art     : Explicit concurrent mark sweep GC freed 64869(3MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 22MB/37MB, paused 584us total 51.469ms
,07-27 15:04:28.166   790  1474 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-27 15:04:28.196   790  1361 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-27 15:04:28.196  1834  1834 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c8a969b8-1333-4509-87bf-aba007255040
,07-27 15:04:28.226   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-27 15:04:28.276  7686  7686 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-27 15:04:28.296  1834  2217 W GCoreFlp: No location to return for getLastLocation()
,07-27 15:04:28.316   790  1266 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a2c9b53, r.packageName :com.google.android.gms
,07-27 15:04:28.316   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@1839c90, r.packageName :com.google.android.gms
,07-27 15:04:28.316   790  1686 D ActivityManager: caller:android.app.ApplicationThreadProxy@261db989, r.packageName :com.google.android.gms
,07-27 15:04:28.316  1834  2263 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 15:04:28.316  4446  7672 D UdcContextInitService: registered all accounts: true
,07-27 15:04:28.326  1834  2342 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-27 15:04:28.366   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:28.366  7686  7686 D BluetoothAdapter: 569355293: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:28.376  7686  7686 D BluetoothAdapter: 569355293: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:28.376  7686  7686 D BluetoothAdapter: 569355293: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:28.376  7686  7686 D BluetoothAdapter: 569355293: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:28.376  7686  7686 D BluetoothAdapter: 569355293: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:28.376  7686  7686 D BluetoothAdapter: 569355293: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:28.386  1834  2342 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-27 15:04:28.416  7686  7686 E BluetoothHeadset: BTStateChangeCB is registed
,07-27 15:04:28.416   790   806 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:28.416  7686  7686 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:28.426  1834  2342 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-27 15:04:28.426  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 15:04:28.426  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:28.426   790  1266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.426  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 15:04:28.426   790  1267 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:28.426  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:28.426  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-27 15:04:28.426  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:28.426  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:28.436   790  1686 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.436   790  1474 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-27 15:04:28.446  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:28.446  4446  4987 V UdcCtxListenerSrv: handle intent
,07-27 15:04:28.446   790  1704 D SettingsProvider: name = driving_mode_on
07-27 15:04:28.446   790  1704 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:28.446   790  1704 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:28.446   790  1704 D SettingsProvider: selectionArgs: false
07-27 15:04:28.446   790  1704 D SettingsProvider: selectionArgs: 10038
07-27 15:04:28.446   790  1704 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:28.446   790  1704 D SettingsProvider: ret = -1
,07-27 15:04:28.456  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-27 15:04:28.456   790  1635 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-27 15:04:28.456   790  1635 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.456   790  1635 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.456   790  1635 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.456   790  1635 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:28.476   790   805 I art     : Explicit concurrent mark sweep GC freed 60437(3MB) AllocSpace objects, 23(416KB) LOS objects, 30% free, 37MB/53MB, paused 1.589ms total 98.952ms
,07-27 15:04:28.496  7714  7714 E Zygote  : MountEmulatedStorage()
,07-27 15:04:28.496  7714  7714 E Zygote  : v2
07-27 15:04:28.496  7714  7714 I libpersona: KNOX_SDCARD checking this for 10131
07-27 15:04:28.496  7714  7714 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:28.506   790  1635 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7714 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 15:04:28.526  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:28.526  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:28.526  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 15:04:28.526   790  1474 I ActivityManager: Killing 6834:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-27 15:04:28.536   790  1576 I ActivityManager: Killing 6906:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,07-27 15:04:28.546  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:28.546  7714  7714 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:28.566  7714  7714 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-27 15:04:28.576  7714  7714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 15:04:28.746  7714  7742 I Babel   : MmsConfig: mnc/mcc: 0/0
07-27 15:04:28.746  7714  7742 I Babel   : MmsConfig.loadMmsSettings
,07-27 15:04:28.746  7714  7714 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-27 15:04:28.746  7714  7742 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
07-27 15:04:28.746  7714  7742 I Babel   : MmsConfig.loadFromDatabase
,07-27 15:04:28.756  7714  7742 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-27 15:04:28.756  7714  7742 I Babel   : MmsConfig.loadFromResources
,07-27 15:04:28.756  7714  7742 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 15:04:28.756  7714  7742 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-27 15:04:28.766   790  3246 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-27 15:04:28.766  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:28.796  7714  7714 I Babel_StickerModule: App launched.
,07-27 15:04:28.806  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:28.806  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:28.806   790   806 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:28.806  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:28.806   790  1704 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:28.806  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:28.806  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:28.806  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:28.806  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:28.806  7387  7387 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 15:04:28.816   790  1576 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-27 15:04:28.816   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:28.816   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.816   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.816   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:28.816   310   762 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-27 15:04:28.816   310   762 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-27 15:04:28.816   310   762 W QCamera2Factory: getCameraInfo: X
,07-27 15:04:28.816   310   310 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-27 15:04:28.816   310   310 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-27 15:04:28.816   310   310 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-27 15:04:28.816   310   310 W QCamera2Factory: getCameraInfo: X
,07-27 15:04:28.826  7714  7714 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 15:04:28.826  7714  7714 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 15:04:28.826  7714  7714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/x-ima
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 15:04:28.836  7714  7714 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 15:04:28.856  7744  7744 E Zygote  : MountEmulatedStorage()
,07-27 15:04:28.856  7744  7744 E Zygote  : v2
07-27 15:04:28.856  7744  7744 I libpersona: KNOX_SDCARD checking this for 10192
07-27 15:04:28.856  7744  7744 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:28.866   790  1576 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7744 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:28.896  7744  7744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:28.896  7744  7744 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:28.896  7744  7744 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:28.896  7714  7714 W VideoCapabilities: Unsupported mime video/wvc1
,07-27 15:04:28.896  7714  7714 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-27 15:04:28.916  7744  7744 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:28.916  7744  7744 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:28.926  7714  7714 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-27 15:04:28.926  7714  7714 W VideoCapabilities: Unsupported mime video/wvc1
,07-27 15:04:28.926  7714  7714 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-27 15:04:28.926  7714  7714 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-27 15:04:28.926  7744  7744 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-27 15:04:28.926  7714  7714 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-27 15:04:28.926  7714  7714 W VideoCapabilities: Unsupported mime video/mp43
,07-27 15:04:28.936  7714  7714 W VideoCapabilities: Unsupported mime video/sorenson
,07-27 15:04:28.946  7714  7714 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 15:04:28.946  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:28.946  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-27 15:04:28.946  7744  7744 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 15:04:28.946  7744  7744 D WifiDirectBR: stopServiceTest : false
,07-27 15:04:28.956  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 15:04:28.956   790  1635 I ActivityManager: Killing 6922:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-27 15:04:28.956  7714  7714 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 15:04:28.956  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 15:04:28.956  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:28.956   790  1474 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.956  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:28.956   790   806 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:28.966  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:28.966  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:28.966  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 15:04:28.966  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:28.966   790  1266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.966  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:28.976  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:28.986   790  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:28.986  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:28.986  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:28.986  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 15:04:28.986  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:28.996  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 15:04:28.996   790  1648 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 15:04:28.996   790  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@3aa966a2, r.packageName :com.android.settings
,07-27 15:04:28.996  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:28.996  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:28.996   790  1576 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,07-27 15:04:28.996   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.996   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.996   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:28.996   790  1576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:29.086  7763  7763 E Zygote  : MountEmulatedStorage()
07-27 15:04:29.086  7763  7763 E Zygote  : v2
07-27 15:04:29.086  7763  7763 I libpersona: KNOX_SDCARD checking this for 1002
07-27 15:04:29.086  7763  7763 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:29.086   790  1576 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7763 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-27 15:04:29.096   790  1264 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-27 15:04:29.096  7763  7763 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:29.096  7763  7763 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:29.096  7763  7763 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:29.096   790  1266 I ActivityManager: Killing 6949:com.wsomacp/u0a29 (adj 15): emptyCount ##41
,07-27 15:04:29.116  7763  7763 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:29.116  7763  7763 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:29.126  7763  7763 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-27 15:04:29.126  7763  7763 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-27 15:04:29.126  7763  7763 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 15:04:29.156  7763  7763 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding GattService
,07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding HeadsetService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding A2dpService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding HidService
,07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding HealthService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding PanService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding SapService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding SapClientService
,07-27 15:04:29.176  7763  7763 D BtSettings.ProfileConfig: Adding HidDevService
07-27 15:04:29.176  7763  7763 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 15:04:29.176   790  1361 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
07-27 15:04:29.176   790  1361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.176   790  1361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.176   790  1361 D SettingsProvider: selectionArgs: false
07-27 15:04:29.176   790  1361 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.176   790  1361 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.176   790  1361 D SettingsProvider: ret = -1
,07-27 15:04:29.176   790   805 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 15:04:29.176   790   805 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.176   790   805 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.176   790   805 D SettingsProvider: selectionArgs: false
07-27 15:04:29.176   790   805 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.176   790   805 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.176   790   805 D SettingsProvider: ret = -1
,07-27 15:04:29.186   790  1145 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-27 15:04:29.186   790  1145 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1145 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1145 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1145 D SettingsProvider: selectionArgs: 1002
,07-27 15:04:29.186   790  1145 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1145 D SettingsProvider: ret = -1
,07-27 15:04:29.186   790  1267 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-27 15:04:29.186   790  1267 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1267 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1267 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1267 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1267 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1267 D SettingsProvider: ret = -1
,07-27 15:04:29.186   790  1377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 15:04:29.186   790  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1377 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1377 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1377 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,07-27 15:04:29.186   790  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1474 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1474 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1474 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  1264 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-27 15:04:29.186   790  1264 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:29.186   790  1264 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1264 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1264 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1264 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1264 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  1686 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-27 15:04:29.186   790  1686 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1686 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 15:04:29.186   790  1686 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1686 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1686 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1686 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  1576 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:29.186   790  1576 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1576 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1576 D SettingsProvider: selectionArgs: false
,07-27 15:04:29.186   790  1576 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1576 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1576 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  1635 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:29.186   790  1635 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1635 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1635 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1635 D SettingsProvider: selectionArgs: 1002
,07-27 15:04:29.186   790  1635 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  1635 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  1266 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
07-27 15:04:29.186   790  1266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  1266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  1266 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  1266 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  1266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:29.186   790  1266 D SettingsProvider: ret = -1
07-27 15:04:29.186   790  3246 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-27 15:04:29.186   790  3246 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:29.186   790  3246 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:29.186   790  3246 D SettingsProvider: selectionArgs: false
07-27 15:04:29.186   790  3246 D SettingsProvider: selectionArgs: 1002
07-27 15:04:29.186   790  3246 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:29.186   790  3246 D SettingsProvider: ret = -1
,07-27 15:04:29.196   790   806 I ActivityManager: Killing 6942:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-27 15:04:29.196  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:29.196   790   805 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:29.196   790   805 D ActivityManager: caller:android.app.ApplicationThreadProxy@95b4aee, r.packageName :com.google.android.gms
,07-27 15:04:29.206  1834  7780 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 15:04:29.206  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:29.216  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:29.226   790   805 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:29.226  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:29.226  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:29.226  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:29.226  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:29.226   790  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@f2c61ab, r.packageName :com.google.android.gms
,07-27 15:04:29.226  1834  7780 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-27 15:04:29.236   790  1266 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-27 15:04:29.236   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.236   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.236   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.236   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:29.316  7782  7782 E Zygote  : MountEmulatedStorage()
07-27 15:04:29.316  7782  7782 E Zygote  : v2
07-27 15:04:29.316  7782  7782 I libpersona: KNOX_SDCARD checking this for 1000
07-27 15:04:29.316  7782  7782 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:29.316   790  1266 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7782 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 15:04:29.326  7782  7782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:29.326  7782  7782 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:29.326  7782  7782 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:29.346  7782  7782 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:29.346  7782  7782 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:29.356  7782  7782 D ResourcesManager: creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,07-27 15:04:29.366   362   362 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-27 15:04:29.366  7782  7782 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-27 15:04:29.366  7782  7782 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-27 15:04:29.366  7782  7782 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-27 15:04:29.376  7782  7782 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-27 15:04:29.376  7782  7782 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-27 15:04:29.386  7782  7782 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 15:04:29.386  7782  7782 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:29.386  7782  7782 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-27 15:04:29.386   790  1458 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-27 15:04:29.386   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.386   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.386   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.386   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:29.426  7798  7798 E Zygote  : MountEmulatedStorage()
,07-27 15:04:29.426  7798  7798 E Zygote  : v2
07-27 15:04:29.426  7798  7798 I libpersona: KNOX_SDCARD checking this for 10144
07-27 15:04:29.426  7798  7798 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:29.436  7798  7798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:29.436  7798  7798 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:29.436  7798  7798 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 15:04:29.436   790  1458 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7798 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:29.456  7798  7798 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:29.456  7798  7798 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:29.466  7798  7798 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 15:04:29.556  7798  7798 I MusicStore: Database version: 108
,07-27 15:04:29.566   790  1458 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.616  7798  7798 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-27 15:04:29.616  7798  7798 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-27 15:04:29.616  7798  7798 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 15:04:29.646  7798  7798 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 15:04:29.686  7798  7798 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 15:04:29.686  7798  7798 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37672d97: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-27 15:04:29.686  7798  7798 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-27 15:04:29.686  7798  7798 D AndroidMusic: GMSCore installation verified
,07-27 15:04:29.696   790  1267 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.706  7798  7798 I ConfigStore: Config Database version: 1
,07-27 15:04:29.746   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-27 15:04:29.746   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:29.746  7798  7798 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-27 15:04:29.746   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-27 15:04:29.746   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:29.746  7798  7798 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-27 15:04:29.746   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-27 15:04:29.746   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:29.746  7798  7798 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-27 15:04:29.756   790  1361 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-27 15:04:29.756   790  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@192783aa, r.packageName :com.google.android.music
,07-27 15:04:29.766   790  1686 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.786   790  1266 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 15:04:29.796   790  1704 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 15:04:29.796   790   806 I AudioService: getStreamVolume 3 index 0
,07-27 15:04:29.796  7798  7798 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-27 15:04:29.806  7798  7798 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-27 15:04:29.826   790  1686 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.836   790  1704 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.836   790  1267 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.836   790  1648 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 15:04:29.846   790  1458 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-27 15:04:29.846   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.846   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.846   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.846   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:29.886  7826  7826 E Zygote  : MountEmulatedStorage()
,07-27 15:04:29.886  7826  7826 E Zygote  : v2
07-27 15:04:29.886  7826  7826 I libpersona: KNOX_SDCARD checking this for 10004
07-27 15:04:29.886  7826  7826 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:29.896   790  1458 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7826 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:29.906  7826  7826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 15:04:29.906  7826  7826 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:29.906  7826  7826 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:29.916   790  1474 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-27 15:04:29.926  7798  7798 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-27 15:04:29.926   790  1267 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:29.926  7826  7826 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:29.936  7826  7826 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:29.946  7826  7826 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-27 15:04:29.946   790  1635 I ActivityManager: Killing 6977:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-27 15:04:29.986   790  1648 I ActivityManager: Killing 7016:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-27 15:04:29.986   790  1266 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-27 15:04:29.986   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.986   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.986   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:29.986   790  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:30.016   303   303 E SMD     : DCD ON
,07-27 15:04:30.026  7846  7846 E Zygote  : MountEmulatedStorage()
,07-27 15:04:30.026  7846  7846 E Zygote  : v2
07-27 15:04:30.026  7846  7846 I libpersona: KNOX_SDCARD checking this for 1000
07-27 15:04:30.026  7846  7846 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:30.036  7846  7846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:30.036  7846  7846 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:30.036  7846  7846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:30.036   790  1266 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7846 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 15:04:30.056  7846  7846 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:30.056  7846  7846 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:30.066  7846  7846 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-27 15:04:30.096  7846  7846 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-27 15:04:30.116  7846  7846 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-27 15:04:30.216  7846  7846 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-27 15:04:30.226  7846  7846 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-27 15:04:30.226  7846  7846 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:30.226  7846  7846 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 15:04:30.296  7174  7174 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-27 15:04:30.296  7174  7174 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-27 15:04:30.316  7174  7174 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-27 15:04:30.326   790  1648 I ActivityManager: Killing 7034:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-27 15:04:30.326  3952  3952 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 15:04:30.326  3952  3952 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469624670340
,07-27 15:04:30.326  3952  3952 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:30.326   790  1266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:30.326   790  1576 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:30.326  3952  3952 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-27 15:04:30.336  3952  3952 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-27 15:04:30.336   790  1264 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-27 15:04:30.336   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.336   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.336   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.336   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:30.376  7862  7862 E Zygote  : MountEmulatedStorage()
07-27 15:04:30.376  7862  7862 E Zygote  : v2
07-27 15:04:30.376  7862  7862 I libpersona: KNOX_SDCARD checking this for 10036
07-27 15:04:30.376  7862  7862 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:30.386   790  1264 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7862 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-27 15:04:30.386  7862  7862 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:30.386  7862  7862 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:30.386  7862  7862 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:30.396  7862  7862 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:30.406  7862  7862 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:30.416  7862  7862 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-27 15:04:30.416  7862  7862 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 15:04:30.416  7530  7607 I WifiManager: packageName : com.test.thalitest
,07-27 15:04:30.416   790  1264 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 15:04:30.416   790  1264 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 15:04:30.416   790  1264 D SecContentProvider2: mCursor = null
07-27 15:04:30.416  7862  7862 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 15:04:30.416   790  1264 D WifiService: setWifiEnabled: true pid=7530, uid=10079
07-27 15:04:30.416   790  1264 W ActivityManager: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:30.416   790  1264 W WifiService: Failed getting userId using ActivityManagerNative
07-27 15:04:30.416   790  1264 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:30.416   790  1264 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 15:04:30.416   790  1264 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 15:04:30.416   790  1264 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 15:04:30.416   790  1264 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 15:04:30.416   790  1264 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 15:04:30.416   790  1264 D SettingsProvider: name = wifi_on
,07-27 15:04:30.426   790  1150 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 15:04:30.426   298  1054 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-27 15:04:30.426   298  1054 I WifiHW  : module is semco
07-27 15:04:30.426   298  1054 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-27 15:04:30.426   298  1054 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-27 15:04:30.426   298  1054 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 15:04:30.426   298  1054 D SoftapController: Softap fwReload - Ok
,07-27 15:04:30.426   298  1054 D CommandListener: Setting iface cfg
07-27 15:04:30.426   298  1054 D CommandListener: Trying to bring down wlan0
,07-27 15:04:30.426   298  1054 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:30.436   790  1150 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 15:04:30.436   790  1150 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 15:04:30.436   790  1150 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-27 15:04:30.436   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:30.436  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:30.436  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 15:04:30.436  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:30.436  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:30.436  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-27 15:04:30.436  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:30.436  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 15:04:30.436  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:30.436  1197  1197 D HotspotTile: onReceive : 2, 0
,07-27 15:04:30.436   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 15:04:30.436  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:30.446  1834  2342 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
07-27 15:04:30.446  1834  2342 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-27 15:04:30.456  7862  7862 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-27 15:04:30.466   790  1576 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:30.466  7878  7878 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-27 15:04:30.466  7878  7878 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 15:04:30.476  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 15:04:30.476  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 15:04:30.476   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7878
07-27 15:04:30.476   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-27 15:04:30.476  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 15:04:30.476   790   805 I ActivityManager: Killing 7050:com.samsung.helphub/1000 (adj 15): emptyCount ##41
07-27 15:04:30.476  7878  7878 I wpa_supplicant: ssSupport state is = 1
07-27 15:04:30.476  7878  7878 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-27 15:04:30.476  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 15:04:30.476   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7878
07-27 15:04:30.476   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-27 15:04:30.486  7190  7190 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-27 15:04:30.486   790  1361 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-27 15:04:30.486   790  1635 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:30.486   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.486  3535  7879 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
07-27 15:04:30.486   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:30.486   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.486   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.486   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:30.496  3535  7879 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-27 15:04:30.496  3535  7879 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-27 15:04:30.496  3535  7879 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-27 15:04:30.496  3535  7879 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-27 15:04:30.576  7881  7881 E Zygote  : MountEmulatedStorage()
07-27 15:04:30.576  7881  7881 E Zygote  : v2
07-27 15:04:30.576  7881  7881 I libpersona: KNOX_SDCARD checking this for 10043
07-27 15:04:30.576  7881  7881 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:30.586   790  1361 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7881 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:30.626  7881  7881 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:30.626  7881  7881 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:30.626  7881  7881 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-27 15:04:30.646  7881  7881 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:30.646  7881  7881 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:30.656  7881  7881 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-27 15:04:30.686  7881  7881 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-27 15:04:30.686  7881  7881 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-27 15:04:30.686  7881  7881 D SPPClientService: PushLog.txt file is not deleted.
,07-27 15:04:30.686  7881  7881 D SPPClientService: PushLog.txt file is not deleted.
07-27 15:04:30.686  7881  7881 D SPPClientService: ============PushLog. stop!
,07-27 15:04:30.696  7881  7881 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-27 15:04:30.696  6861  6861 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-27 15:04:30.696   790  1267 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-27 15:04:30.696   790  1267 D ActivityManager: caller:android.app.ApplicationThreadProxy@1dea1f0a, r.packageName :com.sec.spp.push
,07-27 15:04:30.696  6861  6861 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-27 15:04:30.696  6861  6861 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 15:04:30.696  6861  6861 I SA      : [SLFUCHKMGR] constructor called
,07-27 15:04:30.706  7881  7897 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-27 15:04:30.706  6861  6861 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-27 15:04:30.706  6861  6861 I SA      : [OR] == isSIMCardReady false ==
,07-27 15:04:30.706  6861  6861 I SA      : [SCU] == networkStateCheck == false
07-27 15:04:30.706  6861  6861 I SA      : [OR] onReceive END
,07-27 15:04:30.716   790   805 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-27 15:04:30.716   790   805 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.716   790   805 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.716   790   805 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.716   790   805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:30.746   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-27 15:04:30.756  7900  7900 E Zygote  : MountEmulatedStorage()
07-27 15:04:30.756  7900  7900 E Zygote  : v2
07-27 15:04:30.756  7900  7900 I libpersona: KNOX_SDCARD checking this for 10074
07-27 15:04:30.756  7900  7900 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:30.756   790   805 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7900 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 15:04:30.766  7900  7900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:30.766  7900  7900 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:30.766  7900  7900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:30.766   790  3246 I ActivityManager: Killing 7088:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,07-27 15:04:30.776   346   346 I art     : Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 318us total 13.729ms
,07-27 15:04:30.786  7900  7900 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:30.786   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 282us total 9.630ms
,07-27 15:04:30.786  7900  7900 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:30.796   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 281us total 9.525ms
,07-27 15:04:30.796  7900  7900 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-27 15:04:30.846  7900  7900 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-27 15:04:30.846  7900  7900 I SCloudBackupReceiver: Other Intent
,07-27 15:04:30.856  7402  7402 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-27 15:04:30.856  7402  7402 I KnoxUsageLogPro: premStatus:2
,07-27 15:04:30.856  7402  7402 I KnoxUsageLogPro: isEulaShown : false
,07-27 15:04:30.866  7402  7402 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 15:04:30.866   790  1361 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-27 15:04:30.866   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.866   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.866   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:30.866   790  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:30.906  7917  7917 E Zygote  : MountEmulatedStorage()
07-27 15:04:30.906  7917  7917 E Zygote  : v2
07-27 15:04:30.906  7917  7917 I libpersona: KNOX_SDCARD checking this for 10104
07-27 15:04:30.906  7917  7917 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:30.916   790  1361 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7917 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:30.916  7917  7917 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:30.916  7917  7917 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:30.916   790  1361 I ActivityManager: Killing 7107:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
07-27 15:04:30.916  7917  7917 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-27 15:04:30.936  7917  7917 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:30.936  7917  7917 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:30.946  7917  7917 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 15:04:30.996  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-27 15:04:31.016   790  1145 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-27 15:04:31.016   790  1145 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:31.016   790  1145 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:31.016   790  1145 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:31.016   790  1145 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:31.036  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 15:04:31.036  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 15:04:31.036   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7878
07-27 15:04:31.036   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 15:04:31.036  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 15:04:31.036  7878  7878 I wpa_supplicant: ssSupport state is = 1
07-27 15:04:31.036  7878  7878 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:31.036  7878  7878 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:31.036  7878  7878 E wpa_supplicant: SIM READ ERROR
07-27 15:04:31.036  7878  7878 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:31.036  7878  7878 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:31.036  7878  7878 E wpa_supplicant: SIM READ ERROR
07-27 15:04:31.036  7878  7878 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:31.036  7878  7878 I wpa_supplicant: wpa_default_ap_write_once
07-27 15:04:31.036  7878  7878 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 15:04:31.036  7878  7878 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:31.036  7878  7878 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-27 15:04:31.036  7878  7878 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:31.036  7878  7878 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-27 15:04:31.036  7878  7878 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:31.056  7933  7933 E Zygote  : MountEmulatedStorage()
07-27 15:04:31.056  7933  7933 E Zygote  : v2
07-27 15:04:31.056  7933  7933 I libpersona: KNOX_SDCARD checking this for 10146
07-27 15:04:31.056  7933  7933 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:31.066  7933  7933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 15:04:31.066  7933  7933 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:31.066  7933  7933 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 15:04:31.066   790  1145 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7933 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:31.066   790  1145 I ActivityManager: Killing 7133:com.sec.android.app.samsungapps/u0a45 (adj 15): emptyCount ##41
,07-27 15:04:31.086  7933  7933 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:31.086  7933  7933 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:31.106  7933  7933 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 15:04:31.286   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-27 15:04:31.286   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:31.286  7933  7952 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-27 15:04:31.286   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-27 15:04:31.286   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:31.286  7933  7952 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-27 15:04:31.296   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-27 15:04:31.296   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:31.296  7933  7954 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-27 15:04:31.306   265   561 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-27 15:04:31.306   265   561 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 15:04:31.306  7933  7954 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-27 15:04:31.456  7933  7933 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-27 15:04:31.456  7933  7933 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-27 15:04:31.466  7933  7933 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7703-7705)
,07-27 15:04:31.466  7933  7933 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 15:04:31.476  7933  7933 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29b9d71c}
,07-27 15:04:31.476  7933  7933 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 15:04:31.476  7933  7933 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 15:04:31.496  7933  7933 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 15:04:31.496  7933  7933 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 15:04:31.496  7933  7933 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 15:04:31.866   790  1153 E Tethering: No numeric data
,07-27 15:04:31.866   790  1153 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 15:04:31.866   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:31.866   790  1147 V NetworkStats: performPollLocked(flags=0x1)
07-27 15:04:31.866  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:31.866   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
07-27 15:04:31.866   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:31.876  1197  1197 D HotspotTile: updateTetherState():false, false
,07-27 15:04:31.876   790  1147 V NetworkStats: performPollLocked() took 3ms
,07-27 15:04:31.876   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:31.876   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:31.876   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:31.876  7878  7878 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-27 15:04:31.886  7933  7933 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty(),
,07-27 15:04:31.896  7933  7933 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
07-27 15:04:31.896  7933  7933 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-27 15:04:31.896  7933  7933 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 15:04:31.896  7933  7933 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 15:04:31.896  7933  7933 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 15:04:31.896  7933  7933 I Adreno-EGL: Local Branch: mybranch5813579
07-27 15:04:31.896  7933  7933 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 15:04:31.896  7933  7933 I Adreno-EGL: Local Patches: NONE
07-27 15:04:31.896  7933  7933 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-27 15:04:31.916  7878  7878 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-27 15:04:31.916  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 15:04:31.916  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-27 15:04:31.916   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7878
07-27 15:04:31.916   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 15:04:31.916  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 15:04:31.916  7878  7878 I wpa_supplicant: ssSupport state is = 1
,07-27 15:04:31.916  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 15:04:31.916  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-27 15:04:31.916   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7878
07-27 15:04:31.916   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 15:04:31.916  7878  7878 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 15:04:31.916  7878  7878 I wpa_supplicant: ssSupport state is = 1
07-27 15:04:31.916  7878  7878 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-27 15:04:31.916  7878  7878 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:31.916  7878  7878 E wpa_supplicant: SIM READ ERROR
07-27 15:04:31.916  7878  7878 I wpa_supplicant: wpa_default_ap_write_once
07-27 15:04:31.916  7878  7878 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 15:04:31.916  7878  7878 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:31.956  7878  7878 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-27 15:04:31.956  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-27 15:04:31.986  7878  7878 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-27 15:04:31.986  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-27 15:04:31.986  7878  7878 I wpa_supplicant: Skip scan - bUseNetwork false
,07-27 15:04:31.986   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-27 15:04:31.986  7933  7983 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 15:04:31.986   790  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 15:04:31.996  7878  7878 I wpa_supplicant: HOTSPOT20_ENABLE called
07-27 15:04:31.996  7878  7878 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:31.996  7878  7878 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:31.996  7878  7878 E wpa_supplicant: SIM READ ERROR
07-27 15:04:31.996  7878  7878 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:31.996  7933  7933 I NSApplication: Starting up...
,07-27 15:04:32.016   790  1474 I ActivityManager: Killing 7149:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,07-27 15:04:32.016  7878  7878 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 15:04:32.026  7878  7878 I wpa_supplicant: Skip scan - bUseNetwork false
,07-27 15:04:32.026   790  1150 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:32.036   790  1150 D WifiConfigStore: Loading config and enabling all networks 
07-27 15:04:32.036   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:32.036  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:32.036  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:32.036  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:32.036  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:32.036  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:32.036  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:32.036  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:32.036  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:32.036  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-27 15:04:32.036  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 15:04:32.036  1197  1197 D HotspotTile: onReceive : 3, 0
07-27 15:04:32.036  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:32.036  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:32.036  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:32.036  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:32.036   790  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 15:04:32.036   790  1150 E WifiConfigStore: Not a HS20
,07-27 15:04:32.056   790  1150 E WifiConfigStore: Not a HS20
,07-27 15:04:32.056   790  1150 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 15:04:32.056   790  1150 D WifiNative-HAL: callSECApiInt - ID [65]
,07-27 15:04:32.066   790  1150 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-27 15:04:32.066  7878  7878 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 15:04:32.066  7878  7878 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 15:04:32.066  7878  7878 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 15:04:32.066  7878  7878 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 15:04:32.066  7878  7878 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-27 15:04:32.066  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-27 15:04:32.066  7878  7878 I wpa_supplicant: First Scan Start
,07-27 15:04:32.066  7878  7878 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 15:04:32.066   790  1150 D WifiNative-HAL: Setting external_sim to 1
07-27 15:04:32.066  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:32.066   790  1150 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 15:04:32.066   790  1150 I WifiNative-HAL: startHal
07-27 15:04:32.066   790  1150 E wifi    : getStaticLongField sWifiHalHandle 0x931b986c
07-27 15:04:32.066   790  1150 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x50238a
07-27 15:04:32.066   790  1150 I WifiNative-HAL: Could not start hal
,07-27 15:04:32.086   790  1150 E native  : do suspend true
,07-27 15:04:32.096   790  1149 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 15:04:32.096   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-27 15:04:32.096   298  1054 D CommandListener: Setting iface cfg
07-27 15:04:32.096   298  1054 D CommandListener: Trying to bring up p2p0
07-27 15:04:32.096   790   790 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 15:04:32.096   790   790 D RttService: SCAN_AVAILABLE : 3
07-27 15:04:32.096   790  1149 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 15:04:32.096   790  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:32.096   790  1167 I WifiNative-HAL: startHal
07-27 15:04:32.096   790  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9abc199c
07-27 15:04:32.096   790  1167 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x40237a
07-27 15:04:32.096   790  1167 I WifiNative-HAL: Could not start hal
07-27 15:04:32.096   790  1167 E WifiScanningService: could not start HAL
07-27 15:04:32.096   790  1149 D WifiP2pService: P2pEnablingState
07-27 15:04:32.096   790  1168 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:32.096   790  1149 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-27 15:04:32.096   790  1149 D WifiP2pService: P2p socket connection successful
07-27 15:04:32.096   790  1149 D WifiP2pService: P2pEnabledState
,07-27 15:04:32.096   790   790 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-27 15:04:32.096   790  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-27 15:04:32.096   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:32.096   790  1059 D WifiDisplayController: disconnect
07-27 15:04:32.096   790  1059 D WifiDisplayController: updateConnection
07-27 15:04:32.096   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:32.096   790  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-27 15:04:32.096   790  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 15:04:32.096  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 15:04:32.096   790  3246 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 15:04:32.096  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 15:04:32.096   790  1150 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-27 15:04:32.096   790  1150 D WifiNative-HAL: callSECStringApiVoid - ID [215]
,07-27 15:04:32.096   790  1150 E WifiNative-HAL: invaild command id : 215
07-27 15:04:32.096   790  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:32.096   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:32.096   790  1059 D WifiDisplayAdapter: onP2pDisconnected
07-27 15:04:32.096   790  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 15:04:32.096   790  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
07-27 15:04:32.096   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-27 15:04:32.106   790  1704 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-27 15:04:32.106   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.106   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.106   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.106   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:32.126  7878  7878 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 15:04:32.146  7993  7993 E Zygote  : MountEmulatedStorage()
07-27 15:04:32.146  7993  7993 E Zygote  : v2
07-27 15:04:32.146  7993  7993 I libpersona: KNOX_SDCARD checking this for 10158
07-27 15:04:32.146  7993  7993 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:32.156  7878  7878 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 15:04:32.156   790  1149 D WifiNative-HAL: p2pGetDeviceAddress
07-27 15:04:32.156   790  1149 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,07-27 15:04:32.156   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 15:04:32.156   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:32.166  7993  7993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:32.166  7993  7993 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:32.166  7993  7993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:32.166   790  1704 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7993 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 15:04:32.166   790  1149 D WifiP2pService: DeviceAddress: ea:28:a3
07-27 15:04:32.166   790  1059 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-27 15:04:32.166   790  1059 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-27 15:04:32.166   790  1059 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 15:04:32.166   790  1059 D WifiDisplayController:  secondary type: null
07-27 15:04:32.166   790  1059 D WifiDisplayController:  wps: 0
07-27 15:04:32.166   790  1059 D WifiDisplayController:  grpcapab: 0
07-27 15:04:32.166   790  1059 D WifiDisplayController:  devcapab: 0
07-27 15:04:32.166   790  1059 D WifiDisplayController:  status: 3
07-27 15:04:32.166   790  1059 D WifiDisplayController:  wfdInfo: null
07-27 15:04:32.166   790  1059 D WifiDisplayController:  groupownerAddress: null
07-27 15:04:32.166   790  1059 D WifiDisplayController:  GOdeviceName: null
07-27 15:04:32.166   790  1059 D WifiDisplayController:  interfaceAddress: 
07-27 15:04:32.166   790  1059 D WifiDisplayController:  SConnectInfo : null
,07-27 15:04:32.166   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:32.166   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:32.186  7993  7993 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:32.186  7993  7993 D ActivityThread: Added TimaKeyStore provider
07-27 15:04:32.186   790  1149 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-27 15:04:32.186   790  1149 D WifiP2pService: InactiveState
07-27 15:04:32.186   790  1149 D WifiP2pService: InactiveState{ what=143376 }
07-27 15:04:32.186   790  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 15:04:32.186  7878  7878 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 15:04:32.186   790  1149 D WifiP2pService: InactiveState{ what=143376 }
07-27 15:04:32.186   790  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 15:04:32.196  7993  7993 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-27 15:04:32.196  7993  7993 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 15:04:32.196  7993  7993 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-27 15:04:32.196  7993  7993 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 15:04:32.206  7993  7993 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:32.216  7993  7993 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-27 15:04:32.216  7993  7993 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-27 15:04:32.216   790  1648 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
07-27 15:04:32.216   790  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.216   790  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.216   790  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.216   790  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:32.256  8008  8008 E Zygote  : MountEmulatedStorage()
07-27 15:04:32.256  8008  8008 E Zygote  : v2
07-27 15:04:32.256  8008  8008 I libpersona: KNOX_SDCARD checking this for 10186
07-27 15:04:32.256  8008  8008 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:32.266   790  1648 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8008 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-27 15:04:32.266  8008  8008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:32.266  8008  8008 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:32.266   790  1648 I ActivityManager: Killing 6882:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-27 15:04:32.266  8008  8008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:32.286  8008  8008 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:32.286  8008  8008 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:32.296  8008  8008 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-27 15:04:32.306  8008  8008 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-27 15:04:32.306  8008  8008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:32.306  8008  8008 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-27 15:04:32.306  8008  8008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 15:04:32.306  8008  8008 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 15:04:32.316   790  1576 D CountryDetector: No listener is left
,07-27 15:04:32.386   790  1264 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:32.416   790  1474 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:32.426   790  1377 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:32.456   790  3246 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-27 15:04:32.456   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.456   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.456   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.456   790  3246 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:32.466   790  1361 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:32.476   790  1648 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:32.486   790   805 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:32.496  8031  8031 E Zygote  : MountEmulatedStorage()
07-27 15:04:32.496  8031  8031 E Zygote  : v2
07-27 15:04:32.496  8031  8031 I libpersona: KNOX_SDCARD checking this for 10092
07-27 15:04:32.496  8031  8031 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:32.506   790  3246 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8031 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-27 15:04:32.536  8031  8031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:32.536  8031  8031 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:32.536   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:32.536  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:32.536  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:32.536  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:32.536  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-27 15:04:32.536  8031  8031 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-27 15:04:32.536   790  1264 I ActivityManager: Killing 7206:com.samsung.android.scloud.sync/u0a76 (adj 15): emptyCount ##41
,07-27 15:04:32.536   790  1474 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:32.536   790  1145 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:32.536   790  1264 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,07-27 15:04:32.536   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.536   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.536   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:32.536   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:32.556  8031  8031 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:32.556  8031  8031 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:32.586  8046  8046 E Zygote  : MountEmulatedStorage()
07-27 15:04:32.586  8046  8046 E Zygote  : v2
07-27 15:04:32.586  8046  8046 I libpersona: KNOX_SDCARD checking this for 10200
07-27 15:04:32.586  8046  8046 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:32.596   790  1264 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8046 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:32.606  8046  8046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:32.606  8046  8046 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:32.606  8046  8046 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 15:04:32.606   790  1635 I ActivityManager: Killing 7222:com.sec.android.app.clockpackage/u0a106 (adj 15): emptyCount ##41
,07-27 15:04:32.626  8046  8046 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:32.626  8046  8046 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:32.696   790  1474 I art     : Explicit concurrent mark sweep GC freed 40789(2MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.292ms total 90.081ms
,07-27 15:04:32.706  8031  8031 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-27 15:04:32.716  8046  8046 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-27 15:04:32.716  8031  8031 D BadgeProvider: onCreate
,07-27 15:04:32.716  8031  8031 D BadgeProvider: DatabaseHelper
,07-27 15:04:32.726   790  1377 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-27 15:04:32.736   790  1704 I ActivityManager: Killing 7237:com.sec.esdk.elm/u0a116 (adj 15): emptyCount ##41
,07-27 15:04:32.736  8031  8039 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-27 15:04:32.736   790  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:32.736   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d5fcad3, r.packageName :com.google.android.gms
,07-27 15:04:32.746  4446  4446 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-27 15:04:32.746  4446  5430 I iu.UploadsManager: num queued entries: 0
,07-27 15:04:32.746  4446  5430 I iu.UploadsManager: num updated entries: 0
,07-27 15:04:32.746  4446  5430 I iu.SyncManager: NEXT; no task
07-27 15:04:32.746   790  1458 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,07-27 15:04:32.746   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.746   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.746   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:32.746   790  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:32.756  1443  1443 D Launcher.Model: reloadBadges entered.
,07-27 15:04:32.756  8031  8039 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-27 15:04:32.756  8031  8039 D BadgeProvider: sendNotify, [notify] : null
,07-27 15:04:32.756  8031  8039 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-27 15:04:32.756  8031  8039 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-27 15:04:32.756  8031  8039 D BadgeProvider: update, [UpdateCount] : 1
,07-27 15:04:32.786  8063  8063 E Zygote  : MountEmulatedStorage()
,07-27 15:04:32.786  8063  8063 E Zygote  : v2
07-27 15:04:32.786  8063  8063 I libpersona: KNOX_SDCARD checking this for 10045
07-27 15:04:32.786  8063  8063 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:32.796  8063  8063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:32.796  8063  8063 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:32.796   790  1344 E Watchdog: !@Sync 5
,07-27 15:04:32.796  8063  8063 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-27 15:04:32.796   790  1458 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=8063 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 15:04:32.816  8063  8063 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:32.816  8063  8063 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:32.826  8063  8063 D ResourcesManager: creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,07-27 15:04:32.856  7878  7878 I wpa_supplicant: nl80211: Received scan results (36 BSSes)
07-27 15:04:32.856  7878  7878 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 15:04:32.856  7878  7878 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-27 15:04:32.856  7878  7878 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,07-27 15:04:32.856  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-27 15:04:32.876   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:32.876   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:32.876   790  1686 I ActivityManager: Killing 7288:com.qualcomm.timeservice/1000 (adj 15): emptyCount ##41
,07-27 15:04:32.886  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:32.886   790  1704 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:32.886  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:32.886  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:32.886  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:32.886  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:32.896  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:32.896   790  1576 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:32.896  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-27 15:04:32.896  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:32.896  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:32.896  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:32.906  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 15:04:32.906  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:32.906  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:32.906   790  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:32.906  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:32.906   790  1648 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:32.906  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:32.906  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:32.906  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:32.906  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:32.906  7387  7387 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 15:04:32.916  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 15:04:32.916  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-27 15:04:32.916  7744  7744 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 15:04:32.916  7744  7744 D WifiDirectBR: stopServiceTest : false
,07-27 15:04:32.926  7878  7878 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-27 15:04:32.926  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-27 15:04:32.936  7878  7878 I wpa_supplicant: Associated with F4.99.3E
07-27 15:04:32.936  7878  7878 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-27 15:04:32.936  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-27 15:04:32.936   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:32.936   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:32.936   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:32.936   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:32.946  7878  7878 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-27 15:04:32.946  7878  7878 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-27 15:04:32.946  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-27 15:04:32.946  7878  7878 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:32.946  7878  7878 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-27 15:04:32.946  7878  7878 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,07-27 15:04:32.946  7878  7878 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 15:04:32.946  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-27 15:04:32.956   790  1150 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-27 15:04:32.956  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:32.956  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:32.956   790  1150 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-27 15:04:32.956   790  1152 D ConnectivityService: Got NetworkAgent Messenger
07-27 15:04:32.956   790  1152 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-27 15:04:32.956   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:32.956   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:32.956   790  1152 D ConnectivityService: NetworkAgent connected
07-27 15:04:32.956   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:32.956  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 15:04:32.956  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 15:04:32.966   790  1267 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:32.966  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:32.966   790  1686 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:32.966  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,07-27 15:04:32.966  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:32.966  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:32.966  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:32.966   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:32.966  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:32.966   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:32.976   298  1054 D CommandListener: Setting iface cfg
,07-27 15:04:32.976   790  1150 E WifiStateMachine: Start Dhcp Watchdog 2
,07-27 15:04:32.986   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:32.986   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:32.986  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:32.986  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:32.986   790  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-27 15:04:33.016   303   303 E SMD     : DCD ON
,07-27 15:04:33.066   790  1150 E native  : do suspend false
,07-27 15:04:33.076   790  1149 D WifiP2pService: InactiveState{ what=143375 }
,07-27 15:04:33.076   790  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
07-27 15:04:33.076   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:33.076   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:33.146   790  3089 D SSRM:n  : SIOP:: AP = 400, PST = 371, CUR = 450
,07-27 15:04:33.296  8083  8083 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 15:04:33.296  8083  8083 I dhcpcd  : version 5.5.6 starting
,07-27 15:04:33.296  8083  8083 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 15:04:33.336  1834  2521 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 15:04:33.386  8083  8083 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 15:04:33.386  8083  8083 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-27 15:04:33.386  8083  8083 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-27 15:04:33.386  8083  8083 I dhcpcd  : bssid match
07-27 15:04:33.386  8083  8083 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-27 15:04:33.396  8083  8083 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-27 15:04:33.406  8083  8083 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-27 15:04:33.406   790  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-27 15:04:33.426  7530  7607 I WifiManager: packageName : com.test.thalitest
07-27 15:04:33.426   790  1377 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 15:04:33.426   790  1377 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 15:04:33.426   790  1377 D SecContentProvider2: mCursor = null
,07-27 15:04:33.426   790  1377 D WifiService: setWifiEnabled: false pid=7530, uid=10079
,07-27 15:04:33.426   790  1377 D SettingsProvider: name = wifi_on
,07-27 15:04:33.436   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:33.446   790  1150 E native  : do suspend true
,07-27 15:04:33.456   790  1149 D WifiP2pService: InactiveState{ what=143375 }
07-27 15:04:33.456   790  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 15:04:33.466   298  1054 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:33.466  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:33.466  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:33.496   790  1152 E ConnectivityService: updateNetworkInfo()
,07-27 15:04:33.496   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:33.496   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
07-27 15:04:33.496   298  1054 E Netd    : no such netId 503
,07-27 15:04:33.496   790  1152 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
07-27 15:04:33.496   790  1152 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
07-27 15:04:33.496   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:33.496   790  1152 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-27 15:04:33.506   790  8080 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:33.506   790  8080 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 15:04:33.506   790  1152 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-27 15:04:33.506   790  1152 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-27 15:04:33.506   790   790 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 15:04:33.506  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:33.506  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:33.506   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:33.516  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 15:04:33.516  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:33.516   790   806 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.516  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 15:04:33.516   790  3246 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.516  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:33.516  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:33.516  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:33.516  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:33.526   790  1149 D WifiP2pService: InactiveState{ what=131204 }
,07-27 15:04:33.526   790  1149 D WifiP2pService: P2pEnabledState{ what=131204 }
07-27 15:04:33.526   790   790 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 15:04:33.526   790   790 D RttService: SCAN_AVAILABLE : 1
07-27 15:04:33.526   790  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:33.526   790  1168 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 15:04:33.526   790  1149 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-27 15:04:33.526   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:33.526   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-27 15:04:33.526   790  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.526   790  1059 D WifiDisplayAdapter: onP2pDisconnected
07-27 15:04:33.526   790  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 15:04:33.526   790  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 15:04:33.526   790  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-27 15:04:33.526   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:33.526   790  1059 D WifiDisplayController: disconnect
07-27 15:04:33.526   790  1059 D WifiDisplayController: updateConnection
07-27 15:04:33.526   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:33.526   790  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 15:04:33.526   790   790 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-27 15:04:33.526   790  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-27 15:04:33.526   790  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:33.526  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 15:04:33.526   790  1150 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-27 15:04:33.526   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:33.526   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-27 15:04:33.526   790  1149 D WifiP2pService: P2pDisablingState
07-27 15:04:33.526   790  1149 D WifiP2pService: P2pDisablingState{ what=147458 }
07-27 15:04:33.526   790  1149 D WifiP2pService: p2p socket connection lost
,07-27 15:04:33.526   790  1149 D WifiP2pService: P2pDisabledState
07-27 15:04:33.526   790  1361 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 15:04:33.526   790  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.526   790  1059 D WifiDisplayAdapter: onP2pDisconnected
07-27 15:04:33.526   790  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 15:04:33.526   790  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
07-27 15:04:33.526  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 15:04:33.536  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:33.536   790  1150 E native  : do suspend true
,07-27 15:04:33.536   790  1149 D WifiP2pService: P2pDisabledState{ what=143375 }
07-27 15:04:33.536   790  1149 D WifiP2pService: DefaultState{ what=143375 }
,07-27 15:04:33.536  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:33.546  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 15:04:33.546   790  1648 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.546  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:33.546   790  1635 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.546  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:33.546  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-27 15:04:33.546  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:33.546  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:33.546   298  1054 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:33.546  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:33.546  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:33.546  7878  7878 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-27 15:04:33.546   790   790 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 15:04:33.556   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:33.556  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:33.556  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 15:04:33.556  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:33.556  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:33.556  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-27 15:04:33.556   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:33.556   790  1150 D SecContentProvider2: mCursor = null
07-27 15:04:33.556  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:33.556   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 15:04:33.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:33.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:33.556  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:33.556  7387  7387 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 15:04:33.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:33.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:33.556  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 15:04:33.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 15:04:33.556  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:33.556  1197  1197 D HotspotTile: onReceive : 0, 0
,07-27 15:04:33.556  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:33.566  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:33.566  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-27 15:04:33.566  7744  7744 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 15:04:33.566  7744  7744 D WifiDirectBR: stopServiceTest : false
,07-27 15:04:33.566  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 15:04:33.576  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 15:04:33.576  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:33.576   790   805 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.576  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 15:04:33.576   790  1264 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.576  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,07-27 15:04:33.576  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:33.576  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:33.576  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:33.586   790  1686 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:33.586  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:33.596  7878  7878 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:33.596  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:33.596   790  1474 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:33.596  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:33.596  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:33.596  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:33.596  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:33.636  7878  7878 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-27 15:04:33.636  7878  7878 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,07-27 15:04:33.636  7878  7878 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-27 15:04:33.636  7878  7878 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-27 15:04:33.636  7878  7878 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-27 15:04:33.686  7878  7878 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:33.816  7878  7878 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 15:04:33.816   790  1153 D Tethering: InitialState.processMessage what=4
,07-27 15:04:33.816   790  1153 E Tethering: No numeric data
,07-27 15:04:33.816   790  1153 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-27 15:04:33.816  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:33.816   790  1147 V NetworkStats: performPollLocked(flags=0x1)
07-27 15:04:33.816   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:33.816  1197  1197 D HotspotTile: updateTetherState():false, false
,07-27 15:04:33.816   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
07-27 15:04:33.816   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:33.816   790  1147 V NetworkStats: performPollLocked() took 2ms
,07-27 15:04:33.816   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:33.816   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:33.816   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:33.916   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-27 15:04:33.916   790  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 15:04:33.916   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:33.916  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:33.916  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:33.916  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-27 15:04:33.916  1834  2327 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:33.916   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 15:04:33.916  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:33.916  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,07-27 15:04:33.926  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:33.926  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 15:04:33.926  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:33.926  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:33.926  1197  1197 D HotspotTile: onReceive : 1, 0
,07-27 15:04:33.926  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:33.926  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:33.926   790  1266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:33.926  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:33.936  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:33.936  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:33.936  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:34.116   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-27 15:04:34.176   790   806 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 15:04:34.176   790   806 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 15:04:34.176   790   806 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 15:04:34.176   790   806 D BatteryService: stay LED for fully charged
07-27 15:04:34.176   790   790 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 15:04:34.176   790   790 I MotionRecognitionService: Plugged
07-27 15:04:34.176   790   790 I MotionRecognitionService: setPowerConnected  = true
,07-27 15:04:34.176  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 15:04:34.176  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 15:04:34.186  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-27 15:04:34.186  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:34.186  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 15:04:34.186  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:34.236   790  1267 I ActivityManager: Killing 7256:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,07-27 15:04:34.826   790  1635 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-27 15:04:34.826   790  1635 D ActivityManager: caller:android.app.ApplicationThreadProxy@3bbebd35, r.packageName :com.google.android.music
,07-27 15:04:34.846   790   806 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:34.846   790  1264 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:34.846   790  1458 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:34.866   790  1377 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-27 15:04:34.866   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@10332eb3, r.packageName :com.google.android.music
,07-27 15:04:34.886  1834  1834 D WearableService: callingUid 10015, callindPid: 1834
,07-27 15:04:34.896   790  1686 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 15:04:34.926  7798  7798 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-27 15:04:34.926  7798  8130 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-27 15:04:34.976  7798  8125 I MusicLeanback: Conditions not met for autocaching.
,07-27 15:04:34.976  7798  8125 I MusicLeanback: Stop autocaching.
,07-27 15:04:36.016   303   303 E SMD     : DCD ON,
,07-27 15:04:36.306   790  1576 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-27 15:04:36.316  7933  7953 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-27 15:04:36.446  7530  7607 D BluetoothAdapter: enable()
,07-27 15:04:36.446   790  3246 W ActivityManager: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-27 15:04:36.446   790  3246 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 15:04:36.446   790  3246 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:36.446   790  3246 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 15:04:36.446   790  3246 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-27 15:04:36.446   790  3246 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-27 15:04:36.446   790  3246 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-27 15:04:36.446   790  3246 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-27 15:04:36.446   790  3246 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:36.446   790  3246 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:36.446   790  3246 D SettingsProvider: name = bluetooth_on
,07-27 15:04:36.466   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:36.466   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:36.466   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-27 15:04:36.496  7763  7763 D BluetoothAdapterState: make
,07-27 15:04:36.506  7763  7763 I bluedroid: init
,07-27 15:04:36.506  7763  8143 I BluetoothAdapterState: Entering OffState
,07-27 15:04:36.506  7763  7763 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 15:04:36.506  7763  7763 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 15:04:36.506  7763  7763 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 15:04:36.506  7763  7763 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-27 15:04:36.506  7763  7763 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-27 15:04:36.506  7763  7763 I bluedroid: get_profile_interface socket
,07-27 15:04:36.506  7763  7763 I bluedroid: get_profile_interface map_client
,07-27 15:04:36.516  7763  7763 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-27 15:04:36.516  7763  8146 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-27 15:04:36.516  7763  8146 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-27 15:04:36.526   790  1267 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:36.526  7763  7772 I bluedroid: config_hci_snoop_log
,07-27 15:04:36.526   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-27 15:04:36.526   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:36.526   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:36.536   790  1058 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-27 15:04:36.536  7763  8143 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-27 15:04:36.536  7763  8146 E BluetoothServiceJni: populateRssiValuesNative
07-27 15:04:36.536  7763  8146 I bluedroid: getModelRssiValues
07-27 15:04:36.536  7763  8146 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-27 15:04:36.536  7763  8146 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 15:04:36.536   790   790 D SettingsProvider: name = bluetooth_name
,07-27 15:04:36.536  7763  8146 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 15:04:36.536  7763  8143 D BluetoothAdapterProperties: Setting state to 11
07-27 15:04:36.536  7763  8143 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-27 15:04:36.536  7763  8143 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:36.536  7763  8143 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 15:04:36.536   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:36.546   790   790 I InputMethodManagerService: [BT Setting State] State =11
,07-27 15:04:36.546  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:36.546  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 15:04:36.546  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:36.546  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:36.556  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:36.556   790   805 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 15:04:36.556  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 15:04:36.556   790  1264 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 15:04:36.556  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 15:04:36.556  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:36.556  1739  1739 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 15:04:36.556   790  1576 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:36.556   790  1576 D ActivityManager: caller:android.app.ApplicationThreadProxy@14fa2291, r.packageName :com.google.android.gms
,07-27 15:04:36.556  7763  8143 D BluetoothAdapterService: Autoconnection is available 
,07-27 15:04:36.566  7763  8143 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-27 15:04:36.576  7763  8143 D BluetoothSecureManager: getInstant: null
,07-27 15:04:36.576  7763  8143 D BluetoothSecureManager: calling getMethod for getService
07-27 15:04:36.576  7763  8143 D BluetoothSecureManager: calling getService
,07-27 15:04:36.576  7763  8143 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@345bb806
,07-27 15:04:36.576   790  1361 D BluetoothSecureManagerService: isSecureModeEnabled
07-27 15:04:36.576   790  1361 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-27 15:04:36.576  7763  8143 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 15:04:36.576  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-27 15:04:36.576  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 15:04:36.576  7763  8143 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 15:04:36.586  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:36.586  7763  8143 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 15:04:36.586  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-27 15:04:36.586  7763  8143 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,07-27 15:04:36.586  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-27 15:04:36.586  7763  8143 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-27 15:04:36.596  7763  8143 D BluetoothBondStateMachine: make
,07-27 15:04:36.596  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-27 15:04:36.606  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 15:04:36.606  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-27 15:04:36.606  7763  8154 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 15:04:36.606   790  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:36.606   790  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@29017df7, r.packageName :com.android.bluetooth
,07-27 15:04:36.606  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:36.606  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 15:04:36.606  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:36.606   790  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:36.606   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f8d56cd, r.packageName :com.android.bluetooth
07-27 15:04:36.606  7763  7763 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-27 15:04:36.606  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,07-27 15:04:36.606  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 15:04:36.606  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-27 15:04:36.606   790  1377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:36.606   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@22c60293, r.packageName :com.android.bluetooth
,07-27 15:04:36.616  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 15:04:36.616  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 15:04:36.616  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-27 15:04:36.616   790  3246 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:36.616   790  3246 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ba592c9, r.packageName :com.android.bluetooth
07-27 15:04:36.616  7763  7763 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 15:04:36.616  7763  7763 D BtGatt.GattService: Received start request. Starting profile...
07-27 15:04:36.616  7763  7763 D BtGatt.GattService: start()
07-27 15:04:36.616  7763  7763 I bluedroid: get_profile_interface gatt
,07-27 15:04:36.616  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:36.616  7763  7763 D BtGatt.AdvertiseManager: advertise manager created
,07-27 15:04:36.616  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 15:04:36.616  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 15:04:36.616  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-27 15:04:36.616   790  1361 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:36.616   790  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a4434ef, r.packageName :com.android.bluetooth
,07-27 15:04:36.626  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 15:04:36.626  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 15:04:36.626  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-27 15:04:36.626   790  1361 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:36.626   790  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e1d6be8, r.packageName :com.android.bluetooth
,07-27 15:04:36.636  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:36.636  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 15:04:36.636  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:36.636  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-27 15:04:36.636   790  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:36.636   790  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@9a6e8a6, r.packageName :com.android.bluetooth
,07-27 15:04:36.636  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 15:04:36.636  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-27 15:04:36.636  7763  8143 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-27 15:04:36.636  7763  7763 D HeadsetService: Received start request. Starting profile...
,07-27 15:04:36.636   790  1635 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:36.636   790  1635 D ActivityManager: caller:android.app.ApplicationThreadProxy@36515e94, r.packageName :com.android.bluetooth
,07-27 15:04:36.636  7763  7763 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 15:04:36.636  7763  7763 D HeadsetStateMachine: make
,07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 15:04:36.646  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:36.646  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 15:04:36.646  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,07-27 15:04:36.646  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 15:04:36.646  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 15:04:36.646  7763  8143 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 15:04:36.646  7763  7763 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 15:04:36.666   790  1264 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-27 15:04:36.666   790  3246 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-27 15:04:36.666  7763  7763 I bluedroid: get_profile_interface handsfree
,07-27 15:04:36.676  7763  7763 I DualScoManager: Instantiating Dual Sco Manager
07-27 15:04:36.676  7763  7763 I DualScoManager: Set HeadsetServiceHelper
,07-27 15:04:36.676  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:36.676  7763  7763 D BluetoothAtMessage: createCMTIContentObservers
,07-27 15:04:36.676   790  1635 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,07-27 15:04:36.676   790  1635 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:36.676   790  1635 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:36.676   790  1635 D SettingsProvider: selectionArgs: false
07-27 15:04:36.676   790  1635 D SettingsProvider: selectionArgs: 1002
,07-27 15:04:36.676   790  1635 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:36.676   790  1635 D SettingsProvider: ret = -1
,07-27 15:04:36.676  7763  8168 D HeadsetStateMachine: Enter Disconnected: -2
,07-27 15:04:36.676  7763  8168 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-27 15:04:36.676  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:36.686  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:36.686  7763  7763 D A2dpService: Received start request. Starting profile...
,07-27 15:04:36.686  7763  7763 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-27 15:04:36.686  7763  7763 V Avrcp   : make
07-27 15:04:36.686  7763  7763 V Avrcp   : Avrcp
,07-27 15:04:36.686  7763  7763 I bluedroid: get_profile_interface avrcp
,07-27 15:04:36.686  7763  8168 D HeadsetStateMachine: map size, before remove : 0
07-27 15:04:36.686  7763  8168 D HeadsetStateMachine: map size, after remove: 0
,07-27 15:04:36.686  7763  7763 V Avrcp   : start
,07-27 15:04:36.686  7763  8168 D HeadsetStateMachine: mNextConnectingDevice : null
,07-27 15:04:36.696  7763  7763 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 15:04:36.696  7763  7763 V Avrcp   : ++registerMediaPlayers++
,07-27 15:04:36.696  7763  7763 I Avrcp   : No of Audio players :: 2
,07-27 15:04:36.696  7763  7763 I Avrcp   : App Package name is com.google.android.music
,07-27 15:04:36.696  7763  7763 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 15:04:36.706  7763  7763 I Avrcp   : App pkg name is Google Play Music
,07-27 15:04:36.706  7763  7763 I Avrcp   : Name::Google Play Music
,07-27 15:04:36.706  7763  7763 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 15:04:36.706  7763  7763 I Avrcp   : App Package name is com.sec.android.app.music
07-27 15:04:36.706  7763  7763 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-27 15:04:36.706  7763  7763 I Avrcp   : App pkg name is Music
,07-27 15:04:36.706  7763  7763 I Avrcp   : Name::Music
07-27 15:04:36.706  7763  7763 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-27 15:04:36.706  7763  7763 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-27 15:04:36.706  7763  7763 I Avrcp   : No of Video players :: 1
07-27 15:04:36.706  7763  7763 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-27 15:04:36.706  7763  7763 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-27 15:04:36.706  7763  7763 I Avrcp   : Video App pkg name is Video Player
,07-27 15:04:36.706  7763  7763 I Avrcp   : Name::Video Player
07-27 15:04:36.706  7763  7763 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-27 15:04:36.706  7763  7763 I Avrcp   : Add tempPlayer
07-27 15:04:36.706  7763  7763 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 15:04:36.716  7763  7763 I Avrcp   : Total no of players: 4
07-27 15:04:36.716  7763  7763 V Avrcp   : swapping the samsung player with 1st player
07-27 15:04:36.716  7763  7763 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-27 15:04:36.716  7763  8172 V Avrcp   : handleMessage, msg=207
,07-27 15:04:36.716  7763  8172 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
07-27 15:04:36.716  7763  7763 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-27 15:04:36.716  7763  7763 D A2dpStateMachine: make
,07-27 15:04:36.716  7763  7763 I bluedroid: get_profile_interface a2dp
,07-27 15:04:36.716  7763  8174 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 15:04:36.716  7763  7763 E bt-btif : warning : media task started media_task_refcnt 1 
,07-27 15:04:36.716  7763  8172 D BluetoothMediaBrowser: no now playing list
,07-27 15:04:36.716  7763  8172 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-27 15:04:36.716  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:36.716  7763  8173 D A2dpStateMachine: Enter Disconnected: -2
07-27 15:04:36.716  7763  8172 D Avrcp   :  checkNowPlayingList start
,07-27 15:04:36.716  7763  7763 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 15:04:36.726  7763  7763 D HidService: Received start request. Starting profile...
07-27 15:04:36.726  7763  7763 I bluedroid: get_profile_interface hidhost
,07-27 15:04:36.726  7763  7763 D HidService: setHidService(): set to: null
07-27 15:04:36.726  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:36.726  7763  7763 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 15:04:36.726  7763  7763 D HealthService: Received start request. Starting profile...
,07-27 15:04:36.726  7763  7763 I bluedroid: get_profile_interface health
,07-27 15:04:36.726  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:36.726  7763  7763 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 15:04:36.726  7763  7763 D PanService: Received start request. Starting profile...
07-27 15:04:36.726  7763  7763 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 15:04:36.726  7763  7763 I bluedroid: get_profile_interface pan
,07-27 15:04:36.726  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:36.726  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-27 15:04:36.736  7763  7763 D BluetoothMapService: Received start request. Starting profile...
,07-27 15:04:36.756  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:36.756  7763  7763 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-27 15:04:36.766  7763  7763 D SapService: Received start request. Starting profile...
07-27 15:04:36.766  7763  7763 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-27 15:04:36.766  7763  7763 I bluedroid: get_profile_interface sap
07-27 15:04:36.766  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:36.766  7763  7763 D HeadsetStateMachine: Try to query the phonestate on bind
,07-27 15:04:36.766  1407  1419 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 15:04:36.766  1407  1407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-27 15:04:36.766  7763  7763 D HeadsetStateMachine: Proxy object connected
,07-27 15:04:36.766  7763  7763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-27 15:04:36.766  7763  7763 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-27 15:04:36.766  7763  8168 D HeadsetStateMachine: Disconnected process message: 11
07-27 15:04:36.766  7763  7763 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-27 15:04:36.766  7763  8168 D HeadsetStateMachine: Disconnected process message: 18
07-27 15:04:36.766  7763  7763 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 15:04:36.766  7763  7763 D BluetoothA2dp: Proxy object connected
07-27 15:04:36.766  7763  7763 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-27 15:04:36.766  7763  8168 D HeadsetStateMachine: Disconnected process message: 10
07-27 15:04:36.766  7763  8168 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 15:04:36.766  7763  8168 D HeadsetStateMachine: Disconnected process message: 11
,07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-27 15:04:36.766  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-27 15:04:36.776  7763  8143 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-27 15:04:36.776  7763  8143 I bluedroid: enable
,07-27 15:04:36.776  7763  8178 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 15:04:36.776  7763  8143 I bt_hci_bdroid: init
,07-27 15:04:36.776  7763  8143 I bt_vendor: init
07-27 15:04:36.776  7763  8143 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 15:04:36.776  7763  8143 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 15:04:36.776  7763  8143 D bt_userial: userial_init
07-27 15:04:36.776  7763  8143 D bt_vendor: op for 5
,07-27 15:04:36.776  7763  8143 D bt_vendor: op for 0
,07-27 15:04:36.776  7763  8143 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 15:04:36.776  7763  8143 D bt_upio : is_emulator_context : 0
07-27 15:04:36.776  7763  8143 D bt_upio : is_rfkill_disabled ? [0]
07-27 15:04:36.776  7763  8143 D bt_upio : is_rfkill_disabled ? [0]
,07-27 15:04:36.776  7763  8143 D bt_vendor: op for 0
07-27 15:04:36.776  7763  8143 D bt_upio : upio_set_bluetooth_power(on: 1)
07-27 15:04:36.776  7763  8143 D bt_upio : is_emulator_context : 0
07-27 15:04:36.776  7763  8143 D bt_upio : is_rfkill_disabled ? [0]
,07-27 15:04:36.776  7763  8180 D bt_vendor: op for 3
07-27 15:04:36.776  7763  8180 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 15:04:36.776  7763  8180 I bt_userial_vendor: userial_vendor_open():UART is setup
07-27 15:04:36.776  7763  8180 I bt_userial_vendor: device fd = 66 open
,07-27 15:04:36.776  7763  8180 D bt_vendor: op for 1
07-27 15:04:36.776  7763  8180 E bt_hwcfg: Start CFG HW, HCI reset
07-27 15:04:36.776  7763  8181 D bt_userial: Entering userial_read_thread()
,07-27 15:04:36.856  7763  8180 E bt_hwcfg: Read Local Name after HCI reset
,07-27 15:04:36.886  7763  8180 D bt_hwcfg: Chipset BCM4335C0
07-27 15:04:36.886  7763  8180 D bt_hwcfg: Target name = [BCM4335C0]
,07-27 15:04:36.886  7763  8180 I bt_hwcfg: module_type[semco].
07-27 15:04:36.886  7763  8180 I bt_hwcfg: not ZERO...
07-27 15:04:36.886  7763  8180 I bt_hwcfg: module_type[semco] is invalid.
,07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG . BCM4335C0
,07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-27 15:04:36.886  7763  8180 E bt_hwcfg: fw ver (org)0.0
,07-27 15:04:36.886  7763  8180 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-27 15:04:36.886  7763  8180 E bt_hwcfg: Remove module rev, try again BCM4335
07-27 15:04:36.886  7763  8180 D bt_hwcfg: Target name = [BCM4335]
07-27 15:04:36.886  7763  8180 I bt_hwcfg: module_type[semco].
07-27 15:04:36.886  7763  8180 I bt_hwcfg: not ZERO...
07-27 15:04:36.886  7763  8180 I bt_hwcfg: module_type[semco] is invalid.
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG . BCM4335
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG .. BCM4335
,07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
,07-27 15:04:36.886  7763  8180 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-27 15:04:36.886  7763  8180 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-27 15:04:36.886  7763  8180 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-27 15:04:36.886  7763  8180 E bt_hwcfg: ORG patchram base 0111
07-27 15:04:36.886  7763  8180 E bt_hwcfg: ORG patchram minor 0559
07-27 15:04:36.886  7763  8180 E bt_hwcfg: fw ver (org)111.559
07-27 15:04:36.886  7763  8180 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-27 15:04:36.906  7763  8180 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 15:04:36.916  7763  8180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 15:04:37.326  7763  8180 I bt_hwcfg: bt vendor lib: set UART baud 115200,
07-27 15:04:37.326  7763  8180 I bt_hwcfg: FW Download delta = 471118
07-27 15:04:37.326  7763  8180 D bt_hwcfg: Settlement delay -- 100 ms
07-27 15:04:37.326  7763  8180 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 15:04:37.446  7763  8180 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,07-27 15:04:37.466  7763  8180 I bt_hwcfg: vendor lib fwcfg completed,
,07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_PAN
,07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_SAP
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 15:04:37.476  7763  8178 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-27 15:04:37.696  7763  8178 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-27 15:04:37.696  7763  8178 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xaf718b5d 
,07-27 15:04:37.696  7763  8178 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf718b5d 
,07-27 15:04:37.926  7763  8146 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-27 15:04:37.926  7763  8146 E bt-btif : Calling BTA_HhEnable
,07-27 15:04:37.926  7763  8146 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-27 15:04:37.926  7763  8146 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
07-27 15:04:37.926  7763  8146 E BluetoothServiceJni: populateRssiValuesNative
07-27 15:04:37.926  7763  8146 I bluedroid: getModelRssiValues
07-27 15:04:37.926  7763  8146 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-27 15:04:37.926  7763  8146 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 15:04:37.936  7763  8146 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 15:04:37.936   790   790 D SettingsProvider: name = bluetooth_name
,07-27 15:04:37.936  7763  8146 D BluetoothAdapterProperties: Scan Mode:20
,07-27 15:04:37.936  7763  8146 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 15:04:37.936  7763  8146 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
07-27 15:04:37.936  7763  8146 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-27 15:04:37.936  7763  8146 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-27 15:04:37.936  7763  8146 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-27 15:04:37.936  7763  8146 E bt-btif : btif_sock_init: !vhci_init
,07-27 15:04:37.936  7763  8146 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-27 15:04:37.936  7763  8146 D IOP_DB_BT: db_open: db_open : handle 3025616912l, read 14063 bytes onto local cache
,07-27 15:04:37.936  7763  8146 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-27 15:04:37.936  7763  8146 D IOP_DB_BT: db_query: result 1
,07-27 15:04:37.936  7763  8146 I         : iop_db_open: iop_db_open status 0
07-27 15:04:37.936  7763  8146 D bte_conf: Device ID record 1 : primary
,07-27 15:04:37.936  7763  8146 D bte_conf:   vendorId            = 0075
07-27 15:04:37.936  7763  8146 D bte_conf:   vendorIdSource      = 0001
07-27 15:04:37.936  7763  8146 D bte_conf:   product             = 0100
07-27 15:04:37.936  7763  8146 D bte_conf:   version             = 0200
,07-27 15:04:37.936  7763  8146 D bte_conf:   clientExecutableURL = 
,07-27 15:04:37.936  7763  8146 D bte_conf:   serviceDescription  = 
07-27 15:04:37.946  7763  8146 D bte_conf:   documentationURL    = 
07-27 15:04:37.946  7763  8146 D bte_conf: bte_load_did_conf no section named DID2.
,07-27 15:04:37.946  7763  8146 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 15:04:37.946  7763  8180 D bt_vendor: op for 2
07-27 15:04:37.946  7763  8180 D bt_vendor: op for 6
,07-27 15:04:37.946  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.946  7763  8180 D bt_upio : proc btwrite assertion
,07-27 15:04:37.946  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.946  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.946  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.946  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.946  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:37.946  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:37.946  7763  8143 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 15:04:37.946  7763  8143 D BluetoothAdapterProperties: ScanMode =  20
,07-27 15:04:37.956  7763  8143 D BluetoothAdapterProperties: State =  11
,07-27 15:04:37.956   790  1377 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 15:04:37.956  7763  8146 D BluetoothAdapterProperties: Scan Mode:21
,07-27 15:04:37.956  7763  8146 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 15:04:37.956  7763  8143 D BluetoothAdapterProperties: Setting state to 12
,07-27 15:04:37.956  7763  8143 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 15:04:37.956   790  1264 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-27 15:04:37.956   790  1264 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:37.956   790  1264 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:37.956   790  1264 D SettingsProvider: selectionArgs: false
,07-27 15:04:37.956   790  1264 D SettingsProvider: selectionArgs: 1002
07-27 15:04:37.956   790  1264 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:37.956   790  1264 D SettingsProvider: ret = -1
,07-27 15:04:37.956  7763  8143 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:37.956  7763  8143 D BluetoothAdapterService: updateAdapterState state is 12
,07-27 15:04:37.956   790  1686 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:37.966   790  1686 D ActivityManager: caller:android.app.ApplicationThreadProxy@8d394c4, r.packageName :com.android.bluetooth
,07-27 15:04:37.966  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.966  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.976  7763  8180 E bt_h4   : vendor lib postload completed
07-27 15:04:37.976  7763  8180 D bt_vendor: op for 7
07-27 15:04:37.976  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.976  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.976  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.976  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.976  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.976  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.976  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.976  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.976  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.976  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.986  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.986  7763  7763 I BluetoothPbapService: Handler(): got msg=1
,07-27 15:04:37.986  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.986  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.986   790  1361 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 15:04:37.986  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.986  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.986  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.986  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.986  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.986  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.986  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.986  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.996  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.996  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:37.996  7763  7763 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 15:04:37.996  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.996  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.996  1315  1328 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 15:04:37.996  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.996  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:37.996   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-27 15:04:37.996  7763  8180 D bt_vendor: op for 7
07-27 15:04:37.996  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:37.996  7763  8180 D bt_vendor: op for 7
,07-27 15:04:37.996  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.006  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.006  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.006  7763  8143 D BluetoothAdapterService: Autoconnection is available 
,07-27 15:04:38.006  7763  8180 D bt_vendor: op for 7
,07-27 15:04:38.006  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:38.006  7763  8143 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,07-27 15:04:38.006  7763  8143 D BluetoothAdapterService: starting service from this receiver
07-27 15:04:38.006   790  1704 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:38.006   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@17d73930, r.packageName :com.android.bluetooth
,07-27 15:04:38.006  7763  8180 D bt_vendor: op for 7
,07-27 15:04:38.006  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.006  7763  8180 D bt_vendor: op for 7
,07-27 15:04:38.006  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.016  7763  8143 I BluetoothAdapterState: Entering On State from state = 11
,07-27 15:04:38.016  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.016  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.016   790  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.016  1407  1433 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 15:04:38.016  1315  1315 D BluetoothMap: Proxy object connected
07-27 15:04:38.016  1315  1315 D MapProfile: Bluetooth service connected
,07-27 15:04:38.016  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.016  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:38.016   790  1058 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:38.016   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:38.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:38.016  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.016  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:38.016   790   790 D BluetoothA2dp: Proxy object connected
,07-27 15:04:38.016  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.016  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.016  7763  8180 D bt_vendor: op for 7
,07-27 15:04:38.016  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.026  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:38.026   790  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.026  3186  7721 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:38.026   790  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:38.026  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:38.026  1407  1433 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:38.026  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:38.026   790  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.026  1407  1419 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:38.026   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.026   790  1058 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:38.026  1315  7720 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 15:04:38.036  7763  8195 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-27 15:04:38.036   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-27 15:04:38.036  7763  8195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 15:04:38.036   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.036  1315  1315 D BluetoothInputDevice: Proxy object connected
07-27 15:04:38.036  1315  1315 D HidProfile: Bluetooth service connected
07-27 15:04:38.036  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.036  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:38.036  7763  8195 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
,07-27 15:04:38.036  7763  8195 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 15:04:38.036  7763  8195 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 15:04:38.036  7763  8195 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e8ad94a
07-27 15:04:38.036  1315  1336 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 15:04:38.036  7763  8195 D BluetoothSocket: channel: 19
,07-27 15:04:38.036  1315  1328 D BluetoothPan: Binding service...
07-27 15:04:38.036  7763  8195 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 15:04:38.036   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-27 15:04:38.036  3186  3197 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:38.036   790  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:38.036  1315  1315 D HeadsetProfile: Bluetooth service connected
07-27 15:04:38.036  3186  3186 D BluetoothA2dp: Proxy object connected
07-27 15:04:38.036  1315  1336 D Bluetoothsap: onBluetoothStateChange: up=true
07-27 15:04:38.046  1315  1336 D Bluetoothsap: Binding service...
,07-27 15:04:38.046  1315  1336 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-27 15:04:38.046   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-27 15:04:38.046  1315  1336 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-27 15:04:38.046  1315  1315 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 15:04:38.046  1315  1328 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:38.046   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:38.046  1315  1315 D PanProfile: Bluetooth service connected
,07-27 15:04:38.046  7763  7774 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:38.046   790  1058 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:38.046  1427  1756 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 15:04:38.046  1315  7720 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 15:04:38.046  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object connected
07-27 15:04:38.046  1315  1315 D SapProfile: Bluetooth service connected
07-27 15:04:38.046  1315  1315 D Bluetoothsap: getConnectedDevices()
,07-27 15:04:38.046   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-27 15:04:38.046   790  1058 D BluetoothPan: Binding service...
,07-27 15:04:38.056   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-27 15:04:38.056   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-27 15:04:38.056   790   790 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 15:04:38.056  1315  1315 D BluetoothA2dp: Proxy object connected
07-27 15:04:38.056  1315  1315 D A2dpProfile: Bluetooth service connected
,07-27 15:04:38.056   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:38.056   790   790 I InputMethodManagerService: [BT Setting State] State =12
07-27 15:04:38.056   790   790 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 15:04:38.056  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-27 15:04:38.056  1739  1739 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 15:04:38.056  1407  1407 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@18bdb6af, true
07-27 15:04:38.056  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 15:04:38.056  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:38.056  1407  1407 D BluetoothHeadset: registerMessageListener
,07-27 15:04:38.056  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:38.066   790  1264 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:38.066   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 15:04:38.066   790  1264 D ActivityManager: caller:android.app.ApplicationThreadProxy@35123efd, r.packageName :com.google.android.gms
07-27 15:04:38.066  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:38.066  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:38.066   790  1635 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:38.066   790   806 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-27 15:04:38.066  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:38.066  1197  1594 D BluetoothTile:  handleUpdatestate:false name:null
07-27 15:04:38.066  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 15:04:38.066  1315  1315 D BluetoothPbap: Proxy object connected
07-27 15:04:38.066  1315  1315 D PbapServerProfile: Bluetooth service connected
07-27 15:04:38.066  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:38.066  7763  7774 D HeadsetService: registerMessageListener
,07-27 15:04:38.066  7763  7774 D HeadsetService: registerMessageListener
07-27 15:04:38.066  7763  8168 D HeadsetStateMachine: Disconnected process message: 70
07-27 15:04:38.066  1407  1407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-27 15:04:38.066  7763  8168 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@288f40bb
07-27 15:04:38.066  1407  1407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-27 15:04:38.076  7763  8213 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-27 15:04:38.076  7763  8168 D HeadsetStateMachine: Disconnected process message: 9
,07-27 15:04:38.076  1315  1315 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-27 15:04:38.076  1315  1315 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-27 15:04:38.076  7763  8213 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 15:04:38.076  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.076  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:38.076  7763  8213 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
07-27 15:04:38.076  7763  8213 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 15:04:38.076  7763  8213 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 15:04:38.076  7763  8213 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3659b9d8
07-27 15:04:38.076  7763  8213 D BluetoothSocket: channel: 5
,07-27 15:04:38.076  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 15:04:38.086  7763  8168 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-27 15:04:38.086   790  1576 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 15:04:38.086   790  1576 D ActivityManager: caller:android.app.ApplicationThreadProxy@14b57cc0, r.packageName :com.android.settings
,07-27 15:04:38.086   310   762 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-27 15:04:38.086   310   762 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-27 15:04:38.086   310   762 V voice   : voice_set_parameters: exit with code(-2)
07-27 15:04:38.086   310   762 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-27 15:04:38.086   310   762 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 15:04:38.086   310   762 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 15:04:38.086   310   762 V audio_hw_primary: adev_set_parameters: exit
07-27 15:04:38.086  7763  8168 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-27 15:04:38.086  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:38.086  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:38.096  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:38.096  7763  7763 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 15:04:38.096   790  1264 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:38.096   790  1264 D ActivityManager: caller:android.app.ApplicationThreadProxy@30d7c13e, r.packageName :com.android.bluetooth
,07-27 15:04:38.116   790   805 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 15:04:38.126  7763  8221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 15:04:38.126  7763  8221 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-27 15:04:38.126  7763  8221 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 15:04:38.126  7763  8221 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 15:04:38.126  7763  8221 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@209c9b84
,07-27 15:04:38.126  7763  8180 D bt_vendor: op for 7
07-27 15:04:38.126  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:38.126  7763  8221 D BluetoothSocket: channel: 12
,07-27 15:04:38.126  7763  8221 I BtOppRfcommListener: Accept thread started.
,07-27 15:04:38.156  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:38.156   790  1704 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:38.156   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@116b12bb, r.packageName :com.google.android.gms
,07-27 15:04:38.166  1834  8224 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 15:04:38.166  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:38.176   790   806 D ActivityManager: caller:android.app.ApplicationThreadProxy@20da584, r.packageName :com.google.android.gms
,07-27 15:04:38.176  1834  8224 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 15:04:39.016   303   303 E SMD     : DCD ON
,07-27 15:04:39.476  7530  7607 D BluetoothAdapter: disable()
,07-27 15:04:39.476   790  1458 D SettingsProvider: name = bluetooth_on
,07-27 15:04:39.506  7763  8143 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-27 15:04:39.506  7763  8143 D BluetoothAdapterProperties: Setting state to 13
07-27 15:04:39.506  7763  8143 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-27 15:04:39.506  7763  8143 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:39.506  7763  8143 D BluetoothAdapterService: updateAdapterState state is 13
,07-27 15:04:39.506   790  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:39.506   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@268e61a2, r.packageName :com.android.bluetooth
,07-27 15:04:39.506  7763  7763 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-27 15:04:39.506  7763  8143 D BluetoothAdapterService: Autoconnection is available 
,07-27 15:04:39.506  7763  8143 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-27 15:04:39.506  7763  8143 D BluetoothAdapterService: terminating service from this receiver
,07-27 15:04:39.506  7763  7763 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26289f6d, channel: 19, state: LISTENING
,07-27 15:04:39.516  7763  7763 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26289f6d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e8ad94a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b2d47a2mSocket: android.net.LocalSocket@27670c33 impl:android.net.LocalSocketImpl@f09ebf0 fd:FileDescriptor[73]
07-27 15:04:39.516  7763  7763 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27670c33 impl:android.net.LocalSocketImpl@f09ebf0 fd:FileDescriptor[73]
,07-27 15:04:39.516  7763  8143 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 15:04:39.526   790  1474 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 15:04:39.526  7763  8143 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-27 15:04:39.526  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.526  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.526  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.526  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.526  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.526  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:39.526  7763  8146 D BluetoothAdapterProperties: Scan Mode:20
,07-27 15:04:39.526  7763  8143 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-27 15:04:39.526  7763  8143 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-27 15:04:39.526  7763  8143 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,07-27 15:04:39.526  7763  8143 E bt-btif : cmd socket is not created
,07-27 15:04:39.526  7763  8143 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-27 15:04:39.526  7763  8180 D bt_vendor: op for 7
07-27 15:04:39.526  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.536  7763  8178 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,07-27 15:04:39.536  7763  8178 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,07-27 15:04:39.536  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:39.536  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:39.536  7763  8178 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-27 15:04:39.536  7763  8180 D bt_vendor: op for 7
07-27 15:04:39.536  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.536  7763  8221 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-27 15:04:39.536  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.536  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.536  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.536  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.536  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.536  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:39.546  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:39.546  7763  8180 D bt_vendor: op for 7
,07-27 15:04:39.546  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:39.546  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:39.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 15:04:39.556  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:39.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:39.556  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:39.556  7530  7530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 15:04:39.556  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:39.556   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:39.566   790   790 I InputMethodManagerService: [BT Setting State] State =13
,07-27 15:04:39.566  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-27 15:04:39.566  7763  7763 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24bc3bee, channel: 5, state: LISTENING
,07-27 15:04:39.566  7763  7763 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24bc3bee, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3659b9d8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@67c388fmSocket: android.net.LocalSocket@29b9d71c impl:android.net.LocalSocketImpl@1f534f25 fd:FileDescriptor[75]
07-27 15:04:39.566  7763  7763 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29b9d71c impl:android.net.LocalSocketImpl@1f534f25 fd:FileDescriptor[75]
,07-27 15:04:39.566  7763  7763 I BtOppRfcommListener: stopping Accept Thread
,07-27 15:04:39.566  7763  7763 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@143428fa, channel: 12, state: LISTENING
07-27 15:04:39.566  7763  7763 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@143428fa, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@209c9b84, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a0dceabmSocket: android.net.LocalSocket@201b4908 impl:android.net.LocalSocketImpl@eb8a1 fd:FileDescriptor[80]
07-27 15:04:39.566  7763  7763 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@201b4908 impl:android.net.LocalSocketImpl@eb8a1 fd:FileDescriptor[80]
,07-27 15:04:39.566  7763  8221 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-27 15:04:39.566  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 15:04:39.566  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:39.566  1197  1594 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 15:04:39.576  1197  1594 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 15:04:39.576   790  1635 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:39.576   790  3246 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 15:04:39.576  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 15:04:39.576  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 15:04:39.576  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:39.576  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:39.576   790   805 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:39.576   790   805 D ActivityManager: caller:android.app.ApplicationThreadProxy@31ab1e33, r.packageName :com.google.android.gms
,07-27 15:04:39.586  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:39.586  1739  1739 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-27 15:04:39.586  1315  1315 D BluetoothPbap: Proxy object disconnected
07-27 15:04:39.586  1315  1315 D PbapServerProfile: Bluetooth service disconnected
07-27 15:04:39.586  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:39.586  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 15:04:39.596   790  1704 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-27 15:04:39.596   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@257c2769, r.packageName :com.android.settings
,07-27 15:04:39.596  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:39.596  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:39.656  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:39.666  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:39.686  7763  8180 D bt_vendor: op for 6
07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:39.686  7763  8180 D bt_vendor: op for 7
07-27 15:04:39.686  7763  8180 D bt_upio : BT_WAKE is asserted already
07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:39.686  7763  8181 D bt_userial: RX termination
07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:39.686  7763  8178 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:39.686  7763  8178 W bt-btif : ag scb idx 1 not allocated
07-27 15:04:39.686  7763  8178 W bt-btif : ag scb idx 2 not allocated
07-27 15:04:39.686  7763  8178 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 15:04:39.686  7763  8181 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
,07-27 15:04:39.686  7763  8181 D bt_userial: Leaving userial_read_thread()
07-27 15:04:39.686  7763  8146 D bt_userial: userial_close_reader Joined userial reader thread: 0
07-27 15:04:39.686  7763  8180 D bt_vendor: op for 9
07-27 15:04:39.686  7763  8180 D bt_hwcfg: hw_epilog_process
,07-27 15:04:39.686  7763  8146 D bt_vendor: op for 4
07-27 15:04:39.686  7763  8146 I bt_userial_vendor: device fd = 66 close
,07-27 15:04:39.686  7763  8146 D bt_vendor: op for 0
,07-27 15:04:39.686  7763  8146 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 15:04:39.686  7763  8146 D bt_upio : is_emulator_context : 0
07-27 15:04:39.686  7763  8146 D bt_upio : is_rfkill_disabled ? [0]
,07-27 15:04:39.696  7763  8146 D bt_vendor: cleanup,
,07-27 15:04:39.696  7763  8178 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 15:04:39.696  7763  8146 I GKI_LINUX: GKI_exit_task 0 done
07-27 15:04:39.696  7763  8146 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-27 15:04:39.696  7763  8143 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 15:04:39.696  7763  8143 D BtConfig.SecureMode: isSecureModeOn:false
07-27 15:04:39.696  7763  8143 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-27 15:04:39.696  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-27 15:04:39.696   790  1377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:39.696   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@25ef6a8f, r.packageName :com.android.bluetooth
,07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 15:04:39.696  7763  7763 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 15:04:39.696  7763  7763 D BtGatt.GattService: Received stop request...Stopping profile...
,07-27 15:04:39.696  7763  7763 D BtGatt.GattService: stop()
07-27 15:04:39.696  7763  7763 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 15:04:39.696  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:39.696   790  1266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:39.696   790  1266 D ActivityManager: caller:android.app.ApplicationThreadProxy@1302211c, r.packageName :com.android.bluetooth
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,07-27 15:04:39.696  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-27 15:04:39.696   790  1377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:39.696   790  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@35a6d125, r.packageName :com.android.bluetooth
,07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 15:04:39.696  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-27 15:04:39.696   790  3246 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:39.696  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:39.696   790  3246 D ActivityManager: caller:android.app.ApplicationThreadProxy@135e82fa, r.packageName :com.android.bluetooth
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,07-27 15:04:39.696  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 15:04:39.696  7763  7763 D HeadsetService: Received stop request...Stopping profile...
07-27 15:04:39.696   790   805 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:39.696   790   805 D ActivityManager: caller:android.app.ApplicationThreadProxy@128220ab, r.packageName :com.android.bluetooth
,07-27 15:04:39.696  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 15:04:39.696  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 15:04:39.696  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-27 15:04:39.706  1315  1315 D HeadsetProfile: Bluetooth service disconnected
,07-27 15:04:39.706   790  1267 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:39.706   790  1267 D ActivityManager: caller:android.app.ApplicationThreadProxy@369e3308, r.packageName :com.android.bluetooth
,07-27 15:04:39.706   790   790 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-27 15:04:39.706  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.706  7763  7763 D A2dpService: Received stop request...Stopping profile...
07-27 15:04:39.706   790  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:39.706  7763  7763 V Avrcp   : doQuit
07-27 15:04:39.706   790  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@35185aa1, r.packageName :com.android.bluetooth
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 15:04:39.706  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-27 15:04:39.706  7763  8173 D A2dpStateMachine: Exit Disconnected: -1
07-27 15:04:39.706   790  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:39.706  7686  7686 W BluetoothHeadset: Proxy not attached to service
,07-27 15:04:39.706   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@81d4c6, r.packageName :com.android.bluetooth
07-27 15:04:39.706  7763  7763 D Avrcp   : Unregistering previous receiver
,07-27 15:04:39.706  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:39.706  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,07-27 15:04:39.706  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 15:04:39.706  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 15:04:39.706  7763  8143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 15:04:39.706  7763  8143 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 15:04:39.706  7763  8143 D BluetoothAdapterState: Stopping profile services that were post enabled
,07-27 15:04:39.706  1315  1315 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:39.706  1315  1315 D A2dpProfile: Bluetooth service disconnected
07-27 15:04:39.706  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-27 15:04:39.706   790   790 D BluetoothA2dp: Proxy object disconnected
,07-27 15:04:39.706   790   790 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 15:04:39.706  7763  7763 D HidService: Received stop request...Stopping profile...
07-27 15:04:39.706  7763  7763 D HidService: Stopping Bluetooth HidService
07-27 15:04:39.706  7763  7763 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 15:04:39.706  7763  7763 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,07-27 15:04:39.706  7763  7763 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 15:04:39.706  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
07-27 15:04:39.706  3186  3186 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:39.706  1315  1315 D BluetoothInputDevice: Proxy object disconnected
,07-27 15:04:39.706  1315  1315 D HidProfile: Bluetooth service disconnected
07-27 15:04:39.706  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-27 15:04:39.706  7763  7763 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:39.706  7763  7763 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-27 15:04:39.706  7763  7763 D HealthService: Received stop request...Stopping profile...
07-27 15:04:39.706  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:39.716  7763  7763 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 15:04:39.716  7763  7763 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:39.716  7763  7763 D PanService: Received stop request...Stopping profile...
,07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:39.716   790   790 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 15:04:39.716  7763  7763 D BluetoothMapService: Received stop request...Stopping profile...
,07-27 15:04:39.716  1315  1315 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 15:04:39.716  1315  1315 D PanProfile: Bluetooth service disconnected
,07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:39.716  7763  7763 D SapService: Received stop request...Stopping profile...
,07-27 15:04:39.716  7763  7763 D SapService: Stopping Bluetooth SapService
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15a2c7a9
,07-27 15:04:39.716  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-27 15:04:39.716  7763  7763 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-27 15:04:39.716  7763  7763 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-27 15:04:39.716  7763  8174 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 15:04:39.716  7763  7763 I GKI_LINUX: GKI_exit_task 2 done
07-27 15:04:39.716  7763  7763 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 15:04:39.716  7763  7763 V Avrcp   : cleanup
07-27 15:04:39.716  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-27 15:04:39.716  7763  7763 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.716  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-27 15:04:39.716  7763  7763 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.716  7763  7763 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 15:04:39.716  7763  7763 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 15:04:39.716  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-27 15:04:39.716  7763  7763 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.716  7763  7763 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 15:04:39.716  7763  7763 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-27 15:04:39.716  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-27 15:04:39.716  7763  7763 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 15:04:39.716  7763  7763 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-27 15:04:39.716  7763  7763 E BluetoothAdapterService(362989481): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-27 15:04:39.716  7763  8143 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-27 15:04:39.716  7763  7763 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-27 15:04:39.716  7763  7763 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-27 15:04:39.716  7763  8143 D BluetoothAdapterProperties: Setting state to 10
07-27 15:04:39.716  7763  8143 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 15:04:39.716  7763  8143 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-27 15:04:39.716  7763  8143 D BluetoothAdapterService: updateAdapterState state is 10
07-27 15:04:39.726  7763  8143 D BluetoothAdapterService: Autoconnection is available 
07-27 15:04:39.726  7763  8143 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-27 15:04:39.726  7763  8143 I BluetoothAdapterState: Entering OffState
07-27 15:04:39.726  1315  1336 D BluetoothMap: onBluetoothStateChange: up=false
07-27 15:04:39.726  1315  1315 D BluetoothMap: Proxy object disconnected
07-27 15:04:39.726  1315  1315 D MapProfile: Bluetooth service disconnected
07-27 15:04:39.726  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-27 15:04:39.726  1315  1315 D SapProfile: Bluetooth service disconnected
,07-27 15:04:39.726   790  1058 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 15:04:39.726  1315  7720 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 15:04:39.726  3186  3197 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 15:04:39.726  1315  7720 D Bluetoothsap: onBluetoothStateChange: up=false
07-27 15:04:39.726  1315  7720 D Bluetoothsap: Unbinding service...
07-27 15:04:39.726  1315  1328 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 15:04:39.726  7763  8062 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 15:04:39.726  1315  1336 D BluetoothPbap: onBluetoothStateChange: up=false
,07-27 15:04:39.726   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,07-27 15:04:39.726   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-27 15:04:39.736   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.736   790   790 I InputMethodManagerService: [BT Setting State] State =10
07-27 15:04:39.736   790   790 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 15:04:39.736  1739  1739 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-27 15:04:39.736  1197  1197 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:39.736  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.736  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 15:04:39.736  1197  1197 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:39.736  1197  1197 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:39.736  1197  1594 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:39.736  1197  1594 D BluetoothAdapter: 461855567: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:39.736  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 15:04:39.736   790  1361 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:39.736  7763  8146 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-27 15:04:39.736  1834  2327 D BluetoothAdapter: 135578864: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:39.736  1834  2327 D BluetoothAdapter: 135578864: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:39.736   790  1458 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 15:04:39.736  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:39.736  7763  7763 I GKI_LINUX: GKI_exit_task 1 done
07-27 15:04:39.736  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:39.736  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.736  7763  7763 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-27 15:04:39.736  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:39.736  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 15:04:39.746  7763  7763 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 15:04:39.746   790   805 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:39.746   790   805 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d401c87, r.packageName :com.google.android.gms
07-27 15:04:39.746  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 15:04:39.746  7763  7763 I art     : System.exit called, status: 0
07-27 15:04:39.746  7763  7763 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 15:04:39.746   790  1474 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-27 15:04:39.746   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fbeffdd, r.packageName :com.android.settings
,07-27 15:04:39.756  1315  1315 D DockEventReceiver: finishStartingService: stopping service
07-27 15:04:39.756  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:39.786   790  1377 I ActivityManager: Process com.android.bluetooth (pid 7763)(adj 0) has died(204,1562)
,07-27 15:04:39.816  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:39.816   790  1576 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:39.816   790  1576 D ActivityManager: caller:android.app.ApplicationThreadProxy@830bcd9, r.packageName :com.google.android.gms
,07-27 15:04:39.826  1834  8257 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 15:04:39.826  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:39.826   790  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@34c6157f, r.packageName :com.google.android.gms
,07-27 15:04:39.836  1834  8257 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-27 15:04:40.126   790  3122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 15:04:42.026   303   303 E SMD     : DCD ON
,07-27 15:04:42.597  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 15:04:42.597  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:43.217   790  3089 D SSRM:n  : SIOP:: AP = 360, PST = 371, CUR = 450
,07-27 15:04:44.627   790  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 15:04:44.627   790  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 15:04:44.627   790  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 15:04:44.627   790   790 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 15:04:44.627   790  1458 D BatteryService: stay LED for fully charged
,07-27 15:04:44.627   790   790 I MotionRecognitionService: Plugged
,07-27 15:04:44.627   790   790 I MotionRecognitionService: setPowerConnected  = true
,07-27 15:04:44.627  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 15:04:44.627  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 15:04:44.637  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 15:04:44.637  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:44.637  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:44.637  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 15:04:45.026   303   303 E SMD     : DCD ON
,07-27 15:04:45.596  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:45.596  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b2f8813 added. We now have 6 listener(s)
,07-27 15:04:45.596  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:45.606  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:45.606  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3064ea50 added. We now have 7 listener(s)
,07-27 15:04:45.606  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:45.606  7530  7607 I System.out: IsBluetoothEnabled
,07-27 15:04:45.616  7530  7607 D BluetoothAdapter: disable(),
,07-27 15:04:45.616   790  1704 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-27 15:04:45.616  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:45.616  7530  7607 D BluetoothAdapter: enable()
,07-27 15:04:45.626   790  1686 W ActivityManager: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-27 15:04:45.626   790  1686 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 15:04:45.626   790  1686 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:45.626   790  1686 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 15:04:45.626   790  1686 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-27 15:04:45.626   790  1686 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-27 15:04:45.626   790  1686 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-27 15:04:45.626   790  1686 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-27 15:04:45.626   790  1686 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 15:04:45.626   790  1686 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:45.626   790  1686 D SettingsProvider: name = bluetooth_on
,07-27 15:04:45.626   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:45.636   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:45.636   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-27 15:04:45.636   790  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:45.636   790  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:45.636   790  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:45.636   790  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:45.676  8267  8267 E Zygote  : MountEmulatedStorage()
,07-27 15:04:45.686   790  1058 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8267 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-27 15:04:45.686  8267  8267 E Zygote  : v2
07-27 15:04:45.686  8267  8267 I libpersona: KNOX_SDCARD checking this for 1002
07-27 15:04:45.686  8267  8267 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:45.696  8267  8267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 15:04:45.696  8267  8267 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:45.696  8267  8267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:45.736  8267  8267 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:45.736  8267  8267 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:45.746  8267  8267 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-27 15:04:45.746  8267  8267 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-27 15:04:45.756  8267  8267 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 15:04:45.766  8267  8267 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding GattService
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding HeadsetService
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding A2dpService
07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding HidService
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding HealthService
07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding PanService
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding SapService
07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding HeadsetClientService
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding SapClientService
,07-27 15:04:45.796  8267  8267 D BtSettings.ProfileConfig: Adding HidDevService
07-27 15:04:45.796  8267  8267 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 15:04:45.806   790  1266 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,07-27 15:04:45.806   790  1266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.806   790  1266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.806   790  1266 D SettingsProvider: selectionArgs: false
07-27 15:04:45.806   790  1266 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.806   790  1266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:45.806   790  1266 D SettingsProvider: ret = -1
07-27 15:04:45.806   790  1458 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:45.806   790  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.806   790  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.806   790  1458 D SettingsProvider: selectionArgs: false
07-27 15:04:45.806   790  1458 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.806   790  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:45.806   790  1458 D SettingsProvider: ret = -1
07-27 15:04:45.806   790  1635 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-27 15:04:45.806   790  1635 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:45.806   790  1635 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.806   790  1635 D SettingsProvider: selectionArgs: false
07-27 15:04:45.806   790  1635 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.806   790  1635 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.806   790  1635 D SettingsProvider: ret = -1
,07-27 15:04:45.806   790  1361 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-27 15:04:45.806   790  1361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:45.806   790  1361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.806   790  1361 D SettingsProvider: selectionArgs: false
07-27 15:04:45.806   790  1361 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.806   790  1361 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.806   790  1361 D SettingsProvider: ret = -1
,07-27 15:04:45.806   790  1648 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 15:04:45.806   790  1648 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:45.806   790  1648 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.806   790  1648 D SettingsProvider: selectionArgs: false
07-27 15:04:45.806   790  1648 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.806   790  1648 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.806   790  1648 D SettingsProvider: ret = -1
,07-27 15:04:45.806   790  3246 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-27 15:04:45.806   790  3246 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.806   790  3246 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 15:04:45.806   790  3246 D SettingsProvider: selectionArgs: false
07-27 15:04:45.806   790  3246 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.806   790  3246 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.806   790  3246 D SettingsProvider: ret = -1
,07-27 15:04:45.806   790  1576 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-27 15:04:45.806   790  1576 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.806   790  1576 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 15:04:45.816   790  1576 D SettingsProvider: selectionArgs: false
07-27 15:04:45.816   790  1576 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.816   790  1576 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.816   790  1576 D SettingsProvider: ret = -1
,07-27 15:04:45.816   790  1267 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-27 15:04:45.816   790  1267 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:45.816   790  1267 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.816   790  1267 D SettingsProvider: selectionArgs: false
07-27 15:04:45.816   790  1267 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.816   790  1267 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.816   790  1267 D SettingsProvider: ret = -1
,07-27 15:04:45.816   790   806 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:45.816   790   806 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:45.816   790   806 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.816   790   806 D SettingsProvider: selectionArgs: false
07-27 15:04:45.816   790   806 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.816   790   806 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:45.816   790   806 D SettingsProvider: ret = -1
07-27 15:04:45.816   790  1377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,07-27 15:04:45.816   790  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.816   790  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.816   790  1377 D SettingsProvider: selectionArgs: false
07-27 15:04:45.816   790  1377 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.816   790  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:45.816   790  1377 D SettingsProvider: ret = -1
07-27 15:04:45.816   790  1264 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,07-27 15:04:45.816   790  1264 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.816   790  1264 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.816   790  1264 D SettingsProvider: selectionArgs: false
07-27 15:04:45.816   790  1264 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.816   790  1264 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:45.816   790  1264 D SettingsProvider: ret = -1
07-27 15:04:45.816   790  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,07-27 15:04:45.816   790  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.816   790  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.816   790  1474 D SettingsProvider: selectionArgs: false
07-27 15:04:45.816   790  1474 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.816   790  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 15:04:45.816   790  1474 D SettingsProvider: ret = -1
,07-27 15:04:45.836  8267  8267 D BluetoothAdapterState: make
,07-27 15:04:45.836  8267  8267 I bluedroid: init
,07-27 15:04:45.836  8267  8286 I BluetoothAdapterState: Entering OffState
,07-27 15:04:45.836  8267  8267 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 15:04:45.836  8267  8267 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 15:04:45.836  8267  8267 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 15:04:45.836  8267  8267 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-27 15:04:45.846  8267  8267 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-27 15:04:45.846  8267  8267 I bluedroid: get_profile_interface socket
07-27 15:04:45.846  8267  8267 I bluedroid: get_profile_interface map_client
07-27 15:04:45.846  8267  8290 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-27 15:04:45.846  8267  8267 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-27 15:04:45.846  8267  8290 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-27 15:04:45.846  8267  8290 E BluetoothServiceJni: populateRssiValuesNative
07-27 15:04:45.846  8267  8290 I bluedroid: getModelRssiValues
07-27 15:04:45.846  8267  8290 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 15:04:45.846  8267  8290 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 15:04:45.846   790   790 D SettingsProvider: name = bluetooth_name
,07-27 15:04:45.846  8267  8290 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 15:04:45.846   790  1576 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:45.856  8267  8275 I bluedroid: config_hci_snoop_log
,07-27 15:04:45.856   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-27 15:04:45.856   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 15:04:45.856   790  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 15:04:45.856   790  1058 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-27 15:04:45.856  8267  8286 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-27 15:04:45.856  8267  8286 D BluetoothAdapterProperties: Setting state to 11
07-27 15:04:45.866  8267  8286 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-27 15:04:45.866  8267  8286 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:45.866  8267  8286 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 15:04:45.866  8267  8286 D BluetoothAdapterService: Autoconnection is available 
07-27 15:04:45.866  8267  8286 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-27 15:04:45.866   790  1264 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:45.866  1739  1739 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 15:04:45.866   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:45.866   790   790 I InputMethodManagerService: [BT Setting State] State =11
,07-27 15:04:45.866  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 15:04:45.866  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:45.866   790  1264 D ActivityManager: caller:android.app.ApplicationThreadProxy@ff3065a, r.packageName :com.google.android.gms
07-27 15:04:45.866  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:45.866   790  1648 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:45.866   790  3246 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 15:04:45.866  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:45.876  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 15:04:45.876  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 15:04:45.876  8267  8286 D BluetoothSecureManager: getInstant: null
07-27 15:04:45.876  8267  8286 D BluetoothSecureManager: calling getMethod for getService
07-27 15:04:45.876  8267  8286 D BluetoothSecureManager: calling getService
,07-27 15:04:45.876  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:45.876  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:45.876  8267  8286 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1a941448
,07-27 15:04:45.876   790  1635 D BluetoothSecureManagerService: isSecureModeEnabled
07-27 15:04:45.876   790  1635 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-27 15:04:45.876  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
07-27 15:04:45.876  8267  8286 D BtConfig.SecureMode: isSecureModeOn:false
07-27 15:04:45.876  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService,
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-27 15:04:45.886  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 15:04:45.886  8267  8286 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-27 15:04:45.896  8267  8286 D BluetoothBondStateMachine: make
,07-27 15:04:45.896  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-27 15:04:45.896  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 15:04:45.896  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-27 15:04:45.896  8267  8292 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 15:04:45.896   790   806 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.896   790   806 D ActivityManager: caller:android.app.ApplicationThreadProxy@94fd568, r.packageName :com.android.bluetooth
,07-27 15:04:45.906  8267  8267 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-27 15:04:45.906  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 15:04:45.906  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 15:04:45.906  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-27 15:04:45.906   790  1704 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.906   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@7cb2e26, r.packageName :com.android.bluetooth
,07-27 15:04:45.906  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 15:04:45.906  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 15:04:45.906  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-27 15:04:45.916   790  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.916   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@e014, r.packageName :com.android.bluetooth
,07-27 15:04:45.916  8267  8267 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 15:04:45.916  8267  8267 D BtGatt.GattService: Received start request. Starting profile...
,07-27 15:04:45.916  8267  8267 D BtGatt.GattService: start()
07-27 15:04:45.916  8267  8267 I bluedroid: get_profile_interface gatt
,07-27 15:04:45.916  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
07-27 15:04:45.916  8267  8267 D BtGatt.AdvertiseManager: advertise manager created
,07-27 15:04:45.916  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 15:04:45.916  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 15:04:45.916  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-27 15:04:45.916   790  1576 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.916   790  1576 D ActivityManager: caller:android.app.ApplicationThreadProxy@fac06b2, r.packageName :com.android.bluetooth
,07-27 15:04:45.916  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 15:04:45.916  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 15:04:45.916  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-27 15:04:45.916   790  1266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.916   790  1266 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e15e980, r.packageName :com.android.bluetooth
,07-27 15:04:45.926  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 15:04:45.926  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 15:04:45.926  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-27 15:04:45.926   790  1648 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:45.926   790  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c4fdbfe, r.packageName :com.android.bluetooth
,07-27 15:04:45.926  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 15:04:45.926  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 15:04:45.926  8267  8286 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-27 15:04:45.926   790  3246 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.926   790  3246 D ActivityManager: caller:android.app.ApplicationThreadProxy@74f727b, r.packageName :com.android.bluetooth
,07-27 15:04:45.926  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 15:04:45.926  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 15:04:45.926  8267  8286 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-27 15:04:45.936   790  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:45.936   790  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@62608f1, r.packageName :com.android.bluetooth
,07-27 15:04:45.936  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:45.936  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:45.936  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 15:04:45.936  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 15:04:45.936  8267  8286 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 15:04:45.936  8267  8286 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 15:04:45.936  8267  8286 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 15:04:45.936  8267  8267 D HeadsetService: Received start request. Starting profile...
,07-27 15:04:45.936  8267  8267 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 15:04:45.936  8267  8267 D HeadsetStateMachine: make
,07-27 15:04:45.946  8267  8267 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 15:04:45.946   790   806 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-27 15:04:45.956   790  1576 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-27 15:04:45.956  8267  8267 I bluedroid: get_profile_interface handsfree
,07-27 15:04:45.966  8267  8267 I DualScoManager: Instantiating Dual Sco Manager
,07-27 15:04:45.966  8267  8267 I DualScoManager: Set HeadsetServiceHelper
,07-27 15:04:45.966  8267  8267 D BluetoothAtMessage: createCMTIContentObservers
,07-27 15:04:45.966   790  1361 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-27 15:04:45.966   790  1361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 15:04:45.966   790  1361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:45.966   790  1361 D SettingsProvider: selectionArgs: false
07-27 15:04:45.966   790  1361 D SettingsProvider: selectionArgs: 1002
07-27 15:04:45.966   790  1361 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:45.966   790  1361 D SettingsProvider: ret = -1
,07-27 15:04:45.966  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:45.966  8267  8295 D HeadsetStateMachine: Enter Disconnected: -2
,07-27 15:04:45.966  8267  8295 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-27 15:04:45.976  8267  8267 D A2dpService: Received start request. Starting profile...
,07-27 15:04:45.976  8267  8295 D HeadsetStateMachine: map size, before remove : 0
07-27 15:04:45.976  8267  8295 D HeadsetStateMachine: map size, after remove: 0
07-27 15:04:45.976  8267  8295 D HeadsetStateMachine: mNextConnectingDevice : null
,07-27 15:04:45.976  8267  8267 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-27 15:04:45.976  8267  8267 V Avrcp   : make
,07-27 15:04:45.976  8267  8267 V Avrcp   : Avrcp
,07-27 15:04:45.976  8267  8267 I bluedroid: get_profile_interface avrcp
,07-27 15:04:45.976  8267  8267 V Avrcp   : start
,07-27 15:04:45.986  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:45.986  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:45.996  8267  8267 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 15:04:45.996  8267  8267 V Avrcp   : ++registerMediaPlayers++
,07-27 15:04:45.996  8267  8267 I Avrcp   : No of Audio players :: 2
,07-27 15:04:45.996  8267  8267 I Avrcp   : App Package name is com.google.android.music
,07-27 15:04:45.996  8267  8267 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 15:04:46.006  8267  8267 I Avrcp   : App pkg name is Google Play Music
,07-27 15:04:46.006  8267  8267 I Avrcp   : Name::Google Play Music
,07-27 15:04:46.006  8267  8267 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 15:04:46.006  8267  8267 I Avrcp   : App Package name is com.sec.android.app.music
,07-27 15:04:46.006  8267  8267 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-27 15:04:46.006  8267  8267 I Avrcp   : App pkg name is Music
,07-27 15:04:46.006  8267  8267 I Avrcp   : Name::Music
07-27 15:04:46.006  8267  8267 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-27 15:04:46.006  8267  8267 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-27 15:04:46.006  8267  8267 I Avrcp   : No of Video players :: 1
,07-27 15:04:46.006  8267  8267 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-27 15:04:46.016  8267  8267 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-27 15:04:46.016  8267  8267 I Avrcp   : Video App pkg name is Video Player
,07-27 15:04:46.016  8267  8267 I Avrcp   : Name::Video Player
07-27 15:04:46.016  8267  8267 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,07-27 15:04:46.016  8267  8267 I Avrcp   : Add tempPlayer
07-27 15:04:46.016  8267  8267 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 15:04:46.016  8267  8267 I Avrcp   : Total no of players: 4
07-27 15:04:46.016  8267  8267 V Avrcp   : swapping the samsung player with 1st player
,07-27 15:04:46.016  8267  8267 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-27 15:04:46.016  8267  8305 V Avrcp   : handleMessage, msg=207
,07-27 15:04:46.016  8267  8305 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-27 15:04:46.016  8267  8267 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 15:04:46.016  8267  8267 D A2dpStateMachine: make
,07-27 15:04:46.026  8267  8267 I bluedroid: get_profile_interface a2dp
,07-27 15:04:46.026  8267  8305 D BluetoothMediaBrowser: no now playing list
07-27 15:04:46.026  8267  8309 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 15:04:46.026  8267  8267 E bt-btif : warning : media task started media_task_refcnt 1 
,07-27 15:04:46.026  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:46.026  8267  8308 D A2dpStateMachine: Enter Disconnected: -2
07-27 15:04:46.026  8267  8305 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,07-27 15:04:46.026  8267  8305 D Avrcp   :  checkNowPlayingList start
,07-27 15:04:46.026  8267  8267 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 15:04:46.026  8267  8267 D HidService: Received start request. Starting profile...
,07-27 15:04:46.026  8267  8267 I bluedroid: get_profile_interface hidhost
07-27 15:04:46.026  8267  8267 D HidService: setHidService(): set to: null
07-27 15:04:46.026  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:46.026  8267  8267 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 15:04:46.036  8267  8267 D HealthService: Received start request. Starting profile...
,07-27 15:04:46.036  8267  8267 I bluedroid: get_profile_interface health
,07-27 15:04:46.036  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:46.036  8267  8267 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 15:04:46.036  8267  8267 D PanService: Received start request. Starting profile...
07-27 15:04:46.036  8267  8267 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 15:04:46.036  8267  8267 I bluedroid: get_profile_interface pan
,07-27 15:04:46.036  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:46.046  8267  8267 D BluetoothMapService: Received start request. Starting profile...
,07-27 15:04:46.066  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:46.066  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-27 15:04:46.066  8267  8267 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-27 15:04:46.076  8267  8267 D SapService: Received start request. Starting profile...
07-27 15:04:46.076  8267  8267 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-27 15:04:46.076  8267  8267 I bluedroid: get_profile_interface sap
07-27 15:04:46.076  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:46.076  8267  8267 D HeadsetStateMachine: Try to query the phonestate on bind
07-27 15:04:46.076  1407  3082 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 15:04:46.076  1407  1407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-27 15:04:46.076  8267  8267 D HeadsetStateMachine: Proxy object connected
,07-27 15:04:46.076  8267  8267 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-27 15:04:46.076  8267  8267 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 15:04:46.076  8267  8295 D HeadsetStateMachine: Disconnected process message: 11
,07-27 15:04:46.076  8267  8267 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 15:04:46.076  8267  8295 D HeadsetStateMachine: Disconnected process message: 18
07-27 15:04:46.076  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,07-27 15:04:46.076  8267  8267 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 15:04:46.076  8267  8295 D HeadsetStateMachine: Disconnected process message: 10
07-27 15:04:46.076  8267  8267 D BluetoothA2dp: Proxy object connected
07-27 15:04:46.076  8267  8295 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 15:04:46.076  8267  8267 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-27 15:04:46.076  8267  8295 D HeadsetStateMachine: Disconnected process message: 11
,07-27 15:04:46.076  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,07-27 15:04:46.076  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-27 15:04:46.076  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,07-27 15:04:46.076  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-27 15:04:46.086  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-27 15:04:46.086  8267  8267 E BluetoothAdapterService(414069875): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-27 15:04:46.086  8267  8286 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-27 15:04:46.086  8267  8286 I bluedroid: enable
,07-27 15:04:46.086  8267  8286 I bt_hci_bdroid: init
,07-27 15:04:46.086  8267  8313 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,07-27 15:04:46.086  8267  8286 I bt_vendor: init
07-27 15:04:46.086  8267  8286 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 15:04:46.086  8267  8286 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 15:04:46.086  8267  8286 D bt_userial: userial_init
07-27 15:04:46.086  8267  8286 D bt_vendor: op for 5
,07-27 15:04:46.086  8267  8286 D bt_vendor: op for 0
,07-27 15:04:46.086  8267  8286 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 15:04:46.086  8267  8286 D bt_upio : is_emulator_context : 0
07-27 15:04:46.086  8267  8286 D bt_upio : is_rfkill_disabled ? [0]
07-27 15:04:46.086  8267  8286 D bt_upio : is_rfkill_disabled ? [0]
,07-27 15:04:46.086  8267  8286 D bt_vendor: op for 0
07-27 15:04:46.086  8267  8286 D bt_upio : upio_set_bluetooth_power(on: 1)
07-27 15:04:46.086  8267  8286 D bt_upio : is_emulator_context : 0
07-27 15:04:46.086  8267  8286 D bt_upio : is_rfkill_disabled ? [0]
,07-27 15:04:46.096  8267  8317 D bt_vendor: op for 3
07-27 15:04:46.096  8267  8317 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 15:04:46.096  8267  8317 I bt_userial_vendor: userial_vendor_open():UART is setup
07-27 15:04:46.096  8267  8317 I bt_userial_vendor: device fd = 65 open
,07-27 15:04:46.096  8267  8317 D bt_vendor: op for 1
07-27 15:04:46.096  8267  8317 E bt_hwcfg: Start CFG HW, HCI reset
07-27 15:04:46.096  8267  8318 D bt_userial: Entering userial_read_thread()
,07-27 15:04:46.176  8267  8317 E bt_hwcfg: Read Local Name after HCI reset
,07-27 15:04:46.196  8267  8317 D bt_hwcfg: Chipset BCM4335C0
07-27 15:04:46.196  8267  8317 D bt_hwcfg: Target name = [BCM4335C0]
07-27 15:04:46.196  8267  8317 I bt_hwcfg: module_type[semco].
07-27 15:04:46.196  8267  8317 I bt_hwcfg: not ZERO...
07-27 15:04:46.196  8267  8317 I bt_hwcfg: module_type[semco] is invalid.
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG . BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: fw ver (org)0.0
07-27 15:04:46.196  8267  8317 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-27 15:04:46.196  8267  8317 E bt_hwcfg: Remove module rev, try again BCM4335
07-27 15:04:46.196  8267  8317 D bt_hwcfg: Target name = [BCM4335]
07-27 15:04:46.196  8267  8317 I bt_hwcfg: module_type[semco].
07-27 15:04:46.196  8267  8317 I bt_hwcfg: not ZERO...
07-27 15:04:46.196  8267  8317 I bt_hwcfg: module_type[semco] is invalid.
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG . BCM4335
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG .. BCM4335
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-27 15:04:46.196  8267  8317 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-27 15:04:46.196  8267  8317 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-27 15:04:46.196  8267  8317 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-27 15:04:46.196  8267  8317 E bt_hwcfg: ORG patchram base 0111
07-27 15:04:46.196  8267  8317 E bt_hwcfg: ORG patchram minor 0559
07-27 15:04:46.196  8267  8317 E bt_hwcfg: fw ver (org)111.559
07-27 15:04:46.196  8267  8317 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-27 15:04:46.216  8267  8317 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 15:04:46.216  8267  8317 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 15:04:46.656  8267  8317 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 15:04:46.656  8267  8317 I bt_hwcfg: FW Download delta = 488292
,07-27 15:04:46.656  8267  8317 D bt_hwcfg: Settlement delay -- 100 ms
07-27 15:04:46.656  8267  8317 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 15:04:46.766  8267  8317 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 15:04:46.806  8267  8317 I bt_hwcfg: vendor lib fwcfg completed
,07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_GAP
,07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_SAP
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_GATT
,07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 15:04:46.816  8267  8313 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-27 15:04:47.046  8267  8313 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-27 15:04:47.056  8267  8313 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xb3a18b5d 
,07-27 15:04:47.056  8267  8313 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3a18b5d 
,07-27 15:04:47.266  8267  8290 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-27 15:04:47.266  8267  8290 E bt-btif : Calling BTA_HhEnable
,07-27 15:04:47.276  8267  8290 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-27 15:04:47.276  8267  8290 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
07-27 15:04:47.276  8267  8290 E BluetoothServiceJni: populateRssiValuesNative
07-27 15:04:47.276  8267  8290 I bluedroid: getModelRssiValues
07-27 15:04:47.276  8267  8290 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-27 15:04:47.276  8267  8290 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 15:04:47.276  8267  8290 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 15:04:47.276   790   790 D SettingsProvider: name = bluetooth_name
,07-27 15:04:47.276  8267  8290 D BluetoothAdapterProperties: Scan Mode:20
,07-27 15:04:47.276  8267  8290 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 15:04:47.276  8267  8290 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
07-27 15:04:47.276  8267  8290 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-27 15:04:47.276  8267  8290 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
07-27 15:04:47.276  8267  8290 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,07-27 15:04:47.276  8267  8290 E bt-btif : btif_sock_init: !vhci_init
07-27 15:04:47.276  8267  8290 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-27 15:04:47.276  8267  8317 D bt_vendor: op for 2
,07-27 15:04:47.276  8267  8317 D bt_vendor: op for 6
07-27 15:04:47.276  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.276  8267  8290 D IOP_DB_BT: db_open: db_open : handle 3017056272l, read 14063 bytes onto local cache
,07-27 15:04:47.286  8267  8317 D bt_upio : proc btwrite assertion
,07-27 15:04:47.286  8267  8290 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-27 15:04:47.286  8267  8290 D IOP_DB_BT: db_query: result 1
,07-27 15:04:47.286  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.286  8267  8317 D bt_upio : BT_WAKE is asserted already
07-27 15:04:47.286  8267  8290 I         : iop_db_open: iop_db_open status 0
,07-27 15:04:47.286  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.286  8267  8317 D bt_upio : BT_WAKE is asserted already
07-27 15:04:47.286  8267  8290 D bte_conf: Device ID record 1 : primary
07-27 15:04:47.286  8267  8290 D bte_conf:   vendorId            = 0075
,07-27 15:04:47.286  8267  8290 D bte_conf:   vendorIdSource      = 0001
07-27 15:04:47.286  8267  8290 D bte_conf:   product             = 0100
07-27 15:04:47.286  8267  8290 D bte_conf:   version             = 0200
07-27 15:04:47.286  8267  8290 D bte_conf:   clientExecutableURL = 
,07-27 15:04:47.286  8267  8290 D bte_conf:   serviceDescription  = 
07-27 15:04:47.286  8267  8290 D bte_conf:   documentationURL    = 
07-27 15:04:47.286  8267  8290 D bte_conf: bte_load_did_conf no section named DID2.
,07-27 15:04:47.286  8267  8286 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,07-27 15:04:47.286  8267  8286 D BluetoothAdapterProperties: ScanMode =  20
07-27 15:04:47.286  8267  8286 D BluetoothAdapterProperties: State =  11
,07-27 15:04:47.286   790  1266 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 15:04:47.286  8267  8286 D BluetoothAdapterProperties: Setting state to 12
,07-27 15:04:47.286  8267  8286 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 15:04:47.296  8267  8290 D BluetoothAdapterProperties: Scan Mode:21
,07-27 15:04:47.296  8267  8290 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 15:04:47.296   790  1635 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-27 15:04:47.296   790  1635 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 15:04:47.296   790  1635 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 15:04:47.296   790  1635 D SettingsProvider: selectionArgs: false
07-27 15:04:47.296   790  1635 D SettingsProvider: selectionArgs: 1002
,07-27 15:04:47.296   790  1635 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 15:04:47.296   790  1635 D SettingsProvider: ret = -1
,07-27 15:04:47.296  8267  8286 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 15:04:47.296  8267  8286 D BluetoothAdapterService: updateAdapterState state is 12
,07-27 15:04:47.296   790  1635 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 15:04:47.296   790  1635 D ActivityManager: caller:android.app.ApplicationThreadProxy@17a1061, r.packageName :com.android.bluetooth
,07-27 15:04:47.296  8267  8317 E bt_h4   : vendor lib postload completed
,07-27 15:04:47.316  8267  8286 D BluetoothAdapterService: Autoconnection is available 
,07-27 15:04:47.316  8267  8286 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 15:04:47.316  8267  8286 D BluetoothAdapterService: starting service from this receiver
,07-27 15:04:47.316   790   806 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:47.316   790   806 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c292847, r.packageName :com.android.bluetooth
,07-27 15:04:47.316  8267  8286 I BluetoothAdapterState: Entering On State from state = 11
,07-27 15:04:47.316  1315  1328 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 15:04:47.316  8267  8267 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:47.326  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:47.326  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:47.336  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.336  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.336  8267  8290 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 15:04:47.336  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.336  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.336  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.336  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.336  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.346  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.346  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.346  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.346  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.346  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.346  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.346  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.346  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.346  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.346  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.346  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.356  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.356  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.356  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.356  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.356  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.356  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.356  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.356  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.356  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.356  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.356  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.356  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.376  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.376  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.376  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.376  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.376  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.376  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.376  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.376  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.376  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.376  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.386  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.386  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.386  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.386  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.386  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.386  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.386  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.386  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.386  8267  8317 D bt_vendor: op for 7
,07-27 15:04:47.386  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.386  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.386  8267  8317 D bt_upio : BT_WAKE is asserted already
,07-27 15:04:47.436   790  1058 I art     : Explicit concurrent mark sweep GC freed 52349(2MB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 37MB/53MB, paused 1.214ms total 115.273ms
,07-27 15:04:47.436   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-27 15:04:47.446  8267  8267 I BluetoothPbapService: Handler(): got msg=1
,07-27 15:04:47.446   790  1686 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 15:04:47.446  8267  8342 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-27 15:04:47.446  1315  1315 D BluetoothMap: Proxy object connected
07-27 15:04:47.446  1315  1315 D MapProfile: Bluetooth service connected
,07-27 15:04:47.456   790  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.456  8267  8342 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 15:04:47.456  1407  1419 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:47.456  8267  8342 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
07-27 15:04:47.456   790  1058 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 15:04:47.456  8267  8342 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 15:04:47.456  8267  8342 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 15:04:47.456  8267  8342 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@393daec
07-27 15:04:47.456  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.456  8267  8317 D bt_upio : BT_WAKE is asserted already
07-27 15:04:47.456   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:47.456  8267  8342 D BluetoothSocket: channel: 19
07-27 15:04:47.456   790   790 D BluetoothA2dp: Proxy object connected
07-27 15:04:47.456  8267  8342 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 15:04:47.456   790  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.456  3186  3202 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:47.456   790  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.456  1407  3082 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:47.456   790  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.456  1407  7722 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 15:04:47.456   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.456   790  1058 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:47.466  1315  7720 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 15:04:47.466   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-27 15:04:47.466  1315  1315 D BluetoothInputDevice: Proxy object connected
07-27 15:04:47.466  1315  1315 D HidProfile: Bluetooth service connected
,07-27 15:04:47.466   790  1058 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.466  7686  7695 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:47.466   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.466  1315  1328 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 15:04:47.466  1315  1315 D HeadsetProfile: Bluetooth service connected
07-27 15:04:47.466  1315  1336 D BluetoothPan: Binding service...
,07-27 15:04:47.466   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-27 15:04:47.466  3186  7721 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:47.476  1315  1315 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 15:04:47.476  1315  1315 D PanProfile: Bluetooth service connected
,07-27 15:04:47.476   790  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:47.476  3186  3186 D BluetoothA2dp: Proxy object connected
,07-27 15:04:47.476  1315  1328 D Bluetoothsap: onBluetoothStateChange: up=true
07-27 15:04:47.476  1315  1328 D Bluetoothsap: Binding service...
,07-27 15:04:47.476  1315  1328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-27 15:04:47.476   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-27 15:04:47.476  1315  1328 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-27 15:04:47.476  8267  8275 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 15:04:47.476  1315  1336 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:47.476  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object connected
07-27 15:04:47.476  1315  1315 D SapProfile: Bluetooth service connected
07-27 15:04:47.476  1315  1315 D Bluetoothsap: getConnectedDevices()
,07-27 15:04:47.476   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 15:04:47.476  1315  1315 D BluetoothA2dp: Proxy object connected
,07-27 15:04:47.476   790  1058 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 15:04:47.476  1427  1682 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 15:04:47.476  1315  1315 D A2dpProfile: Bluetooth service connected
07-27 15:04:47.476  1315  7720 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 15:04:47.476   790  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-27 15:04:47.486   790  1058 D BluetoothPan: Binding service...
,07-27 15:04:47.486   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-27 15:04:47.486   790   790 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 15:04:47.486   790  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-27 15:04:47.486  1315  1315 D BluetoothPbap: Proxy object connected
07-27 15:04:47.486  1315  1315 D PbapServerProfile: Bluetooth service connected
,07-27 15:04:47.486  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-27 15:04:47.486  7686  7686 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:47.486  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:47.486   790   790 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:47.486   790   790 I InputMethodManagerService: [BT Setting State] State =12
07-27 15:04:47.486   790   790 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-27 15:04:47.486   790  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 15:04:47.486   790  1145 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:47.486   790  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@3de0704, r.packageName :com.google.android.gms
,07-27 15:04:47.486  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:47.486  1739  1739 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 15:04:47.486  1407  1407 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@10ca4abc, true
,07-27 15:04:47.496  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 15:04:47.496  1407  1407 D BluetoothHeadset: registerMessageListener
,07-27 15:04:47.496  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:47.496  8267  8331 D HeadsetService: registerMessageListener
,07-27 15:04:47.496  8267  8331 D HeadsetService: registerMessageListener
07-27 15:04:47.496  8267  8295 D HeadsetStateMachine: Disconnected process message: 70
,07-27 15:04:47.496  8267  8295 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@11304eb5
,07-27 15:04:47.496  1197  1594 D BluetoothTile:  handleUpdatestate:false name:null
07-27 15:04:47.496  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 15:04:47.496  1407  1407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-27 15:04:47.496  1407  1407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-27 15:04:47.496  1315  1315 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-27 15:04:47.496  1315  1315 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-27 15:04:47.496  8267  8295 D HeadsetStateMachine: Disconnected process message: 9
,07-27 15:04:47.496   790  1458 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 15:04:47.496  8267  8295 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-27 15:04:47.496   790  1648 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-27 15:04:47.496  8267  8345 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-27 15:04:47.496  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 15:04:47.496   310  4662 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-27 15:04:47.496   310  4662 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-27 15:04:47.496   310  4662 V voice   : voice_set_parameters: exit with code(-2)
07-27 15:04:47.496   310  4662 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-27 15:04:47.496   310  4662 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 15:04:47.496   310  4662 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 15:04:47.496   310  4662 V audio_hw_primary: adev_set_parameters: exit
07-27 15:04:47.496  8267  8295 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-27 15:04:47.496  8267  8345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 15:04:47.506  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.506  8267  8317 D bt_upio : BT_WAKE is asserted already
07-27 15:04:47.506  8267  8345 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
07-27 15:04:47.506  8267  8345 D BluetoothSocket: bindListen(), new LocalSocket 
,07-27 15:04:47.506  8267  8345 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 15:04:47.506  8267  8345 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e8ad94a
07-27 15:04:47.506  8267  8345 D BluetoothSocket: channel: 5
,07-27 15:04:47.506  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 15:04:47.506   790  1458 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 15:04:47.506   790  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d1a0db3, r.packageName :com.android.settings
,07-27 15:04:47.506  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:47.516  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 15:04:47.516  8267  8267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ae3473
,07-27 15:04:47.516  8267  8267 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 15:04:47.516   790  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 15:04:47.516   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@10f62e9, r.packageName :com.android.bluetooth
,07-27 15:04:47.546   790  1474 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 15:04:47.556  8267  8352 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 15:04:47.556  8267  8352 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
07-27 15:04:47.556  8267  8352 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 15:04:47.556  8267  8352 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 15:04:47.556  8267  8317 D bt_vendor: op for 7
07-27 15:04:47.556  8267  8352 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@209c9b84
07-27 15:04:47.556  8267  8317 D bt_upio : BT_WAKE is asserted already
07-27 15:04:47.556  8267  8352 D BluetoothSocket: channel: 12
07-27 15:04:47.556  8267  8352 I BtOppRfcommListener: Accept thread started.
,07-27 15:04:47.616  1834  1834 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:47.616   790  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:47.616   790  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@39afb07a, r.packageName :com.google.android.gms
,07-27 15:04:47.616  1834  8355 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 15:04:47.626  1834  1834 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 15:04:47.636   790  1266 D ActivityManager: caller:android.app.ApplicationThreadProxy@30e3f407, r.packageName :com.google.android.gms
,07-27 15:04:47.636  1834  8355 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:47.646  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:47.646  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:47.646  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:47.646  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@243c5449 added. We now have 8 listener(s)
07-27 15:04:47.646  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:47.646  7530  7607 I WifiManager: packageName : com.test.thalitest
,07-27 15:04:47.646   790  1648 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 15:04:47.646   790  1648 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 15:04:47.646   790  1648 D SecContentProvider2: mCursor = null
,07-27 15:04:47.656   790  1648 D WifiService: setWifiEnabled: false pid=7530, uid=10079
,07-27 15:04:47.656   790  1648 D SettingsProvider: name = wifi_on
,07-27 15:04:47.656  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:47.656  7530  7607 I WifiManager: packageName : com.test.thalitest
07-27 15:04:47.656   790   805 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 15:04:47.656   790   805 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 15:04:47.656   790   805 D SecContentProvider2: mCursor = null
,07-27 15:04:47.656   790   805 D WifiService: setWifiEnabled: true pid=7530, uid=10079
07-27 15:04:47.656   790   805 W ActivityManager: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-27 15:04:47.656   790   805 W WifiService: Failed getting userId using ActivityManagerNative
07-27 15:04:47.656   790   805 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7530, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 15:04:47.656   790   805 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 15:04:47.656   790   805 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 15:04:47.656   790   805 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 15:04:47.656   790   805 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 15:04:47.656   790   805 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 15:04:47.656   790   805 D SettingsProvider: name = wifi_on
,07-27 15:04:47.666   790  1150 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 15:04:47.666   298  1054 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-27 15:04:47.666   298  1054 I WifiHW  : module is semco
07-27 15:04:47.666   298  1054 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-27 15:04:47.666   298  1054 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-27 15:04:47.666   298  1054 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 15:04:47.666   298  1054 D SoftapController: Softap fwReload - Ok
,07-27 15:04:47.666   298  1054 D CommandListener: Setting iface cfg
07-27 15:04:47.666   298  1054 D CommandListener: Trying to bring down wlan0
,07-27 15:04:47.666   298  1054 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:47.666   790  1150 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 15:04:47.696  8359  8359 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,07-27 15:04:47.696  8359  8359 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 15:04:47.706  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 15:04:47.706  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 15:04:47.706   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8359
07-27 15:04:47.706   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 15:04:47.706  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,07-27 15:04:47.706  8359  8359 I wpa_supplicant: ssSupport state is = 1
07-27 15:04:47.706  8359  8359 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-27 15:04:47.706  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 15:04:47.706   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8359
07-27 15:04:47.706   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-27 15:04:47.736   790  1061 I PowerManagerService: [PWL] Off : 105s ago
07-27 15:04:47.736   790  1061 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-27 15:04:47.736   790  1061 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-27 15:04:47.736   790  1061 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=790, ws=null) (elapsedTime=20145)
07-27 15:04:47.736   790  1061 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=8267, ws=null) (elapsedTime=916)
07-27 15:04:47.736   790  1061 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=233)
,07-27 15:04:47.766   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:47.776  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:47.776   790  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 15:04:47.776  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:47.776  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-27 15:04:47.776  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:47.776  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,07-27 15:04:47.776  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:47.776  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 15:04:47.776  1197  1197 D HotspotTile: onReceive : 2, 0
,07-27 15:04:47.776  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:47.776   790  1150 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 15:04:47.786  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:47.786   790  1266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:47.786  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:47.786  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:47.786  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 15:04:47.796  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:47.966   379   379 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-27 15:04:48.016   303   303 E SMD     : DCD ON
,07-27 15:04:48.226  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-27 15:04:48.296  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 15:04:48.296  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-27 15:04:48.296   379   379 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8359
07-27 15:04:48.296   379   379 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-27 15:04:48.296  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 15:04:48.296  8359  8359 I wpa_supplicant: ssSupport state is = 1
07-27 15:04:48.296  8359  8359 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-27 15:04:48.296  8359  8359 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:48.296  8359  8359 E wpa_supplicant: SIM READ ERROR
07-27 15:04:48.296  8359  8359 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:48.296  8359  8359 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:48.296  8359  8359 E wpa_supplicant: SIM READ ERROR
,07-27 15:04:48.296  8359  8359 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:48.296  8359  8359 I wpa_supplicant: wpa_default_ap_write_once
07-27 15:04:48.296  8359  8359 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 15:04:48.296  8359  8359 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-27 15:04:48.296  8359  8359 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-27 15:04:48.296  8359  8359 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:48.296  8359  8359 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-27 15:04:48.296  8359  8359 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:48.946   790  1153 E Tethering: No numeric data
,07-27 15:04:48.946   790  1153 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 15:04:48.946   790  1147 V NetworkStats: performPollLocked(flags=0x1)
07-27 15:04:48.946   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:48.946   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 15:04:48.946   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:48.946  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-27 15:04:48.946  1197  1197 D HotspotTile: updateTetherState():false, false
,07-27 15:04:48.946   790  1147 V NetworkStats: performPollLocked() took 3ms
07-27 15:04:48.946   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:48.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:48.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:48.956  8359  8359 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-27 15:04:48.966  8359  8359 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-27 15:04:48.966  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 15:04:48.966  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 15:04:48.966   379   379 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8359
07-27 15:04:48.966   379   379 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-27 15:04:48.966  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 15:04:48.966  8359  8359 I wpa_supplicant: ssSupport state is = 1
,07-27 15:04:48.966  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 15:04:48.966  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 15:04:48.966   379   379 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8359
07-27 15:04:48.966   379   379 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-27 15:04:48.966  8359  8359 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,07-27 15:04:48.966  8359  8359 I wpa_supplicant: ssSupport state is = 1
07-27 15:04:48.966  8359  8359 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:48.966  8359  8359 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:48.966  8359  8359 E wpa_supplicant: SIM READ ERROR
,07-27 15:04:48.966  8359  8359 I wpa_supplicant: wpa_default_ap_write_once
07-27 15:04:48.966  8359  8359 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 15:04:48.966  8359  8359 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:48.986  8359  8359 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,07-27 15:04:48.986  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-27 15:04:48.986  8359  8359 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,07-27 15:04:48.986  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-27 15:04:48.986   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-27 15:04:48.986   790  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 15:04:48.986  8359  8359 I wpa_supplicant: HOTSPOT20_ENABLE called
07-27 15:04:48.986  8359  8359 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 15:04:48.986  8359  8359 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 15:04:48.986  8359  8359 E wpa_supplicant: SIM READ ERROR
07-27 15:04:48.986  8359  8359 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 15:04:49.016   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:49.016  8359  8359 I wpa_supplicant: Skip scan - bUseNetwork false
07-27 15:04:49.016   790  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-27 15:04:49.016  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:49.016  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:49.016  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:49.016  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-27 15:04:49.016  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:49.016  1197  1594 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 15:04:49.016  1197  1197 D HotspotTile: onReceive : 3, 0
,07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:49.016  7530  7530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:49.016  7530  7530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:49.016   790  1150 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 15:04:49.016   790  1150 D WifiConfigStore: Loading config and enabling all networks 
,07-27 15:04:49.016  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:49.026  7070  7070 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 15:04:49.026   790  1648 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:49.026  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 15:04:49.026  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:49.026  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:49.026  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:49.026   790  1150 E WifiConfigStore: Not a HS20
,07-27 15:04:49.046   790  1150 E WifiConfigStore: Not a HS20
,07-27 15:04:49.046   790  1150 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 15:04:49.046   790  1150 D WifiNative-HAL: callSECApiInt - ID [65]
,07-27 15:04:49.056   790  1150 D WifiNative-HAL: callSECApiBoolean - ID [13]
,07-27 15:04:49.056  8359  8359 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 15:04:49.056  8359  8359 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 15:04:49.056  8267  8317 D bt_vendor: op for 7
07-27 15:04:49.056  8359  8359 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 15:04:49.056  8359  8359 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 15:04:49.056  8359  8359 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-27 15:04:49.056  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-27 15:04:49.056  8359  8359 I wpa_supplicant: First Scan Start
,07-27 15:04:49.056  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:49.056  8359  8359 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-27 15:04:49.056   790  1150 D WifiNative-HAL: Setting external_sim to 1
,07-27 15:04:49.056   790  1150 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 15:04:49.056   790  1150 I WifiNative-HAL: startHal
07-27 15:04:49.056   790  1150 E wifi    : getStaticLongField sWifiHalHandle 0x931b986c
07-27 15:04:49.056   790  1150 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0xa01b22
07-27 15:04:49.056   790  1150 I WifiNative-HAL: Could not start hal
,07-27 15:04:49.076   790  1150 E native  : do suspend true
,07-27 15:04:49.076   790  1149 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 15:04:49.076   298  1054 D CommandListener: Setting iface cfg
07-27 15:04:49.076   298  1054 D CommandListener: Trying to bring up p2p0
07-27 15:04:49.076   790   790 D WifiScanningService: SCAN_AVAILABLE : 3
,07-27 15:04:49.086   790  1149 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 15:04:49.086   790   790 D RttService: SCAN_AVAILABLE : 3
07-27 15:04:49.086   790  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:49.086   790  1149 D WifiP2pService: P2pEnablingState
07-27 15:04:49.086   790  1167 I WifiNative-HAL: startHal
07-27 15:04:49.086   790  1149 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-27 15:04:49.086   790  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9abc199c
07-27 15:04:49.086   790  1149 D WifiP2pService: P2p socket connection successful
07-27 15:04:49.086   790  1149 D WifiP2pService: P2pEnabledState
07-27 15:04:49.086   790  1168 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 15:04:49.086   790  1167 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x901936
07-27 15:04:49.086   790  1167 I WifiNative-HAL: Could not start hal
07-27 15:04:49.086   790  1167 E WifiScanningService: could not start HAL
07-27 15:04:49.086   790  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-27 15:04:49.086   790  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,07-27 15:04:49.086   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:49.086   790  1059 D WifiDisplayController: disconnect
07-27 15:04:49.086   790  1059 D WifiDisplayController: updateConnection
07-27 15:04:49.086   790  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 15:04:49.086   790   790 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-27 15:04:49.086   790  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 15:04:49.086   790  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-27 15:04:49.086  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 15:04:49.086  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 15:04:49.086   790  1474 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 15:04:49.086  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 15:04:49.096   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:49.096   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-27 15:04:49.096   790  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:49.096   790  1059 D WifiDisplayAdapter: onP2pDisconnected
07-27 15:04:49.096   790  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
,07-27 15:04:49.096   790  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
07-27 15:04:49.096   790  1150 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-27 15:04:49.096   790  1150 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-27 15:04:49.096   790  1150 E WifiNative-HAL: invaild command id : 215
,07-27 15:04:49.096  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:49.096  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 15:04:49.096   790  1704 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:49.096  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 15:04:49.096   790  1267 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:49.096  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:49.096  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-27 15:04:49.096  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 15:04:49.096  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:49.106  7387  7387 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 15:04:49.106  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:49.106  7744  7744 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-27 15:04:49.106  7744  7744 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 15:04:49.106  7744  7744 D WifiDirectBR: stopServiceTest : false
,07-27 15:04:49.126  8359  8359 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 15:04:49.126   790  1149 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 15:04:49.126   790  1149 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,07-27 15:04:49.126   790  1059 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-27 15:04:49.126   790  1059 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-27 15:04:49.126   790  1059 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 15:04:49.126   790  1059 D WifiDisplayController:  secondary type: null
07-27 15:04:49.126   790  1059 D WifiDisplayController:  wps: 0
07-27 15:04:49.126   790  1059 D WifiDisplayController:  grpcapab: 0
07-27 15:04:49.126   790  1059 D WifiDisplayController:  devcapab: 0
07-27 15:04:49.126   790  1059 D WifiDisplayController:  status: 3
07-27 15:04:49.126   790  1059 D WifiDisplayController:  wfdInfo: null
07-27 15:04:49.126   790  1059 D WifiDisplayController:  groupownerAddress: null
07-27 15:04:49.126   790  1059 D WifiDisplayController:  GOdeviceName: null
07-27 15:04:49.126   790  1059 D WifiDisplayController:  interfaceAddress: 
07-27 15:04:49.126   790  1059 D WifiDisplayController:  SConnectInfo : null
07-27 15:04:49.126   790  1149 D WifiP2pService: DeviceAddress: ea:28:a3
,07-27 15:04:49.156  8359  8359 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 15:04:49.156   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:49.156   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:49.156   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:49.156   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:49.166   790  1149 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-27 15:04:49.166   790  1149 D WifiP2pService: InactiveState
,07-27 15:04:49.166   790  1149 D WifiP2pService: InactiveState{ what=143376 }
07-27 15:04:49.166   790  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 15:04:49.176  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 15:04:49.176   790  1149 D WifiP2pService: InactiveState{ what=143376 }
07-27 15:04:49.176   790  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 15:04:49.286  8267  8330 D bt_upio : ..proc_btwrite_timeout..
,07-27 15:04:49.366   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:49.676  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:49.676  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:49.686  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-27 15:04:49.696  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-27 15:04:49.696  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@110d2063 Bundle[{}]
,07-27 15:04:49.696  7530  7607 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 15:04:49.696  7530  7607 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 15:04:49.696  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 15:04:49.696  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-27 15:04:49.696  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-27 15:04:49.696  7530  7607 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 15:04:49.706  7530  7607 I System.out: Running OutgoingSocketThread
,07-27 15:04:49.716  7530  8384 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1327)
,07-27 15:04:49.726  7530  8384 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38688
,07-27 15:04:49.726  7530  8384 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-27 15:04:49.866  8359  8359 I wpa_supplicant: nl80211: Received scan results (20 BSSes)
07-27 15:04:49.866  8359  8359 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 15:04:49.866  8359  8359 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-27 15:04:49.866  8359  8359 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-27 15:04:49.866  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-27 15:04:49.886   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 15:04:49.886   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:49.936  8359  8359 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-27 15:04:49.936  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-27 15:04:49.936  8359  8359 I wpa_supplicant: Associated with F4.99.3E
07-27 15:04:49.936  8359  8359 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-27 15:04:49.936  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-27 15:04:49.946   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 15:04:49.946   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:49.946   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:49.946   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:49.956  8359  8359 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-27 15:04:49.956  8359  8359 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-27 15:04:49.956  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-27 15:04:49.956  8359  8359 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:49.956  8359  8359 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-27 15:04:49.956  8359  8359 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
07-27 15:04:49.966  8359  8359 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 15:04:49.966  8359  8359 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-27 15:04:49.966   790  1150 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-27 15:04:49.966  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:49.966  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:49.976   790  1150 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-27 15:04:49.976   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:49.976   790  1152 D ConnectivityService: Got NetworkAgent Messenger
07-27 15:04:49.976   790  1152 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,07-27 15:04:49.976   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:49.976   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:49.976   790  1152 D ConnectivityService: NetworkAgent connected
,07-27 15:04:49.986  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 15:04:49.986   790  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 15:04:49.986  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 15:04:49.986   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:49.986  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:49.986   790   806 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:49.986  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:49.986  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:49.986  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 15:04:49.986  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:49.996   298  1054 D CommandListener: Setting iface cfg
,07-27 15:04:50.006   790  1150 E WifiStateMachine: Start Dhcp Watchdog 3
,07-27 15:04:50.006   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 15:04:50.006   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:50.006   790  1266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:50.016  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:50.016  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:50.016   790  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-27 15:04:50.016   790  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 15:04:50.016   790  1150 D SecContentProvider2: mCursor = null
,07-27 15:04:50.026  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:50.096   790  1150 E native  : do suspend false
,07-27 15:04:50.106   790  1149 D WifiP2pService: InactiveState{ what=143375 }
,07-27 15:04:50.106   790  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 15:04:50.316  8403  8403 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 15:04:50.316  8403  8403 I dhcpcd  : version 5.5.6 starting
,07-27 15:04:50.316  8403  8403 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 15:04:50.366   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:50.386  8403  8403 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 15:04:50.386  8403  8403 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-27 15:04:50.386  8403  8403 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-27 15:04:50.386  8403  8403 I dhcpcd  : bssid match
07-27 15:04:50.386  8403  8403 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-27 15:04:50.416  8403  8403 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-27 15:04:50.416  8403  8403 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-27 15:04:50.426   790  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-27 15:04:50.716   790  1150 E native  : do suspend true
,07-27 15:04:50.716  7530  7607 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1328)
,07-27 15:04:50.716  7530  7607 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1328)
07-27 15:04:50.716  7530  7607 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1328)
07-27 15:04:50.716  7530  7607 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1328)
,07-27 15:04:50.716   790  1149 D WifiP2pService: InactiveState{ what=143375 }
07-27 15:04:50.716   790  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 15:04:50.726   790  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-27 15:04:50.726  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:50.726  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:50.726   790  1150 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 15:04:50.726   790  1150 E WifiStateMachine: VerifyingLinkState enter
,07-27 15:04:50.726  7530  7607 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1333)
,07-27 15:04:50.726  7530  7607 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 1333)
07-27 15:04:50.726  7530  7607 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1333)
07-27 15:04:50.726   790  1150 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 15:04:50.726   790  1152 E ConnectivityService: updateNetworkInfo()
,07-27 15:04:50.726  7530  7607 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 1334)
07-27 15:04:50.726   790  1152 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 15:04:50.726   790  1152 D ConnectivityService: Adding iface wlan0 to network 504
07-27 15:04:50.726  7530  7607 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1336)
,07-27 15:04:50.736  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:50.736  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d4514e added. We now have 2 listener(s)
,07-27 15:04:50.736  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:50.736  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.736  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.736  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.736  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2380926f added. We now have 9 listener(s)
07-27 15:04:50.736  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:50.736   790  1162 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-27 15:04:50.736   790  1162 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 15:04:50.736   790  1162 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 15:04:50.736   790  1162 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 15:04:50.736   790  1162 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 15:04:50.746  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:50.746  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:50.746  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:50.746  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:50.756  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:50.756  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:50.756  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 15:04:50.756  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.756  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.756  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 15:04:50.756   790  1150 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
07-27 15:04:50.756  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ecec05 added. We now have 3 listener(s)
,07-27 15:04:50.756  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 15:04:50.766  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 15:04:50.766  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 15:04:50.766  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 15:04:50.766  1315  1315 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 15:04:50.766   790   790 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-27 15:04:50.766  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 15:04:50.776  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.776   790  1152 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-27 15:04:50.776  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.776  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca8345a added. We now have 10 listener(s)
07-27 15:04:50.776  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:50.776  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:50.776  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 15:04:50.776   790   790 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-27 15:04:50.776   790   790 I WifiTrafficPoller: mBoosterFLAG : 0
07-27 15:04:50.776   790   790 I WifiTrafficPoller: current booster mode : FullMode
07-27 15:04:50.776   790   790 D WifiNative-HAL: callSECApiVoid - ID [212]
07-27 15:04:50.776  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 15:04:50.776  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.776  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.776  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:50.776  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.776  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d4514e removed from the list
,07-27 15:04:50.776  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.776  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2380926f removed from the list
07-27 15:04:50.776  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 15:04:50.776   790  1152 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,07-27 15:04:50.776   790  1152 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
07-27 15:04:50.776  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.776   790  1152 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 15:04:50.776   790  1152 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-27 15:04:50.776   790  1152 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
07-27 15:04:50.776   790  1150 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 15:04:50.776   298  1054 V         : QcRouteController
,07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:50.776  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.776  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 15:04:50.786  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.786  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2380926f not in the list
07-27 15:04:50.786  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.786  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca8345a removed from the list
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.786  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.786  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ecec05 removed from the list
,07-27 15:04:50.786  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:50.786  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2de68b added. We now have 2 listener(s)
,07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.786  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.786  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294bb368 added. We now have 9 listener(s)
07-27 15:04:50.786  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:50.786  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:50.796  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:50.806  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:50.806   790  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:50.806  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:50.806  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:50.806  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:50.806  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a53c26 added. We now have 3 listener(s)
07-27 15:04:50.806   298  1054 V         : QcRouteController
,07-27 15:04:50.816  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.816  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:50.816  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.816  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.816  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.816  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b126067 added. We now have 10 listener(s)
07-27 15:04:50.816  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:50.816  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:50.816  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:50.816  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:50.816  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 15:04:50.816  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.816  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 15:04:50.816  7530  7607 E BluetoothAdapter: bluetooth le advertising not supported
07-27 15:04:50.816  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:50.816  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 15:04:50.816  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 15:04:50.816  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 15:04:50.826  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:50.826  7530  7607 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:50.826  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 15:04:50.826  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 15:04:50.826  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 15:04:50.826  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:50.826  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.826  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:50.826  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.826  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2de68b removed from the list
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.826  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294bb368 removed from the list
07-27 15:04:50.826  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 15:04:50.826  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.826  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.826  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.826  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294bb368 not in the list
07-27 15:04:50.826   298  1054 V         : QcRouteController
07-27 15:04:50.826  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.826  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.826  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:50.826  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.826  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b126067 removed from the list
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.826  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.826  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.826  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 15:04:50.826  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a53c26 removed from the list
07-27 15:04:50.826  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 15:04:50.826  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18f4b2 added. We now have 2 listener(s)
,07-27 15:04:50.836  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 15:04:50.836  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.836  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.836  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.836  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34da9c03 added. We now have 9 listener(s)
07-27 15:04:50.836  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:50.836  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:50.836  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:50.836  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:50.846  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:50.846  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:50.846  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 15:04:50.846  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345e1b9 added. We now have 3 listener(s)
07-27 15:04:50.846  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.846  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 15:04:50.846  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.846  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 15:04:50.846   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:50.846  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 15:04:50.846   790  3246 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:50.846  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 15:04:50.846  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 15:04:50.846  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 15:04:50.846  1315  2699 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 15:04:50.846  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:50.846  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.846  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 15:04:50.846  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.846  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9da9fe added. We now have 10 listener(s)
07-27 15:04:50.846  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:50.846  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-27 15:04:50.846  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:50.846  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:50.846  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:50.846  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 15:04:50.846   298  1054 V         : QcRouteController
,07-27 15:04:50.866  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 15:04:50.866   790  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:50.866  7530  7607 E BluetoothAdapter: bluetooth le advertising not supported
,07-27 15:04:50.866  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-27 15:04:50.866  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 15:04:50.866  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 15:04:50.866  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 15:04:50.866  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 15:04:50.866  7530  7607 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-27 15:04:50.866  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:50.866   298  1054 V         : QcRouteController
07-27 15:04:50.866  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:50.866  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:50.866  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.866  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.866  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:50.866  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.866  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18f4b2 removed from the list
07-27 15:04:50.866  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 15:04:50.866  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34da9c03 removed from the list
07-27 15:04:50.866  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:50.866  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.866  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:50.866  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.876  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34da9c03 not in the list
07-27 15:04:50.876  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.876  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.876  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9da9fe removed from the list
,07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.876  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.876  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345e1b9 removed from the list
,07-27 15:04:50.876  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:50.876  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@159e075 added. We now have 2 listener(s)
,07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.876  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.876  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@526680a added. We now have 9 listener(s)
07-27 15:04:50.876  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:50.876  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:50.886  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:50.886  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:50.886  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:50.886  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:50.886  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 15:04:50.886  1315  1315 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 15:04:50.886  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:50.886  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3586c698 added. We now have 3 listener(s)
07-27 15:04:50.886  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.886   298  1054 V         : QcRouteController
,07-27 15:04:50.886  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.886  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:50.886   298  1054 V         : QcRouteController
,07-27 15:04:50.886  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.886  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.886   790  1474 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
07-27 15:04:50.886  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.886  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c750ef1 added. We now have 10 listener(s)
07-27 15:04:50.886  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:50.886  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:50.896  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 15:04:50.896  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:50.896  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 15:04:50.896  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 15:04:50.896  7530  7607 E BluetoothAdapter: bluetooth le advertising not supported
07-27 15:04:50.896   790  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:50.896  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:50.896  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 15:04:50.906  7070  7070 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 15:04:50.906  7530  7607 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-27 15:04:50.906  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:50.906  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:50.906  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.906  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.906  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@159e075 removed from the list
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.906  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@526680a removed from the list
07-27 15:04:50.906  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.906  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.906  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@526680a not in the list
07-27 15:04:50.906  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.906  7530  7607 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.906  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c750ef1 removed from the list
07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.906  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.906   298  1054 V         : QcRouteController
07-27 15:04:50.906  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:50.906  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.906  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3586c698 removed from the list
,07-27 15:04:50.906  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:50.906  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@386db444 added. We now have 2 listener(s)
,07-27 15:04:50.916  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 15:04:50.916  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.916  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.916  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.916  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@243aa92d added. We now have 9 listener(s)
07-27 15:04:50.916  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:50.916  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:50.916  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:50.916   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:50.916  7530  7607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:50.926  7530  7607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:50.926  7530  7607 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:50.926  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 15:04:50.926  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222a8bf3 added. We now have 3 listener(s)
07-27 15:04:50.926   790  1648 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=790
07-27 15:04:50.926  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:50.926  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.926  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b3d0b0 added. We now have 10 listener(s)
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:50.926  7530  7607 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:50.926  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:50.926  7530  7607 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:50.926  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.926  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:50.926  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.926  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@386db444 removed from the list
07-27 15:04:50.926  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.926  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@243aa92d removed from the list
,07-27 15:04:50.926  7530  7530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.926  7530  7607 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.926   790  1152 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
07-27 15:04:50.926   790  1152 D ConnectivityService: LTETest block dns file not exists
,07-27 15:04:50.926  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.926  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.926  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.926   790  1152 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-27 15:04:50.926  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.926   790  1152 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-27 15:04:50.926  7530  7607 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@243aa92d not in the list
07-27 15:04:50.926   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:50.926  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.926   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 15:04:50.926  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.926   790  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 15:04:50.926   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:50.926   790  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:50.926   790  1058 D EntConnectivity: Not allowed due to - mEnabled false
07-27 15:04:50.926   790  1152 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-27 15:04:50.926   790  1152 E ConnectivityService: updateNetworkInfo()
07-27 15:04:50.926   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:50.926   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:50.926   790  1152 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-27 15:04:50.926   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-27 15:04:50.926   790  1152 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:50.926   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:50.926   790  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:50.926   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 15:04:50.926   790  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:50.926   790  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:50.926   790  8385 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 15:04:50.936   790  1152 D ConnectivityService: currentScore = 0, newScore = 60
07-27 15:04:50.936   790  1152 D ConnectivityService:    accepting network in place of null
07-27 15:04:50.936   790  1152 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:50.936  1427  1427 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:50.936   790  1152 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 15:04:50.936   790  1152 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-27 15:04:50.936   790  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:50.936   790  1152 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:50.936   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:50.936   790  1153 D Tethering: MasterInitialState.processMessage what=3
07-27 15:04:50.936   790  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 15:04:50.936   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:50.936   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:50.936   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.936   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:50.936   790  1147 V NetworkStats: updateIfacesLocked()
07-27 15:04:50.936   790  1147 V NetworkStats: performPollLocked(flags=0x1)
,07-27 15:04:50.936   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
07-27 15:04:50.936   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:50.936   790  1152 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
07-27 15:04:50.946   790  1147 V NetworkStats: performPollLocked() took 3ms
07-27 15:04:50.946   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946   790  1058 D EntConnectivity: Not allowed due to - mEnabled false
07-27 15:04:50.946   790  1152 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-27 15:04:50.946   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:50.946   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:50.946   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:50.946   790  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:50.946   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:50.946  1197  1584 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 15:04:50.946   790  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-27 15:04:50.946  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:50.946  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:50.946  7530  7607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:50.946  7530  7607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b3d0b0 removed from the list
07-27 15:04:50.946  7530  7607 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:50.946  7530  7607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:50.946  7530  7607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:50.946  7530  7607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:50.946  7530  7607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222a8bf3 removed from the list
07-27 15:04:50.946   790  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:50.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946  4446  7480 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 15:04:50.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:50.946   790  1148 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-27 15:04:50.946  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 15:04:50.946  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 15:04:50.946  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 15:04:50.946  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-27 15:04:50.946  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-27 15:04:50.946  7530  7607 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:50.956   790   806 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: updateDataNetType()
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 15:04:50.956  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-27 15:04:50.956   790  1266 I AudioService: getStreamVolume 3 index 0
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:50.956  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 15:04:50.956  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 15:04:50.956  7530  8473 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1342, name: My test thread name)
07-27 15:04:50.956  7530  8473 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1342, thread name: My test thread name)
07-27 15:04:50.956  7530  8473 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1342, name: My test thread name)
07-27 15:04:50.966  7530  8474 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1344, name: My test thread name)
07-27 15:04:50.966  7530  8474 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1344, thread name: My test thread name)
07-27 15:04:50.966  7530  8474 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1344, name: My test thread name)
07-27 15:04:50.966  7530  7607 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-27 15:04:50.966  7530  7607 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-27 15:04:50.966  7530  7607 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-27 15:04:50.966  7530  7607 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-27 15:04:50.966  7530  7607 D com.test.thalitest.ThaliTestRunner: Total duration: 23784 ms
07-27 15:04:50.966  7530  7607 I jxcore-log: Total number of executed tests:  80
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.966  7530  7607 I jxcore-log: Number of passed tests:  80
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.966  7530  7607 I jxcore-log: Number of failed tests:  0
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.966  7530  7607 I jxcore-log: Number of ignored tests:  0
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.966  7530  7607 I jxcore-log: Total duration:  23784
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.966  7530  7607 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.966  7530  7607 I jxcore-log: Unit Test app is loaded
07-27 15:04:50.966  7530  7607 I jxcore-log: 
07-27 15:04:50.976  7530  7530 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 15:04:50.976  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.976  7530  7607 I jxcore-log: 
07-27 15:04:50.976  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.976  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.986  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.986  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
07-27 15:04:50.996  7530  7607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:50.996  7530  7607 I jxcore-log: 
,07-27 15:04:51.006  7530  7607 I jxcore-log: My device name is: samsung-SM-N9005
07-27 15:04:51.006  7530  7607 I jxcore-log: 
07-27 15:04:51.016   790  8385 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-27 15:04:51.016   303   303 E SMD     : DCD ON
,07-27 15:04:51.066   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 13:04:51 GMT], X-Android-Received-Millis=[1469624691081], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469624691053]}
,07-27 15:04:51.066   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 15:04:51.066   790  8385 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-27 15:04:51.066   790  1152 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,07-27 15:04:51.066   790  1152 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-27 15:04:51.066   790  1152 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:51.066   790  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:51.066   790  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:51.066   790  1152 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
07-27 15:04:51.066   790  1152 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-27 15:04:51.066   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:51.076   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:51.076   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:51.076   790  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:51.076   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:51.076   790  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:51.076  1197  1584 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-27 15:04:51.076   790  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 15:04:51.076  4446  7480 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-27 15:04:51.076   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: updateDataNetType()
07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 15:04:51.076  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-27 15:04:51.076  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 15:04:51.076  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 15:04:51.256  8475  8475 D AndroidRuntime: 
07-27 15:04:51.256  8475  8475 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-27 15:04:51.256  8475  8475 D AndroidRuntime: CheckJNI is OFF
,07-27 15:04:51.256  8475  8475 D AndroidRuntime: readGMSProperty: start
07-27 15:04:51.256  8475  8475 D AndroidRuntime: readGMSProperty: already setted!!
,07-27 15:04:51.256  8475  8475 D AndroidRuntime: readGMSProperty: end
07-27 15:04:51.256  8475  8475 D AndroidRuntime: addProductProperty: start
,07-27 15:04:51.366   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:51.386  8475  8475 E AffinityControl: AffinityControl: registerfunction enter
,07-27 15:04:51.406  8475  8475 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 15:04:51.426   790  3246 D PackageManager: START PACKAGE DELETE: observer{709155676}
07-27 15:04:51.426   790  3246 D PackageManager: pkg{<packageName>}
07-27 15:04:51.426   790  3246 D PackageManager: user{0}
07-27 15:04:51.426   790  3246 D PackageManager: caller{2000}
07-27 15:04:51.426   790  3246 D PackageManager: flags{2}
07-27 15:04:51.426   790  3246 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-27 15:04:51.426   790  3246 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-27 15:04:51.426   790  3246 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-27 15:04:51.426   790  3246 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-27 15:04:51.426   790  3246 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-27 15:04:51.426   790  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-27 15:04:51.426   790  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-27 15:04:51.426   790  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-27 15:04:51.426   790  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
,07-27 15:04:51.426   790  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-27 15:04:51.426   790  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,07-27 15:04:51.426   790  1021 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,07-27 15:04:51.436   790  1021 I ActivityManager: Killing 7530:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,07-27 15:04:51.436   790  1021 I ActivityManager:   Force finishing activity ActivityRecord{7e6cc5b u0 com.test.thalitest/.MainActivity t99}
,07-27 15:04:51.436   790  1021 D FocusedStackFrame: Set to : 0
,07-27 15:04:51.436   790  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:51.436   790  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-27 15:04:51.446   790  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 15:04:51.446   790  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 15:04:51.446   790  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 15:04:51.446   266  1449 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,07-27 15:04:51.446   266  1449 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,07-27 15:04:51.516   790  1065 W PackageSettings: Skipping PackageSetting{1903bdd0 com.example.hello/10078} due to missing metadata
,07-27 15:04:51.546   790   790 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.546   790   790 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.546   790  1018 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:51.546   790  3089 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.546   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:51.546   790   790 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-27 15:04:51.546   790   790 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
,07-27 15:04:51.546   790   790 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.546   790   790 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.546   790   790 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.546   790   790 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.546   790   790 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.546   790  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 15:04:51.546   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:51.546   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:51.546   790  1154 D SmartBondingService: getSBEnabled() enabled =false
,07-27 15:04:51.556   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.556   790  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.556   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.556   790  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.556   790  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.556   790  1264 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.556   790  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 15:04:51.556  1497  1497 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 15:04:51.556   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  3089 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  1474 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.566   790  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.566   790  1264 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  1018 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566  7798  7798 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
07-27 15:04:51.566   790  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  1686 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  1264 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.566   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.576  7782  7782 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-27 15:04:51.576  7782  7782 I PCWCLIENTTRACE_PushUtil: sales region : global
07-27 15:04:51.576  7782  7782 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 15:04:51.576  7782  7782 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:51.576   790  1635 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.576  7798  7798 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-27 15:04:51.586   790  1018 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.596   790  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,07-27 15:04:51.616   790  1458 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-27 15:04:51.616   790  1458 D SecContentProvider2: mCursor = null
,07-27 15:04:51.636  1497  1497 I art     : Explicit concurrent mark sweep GC freed 1232(59KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 20MB/33MB, paused 648us total 34.920ms
,07-27 15:04:51.636   790   790 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-27 15:04:51.646   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-27 15:04:51.646   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-27 15:04:51.646  3682  3682 I art     : Explicit concurrent mark sweep GC freed 5482(303KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/26MB, paused 348us total 20.640ms
07-27 15:04:51.646   790  1059 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-27 15:04:51.646  1443  1443 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-27 15:04:51.646   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-27 15:04:51.656  1443  1443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 15:04:51.656  1443  1443 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 15:04:51.656  1443  1443 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-27 15:04:51.656  7070  7070 I art     : Explicit concurrent mark sweep GC freed 7865(490KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 372us total 56.022ms
,07-27 15:04:51.656  1443  1443 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:51.656  1443  1443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 15:04:51.656  1443  1443 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 15:04:51.656  1739  1739 E SamsungIME: mOCRHelper is null
,07-27 15:04:51.666  1443  1443 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-27 15:04:51.666  1443  1443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 15:04:51.666  1443  1443 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 15:04:51.666  7846  7846 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:51.666  7846  7846 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 15:04:51.676  5454  5454 I art     : Explicit concurrent mark sweep GC freed 645(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 309us total 34.386ms
,07-27 15:04:51.676  1414  1414 D RegisteredServicesCache: empty dynamic service
,07-27 15:04:51.676   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-27 15:04:51.686  4446  4446 I art     : Explicit concurrent mark sweep GC freed 31449(1822KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 24MB/40MB, paused 1.261ms total 67.249ms
,07-27 15:04:51.686   790  1123 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 15:04:51.686   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-27 15:04:51.696   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-27 15:04:51.716   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,07-27 15:04:51.726   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-27 15:04:51.746   790  1147 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-27 15:04:51.746   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:51.746   790  1147 V NetworkStats: performPollLocked(flags=0x3)
,07-27 15:04:51.746   790  1147 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 15:04:51.746   790  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.746   790  1147 V NetworkStats: performPollLocked() took 5ms
07-27 15:04:51.746   790  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:51.776   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-27 15:04:51.786   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-27 15:04:51.796   790  1474 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-27 15:04:51.796   790  1474 D SecContentProvider2: mCursor = null
,07-27 15:04:51.796   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-27 15:04:51.796  1834  2263 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 15:04:51.806   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-27 15:04:51.806   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-27 15:04:51.816  7174  7174 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-27 15:04:51.826  7174  7174 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-27 15:04:51.826   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 15:04:51.826   790  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 15:04:51.826  7174  7174 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-27 15:04:51.836   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-27 15:04:51.836  3952  3952 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 15:04:51.836   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-27 15:04:51.846   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-27 15:04:51.846   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-27 15:04:51.846   790   790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-27 15:04:51.846  3952  3952 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469624691853
,07-27 15:04:51.846  3952  3952 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:51.846   790   805 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.846   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.846  3952  3952 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-27 15:04:51.846  3952  3952 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-27 15:04:51.856  3952  3952 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-27 15:04:51.856   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-27 15:04:51.856   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 15:04:51.866  3952  3952 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-27 15:04:51.866   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-27 15:04:51.866   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-27 15:04:51.876   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-27 15:04:51.876   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 15:04:51.876   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 15:04:51.886   790   805 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.886   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-27 15:04:51.886   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-27 15:04:51.886   790  1018 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-27 15:04:51.886   790  1018 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-27 15:04:51.896   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,07-27 15:04:51.896  7190  7190 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-27 15:04:51.896   790  1648 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-27 15:04:51.896   790  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@2973441c, r.packageName :com.samsung.android.app.galaxyfinder
,07-27 15:04:51.906   790   790 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,07-27 15:04:51.906   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-27 15:04:51.916   790   790 D RCPManagerService: PackageReceiver onReceive()
,07-27 15:04:51.916   790   790 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-27 15:04:51.926   790   790 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-27 15:04:51.926   790   790 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-27 15:04:51.926   790   790 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicy: uID is 10079
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicy: Removed Packageuid is0
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-27 15:04:51.926   790   790 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-27 15:04:51.926   790   790 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-27 15:04:51.926   790  1179 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,07-27 15:04:51.936   790   790 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,07-27 15:04:51.936  7881  7881 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-27 15:04:51.936   790   806 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.936  3535  8499 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
07-27 15:04:51.936   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.936  3535  8499 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-27 15:04:51.936   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.936   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-27 15:04:51.936  6861  6861 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-27 15:04:51.936  3535  8499 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
07-27 15:04:51.936  6861  6861 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-27 15:04:51.936  6861  6861 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 15:04:51.946  6861  6861 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
07-27 15:04:51.946  6861  6861 I SA      : [OR] == isSIMCardReady false ==
,07-27 15:04:51.946   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.946  6861  6861 I SA      : [SCU] == networkStateCheck == true
,07-27 15:04:51.946  6861  6861 I SA      : [DM] getCountryCodeFromCSC : PL
,07-27 15:04:51.946  6861  6861 I SA      : isChinaCountryCode : false
07-27 15:04:51.946  6861  6861 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-27 15:04:51.946   790  1152 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
07-27 15:04:51.946  6861  6861 I SA      : [OR] == networkStateCheck true ==
,07-27 15:04:51.946  6861  6861 I SA      : [OR] GetMyCountryZoneTask
,07-27 15:04:51.946  6861  6861 I SA      : [OR] onReceive END
,07-27 15:04:51.956   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-27 15:04:51.956   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.956   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.956   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-27 15:04:51.966   790  1458 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-27 15:04:51.966   790  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@21acab6f, r.packageName :com.android.providers.downloads
,07-27 15:04:51.966  6861  8500 I SA      : [SRS] prepareGetMyCountryZone
,07-27 15:04:51.966  7900  7900 I SCloudBackupReceiver: Other Intent
,07-27 15:04:51.966   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.966   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-27 15:04:51.966  7402  7402 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-27 15:04:51.966  7402  7402 I KnoxUsageLogPro: premStatus:2
,07-27 15:04:51.976  7402  7402 I KnoxUsageLogPro: isEulaShown : false
07-27 15:04:51.976  7402  7402 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 15:04:51.976  3535  8499 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-27 15:04:51.976  3535  8499 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-27 15:04:51.976  6861  8500 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-27 15:04:51.976  3535  8499 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-27 15:04:51.986  3535  8499 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-27 15:04:51.986   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.986  3535  8499 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-27 15:04:51.986  3535  8499 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-27 15:04:51.986   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.986  3535  8499 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
07-27 15:04:51.986   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-27 15:04:51.986  3535  8499 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-27 15:04:51.986  6861  8500 I SA      : [SSP] query invoked
,07-27 15:04:51.996   790  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.996  6861  8500 I SA      : [TPMU] GetMccFromDB : null
,07-27 15:04:51.996   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:51.996  6861  8500 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 15:04:51.996  6861  8500 I SA      : [TPM] isNoProxy(default) : true
,07-27 15:04:52.006   790  3089 I SQLiteConnectionPool: exportDB...
,07-27 15:04:52.006   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 15:04:52.006   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-27 15:04:52.016  3535  8499 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-27 15:04:52.016  6861  8500 E File    : fail readDirectory() errno=2
07-27 15:04:52.016   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.016   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.026   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-27 15:04:52.026   790  1065 I art     : Explicit concurrent mark sweep GC freed 80888(5MB) AllocSpace objects, 13(208KB) LOS objects, 29% free, 37MB/53MB, paused 3.142ms total 286.029ms
,07-27 15:04:52.026   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-27 15:04:52.036  7993  7993 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:52.036  7993  7993 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-27 15:04:52.036  7993  7993 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-27 15:04:52.036   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.036   790   806 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.036   790  1686 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.046  3535  8499 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 15:04:52.046   790  1267 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:52.046   790   805 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 15:04:52.056   790  1264 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.056  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-27 15:04:52.056   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 15:04:52.056  7271  7271 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 15:04:52.056  7271  7271 D SecurityLogAgent: StateMachine : Current State = 1
07-27 15:04:52.056   790  1704 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.056   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 15:04:52.056  7271  7271 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 15:04:52.066   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.066   790  1686 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.066   790  1635 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,07-27 15:04:52.066   790  1635 D ActivityManager: caller:android.app.ApplicationThreadProxy@371bb7d6, r.packageName :com.sec.android.app.SmartClipService
,07-27 15:04:52.066   790  3089 I SQLiteConnectionPool: ...exportDB
,07-27 15:04:52.076   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-27 15:04:52.076   790  3089 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,07-27 15:04:52.086   790  1704 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 15:04:52.086   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c3d3944, r.packageName :com.google.android.gms
,07-27 15:04:52.086   790  1267 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.086   790  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.086   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.086   790  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.086   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.086   790  1266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.086  4446  4446 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 15:04:52.096   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-27 15:04:52.096  4446  5430 I iu.UploadsManager: num queued entries: 0
,07-27 15:04:52.096   790  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.096  4446  5430 I iu.UploadsManager: num updated entries: 0
,07-27 15:04:52.096  8063  8063 D WaitQueueForNetworkActivate: notifyNetworkActivated
07-27 15:04:52.096  4446  5430 I iu.SyncManager: NEXT; no task
,07-27 15:04:52.106   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.106   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.106   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-27 15:04:52.106   790  1018 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-27 15:04:52.106   790  1018 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:52.106   790  1018 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 15:04:52.106   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.106   790  1018 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-27 15:04:52.116   790  1018 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,07-27 15:04:52.116   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-27 15:04:52.126   790  1065 D PackageManager: delete codoeFile: 
,07-27 15:04:52.136   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-27 15:04:52.136   790  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-27 15:04:52.136   790  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,07-27 15:04:52.136   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.136   790  1065 D PackageManager: result of delete: 1{709155676}
,07-27 15:04:52.146   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-27 15:04:52.146   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.146   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-27 15:04:52.146  8475  8475 D AndroidRuntime: Shutting down VM
,07-27 15:04:52.146   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.146   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-27 15:04:52.146   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-27 15:04:52.156   790  1065 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-27 15:04:52.156   790  1065 D PackageManager: userId{-1}
07-27 15:04:52.156   790  1065 D PackageManager: andCode{true}
,07-27 15:04:52.156   790  1065 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,07-27 15:04:52.156   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 15:04:52.156   790  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.156   790  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.156   790  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.156   790  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.156   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-27 15:04:52.156   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.156   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-27 15:04:52.156   790  1018 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-27 15:04:52.156   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.156   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-27 15:04:52.156   790  1018 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-27 15:04:52.166   790  1018 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 15:04:52.196  8511  8511 E Zygote  : MountEmulatedStorage()
,07-27 15:04:52.196  8511  8511 E Zygote  : v2
07-27 15:04:52.196  8511  8511 I libpersona: KNOX_SDCARD checking this for 10007
07-27 15:04:52.196  8511  8511 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:52.206   790  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8511 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-27 15:04:52.206   790  1018 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-27 15:04:52.206   790  1018 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-27 15:04:52.246  8511  8511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:52.246   790   806 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.246  8511  8511 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:52.246   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.246  1834  8507 I qtaguid : Tagging socket 49 with tag 1000040700000000{268436487,0} uid -1, pid: 1834, getuid(): 10015
07-27 15:04:52.246  8511  8511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:52.246   790  3246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.246   790  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.246   790  1635 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.276  8511  8511 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:52.276  8511  8511 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:52.276   790   806 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
07-27 15:04:52.276   790   806 D ActivityManager: caller:android.app.ApplicationThreadProxy@16837b74, r.packageName :com.sec.android.app.samsungapps
,07-27 15:04:52.286   790  1704 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:52.286   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@2847a0e3, r.packageName :com.google.android.gms
,07-27 15:04:52.296  3952  3952 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 15:04:52.296  8511  8511 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,07-27 15:04:52.296  3952  3952 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1469624692308
,07-27 15:04:52.296  3952  3952 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,07-27 15:04:52.296  3952  3952 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,07-27 15:04:52.296  1443  1443 D SurfaceWidgetView: destroyHardwareResources():289479137
,07-27 15:04:52.306   790  1704 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 15:04:52.306   790  1704 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 15:04:52.306   790  1704 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 15:04:52.306   790  1704 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 15:04:52.306   790  1704 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,07-27 15:04:52.306  1443  1443 D Launcher: onRestart, Launcher: 179152079
,07-27 15:04:52.306  1443  1443 D Launcher: onStart, Launcher: 179152079
07-27 15:04:52.306  1443  1443 D Launcher.HomeView: onStart
,07-27 15:04:52.306  4446  8528 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-27 15:04:52.306  4446  8528 D SchedPeriodicTask: Scheduled AdAttestation task.
07-27 15:04:52.316  1443  1443 V ActivityThread: updateVisibility : ActivityRecord{336182f3 token=android.os.BinderProxy@379e421 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-27 15:04:52.316  8063  8063 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-27 15:04:52.316  1762  1779 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,07-27 15:04:52.316  1762  2046 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-27 15:04:52.316  1762  2046 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-27 15:04:52.316  8063  8063 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-27 15:04:52.326  8063  8063 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-27 15:04:52.326  8063  8063 D InitializeManagerStateMachine: exit::IDLE
,07-27 15:04:52.326  8063  8063 D InitializeManagerStateMachine: entry::NETWORK_CHECK
07-27 15:04:52.326   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,07-27 15:04:52.326   790  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 15:04:52.336   790  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 15:04:52.336   790  1377 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.336   790  1704 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 15:04:52.336   790  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.336  8063  8063 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-27 15:04:52.336   790  1704 D ActivityManager: caller:android.app.ApplicationThreadProxy@5aba199, r.packageName :com.google.android.gms
07-27 15:04:52.336  8063  8063 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-27 15:04:52.336  8063  8063 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-27 15:04:52.336  8063  8063 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-27 15:04:52.336  8063  8063 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-27 15:04:52.336  8063  8063 D InitializeManagerStateMachine: entry::SUCCESS
07-27 15:04:52.336  8063  8063 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-27 15:04:52.336   790  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-27 15:04:52.336   790  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 15:04:52.336   790  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 15:04:52.336   790  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 15:04:52.346  8063  8063 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-27 15:04:52.346  8063  8063 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
07-27 15:04:52.346   790  1704 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.346  8063  8063 D InitializeManagerStateMachine: exit::SUCCESS
07-27 15:04:52.346  8063  8063 D InitializeManagerStateMachine: entry::IDLE
,07-27 15:04:52.346   790  1474 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 15:04:52.346   790  1264 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.346   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.346   790  1474 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7530 uid 10079
,07-27 15:04:52.356   790  1576 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.356   790  8532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 15:04:52.356   790   805 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.366   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:52.366   790  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.366   790  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.376   790  1635 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.386   790  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:52.396  3952  3952 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,07-27 15:04:52.406  3952  3952 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-27 15:04:52.406   790  1264 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-27 15:04:52.406   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.406   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.406   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.406   790  1264 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:52.416   790  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
,07-27 15:04:52.416   790  1152 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 15:04:52.416   790  1152 D ConnectivityService: identical MTU - not setting
,07-27 15:04:52.416   790  1152 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-27 15:04:52.416   790  1152 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,07-27 15:04:52.416   298  1054 V         : QcRouteController
,07-27 15:04:52.436   298  1054 V         : QcRouteController
,07-27 15:04:52.436   790  1152 W NetworkManagementService: route cmd failed: 
07-27 15:04:52.436   790  1152 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '105 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 105 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-27 15:04:52.436   790  1152 W NetworkManagementService: '
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:52.436   790  1152 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 15:04:52.436   790  1152 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-27 15:04:52.436   790  1152 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-27 15:04:52.436   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:52.436   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.436   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.436   790  1152 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:52.446  1197  1584 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 15:04:52.446  8538  8538 E Zygote  : MountEmulatedStorage()
07-27 15:04:52.446  8538  8538 E Zygote  : v2
07-27 15:04:52.446  8538  8538 I libpersona: KNOX_SDCARD checking this for 10116
07-27 15:04:52.446  8538  8538 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:52.446   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:52.446   790  1152 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:52.446   790  1152 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-27 15:04:52.446   790  1152 D ConnectivityService: calling update connectivity
07-27 15:04:52.446   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.446   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:52.446   790  1152 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:52.446   790  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.446   790  1152 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:52.446   790  1264 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8538 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,07-27 15:04:52.456   790  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{60be1e8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:188692
,07-27 15:04:52.456   790   790 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
07-27 15:04:52.456   790   790 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.456   790  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,07-27 15:04:52.456   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:52.456   790  1154 D SmartBondingService: getSBEnabled() enabled =false
07-27 15:04:52.456   790  1154 D SmartBondingService: getSBEnabled() enabled =false
,07-27 15:04:52.466  8538  8538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:52.466  8538  8538 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 15:04:52.466  1197  1584 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 15:04:52.466  4446  7480 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 15:04:52.466  8538  8538 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:52.466  4446  7480 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 15:04:52.486  8538  8538 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:52.486  8538  8538 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:52.496  8538  8538 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-27 15:04:52.516  8538  8538 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-27 15:04:52.516  8538  8538 D elm:14491: ELMEngine.ELMEngine( context ).
,07-27 15:04:52.516  8538  8538 D elm:14491: MDMBridge.setEnterpriseBridge()
,07-27 15:04:52.516   790  1648 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-27 15:04:52.516   790  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@13c206a, r.packageName :com.sec.esdk.elm
,07-27 15:04:52.526  8538  8538 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-27 15:04:52.526  3617  3617 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-27 15:04:52.526  3617  3617 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 15:04:52.526  3617  3617 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-27 15:04:52.526  3617  3617 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-27 15:04:52.526  3617  3617 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-27 15:04:52.526  3617  3617 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-27 15:04:52.526  3617  3617 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-27 15:04:52.526  3617  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:52.526  3617  3617 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:52.526  3617  3617 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:52.526  3617  3617 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:52.526  3617  3617 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:52.526  3617  3617 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:52.526  3617  3617 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:52.526  8538  8538 D elm:14491: ElmAgentService : onCreate()
07-27 15:04:52.526   790  1704 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
,07-27 15:04:52.526  8538  8553 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-27 15:04:52.536  8538  8553 D elm:14491: MainReceiver.listeningToPackageRemoved()
,07-27 15:04:52.536  8538  8553 D elm:14491: MDMBridge.getInstance()
07-27 15:04:52.536  8538  8553 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-27 15:04:52.536   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.536   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.536   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.536   790  1704 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:52.536  8538  8553 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-27 15:04:52.576  8556  8556 E Zygote  : MountEmulatedStorage()
07-27 15:04:52.586  8556  8556 E Zygote  : v2
07-27 15:04:52.586  8556  8556 I libpersona: KNOX_SDCARD checking this for 10021
07-27 15:04:52.586  8556  8556 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:52.586   790  1704 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8556 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,07-27 15:04:52.596   790  1267 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.596   790  1267 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.596   790  1267 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 15:04:52.596   790  1267 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 15:04:52.596  8538  8538 D elm:14491: ElmAgentService : onDestroy().
,07-27 15:04:52.596  8556  8556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 15:04:52.596  8556  8556 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:52.596  8556  8556 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 15:04:52.606   346   346 I art     : Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 315us total 14.517ms
,07-27 15:04:52.616   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.732ms
,07-27 15:04:52.616   790  1123 I EventHub: Removing device '/dev/input/event6' due to inotify event
,07-27 15:04:52.626  8556  8556 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:52.626  8556  8556 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:52.626   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 354us total 12ms
,07-27 15:04:52.646   790  1123 I EventHub: Removing device '/dev/input/event7' due to inotify event
,07-27 15:04:52.666   790  1267 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8571 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-27 15:04:52.666  8571  8571 E Zygote  : MountEmulatedStorage()
07-27 15:04:52.666  8571  8571 E Zygote  : v2
07-27 15:04:52.666  8571  8571 I libpersona: KNOX_SDCARD checking this for 10015
07-27 15:04:52.666  8571  8571 I libpersona: KNOX_SDCARD not a persona
,07-27 15:04:52.706   790  1123 I EventHub: Removing device '/dev/input/event8' due to inotify event
,07-27 15:04:52.706  6861  8500 I SA      : [RC New] Execute method=[GET] start
,07-27 15:04:52.716  8571  8571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 15:04:52.716  8571  8571 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 15:04:52.716  8571  8571 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 15:04:52.736   790   805 I ActivityManager: Killing 7318:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,07-27 15:04:52.746  8571  8571 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 15:04:52.746  8571  8571 D ActivityThread: Added TimaKeyStore provider
,07-27 15:04:52.756   790  1123 I EventHub: Removing device '/dev/input/event9' due to inotify event
,07-27 15:04:52.756  8571  8571 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-27 15:04:52.766  8571  8571 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-27 15:04:52.766  8571  8571 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 15:04:52.766  6861  8500 I SA      : [RC New] Security=[true]
,07-27 15:04:52.776  6861  8500 I System.out: Thread-1080(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 15:04:52.796  8556  8556 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,07-27 15:04:52.796  8556  8556 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.service.health/cache
07-27 15:04:52.796  8556  8556 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-27 15:04:52.796  8556  8556 W         : Zip: inflate read failed (14837 vs 32768)
,07-27 15:04:52.806  8556  8556 D AndroidRuntime: Shutting down VM
,07-27 15:04:52.806  8556  8556 E AndroidRuntime: FATAL EXCEPTION: main
07-27 15:04:52.806  8556  8556 E AndroidRuntime: Process: com.sec.android.service.health, PID: 8556
07-27 15:04:52.806  8556  8556 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.android.service.health.cp.TrustZoneSecurityProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.service.health.cp.TrustZoneSecurityProvider" on path: DexPathList[[zip file "/system/priv-app/HealthService/HealthService.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.service.health.cp.TrustZoneSecurityProvider" on path: DexPathList[[zip file "/system/priv-app/HealthService/HealthService.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	... 11 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/HealthService/HealthService.apk': I/O Error
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile,(PathClassLoader.java:76)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		... 9 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@HealthService@HealthService.apk@classes.dex': Read-only file system
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		... 27 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/HealthService/HealthService.apk'
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		... 27 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/HealthService/arm/HealthService.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		... 27 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Caused by: java.io.IOException: 
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		... 27 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.service.health.cp.TrustZoneSecurityProvider
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 		... 13 more
07-27 15:04:52.806  8556  8556 E AndroidRuntime: 	Ca
07-27 15:04:52.806  6861  8500 I System.out: Thread-1080(ApacheHTTPLog):isShipBuild true
,07-27 15:04:52.806   790  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.service.health
,07-27 15:04:52.806  6861  8500 I System.out: Thread-1080(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-27 15:04:52.816  6112  6112 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,07-27 15:04:52.816  6112  6112 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM config WHERE config_id=?] disk I/O error
07-27 15:04:52.816  8556  8556 I Process : Sending signal. PID: 8556 SIG: 9
,07-27 15:04:52.816   790  8586 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
07-27 15:04:52.816   790  8586 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-27 15:04:52.816   790  8586 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-27 15:04:52.816   790  8586 E AndroidRuntime: 	... 5 more
,07-27 15:04:52.816   263   263 E lowmemorykiller: Error writing /proc/8556/oom_score_adj; errno=22
,07-27 15:04:52.826   790  1123 I EventHub: Removing device '/dev/input/event10' due to inotify event
,07-27 15:04:52.826  7782  7782 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-27 15:04:52.826  7782  7782 I PCWCLIENTTRACE_PushUtil: sales region : global
07-27 15:04:52.826  7782  7782 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 15:04:52.826  7782  7782 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-27 15:04:52.836   790  1474 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,07-27 15:04:52.836   790  8586 E android.os.Debug: ro.product_ship = true
07-27 15:04:52.836   790  8586 E android.os.Debug: ro.debug_level = 0x4f4c
07-27 15:04:52.836  8571  8571 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 15:04:52.836  8571  8571 I MultiDex: install
07-27 15:04:52.836   790  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@274e630d, r.packageName :com.sec.android.app.shealth
07-27 15:04:52.836  8571  8571 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 15:04:52.836   790  8586 E AndroidRuntime: Error reporting crash
07-27 15:04:52.836   790  8586 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-27 15:04:52.836   790  8586 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-27 15:04:52.836   790  8586 E AndroidRuntime: 	... 11 more
07-27 15:04:52.836   790  8586 I Process : Sending signal. PID: 790 SIG: 9
,07-27 15:04:52.836  6112  6112 D AndroidRuntime: Shutting down VM
,07-27 15:04:52.846  6112  6112 D HockeyApp: Writing unhandled exception to: /data/data/sstream.app/files/39de0a21-c7a3-4da1-8599-cb0474a5bcf1.stacktrace
,07-27 15:04:52.846  6112  6112 E HockeyApp: Error saving exception stacktrace!
07-27 15:04:52.846  6112  6112 E HockeyApp: 
07-27 15:04:52.846  6112  6112 E HockeyApp: java.io.FileNotFoundException: /data/data/sstream.app/files/39de0a21-c7a3-4da1-8599-cb0474a5bcf1.stacktrace: open failed: ENOENT (No such file or directory)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at java.io.FileWriter.<init>(FileWriter.java:80)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-27 15:04:52.846  6112  6112 E HockeyApp: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at libcore.io.Posix.open(Native Method)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 15:04:52.846  6112  6112 E HockeyApp: 	... 7 more
,07-27 15:04:52.846  8571  8571 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/app_extracted_libs): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)
07-27 15:04:52.846  8571  8571 E File    : fail readDirectory() errno=2
,07-27 15:04:52.846  8571  8571 D AndroidRuntime: Shutting down VM
,07-27 15:04:52.856  8571  8571 D ChimeraCfgMgr: Reading stored module config
,07-27 15:04:52.856  8571  8571 E ChimeraCfgMgr: Failed to read module config: /data/data/com.google.android.gms/app_chimera/current_config.pb: open failed: ENOENT (No such file or directory)
,07-27 15:04:52.976   264   264 I ServiceManager: service 'connectivity' died
07-27 15:04:52.976   266  1460 I SurfaceFlinger: restart the boot-animation @ binderDied
,07-27 15:04:52.976  1407  3082 W Sensors : sensorservice died [0xaef72900]
07-27 15:04:52.976   264   264 I ServiceManager: service 'sb_service' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'servicediscovery' died
07-27 15:04:52.976  1855  1889 W Sensors : sensorservice died [0xaefa8a00]
07-27 15:04:52.976   264   264 I ServiceManager: service 'updatelock' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'notification' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'devicestoragemonitor' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'location' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'country_detector' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'backup' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'appwidget' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'netpolicy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'wifip2p' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'voiceinteraction' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'SecExternalDisplayService' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'diskstats' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'mDNIe' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'spengestureservice' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'quickconnect' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'samplingprofiler' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'commontime_management' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'dreams' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'print' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'restrictions' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'media_session' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'media_router' died
07-27 15:04:52.976   310  4662 W AudioFlinger: power manager service died !!!
07-27 15:04:52.976   264   264 I ServiceManager: service 'trust' died
07-27 15:04:52.976   310  4662 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
07-27 15:04:52.976   264   264 I ServiceManager: service 'fingerprint' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'launcherapps' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'voip' died
07-27 15:04:52.976  1834  2505 W Sensors : sensorservice died [0xaef75380]
07-27 15:04:52.976   264   264 I ServiceManager: service 'media_projection' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'lpnet' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'imms' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'wifi' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'msapwifi' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'wifiscanner' died
07-27 15:04:52.976  1197  5489 W Sensors : sensorservice died [0xafb14240]
07-27 15:04:52.976   264   264 I ServiceManager: service 'rttmanager' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'sec_analytics' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'tactileassist' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'bluetooth_manager' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'bluetooth_secure_mode_manager' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'rcp' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'input_method' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'accessibility' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'harmony_eas_service' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'sdp' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'log_manager_service' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'wifi_policy' died
07-27 15:04:52.976   ,264   264 I ServiceManager: service 'phone_restriction_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'remoteinjection' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'mum_container_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'enterprise_billing_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'knox_timakeystore_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'motion_recognition' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'cover' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'mount' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'lock_settings' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'device_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'enterprise_license_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'application_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'enterprise_policy' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'statusbar' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'clipboard' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'clipboardEx' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'network_management' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'ABTPersistenceService' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'textservices' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'network_score' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'netstats' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'search' died
07-27 15:04:52.976   264   264 I ServiceManager: service 'dropbox' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'wallpaper' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'audio' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'DockObserver' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'usb' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'serial' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'uimode' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'jobscheduler' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'activity' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'context_aware' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'scontext' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'barbeam' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'multiwindow_facade' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'window' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'input' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'mdm.remotedesktop' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'sensorservice' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'persona_policy' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'batterystats' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'appops' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'power' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'display' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'webviewupdate' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'scheduling_policy' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'telephony.registry' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'entropy' died
,07-27 15:04:52.986   264   264 I ServiceManager: service 'samsung.smartfaceservice' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'consumer_ir' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'alarm' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'account' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'content' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'DirEncryptService' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'ReactiveService' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'sedenial' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'vibrator' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'tima' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'cepproxyks' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'CustomFrequencyManagerService' died
,07-27 15:04:52.986   264   264 I ServiceManager: service 'SEAMService' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'persona' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'procstats' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'battery' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'user' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'usagestats' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'package' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'meminfo' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'dbinfo' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'gfxinfo' died
,07-27 15:04:52.986   264   264 I ServiceManager: service 'cpuinfo' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'permission' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'hardware' died
07-27 15:04:52.986   264   264 I ServiceManager: service 'edmnativehelper' died
07-27 15:04:52.986  1443  1466 W Sensors : sensorservice died [0xafb28200]
07-27 15:04:52.986  1427  1452 W Sensors : sensorservice died [0xaefe8180]
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=2 Removed GocusedStac (5/9)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=3 Removed EimLayer (0/8)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=4 Removed EimLayer (0/7)
,07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=5 Removed EimLayer (0/6)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=6 Removed EimLayer (0/5)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=3 Removed EimLayer (-2/5)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=4 Removed EimLayer (-2/5)
,07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=5 Removed EimLayer (-2/5)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=6 Removed EimLayer (-2/5)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=7 Removed JmageWallpa (0/4)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/4)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=9 Removed TtatusBar (1/3)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=13 Removed Uoast (1/2)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=14 Removed Mauncher (0/1)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=14 Removed Mauncher (-2/1)
,07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=9 Removed TtatusBar (-2/1)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=11 Removed DolorFade (0/0)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=13 Removed Uoast (-2/0)
07-27 15:04:52.986   266  1449 I SurfaceFlinger: id=11 Removed DolorFade (-2/0)
07-27 15:04:52.986  1197  1580 E WifiManager: Channel connection lost
07-27 15:04:52.986  1834  2261 E WifiManager: Channel connection lost
07-27 15:04:52.986   266   266 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a62000
07-27 15:04:52.986   266   266 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-27 15:04:52.996  1497  3779 E WifiManager: Channel connection lost
07-27 15:04:52.996  1762  1777 W Sensors : sensorservice died [0xafb07300]
07-27 15:04:52.996  8571  8571 W ChimeraUtils: Can't get Chimera config
07-27 15:04:52.996  1427  1792 E WifiManager: Channel connection lost
07-27 15:04:52.996  7686  7712 E WifiManager: Channel connection lost
07-27 15:04:52.996  4934  5009 E WifiManager: Channel connection lost
07-27 15:04:52.996  1315  2700 E WifiManager: Channel connection lost
07-27 15:04:53.006  6149  6149 E SearchManager: getSearchablesInInsightSearch() failed: android.os.DeadObjectException
07-27 15:04:53.006  6149  6149 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
07-27 15:04:53.006  8571  8571 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
07-27 15:04:53.006  8571  8571 I GCore-Chimera-Crash: 
07-27 15:04:53.006  8571  8571 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-27 15:04:53.006  8571  8571 E AndroidRuntime: FATAL EXCEPTION: main
07-27 15:04:53.006  8571  8571 E AndroidRuntime: Process: com.google.android.gms.unstable, PID: 8571
07-27 15:04:53.006  8571  8571 E AndroidRuntime: java.lang.RuntimeException: Unable to create application com.google.android.gms.common.app.GmsApplication: java.lang.NullPointerException: Attempt to get length of null array
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5112)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: Caused by: java.lang.NullPointerException: Attempt to get length of null array
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at iwu.a(:com.google.android.gms:320)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at com.google.android.gms.common.app.GmsApplication.onCreate(:com.google.android.gms:195)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 15:04:53.006  8571  8571 E AndroidRuntime: 	... 9 more
07-27 15:04:53.016  8571  8591 D ChimeraCfgMgr: Reading stored module config
07-27 15:04:53.016  8571  8571 E AndroidRuntime: Error reporting crash
07-27 15:04:53.016  8571  8571 E AndroidRuntime: android.os.DeadObjectException
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at icd.uncaughtException(:com.google.android.gms:54)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at ibx.uncaughtException(:com.google.android.gms:62)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-27 15:04:53.016  8571  8571 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-27 15:04:53.016  8571  8571 I Process : Sending signal. PID: 8571 SIG: 9
,07-27 15:04:53.036   313   313 E installd: eof
07-27 15:04:53.036   313   313 E installd: failed to read size
07-27 15:04:53.036   313   313 I installd: closing connection
,07-27 15:04:53.226   266   529 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-27 15:04:53.226   266   266 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-27 15:04:53.226   266   266 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-27 15:04:53.296  8267  8288 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-27 15:04:53.366   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 15:04:53.416  6861  8500 I SA      : [RC New] [v2liruge] api execute + 646
,07-27 15:04:53.416  6861  8500 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,07-27 15:04:53.416  6861  8500 I System.out: AsyncTask #1 calls detatch()
,07-27 15:04:53.416  6861  8500 I SA      : [TPMU] getNetworkMcc : 
,07-27 15:04:53.436  6861  8500 I SA      : [SCU] saveMccToPreferece Start
,07-27 15:04:53.436  6861  8500 I SA      : [SCU] RegionMCC : 260
07-27 15:04:53.436  6861  8500 I SA      : [SSP] query invoked
,07-27 15:04:53.436  6861  8500 I SA      : [TPMU] GetMccFromDB : null
,07-27 15:04:53.436  6861  8500 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 15:04:53.436  6861  8500 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.osp.app.signin/shared_prefs/SERVICE_DISTRICT.xml
07-27 15:04:53.436  6861  8500 I SA      : [SCU] saveMccToPreferece End
,07-27 15:04:53.436  6861  8500 I SA      : [RC New] executeRequest [v2liruge] end. 734
07-27 15:04:53.436  6861  8500 I SA      : [RC New] Execute end
,07-27 15:04:53.436  6861  6861 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,07-27 15:04:53.446  6861  6861 I SA      : [OR] GetMyCountryZoneTask Success
,07-27 15:04:53.476   266   529 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-27 15:04:53.476   266   266 I SurfaceFlinger: Disp[0] Orientation 0=>0

```
