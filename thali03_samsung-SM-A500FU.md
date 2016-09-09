#### Test 83627337ab51778_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-09 13:35:23.696   290   290 E SMD     : DCD OFF
,09-09 13:35:24.656  6222  6222 D AndroidRuntime: 
09-09 13:35:24.656  6222  6222 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:35:24.656  6222  6222 D AndroidRuntime: CheckJNI is OFF
09-09 13:35:24.666  6222  6222 D AndroidRuntime: readGMSProperty: start
09-09 13:35:24.666  6222  6222 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:35:24.666  6222  6222 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:35:24.666  6222  6222 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:35:24.666  6222  6222 D AndroidRuntime: readGMSProperty: end
09-09 13:35:24.666  6222  6222 D AndroidRuntime: addProductProperty: start
09-09 13:35:24.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
09-09 13:35:24.816  6222  6222 E AffinityControl: AffinityControl: registerfunction enter
09-09 13:35:24.846  6222  6222 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:35:24.856  1013  3229 E PersonaManagerService: inState():  stateMachine is null !!
09-09 13:35:24.856  1013  3229 I PersonaManagerService: PersonaId don't exist
09-09 13:35:24.856  1013  3229 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 13:35:24.856  1013  3229 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-09 13:35:24.876  1013  3229 W ActivityManager: mDVFSHelper.acquire()
09-09 13:35:24.886  1013  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 13:35:24.886  1013  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 13:35:24.886  1013  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:24.886  1013  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:24.886  1013  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:24.886  1013  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:24.896  1013  3229 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-09 13:35:24.896  1013  3229 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6233 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:35:24.896  1013  3229 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:35:24.896  6233  6233 I libpersona: KNOX_SDCARD checking this for 10155
09-09 13:35:24.896  1013  3229 D InputDispatcher: Focused application set to: xxxx
09-09 13:35:24.896  6233  6233 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:24.896  1013  3229 D InputDispatcher: Focus left window: 3142
09-09 13:35:24.896  6233  6233 E Zygote  : MountEmulatedStorage()
09-09 13:35:24.896  6233  6233 E Zygote  : v2
09-09 13:35:24.896  6222  6222 D AndroidRuntime: Shutting down VM
09-09 13:35:24.906  1013  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 13:35:24.906  1013  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 13:35:24.906   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-09 13:35:24.906  6233  6233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:35:24.916  6233  6233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:35:24.916  6233  6233 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 13:35:24.916  1013  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:35:24.916  1013  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 13:35:24.936  6233  6233 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:24.946  6233  6233 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:24.956  1013  1013 V ActivityManager: Display changed displayId=0
09-09 13:35:24.956  1013  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:35:24.966  1013  1026 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:35:25.006   257   455 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-09 13:35:25.006   257  1095 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
09-09 13:35:25.016  3142  3142 V ActivityThread: updateVisibility : ActivityRecord{e20c799 token=android.os.BinderProxy@175ca624 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-09 13:35:25.076  6233  6233 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-09 13:35:25.086  6233  6233 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4166-4168)
09-09 13:35:25.086  6233  6233 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:25.106  6222  6222 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 13:35:25.116  6233  6233 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4244aa5}
09-09 13:35:25.116  6233  6233 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:25.116  6233  6233 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:35:25.146  6233  6233 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-09 13:35:25.156  6233  6233 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:25.156  6233  6233 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-09 13:35:25.176  6233  6233 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-09 13:35:25.176  6233  6233 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
09-09 13:35:25.176  6233  6233 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-09 13:35:25.176  6233  6233 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:25.176  6233  6233 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:25.176  6233  6233 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:25.176  6233  6233 I Adreno-EGL: Local Branch: 
09-09 13:35:25.176  6233  6233 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:25.176  6233  6233 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:25.176  6233  6233 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:25.266  6233  6259 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-09 13:35:25.446  6233  6233 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:25.456  6233  6233 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:35:25.466  6233  6233 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-09 13:35:25.466  6233  6233 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 13:35:25.466  6233  6233 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 13:35:25.476  1013  1039 W ActivityManager: Activity pause timeout for ActivityRecord{2c610712 u0 com.test.thalitest/.MainActivity t128}
,09-09 13:35:25.476  6233  6233 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:25.476  6233  6233 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:25.506  6233  6272 D OpenGLRenderer: Render dirty regions requested: true
09-09 13:35:25.516  1013  3214 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:35:25.516  1013  3214 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 13:35:25.516  1013  3214 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 13:35:25.516  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:35:25.516  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 13:35:25.526  6233  6233 V ActivityThread: updateVisibility : ActivityRecord{180f564 token=android.os.BinderProxy@1784cef6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 13:35:25.526  6233  6233 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-09 13:35:25.526  6233  6233 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 13:35:25.536   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-09 13:35:25.546  1013  1541 D InputDispatcher: Focus entered window: 6233
,09-09 13:35:25.546  1013  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:35:25.546  1013  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:35:25.556  6233  6233 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:35:25.556  6233  6272 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:35:25.556  6233  6272 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-09 13:35:25.556  6233  6272 D OpenGLRenderer: Enabling debug mode 0
,09-09 13:35:25.586  1013  1075 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:35:25.586  1013  6276 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-09 13:35:25.586  1173  1173 D PanelView: There is/are notification(s) 
,09-09 13:35:25.606  1013  1044 I ActivityManager: Displayed Component not be shown by security: +629ms (total +719ms)
,09-09 13:35:25.606  1013  1044 W ActivityManager: mDVFSHelper.release()
09-09 13:35:25.606  1013  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c610712 u0 com.test.thalitest/.MainActivity t128} time:114680
,09-09 13:35:25.606  1891  1891 I SamsungIME: getCurrentCandidateView
,09-09 13:35:25.606  6233  6233 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 13:35:25.606  6233  6233 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6233
,09-09 13:35:25.616  6233  6233 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1784cef6 time:114690,
09-09 13:35:25.616   257   455 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-09 13:35:25.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:25.676  1891  1891 D SamsungIME: Dismiss ExpandCandiate
,09-09 13:35:25.726  6233  6233 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:35:25.816  1891  1891 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:35:25.836  6233  6275 D jxcore_app_log: JniHelper::setJavaVM(0xb81ee328), pthread_self() = -1200285872
,09-09 13:35:25.846  6233  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:35:25.846  6233  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:35:25.846  6233  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:35:25.846  6233  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:35:25.846  6233  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:35:25.846  6233  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10be7f94 added. We now have 1 listener(s)
,09-09 13:35:25.846  1891  1891 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:35:25.856  6233  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-09 13:35:25.856  6233  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:35:25.856  6233  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:25.856  6233  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 13:35:25.856  6233  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea90b83 added. We now have 1 listener(s)
09-09 13:35:25.856  6233  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:25.866  6233  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-09 13:35:25.876  6233  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:25.876  6233  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:25.876  6233  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:35:25.876  6233  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:25.876  6233  6275 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:35:25.876  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:25.886  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:25.886  5443  5443 D FactoryTest: Not factory mode
09-09 13:35:25.886  5443  5443 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 13:35:25.886  5443  5443 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-09 13:35:25.886  5443  5443 D MTPRx   : still no open session command from host, so toast
,09-09 13:35:25.886  5443  5443 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-09 13:35:25.886  5443  5443 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114969
09-09 13:35:25.886  5443  5443 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-09 13:35:25.896  1013  1638 E PersonaManagerService: inState():  stateMachine is null !!
,09-09 13:35:25.896  1013  1638 I PersonaManagerService: PersonaId don't exist
09-09 13:35:25.896  1013  1638 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 13:35:25.896  1013  1638 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:35:25.896  1013  1638 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:25.896  1013  1638 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:25.896  1013  1638 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 13:35:25.896  1013  1638 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:35:25.906  6233  6233 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:35:25.916  1013  1638 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:35:25.916  1013  1638 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:35:25.916  1013  1638 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:35:25.916  1013  1638 D InputDispatcher: Focused application set to: xxxx
,09-09 13:35:25.916  1013  1638 D InputDispatcher: Focus left window: 6233
,09-09 13:35:25.916  5443  5443 E MTPRx   : started activity for popup
,09-09 13:35:25.926  1891  1891 I SamsungIME: KeybaordView init() : load resources
,09-09 13:35:25.926  1013  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:35:25.926  1013  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:35:25.946  5443  5443 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 13:35:25.946  5443  5443 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:35:25.946  5443  5443 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 13:35:25.946  5443  5443 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:25.956  5443  5443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:35:25.956  5443  5443 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:35:25.986  5443  5443 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 13:35:25.986  1891  1891 I SamsungIME: getCurrentKeyboard
09-09 13:35:25.986  1891  1891 I SamsungIME: getTextKeyboard
,09-09 13:35:25.986  1013  1245 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:35:25.986  1013  1245 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:35:25.986  1013  1245 D InputDispatcher: Focused application set to: xxxx
,09-09 13:35:25.996  1013  1245 D InputDispatcher: Focus entered window: 6233
,09-09 13:35:25.996  1013  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:35:25.996  1013  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:35:25.996  1013  1026 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:35:25.996  1013  1026 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2ee6c9ed attribute=null, token = android.os.BinderProxy@2660077d
,09-09 13:35:26.006  1891  1891 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 13:35:26.046  5443  5443 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 13:35:26.056  5443  5443 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-09 13:35:26.056  5443  5443 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 13:35:26.076  6233  6233 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:35:26.076  6233  6233 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 13:35:26.086  6233  6233 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:35:26.086  6233  6233 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 13:35:26.086  1013  1638 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:35:26.086  1013  1638 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 13:35:26.086  1013  1638 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 13:35:26.086  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:35:26.086  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 13:35:26.096  6233  6233 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 13:35:26.096  6233  6233 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:35:26.106  6233  6233 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1784cef6 time:115180
,09-09 13:35:26.106  6233  6233 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2df62715 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@156179c6, 16908290=android.view.AbsSavedState$1@156179c6}, android:focusedViewId=100}]}]
09-09 13:35:26.106  6233  6233 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:35:26.106  6233  6233 V ActivityThread: updateVisibility : ActivityRecord{180f564 token=android.os.BinderProxy@1784cef6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 13:35:26.106  6233  6233 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:35:26.106  6233  6233 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:35:26.106  1013  1356 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:35:26.506  6233  6282 W jxcore-log: Initializing JXcore engine
09-09 13:35:26.506  6233  6282 W jxcore-log: JXcore engine is ready
,09-09 13:35:26.536  1891  6284 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 13:35:26.556  1890  1890 E audit   : type=1400 msg=audit(1473420926.556:205): avc:  denied  { ioctl } for  pid=6282 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 13:35:26.556  1890  1890 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:35:26.566  1890  1890 E audit   : type=1300 msg=audit(1473420926.556:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d9068f8 items=0 ppid=312 ppcomm=main pid=6282 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 13:35:26.566  1890  1890 E audit   : type=1320 msg=audit(1473420926.556:205): 
,09-09 13:35:26.576  6233  6282 W jxcore-log: Starting JXcore engine
,09-09 13:35:26.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:26.676  6233  6282 W jxcore-log: Platform android
09-09 13:35:26.676  6233  6282 W jxcore-log: 
09-09 13:35:26.676  6233  6282 W jxcore-log: Process ARCH arm
09-09 13:35:26.676  6233  6282 W jxcore-log: 
,09-09 13:35:26.696   290   290 E SMD     : DCD OFF
,09-09 13:35:26.876  6233  6282 I jxcore-log: JXcore Cordova bridge is ready!,
09-09 13:35:26.876  6233  6282 I jxcore-log: 
09-09 13:35:26.876  6233  6282 W jxcore-log: JXcore engine is started
,09-09 13:35:26.886  6233  6275 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 13:35:26.886  6233  6233 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:35:26.966  1013  3229 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:35:26.966  1013  3229 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4181, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 13:35:26.966  1013  3229 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:35:26.966  1013  3229 D BatteryService: stay LED for charging
,09-09 13:35:26.966  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:35:26.976  1013  1013 I MotionRecognitionService: Plugged
,09-09 13:35:26.976  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:35:26.976  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:35:26.976  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:35:26.976  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:35:26.976  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-09 13:35:26.986  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:35:26.986  2654  2726 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:27.006  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:27.006  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:27.006  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:27.656  1013  2771 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 13:35:27.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:28.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:28.906  1013  1039 W ActivityManager: mDVFSHelper.release(),
,09-09 13:35:29.676   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-09 13:35:29.696   290   290 E SMD     : DCD OFF,
,09-09 13:35:29.906  1013  2727 D SSRM:n  : SIOP:: AP = 330
,09-09 13:35:30.926  1013  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:35:30.926  1013  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-09 13:35:30.946  1907  1907 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-09 13:35:31.136  1013  1075 I art     : Explicit concurrent mark sweep GC freed 49694(2MB) AllocSpace objects, 23(368KB) LOS objects, 33% free, 28MB/42MB, paused 5.286ms total 170.225ms
,09-09 13:35:31.156  1013  1317 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:31.156  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.156  1013  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.156  1013  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:31.156  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.166  3806  3806 D ConnectivityManager: CallingUid : 10012, CallingPid : 3806
,09-09 13:35:31.166  1013  1317 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:35:31.166  1013  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-09 13:35:31.166  1013  1132 D ConnectivityService: apparently satisfied.  currentScore=60
,09-09 13:35:31.176  1013  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-09 13:35:31.176  3806  6291 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:35:31.236  3806  6292 W DriveInitializer: Background init thread started
,09-09 13:35:31.256   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-09 13:35:31.256   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:31.256  3806  6292 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-09 13:35:31.306  1013  3230 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:31.306  1013  3230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.306  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:31.306  1013  3230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.306  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.326  1013  1360 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-09 13:35:31.326  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.336  3806  6292 W DriveInitializer: Background init thread ended
,09-09 13:35:31.346  1013  1360 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:31.346  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.346  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:31.346  1013  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.346  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.376  3806  6300 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-09 13:35:31.376  3806  6300 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-09 13:35:31.386  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:31.416  1013  1039 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:31.416  1013  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.416  1013  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.526  1013  1356 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:31.526  1013  1356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.526  1013  1356 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.526  1013  1356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.526  1013  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.556  1013  3230 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:31.556  1013  3230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.556  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.556  1013  3230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.556  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.606  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:31.616  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.616  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.616  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.626  1013  3230 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:31.626  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.626  1013  3230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.626  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.676  1013  3214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:31.676  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.676  1013  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.676  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.676  1013  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:31.676  1013  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:31.676  1013  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:31.676  1013  3214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:31.696  6305  6305 E Zygote  : MountEmulatedStorage()
,09-09 13:35:31.696  6305  6305 I libpersona: KNOX_SDCARD checking this for 10012
09-09 13:35:31.696  6305  6305 E Zygote  : v2
09-09 13:35:31.696  6305  6305 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:31.696  6305  6305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:35:31.696  1013  3214 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6305 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-09 13:35:31.696  6305  6305 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:31.706  6305  6305 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:31.716   312   312 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 25.044ms
,09-09 13:35:31.726  6305  6305 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:31.726  6305  6305 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:31.736   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.138ms
,09-09 13:35:31.746  6305  6305 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 13:35:31.746  6305  6305 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:35:31.756   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 787us total 17.603ms
,09-09 13:35:31.786  6305  6305 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:35:31.786  6305  6305 I MultiDex: install
09-09 13:35:31.786  6305  6305 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:35:31.816  6305  6305 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:35:31.886  6305  6305 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:35:31.886  6305  6305 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20770056: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:35:31.886  6305  6305 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:35:31.906  6305  6305 D ChimeraCfgMgr: Reading stored module config
,09-09 13:35:31.916  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.926  1013  2968 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:31.936  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.936  1013  2968 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.936  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.946  1013  1356 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:31.946  1013  1356 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:31.946  1013  1356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:31.946  1013  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.996  1907  1907 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=40d88bcb-98fa-4f8e-8cc0-9d56226b7b3c
,09-09 13:35:32.006  6305  6323 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:35:32.016  1013  1025 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-09 13:35:32.016  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:35:32.016  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.016  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.016  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.026  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:32.026  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:32.036  6305  6305 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:35:32.036  6305  6305 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:35:32.046  1013  1317 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.056  1013  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.056  1013  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.056  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.116   285   726 D WVCdm   : Instantiating CDM.
,09-09 13:35:32.116   285   285 I WVCdm   : CdmEngine::OpenSession
,09-09 13:35:32.126   285   285 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-09 13:35:32.136   285   285 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-09 13:35:32.166   285   285 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-09 13:35:32.166   285   285 D DrmWidevineDash: Service_Initialize: starts!
09-09 13:35:32.166   285   285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-09 13:35:32.166   285   285 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:35:32.166   285   285 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-09 13:35:32.166   285   285 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-09 13:35:32.166   285   285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-09 13:35:32.166   285   285 D QSEECOMAPI: : App is not loaded in QSEE
09-09 13:35:32.166   285   285 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-09 13:35:32.166   285   285 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-09 13:35:32.166   285   285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-09 13:35:32.166   285   285 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:35:32.166  1607  1632 I art     : Explicit concurrent mark sweep GC freed 1400(47KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 736us total 31.498ms
,09-09 13:35:32.186   285   285 D QSEECOMAPI: : Loaded image: APP id = 11
,09-09 13:35:32.186   285   285 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-09 13:35:32.196   285   285 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-09 13:35:32.196   285   285 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-09 13:35:32.196   285   285 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16f5000
09-09 13:35:32.196   285   285 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16f5000
09-09 13:35:32.196   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,09-09 13:35:32.196   430   441 D DrmLibTime: got the req here! ret=0
09-09 13:35:32.196   430   441 D DrmLibTime: command id, time_cmd_id = 770
09-09 13:35:32.196   430   441 D DrmLibTime: time_getutcsec starts!
09-09 13:35:32.196   430   441 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-09 13:35:32.196   430   441 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-09 13:35:32.196   430   441 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-09 13:35:32.196   430   441 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-09 13:35:32.216   430   441 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
09-09 13:35:32.216   430   441 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-09 13:35:32.216   430   441 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-09 13:35:32.216   430   441 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,09-09 13:35:32.216   324   425 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-09 13:35:32.216   324  6329 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-09 13:35:32.216   324  6329 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
,09-09 13:35:32.216   324  6329 D QC-time-services: offset is: 0 for base: 0
,09-09 13:35:32.216   430   441 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-09 13:35:32.216   430   441 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-09 13:35:32.216   430   441 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473420932
09-09 13:35:32.216   430   441 D DrmLibTime: time_getutcsec returns 0, sec = 1473420932; nsec = 0
,09-09 13:35:32.216   430   441 D DrmLibTime: time_getutcsec finished! 
09-09 13:35:32.216   430   441 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-09 13:35:32.216   430   441 D DrmLibTime: before calling ioctl to read the next time_cmd
09-09 13:35:32.216   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:35:32.216   324   425 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-09 13:35:32.226   285   285 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-09 13:35:32.226   285   285 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-09 13:35:32.226   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.236   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.236   285   285 D DrmWidevineDash: hlos api version =  9
09-09 13:35:32.236   285   285 D DrmWidevineDash: tz api version =  9
09-09 13:35:32.236   285   285 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-09 13:35:32.236   285   285 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-09 13:35:32.236   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.236  6305  6313 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-09 13:35:32.236  6305  6313 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:35:32.236  6305  6313 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 13:35:32.236  6305  6313 I System.out: (HTTPLog)-Thread-1049-423445995: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-09 13:35:32.236  6305  6313 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:32.236   277   978 D EnterpriseController: uids 10012
09-09 13:35:32.236   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:35:32.236  6305  6319 I art     : Background partial concurrent mark sweep GC freed 2288(319KB) AllocSpace objects, 1(101KB) LOS objects, 40% free, 10MB/17MB, paused 23.093ms total 55.487ms
09-09 13:35:32.236   277   978 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:35:32.246   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-09 13:35:32.246   285   285 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbec281b0
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-09 13:35:32.246   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 13:35:32.246   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb881a2e0, dataLength=8
09-09 13:35:32.246   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.246   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.246   285   285 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-09 13:35:32.256   285   285 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb87ac788, wrapped_rsa_key_length=1280
09-09 13:35:32.256   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.256   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.256   285   285 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-09 13:35:32.256   285   285 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:35:32.256   285  1011 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-09 13:35:32.256   285  1011 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:35:32.256   285  1011 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-09 13:35:32.256   285  1011 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8818a50, idLength=0xb1464730
09-09 13:35:32.256   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1464746, maximum = 0xb1464747
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.276   285  1011 D DrmWidevineDash: hlos api version =  9
09-09 13:35:32.276   285  1011 D DrmWidevineDash: tz api version =  9
,09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb14647b4
09-09 13:35:32.276  1907  2130 I art     : Explicit concurrent mark sweep GC freed 57366(3MB) AllocSpace objects, 10(400KB) LOS objects, 39% free, 14MB/23MB, paused 1.507ms total 81.916ms
09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-09 13:35:32.276   285  1011 D WVCdm   : PrepareKeyRequest: nonce=2761995903
09-09 13:35:32.276   285  1011 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8807ae8
09-09 13:35:32.276   285  1011 D DrmWidevineDash: message_length=1599, signature=0xb87bf2f8, signature_length=0xb1464714
09-09 13:35:32.276   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.326  1907  2115 W GCoreFlp: No location to return for getLastLocation()
,09-09 13:35:32.346  1013  1540 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.346  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:32.346  1013  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:32.346  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.356  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.356  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:32.356  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:32.356  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.356  1013  2968 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.356  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.366  1013  2968 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:32.366  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.386  6305  6313 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:32.386  6305  6313 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6305, getuid(): 10012
,09-09 13:35:32.386  1907  2121 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:35:32.396  3806  6301 D UdcContextInitService: registered all accounts: true
,09-09 13:35:32.396  1907  2130 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-09 13:35:32.436   285  1011 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.436   285  1011 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-09 13:35:32.436   285   726 I WVCdm   : CdmEngine::CloseSession
,09-09 13:35:32.436   285   726 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-09 13:35:32.436   285   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.436   285   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.436   285   726 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-09 13:35:32.436   285   726 I WVCdm   : L3 Terminate.
09-09 13:35:32.436   285   726 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-09 13:35:32.436   285   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:35:32.436   285   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:35:32.436   285   726 D DrmWidevineDash: Service_Uninitialize: starts!
09-09 13:35:32.436   285   726 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-09 13:35:32.436   285   726 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-09 13:35:32.436   285   726 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-09 13:35:32.436   285   726 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-09 13:35:32.566  1013  1541 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 13:35:32.566  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:35:32.566  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.566  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.566  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.596  1013  2968 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-09 13:35:32.596  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.596  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.596  1013  2968 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.596  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.606  1907  2130 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:32.606   277   978 D EnterpriseController: uids 10012
09-09 13:35:32.606   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:35:32.606   277   978 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:35:32.606  1907  2130 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:32.606  1907  2130 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:32.696   290   290 E SMD     : DCD OFF
,09-09 13:35:32.706  1907  2130 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:33.006  6305  6313 I qtaguid : Untagging socket 33
,09-09 13:35:33.316  6339  6339 I dex2oat : ----------------------------------------------------
09-09 13:35:33.316  6339  6339 I dex2oat : <SS>: S T A R T I N G . . .
09-09 13:35:33.316  6339  6339 I dex2oat : <SS>: Zip is absent. Canceled.
,09-09 13:35:33.316  6339  6339 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:35:33.356  6339  6339 I dex2oat : dex2oat took 32.714ms (threads: 4)
,09-09 13:35:33.366  6305  6313 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:33.366  6305  6313 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:33.366  6305  6313 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:33.366  6305  6313 I Adreno-EGL: Local Branch: 
09-09 13:35:33.366  6305  6313 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:33.366  6305  6313 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:33.366  6305  6313 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:33.456  6305  6313 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:33.456  6305  6313 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:33.456  6305  6313 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:33.456  6305  6313 I Adreno-EGL: Local Branch: 
09-09 13:35:33.456  6305  6313 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:33.456  6305  6313 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:33.456  6305  6313 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:33.826  6305  6313 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:33.826  6305  6313 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:33.826  6305  6313 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:33.826  6305  6313 I Adreno-EGL: Local Branch: 
09-09 13:35:33.826  6305  6313 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:33.826  6305  6313 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:33.826  6305  6313 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:33.946  1907  6303 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:33.946  1907  6303 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:33.946  1907  6303 I qtaguid : Tagging socket 73 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:33.986  1907  6303 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:34.126  1907  2130 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:35:34.126  1907  2130 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-09 13:35:34.126  1907  2130 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-09 13:35:32.486+0200, stopTime=2016-09-09 13:35:34.135+0200, duration=1649ms
,09-09 13:35:34.136  1907  6346 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:34.146   277   978 D EnterpriseController: uids 10012
09-09 13:35:34.146   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:35:34.146   277   978 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:35:34.146  1907  6346 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-09 13:35:34.146  1907  6346 I qtaguid : Tagging socket 78 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:34.186  1907  6346 I qtaguid : Tagging socket 81 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:34.196  1013  1245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 13:35:34.536  1907  6346 I qtaguid : Untagging socket 78
,09-09 13:35:34.566  1013  2967 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:34.566  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-09 13:35:34.566  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.566  1013  2967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.566  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.596  1907  2130 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-09 13:35:34.646  1013  1360 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.646  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.656  1013  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.656  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.676  1013  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:34.676  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.676  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.676  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.726  1013  3230 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.726  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.726  1013  3230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.726  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.726  1907  6354 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:34.726  1907  6352 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:35:34.726  1013  1540 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.726  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.726  1013  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.726  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.756  1013  1075 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.756  1013  1075 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.756  1013  1075 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.756  1013  1075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.756  1907  6354 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:34.756  1907  6352 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:35:34.756  1013  3229 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.756  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.756  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.756  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.786  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:34.786  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.786  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.786  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.786  1907  6354 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:34.786  1907  6352 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-09 13:35:34.786  1907  6352 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-09 13:35:34.786  1907  6352 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:35:34.836  1013  1075 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:34.866  1907  6352 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:34.876   277   978 D EnterpriseController: uids 10012
09-09 13:35:34.876   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:35:34.876   277   978 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:35:34.876  1907  6352 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:34.876  1907  6352 I qtaguid : Tagging socket 89 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1907, getuid(): 10012
,09-09 13:35:34.936  1013  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 13:35:35.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:35.706   290   290 E SMD     : DCD OFF,
,09-09 13:35:35.926  1907  6352 I qtaguid : Tagging socket 91 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1907, getuid(): 10012
,09-09 13:35:36.196  1013  2967 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:36.206  1907  6352 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.206  1907  6352 I qtaguid : Tagging socket 89 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1907, getuid(): 10012
,09-09 13:35:36.246  1907  6349 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.246  1907  6349 I qtaguid : Tagging socket 78 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1907, getuid(): 10012
,09-09 13:35:36.346  1013  2967 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:36.356  1907  6352 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.356  1907  6352 I qtaguid : Tagging socket 89 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1907, getuid(): 10012
,09-09 13:35:36.496  1907  6349 I qtaguid : Untagging socket 78
,09-09 13:35:36.496  1013  1356 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:36.496  1907  2130 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-09 13:35:36.506  1907  6352 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.506  1907  6352 I qtaguid : Tagging socket 89 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1907, getuid(): 10012
,09-09 13:35:36.516  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 13:35:36.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:37.036  1013  1360 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:35:37.036  1013  1360 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4193, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 13:35:37.036  1013  1360 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:35:37.036  1013  1360 D BatteryService: stay LED for charging
09-09 13:35:37.036  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:35:37.036  1013  1013 I MotionRecognitionService: Plugged
,09-09 13:35:37.036  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:35:37.046  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-09 13:35:37.046  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
09-09 13:35:37.046  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:35:37.046  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:35:37.056  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:35:37.056  2654  2726 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:37.066  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
09-09 13:35:37.066  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:37.066  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:37.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:38.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:38.706   290   290 E SMD     : DCD OFF,
,09-09 13:35:38.936  1013  1356 I ActivityManager: Killing 5353:com.google.android.talk/u0a104 (adj 15): empty #31
,09-09 13:35:39.066  1013  1046 I PowerManagerService: [PWL] Off : 50s ago,
,09-09 13:35:39.676   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-09 13:35:39.876  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-09 13:35:39.876  6233  6282 I jxcore-log: 
,09-09 13:35:39.876  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-09 13:35:39.876  6233  6282 I jxcore-log: 
,09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:39.886  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:39.886  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:39.886  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:35:39.886  6233  6282 I jxcore-log: 
,09-09 13:35:39.886  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:35:39.886  6233  6282 I jxcore-log: 
,09-09 13:35:39.936  1013  2727 D SSRM:n  : SIOP:: AP = 350
,09-09 13:35:40.536  6233  6282 I jxcore-log: Unit Test app is loaded
09-09 13:35:40.536  6233  6282 I jxcore-log: 
,09-09 13:35:40.546  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:35:40.546  6233  6282 I jxcore-log: 
,09-09 13:35:40.546  6233  6233 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:35:40.556  6233  6282 D executeNativeTests: Running unit tests
,09-09 13:35:40.556  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:40.556  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c5496d2 added. We now have 2 listener(s)
,09-09 13:35:40.566  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:35:40.566  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:40.566  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:40.566  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:35:40.566  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6463a3 added. We now have 2 listener(s)
,09-09 13:35:40.566  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:40.566  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:40.566  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:40.576  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:40.576  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:40.576  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:40.576  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:40.586  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:35:41.706   290   290 E SMD     : DCD OFF,
,09-09 13:35:44.706   290   290 E SMD     : DCD OFF,
,09-09 13:35:47.096  1013  1360 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-09 13:35:47.096  1013  1360 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 13:35:47.096  1013  1360 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:35:47.096  1013  1360 D BatteryService: stay LED for charging,
09-09 13:35:47.096  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:35:47.096  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-09 13:35:47.096  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:35:47.106  1013  1013 I MotionRecognitionService: Plugged
09-09 13:35:47.106  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
09-09 13:35:47.106  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:35:47.106  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-09 13:35:47.106  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:35:47.106  2654  2726 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:47.126  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2,
09-09 13:35:47.126  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
09-09 13:35:47.126  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:47.656  1013  2771 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 13:35:47.706   290   290 E SMD     : DCD OFF,
,09-09 13:35:49.366  1013  1324 E Watchdog: !@Sync 4
,09-09 13:35:49.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:49.966  1013  2727 D SSRM:n  : SIOP:: AP = 330
,09-09 13:35:50.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:50.676  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:50.686  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 added. We now have 3 listener(s)
,09-09 13:35:50.686  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:35:50.686  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:50.686  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:50.686  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:50.686  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace added. We now have 3 listener(s)
09-09 13:35:50.686  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:50.686  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:50.686  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:50.696  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:50.696  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:50.696  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:50.696  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:50.696  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:50.696  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:35:50.696  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:50.696  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:50.696  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:50.706  6233  6282 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:35:50.706  6233  6282 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:35:50.706  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
09-09 13:35:50.706  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:50.706  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:50.706  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:50.706  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:50.706  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:50.706  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:50.706  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:50.706  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 removed from the list,
09-09 13:35:50.706  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:50.706  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace removed from the list
09-09 13:35:50.706  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:50.706  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:50.706  6233  6282 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:35:50.706  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:50.706  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:50.706  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:50.706  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:50.706  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:50.706  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:50.706  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:50.706  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:50.706  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:50.706   290   290 E SMD     : DCD OFF
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionMo,del: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:50.716  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:50.716  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:50.716  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:50.716  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:50.716  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:50.716  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:50.716  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:50.716  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:50.716  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:50.716  6233  6282 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:50.716  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:50.716  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:50.726  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:50.726  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:50.726  6233  6282 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:35:50.726  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:50.726  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:50.726  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:50.726  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:50.726  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:50.726  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:50.726  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:50.726  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:35:50.726  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:50.726  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:50.736  6233  6364 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:50.736  6233  6364 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:50.736  6233  6364 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-09 13:35:50.736  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:35:50.736  6233  6364 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:50.736  6233  6364 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:50.746  6233  6364 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e4875da
09-09 13:35:50.746  6233  6364 D BluetoothSocket: channel: 6
09-09 13:35:50.746  6233  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:35:50.746  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:35:50.746  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:35:50.746  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:35:50.746  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 7C F9 0E 37 96 AB
,09-09 13:35:50.746  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:50.746  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:50.746  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:35:50.756  2654  2664 D BtGatt.GattService: registerClient() - UUID=b9d8b42c-0e9c-404a-aed9-089ac1804442
,09-09 13:35:50.806  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=b9d8b42c-0e9c-404a-aed9-089ac1804442, clientIf=6
,09-09 13:35:50.806  6233  6241 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:50.816  2654  2724 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:50.846  2654  2724 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 3
,09-09 13:35:50.856  2654  2724 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:50.856  2654  2724 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:50.856  2654  2724 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:50.856  2654  2724 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:50.866  2654  2720 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:50.876  2654  2724 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:50.876  2654  2720 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:50.876  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:35:50.876  2654  2724 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:50.876  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:50.876  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:50.886  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:50.886  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:50.886  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:35:50.886  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:35:50.886  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:50.886  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:35:50.886  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:50.886  6233  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:50.886  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:35:50.896  6233  6282 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:50.896  6233  6282 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:35:50.896  6233  6282 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:35:50.896  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
,09-09 13:35:50.896  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
09-09 13:35:50.896  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:50.896  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:50.896  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:50.896  6233  6282 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e6d90e8, channel: 6, state: LISTENING
09-09 13:35:50.896  6233  6282 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e6d90e8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e4875da, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@323d9301mSocket: android.net.LocalSocket@1ac815a6 impl:android.net.LocalSocketImpl@22dfbe7 fd:FileDescriptor[106]
09-09 13:35:50.896  6233  6282 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ac815a6 impl:android.net.LocalSocketImpl@22dfbe7 fd:FileDescriptor[106],
09-09 13:35:50.896  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:50.896  6233  6364 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e6d90e8, channel: 6, state: CLOSED
09-09 13:35:50.896  6233  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:50.896  6233  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:35:50.896  6233  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
09-09 13:35:50.896  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:50.896  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:50.896  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:35:50.896  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:35:50.896  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:50.896  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:50.896  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:50.896  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:50.896  6233  6282 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:35:50.896  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:50.896  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:35:50.906  2654  2724 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:50.906  2654  2724 D BtGatt.AdvertiseManager: stop advertise for client 6,
09-09 13:35:50.906  2654  2724 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:35:50.906  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:50.906  2654  2720 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-09 13:35:50.906  2654  2720 D BtGatt.GattService: Client app is not null!
09-09 13:35:50.906  2654  2663 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:50.916  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:35:50.916  6233  6233 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:35:50.916  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:50.916  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:50.916  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:50.916  6233  6282 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:50.916  6233  6282 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,09-09 13:35:50.916  6233  6282 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-09 13:35:50.916  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:50.916  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:50.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:50.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:50.926  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:35:50.926  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:50.926  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:50.926  6233  6370 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:50.926  6233  6370 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:50.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:50.936  6233  6370 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,09-09 13:35:50.936  6233  6370 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:50.936  6233  6370 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:50.936  6233  6370 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364fe632
,09-09 13:35:50.936  6233  6370 D BluetoothSocket: channel: 6
,09-09 13:35:50.936  6233  6370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:35:50.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:35:50.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:35:50.936  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 7C F9 0E 37 96 AB
09-09 13:35:50.936  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:50.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:50.936  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:50.936  2654  2962 D BtGatt.GattService: registerClient() - UUID=355abcd6-93a6-46c0-bfb8-528c04db418f
,09-09 13:35:50.986  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=355abcd6-93a6-46c0-bfb8-528c04db418f, clientIf=6
,09-09 13:35:50.986  6233  6247 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:50.986  2654  2724 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:51.006  2654  2724 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 4
,09-09 13:35:51.006  2654  2724 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:51.006  2654  2724 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:51.006  2654  2724 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:51.006  2654  2724 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:51.016  2654  2720 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:51.016  2654  2724 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:51.026  2654  2720 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:51.026  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:51.026  2654  2724 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:51.026  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:51.026  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:51.026  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:51.026  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:51.036  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:51.036  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:35:51.036  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:51.036  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:35:51.036  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:51.036  6233  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:51.036  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:51.036  6233  6282 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:51.046  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:51.046  6233  6282 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3abf9500, channel: 6, state: LISTENING
,09-09 13:35:51.046  6233  6282 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3abf9500, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364fe632, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20f8a139mSocket: android.net.LocalSocket@3612337e impl:android.net.LocalSocketImpl@22e480df fd:FileDescriptor[107]
,09-09 13:35:51.046  6233  6282 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3612337e impl:android.net.LocalSocketImpl@22e480df fd:FileDescriptor[107]
09-09 13:35:51.046  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:35:51.046  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:51.046  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
,09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.046  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:51.046  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:51.046  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:35:51.046  6233  6370 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3abf9500, channel: 6, state: CLOSED
09-09 13:35:51.046  6233  6370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:51.046  6233  6370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:51.046  6233  6370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:51.046  6233  6282 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:51.046  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:51.046  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:35:51.046  2654  2724 D BtGatt.AdvertiseManager: message : 1
,09-09 13:35:51.046  2654  2724 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:35:51.046  2654  2724 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:35:51.056  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:51.056  2654  2720 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:35:51.056  2654  2720 D BtGatt.GattService: Client app is not null!
,09-09 13:35:51.056  2654  2961 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:35:51.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:35:51.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:35:51.066  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:51.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:35:51.066  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:51.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:51.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:51.066  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:51.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:51.066  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:51.076  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:51.076  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:35:51.076  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:51.076  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
,09-09 13:35:51.076  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.076  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.076  6233  6282 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:35:51.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:51.086  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:51.086  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:51.086  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:51.086  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:35:51.096  6233  6282 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3,
09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-09 13:35:51.096  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:51.096  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:51.096  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:51.096  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:51.096  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:51.096  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:35:51.096  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.096  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:35:51.106  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:51.106  6233  6373 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:51.106  6233  6373 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:51.106  6233  6373 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-09 13:35:51.106  6233  6373 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 13:35:51.106  6233  6373 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:51.106  6233  6373 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1aba4bfb
09-09 13:35:51.106  6233  6373 D BluetoothSocket: channel: 6
,09-09 13:35:51.106  6233  6373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:35:51.106  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:51.116  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:51.116  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:35:51.116  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:35:51.116  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 7C F9 0E 37 96 AB
,09-09 13:35:51.116  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:51.116  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:51.116  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:51.116  2654  2964 D BtGatt.GattService: registerClient() - UUID=b5a02986-f0c1-482f-9d14-090f85a98846
,09-09 13:35:51.166  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=b5a02986-f0c1-482f-9d14-090f85a98846, clientIf=6
,09-09 13:35:51.166  6233  6241 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:51.166  2654  2724 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:51.186  2654  2724 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 5
,09-09 13:35:51.186  2654  2724 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:51.186  2654  2724 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:51.186  2654  2724 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:51.186  2654  2724 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:51.196  2654  2720 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:51.196  2654  2724 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:51.206  2654  2720 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:51.206  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:51.206  2654  2724 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:51.206  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:51.206  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:51.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:51.216  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:51.216  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:51.216  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:35:51.216  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:35:51.216  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:35:51.216  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:51.216  6233  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:51.216  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:51.216  6233  6282 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:51.226  6233  6282 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:35:51.226  6233  6282 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 13:35:51.226  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:35:51.226  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:35:51.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:51.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:51.226  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:51.226  6233  6282 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26d03e71, channel: 6, state: LISTENING
,09-09 13:35:51.226  6233  6282 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26d03e71, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1aba4bfb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36173456mSocket: android.net.LocalSocket@2a57acd7 impl:android.net.LocalSocketImpl@34849c4 fd:FileDescriptor[106]
,09-09 13:35:51.226  6233  6282 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a57acd7 impl:android.net.LocalSocketImpl@34849c4 fd:FileDescriptor[106]
,09-09 13:35:51.226  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:35:51.226  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:51.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
09-09 13:35:51.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:51.226  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:51.226  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:35:51.226  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:51.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:51.226  6233  6373 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26d03e71, channel: 6, state: CLOSED
09-09 13:35:51.226  6233  6373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:51.226  6233  6373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
09-09 13:35:51.226  6233  6373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:51.226  6233  6282 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:51.226  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:51.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:35:51.236  2654  2724 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:51.236  2654  2724 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:35:51.236  2654  2724 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:35:51.236  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:51.236  2654  2720 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:35:51.236  2654  2720 D BtGatt.GattService: Client app is not null!
09-09 13:35:51.236  2654  2962 D BtGatt.GattService: unregisterClient() - clientIf=6,
09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:51.246  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:51.246  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:51.246  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:51.246  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:35:51.246  6233  6233 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:35:51.246  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-09 13:35:51.246  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:51.246  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:35:51.246  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:51.246  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.246  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:51.246  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.246  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.246  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.246  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:51.246  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.256  6233  6282 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:35:51.256  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.256  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.256  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.256  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.256  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.256  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list,
09-09 13:35:51.256  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.256  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.256  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.256  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:35:51.256  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.256  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.256  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.256  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
,09-09 13:35:51.256  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.256  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.256  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.256  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.256  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.256  6233  6282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 13:35:51.256  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.256  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.256  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.256  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.256  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:51.256  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.256  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:51.256  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.266  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.266  6233  6282 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-09 13:35:51.266  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.266  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.266  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.266  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.266  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:51.266  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.266  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.266  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:51.266  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.266  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:35:51.266  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:51.266  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:51.266  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:51.266  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:51.266  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-09 13:35:51.266  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:51.266  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:51.266  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:51.266  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.276  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.276  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.276  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.276  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.276  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:51.276  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.276  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.276  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 13:35:51.276  6233  6282 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:35:51.276  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-09 13:35:51.276  6233  6282 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:51.276  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:51.276  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:35:51.276  6233  6282 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:51.276  6233  6282 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-09 13:35:51.276  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:51.276  6233  6282 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:51.276  6233  6282 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:35:51.276  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:51.276  6233  6282 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:51.276  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:35:51.286  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:35:51.286  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55),
09-09 13:35:51.286  6233  6282 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:51.286  6233  6282 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.286  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.286  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.286  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:35:51.286  6233  6377 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1168)
09-09 13:35:51.286  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.286  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.286  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.286  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.286  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.286  6233  6282 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.286  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.286  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.286  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.286  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.286  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.286  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.286  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.296  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.296  6233  6378 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1168
,09-09 13:35:51.296  6233  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:35:51.296  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.296  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.296  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.296  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.296  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.296  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:51.296  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.296  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:35:51.296  6233  6282 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:51.296  6233  6282 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:51.296  6233  6282 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:51.296  6233  6282 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:51.296  6233  6282 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:51.296  6233  6282 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:35:51.296  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 13:35:51.296  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.296  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.296  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.296  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.296  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.296  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.296  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.296  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.296  6233  6377 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 13:35:51.296  6233  6377 D BluetoothSocket: connect(): myUserId = 0
09-09 13:35:51.296  6233  6377 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:51.296  6233  6282 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:51.296  2654  2663 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:51.296  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.306  6233  6377 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:51.306  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:51.306  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:51.306  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:51.306  6233  6282 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-09 13:35:51.306  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:51.306  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:51.306  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:51.306  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:51.306  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:51.306  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:51.306  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.316  6233  6379 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:51.316  6233  6379 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:51.316  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:51.316  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:51.316  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:35:51.316  6233  6379 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-09 13:35:51.316  6233  6379 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:51.316  6233  6379 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:51.316  6233  6379 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d623e30
09-09 13:35:51.316  6233  6379 D BluetoothSocket: channel: 6
09-09 13:35:51.316  6233  6379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:35:51.316  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-09 13:35:51.316  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:51.316  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:35:51.316  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:35:51.316  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 7C F9 0E 37 96 AB
,09-09 13:35:51.316  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:51.316  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:51.316  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:51.326  2654  2663 D BtGatt.GattService: registerClient() - UUID=ab1c499c-e47c-4b8b-9d21-7f5348ced725
,09-09 13:35:51.366  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=ab1c499c-e47c-4b8b-9d21-7f5348ced725, clientIf=6
,09-09 13:35:51.366  6233  6247 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:51.366  2654  2724 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:51.386  2654  2724 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 6
,09-09 13:35:51.386  2654  2724 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:51.386  2654  2724 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:51.386  2654  2724 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:51.386  2654  2724 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:51.386  2654  2720 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:51.396  2654  2724 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:51.396  2654  2720 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:51.396  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:51.396  2654  2724 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:51.396  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:35:51.396  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:35:51.396  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:51.406  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:51.406  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:51.406  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:35:51.406  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:35:51.406  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:35:51.406  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:51.406  6233  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:51.406  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:51.406  6233  6282 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:51.416  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:35:51.416  6233  6282 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34f0782e, channel: 6, state: LISTENING
,09-09 13:35:51.416  6233  6282 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34f0782e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d623e30, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30955fcfmSocket: android.net.LocalSocket@1be50d5c impl:android.net.LocalSocketImpl@1bc0e865 fd:FileDescriptor[106]
09-09 13:35:51.416  6233  6282 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1be50d5c impl:android.net.LocalSocketImpl@1bc0e865 fd:FileDescriptor[106]
,09-09 13:35:51.416  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:35:51.416  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:51.416  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:51.416  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:51.416  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:35:51.416  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:51.416  6233  6379 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34f0782e, channel: 6, state: CLOSED
09-09 13:35:51.416  6233  6379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:51.416  6233  6379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:51.416  6233  6379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:51.416  6233  6282 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:35:51.416  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:51.416  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:35:51.426  2654  2724 D BtGatt.AdvertiseManager: message : 1
,09-09 13:35:51.426  2654  2724 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:35:51.426  2654  2724 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:35:51.426  2654  2724 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:51.426  2654  2720 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:35:51.426  2654  2720 D BtGatt.GattService: Client app is not null!
,09-09 13:35:51.426  2654  2964 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:51.436  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:51.436  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:35:51.436  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:51.436  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:51.436  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:51.436  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:51.436  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:51.436  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.436  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.436  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.436  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.436  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.436  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
,09-09 13:35:51.436  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.446  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.446  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.446  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.446  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.446  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:35:51.446  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.446  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:51.446  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:35:51.446  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:35:51.446  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:35:51.446  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:51.446  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:35:51.446  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:51.446  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:35:51.456  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:35:51.456  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.456  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.456  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:51.456  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.456  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:35:51.456  6233  6383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:51.456  6233  6383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:51.456  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:51.456  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:51.456  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:51.456  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:51.456  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.456  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.456  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.456  6233  6282 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:35:51.456  6233  6282 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:35:51.456  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:51.456  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:35:51.456  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:51.456  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.456  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.456  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.456  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-09 13:35:51.456  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.456  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.456  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.456  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.466  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 13:35:51.466  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.466  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-09 13:35:51.466  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list
09-09 13:35:51.466  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.466  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
,09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.466  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.466  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.466  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.466  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.466  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.466  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57833c9 not in the list,
09-09 13:35:51.466  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.466  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6b7ace not in the list
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:51.466  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.466  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:51.466  6233  6282 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
09-09 13:35:51.466  6233  6282 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:51.466  6233  6282 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:35:51.466  6233  6282 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1,
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
09-09 13:35:51.466  6233  6282 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:35:51.466  6233  6282 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:35:51.466  6233  6282 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:35:51.466  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:51.466  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb229eb added. We now have 3 listener(s)
,09-09 13:35:51.476  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-09 13:35:51.476  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:51.476  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:51.476  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:51.476  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a63a348 added. We now have 3 listener(s)
09-09 13:35:51.476  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:51.476  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:51.476  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:51.486  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:51.486  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 13:35:51.486  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:51.486  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:35:51.486  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.486  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.486  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:51.486  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:51.486  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb229eb removed from the list
09-09 13:35:51.486  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.486  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a63a348 removed from the list
,09-09 13:35:51.486  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.486  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.486  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.496  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:51.496  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a835f06 added. We now have 3 listener(s)
,09-09 13:35:51.496  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:35:51.496  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:51.496  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:51.496  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:51.496  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58779c7 added. We now have 3 listener(s)
09-09 13:35:51.496  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:51.496  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:51.496  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:51.506  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:51.506  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:51.506  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:51.506  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:51.506  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:51.506  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:51.506  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:51.506  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a835f06 removed from the list
09-09 13:35:51.506  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:51.506  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58779c7 removed from the list
,09-09 13:35:51.506  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.506  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.506  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:51.506  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:51.516  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-09 13:35:51.516  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@359cbf1d added. We now have 3 listener(s)
,09-09 13:35:51.516  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:35:51.516  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:51.516  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:51.516  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:35:51.516  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3666592 added. We now have 3 listener(s)
09-09 13:35:51.516  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:51.516  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:51.526  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:51.526  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:51.526  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:51.526  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:51.536  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.536  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:51.536  1013  1638 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-09 13:35:51.536  1013  1638 D WifiService: setWifiEnabled: false pid=6233, uid=10155
09-09 13:35:51.536  1013  1638 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:51.536  1013  1638 D SecContentProvider2: mCursor = null
09-09 13:35:51.536  1013  1638 D SettingsProvider: name = wifi_on
,09-09 13:35:51.546  1013  1130 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:35:51.546  1994  1994 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:35:51.546  1994  1994 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 13:35:51.546  1994  1994 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:35:51.546  1994  1994 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:35:51.556  1013  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:35:51.566  1013  1130 E WifiNative-wlan0: do suspend true,
,09-09 13:35:51.676   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:51.726  1013  1125 D WifiP2pService: InactiveState{ what=143375 },
09-09 13:35:51.726  1013  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:51.726  1994  1994 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
,09-09 13:35:51.736  1013  1125 D WifiP2pService: InactiveState{ what=147461 },
09-09 13:35:51.736  1013  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
09-09 13:35:51.736  1013  1125 D WifiP2pService: DefaultState{ what=147461 }
,09-09 13:35:51.736  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:51.736  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:35:51.736  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.736  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.736  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.736  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.746   277   982 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:51.746  1907  4417 V NativeCrypto: Read error: ssl=0xb873e5d8: I/O error during system call, Connection timed out
,09-09 13:35:51.766  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:51.766  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:35:51.766  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,09-09 13:35:51.776  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:35:51.806  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:51.806  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:51.806  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.806  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:51.806  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.806  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.816  1013  1125 D WifiP2pService: InactiveState{ what=131204 },
09-09 13:35:51.816  1013  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 13:35:51.816  1013  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:35:51.816  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:35:51.816  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-09 13:35:51.816  1013  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:51.816  1013  1149 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:35:51.816  1013  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
,09-09 13:35:51.826  1013  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-09 13:35:51.836  1013  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:51.836  1013  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:51.836  1013  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:35:51.846  1013  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:35:51.846  1013  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:35:51.846  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 13:35:51.846  1013  1044 D WifiDisplayController: disconnect
09-09 13:35:51.846  1013  1044 D WifiDisplayController: updateConnection,
09-09 13:35:51.846  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-09 13:35:51.846  1013  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:51.846  1013  1125 D WifiP2pService: P2pDisablingState,
09-09 13:35:51.846  1013  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:35:51.846  1013  1125 D WifiP2pService: p2p socket connection lost
09-09 13:35:51.846  1013  1125 D WifiP2pService: P2pDisabledState
,09-09 13:35:51.846  1013  1130 E WifiNative-wlan0: do suspend true
,09-09 13:35:51.856  1013  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-09 13:35:51.856  1013  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:51.856  1013  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:51.856  1013  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:35:51.856  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:35:51.856  1013  1360 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:51.856  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:35:51.886  1013  1125 D WifiP2pService: P2pDisabledState{ what=143375 },
09-09 13:35:51.886  1013  1125 D WifiP2pService: DefaultState{ what=143375 },
09-09 13:35:51.886  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:51.886  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:51.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.896   277   982 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:35:51.896  1013  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 13:35:51.896  1013  2162 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:51.896  1013  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-09 13:35:51.896  1173  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:35:51.896  1013  1132 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:51.896  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:35:51.896  1013  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 13:35:51.896  1454  1454 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:51.896  1013  1132 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 13:35:51.896  1013  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 13:35:51.896  1013  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:35:51.906  3806  6291 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
,09-09 13:35:51.906  1994  1994 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:51.906  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:51.906  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:51.906  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.906  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.906  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.906  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.906  1013  1123 V NetworkStats: updateIfacesLocked()
09-09 13:35:51.906  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:51.906  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:51.906  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:51.906  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:35:51.916  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-09 13:35:51.916  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:51.926  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:51.926  1013  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:35:51.926  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:51.926  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:51.926  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:51.926  1013  1123 V NetworkStats: performPollLocked() took 15ms
,09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:51.926  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.926  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:51.926  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 13:35:51.926  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:35:51.926  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:51.926  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:51.936  1173  1173 D HotspotTile: onReceive : 0, 0
,09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:51.936  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:51.946  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:51.946  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:51.956  1013  1075 I art     : Explicit concurrent mark sweep GC freed 39278(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 28MB/42MB, paused 4.298ms total 204.437ms,
09-09 13:35:51.956  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:51.956  1013  1541 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:51.956  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:51.956  1013  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 13:35:51.966  1907  4417 V NativeCrypto: SSL shutdown failed: ssl=0xb873e5d8: I/O error during system call, Broken pipe
,09-09 13:35:51.966  1013  1132 D ConnectivityService: nai.networkMonitor.doQuit()
,09-09 13:35:51.966  1013  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 13:35:51.966  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:51.966  1013  1132 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 13:35:51.966  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:51.966  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:35:51.966  1907  4417 E GCM     : Wifi connection closed with errorCode 20
,09-09 13:35:51.966  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:51.966  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:51.966  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:51.966  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:51.966  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:51.976  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:51.976  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:51.976  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:51.976  1013  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:35:51.976  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:51.976  3578  3578 I Hs20UtilService: Starting #8
,09-09 13:35:51.976  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:35:51.976  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:35:51.976  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:35:51.976  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:35:51.976  1013  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 13:35:51.976  1013  1133 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:51.976  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:51.986  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:51.986  6233  6233 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:35:51.986  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:51.986  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:51.986  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:51.986  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:51.986  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:51.986  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:51.986  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:52.016  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:35:52.016  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:52.016  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:52.026  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:52.026  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 13:35:52.026  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:52.026  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:52.026  1013  1075 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 13:35:52.036  1013  1075 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.036  1013  1075 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.036  1013  1075 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.036  1013  1075 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.046  6392  6392 E Zygote  : MountEmulatedStorage(),
09-09 13:35:52.046  6392  6392 E Zygote  : v2
09-09 13:35:52.046  6392  6392 I libpersona: KNOX_SDCARD checking this for 10068
09-09 13:35:52.046  6392  6392 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:52.046  6392  6392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:35:52.046  1013  1075 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6392 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:52.046  6392  6392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:52.046  6392  6392 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:35:52.056  1013  3228 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:35:52.056  1013  3228 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:52.056  1013  3228 D SecContentProvider2: mCursor = null
,09-09 13:35:52.056  1013  3228 D WifiService: setWifiEnabled: true pid=6233, uid=10155
09-09 13:35:52.056  1013  3228 W ActivityManager: Permission Denial: getCurrentUser() from pid=6233, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:35:52.056  1013  3228 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:35:52.056  1013  3228 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6233, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:52.056  1013  3228 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 13:35:52.056  1013  3228 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:35:52.056  1013  3228 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:35:52.056  1013  3228 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:35:52.056  1013  3228 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:35:52.056  1013  3228 D SettingsProvider: name = wifi_on
,09-09 13:35:52.076  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.076  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.076  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.086  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.086  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.086  1994  1994 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:52.086  6392  6392 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:52.086  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.086  6392  6392 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:52.086  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.086  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.086  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.086  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.096  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.096  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.096  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.096  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.096  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.096  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.096  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.096  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.096  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.106  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.106  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.106  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.106  6392  6392 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:35:52.106  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.106  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:52.106  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.106  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.106  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.116  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:52.116  1994  1994 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:35:52.116  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:52.116  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:35:52.116  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:35:52.116  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:52.116  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:52.126  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:52.136  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:35:52.156  6392  6392 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:35:52.156  1013  1638 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 13:35:52.166  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.166  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.166  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.166  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.176  6424  6424 E Zygote  : MountEmulatedStorage()
,09-09 13:35:52.176  1013  1638 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6424 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:52.176  6424  6424 E Zygote  : v2
,09-09 13:35:52.176  6424  6424 I libpersona: KNOX_SDCARD checking this for 10069
09-09 13:35:52.176  6424  6424 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:52.176  1013  1638 I ActivityManager: Killing 5047:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,09-09 13:35:52.176  6424  6424 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:52.186  6424  6424 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:35:52.186  6424  6424 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:52.196  6424  6424 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:52.196  6424  6424 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:52.206  1994  1994 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 13:35:52.206  1994  1994 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 13:35:52.206  1994  1994 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:35:52.206  1994  1994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 13:35:52.206  1994  1994 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:52.216  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:52.216  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:52.216  1013  1130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-09 13:35:52.216  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:52.216  1013  1133 D Tethering: InitialState.processMessage what=4
,09-09 13:35:52.216  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:52.216  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:52.216  1013  1133 E Tethering: No numeric data
,09-09 13:35:52.216  1013  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:52.216  1013  1133 D Tethering: clearTetheredNotification()
09-09 13:35:52.216  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:52.216  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.216  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:52.216  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:52.216  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:35:52.216  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:52.216  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:52.216  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:52.216  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:52.226  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:52.226  1013  1123 V NetworkStats: performPollLocked() took 5ms
09-09 13:35:52.226  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:52.226  6424  6424 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:52.226  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.226  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:52.236  1013  1541 I ActivityManager: Killing 5501:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-09 13:35:52.236  1013  3214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:52.236  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:52.246  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.246  1013  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.246  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:52.246  3578  3578 I Hs20UtilService: Starting #9
,09-09 13:35:52.246  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:52.246  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:35:52.246  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:35:52.246  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:52.246  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:52.246  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:52.246  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:52.246  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:52.256  1013  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:52.256  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:52.256  1013  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.256  1013  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.256  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:52.256  1013  3230 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-09 13:35:52.256  3578  3578 I Hs20UtilService: Starting #10
,09-09 13:35:52.256  3578  3598 I Hs20UtilService: Message received 5011
09-09 13:35:52.256  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.256  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.256  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.256  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.266   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75f67c8
09-09 13:35:52.266   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-09 13:35:52.266   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
09-09 13:35:52.266   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1218484088)
,09-09 13:35:52.276  6439  6439 E Zygote  : MountEmulatedStorage()
,09-09 13:35:52.286  6439  6439 E Zygote  : v2
09-09 13:35:52.286  6439  6439 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:52.286  6439  6439 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:52.286  1013  3230 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 13:35:52.286  6439  6439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:52.286  6439  6439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:52.286  6439  6439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:35:52.316   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
09-09 13:35:52.316   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-09 13:35:52.316   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1218484088) wakelock released: 1, error no: 0
,09-09 13:35:52.316   271   302 I rmt_storage: 
09-09 13:35:52.316   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75f67c8
,09-09 13:35:52.316  6439  6439 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:52.316  6439  6439 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:52.346  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
,09-09 13:35:52.346  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:52.346  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:35:52.346  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:52.346  1013  2967 I ActivityManager: Killing 5592:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-09 13:35:52.356  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.356  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.356  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.366  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.366  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.366  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.366  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.366  1013  1013 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:52.366  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-09 13:35:52.366  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-09 13:35:52.366  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.366  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.366  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.366  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.376  6455  6455 E Zygote  : MountEmulatedStorage(),
,09-09 13:35:52.376  6455  6455 E Zygote  : v2
09-09 13:35:52.376  6455  6455 I libpersona: KNOX_SDCARD checking this for 10104
,09-09 13:35:52.376  6455  6455 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:52.386  6455  6455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:35:52.386  1013  1013 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6455 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,09-09 13:35:52.386  6455  6455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:35:52.386  6455  6455 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:52.406  1013  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:52.416  1013  1013 I ApplicationPolicy: updateDataUsageMap
,09-09 13:35:52.426  1994  1994 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 13:35:52.426  6455  6455 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:52.426  6455  6455 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:52.436  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:52.436  3142  3142 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-09 13:35:52.436  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:52.436  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:52.436  3142  3142 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-09 13:35:52.456  6455  6455 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:35:52.456  1013  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:52.516  1994  1994 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 13:35:52.526  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:52.526  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:52.526  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:52.526  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 13:35:52.526  1013  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:35:52.526  1013  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:35:52.536  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:52.536  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:52.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:52.536  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:52.536  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 13:35:52.536  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:52.546  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:52.546  1907  2131 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:52.546  1173  1173 D HotspotTile: onReceive : 1, 0
,09-09 13:35:52.546  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:52.546  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:52.546  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:52.546  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:52.656  6455  6478 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-09 13:35:52.656  6455  6478 I Babel   : MmsConfig.loadMmsSettings
09-09 13:35:52.656  6455  6478 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-09 13:35:52.656  6455  6478 I Babel   : MmsConfig.loadFromDatabase
,09-09 13:35:52.666  6455  6478 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 13:35:52.666  6455  6478 I Babel   : MmsConfig.loadFromResources
,09-09 13:35:52.666  6455  6478 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:35:52.666  6455  6478 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-09 13:35:52.676  1013  1075 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-09 13:35:52.676  1013  1075 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 13:35:52.676  1013  1075 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.676  1013  1075 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:52.676  1013  1075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:35:52.676  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:52.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:52.726  6455  6455 I Babel_StickerModule: App launched.
,09-09 13:35:52.736  1013  3228 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.736  1013  3228 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.736  1013  3228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.746   285   695 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-09 13:35:52.746   285   695 W QCamera2Factory: getCameraInfo: X
,09-09 13:35:52.746   285   285 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,09-09 13:35:52.746   285   285 W QCamera2Factory: getCameraInfo: X
,09-09 13:35:52.756  6455  6455 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:52.766  6455  6455 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:35:52.766  6455  6455 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:35:52.766  6455  6455 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-09 13:35:52.766  6455  6455 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 13:35:52.776  6455  6455 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 13:35:52.776  6455  6455 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 13:35:52.776  6455  6455 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:35:52.776  6455  6455 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:35:52.786  6455  6455 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:35:52.786  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:35:52.796  6455  6455 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 13:35:52.796  6455  6455 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:35:52.796  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:35:52.796  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 13:35:52.806  6455  6455 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-09 13:35:52.806  6455  6455 W VideoCapabilities: Unsupported mime video/mp43
,09-09 13:35:52.816  6455  6455 W VideoCapabilities: Unsupported mime video/sorenson
,09-09 13:35:52.816  6455  6455 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:35:52.826  6455  6455 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:35:52.856  1013  1541 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-09 13:35:52.856  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-09 13:35:52.856  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.856  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:52.856  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:35:52.866  1013  2968 I ActivityManager: Killing 5119:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-09 13:35:52.906  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.906  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.906  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.906  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.906  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.906  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.916  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.916  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.916  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.916  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.916  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.926  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.926  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.926  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.926  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.926  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.926  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.926  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.926  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.926  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.936  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.936  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.936  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.936  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.936  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.936  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.936  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.936  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.936  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:52.946  5813  5813 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:35:52.946  5813  5813 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:35:52.946  5813  5813 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:35:52.946  5813  5813 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:52.946  1013  1540 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-09 13:35:52.946  1013  1540 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:35:52.946  1013  1540 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-09 13:35:52.956  5813  6481 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 13:35:52.956  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.956  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.956  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.956  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.966  1013  1540 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6483 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:52.966  6483  6483 E Zygote  : MountEmulatedStorage()
09-09 13:35:52.966  6483  6483 E Zygote  : v2
09-09 13:35:52.966  6483  6483 I libpersona: KNOX_SDCARD checking this for 10111
09-09 13:35:52.966  6483  6483 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:52.966  6483  6483 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:52.976  6483  6483 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:52.976  1013  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-09 13:35:52.976  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.976  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.976  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:52.976  6483  6483 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:35:52.976  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:52.996  6495  6495 E Zygote  : MountEmulatedStorage()
09-09 13:35:52.996  6495  6495 I libpersona: KNOX_SDCARD checking this for 10009
09-09 13:35:52.996  6495  6495 E Zygote  : v2
09-09 13:35:52.996  6495  6495 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:52.996  6495  6495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:52.996  6483  6483 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 13:35:52.996  6483  6483 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:52.996  6495  6495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:52.996  6495  6495 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.006  1013  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6495 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-09 13:35:53.006  1724  1724 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:53.006  1013  1041 D Tethering: interfaceRemoved wlan0
09-09 13:35:53.006  1013  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:35:53.016  1013  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-09 13:35:53.016  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.016  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.016  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.016  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.026  6495  6495 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:53.026  6495  6495 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.036  6510  6510 E Zygote  : MountEmulatedStorage()
09-09 13:35:53.036  6510  6510 E Zygote  : v2
09-09 13:35:53.036  6510  6510 I libpersona: KNOX_SDCARD checking this for 10145
09-09 13:35:53.036  6510  6510 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:53.036  6510  6510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:53.036  1013  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6510 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-09 13:35:53.036  6510  6510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:53.036  6510  6510 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.056  1724  1724 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:35:53.056  1724  1724 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-09 13:35:53.056  1724  1724 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-09 13:35:53.056  1724  1724 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:53.066  1724  1724 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:53.066  1724  1724 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 13:35:53.076  6510  6510 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:53.076  6510  6510 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:53.076  1013  2968 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
09-09 13:35:53.076  1294  1866 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,09-09 13:35:53.076  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.076  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.076  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.076  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.076  1013  1041 D Tethering: interfaceRemoved p2p0
,09-09 13:35:53.086  1013  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:35:53.096  6528  6528 E Zygote  : MountEmulatedStorage(),
09-09 13:35:53.096  6528  6528 E Zygote  : v2
09-09 13:35:53.096  6528  6528 I libpersona: KNOX_SDCARD checking this for 10081
09-09 13:35:53.096  6528  6528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:35:53.096  6528  6528 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:53.096  1013  2968 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6528 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:53.106  6528  6528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:35:53.106  6528  6528 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
09-09 13:35:53.116  1724  1724 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
09-09 13:35:53.116  6528  6528 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:53.116  6528  6528 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.126  6510  6510 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:35:53.126  6510  6510 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:35:53.126  6510  6510 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:35:53.126  6510  6510 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:35:53.126  6510  6510 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:35:53.156  1013  3230 I ActivityManager: Killing 5830:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-09 13:35:53.156  3601  3601 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:35:53 GMT+02:00 2016
,09-09 13:35:53.166  1013  3214 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:35:53.166  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.166  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:53.166  1013  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:53.166  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
09-09 13:35:53.166  3601  3601 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:35:53.176  3601  3601 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 13:35:53.176  1013  1540 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 13:35:53.176  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.176  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.176  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.176  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.176  3601  3601 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:35:53.176  3601  3601 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:35:53.186  3601  6546 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:35:53.186  3601  6546 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:53.196  6483  6483 I MusicStore: Database version: 108,
,09-09 13:35:53.196  6549  6549 E Zygote  : MountEmulatedStorage(),
09-09 13:35:53.196  6549  6549 E Zygote  : v2
09-09 13:35:53.196  6549  6549 I libpersona: KNOX_SDCARD checking this for 10034,
09-09 13:35:53.196  6549  6549 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.196  6549  6549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:35:53.196  3601  6546 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 13:35:53.196  1013  1540 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6549 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-09 13:35:53.206  6549  6549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:53.206  3601  6546 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 13:35:53.206  6549  6549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.206  3601  3601 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 13:35:53.216  1013  1360 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.216  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:53.216  6549  6549 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.236  1013  1541 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.236  1013  1360 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:53.236  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:35:53.236  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.236  1013  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:53.236  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.256  1013  2968 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 13:35:53.256  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.256  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.256  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.256  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.256  6549  6549 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 13:35:53.266  6568  6568 E Zygote  : MountEmulatedStorage(),
09-09 13:35:53.266  6568  6568 E Zygote  : v2,
09-09 13:35:53.276  6568  6568 I libpersona: KNOX_SDCARD checking this for 10113
,09-09 13:35:53.276  6568  6568 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.276  1013  2968 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6568 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:53.276  6568  6568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:35:53.276  1013  2968 I ActivityManager: Killing 5525:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
09-09 13:35:53.276  1013  1356 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.276  6568  6568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:53.276  6568  6568 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.276  1013  2968 I ActivityManager: Killing 5847:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-09 13:35:53.306  6568  6568 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:53.306  6568  6568 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.316  3190  6587 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 13:35:53.316  3190  6587 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 13:35:53.316  3190  6587 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 13:35:53.316  1013  1962 V SAMP_SPCM_test: CSC File load.. 
,09-09 13:35:53.326  3190  6587 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 13:35:53.326  3190  6587 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:35:53.326  5881  5881 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-09 13:35:53.336  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-09 13:35:53.336  1013  1025 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.356  6483  6483 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:35:53.356  6483  6483 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:35:53.366  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-09 13:35:53.376  1013  1962 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:35:53.376  1013  1962 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-09 13:35:53.386  6057  6057 I SA      : [DM] init START
09-09 13:35:53.386  1013  3214 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:35:53.386  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-09 13:35:53.386  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:53.396  1013  3214 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:35:53.396  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-09 13:35:53.406  5993  6003 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-09 13:35:53.416  6057  6057 I SA      : [DM] This device is not a Vodafone
09-09 13:35:53.416  1013  1962 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
09-09 13:35:53.416  1013  1360 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
09-09 13:35:53.416  6057  6057 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-09 13:35:53.426  1477  1477 D Launcher.Model: reloadBadges entered.
,09-09 13:35:53.436  5993  6003 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 13:35:53.436  5993  6003 D BadgeProvider: sendNotify, [notify] : null
09-09 13:35:53.436  5993  6003 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 13:35:53.436  5993  6003 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:35:53.436  5993  6003 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:35:53.436  6057  6057 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:35:53.436  6057  6057 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-09 13:35:53.436  6057  6057 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-09 13:35:53.436  6057  6057 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-09 13:35:53.436  1013  3230 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.436  5881  6590 E SPPClientService: [[SystemStateMonitorService]] No Active Internet,
,09-09 13:35:53.446  6483  6483 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
09-09 13:35:53.456  6057  6057 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-09 13:35:53.466  6057  6057 I SA      : [SCU] isHaveSA() - false
09-09 13:35:53.466  6057  6057 I SA      : support phone number id : false
09-09 13:35:53.466  6057  6057 I SA      : [DM] Supports Ref Jpn : true
,09-09 13:35:53.466  6057  6057 I SA      : [DM] init END
09-09 13:35:53.466  6057  6057 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 13:35:53.476  6057  6057 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 13:35:53.476  6057  6057 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:35:53.476  1013  2968 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.486  6057  6057 I SA      : [SLFUCHKMGR] constructor called
,09-09 13:35:53.486  1013  3230 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.486  6057  6057 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:35:53.486  6057  6057 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:35:53.496  6057  6057 I SA      : [SCU] == networkStateCheck == false
09-09 13:35:53.496  6057  6057 I SA      : [OR] onReceive END
,09-09 13:35:53.496  1221  1221 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:53.506  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:53.506  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:53.506  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:53.506  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:53.506  1013  2967 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-09 13:35:53.506  1013  2967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.506  1013  2967 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.506  1013  2967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.506  1013  2967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.526  6597  6597 E Zygote  : MountEmulatedStorage(),
09-09 13:35:53.526  6597  6597 I libpersona: KNOX_SDCARD checking this for 10159
09-09 13:35:53.526  6597  6597 E Zygote  : v2
09-09 13:35:53.526  6597  6597 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.526  6597  6597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:35:53.526  1013  2967 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6597 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:53.526  6483  6483 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:35:53.526  6483  6483 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19ea46a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:35:53.526  6483  6483 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:35:53.526  6483  6483 D AndroidMusic: GMSCore installation verified
,09-09 13:35:53.526  6597  6597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:53.536  6597  6597 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,09-09 13:35:53.546   312   312 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 22.699ms
,09-09 13:35:53.556  6597  6597 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:53.566  6597  6597 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:53.566  1013  1541 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:35:53.566  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-09 13:35:53.566   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.608ms
09-09 13:35:53.566  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:53.566  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.566  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.586  6483  6483 I ConfigStore: Config Database version: 1
,09-09 13:35:53.596   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 19.078ms
,09-09 13:35:53.616  1013  1317 I ActivityManager: Killing 5560:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-09 13:35:53.616  1013  3229 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:53.626  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.626  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.626  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:53.626  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:53.636  3806  3806 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:35:53.646  3806  4608 I iu.UploadsManager: num queued entries: 0
,09-09 13:35:53.646  3806  4608 I iu.UploadsManager: num updated entries: 0
,09-09 13:35:53.646  3806  4608 I iu.SyncManager: NEXT; no task
,09-09 13:35:53.666   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 13:35:53.666   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.666  6483  6483 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 13:35:53.676   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 13:35:53.676   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.676  6483  6483 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 13:35:53.676   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 13:35:53.676   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.676  6483  6483 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 13:35:53.686   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:35:53.686   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.686  6568  6615 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
09-09 13:35:53.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...
09-09 13:35:53.686  1013  2967 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-09 13:35:53.686  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.686  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.686  1013  2967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.686  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.696   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:35:53.696   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.696  6568  6615 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:35:53.696  1013  2968 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:53.706  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-09 13:35:53.706  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.706  1013  2968 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:53.706  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.706   290   290 E SMD     : DCD OFF
,09-09 13:35:53.716   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:35:53.716   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.716  6568  6619 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:35:53.716   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:35:53.716   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:53.716  6568  6619 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:35:53.736  1013  3230 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:35:53.736  1013  3228 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:35:53.736  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:35:53.736  1013  1130 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:35:53.746  1013  3230 I AudioService: getStreamVolume 3 index 0
,09-09 13:35:53.746  6483  6483 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:35:53.756  6483  6483 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:35:53.786  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-09 13:35:53.786  1013  3228 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 13:35:53.786  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.786  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.796  1013  2967 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:53.796  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:35:53.796  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.796  1013  2967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.796  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.796  1013  3229 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:53.796  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.806  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.806  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.806  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.806  1013  1541 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:53.806  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.806  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.806  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.806  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.816  1013  3228 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:35:53.826  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 13:35:53.826  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.826  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.826  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.826  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.846  6636  6636 E Zygote  : MountEmulatedStorage()
09-09 13:35:53.846  6636  6636 E Zygote  : v2
,09-09 13:35:53.846  6636  6636 I libpersona: KNOX_SDCARD checking this for 10002
09-09 13:35:53.846  6636  6636 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.846  6636  6636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:53.846  1013  1013 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6636 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:53.846  6636  6636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:53.846  6636  6636 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.866  6636  6636 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:53.866  6636  6636 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.886  1013  1317 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
09-09 13:35:53.886  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.886  1013  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.886  1013  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.886  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 13:35:53.896  6483  6483 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-09 13:35:53.896  1013  3229 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:53.906  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:35:53.906  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.906  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.906  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:53.916  1013  3230 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:53.916  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.916  1013  3230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.916  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 13:35:53.926  6568  6568 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-09 13:35:53.936  6568  6568 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3018-3019)
,09-09 13:35:53.946  6568  6568 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:35:53.956  1013  1026 I ActivityManager: Killing 5896:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-09 13:35:53.956  6568  6568 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {226e2b06}
,09-09 13:35:53.956  6568  6568 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:35:53.956  6568  6568 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:35:53.956  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 13:35:53.966  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.966  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.966  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.966  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.986  6660  6660 E Zygote  : MountEmulatedStorage()
,09-09 13:35:53.986  6660  6660 E Zygote  : v2
09-09 13:35:53.986  6660  6660 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:53.986  6660  6660 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.986  6568  6568 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:35:53.986  6568  6568 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:35:53.986  1013  1025 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 13:35:53.986  6660  6660 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:53.986  6568  6568 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:35:53.996  6660  6660 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:53.996  6660  6660 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:35:54.006  6568  6568 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-09 13:35:54.016  6660  6660 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:54.016  6568  6568 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-09 13:35:54.016  6568  6568 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-09 13:35:54.016  6660  6660 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:54.016  6568  6568 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:54.016  6568  6568 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:54.016  6568  6568 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:54.016  6568  6568 I Adreno-EGL: Local Branch: 
09-09 13:35:54.016  6568  6568 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:54.016  6568  6568 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:54.016  6568  6568 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:54.056  6660  6660 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 13:35:54.076  6568  6689 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:35:54.076  6568  6568 I NSApplication: Starting up...
,09-09 13:35:54.086  1013  1638 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 13:35:54.086  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:54.096  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.096  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.096  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:54.106  6694  6694 E Zygote  : MountEmulatedStorage()
,09-09 13:35:54.106  6694  6694 E Zygote  : v2
09-09 13:35:54.106  6694  6694 I libpersona: KNOX_SDCARD checking this for 10120
09-09 13:35:54.106  6694  6694 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:54.106  6694  6694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:54.106  6694  6694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:35:54.106  1013  1638 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6694 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,09-09 13:35:54.106  6694  6694 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:35:54.106  1013  1638 I ActivityManager: Killing 5919:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
09-09 13:35:54.106  1013  1638 I ActivityManager: Killing 6009:com.sec.android.app.myfiles/u0a47 (adj 15): empty #32
09-09 13:35:54.116  1013  1638 I ActivityManager: Killing 5793:com.android.mms/u0a46 (adj 15): empty #33
,09-09 13:35:54.136  6694  6694 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:54.136  6694  6694 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:54.156  1013  1041 D Tethering: interfaceAdded wlan0,
09-09 13:35:54.156  6694  6694 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:54.156  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 13:35:54.156  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:54.156  1013  1133 E Tethering: No numeric data
09-09 13:35:54.156  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:54.166  1013  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:54.166  1013  1133 D Tethering: clearTetheredNotification()
09-09 13:35:54.166  1013  1133 D Tethering: InitialState.processMessage what=4
,09-09 13:35:54.166  1013  1041 D Tethering: interfaceAdded p2p0
,09-09 13:35:54.166  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:35:54.166  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:54.166  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:54.166  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:54.166  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:54.166  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:35:54.166  1013  1133 E Tethering: No numeric data
,09-09 13:35:54.166  1013  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:35:54.166  1013  1133 D Tethering: clearTetheredNotification()
,09-09 13:35:54.176  1013  1123 V NetworkStats: performPollLocked() took 6ms,
09-09 13:35:54.176  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:35:54.176  1013  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 13:35:54.176  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 13:35:54.176  1013  1041 D Tethering: interfaceStatusChanged p2p0, false,
09-09 13:35:54.176  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:35:54.176  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:54.176  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:35:54.176  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:54.176  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:54.176  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:54.176  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:54.186  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:54.186  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:54.186   277   982 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-09 13:35:54.186   277   982 D SoftapController: Softap fwReload - Ok
,09-09 13:35:54.186   277   982 D CommandListener: Setting iface cfg
09-09 13:35:54.186   277   982 D CommandListener: Trying to bring down wlan0
,09-09 13:35:54.186   277   982 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:54.186  1013  1123 V NetworkStats: performPollLocked() took 8ms
09-09 13:35:54.186  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:54.186  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:54.196  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:54.196  1013  1130 E WifiHW  : supplicant_name : p2p_supplicant,
,09-09 13:35:54.196  1013  1638 D CountryDetector: No listener is left
,09-09 13:35:54.196  6660  6660 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 13:35:54.206  1013  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:35:54.216  6660  6660 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 13:35:54.216  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:54.216  6660  6660 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:54.216  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:54.216  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:54.216  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:54.216  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:54.216  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:54.216  6660  6660 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:35:54.216  6660  6660 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-09 13:35:54.216  6660  6660 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:35:54.216  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:54.216  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:35:54.216  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:35:54.216  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:54.216  1173  1173 D HotspotTile: onReceive : 2, 0
,09-09 13:35:54.226  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:54.226  1013  2967 I ActivityManager: Killing 6035:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-09 13:35:54.226  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:54.236  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:54.236  6710  6710 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 13:35:54.236  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.236  6710  6710 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:35:54.236  6710  6710 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:35:54.256  6710  6710 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-09 13:35:54.256   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6710
09-09 13:35:54.256   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:35:54.256  6710  6710 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:35:54.256  6710  6710 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:54.256  6710  6710 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:35:54.256  6710  6710 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 13:35:54.256   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6710
09-09 13:35:54.256   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 13:35:54.416   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-09 13:35:54.426  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-09 13:35:54.476  1013  3230 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 13:35:54.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:54.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:54.496  1013  3230 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6718 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 13:35:54.496  1013  3230 I ActivityManager: Killing 6073:com.wsomacp/u0a25 (adj 15): empty #31
,09-09 13:35:54.506  6710  6710 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-09 13:35:54.506  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
09-09 13:35:54.506  6718  6718 I libpersona: KNOX_SDCARD checking this for 10125
09-09 13:35:54.506  6718  6718 E Zygote  : MountEmulatedStorage()
09-09 13:35:54.506  6718  6718 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:54.506  6718  6718 E Zygote  : v2
,09-09 13:35:54.506  6718  6718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:35:54.506  6718  6718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:35:54.506  6718  6718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:35:54.516  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 13:35:54.516   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6710
09-09 13:35:54.516   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:35:54.516  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:35:54.516  6710  6710 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:54.516  6710  6710 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:54.516  6710  6710 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:54.516  6710  6710 E wpa_supplicant: SIM READ ERROR
09-09 13:35:54.516  6710  6710 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:54.516  6710  6710 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:54.516  6710  6710 E wpa_supplicant: SIM READ ERROR
09-09 13:35:54.516  6710  6710 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:54.516  6710  6710 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:35:54.516  6710  6710 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:35:54.516  6710  6710 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:54.516  6710  6710 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:35:54.516  6710  6710 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:54.516  6710  6710 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:35:54.526  6710  6710 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:35:54.526  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:54.526  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:54.526  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:54.526  6718  6718 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:54.526  6718  6718 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:54.536  6718  6718 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:54.546  6718  6718 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:35:54.546  6718  6718 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:35:54.556  6718  6718 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:54.556  6718  6718 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 13:35:54.556  6718  6718 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:35:54.566  1013  3229 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:35:54.566  1013  3229 I ActivityManager: Killing 5864:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-09 13:35:54.566  1013  1360 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:54.566  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:54.566  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:54.566  1013  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:54.566  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:54.576  3578  3578 I Hs20UtilService: Starting #11
,09-09 13:35:54.576  3578  3598 I Hs20UtilService: Message received 5011
,09-09 13:35:54.576  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:54.576  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:54.576  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:54.576  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:54.586  1013  3228 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:54.586  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:54.586  1013  3228 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:54.586  1013  3228 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:54.586  1013  3228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:54.586  3578  3578 I Hs20UtilService: Starting #12
,09-09 13:35:54.586  3578  3598 I Hs20UtilService: Message received 5011
,09-09 13:35:54.586  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:54.586  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:54.586  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:54.586  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:54.606  6710  6710 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-09 13:35:54.686   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-09 13:35:54.846  6710  6710 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
09-09 13:35:54.846  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:35:54.856  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-09 13:35:54.856   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6710
09-09 13:35:54.856   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:35:54.866  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-09 13:35:54.866  6710  6710 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:54.866  6710  6710 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 13:35:54.866  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:35:54.876  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 13:35:54.876   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6710
09-09 13:35:54.876   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-09 13:35:54.876  6710  6710 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:35:54.876  6710  6710 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:54.876  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:54.876  6710  6710 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:54.876  6710  6710 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:54.876  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:54.876  6710  6710 E wpa_supplicant: SIM READ ERROR
09-09 13:35:54.876  6710  6710 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:35:54.876  6710  6710 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:35:54.876  6710  6710 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:35:54.876  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:54.876  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:35:54.876  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:54.876  1013  1041 D Tethering: interfaceStatusChanged p2p0, false,
,09-09 13:35:54.926  6710  6710 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 13:35:54.926  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:35:54.986  6710  6710 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 13:35:54.986  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-09 13:35:54.986  6710  6710 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:35:54.996  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-09 13:35:54.996  1013  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:35:54.996  6710  6710 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-09 13:35:54.996  6710  6710 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 13:35:54.996  6710  6710 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:35:55.006  6710  6710 E wpa_supplicant: SIM READ ERROR
09-09 13:35:55.006  6710  6710 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 13:35:55.016  6710  6710 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 13:35:55.036  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:55.036  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:55.036  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:55.036  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:55.036  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:35:55.036  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:55.036  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:55.036  1013  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
09-09 13:35:55.036  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:55.036  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 13:35:55.046  6710  6710 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:35:55.046  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:55.046  1013  1130 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:35:55.046  1173  1173 D HotspotTile: onReceive : 3, 0
,09-09 13:35:55.046  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.056  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.056  1013  1130 E WifiConfigStore: Not a HS20
,09-09 13:35:55.056  1013  1130 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:35:55.056  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.066  1013  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:35:55.066  1013  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:35:55.066  6710  6710 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:35:55.066  6710  6710 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:35:55.066  6710  6710 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:35:55.066  6710  6710 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:35:55.066  6710  6710 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:35:55.066  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:35:55.066  6710  6710 I wpa_supplicant: First Scan Start
09-09 13:35:55.066  6710  6710 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.066  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:55.066  1013  1130 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:35:55.066  1013  1130 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:35:55.066  1013  1130 I WifiNative-HAL: startHal
09-09 13:35:55.066  1013  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9c84c88c
09-09 13:35:55.066  1013  1130 I WifiNative-HAL: Could not start hal
,09-09 13:35:55.066  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:55.076  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:55.076  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:55.076  1013  1130 E WifiNative-wlan0: do suspend true
,09-09 13:35:55.076  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.076  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.076  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:55.076  1013  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 13:35:55.076  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:55.076  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 13:35:55.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.076  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.076  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:55.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:55.076  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@359cbf1d removed from the list
09-09 13:35:55.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.076  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3666592 removed from the list
,09-09 13:35:55.076  3578  3578 I Hs20UtilService: Starting #13
09-09 13:35:55.076  1013  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:35:55.076  1013  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:35:55.076  1013  1130 E WifiNative-wlan0: invaild command id : 215
,09-09 13:35:55.076  3578  3598 I Hs20UtilService: Message received 5011
09-09 13:35:55.076  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 13:35:55.076  1013  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.076   277   982 D CommandListener: Setting iface cfg
09-09 13:35:55.076   277   982 D CommandListener: Trying to bring up p2p0
09-09 13:35:55.076  1013  1148 I WifiNative-HAL: startHal
09-09 13:35:55.076  1013  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:35:55.076  1013  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dd049bc
09-09 13:35:55.076  1013  1148 I WifiNative-HAL: Could not start hal
09-09 13:35:55.076  1013  1148 E WifiScanningService: could not start HAL
,09-09 13:35:55.076  1013  1013 D RttService: SCAN_AVAILABLE : 3
,09-09 13:35:55.086  6710  6710 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:35:55.086  1013  1125 D WifiP2pService: P2pEnablingState
,09-09 13:35:55.086  1013  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-09 13:35:55.086  1013  1149 D RttService: DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.086  1013  1125 D WifiP2pService: P2p socket connection successful
09-09 13:35:55.086  6710  6710 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.086  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.086  1013  1125 D WifiP2pService: P2pEnabledState
,09-09 13:35:55.086  6710  6710 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-09 13:35:55.086  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-09 13:35:55.086  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.096  1013  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:35:55.086  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.086  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:55.086  1013  1130 D SecContentProvider2: mCursor = null
09-09 13:35:55.096  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:55.096  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:35:55.096  1013  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-09 13:35:55.096  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:55.096  1013  1044 D WifiDisplayController: disconnect
,09-09 13:35:55.096  1013  1044 D WifiDisplayController: updateConnection
,09-09 13:35:55.096  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-09 13:35:55.096  1013  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
09-09 13:35:55.096  1013  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:55.096  1013  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:35:55.096  1013  1130 E WifiNative-wlan0: invaild command id : 215
09-09 13:35:55.096  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:55.096  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:55.096  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:55.096  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c599360 added. We now have 3 listener(s)
09-09 13:35:55.096  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:55.096  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:55.096  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:55.096  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:55.106  1013  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 13:35:55.106  1013  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-09 13:35:55.106  1013  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:55.106  1013  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:55.106  1013  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:55.106  1013  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:35:55.106  1013  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-09 13:35:55.106  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:35:55.106  1013  1075 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:55.106  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:35:55.106  1013  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  secondary type: null
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  wps: 0
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  grpcapab: 0
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  devcapab: 0
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  status: 3
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  wfdInfo: null
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  groupownerAddress: null
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  GOdeviceName: null
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  interfaceAddress: 
09-09 13:35:55.106  1013  1044 D WifiDisplayController:  SConnectInfo : null
,09-09 13:35:55.116  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:35:55.116  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:55.116  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:55.116  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:35:55.116  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194b3019 added. We now have 3 listener(s)
09-09 13:35:55.116  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:55.116  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:55.116  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:35:55.116  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:55.116  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:55.126  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.126  1013  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:35:55.126  1013  1125 D WifiP2pService: InactiveState
,09-09 13:35:55.126  1013  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:35:55.126  1013  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:35:55.126  6710  6710 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:35:55.126  1013  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:35:55.126  1013  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
09-09 13:35:55.126  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:55.126  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:55.126  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:55.126  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.136  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.136  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:55.136  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
09-09 13:35:55.136  6392  6392 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:35:55.136  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:55.136  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:55.136  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.136  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.136  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:55.136  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:55.136  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c599360 removed from the list
09-09 13:35:55.136  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.136  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194b3019 removed from the list
,09-09 13:35:55.136  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.136  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.136  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 13:35:55.136  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.146  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 13:35:55.146  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:35:55.146  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:35:55.146  6424  6424 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:55.146  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:55.146  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1073dabf added. We now have 3 listener(s)
,09-09 13:35:55.146  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:35:55.146  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:55.146  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:55.146  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:55.146  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb4858c added. We now have 3 listener(s)
09-09 13:35:55.146  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:55.146  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:55.156  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.156  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.156  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.156  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:55.156  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.156  6233  6282 D BluetoothAdapter: disable()
,09-09 13:35:55.166  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.166  1013  1317 D SettingsProvider: name = bluetooth_on
,09-09 13:35:55.166  2654  2717 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-09 13:35:55.166  2654  2717 D BluetoothAdapterProperties: Setting state to 13,
09-09 13:35:55.166  2654  2717 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:35:55.166  1013  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.166  2654  2717 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:55.166  1013  1356 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
09-09 13:35:55.166  2654  2717 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 13:35:55.176  1013  1356 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.176  1013  1356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.176  1013  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.176  2654  2717 D BluetoothAdapterService: Autoconnection is available 
,09-09 13:35:55.176  2654  2717 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 13:35:55.176  2654  2717 D BluetoothAdapterService: terminating service from this receiver
,09-09 13:35:55.176  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:55.176  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,09-09 13:35:55.176  2654  2654 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-09 13:35:55.176  2654  2654 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@611395c, channel: 19, state: LISTENING
09-09 13:35:55.176  2654  2654 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@611395c, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d4988d7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@df7a465mSocket: android.net.LocalSocket@31a5f53a impl:android.net.LocalSocketImpl@193d45eb fd:FileDescriptor[74]
09-09 13:35:55.176  2654  2654 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31a5f53a impl:android.net.LocalSocketImpl@193d45eb fd:FileDescriptor[74]
,09-09 13:35:55.186  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:35:55.186  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 13:35:55.186  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.186  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-09 13:35:55.196  1891  1891 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:55.196  1325  1325 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:55.206  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.206  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.206  1013  2968 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:35:55.206  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.206  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:55.206  1013  1075 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.206  1013  1075 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.206  1013  1075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.206  1013  1075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.206  6233  6282 D BluetoothAdapter: enable()
,09-09 13:35:55.206  1173  1712 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:55.206  2654  2717 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:35:55.206  2654  2717 D BluetoothAdapterProperties: mDiscovering is false
,09-09 13:35:55.206  1013  1638 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 13:35:55.206  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 13:35:55.206  1173  1712 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:55.216  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Bluetooth,
,09-09 13:35:55.216  6233  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:55.216  1013  3214 W ActivityManager: Permission Denial: getCurrentUser() from pid=6233, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:35:55.216  6233  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.216  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.216  6233  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.216  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.216  6233  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.216  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.226  1013  3214 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 13:35:55.226  1013  3214 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6233, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:55.226  1013  3214 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 13:35:55.226  1013  3214 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-09 13:35:55.226  1013  3214 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-09 13:35:55.226  1013  3214 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-09 13:35:55.226  1013  3214 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:35:55.226  1013  3214 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:35:55.226  1013  3214 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:35:55.226  1013  3214 D SettingsProvider: name = bluetooth_on
,09-09 13:35:55.226  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.226  1013  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:35:55.226  1013  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:35:55.356  1013  1540 I art     : Explicit concurrent mark sweep GC freed 60051(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.565ms total 162.241ms
,09-09 13:35:55.356  1013  1025 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:35:55.356  2654  2717 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 13:35:55.356  1013  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 13:35:55.356  1013  3229 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:55.356  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.356  1325  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:35:55.356  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.356  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.356  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.366  1013  3228 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:35:55.366  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.366  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.366  1013  3228 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.366  1013  3228 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.366  1013  3228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:35:55.366  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.366  2654  2720 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:35:55.366  2654  2720 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:35:55.376  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.376  2654  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = USER_TURN_ON, isTurningOn=false, isTurningOff=true
,09-09 13:35:55.376  2654  2717 I BluetoothAdapterState: CURRENT_STATE=PENDING: Deferring request USER_TURN_ON
,09-09 13:35:55.376  2654  2654 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@29268f48, channel: 5, state: LISTENING
09-09 13:35:55.376  2654  2654 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@29268f48, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d4af5c4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ec321e1mSocket: android.net.LocalSocket@226e2b06 impl:android.net.LocalSocketImpl@6a855c7 fd:FileDescriptor[76]
09-09 13:35:55.376  2654  2654 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@226e2b06 impl:android.net.LocalSocketImpl@6a855c7 fd:FileDescriptor[76]
,09-09 13:35:55.376  2654  2654 I BtOppRfcommListener: stopping Accept Thread
09-09 13:35:55.376  2654  2654 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3eb957f4, channel: 12, state: LISTENING
,09-09 13:35:55.376  2654  2654 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3eb957f4, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39fdc42e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@286efb1dmSocket: android.net.LocalSocket@1d31f192 impl:android.net.LocalSocketImpl@eca8763 fd:FileDescriptor[79]
09-09 13:35:55.376  2654  2654 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d31f192 impl:android.net.LocalSocketImpl@eca8763 fd:FileDescriptor[79]
,09-09 13:35:55.386  2654  5008 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:35:55.386  2654  5008 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 13:35:55.386  2654  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:35:55.386  2654  2717 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-09 13:35:55.386  2654  2717 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-09 13:35:55.386  2654  2717 E bt-btif : cmd socket is not created
09-09 13:35:55.386  2654  2803 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 13:35:55.386  2654  2803 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms,
,09-09 13:35:55.386  2654  2717 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 13:35:55.386  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:35:55.386  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.386  2654  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 13:35:55.386  6233  6377 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cd514ea, channel: -1, state: INIT
09-09 13:35:55.386  6233  6377 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cd514ea, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a1563db, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35ea6e78mSocket: android.net.LocalSocket@b49c951 impl:android.net.LocalSocketImpl@f6795b6 fd:FileDescriptor[107]
09-09 13:35:55.386  6233  6377 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b49c951 impl:android.net.LocalSocketImpl@f6795b6 fd:FileDescriptor[107]
,09-09 13:35:55.386  6233  6377 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1168)
,09-09 13:35:55.386  2654  2654 V BluetoothOppManager: cleanUp...
,09-09 13:35:55.396  1325  1325 D BluetoothPbap: Proxy object disconnected
09-09 13:35:55.396  1325  1325 D PbapServerProfile: Bluetooth service disconnected
,09-09 13:35:55.396  1325  1325 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:35:55.396  1325  1325 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:55.406  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-09 13:35:55.406  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 13:35:55.406  1013  1356 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 13:35:55.406  1013  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.406  1013  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.406  1013  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.406  1013  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.416  6748  6748 E Zygote  : MountEmulatedStorage()
,09-09 13:35:55.416  1013  1356 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6748 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-09 13:35:55.426  6748  6748 E Zygote  : v2
09-09 13:35:55.426  6748  6748 I libpersona: KNOX_SDCARD checking this for 10003
09-09 13:35:55.426  6748  6748 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:55.426  6748  6748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:55.426  6748  6748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:55.426  6748  6748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:55.446  6748  6748 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:55.446  6748  6748 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:55.476  6748  6748 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 13:35:55.506  6748  6748 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 13:35:55.506  6748  6748 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 13:35:55.506  6748  6748 D UserAnalysis: Create SecureDbHelper
,09-09 13:35:55.516  6748  6748 D IntelligenceServiceApplication: onCreate()
,09-09 13:35:55.516  1013  3228 I ActivityManager: Killing 6105:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-09 13:35:55.526  1013  3228 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 13:35:55.526  1013  3228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.526  1013  3228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.526  1013  3228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.526  1013  3228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.526  6748  6748 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-09 13:35:55.536  6766  6766 E Zygote  : MountEmulatedStorage(),
09-09 13:35:55.536  1013  3228 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6766 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-09 13:35:55.536  6766  6766 E Zygote  : v2,
09-09 13:35:55.536  6766  6766 I libpersona: KNOX_SDCARD checking this for 10107
09-09 13:35:55.536  6766  6766 I libpersona: KNOX_SDCARD not a persona,
,09-09 13:35:55.536  6766  6766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:35:55.546  1013  1638 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 13:35:55.546  6748  6748 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,09-09 13:35:55.546  6766  6766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:35:55.546  6766  6766 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:55.546  6748  6748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-09 13:35:55.566  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:55.566  6766  6766 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:35:55.586  2654  2803 W bt-btif : ag scb idx 1 not allocated
09-09 13:35:55.586  2654  2803 W bt-btif : ag scb idx 2 not allocated
09-09 13:35:55.586  2654  2803 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:35:55.586  2654  2901 I bt_userial_mct: exiting userial_read_thread
09-09 13:35:55.586  2654  2901 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 13:35:55.586  2654  2720 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 13:35:55.586  2654  2805 I bt_vendor: hw_epilog_process
09-09 13:35:55.586  2654  2720 D bt_userial_mct: userial_close
09-09 13:35:55.586  2654  2720 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-09 13:35:55.776  1013  2968 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,09-09 13:35:55.776  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:35:55.786  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.786  1013  2968 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:55.786  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.796  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:55.796  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=222 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=213 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.k.c(PG:583)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.836  6766  6766 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.836  6766  6766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.846  1013  1541 I ActivityManager: Killing 6129:com.samsung.helphub/1000 (adj 15): empty #31
09-09 13:35:55.846  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 13:35:55.856  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:35:55.856  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 13:35:55.856  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.856  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.856  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:35:55.866  2654  2720 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 13:35:55.866  2654  2720 I bt_vendor: bluetooth satus is on
09-09 13:35:55.866  2654  2720 I bt_vendor: bt-vendor : resetting BT status
09-09 13:35:55.866  2654  2720 I bt_vendor: Starting hciattach daemon
09-09 13:35:55.866  2654  2720 I bt_vendor: try to set false
09-09 13:35:55.866  2654  2720 I bt_vendor: Starting hciattach daemon
09-09 13:35:55.866  2654  2720 I bt_vendor: try to set false
09-09 13:35:55.866  2654  2720 I bt_vendor: cleanup
09-09 13:35:55.866  2654  2803 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 13:35:55.866  2654  2720 I GKI_LINUX: GKI_exit_task 0 done
09-09 13:35:55.866  2654  2720 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 13:35:55.876  2654  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:35:55.876  2654  2717 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:35:55.876  2654  2717 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 13:35:55.876  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 13:35:55.876  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:35:55.876  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 13:35:55.876  1013  3229 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.876  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-09 13:35:55.876  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.876  1013  3229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.876  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.876  2654  2654 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:35:55.876  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.876  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.876  2654  2654 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:35:55.876  2654  2654 D BtGatt.GattService: stop()
09-09 13:35:55.876  2654  2654 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:35:55.876  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:55.876  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.876  1013  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.876  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 13:35:55.876  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.876  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.876  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.876  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.876  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.876  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.886  1013  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.886  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 13:35:55.886  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.886  1013  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.886  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.886  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 13:35:55.886  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.886  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 13:35:55.886  1013  2968 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.886  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 13:35:55.886  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.886  1013  2968 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.886  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.886  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:35:55.886  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:35:55.886  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 13:35:55.886  1013  1638 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.886  1013  1638 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 13:35:55.886  1013  1638 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.886  1013  1638 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.886  1013  1638 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.896  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:35:55.896  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:35:55.896  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 13:35:55.896  1013  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.896  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:35:55.896  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.896  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.896  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.896  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.896  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.896  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.896  1013  3229 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.896  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 13:35:55.896  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.896  1013  3229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.896  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.896  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:35:55.896  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.896  2654  2717 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 13:35:55.896  1013  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.906  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 13:35:55.906  1013  1317 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.906  1013  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.906  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.906  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.906  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.906  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:35:55.906  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.906  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:35:55.906  2654  2717 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 13:35:55.906  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-09 13:35:55.906  2654  2654 D HeadsetService: Received stop request...Stopping profile...
09-09 13:35:55.916  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:55.916  1325  1325 D HeadsetProfile: Bluetooth service disconnected
09-09 13:35:55.916  2654  2654 D A2dpService: Received stop request...Stopping profile...
09-09 13:35:55.916  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 13:35:55.916  2654  2733 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:35:55.916  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:55.916  2862  2862 D BluetoothA2dp: Proxy object disconnected
,09-09 13:35:55.916  1013  1013 D BluetoothA2dp: Proxy object disconnected
09-09 13:35:55.916  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 13:35:55.916  1325  1325 D BluetoothA2dp: Proxy object disconnected
09-09 13:35:55.916  1325  1325 D A2dpProfile: Bluetooth service disconnected
,09-09 13:35:55.916  2654  2654 D HidService: Received stop request...Stopping profile...
09-09 13:35:55.916  2654  2654 D HidService: Stopping Bluetooth HidService
09-09 13:35:55.916  2654  2654 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:35:55.916  2654  2654 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 13:35:55.916  2654  2654 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:35:55.916  6766  6785 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:35:55.926  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:55.926  2654  2654 D HealthService: Received stop request...Stopping profile...
09-09 13:35:55.926  1325  1325 D BluetoothInputDevice: Proxy object disconnected
09-09 13:35:55.926  1325  1325 D HidProfile: Bluetooth service disconnected
09-09 13:35:55.926  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:55.926  2654  2654 D PanService: Received stop request...Stopping profile...
09-09 13:35:55.926  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:55.926  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 13:35:55.926  1325  1325 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:35:55.926  1325  1325 D PanProfile: Bluetooth service disconnected
,09-09 13:35:55.926  2654  2654 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 13:35:55.926  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:55.936  2654  2654 D SapService: Received stop request...Stopping profile...
09-09 13:35:55.936  1325  1325 D BluetoothMap: Proxy object disconnected
09-09 13:35:55.936  1325  1325 D MapProfile: Bluetooth service disconnected
,09-09 13:35:55.936  2654  2654 D SapService: Stopping Bluetooth SapService
09-09 13:35:55.936  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:55.936  1013  2967 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:55.936  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 13:35:55.936  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.936  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 13:35:55.936  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.936  1013  2967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.936  1325  1325 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 13:35:55.936  1325  1325 D SapProfile: Bluetooth service disconnected
09-09 13:35:55.936  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.946  2654  2654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:35:55.946  2654  2654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 13:35:55.946  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 13:35:55.946  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.946  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 13:35:55.946  2654  2654 D BluetoothA2dp: Proxy object disconnected
09-09 13:35:55.946  2654  2654 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-09 13:35:55.946  2654  2734 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 13:35:55.946  2654  2654 I GKI_LINUX: GKI_exit_task 2 done
09-09 13:35:55.946  2654  2654 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 13:35:55.946  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 13:35:55.946  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.946  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 13:35:55.946  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 13:35:55.946  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.946  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.946  2654  2654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:35:55.946  2654  2654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 13:35:55.946  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 13:35:55.946  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.946  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.946  2654  2654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:35:55.946  2654  2654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 13:35:55.946  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-09 13:35:55.946  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.946  2654  2654 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-09 13:35:55.946  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 13:35:55.946  2654  2654 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,09-09 13:35:55.946  2654  2654 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-09 13:35:55.956  2654  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-09 13:35:55.956  2654  2717 D BluetoothAdapterProperties: Setting state to 10
09-09 13:35:55.956  2654  2717 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: updateAdapterState state is 10
09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: Autoconnection is available 
09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 13:35:55.956  2654  2717 I BluetoothAdapterState: Entering OffState,
09-09 13:35:55.956  2862  2878 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:35:55.956  2862  2878 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:55.956  2654  2717 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 13:35:55.956  2654  2717 D BluetoothAdapterProperties: Setting state to 11
09-09 13:35:55.956  2654  2717 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: updateAdapterState state is 11
09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: Autoconnection is available 
,09-09 13:35:55.956  2654  2717 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-09 13:35:55.956  2654  2717 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 10
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 13:35:55.956  1013  1075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:35:55.956  1013  1075 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,09-09 13:35:55.956  1013  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.956  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
09-09 13:35:55.956  1907  1918 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.956  1907  1918 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 13:35:55.966  1013  2968 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:55.956  1325  6742 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:35:55.966  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 13:35:55.956  1013  1075 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.956  1013  1075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.956  1013  1075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.956  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.956  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.956  2654  2654 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:35:55.956  2654  2654 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:35:55.956  2654  2654 D BtGatt.GattService: start()
09-09 13:35:55.956  2654  2654 D BtGatt.GattService: start()
09-09 13:35:55.956  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:55.956  2654  2654 D BtGatt.AdvertiseManager: advertise manager created
09-09 13:35:55.956  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.956  1013  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.956  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.966  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.966  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.966  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.966  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.966  1013  2968 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.966  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.966  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 13:35:55.966  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.966  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 13:35:55.966  1013  2967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.966  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 13:35:55.966  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.966  1013  2967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.966  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.966  2654  2654 D BtGatt.GattService: mStartError = false
09-09 13:35:55.966  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:55.966  1441  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.966  2654  2654 D HeadsetService: Received start request. Starting profile...
09-09 13:35:55.966  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:35:55.966  2654  2654 D HeadsetService: start()
09-09 13:35:55.966  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:35:55.966  2654  2654 D HeadsetStateMachine: make
09-09 13:35:55.966  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 13:35:55.966  1013  1075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.966  1013  1075 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 13:35:55.966  1441  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.966  1013  1075 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.966  1013  1075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.966  1013  1075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.976  2654  2654 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 13:35:55.976  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:35:55.976  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:35:55.976  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 13:35:55.976  1013  3214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.976  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.976  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.976  1013  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.976  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.976  1013  1360 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 13:35:55.976  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.976  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.976  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.976  2654  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.976  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.976  1013  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.976  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-09 13:35:55.976  1013  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.976  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.976  1325  1333 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 13:35:55.976  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.976  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.976  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.986  1013  3230 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 13:35:55.986  1013  3230 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:35:55.986  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 13:35:55.986  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.986  1013  3230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.986  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-09 13:35:55.986  2654  2654 I bluedroid: get_profile_interface handsfree
09-09 13:35:55.986  1013  3229 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.986  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.986  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.986  1013  3229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.986  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.986  2654  2663 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.986  2654  2663 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:55.986  1454  1467 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.986  1454  1467 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.986  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.986  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.986  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:35:55.986  2654  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.986  2654  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:35:55.986  2654  2717 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 13:35:55.986  6766  6777 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.986  6766  6777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.986  6233  6241 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:35:55.986  6233  6241 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.996  2654  2654 E DualScoManager: Dual Sco Manager already instantiated
09-09 13:35:55.996  2654  2654 I DualScoManager: Set HeadsetServiceHelper
09-09 13:35:55.996  2654  2654 D BluetoothAtMessage: createCMTIContentObservers
,09-09 13:35:55.996  1013  2967 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-09 13:35:55.996  1013  2967 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:35:55.996  1013  2967 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:35:55.996  1013  2967 D SettingsProvider: selectionArgs: false
09-09 13:35:55.996  1013  2967 D SettingsProvider: selectionArgs: 1002
,09-09 13:35:55.996  1013  2967 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:35:55.996  1013  2967 D SettingsProvider: ret = -1
09-09 13:35:55.996  6233  6241 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 13:35:55.996  6233  6241 D BluetoothLeAdvertiser: Exit stop advertising
09-09 13:35:55.996  6233  6241 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 13:35:55.996  6233  6241 D BluetoothLeScanner: Exiting stopAllScan
,09-09 13:35:55.996  2654  6795 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 13:35:55.996  2654  2654 D HeadsetService: mStartError = false
09-09 13:35:55.996  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:55.996  2654  2654 D A2dpService: Received start request. Starting profile...
09-09 13:35:55.996  2654  2654 D A2dpService: start()
09-09 13:35:55.996  2654  2654 I bluedroid: get_profile_interface avrcp
,09-09 13:35:55.996  1427  6792 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.996  2654  6795 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 13:35:55.996  1427  6792 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.996  1325  1334 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 13:35:55.996  1325  1334 D Bluetoothsap: Unbinding service...
09-09 13:35:55.996  2654  6795 D HeadsetStateMachine: map size, before remove : 0
09-09 13:35:55.996  2654  6795 D HeadsetStateMachine: map size, after remove: 0
09-09 13:35:55.996  1013  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:35:55.996  2862  2878 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:35:55.996  1325  1333 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:35:55.996  2654  2654 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 13:35:55.996  1325  1333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:56.006  2654  2654 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 13:35:56.006  2654  2654 D A2dpStateMachine: make
,09-09 13:35:56.006  1325  6742 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:35:56.006  2654  6796 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 13:35:56.016  2654  2654 I bluedroid: get_profile_interface a2dp
09-09 13:35:56.016  1173  1740 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:56.016  1173  1740 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:56.016  1013  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:56.016  1013  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:56.016  2654  6798 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 13:35:56.016  2654  2654 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 13:35:56.016  2654  2654 D A2dpService: mStartError = false
09-09 13:35:56.016  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:56.016  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 13:35:56.016  2654  2654 D HidService: Received start request. Starting profile...
09-09 13:35:56.016  2654  2654 D HidService: start()
09-09 13:35:56.016  2654  2654 I bluedroid: get_profile_interface hidhost
09-09 13:35:56.016  2654  2654 D HidService: setHidService(): set to: null
09-09 13:35:56.016  2654  2654 D HidService: mStartError = false
09-09 13:35:56.016  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:56.016  2654  6797 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:35:56.016  2654  2654 D HealthService: Received start request. Starting profile...
09-09 13:35:56.016  2654  2654 D HealthService: start()
,09-09 13:35:56.016  2654  2654 I bluedroid: get_profile_interface health
,09-09 13:35:56.016  2654  2654 D HealthService: mStartError = false
09-09 13:35:56.016  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:56.016  2654  2654 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 13:35:56.016  1427  6792 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 13:35:56.016  1325  1334 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:35:56.016  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 13:35:56.016  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 13:35:56.026  1427  6792 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 13:35:56.026  2654  2654 D PanService: Received start request. Starting profile...
09-09 13:35:56.026  2654  2961 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:35:56.026  2654  2654 D PanService: start()
09-09 13:35:56.026  2654  2654 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:35:56.026  2654  2654 I bluedroid: get_profile_interface pan
09-09 13:35:56.026  2654  2654 D PanService: mStartError = false
09-09 13:35:56.026  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:35:56.026  2654  2654 D BluetoothMapService: Received start request. Starting profile...
09-09 13:35:56.026  2654  2654 D BluetoothMapService: start()
,09-09 13:35:56.026  2654  2654 D BluetoothMapService: mStartError = false
09-09 13:35:56.026  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:56.026  2654  2654 D HeadsetStateMachine: Proxy object connected
09-09 13:35:56.026  2654  2654 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 13:35:56.026  2654  2654 D SapService: Received start request. Starting profile...
09-09 13:35:56.026  2654  2654 D SapService: start()
09-09 13:35:56.026  2654  2654 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 13:35:56.026  2654  2654 I bluedroid: get_profile_interface sap
09-09 13:35:56.026  2654  2654 D SapService: mStartError = false
09-09 13:35:56.026  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:56.026  2654  2654 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 13:35:56.026  2654  2654 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 13:35:56.026  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 13:35:56.026  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:35:56.026  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 13:35:56.026  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 13:35:56.026  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 13:35:56.026  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-09 13:35:56.026  2654  6795 D HeadsetStateMachine: Disconnected process message: 11
09-09 13:35:56.026  2654  6795 D HeadsetStateMachine: Disconnected process message: 18
09-09 13:35:56.026  2654  6795 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:35:56.026  2654  6795 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:35:56.026  2654  6795 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:35:56.026  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.026  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
09-09 13:35:56.026  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:35:56.036  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:56.036  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:56.036  1173  1173 D BluetoothTile:  getBluetoothState : 10
,09-09 13:35:56.036  1891  1891 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:56.046  1013  1356 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:35:56.046  1013  3214 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:35:56.046  1325  1325 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.046  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:35:56.046  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.046  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.046  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:56.046  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,09-09 13:35:56.046  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.046  1325  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:35:56.056  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:56.056  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.056  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-09 13:35:56.056  1891  1891 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:56.056  1013  1360 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:35:56.056  1013  1356 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:35:56.056  1173  1712 D BluetoothTile:  handleUpdatestate:false name:null
09-09 13:35:56.056  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:35:56.066  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:35:56.066  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.066  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.066  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:56.066  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.066  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.066  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.066  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.066  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.076  1013  1317 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 13:35:56.076  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.076  1013  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.076  1013  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.076  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:35:56.076  2654  6796 D BluetoothMediaBrowser: no now playing list
,09-09 13:35:56.076  2654  6796 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 13:35:56.076  1325  1325 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.076  1013  1360 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:56.076  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.086  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.086  1013  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.086  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.096  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 13:35:56.096  2654  2654 E BluetoothAdapterService(69487269): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 13:35:56.096  2654  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-09 13:35:56.096  2654  2717 I bluedroid: enable
09-09 13:35:56.096  1325  1325 D DockEventReceiver: finishStartingService: stopping service
09-09 13:35:56.096  2654  2717 I bt_hci_bdroid: init
,09-09 13:35:56.096  2654  6804 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 13:35:56.096  2654  2717 I bt_vendor: bt-vendor : init
09-09 13:35:56.096  2654  2717 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 13:35:56.096  2654  2717 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 13:35:56.096  2654  2717 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-09 13:35:56.096  2654  2717 D bt_userial_mct: userial_init
,09-09 13:35:56.106  2654  2717 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 13:35:56.106  2654  2717 I bt_vendor: Starting hciattach daemon
09-09 13:35:56.106  2654  2717 I bt_vendor: try to set false
,09-09 13:35:56.106  2654  2717 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 13:35:56.106  2654  2717 I bt_vendor: Starting hciattach daemon
09-09 13:35:56.106  2654  2717 I bt_vendor: try to set true
,09-09 13:35:56.106  1325  1325 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:56.106  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.106  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 13:35:56.126  6809  6809 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 13:35:56.156  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:35:56.166  1013  1075 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:56.166  1013  1075 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.166  1013  1075 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-09 13:35:56.166  1013  1075 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.166  1013  1075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.176  6821  6821 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 13:35:56.176  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:35:56.176  1907  6822 D EasyUnlockInitService: Handling intent for initializer IntentService.,
,09-09 13:35:56.186  1013  3214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:56.186  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.186  1013  3214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.186  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.186  6823  6823 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:35:56.196  1325  1325 D BluetoothNotiBroadcastReceiver: onReceive,
,09-09 13:35:56.206  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.206  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 13:35:56.206  1013  3229 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:56.216  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.216  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.216  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.216  6825  6825 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:35:56.226  1907  6822 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 13:35:56.226  6826  6826 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 13:35:56.236  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:35:56.246  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:35:56.246  6827  6827 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:35:56.256  6828  6828 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 13:35:56.346  6710  6710 I wpa_supplicant: nl80211: Received scan results (11 BSSes),
09-09 13:35:56.346  6710  6710 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-09 13:35:56.346  1013  6736 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-09 13:35:56.346  6710  6710 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 13:35:56.346  6710  6710 I wpa_supplicant: Trying to associate with  'G700'
,09-09 13:35:56.356  6710  6710 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-09 13:35:56.356  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-09 13:35:56.366  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:56.366  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:56.466  6710  6710 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:35:56.466  6710  6710 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 13:35:56.466  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:35:56.466  6710  6710 I wpa_supplicant: Associated with F4.99.3E
,09-09 13:35:56.466  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:56.466  6710  6710 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:35:56.466  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:56.466  6710  6710 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-09 13:35:56.466  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
,09-09 13:35:56.466  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:56.466  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:56.466  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:56.466  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:56.476  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, true,
09-09 13:35:56.476  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:35:56.476  1013  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:35:56.476  6831  6831 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,09-09 13:35:56.476  6710  6710 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:35:56.476  6710  6710 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 13:35:56.476  1013  1133 E Tethering: No numeric data
09-09 13:35:56.476  6710  6710 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-09 13:35:56.476  1013  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:56.476  1013  1133 D Tethering: clearTetheredNotification()
09-09 13:35:56.476  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 13:35:56.476  6710  6710 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:35:56.476  6710  6710 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
,09-09 13:35:56.476  6710  6710 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 13:35:56.486  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:56.476  6710  6710 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:35:56.486  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:56.476  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:35:56.486  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:35:56.486  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:56.486  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:35:56.486  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:56.486  1013  1130 D SecContentProvider2: mCursor = null
09-09 13:35:56.486  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:35:56.486  1013  1041 D Tethering: interfaceStatusChanged wlan0, true
09-09 13:35:56.486  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:56.486  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:56.496  1013  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:35:56.496  1013  1123 V NetworkStats: performPollLocked() took 14ms
09-09 13:35:56.496  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:56.506  1013  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:35:56.506  6832  6832 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:35:56.506  1013  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 13:35:56.506  1013  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 13:35:56.506  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:56.506  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:35:56.516  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:56.516  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:56.516  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.516  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.516  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.516  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.516  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:56.516  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:56.516  1013  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:35:56.516  1013  2968 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:56.516  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:56.516  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.516  1013  2968 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.516  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:56.516  3578  3578 I Hs20UtilService: Starting #14
,09-09 13:35:56.516  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:35:56.526  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:56.526  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:35:56.526  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:35:56.526  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:56.526  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:56.526  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:56.526  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:56.546  1013  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-09 13:35:56.556   277   982 D CommandListener: Setting iface cfg
09-09 13:35:56.556  2654  2717 I bt_vendor: bluetooth satus is on
09-09 13:35:56.556  2654  6806 D bt_userial_mct: userial_open(port:0)
09-09 13:35:56.556  2654  6806 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-09 13:35:56.556  2654  6806 I bt_vendor: Done intiailizing UART
09-09 13:35:56.556  2654  6806 I bt_vendor: Done intiailizing UART
09-09 13:35:56.556  2654  6806 I bt_userial_mct: CMD=73, EVT=73, ACL_Out=74, ACL_In=74
09-09 13:35:56.556  2654  6806 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 13:35:56.556  1013  1130 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 13:35:56.556  2654  6804 E bt-att  : DIS already initalized
09-09 13:35:56.556  2654  6836 D bt_userial_mct: Entering userial_read_thread()
09-09 13:35:56.556  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:56.556  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 13:35:56.566  2654  6804 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-09 13:35:56.566  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:56.566  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:56.646  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:56.646  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:56.646  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.646  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.646  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:56.646  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:56.646  2654  6804 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 13:35:56.656  2654  6804 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40366e9 
,09-09 13:35:56.656  2654  6804 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40366e9 
09-09 13:35:56.656  1013  1130 E WifiNative-wlan0: do suspend false
,09-09 13:35:56.656  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:56.656  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:56.656  1013  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:35:56.656  1013  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:56.666  2654  2720 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 13:35:56.666  2654  2720 E bt-btif : Calling BTA_HhEnable
,09-09 13:35:56.666  2654  2720 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 13:35:56.676  2654  2720 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 13:35:56.676  2654  2720 E BluetoothServiceJni: populateRssiValuesNative
,09-09 13:35:56.676  2654  2720 I bluedroid: getModelRssiValues
09-09 13:35:56.676  2654  2720 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 13:35:56.676  2654  2720 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 13:35:56.676  2654  2720 D BluetoothAdapterProperties: Name is: A5-1
,09-09 13:35:56.676  1013  1013 D SettingsProvider: name = bluetooth_name
,09-09 13:35:56.676  2654  2720 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 13:35:56.686  2654  2720 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:35:56.686  2654  2720 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:35:56.686  2654  2720 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-09 13:35:56.686  2654  2720 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-09 13:35:56.686  2654  2720 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-09 13:35:56.686  2654  2720 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-09 13:35:56.686  2654  2720 E bt-btif : btif_sock_init: !vhci_init
,09-09 13:35:56.686  2654  6836 E bt_mct  : hci lib postload completed
,09-09 13:35:56.686  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.686  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.686  2654  2720 D bte_conf: Device ID record 1 : primary
09-09 13:35:56.686  2654  2720 D bte_conf:   vendorId            = 0075
09-09 13:35:56.686  2654  2720 D bte_conf:   vendorIdSource      = 0001
09-09 13:35:56.686  2654  2720 D bte_conf:   product             = 0100
09-09 13:35:56.686  2654  2720 D bte_conf:   version             = 0200
09-09 13:35:56.686  2654  2720 D bte_conf:   clientExecutableURL = 
09-09 13:35:56.686  2654  2720 D bte_conf:   serviceDescription  = 
09-09 13:35:56.686  2654  2720 D bte_conf:   documentationURL    = 
09-09 13:35:56.686  2654  2720 D bte_conf: bte_load_did_conf no section named DID2.
,09-09 13:35:56.696  2654  2720 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:35:56.696  2654  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 13:35:56.696  2654  2717 D BluetoothAdapterProperties: ScanMode =  20
,09-09 13:35:56.696  2654  2717 D BluetoothAdapterProperties: State =  11
,09-09 13:35:56.696  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.696  1013  1026 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:35:56.696  2654  2717 D BluetoothAdapterProperties: Setting state to 12
,09-09 13:35:56.696  2654  2717 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:35:56.706  2654  2720 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:35:56.706  2654  2720 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:35:56.706  2654  2720 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:35:56.706  1013  3214 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-09 13:35:56.706  1013  3214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:35:56.706  1013  3214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:35:56.706  1013  3214 D SettingsProvider: selectionArgs: false
,09-09 13:35:56.706  1013  3214 D SettingsProvider: selectionArgs: 1002
09-09 13:35:56.706  1013  3214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 13:35:56.706  1013  3214 D SettingsProvider: ret = -1
,09-09 13:35:56.706  2654  2717 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:56.706  2654  2717 D BluetoothAdapterService: updateAdapterState state is 12
09-09 13:35:56.706  1013  2967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:56.706  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.706  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.706  1013  2967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.706  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:56.706  6233  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:56.716   290   290 E SMD     : DCD OFF
09-09 13:35:56.716  2654  2717 D BluetoothAdapterService: Autoconnection is available 
,09-09 13:35:56.716  2654  2717 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 13:35:56.716  2654  2717 D BluetoothAdapterService: starting service from this receiver
,09-09 13:35:56.716  1013  1638 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:56.716  1013  1638 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.716  2862  2870 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.716  2862  2870 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
09-09 13:35:56.716  1013  1638 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.716  1013  1638 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.716  1013  1638 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.716  2654  2654 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-09 13:35:56.716  2654  2654 I BluetoothPbapService: Handler(): got msg=1
09-09 13:35:56.716  1907  1917 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.716  1907  1917 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.726  2654  2717 I BluetoothAdapterState: Entering On State from state = 11
09-09 13:35:56.726  1013  3229 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:35:56.726  1325  6742 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:35:56.726  6233  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:56.726  1325  6742 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.726  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:35:56.726  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.736  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.736  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.736  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.736  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:56.736  2654  6840 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 13:35:56.736  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:56.746  1427  1460 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.746  1325  1325 D BluetoothA2dp: Proxy object connected
,09-09 13:35:56.746  1325  1325 D A2dpProfile: Bluetooth service connected
,09-09 13:35:56.746  2654  6840 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:56.746  2654  6840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:56.746  1013  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.746  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.756  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.756  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.756  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.756  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:56.756  1427  1460 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.756  1441  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.756  1441  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.756  2654  6840 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
09-09 13:35:56.756  2654  6840 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:56.756  2654  6840 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:56.756  2654  6840 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d8dc031
,09-09 13:35:56.756  2654  6840 D BluetoothSocket: channel: 19
09-09 13:35:56.756  2654  6840 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 13:35:56.756  1325  1333 D BluetoothPan: Binding service...
,09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.756  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:56.766  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:35:56.766  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.766  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.766  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.766  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.766  1325  6742 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 13:35:56.766  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:56.766  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:56.766  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:56.766  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:56.766  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:56.766  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1073dabf removed from the list
09-09 13:35:56.766  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:56.766  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb4858c removed from the list
09-09 13:35:56.766  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:56.766  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:56.766  1325  1325 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:35:56.766  1325  1325 D PanProfile: Bluetooth service connected
,09-09 13:35:56.766  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-09 13:35:56.766  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:56.766  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7c62b7 added. We now have 3 listener(s)
,09-09 13:35:56.766  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.766  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.766  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.766  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.766  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:56.776  2654  2961 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.776  2654  2961 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.776  1454  1781 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:35:56.776  1454  1781 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.776  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:35:56.776  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:56.776  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:56.776  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:56.776  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e93fa24 added. We now have 3 listener(s)
09-09 13:35:56.776  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:56.776  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.776  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:56.776  2862  2878 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.776  1013  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.776  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.776  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.776  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.776  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-09 13:35:56.776  1325  1325 D BluetoothPbap: Proxy object connected
,09-09 13:35:56.776  2862  2878 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.776  1325  1325 D PbapServerProfile: Bluetooth service connected
,09-09 13:35:56.776  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:56.776  6766  6775 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.776  6766  6775 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.776  6233  6247 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.776  6233  6247 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.786  1454  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.786  1013  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.786  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.786  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.786  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.786  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.786  1454  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.786  1325  1334 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.786  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:56.786  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.786  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.786  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.786  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.786  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.786  1325  1334 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:35:56.786  1325  1325 D HeadsetProfile: Bluetooth service connected
,09-09 13:35:56.786  1427  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.786  1427  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.786  1325  1334 D Bluetoothsap: onBluetoothStateChange: up=true
,09-09 13:35:56.786  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:56.796  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:56.796  1325  1334 D Bluetoothsap: Binding service...
,09-09 13:35:56.796  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.796  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.796  1013  1541 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 13:35:56.796  1325  1334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-09 13:35:56.796  1013  1541 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:56.796  1013  1541 D SecContentProvider2: mCursor = null
,09-09 13:35:56.796  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 13:35:56.796  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.796  1013  1541 D WifiService: setWifiEnabled: false pid=6233, uid=10155
,09-09 13:35:56.796  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.796  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.796  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-09 13:35:56.796  1325  1334 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 13:35:56.796  1013  1043 D BluetoothPan: Binding service...
,09-09 13:35:56.796  1013  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:35:56.796  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:35:56.796  1013  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:35:56.796  1013  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.796  1013  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:35:56.796  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:35:56.796  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.796  2862  2878 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:35:56.796  1013  1013 D BluetoothA2dp: Proxy object connected
09-09 13:35:56.806  1325  1325 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 13:35:56.806  1325  1325 D SapProfile: Bluetooth service connected
09-09 13:35:56.806  1325  1325 D Bluetoothsap: getConnectedDevices()
09-09 13:35:56.806  2862  2878 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 13:35:56.806  1013  1541 D SettingsProvider: name = wifi_on
,09-09 13:35:56.806  1013  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:35:56.806  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.806  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.806  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.806  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.806  1013  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.806  2862  2862 D BluetoothA2dp: Proxy object connected
,09-09 13:35:56.806  1013  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.806  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.806  1013  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:35:56.806  1325  1333 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.806  1325  1333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.806  1325  1334 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:35:56.806  1013  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:35:56.816  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-09 13:35:56.816  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.816  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.816  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.816  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.816  1173  1740 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:35:56.816  1173  1740 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:35:56.816  1013  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.816  1013  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.816  1325  1325 D BluetoothMap: Proxy object connected
09-09 13:35:56.816  1325  1325 D MapProfile: Bluetooth service connected
09-09 13:35:56.816  1325  1325 D BluetoothMap: getConnectedDevices()
,09-09 13:35:56.816  1427  1460 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.816  1013  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.816  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.816  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.816  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:56.816  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.816  1427  1460 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.816  1427  1460 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.816  1013  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:35:56.816  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.826  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.826  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.826  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.826  1427  1460 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:35:56.826  1013  1130 E WifiNative-wlan0: do suspend true
,09-09 13:35:56.826  1325  1333 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:35:56.826  1013  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-09 13:35:56.826  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.826  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.826  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.826  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.826  1325  1325 D BluetoothInputDevice: Proxy object connected
,09-09 13:35:56.826  1325  1325 D HidProfile: Bluetooth service connected
09-09 13:35:56.826  2654  2663 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:35:56.826  2654  2663 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.826  1013  1043 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:35:56.826  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.836  1013  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.836  1013  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.836  1013  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.836  2654  2654 D BluetoothA2dp: Proxy object connected
09-09 13:35:56.836  2654  2654 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 13:35:56.836  1013  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 13:35:56.836  1013  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 13:35:56.836  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.836  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
09-09 13:35:56.836  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:35:56.836  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:35:56.846  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2ea90b83, true
,09-09 13:35:56.846  1891  1891 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:56.846  1427  1427 D BluetoothHeadset: registerMessageListener
,09-09 13:35:56.846  1173  1712 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:56.846  1013  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:35:56.846  1013  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:56.846  1325  1325 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.846  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:56.846  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:56.846  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-09 13:35:56.856  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.856  2654  2664 D HeadsetService: registerMessageListener
,09-09 13:35:56.856  2654  2664 D HeadsetService: registerMessageListener
,09-09 13:35:56.856  2654  6795 D HeadsetStateMachine: Disconnected process message: 70
09-09 13:35:56.856  2654  6795 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2ccff316
09-09 13:35:56.856  1173  1712 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:56.856  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 13:35:56.856  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 13:35:56.856  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.856  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.856   277   982 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:56.856  1013  1356 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:56.856  1013  1356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-09 13:35:56.866  1013  3228 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:35:56.866  1013  1075 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-09 13:35:56.866  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:35:56.866  1173  1712 D BluetoothTile:  handleUpdatestate:false name:null
09-09 13:35:56.866  1013  1132 E ConnectivityService: updateNetworkInfo()
,09-09 13:35:56.866  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:56.866  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:56.866  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-09 13:35:56.866  1013  1356 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.866   277   982 E Netd    : no such netId 503
09-09 13:35:56.866  1013  1356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.866  1013  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.876  1013  1132 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-09 13:35:56.876  1013  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 13:35:56.876  1013  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-09 13:35:56.876  1013  6833 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.876  1013  6833 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-09 13:35:56.876  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-09 13:35:56.876  1325  1325 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.,
09-09 13:35:56.876  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-09 13:35:56.876  1325  1325 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 13:35:56.876  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128,
,09-09 13:35:56.876  1325  1325 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 13:35:56.876  1013  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 13:35:56.876  1325  1325 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-09 13:35:56.876  1013  1132 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:35:56.876  1013  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 13:35:56.876  6845  6845 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-09 13:35:56.876  2654  6844 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 13:35:56.876  6845  6845 I dhcpcd  : version 5.5.6 starting
09-09 13:35:56.876  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:35:56.886  6845  6845 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:35:56.886  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:56.886  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:56.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:56.886  1013  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:35:56.886  2654  6795 D HeadsetStateMachine: Disconnected process message: 9
,09-09 13:35:56.886  2654  6795 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-09 13:35:56.886  1013  1125 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:35:56.886  1013  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 13:35:56.896  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:56.896  1013  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:35:56.896  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:56.896  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:56.896  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.896  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.896  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.896  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:56.896  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1,
09-09 13:35:56.896  1013  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.896  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-09 13:35:56.896  1013  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:35:56.906  1013  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:35:56.906  1013  1044 D WifiDisplayAdapter: onP2pDisconnected
,09-09 13:35:56.906  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:35:56.906  1013  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:56.906  2654  6844 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:56.906  1013  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:35:56.906  2654  6844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:56.906  1013  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:35:56.906  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:35:56.906  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:56.906   285   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 13:35:56.906  1013  1044 D WifiDisplayController: disconnect
09-09 13:35:56.906   285   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 13:35:56.906  1013  1044 D WifiDisplayController: updateConnection
09-09 13:35:56.906   285   695 V voice   : voice_set_parameters: exit with code(-2)
09-09 13:35:56.906  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:56.906   285   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 13:35:56.906  1013  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:56.906   285   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 13:35:56.906  1013  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:35:56.906   285   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 13:35:56.906   285   695 V audio_hw_primary: adev_set_parameters: exit
09-09 13:35:56.906  2654  6795 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 13:35:56.906  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:35:56.906  1013  1025 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:35:56.906  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:35:56.916  2654  6844 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[83]}
09-09 13:35:56.916  2654  6844 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 13:35:56.916  2654  6844 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:56.916  1013  1125 D WifiP2pService: P2pDisablingState
09-09 13:35:56.916  2654  6844 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@99f6497
09-09 13:35:56.916  1013  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:35:56.916  1325  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 13:35:56.916  1013  1125 D WifiP2pService: p2p socket connection lost
09-09 13:35:56.916  1013  1125 D WifiP2pService: P2pDisabledState
09-09 13:35:56.916  1013  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:35:56.916  1013  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:56.916  1013  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:56.916  1013  1130 E WifiNative-wlan0: do suspend true
09-09 13:35:56.916  1013  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:35:56.916  2654  6844 D BluetoothSocket: channel: 5
09-09 13:35:56.916  1013  3230 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:35:56.916  1013  3230 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.916  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.916  1013  3230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.916  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:35:56.936  6845  6845 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:35:56.936  6845  6845 E dhcpcd  : wlan0: sendmsg: Network is unreachable
,09-09 13:35:56.936  1325  1325 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:35:56.936  1325  1325 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:56.946  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.946  6845  6845 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 13:35:56.946  6845  6845 I dhcpcd  : bssid match
09-09 13:35:56.946  6845  6845 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-09 13:35:56.946  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
09-09 13:35:56.946  1013  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 13:35:56.946  1013  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-09 13:35:56.946   277   982 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:56.956  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:56.956  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:56.956  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.956  6710  6710 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:56.966  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
09-09 13:35:56.966  2654  2654 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:35:56.966  1013  3214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-09 13:35:56.966  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
09-09 13:35:56.966  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.966  1013  3214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.966  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.966  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:56.966  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:35:56.976  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:56.976  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 13:35:56.976  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.976  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.976  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.976  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.976  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:56.976  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:35:56.976  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 13:35:56.976  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:56.976  1173  1173 D HotspotTile: onReceive : 0, 0
,09-09 13:35:56.986  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.986  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:56.986  1013  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:35:56.996  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:56.996  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:35:56.996  1013  1356 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:56.996  1013  1356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 13:35:57.006  1013  1356 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.006  1013  1356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:57.006  1013  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:57.006  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:57.006  2654  6862 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:57.006  2654  6862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:57.006  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:57.006  2654  6862 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-09 13:35:57.006  2654  6862 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:57.006  2654  6862 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:57.006  2654  6862 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a6bb333
,09-09 13:35:57.016  2654  6862 D BluetoothSocket: channel: 12
,09-09 13:35:57.016  2654  6862 I BtOppRfcommListener: Accept thread started.
,09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:57.016  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:57.016  1907  6863 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 13:35:57.016  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 13:35:57.016  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:57.026  1013  1245 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:57.026  1013  1245 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.026  1013  1245 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.026  1013  1245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.026  1013  1245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:57.026  1013  2968 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:57.026  3578  3578 I Hs20UtilService: Starting #15
,09-09 13:35:57.026  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.026  1013  2968 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:57.026  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:57.026  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:35:57.036  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:35:57.036  1907  6863 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
09-09 13:35:57.036  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:57.036  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:57.036  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:57.036  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:57.036  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:57.036  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:57.046  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:35:57.046  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:57.046  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:57.046  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:57.046  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:57.046  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:57.046  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:57.056  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:57.056  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:35:57.056  6392  6392 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:35:57.056  6424  6424 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:57.066  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:57.066  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.066  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.066  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:57.066  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:57.076  3578  3578 I Hs20UtilService: Starting #16
,09-09 13:35:57.076  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:57.076  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:35:57.076  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:35:57.076  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:57.076  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:57.076  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:57.076  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:57.076  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:57.086  1013  1541 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:57.086  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.086  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.086  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:57.086  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:57.086  3578  3578 I Hs20UtilService: Starting #17
,09-09 13:35:57.096  3578  3598 I Hs20UtilService: Message received 5011
09-09 13:35:57.096  6710  6710 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:57.106  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:57.106  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:57.106  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:57.106  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:57.126  6710  6710 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:35:57.126  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:57.126  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:57.126  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:35:57.126  6845  6845 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-09 13:35:57.126  6845  6845 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-09 13:35:57.146  6710  6710 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 13:35:57.156  6710  6710 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,09-09 13:35:57.156  1013  1130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-09 13:35:57.156  6710  6710 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:35:57.156  6710  6710 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:35:57.156  6710  6710 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:57.156  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 13:35:57.156  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:57.166  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-09 13:35:57.166  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.166  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:57.166  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:57.166  1013  1133 D Tethering: InitialState.processMessage what=4
09-09 13:35:57.166  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.166  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:57.176  1013  1133 E Tethering: No numeric data
,09-09 13:35:57.176  1013  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:35:57.176  1013  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:57.176  1013  1026 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 13:35:57.176  1013  1133 D Tethering: clearTetheredNotification()
09-09 13:35:57.176  1013  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:35:57.176  1013  1026 D BatteryService: stay LED for charging
09-09 13:35:57.186  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.176  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 13:35:57.176  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.186  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:57.186  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:57.186  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:57.186  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:57.186  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:35:57.186  1013  1123 V NetworkStats: performPollLocked() took 7ms
,09-09 13:35:57.186  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:57.196  1013  1013 I MotionRecognitionService: Plugged
09-09 13:35:57.196  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:35:57.196  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:35:57.206  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:35:57.196  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:35:57.206  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-09 13:35:57.226  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:35:57.226  2654  6795 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:57.226  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2,
09-09 13:35:57.226  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
09-09 13:35:57.226  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:35:57.296  1013  1039 W ProcessCpuTracker: Skipping unknown process pid 6868,
,09-09 13:35:57.296  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.296  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:57.316  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:35:57.316  1013  1025 D WifiService: setWifiEnabled: true pid=6233, uid=10155
09-09 13:35:57.316  1013  1025 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:35:57.316  1013  1025 W ActivityManager: Permission Denial: getCurrentUser() from pid=6233, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:57.316  1013  1025 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:57.316  1013  1025 D SecContentProvider2: mCursor = null
09-09 13:35:57.316  1013  1025 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:35:57.316  1013  1025 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6233, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:57.316  1013  1025 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 13:35:57.316  1013  1025 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:35:57.316  1013  1025 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:35:57.316  1013  1025 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:35:57.316  1013  1025 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 13:35:57.316  1013  1025 D SettingsProvider: name = wifi_on
,09-09 13:35:57.416  6710  6710 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 13:35:57.466  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.466  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:57.466  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:57.516  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:35:57.516  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.516  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:57.516  6710  6710 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-09 13:35:57.626  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 13:35:57.626  1013  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-09 13:35:57.626  1013  1130 E WifiConfigStore: setLastSelectedConfiguration -1
09-09 13:35:57.626  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:57.636  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:57.636  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 13:35:57.636  1907  2131 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.636  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:57.636  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.636  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:57.636  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.636  1173  1173 D HotspotTile: onReceive : 1, 0
09-09 13:35:57.636  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:57.636  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.636  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:57.636  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-09 13:35:57.636  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:57.646  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.646  1013  3230 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:57.646  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.646  1013  3230 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.646  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.646  1013  3230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:57.646  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:57.646  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.656  3578  3578 I Hs20UtilService: Starting #18
,09-09 13:35:57.656  3578  3598 I Hs20UtilService: Message received 5011
,09-09 13:35:57.656  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:57.656  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:57.656  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:57.656  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:58.316   277   976 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-09 13:35:58.316  1013  1041 D Tethering: interfaceRemoved wlan0
,09-09 13:35:58.316  1013  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:35:58.556  1013  1041 D Tethering: interfaceRemoved p2p0
,09-09 13:35:58.556  1013  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:35:58.686  1013  3229 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-09 13:35:58.686  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-09 13:35:58.696  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.696  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.696  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 13:35:58.706  6568  6616 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:35:58.736  1013  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.736  1013  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.736  1013  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.746  1013  1541 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-09 13:35:58.746  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-09 13:35:58.746  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.746  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.746  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.756  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.756  1013  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.756  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.766  1013  1025 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:35:58.766  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 13:35:58.766  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:58.766  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.766  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.776  1013  3228 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.776  1013  3228 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:35:58.776  1013  3228 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.776  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
09-09 13:35:58.776  1013  3228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 13:35:58.776  1013  2967 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:35:58.776  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:35:58.776  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:58.776  1013  2967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.776  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.786  1013  3229 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-09 13:35:58.796  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-09 13:35:58.796  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:58.796  1013  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.796  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.826  1013  1540 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:58.826  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.826  1013  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.826  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 13:35:58.836  1907  1907 D WearableService: callingUid 10012, callindPid: 1907
,09-09 13:35:58.846  1013  3228 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:35:58.846  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:35:58.846  1013  3228 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.856  1013  3228 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:58.856  1013  3228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:35:58.936  6483  6890 I MusicLeanback: Conditions not met for autocaching.
,09-09 13:35:58.936  6483  6890 I MusicLeanback: Stop autocaching.
,09-09 13:35:58.996  1907  4379 I art     : Explicit concurrent mark sweep GC freed 64433(3MB) AllocSpace objects, 62(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.333ms total 84.668ms
,09-09 13:35:59.006  6483  6483 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 13:35:59.006  6483  6895 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 13:35:59.256  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:35:59.266  1013  1130 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:35:59.626  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:35:59.626  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:59.626  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:59.626  1013  1041 D Tethering: interfaceAdded wlan0
,09-09 13:35:59.636  1013  1133 E Tethering: No numeric data
09-09 13:35:59.636  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:59.636  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.636  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:59.636  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:59.636  1013  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:59.646  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:59.636  1013  1133 D Tethering: clearTetheredNotification()
09-09 13:35:59.646  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:59.636  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:59.646  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:35:59.636  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:59.646  1013  1041 D Tethering: interfaceAdded p2p0
09-09 13:35:59.646  1013  1123 V NetworkStats: performPollLocked() took 10ms
09-09 13:35:59.646  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.646  1013  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 13:35:59.646  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.646  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.656   277   982 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-09 13:35:59.656   277   982 D SoftapController: Softap fwReload - Ok
,09-09 13:35:59.656   277   982 D CommandListener: Setting iface cfg,
09-09 13:35:59.656   277   982 D CommandListener: Trying to bring down wlan0
,09-09 13:35:59.656   277   982 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:59.666  1013  1130 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:35:59.706  6904  6904 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-09 13:35:59.706  6904  6904 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:35:59.706  6904  6904 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:35:59.716   290   290 E SMD     : DCD OFF
,09-09 13:35:59.726  6904  6904 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 13:35:59.726   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6904
09-09 13:35:59.726   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,09-09 13:35:59.726  6904  6904 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:35:59.726  6904  6904 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:59.726  6904  6904 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:35:59.726  6904  6904 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-09 13:35:59.726   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6904
09-09 13:35:59.726   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-09 13:35:59.766  1013  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:35:59.766  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:59.766  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:59.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:59.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:59.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:59.766  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:35:59.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:59.766  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:59.766  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-09 13:35:59.766  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:35:59.776  1173  1173 D HotspotTile: onReceive : 2, 0
,09-09 13:35:59.776  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:59.776  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:59.786  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-09 13:35:59.786  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:59.786  1013  1540 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:59.786  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:59.786  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:59.786  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:59.786  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:35:59.796  3578  3578 I Hs20UtilService: Starting #19
,09-09 13:35:59.796  3578  3598 I Hs20UtilService: Message received 5011
,09-09 13:35:59.796  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:59.796  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:59.796  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:59.796  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:59.886   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,09-09 13:35:59.896  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,09-09 13:35:59.956  6904  6904 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:35:59.956  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 13:35:59.966  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 13:35:59.976   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6904
09-09 13:35:59.976   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-09 13:35:59.976  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,09-09 13:35:59.976  6904  6904 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:59.976  6904  6904 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:59.976  6904  6904 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:59.976  6904  6904 E wpa_supplicant: SIM READ ERROR
09-09 13:35:59.976  6904  6904 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 13:35:59.976  6904  6904 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:59.976  6904  6904 E wpa_supplicant: SIM READ ERROR
09-09 13:35:59.976  6904  6904 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:35:59.976  6904  6904 I wpa_supplicant: wpa_default_ap_write_once,
09-09 13:35:59.976  6904  6904 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:35:59.976  6904  6904 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:59.976  6904  6904 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:35:59.976  6904  6904 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:59.976  6904  6904 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 13:35:59.976  6904  6904 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:35:59.976  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:59.976  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:59.976  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:59.976  1013  1041 D Tethering: interfaceStatusChanged wlan0, false,
09-09 13:35:59.976  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:35:59.976  1013  1133 D Tethering: InitialState.processMessage what=4
09-09 13:35:59.976  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:59.976  1013  1133 E Tethering: No numeric data
09-09 13:35:59.976  1013  2727 D SSRM:n  : SIOP:: AP = 340
,09-09 13:35:59.976  1013  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:59.976  1013  1133 D Tethering: clearTetheredNotification()
09-09 13:35:59.976  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.976  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:59.976  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:59.986  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.986  1013  1123 V NetworkStats: performPollLocked() took 4ms
,09-09 13:35:59.986  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.986  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.996  1013  1093 V AlarmManager: waitForAlarm result :8
,09-09 13:36:00.066  6904  6904 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 13:36:00.246  6904  6904 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:36:00.246  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 13:36:00.256  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 13:36:00.256   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6904
09-09 13:36:00.256   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-09 13:36:00.256  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 13:36:00.256  6904  6904 I wpa_supplicant: ssSupport state is = 1
09-09 13:36:00.256  6904  6904 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:36:00.256  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-09 13:36:00.276  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 13:36:00.276   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6904
09-09 13:36:00.276   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-09 13:36:00.276  6904  6904 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 13:36:00.276  6904  6904 I wpa_supplicant: ssSupport state is = 1
09-09 13:36:00.276  6904  6904 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.276  6904  6904 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 13:36:00.276  6904  6904 E wpa_supplicant: SIM READ ERROR
09-09 13:36:00.276  6904  6904 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:36:00.276  6904  6904 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:36:00.276  6904  6904 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:36:00.276  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:36:00.276  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:36:00.276  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:36:00.276  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 13:36:00.276  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:36:00.276  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:36:00.326  6904  6904 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 13:36:00.326  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:36:00.486  6904  6904 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-09 13:36:00.486  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:36:00.486  6904  6904 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:36:00.486  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 13:36:00.486  1013  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-09 13:36:00.486  6904  6904 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-09 13:36:00.496  6904  6904 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.496  6904  6904 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:36:00.496  6904  6904 E wpa_supplicant: SIM READ ERROR
09-09 13:36:00.496  6904  6904 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 13:36:00.516  6904  6904 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:36:00.526  6904  6904 I wpa_supplicant: Skip scan - bUseNetwork false,
09-09 13:36:00.526  1013  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:36:00.526  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:00.526  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:36:00.526  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:00.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:00.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:00.536  1173  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:36:00.536  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:00.536  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:00.536  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-09 13:36:00.536  1173  1173 D HotspotTile: onReceive : 3, 0
09-09 13:36:00.536  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 13:36:00.536  1325  1325 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:00.536  1013  1130 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:00.546  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:00.546  1013  1130 E WifiConfigStore: Not a HS20
,09-09 13:36:00.556  1013  1130 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
09-09 13:36:00.556  1013  1638 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:00.556  1013  1638 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:36:00.556  1013  1638 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:00.556  1013  1638 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:00.556  1013  1638 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:00.556  1013  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:36:00.556  3578  3578 I Hs20UtilService: Starting #20
09-09 13:36:00.556  3578  3598 I Hs20UtilService: Message received 5011
,09-09 13:36:00.556  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:00.556  1013  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:36:00.556  6904  6904 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:36:00.556  6904  6904 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:36:00.556  6904  6904 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:36:00.556  6904  6904 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:36:00.556  6904  6904 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:36:00.556  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:36:00.556  6904  6904 I wpa_supplicant: First Scan Start
,09-09 13:36:00.556  6904  6904 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:36:00.566  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:36:00.566  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:36:00.566  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:36:00.566  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:36:00.566  1013  1130 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:36:00.566  1013  1130 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:00.566  1013  1130 I WifiNative-HAL: startHal
09-09 13:36:00.566  1013  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9c84c88c
09-09 13:36:00.566  1013  1130 I WifiNative-HAL: Could not start hal
,09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:00.566  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:00.566  6455  6455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:00.566  1013  1130 E WifiNative-wlan0: do suspend true
,09-09 13:36:00.566  1013  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 13:36:00.576   277   982 D CommandListener: Setting iface cfg
09-09 13:36:00.576   277   982 D CommandListener: Trying to bring up p2p0
,09-09 13:36:00.576  1013  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:36:00.576  1013  1125 D WifiP2pService: P2pEnablingState
09-09 13:36:00.576  1013  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:36:00.576  1013  1125 D WifiP2pService: P2p socket connection successful
,09-09 13:36:00.576  1013  1125 D WifiP2pService: P2pEnabledState
,09-09 13:36:00.576  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:00.576  1013  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:36:00.576  1013  1132 E ConnectivityService: updateNetworkInfo()
,09-09 13:36:00.586  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:36:00.586  1013  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-09 13:36:00.586  1013  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 13:36:00.586  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:36:00.586  1013  1044 D WifiDisplayController: disconnect
,09-09 13:36:00.586  1013  1044 D WifiDisplayController: updateConnection
,09-09 13:36:00.586  1013  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:36:00.586  1013  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:36:00.586  1013  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:36:00.586  1013  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:36:00.586  1013  1130 E WifiNative-wlan0: invaild command id : 215
,09-09 13:36:00.586  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3,
09-09 13:36:00.586  1013  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:00.586  1013  1148 I WifiNative-HAL: startHal
09-09 13:36:00.586  1013  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:00.586  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:00.586  1013  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:36:00.586  1013  1013 D RttService: SCAN_AVAILABLE : 3
09-09 13:36:00.586  1013  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-09 13:36:00.586  1013  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:00.586  1013  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:36:00.596  1013  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 13:36:00.596  1013  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dd049bc
09-09 13:36:00.596  1013  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-09 13:36:00.596  1013  1148 I WifiNative-HAL: Could not start hal
09-09 13:36:00.596  1013  1148 E WifiScanningService: could not start HAL
09-09 13:36:00.596  1013  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:36:00.596  1013  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:36:00.596  1013  1130 E WifiNative-wlan0: invaild command id : 215
09-09 13:36:00.596  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:00.596  6904  6904 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:36:00.596  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-09 13:36:00.606  1013  2967 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:36:00.606  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:36:00.606  6904  6904 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:36:00.606  1013  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-09 13:36:00.606  1013  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  secondary type: null
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  wps: 0
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  grpcapab: 0
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  devcapab: 0
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  status: 3
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  wfdInfo: null
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  groupownerAddress: null
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  GOdeviceName: null
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  interfaceAddress: 
09-09 13:36:00.606  1013  1044 D WifiDisplayController:  SConnectInfo : null
,09-09 13:36:00.606  6904  6904 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-09 13:36:00.606  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:36:00.606  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:36:00.606  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:36:00.616  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:00.616  1013  1130 D SecContentProvider2: mCursor = null
09-09 13:36:00.616  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:36:00.616  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:36:00.616  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:36:00.616  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:36:00.616  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:00.616  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:36:00.616  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:36:00.616  6392  6392 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:36:00.616  6392  6392 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:36:00.626  1013  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 13:36:00.626  1013  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:36:00.626  1013  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:36:00.626  6424  6424 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:36:00.636  1013  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:36:00.636  1013  1125 D WifiP2pService: InactiveState
,09-09 13:36:00.636  1013  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:36:00.636  1013  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:36:00.636  6904  6904 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-09 13:36:00.636  1013  1125 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:36:00.636  1013  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:36:00.826  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:00.826  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:00.826  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:00.826  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:00.826  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:36:00.826  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7c62b7 removed from the list
09-09 13:36:00.826  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:00.826  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e93fa24 removed from the list
09-09 13:36:00.826  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 13:36:00.826  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:00.836  6233  6911 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775,
09-09 13:36:00.836  6233  6911 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:01.336   277   978 D EnterpriseController: uids 10155
09-09 13:36:01.336   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:36:01.336   277   978 D Netd    : getNetworkForDns: using netid 0 for uid 10155
,09-09 13:36:01.346  6233  6911 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:36:01.346  6233  6911 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:36:01.346  6233  6911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:01.346  6233  6911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:01.346  6233  6913 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:36:01.346  6233  6913 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:01.346  6233  6913 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:01.346  6233  6911 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:36:01.346  6233  6913 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:01.346  6233  6918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1229, name: IncomingSocketThread/Sender)
09-09 13:36:01.346  6233  6913 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:01.346  6233  6917 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1228, name: OutgoingSocketThread/Receiver)
09-09 13:36:01.346  6233  6917 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1228, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:01.346  6233  6916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1227, name: OutgoingSocketThread/Sender)
09-09 13:36:01.346  6233  6917 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:01.346  6233  6917 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1228, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:36:01.356  6233  6919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1230, name: IncomingSocketThread/Receiver)
09-09 13:36:01.356  6233  6919 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1230, thread name: IncomingSocketThread/Receiver)
09-09 13:36:01.356  6233  6919 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:01.356  6233  6919 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1230, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:36:01.356  2654  2718 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:36:01.636  6904  6904 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
,09-09 13:36:01.636  6904  6904 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:36:01.646  1013  6909 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:36:01.646  6904  6904 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 13:36:01.646  6904  6904 I wpa_supplicant: Trying to associate with  'G700',
09-09 13:36:01.646  6904  6904 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-09 13:36:01.646  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-09 13:36:01.666  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 13:36:01.666  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:36:01.776  6904  6904 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:36:01.776  6904  6904 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:36:01.776  6904  6904 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 13:36:01.776  6904  6904 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 13:36:01.776  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:36:01.776  6904  6904 I wpa_supplicant: Associated with F4.99.3E
09-09 13:36:01.776  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.776  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:36:01.776  6904  6904 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:36:01.776  6904  6904 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 13:36:01.776  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:36:01.776  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:36:01.786  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:36:01.786  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.786  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:36:01.786  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.786  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.786  1013  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:36:01.786  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.786  1013  1041 D Tethering: interfaceStatusChanged wlan0, true
09-09 13:36:01.786  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:01.786  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:36:01.786  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.796  6904  6904 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-09 13:36:01.796  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 13:36:01.796  1013  1130 D SecContentProvider2: mCursor = null
09-09 13:36:01.796  6904  6904 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
09-09 13:36:01.796  6904  6904 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 13:36:01.796  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 13:36:01.796  6904  6904 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:36:01.796  6904  6904 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 13:36:01.796  6904  6904 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
09-09 13:36:01.796  6904  6904 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:36:01.796  6904  6904 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 13:36:01.796  1013  1133 E Tethering: No numeric data
,09-09 13:36:01.796  1013  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.796  1013  1041 D Tethering: interfaceStatusChanged wlan0, true,
,09-09 13:36:01.796  1013  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.796  1013  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:36:01.796  1013  1133 D Tethering: clearTetheredNotification()
,09-09 13:36:01.806  1013  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:36:01.806  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:36:01.806  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:01.806  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:36:01.806  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:36:01.806  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:36:01.806  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:01.806  1013  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:36:01.816  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:01.816  1013  1123 V NetworkStats: performPollLocked() took 6ms
,09-09 13:36:01.816  1013  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 13:36:01.816  1013  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 13:36:01.816  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:01.816  1013  1132 E ConnectivityService: updateNetworkInfo()
,09-09 13:36:01.816  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:01.816  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:01.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.826  1013  1638 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 13:36:01.826  1013  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:01.826  1013  1638 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:36:01.826  1013  1638 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:01.826  1013  1638 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 13:36:01.826  1013  1638 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:36:01.826  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:01.826  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:01.826  3578  3578 I Hs20UtilService: Starting #21
,09-09 13:36:01.826  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:36:01.826  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:36:01.826  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:36:01.826  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:36:01.826  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:36:01.836  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:36:01.836  1325  1325 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:36:01.836  1325  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:36:01.836  1013  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2df62715 Bundle[{}]
,09-09 13:36:01.846  6233  6282 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:36:01.846  6233  6282 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:36:01.846   277   982 D CommandListener: Setting iface cfg
,09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:36:01.846  1013  1130 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 13:36:01.846  6233  6282 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 13:36:01.846  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:01.846  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:36:01.856  6233  6922 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:36:01.856  6233  6922 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:01.856  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:01.866  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:36:01.866  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.866  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.866  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.866  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.866  1013  1130 E WifiNative-wlan0: do suspend false
,09-09 13:36:01.866  1013  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:36:01.866  1013  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:36:01.866  1013  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:01.866  1013  1130 D SecContentProvider2: mCursor = null
,09-09 13:36:02.096  6926  6926 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:36:02.106  6926  6926 I dhcpcd  : version 5.5.6 starting
,09-09 13:36:02.106  6926  6926 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:36:02.156  6926  6926 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:36:02.156  6926  6926 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 13:36:02.156  6926  6926 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 13:36:02.156  6926  6926 I dhcpcd  : bssid match
09-09 13:36:02.156  6926  6926 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-09 13:36:02.276  6926  6926 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-09 13:36:02.356  6926  6926 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-09 13:36:02.366  6233  6934 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 13:36:02.366  6233  6934 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:02.366  6233  6934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:02.366  6233  6934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:02.366  6233  6934 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:02.366  6233  6922 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:36:02.366  6233  6922 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:02.366  6233  6922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:02.366  6233  6922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:02.366  6233  6922 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:36:02.366  6233  6940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1244, name: OutgoingSocketThread/Receiver)
09-09 13:36:02.366  6233  6940 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1244, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:02.366  6233  6940 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:02.366  6233  6940 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1244, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:36:02.366  6233  6937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1242, name: IncomingSocketThread/Receiver)
,09-09 13:36:02.376  6233  6937 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1242, thread name: IncomingSocketThread/Receiver)
09-09 13:36:02.376  6233  6937 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:02.376  6233  6937 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1242, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:36:02.376  6233  6936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1241, name: IncomingSocketThread/Sender)
,09-09 13:36:02.376  6233  6939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1243, name: OutgoingSocketThread/Sender)
,09-09 13:36:02.696  1013  1130 E WifiNative-wlan0: do suspend true,
,09-09 13:36:02.716   290   290 E SMD     : DCD OFF,
,09-09 13:36:02.726  1013  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:36:02.726  1013  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:36:02.726  1013  1130 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-09 13:36:02.726  1013  1130 E WifiStateMachine: VerifyingLinkState enter
09-09 13:36:02.726  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:02.726  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:02.726  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.726  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.726  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.726  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.736  1013  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:36:02.736  1013  1132 E ConnectivityService: updateNetworkInfo(),
,09-09 13:36:02.736  1013  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-09 13:36:02.736  1013  1132 D ConnectivityService: Adding iface wlan0 to network 504
,09-09 13:36:02.756  1013  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-09 13:36:02.756  1013  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:36:02.756  1013  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-09 13:36:02.756  1013  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:36:02.756  1013  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:36:02.766  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:02.766  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:02.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.766  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.776  1013  1130 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 13:36:02.776  1013  3229 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:36:02.776  1013  3229 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:36:02.776  1013  3229 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:02.776  1013  3229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:02.776  1013  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:02.786  3578  3578 I Hs20UtilService: Starting #22
,09-09 13:36:02.786  1013  1132 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-09 13:36:02.786  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:36:02.786  1013  1132 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-09 13:36:02.796  1325  1325 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 13:36:02.796  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:36:02.796  1013  1132 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-09 13:36:02.796  1013  1132 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:36:02.796  1013  1132 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 13:36:02.796  1013  1132 D ConnectivityService: LTETest block dns file not exists
,09-09 13:36:02.806  1013  1132 E ConnectivityService: updateNetworkInfo(),
,09-09 13:36:02.806  1013  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:02.816  1013  1132 E ConnectivityService: updateNetworkInfo()
09-09 13:36:02.816  1013  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:02.816  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.816  1013  1132 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.816  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 13:36:02.816  1013  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.816  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.816  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-09 13:36:02.816  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:36:02.816  1013  6920 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,09-09 13:36:02.816   277   978 D EnterpriseController: uids 1000
09-09 13:36:02.816   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:36:02.816   277   978 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-09 13:36:02.826  1013  1132 D ConnectivityService:    accepting network in place of null
,09-09 13:36:02.826  1013  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:36:02.826  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:36:02.826  1454  1454 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:36:02.826  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:02.826  1013  1132 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 13:36:02.826  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:02.826  1013  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:02.826  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.826  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.826  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.826  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.826  1013  1132 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-09 13:36:02.836  1013  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-09 13:36:02.836  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:36:02.836  1013  1013 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:36:02.836  1013  1013 I WifiTrafficPoller: current booster mode : FullMode
,09-09 13:36:02.836  1013  1013 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-09 13:36:02.846  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:02.846  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:36:02.846  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.846  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.846  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.846  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.846  1013  1132 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-09 13:36:02.846  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:36:02.846  1013  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.846  1013  1133 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:36:02.846  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.846  1013  1123 V NetworkStats: updateIfacesLocked()
09-09 13:36:02.846  1013  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:36:02.846  1013  1123 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:36:02.846  1173  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:02.846  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:36:02.846  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:36:02.846  3806  6291 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:36:02.856  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.856  1013  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:02.856  1013  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-09 13:36:02.856  1013  1317 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:36:02.856  1013  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:02.856  1013  1123 V NetworkStats: performPollLocked() took 8ms
09-09 13:36:02.856  1013  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:36:02.856  3578  3578 I Hs20UtilService: Starting #23
09-09 13:36:02.856  3578  3598 I Hs20UtilService: Message received 5007
09-09 13:36:02.856  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.856  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.856  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.856  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.856  1013  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-09 13:36:02.866  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:36:02.866  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:36:02.866  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-09 13:36:02.866  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:36:02.866  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:36:02.866  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:36:02.866  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:36:02.866  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:36:02.866  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:36:02.866  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:36:02.866  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 13:36:02.866  1325  1325 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 13:36:02.866  6233  6282 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1253)
09-09 13:36:02.866  6233  6282 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:36:02.866  6233  6282 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1254)
09-09 13:36:02.866  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:02.866  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cf5742 added. We now have 3 listener(s)
,09-09 13:36:02.876  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.876  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:02.876  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.876  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.886  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:36:02.886  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:02.886  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:02.886  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:02.886  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ea7353 added. We now have 3 listener(s)
09-09 13:36:02.886  6233  6282 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:02.886  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:02.886  1013  1540 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:02.886  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:36:02.886  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:02.886  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:02.886  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:02.886  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 13:36:02.886  3578  3578 I Hs20UtilService: Starting #24
,09-09 13:36:02.896  3578  3598 I Hs20UtilService: Message received 5007
,09-09 13:36:02.896  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:36:02.896  1325  1325 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.906  6233  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:02.906  1013  1245 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 13:36:02.906  6233  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.906  6233  6282 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:36:02.906  1013  3228 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 13:36:02.906  1013  3228 D SecContentProvider2: mCursor = null
,09-09 13:36:02.906  1013  1075 D SecContentProvider2: uri = 15 selection = getToastGravity
,09-09 13:36:02.906  1013  1075 D SecContentProvider2: mCursor = null
,09-09 13:36:02.906  1013  1025 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-09 13:36:02.906  1013  1025 D SecContentProvider2: mCursor = null
,09-09 13:36:02.906  1013  3230 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:02.916  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.916  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:02.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:02.916  6233  6282 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cf5742 removed from the list
09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:02.916  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ea7353 removed from the list
09-09 13:36:02.916  1013  3230 D SecContentProvider2: mCursor = null
,09-09 13:36:02.916  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:02.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:02.916  6233  6282 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-09 13:36:02.916  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:02.916  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:02.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:02.916  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:36:02.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:36:02.916  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:36:02.916  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:36:02.916  1013  1356 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-09 13:36:02.916  1013  1356 D SecContentProvider2: mCursor = null
,09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:02.916  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:02.916  1013  1075 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-09 13:36:02.916  1013  1075 D SecContentProvider2: mCursor = null
,09-09 13:36:02.926  1013  6920 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:36:02.926  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:02.926  6233  6965 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:36:02.926  6233  6965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:36:02.926  6233  6965 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
09-09 13:36:02.936  6233  6965 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:36:02.936  6233  6965 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:36:02.936  6233  6965 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cffa58e
09-09 13:36:02.936  6233  6965 D BluetoothSocket: channel: 6
09-09 13:36:02.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:36:02.936  6233  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:36:02.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:02.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:36:02.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:36:02.936  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 7C F9 0E 37 96 AB
09-09 13:36:02.936  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:36:02.936  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:02.936  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:36:02.936  2654  2663 D BtGatt.GattService: registerClient() - UUID=ff22d81f-af7d-47fd-adf7-f35f7ee5a8e5
,09-09 13:36:02.946   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-09 13:36:02.966  1013  1540 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,09-09 13:36:02.976  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:36:02.986  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=ff22d81f-af7d-47fd-adf7-f35f7ee5a8e5, clientIf=5
,09-09 13:36:02.986  6233  6241 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:02.986  2654  6793 D BtGatt.AdvertiseManager: message : 0
,09-09 13:36:02.986  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:02 GMT], X-Android-Received-Millis=[1473420962990], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420962954]}
09-09 13:36:02.986  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:36:02.986  1013  6920 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 13:36:02.986  1013  1132 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.986  1013  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.986  1013  1132 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 13:36:02.986  1013  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:02.986  3806  6291 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:02.986  1013  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:36:02.986  1173  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:36:02.996  2654  6793 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 7
,09-09 13:36:02.996  2654  6793 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:36:02.996  2654  6793 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:36:02.996  2654  6793 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:36:02.996  2654  6793 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:36:03.006  2654  2720 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:36:03.006  2654  6793 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:36:03.006  2654  2720 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:36:03.006  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,09-09 13:36:03.006  2654  6793 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:36:03.006  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:36:03.006  2654  6793 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:36:03.006  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:36:03.006  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:36:03.006  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:36:03.006  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:36:03.016  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:36:03.016  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:03.016  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:03.016  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:36:03.016  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:36:03.016  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:36:03.016  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:36:03.016  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:36:03.016  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:03.026  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.026  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:03.026  6233  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:36:03.026  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:03.346  1013  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.366  1013  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.376  3142  3142 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:03.386  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:03.386  6483  6483 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:03.386  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:03.396  5813  5813 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:36:03.396  5813  5813 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 13:36:03.396  5813  5813 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:36:03.396  5813  5813 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.396  1013  2967 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-09 13:36:03.406  1013  2967 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:03.406  6233  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:03.406  6233  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:03.416  6483  6483 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:36:03.426  1724  1724 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:36:03.426  6495  6495 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 13:36:03.436  1013  1638 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:36:03.446  1013  1025 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:36:03.456  1724  1724 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-09 13:36:03.456  1724  1724 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-09 13:36:03.456  1724  1724 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-09 13:36:03.456  1724  1724 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
09-09 13:36:03.456  1294  1303 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-09 13:36:03.456  1724  1724 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 13:36:03.526  6233  6233 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:36:03.526  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:03.526  6233  6233 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:03.596  1013  3214 I art     : Explicit concurrent mark sweep GC freed 91352(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.459ms total 160.913ms
,09-09 13:36:03.596  1013  3214 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 13:36:03.596  1013  3214 D SecContentProvider2: mCursor = null
,09-09 13:36:03.606  6495  6495 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-09 13:36:03.606  6495  6495 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-09 13:36:03.616  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:36:03.616  6439  6439 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:36:03.616  6439  6439 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:36:03.616  6495  6495 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-09 13:36:03.616  1724  1724 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:36:03.616  1724  1724 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 13:36:03.616  6439  6439 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:36:03.616  6660  6660 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.626  6660  6660 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:36:03.626  6660  6660 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-09 13:36:03.626  6660  6660 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:36:03.626  3601  3601 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:36:03 GMT+02:00 2016
,09-09 13:36:03.626  1013  2967 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:36:03.626  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.636  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.636  1013  2967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.636  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:36:03.636  3601  3601 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:36:03.636  3601  3601 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 13:36:03.646  3601  3601 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:36:03.646  3601  3601 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:36:03.656  3601  6972 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:36:03.656  3601  6972 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:36:03.666  3601  6972 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false,
,09-09 13:36:03.666  3601  6972 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-09 13:36:03.666  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:36:03.666  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.666  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.666  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:36:03.666  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:36:03.676  3601  6972 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-09 13:36:03.676  1013  2967 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 13:36:03.676  1013  2967 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.676  1013  2967 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.676  3601  6972 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
09-09 13:36:03.676  1013  2967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.676  1013  2967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 13:36:03.686  3601  6972 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 13:36:03.686   277   978 D EnterpriseController: uids 10012
09-09 13:36:03.686   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:36:03.686   277   978 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,09-09 13:36:03.686  3806  3806 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:36:03.696  3806  4608 I iu.UploadsManager: num queued entries: 0
,09-09 13:36:03.696  3601  3601 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
09-09 13:36:03.696  3806  4608 I iu.UploadsManager: num updated entries: 0
,09-09 13:36:03.696  3806  4608 I iu.SyncManager: NEXT; no task
,09-09 13:36:03.696  6718  6718 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.706  6718  6718 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:36:03.706  6718  6718 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:36:03.726  5966  5966 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:36:03.736  5881  5881 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-09 13:36:03.736  3190  6984 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:36:03.736  6057  6057 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 13:36:03.746  6057  6057 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,09-09 13:36:03.746  6057  6057 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
09-09 13:36:03.746  3190  6984 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-09 13:36:03.746  3190  6984 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:36:03.746  6057  6057 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:36:03.746  6057  6057 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:36:03.756  6057  6057 I SA      : [SCU] == networkStateCheck == true
,09-09 13:36:03.756  6057  6057 I SA      : [DM] getCountryCodeFromCSC : PL
09-09 13:36:03.756  6057  6057 I SA      : isChinaCountryCode : false
09-09 13:36:03.756  6057  6057 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:36:03.756  6057  6057 I SA      : [OR] == networkStateCheck true ==
,09-09 13:36:03.756  6057  6057 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:36:03.756  6057  6057 I SA      : [OR] onReceive END
,09-09 13:36:03.766  1221  1221 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.766  1013  1541 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-09 13:36:03.766  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.766  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:03.766  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.766  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-09 13:36:03.776  6057  6987 I SA      : [SRS] prepareGetMyCountryZone
,09-09 13:36:03.786  6057  6987 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:36:03.786  6057  6987 I SA      : [SSP] query invoked
,09-09 13:36:03.796  3190  6984 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-09 13:36:03.796  6057  6987 I SA      : [TPMU] GetMccFromDB : null
09-09 13:36:03.796  6057  6987 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:36:03.796  6057  6987 I SA      : [LBE] isSupportCheckDomainRegion : false
09-09 13:36:03.796  6057  6987 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:36:03.796  3190  6984 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-09 13:36:03.796  3190  6984 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-09 13:36:03.796  1013  1075 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-09 13:36:03.796  1013  1075 D SecContentProvider2: mCursor = null
09-09 13:36:03.796  3190  6984 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-09 13:36:03.806  3190  6984 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-09 13:36:03.806  3190  6984 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-09 13:36:03.806  3190  6984 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-09 13:36:03.806  6057  6987 E File    : fail readDirectory() errno=2
,09-09 13:36:03.806  3190  6984 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-09 13:36:03.816  3190  6984 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-09 13:36:03.826  3190  6984 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:36:03.846  1907  6974 I qtaguid : Tagging socket 46 with tag 1000040700000000{268436487,0} for uid -1, pid: 1907, getuid(): 10012
,09-09 13:36:03.846  1013  1132 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 13:36:03.916  1013  3230 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:36:03.916  1013  3230 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.916  1013  3230 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:03.916  1013  3230 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:36:03.916  1013  3230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:36:03.926  1013  3228 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:36:03.926  5966  5966 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-09 13:36:03.926  5966  5966 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-09 13:36:03.926  5966  5966 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:36:03.926  5966  5966 D InitializeManagerStateMachine: exit::IDLE
09-09 13:36:03.926  5966  5966 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:36:03.936  5966  5966 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:36:03.936  5966  5966 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:36:03.936  5966  5966 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: exit::SUCCESS
09-09 13:36:03.936  5966  5966 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:36:04.006  1013  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:04.006  1013  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:36:04.006  1013  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:36:04.066  1013  1046 I PowerManagerService: [PWL] Off : 75s ago
,09-09 13:36:04.206  6057  6987 I SA      : [RC New] Execute method=[GET] start
,09-09 13:36:04.236  6057  6987 I SA      : [RC New] Security=[true]
,09-09 13:36:04.246  6057  6987 I System.out: Thread-1020(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-09 13:36:04.246  6057  6987 I System.out: Thread-1020(ApacheHTTPLog):isSBSettingEnabled false
,09-09 13:36:04.246  6057  6987 I System.out: Thread-1020(ApacheHTTPLog):isShipBuild true
09-09 13:36:04.246  6057  6987 I System.out: Thread-1020(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,09-09 13:36:04.246  6057  6987 I System.out: Thread-1020(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:36:04.246   277   978 D EnterpriseController: uids 10041
09-09 13:36:04.246   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:36:04.246   277   978 D Netd    : getNetworkForDns: using netid 504 for uid 10041
,09-09 13:36:04.836  6057  6987 I SA      : [RC New] [v2liruge] api execute + 595
,09-09 13:36:04.836  6057  6987 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-09 13:36:04.836  6057  6987 I System.out: AsyncTask #1 calls detatch()
,09-09 13:36:04.856  6057  6987 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:36:04.866  6057  6987 I SA      : [OCP] update openData : PL
,09-09 13:36:04.866  6057  6987 I SA      : [TPMU] getNetworkMcc : 
,09-09 13:36:04.866  6057  6987 I SA      : [SCU] saveMccToPreferece Start
,09-09 13:36:04.866  6057  6987 I SA      : [SCU] RegionMCC : 260
,09-09 13:36:04.866  6057  6987 I SA      : [SSP] query invoked
,09-09 13:36:04.876  6057  6987 I SA      : [TPMU] GetMccFromDB : null
,09-09 13:36:04.876  6057  6987 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-09 13:36:04.876  6057  6987 I SA      : [SCU] saveMccToPreferece End
,09-09 13:36:04.876  6057  6987 I SA      : [RC New] executeRequest [v2liruge] end. 663
09-09 13:36:04.876  6057  6987 I SA      : [RC New] Execute end
,09-09 13:36:04.876  6057  6057 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:36:04.876  6057  6057 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:36:05.716   290   290 E SMD     : DCD OFF
,09-09 13:36:05.856  1013  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-09 13:36:06.026  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 13:36:06.026  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:36:06.026  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:36:06.026  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:06.026  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:36:06.026  6233  6282 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a69bc, channel: 6, state: LISTENING
,09-09 13:36:06.026  6233  6282 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@322a69bc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cffa58e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@bae7d45mSocket: android.net.LocalSocket@bd48c9a impl:android.net.LocalSocketImpl@2572f9cb fd:FileDescriptor[110]
,09-09 13:36:06.026  6233  6282 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@bd48c9a impl:android.net.LocalSocketImpl@2572f9cb fd:FileDescriptor[110]
,09-09 13:36:06.026  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:36:06.026  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:36:06.026  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:36:06.036  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:36:06.036  6233  6965 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a69bc, channel: 6, state: CLOSED
09-09 13:36:06.036  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:06.036  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:06.036  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:06.036  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:36:06.036  6233  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:06.036  6233  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:06.036  6233  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:36:06.036  6233  6282 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:36:06.036  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:36:06.036  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:36:06.036  2654  6793 D BtGatt.AdvertiseManager: message : 1
,09-09 13:36:06.036  2654  6793 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:36:06.036  2654  6793 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf5
,09-09 13:36:06.036  2654  6793 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:36:06.046  2654  2720 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:36:06.046  2654  2720 D BtGatt.GattService: Client app is not null!
,09-09 13:36:06.056  2654  2964 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:36:06.056  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:36:06.056  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:36:06.056  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:36:06.056  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:36:06.056  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:36:06.056  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:06.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:36:06.066  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:06.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.066  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:36:06.066  6233  6233 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:06.066  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:06.066  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:06.066  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:36:06.066  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:06.066  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:06.066  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:06.066  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.076  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cf5742 not in the list
09-09 13:36:06.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:06.076  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ea7353 not in the list
,09-09 13:36:06.076  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:06.076  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:06.076  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.076  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-09 13:36:06.076  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:06.076  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:06.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:06.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:06.076  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:06.076  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:06.086  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:06.086  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:06.086  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:36:06.096  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:36:06.096  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:06.096  2654  2663 D BtGatt.GattService: registerClient() - UUID=710510ee-ee2d-45fd-ac83-99e831ecdc97
,09-09 13:36:06.136  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=710510ee-ee2d-45fd-ac83-99e831ecdc97, clientIf=5
,09-09 13:36:06.136  6233  6247 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:06.136  2654  2664 D BtGatt.GattService: start scan with filters
,09-09 13:36:06.146  2654  6794 D BtGatt.ScanManager: handling starting scan
,09-09 13:36:06.146  2654  6794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4244aa5
,09-09 13:36:06.146  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:36:06.146  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 13:36:06.146  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:36:06.146  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 13:36:06.146  2654  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
09-09 13:36:06.146  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:06.146  2654  6794 D BtGatt.ScanManager: allow scan with filters
09-09 13:36:06.146  2654  6794 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 13:36:06.156  2654  6794 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
,09-09 13:36:06.156  2654  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:36:06.156  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.156  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:36:06.156  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:36:06.156  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:06.156  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:06.156  2654  6794 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:36:06.166  2654  6794 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:36:06.166  2654  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:36:06.166  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.166  2654  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:36:06.166  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.196  2654  6794 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 15
,09-09 13:36:06.356  6926  6926 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:36:06.356  6926  6926 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-09 13:36:06.436   257  1095 I SurfaceFlinger: id=15 Removed Uoast (8/9)
,09-09 13:36:06.436   257  1035 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
,09-09 13:36:06.446  1013  1025 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1013) eventTime = 155520
,09-09 13:36:06.446  1013  1025 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013 (0x0),
09-09 13:36:06.446  1013  1025 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1013, ws=WorkSource{10054}) (elapsedTime=3479)
,09-09 13:36:06.656  6233  6233 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:36:06.656  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:06.656  6233  6233 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:06.666  1013  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:06.676  2654  2654 D BtGatt.ScanManager: awakened up at time 155752
,09-09 13:36:06.676  2654  6794 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:06.686  2654  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-09 13:36:06.686  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.686  2654  2720 D BtGatt.GattService: current time is 155764249679
,09-09 13:36:06.686  2654  2720 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, -21, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -95, -120, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 78, -20, -96, 83, -39, -56, 1, -128, -66, -74, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39, 0, -56, 116, 70, 79, 58, 115, 1, -128, -75, -53, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17, 0]
,09-09 13:36:06.696  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
,09-09 13:36:06.696  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 13:36:06.706  2654  2720 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-09 13:36:06.706  2654  2720 D ScanRecord: parseFromBytes
09-09 13:36:06.706  2654  2720 D ScanRecord: first manudata for manu ID
,09-09 13:36:06.706  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 13:36:06.706  2654  2720 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:36:06.706  2654  2720 D ScanRecord: parseFromBytes
,09-09 13:36:06.706  2654  2720 D ScanRecord: first manudata for manu ID
,09-09 13:36:06.706  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,09-09 13:36:06.706  2654  2720 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39]
,09-09 13:36:06.716  2654  2720 D ScanRecord: parseFromBytes
,09-09 13:36:06.716  2654  2720 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17]
,09-09 13:36:06.716  2654  2720 D ScanRecord: parseFromBytes
,09-09 13:36:06.716  2654  2720 D BtGatt.GattService: result: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-95, mTimestampNanos=136169726762}
,09-09 13:36:06.716  2654  2720 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:06.716  2654  2720 D BtGatt.GattService: result: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=131219726762}
09-09 13:36:06.716  2654  2720 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:06.716  2654  2720 D BtGatt.GattService: result: ScanResult{mDevice=73:3A:4F:46:74:C8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -112, -25, -60, -2, -84, -17]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-75, mTimestampNanos=132819726762}
09-09 13:36:06.716  2654  2720 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:06.716  2654  2720 D BtGatt.GattService: result: ScanResult{mDevice=C8:D9:53:A0:EC:4E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, 8, -20, -87, 80, 118, 39]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=133869726762}
09-09 13:36:06.716  2654  2720 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:06.716  6233  6241 D ScanRecord: parseFromBytes
,09-09 13:36:06.716  6233  6241 D ScanRecord: first manudata for manu ID,
09-09 13:36:06.716  6233  6241 D ScanRecord: parseFromBytes,
09-09 13:36:06.716  6233  6241 D ScanRecord: first manudata for manu ID
09-09 13:36:06.716  6233  6241 D ScanRecord: parseFromBytes
09-09 13:36:06.716  6233  6241 D ScanRecord: parseFromBytes
,09-09 13:36:06.726  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-09 13:36:06.726  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-09 13:36:06.726  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
09-09 13:36:06.726  6233  6233 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 5], added - the peer count is 1
09-09 13:36:06.726  6233  6233 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 5], added - the peer count is 2
09-09 13:36:06.726  6233  6233 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 5], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,09-09 13:36:06.726  6233  6233 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 5], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,09-09 13:36:06.736  1013  3228 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-09 13:36:06.736  1013  3228 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:36:06.746  1013  3228 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:06.746  1013  3228 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:36:06.746  1013  3228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:36:06.766  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:06.766  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:06.776  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:06.786  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:07.146  1013  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:36:07.146  1013  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504],
,09-09 13:36:07.156  1173  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295,
09-09 13:36:07.156  1013  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:07.156  1173  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:07.166  3806  6291 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:07.176  3806  6291 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:07.186  2654  2654 D BtGatt.ScanManager: awakened up at time 156266,
09-09 13:36:07.186  1013  1093 V AlarmManager: waitForAlarm result :4,
,09-09 13:36:07.186  2654  6794 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 13:36:07.196  2654  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 13:36:07.196  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:07.236  1013  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:36:07.246  1013  1541 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4222, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 13:36:07.246  1013  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:36:07.246  1013  1541 D BatteryService: stay LED for charging
09-09 13:36:07.246  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:36:07.246  1013  1013 I MotionRecognitionService: Plugged
,09-09 13:36:07.246  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:36:07.246  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:36:07.246  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:36:07.256  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:36:07.256  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-09 13:36:07.266  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:36:07.266  2654  6795 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:36:07.276  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:36:07.276  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:36:07.276  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-09 13:36:07.656  1013  2771 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:36:07.696  1013  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:07.696  2654  2654 D BtGatt.ScanManager: awakened up at time 156776
,09-09 13:36:07.706  2654  6794 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:07.706  2654  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:07.706  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:08.206  1013  1093 V AlarmManager: waitForAlarm result :4,
,09-09 13:36:08.216  2654  2654 D BtGatt.ScanManager: awakened up at time 157292,
,09-09 13:36:08.216  2654  6794 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:08.226  2654  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:08.226  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:08.406  5813  5813 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-09 13:36:08.416  5813  7003 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-09 13:36:08.446  5813  7003 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-09 13:36:08.446  5813  7003 I ReactiveServiceManager: Supported : 1
,09-09 13:36:08.456  1013  2968 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-09 13:36:08.456  1013  2968 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:36:08.466  1013  2968 D QSEECOMAPI: : Loaded image: APP id = 12
,09-09 13:36:08.476  1013  2968 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-09 13:36:08.476  1013  2968 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12,
09-09 13:36:08.476  1013  2968 E terrier : handleString: Failed to handle string(-4)
,09-09 13:36:08.476  1013  2968 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
09-09 13:36:08.476  5813  7003 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-09 13:36:08.476  5813  7003 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E],
,09-09 13:36:08.486  5813  7003 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:36:08.486  5813  7003 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 13:36:08.486  5813  7003 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-09 13:36:08.486  5813  7003 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-09 13:36:08.716   290   290 E SMD     : DCD OFF,
,09-09 13:36:08.726  1013  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:08.726  2654  2654 D BtGatt.ScanManager: awakened up at time 157807
,09-09 13:36:08.736  2654  6794 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:08.736  2654  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:08.736  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:09.166  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:09.166  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:09.166  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:09.166  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cf5742 not in the list
09-09 13:36:09.166  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:09.166  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:09.166  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:09.166  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:09.166  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:09.166  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 13:36:09.176  2654  2962 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:36:09.176  2654  2663 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:36:09.176  2654  6794 D BtGatt.ScanManager: filter size is 1
,09-09 13:36:09.176  2654  6794 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 13:36:09.176  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:36:09.176  2654  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 13:36:09.176  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:09.176  2654  6794 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:36:09.176  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:36:09.186  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 13:36:09.186  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 13:36:09.186  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 13:36:09.186  2654  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 13:36:09.186  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:09.186  2654  6794 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:09.186  2654  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:09.186  2654  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:09.186  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:09.196  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:36:09.196  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:36:09.196  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:09.196  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:09.196  6233  6282 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-09 13:36:09.196  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:09.196  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:09.196  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:09.196  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ea7353 not in the list
09-09 13:36:09.196  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:09.196  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:09.196  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:09.196  6233  6282 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-09 13:36:09.196  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-09 13:36:09.206  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:09.206  6233  6282 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:09.206  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:09.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:09.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:36:09.206  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:36:09.206  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:36:09.206  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:36:09.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:36:09.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:09.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:09.206  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:09.206  6233  6282 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:09.216  6233  7004 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:36:09.216  6233  7004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:36:09.216  6233  7004 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
,09-09 13:36:09.216  6233  7004 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 13:36:09.216  6233  7004 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 13:36:09.216  6233  7004 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11c6d743
09-09 13:36:09.216  6233  7004 D BluetoothSocket: channel: 6
09-09 13:36:09.216  6233  7004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:36:09.216  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:09.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:09.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:36:09.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:36:09.226  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 7C F9 0E 37 96 AB
,09-09 13:36:09.226  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:36:09.226  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:36:09.226  6233  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:36:09.236  2654  2962 D BtGatt.GattService: registerClient() - UUID=5ec360b1-e8ad-49fe-98a6-2bbae5c1e35d
,09-09 13:36:09.276  2654  2720 D BtGatt.GattService: onClientRegistered() - UUID=5ec360b1-e8ad-49fe-98a6-2bbae5c1e35d, clientIf=5
,09-09 13:36:09.276  6233  6241 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
09-09 13:36:09.276  2654  6793 D BtGatt.AdvertiseManager: message : 0,
,09-09 13:36:09.296  2654  6793 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 8
,09-09 13:36:09.296  2654  6793 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:36:09.296  2654  6793 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:36:09.296  2654  6793 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:36:09.296  2654  6793 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:36:09.306  2654  2720 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:36:09.306  2654  6793 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:36:09.306  2654  2720 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:36:09.306  2654  6793 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:36:09.306  2654  6793 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:36:09.306  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:36:09.306  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:09.316  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:09.316  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:36:09.316  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:36:09.316  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:36:09.316  6233  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:36:09.316  6233  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:36:09.316  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:36:09.316  6233  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:09.316  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:09.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:09.826  6233  6233 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:36:09.826  6233  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:09.826  6233  6233 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:10.006  1013  2727 D SSRM:n  : SIOP:: AP = 330
,09-09 13:36:10.366  6926  6926 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:36:10.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:36:11.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:36:11.716   290   290 E SMD     : DCD OFF
,09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:12.326  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:36:12.326  6233  6282 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a4eaef9, channel: 6, state: LISTENING
09-09 13:36:12.326  6233  6282 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a4eaef9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11c6d743, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a668e3emSocket: android.net.LocalSocket@3ef5a49f impl:android.net.LocalSocketImpl@18b9b9ec fd:FileDescriptor[110]
09-09 13:36:12.326  6233  6282 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ef5a49f impl:android.net.LocalSocketImpl@18b9b9ec fd:FileDescriptor[110]
09-09 13:36:12.326  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:12.326  6233  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:36:12.326  6233  7004 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a4eaef9, channel: 6, state: CLOSED
09-09 13:36:12.326  6233  7004 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
09-09 13:36:12.326  6233  7004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:12.326  6233  7004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:36:12.326  6233  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:36:12.326  6233  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:36:12.326  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cf5742 not in the list
09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:12.326  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:36:12.326  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:36:12.326  6233  6282 D BluetoothLeScanner: could not find callback wrapper
09-09 13:36:12.326  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:36:12.326  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:36:12.326  2654  6793 D BtGatt.AdvertiseManager: message : 1
,09-09 13:36:12.326  2654  6793 D BtGatt.AdvertiseManager: stop advertise for client 5
09-09 13:36:12.326  2654  6793 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf5
,09-09 13:36:12.336  2654  6793 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:36:12.336  2654  2720 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-09 13:36:12.336  2654  2720 D BtGatt.GattService: Client app is not null!
09-09 13:36:12.336  2654  2961 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:36:12.346  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:36:12.346  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:36:12.346  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:36:12.346  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:36:12.346  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:36:12.346  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:12.346  6233  6282 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-09 13:36:12.346  6233  6282 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:12.346  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:12.346  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:12.346  6233  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:12.346  6233  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:12.346  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ea7353 not in the list,
09-09 13:36:12.356  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 13:36:12.356  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:12.356  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:12.356  6233  6282 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:12.356  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:12.356  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:12.356  6233  6282 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cf5742 not in the list
,09-09 13:36:12.356  6233  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:12.356  6233  6282 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ea7353 not in the list
09-09 13:36:12.356  6233  6282 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:12.356  6233  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:12.356  6233  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:12.356  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:12.356  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:12.356  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:12.356  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:12.356  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:12.356  6233  6282 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:36:12.366  6233  7009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1274, name: My test thread name)
,09-09 13:36:12.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:12.856  6233  6233 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:36:13.686   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:13.786  3806  4377 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,09-09 13:36:13.936  1013  3214 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:36:13.936  1013  3214 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:36:13.936  1013  3214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:13.936  1013  3214 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-09 13:36:13.936  1013  3214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:36:13.966  5966  5966 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:36:13.966  5966  5966 D PreloadUpdateManagerStateMachine: exit::IDLE
,09-09 13:36:13.966  5966  5966 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:36:13.966  5966  5966 D hcjo    : AutoUpdateTriggerManager:REQUEST2:requestInterval
,09-09 13:36:13.996  5966  5966 I Volley  : RestApi Request Add : 2307
,09-09 13:36:13.996  5966  5966 E File    : fail readDirectory() errno=2
,09-09 13:36:14.366  6233  6282 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1274
,09-09 13:36:14.366  6926  6926 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:36:14.366  6926  6926 I dhcpcd  : wlan0: no IPv6 Routers available
09-09 13:36:14.366  6233  6282 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1274, name: My test thread name)
,09-09 13:36:14.366  6233  7010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1275, name: My test thread name)
,09-09 13:36:14.376  6233  7010 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1275, thread name: My test thread name)
,09-09 13:36:14.376  6233  7010 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1275, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:36:14.376  6233  6282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:14.376  6233  7011 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1279, name: My test thread name)
,09-09 13:36:14.376  6233  7011 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1279, thread name: My test thread name): Test exception.
09-09 13:36:14.376  6233  7011 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1279, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:36:14.376  6233  6282 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
,09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: Proper state of WIFI is set when switched on
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-09 13:36:14.386  6233  7009 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1274, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Proper state of WIFI is set when switched on
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:228)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunn,er: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:36:14.386  6233  6282 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-09 13:36:14.386  6233  6282 I jxcore-log: Total number of executed tests:  82
09-09 13:36:14.386  6233  6282 I jxcore-log: 
,09-09 13:36:14.386  6233  6282 I jxcore-log: Number of passed tests:  81
09-09 13:36:14.386  6233  6282 I jxcore-log: 
,09-09 13:36:14.386  6233  6282 I jxcore-log: Number of failed tests:  1
09-09 13:36:14.386  6233  6282 I jxcore-log: 
,09-09 13:36:14.396  6233  6282 I jxcore-log: Number of ignored tests:  0
09-09 13:36:14.396  6233  6282 I jxcore-log: 
,09-09 13:36:14.396  6233  6282 I jxcore-log: Total duration:  23703
09-09 13:36:14.396  6233  6282 I jxcore-log: 
,09-09 13:36:14.396  6233  6282 I jxcore-log: Failed to execute UT.
09-09 13:36:14.396  6233  6282 I jxcore-log: 
,09-09 13:36:14.396  6233  6282 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-09 13:36:14.396  6233  6282 I jxcore-log: 
,09-09 13:36:14.406  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.406  6233  6282 I jxcore-log: 
09-09 13:36:14.406  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.406  6233  6282 I jxcore-log: 
09-09 13:36:14.406  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.406  6233  6282 I jxcore-log: 
09-09 13:36:14.406  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.406  6233  6282 I jxcore-log: 
09-09 13:36:14.406  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.406  6233  6282 I jxcore-log: 
09-09 13:36:14.416  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.416  6233  6282 I jxcore-log: 
09-09 13:36:14.416  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.416  6233  6282 I jxcore-log: 
09-09 13:36:14.416  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.416  6233  6282 I jxcore-log: 
09-09 13:36:14.416  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:14.416  6233  6282 I jxcore-log: 
09-09 13:36:14.416  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:14.416  6233  6282 I jxcore-log: 
,09-09 13:36:14.426  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:14.426  6233  6282 I jxcore-log: 
,09-09 13:36:14.426  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:14.426  6233  6282 I jxcore-log: 
,09-09 13:36:14.426  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.426  6233  6282 I jxcore-log: 
,09-09 13:36:14.426  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.426  6233  6282 I jxcore-log: 
,09-09 13:36:14.426  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.426  6233  6282 I jxcore-log: 
,09-09 13:36:14.436  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.436  6233  6282 I jxcore-log: 
,09-09 13:36:14.436  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.436  6233  6282 I jxcore-log: 
,09-09 13:36:14.436  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.436  6233  6282 I jxcore-log: 
,09-09 13:36:14.436  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.436  6233  6282 I jxcore-log: 
,09-09 13:36:14.436  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.436  6233  6282 I jxcore-log: 
,09-09 13:36:14.446  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.446  6233  6282 I jxcore-log: 
,09-09 13:36:14.446  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.446  6233  6282 I jxcore-log: 
,09-09 13:36:14.446  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.446  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a4eaef9, channel: 6, state: CLOSED
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a69bc, channel: 6, state: CLOSED
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.456  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:36:14.456  6233  6282 I jxcore-log: 
,09-09 13:36:14.466  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:36:14.466  6233  6282 I jxcore-log: 
,09-09 13:36:14.466  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34f0782e, channel: 6, state: CLOSED
09-09 13:36:14.466  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cd514ea, channel: -1, state: CLOSED
,09-09 13:36:14.466  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:36:14.466  6233  6282 I jxcore-log: 
,09-09 13:36:14.466  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26d03e71, channel: 6, state: CLOSED
09-09 13:36:14.466  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:14.466  6233  6282 I jxcore-log: 
09-09 13:36:14.466  6233  6282 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:14.466  6233  6282 I jxcore-log: 
,09-09 13:36:14.466  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3abf9500, channel: 6, state: CLOSED
,09-09 13:36:14.466  6233  6243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e6d90e8, channel: 6, state: CLOSED
,09-09 13:36:14.466  5966  7013 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-09 13:36:14.466  5966  7013 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:14.466  5966  7013 I System.out: (HTTPLog)-Static: isShipBuild true
,09-09 13:36:14.476  5966  7013 I System.out: (HTTPLog)-Thread-1001-233183872: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
09-09 13:36:14.476  5966  7013 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:14.476   277   978 D EnterpriseController: uids 10010,
09-09 13:36:14.476   277   978 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:36:14.476   277   978 D Netd    : getNetworkForDns: using netid 504 for uid 10010
,09-09 13:36:14.516  5966  7013 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:36:14.516  5966  7013 I qtaguid : Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5966, getuid(): 10010
,09-09 13:36:14.616  5966  7013 I qtaguid : Untagging socket 26
,09-09 13:36:14.616  5966  5966 D hcjo    : AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,09-09 13:36:14.626  5966  5966 D hcjo    : AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,09-09 13:36:14.636  5966  5966 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,09-09 13:36:14.636  5966  5966 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:36:14.636  5966  5966 D PreloadUpdateManagerStateMachine: entry::REQ_UPDATE_CHECK
,09-09 13:36:14.646  5966  5966 I Volley  : RestApi Request Add : 2315,
09-09 13:36:14.646  5966  7014 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:14.646  5966  7014 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-09 13:36:14.646  5966  7014 I qtaguid : Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5966, getuid(): 10010
,09-09 13:36:14.666  7017  7017 D AndroidRuntime: ,
09-09 13:36:14.666  7017  7017 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:36:14.666  7017  7017 D AndroidRuntime: CheckJNI is OFF,
09-09 13:36:14.666  7017  7017 D AndroidRuntime: readGMSProperty: start,
09-09 13:36:14.666  7017  7017 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:36:14.666  7017  7017 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:36:14.666  7017  7017 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:36:14.666  7017  7017 D AndroidRuntime: readGMSProperty: end,
09-09 13:36:14.666  7017  7017 D AndroidRuntime: addProductProperty: start
,09-09 13:36:14.686   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-09 13:36:14.726   290   290 E SMD     : DCD OFF,
,09-09 13:36:14.796  7017  7017 E AffinityControl: AffinityControl: registerfunction enter
,09-09 13:36:14.826  7017  7017 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-09 13:36:14.836  1013  3214 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 13:36:14.836  1013  3214 D PackageManager: START PACKAGE DELETE: observer{517305407}
09-09 13:36:14.836  1013  3214 D PackageManager: pkg{<packageName>}
09-09 13:36:14.836  1013  3214 D PackageManager: user{0}
09-09 13:36:14.836  1013  3214 D PackageManager: caller{2000}
09-09 13:36:14.836  1013  3214 D PackageManager: flags{2}
09-09 13:36:14.836  1013  3214 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 13:36:14.836  1013  3214 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
09-09 13:36:14.836  1013  3214 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:36:14.836  1013  3214 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-09 13:36:14.836  1013  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-09 13:36:14.836  1013  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 13:36:14.836  1013  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 13:36:14.836  1013  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 13:36:14.836  1013  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 13:36:14.836  1013  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-09 13:36:14.846  1013  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-09 13:36:14.846  1013  1039 I ActivityManager: Killing 6233:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 13:36:14.856  1013  1039 I ActivityManager:   Force finishing activity ActivityRecord{2c610712 u0 com.test.thalitest/.MainActivity t128},
,09-09 13:36:14.856  1013  1039 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:36:14.946  1013  1075 I WindowState: WIN DEATH: Window{20d97672 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:36:14.946   257  1035 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,09-09 13:36:14.946   257  1035 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,09-09 13:36:14.956  1013  1075 D InputDispatcher: Focus left window: 6233,
,09-09 13:36:14.966  1013  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:36:14.966  1013  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:36:15.006  1013  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-09 13:36:15.006  1013  1054 I ActivityManager:   Force finishing activity ActivityRecord{2c610712 u0 com.test.thalitest/.MainActivity t128 f}
,09-09 13:36:15.006  1013  1054 W ActivityManager: Duplicate finish request for ActivityRecord{2c610712 u0 com.test.thalitest/.MainActivity t128 f}
,09-09 13:36:15.026  1013  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 13:36:15.036  1013  1039 D InputDispatcher: Focused application released
,09-09 13:36:15.036  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-09 13:36:15.046  5692  5692 I art     : Explicit concurrent mark sweep GC freed 2328(137KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 957us total 34.256ms
,09-09 13:36:15.056  4790  4790 I art     : Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 803us total 26.874ms
,09-09 13:36:15.066  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 13:36:15.066  1013  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:36:15.076  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 13:36:15.086  1891  1891 E SamsungIME: mOCRHelper is null
,09-09 13:36:15.086  5966  7014 I qtaguid : Untagging socket 28
,09-09 13:36:15.086  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-09 13:36:15.096  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-09 13:36:15.106  1907  2121 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:36:15.106  3601  3601 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:36:15 GMT+02:00 2016
,09-09 13:36:15.106  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-09 13:36:15.126  5483  5483 I art     : Explicit concurrent mark sweep GC freed 662(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 760us total 94.171ms
,09-09 13:36:15.126  1013  1638 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:36:15.126  1013  1638 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:36:15.136  1013  1638 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:15.136  1013  1638 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:15.136  1013  1638 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:36:15.136  5966  5966 D PreloadUpdateManagerStateMachine: execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
09-09 13:36:15.136  5966  5966 D PreloadUpdateManagerStateMachine: exit::REQ_UPDATE_CHECK
09-09 13:36:15.136  5966  5966 D PreloadUpdateManagerStateMachine: entry::NOTIFY_NOTIFICATION
09-09 13:36:15.136  5966  5966 D PreloadUpdateManagerStateMachine: exit::NOTIFY_NOTIFICATION
09-09 13:36:15.136  5966  5966 D PreloadUpdateManagerStateMachine: entry::FINISH
,09-09 13:36:15.136  1013  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
,09-09 13:36:15.136  1013  1123 V NetworkStats: performPollLocked(flags=0x3)
,09-09 13:36:15.146  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:15.146  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:36:15.146  1013  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:15.146  1013  1123 V NetworkStats: performPollLocked() took 8ms
,09-09 13:36:15.146  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:15.156  3601  3601 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:36:15.156  3142  3142 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-09 13:36:15.156  1013  1360 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,09-09 13:36:15.156  1013  1360 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 13:36:15.166  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:36:15.166  1013  1360 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 13:36:15.166  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.166  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.166  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.166  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.176  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-09 13:36:15.176  7031  7031 E Zygote  : MountEmulatedStorage()
09-09 13:36:15.176  7031  7031 E Zygote  : v2
09-09 13:36:15.176  7031  7031 I libpersona: KNOX_SDCARD checking this for 10094
,09-09 13:36:15.176  7031  7031 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.186  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-09 13:36:15.186  3806  3806 I art     : Explicit concurrent mark sweep GC freed 4529(172KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 32.372ms total 172.895ms
09-09 13:36:15.186  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:36:15.186  3601  3601 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
09-09 13:36:15.186  1013  1360 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7031 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-09 13:36:15.196  1441  1441 D RegisteredServicesCache: empty dynamic service
09-09 13:36:15.196  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.206  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 13:36:15.206  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 13:36:15.206  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:36:15.206  5966  5966 D PreloadUpdateManagerStateMachine: exit::FINISH
09-09 13:36:15.206  5966  5966 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:36:15.216  3601  3601 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:36:15.216  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:15.216  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:15.226  1013  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-09 13:36:15.226  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.226  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.226  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.226  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.236  3601  3601 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:36:15.236  7046  7046 E Zygote  : MountEmulatedStorage()
09-09 13:36:15.236  7046  7046 E Zygote  : v2
09-09 13:36:15.236  7046  7046 I libpersona: KNOX_SDCARD checking this for 10044
09-09 13:36:15.236  7046  7046 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:15.236  7046  7046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.246  7046  7046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 13:36:15.246  1013  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7046 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-09 13:36:15.246  7046  7046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.246  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:15.246  1013  2968 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-09 13:36:15.246  1013  2968 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-09 13:36:15.246  7031  7031 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.246  3601  7030 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:36:15.256  1013  1013 I art     : Explicit concurrent mark sweep GC freed 32807(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 28MB/42MB, paused 5.160ms total 243.086ms
,09-09 13:36:15.266  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 13:36:15.266  1013  1054 I art     : WaitForGcToComplete blocked for 139.693ms for cause Explicit
,09-09 13:36:15.276  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-09 13:36:15.276  1013  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-09 13:36:15.276  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.276  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.276  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.276  1013  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.286  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-09 13:36:15.286  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-09 13:36:15.286  3601  7030 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
09-09 13:36:15.286  3142  3142 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-09 13:36:15.286  3142  3142 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-09 13:36:15.296  7062  7062 E Zygote  : MountEmulatedStorage(),
09-09 13:36:15.296  7062  7062 E Zygote  : v2
09-09 13:36:15.296  7062  7062 I libpersona: KNOX_SDCARD checking this for 10149
09-09 13:36:15.296  7062  7062 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.296  7062  7062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.296  1013  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7062 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-09 13:36:15.296  7046  7046 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:15.296  7046  7046 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.296  7062  7062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:36:15.296  3601  7030 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 13:36:15.306  7062  7062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.306  1013  1026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 13:36:15.316  1013  1026 D SecContentProvider2: mCursor = null
,09-09 13:36:15.316  1013  2967 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:36:15.316  3601  7030 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 13:36:15.316  1013  2967 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 13:36:15.316  1013  2967 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 13:36:15.316  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-09 13:36:15.326   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-09 13:36:15.326  1013  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 13:36:15.326  7062  7062 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:15.336  7062  7062 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.336  1013  1638 D InputDispatcher: Focus entered window: 3142
,09-09 13:36:15.336  3142  3142 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:36:15.336  1013  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:36:15.336  1013  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:36:15.346  4790  7061 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-09 13:36:15.346  3142  3142 V ActivityThread: updateVisibility : ActivityRecord{e20c799 token=android.os.BinderProxy@175ca624 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-09 13:36:15.356  1013  1025 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:36:15.356  1013  1025 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6233 uid 10155
,09-09 13:36:15.356  1013  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-09 13:36:15.356  1013  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-09 13:36:15.356  1013  1038 W TextServicesManagerService: no available spell checker services found
,09-09 13:36:15.366  1891  1891 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 13:36:15.376  3142  3142 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@175ca624 time:164454
,09-09 13:36:15.376  1013  7078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:36:15.396  4790  4790 I art     : Explicit concurrent mark sweep GC freed 570(33KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 1.002ms total 35.753ms
,09-09 13:36:15.406  7031  7031 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 13:36:15.406  7031  7031 D elm:15183: ELMEngine.ELMEngine( context ).
,09-09 13:36:15.416  7031  7031 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-09 13:36:15.416  1013  1044 W ActivityManager: mDVFSHelper.release()
09-09 13:36:15.416  1013  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8c9fdce u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:164495
,09-09 13:36:15.416  7062  7062 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-09 13:36:15.416  7062  7062 D ThemeInfoUtil: isCurrentFestival = false
,09-09 13:36:15.416  1013  2968 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-09 13:36:15.426  5993  6003 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-09 13:36:15.426  5993  6003 D BadgeProvider: sendNotify, [notify] : null
09-09 13:36:15.426  5993  6003 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-09 13:36:15.426  5993  6003 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:36:15.426  5993  6003 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:36:15.426  7046  7046 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:36:15.426  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.426  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.426  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.426  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.426  3601  7030 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 13:36:15.446  7080  7080 E Zygote  : MountEmulatedStorage(),
,09-09 13:36:15.446  7080  7080 E Zygote  : v2
09-09 13:36:15.446  7080  7080 I libpersona: KNOX_SDCARD checking this for 10152
,09-09 13:36:15.446  7080  7080 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.446  3601  7030 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 13:36:15.446  7080  7080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.446  3601  7030 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 13:36:15.446  7080  7080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:15.446  7080  7080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.456  1013  2968 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7080 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,09-09 13:36:15.476  1013  3230 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-09 13:36:15.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.476  1013  3230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.476  3601  3601 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 13:36:15.486  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:15.486  7080  7080 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.486  7095  7095 E Zygote  : MountEmulatedStorage()
09-09 13:36:15.486  7095  7095 E Zygote  : v2
09-09 13:36:15.486  7095  7095 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:36:15.486  7095  7095 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.486  1013  3230 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7095 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 13:36:15.486  7095  7095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.486  1013  3230 I ActivityManager: Killing 5483:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-09 13:36:15.496  7095  7095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:15.496  7095  7095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.496  1013  1026 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 13:36:15.496  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 13:36:15.496  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.506  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:15.506  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:15.506  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-09 13:36:15.506   312   312 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 21.692ms
,09-09 13:36:15.516  1013  1013 D RCPManagerService: PackageReceiver onReceive()
09-09 13:36:15.516  1013  1013 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 13:36:15.516  1013  1013 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 13:36:15.516  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.516  1013  1013 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-09 13:36:15.516  1013  1013 D OTPFW   : OtpDbHelper::getInstance New instance created
09-09 13:36:15.516  7031  7031 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 13:36:15.526  7095  7095 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:15.526  7095  7095 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:15.526  1013  1013 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-09 13:36:15.526   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.162ms
,09-09 13:36:15.536  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.536  1013  1013 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
09-09 13:36:15.536  1013  1013 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 13:36:15.536  1013  1013 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-09 13:36:15.536  1013  1013 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:36:15.536  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 13:36:15.536  1013  1013 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:36:15.536  1013  1013 V EnterpriseBillingPolicy: uID is 10155
09-09 13:36:15.536  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:36:15.536  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 13:36:15.536  7031  7031 D elm:15183: ElmAgentService : onCreate()
09-09 13:36:15.536  7031  7110 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-09 13:36:15.536  7031  7110 D elm:15183: MainReceiver.listeningToPackageRemoved()
09-09 13:36:15.536  7031  7110 D elm:15183: MDMBridge.getInstance()
09-09 13:36:15.536  7031  7110 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:36:15.546   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.047ms
09-09 13:36:15.546  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:36:15.546  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:36:15.546  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:36:15.546  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 13:36:15.546  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:36:15.546  7031  7110 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:36:15.556  3303  3303 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-09 13:36:15.556  3303  3303 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 13:36:15.556  3303  3303 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-09 13:36:15.556  3303  3303 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-09 13:36:15.556  3303  3303 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 13:36:15.556  3303  3303 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 13:36:15.556  3303  3303 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 13:36:15.556  3303  3303 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:15.556  3303  3303 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:36:15.556  3303  3303 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:36:15.556  3303  3303 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:15.556  3303  3303 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:15.556  3303  3303 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:36:15.556  3303  3303 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 13:36:15.566  1013  1013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:36:15.566  1013  2727 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicy: uID is 10155
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 13:36:15.566  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:36:15.576  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:36:15.576  1013  1013 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-09 13:36:15.576  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 13:36:15.576  1013  1013 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-09 13:36:15.576  1173  1173 D PanelView: There is/are notification(s) 
,09-09 13:36:15.586  7031  7031 D elm:15183: ElmAgentService : onDestroy().
,09-09 13:36:15.586  1013  1159 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-09 13:36:15.586  1013  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-09 13:36:15.586  7080  7080 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-09 13:36:15.586  1013  1638 I ActivityManager: Killing 6166:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-09 13:36:15.606  1013  1360 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,09-09 13:36:15.606  1013  1360 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-09 13:36:15.606  7095  7095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-09 13:36:15.606  1013  1360 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:15.606  1013  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:15.606  1013  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-09 13:36:15.616  1013  3228 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:36:15.626  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-09 13:36:15.626  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 13:36:15.626  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:15.626  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:15.626  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 13:36:15.636  1013  1638 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-09 13:36:15.636  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.636  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.636  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.636  1013  1638 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.646  7116  7116 E Zygote  : MountEmulatedStorage(),
09-09 13:36:15.646  7116  7116 I libpersona: KNOX_SDCARD checking this for 10156
09-09 13:36:15.646  7116  7116 E Zygote  : v2
09-09 13:36:15.646  7116  7116 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:15.646  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:36:15.656  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:36:15.656  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:36:15.656  1013  1638 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7116 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,09-09 13:36:15.666  1013  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-09 13:36:15.676  1173  1173 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-09 13:36:15.676  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.676  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.676  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.676  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.676  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:36:15.676  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:36:15.676  1013  1054 I art     : Explicit concurrent mark sweep GC freed 13871(793KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 3.698ms total 409.153ms
09-09 13:36:15.676  1173  1173 D PanelView: There is/are notification(s) 
09-09 13:36:15.676  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-09 13:36:15.686  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:36:15.686  1173  1173 D PanelView: There is/are notification(s) 
09-09 13:36:15.686  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:15.686  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-09 13:36:15.686  7116  7116 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.686  5813  5813 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 13:36:15.686  5813  5813 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:36:15.686  5813  5813 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:36:15.686  5813  5813 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-09 13:36:15.706  7132  7132 E Zygote  : MountEmulatedStorage(),
09-09 13:36:15.706  7132  7132 E Zygote  : v2
09-09 13:36:15.706  7132  7132 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:36:15.706  7132  7132 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:15.706  7132  7132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:36:15.706  7132  7132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:36:15.716  1013  1317 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 13:36:15.716  7132  7132 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:36:15.716  1013  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 13:36:15.726  1013  1317 I ActivityManager: Killing 5756:com.android.defcontainer/u0a4 (adj 15): empty #31
,09-09 13:36:15.726  1013  1317 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-09 13:36:15.736  7132  7132 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:15.736  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.736  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.736  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.736  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.736  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:15.746  7132  7132 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.746  7116  7116 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-09 13:36:15.746  7116  7116 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-09 13:36:15.746  7144  7144 E Zygote  : MountEmulatedStorage()
09-09 13:36:15.746  7144  7144 E Zygote  : v2
09-09 13:36:15.746  7144  7144 I libpersona: KNOX_SDCARD checking this for 10032
09-09 13:36:15.746  7144  7144 I libpersona: KNOX_SDCARD not a persona,
09-09 13:36:15.756  1013  1317 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7144 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-09 13:36:15.756  7144  7144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.756  1173  1173 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-09 13:36:15.756  1013  1317 I ActivityManager: Killing 5612:com.android.vending/u0a28 (adj 15): empty #31
,09-09 13:36:15.756  7116  7116 I TapandpayWidget:Utils: Clear T&P info.
09-09 13:36:15.756  7144  7144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:15.756  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:15.756  7144  7144 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.776  1013  1054 D PackageManager: delete codoeFile: 
,09-09 13:36:15.776  7046  7046 D NearbySource: Nearby Source Create!
,09-09 13:36:15.776  7132  7132 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:15.776  7046  7046 D NearbyContext: Nearby Context Create!
,09-09 13:36:15.786  7116  7116 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-09 13:36:15.786  1013  2968 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,09-09 13:36:15.786  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.786  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.786  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.786  1013  2968 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.786  1013  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
09-09 13:36:15.786  1013  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-09 13:36:15.796  7144  7144 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:15.796  7144  7144 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.796  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-09 13:36:15.796  7132  7132 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 13:36:15.796  1013  1054 D PackageManager: result of delete: 1{517305407}
,09-09 13:36:15.806  7163  7163 E Zygote  : MountEmulatedStorage(),
09-09 13:36:15.806  7163  7163 E Zygote  : v2
09-09 13:36:15.806  7163  7163 I libpersona: KNOX_SDCARD checking this for 10160
09-09 13:36:15.806  7163  7163 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.806  7163  7163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:36:15.806  1013  2968 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7163 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,09-09 13:36:15.816  1013  1356 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 13:36:15.816  1013  1356 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-09 13:36:15.816  7163  7163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:15.816  7163  7163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:15.816  1013  2968 I ActivityManager: Killing 6305:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,09-09 13:36:15.826  1013  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:36:15.826  1013  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:15.826  1013  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:36:15.826  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:15.826  7017  7017 D AndroidRuntime: Shutting down VM
,09-09 13:36:15.836   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 13:36:15.836   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:15.846  7046  7046 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-09 13:36:15.846  7046  7046 D SLinkSource: Samsung link source created
,09-09 13:36:15.846  7163  7163 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:15.846  7163  7163 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:15.846  1013  1360 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-09 13:36:15.846  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.846  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.846  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.846  1013  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.856  1013  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 13:36:15.856  1013  1054 D PackageManager: userId{-1}
09-09 13:36:15.856  1013  1054 D PackageManager: andCode{true}
,09-09 13:36:15.866  7178  7178 E Zygote  : MountEmulatedStorage()
,09-09 13:36:15.866  7178  7178 E Zygote  : v2
09-09 13:36:15.866  7178  7178 I libpersona: KNOX_SDCARD checking this for 10091
09-09 13:36:15.866  7178  7178 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.866  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:36:15.866  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:15.866  1013  1360 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7178 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:15.866  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:15.866  1013  1360 I ActivityManager: Killing 6748:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,09-09 13:36:15.866  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:36:15.866  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:15.876  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.876  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:36:15.886  1013  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 13:36:15.886  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.886  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.886  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.886  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.886  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.886  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.886  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:36:15.896  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:15.896  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:36:15.896  1013  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-09 13:36:15.906  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:15.906  7178  7178 D ActivityThread: Added TimaKeyStore provider,
,09-09 13:36:15.906  7193  7193 E Zygote  : MountEmulatedStorage()
09-09 13:36:15.906  7193  7193 E Zygote  : v2
09-09 13:36:15.906  7193  7193 I libpersona: KNOX_SDCARD checking this for 10004
09-09 13:36:15.906  7193  7193 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:15.906  7163  7163 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:36:15.906  7193  7193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.906  1013  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7193 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 13:36:15.916  7193  7193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:15.916  7193  7193 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:36:15.916  1013  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 13:36:15.916  1013  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 13:36:15.936  7193  7193 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:15.936  7193  7193 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:15.946  7163  7163 D [0]UMC:UMCContentProvider: @onCreate
,09-09 13:36:15.956  4790  4790 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-09 13:36:15.966  7163  7163 D [0]UMC:Core: onCreate(): 
,09-09 13:36:15.966  7163  7163 D [0]UMC:Core: @isManagedProfileUser
,09-09 13:36:15.966  7163  7163 D [0]UMC:Core: userId: 0
,09-09 13:36:15.966  1013  1540 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 13:36:15.966  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.966  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.966  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:15.966  1013  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:15.976  1013  1075 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:36:15.976  7144  7204 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-09 13:36:15.986  7212  7212 E Zygote  : MountEmulatedStorage()
09-09 13:36:15.986  7212  7212 E Zygote  : v2
09-09 13:36:15.986  7212  7212 I libpersona: KNOX_SDCARD checking this for 10035
09-09 13:36:15.986  7212  7212 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:15.986  7212  7212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:15.986  7163  7163 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
09-09 13:36:15.986  7163  7163 D [0]UMC:Core: userInfo.isManagedProfile() : false
,09-09 13:36:15.986  7212  7212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 13:36:15.986  1013  1540 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7212 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:15.986  7212  7212 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 13:36:15.986  1013  1540 I ActivityManager: Killing 6766:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,09-09 13:36:15.996  7046  7207 D ContactProvider: getAllContactInfoList Start
,09-09 13:36:15.996  1013  1541 I ActivityManager: Killing 1607:com.google.process.gapps/u0a12 (adj 15): empty #31
,09-09 13:36:16.006  5993  6003 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-09 13:36:16.006  5993  6003 D BadgeProvider: sendNotify, [notify] : null
,09-09 13:36:16.006  5993  6003 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-09 13:36:16.006  5993  6003 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:36:16.006  5993  6003 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:36:16.006  1013  1638 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:36:16.016  7046  7046 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-09 13:36:16.016  7212  7212 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.016  7212  7212 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.036  7144  7204 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-09 13:36:16.036  7144  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:16.036  7144  7204 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:36:16.036  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.036  7144  7204 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 13:36:16.036  7017  7017 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 13:36:16.036  7144  7204 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 13:36:16.046  7163  7163 D [0]UMC:DeviceInfo: USA==US==
,09-09 13:36:16.056  7046  7207 D ContactProvider: getAllContactInfoList End
,09-09 13:36:16.056  7046  7207 I syncContacts: thread: 1148, sync time = 109
,09-09 13:36:16.056  7144  7204 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 13:36:16.056  7144  7204 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-09 13:36:16.066  7144  7204 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:36:16.066  7144  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:16.066  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.066  7144  7204 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:36:16.066  7178  7178 E PhotosPlugin: Loading PhotosPlugin
,09-09 13:36:16.066  1013  1317 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-09 13:36:16.066  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.066  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.066  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.066  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.086  7228  7228 E Zygote  : MountEmulatedStorage()
,09-09 13:36:16.086  7228  7228 E Zygote  : v2
09-09 13:36:16.086  7228  7228 I libpersona: KNOX_SDCARD checking this for 10046
09-09 13:36:16.086  7228  7228 I libpersona: KNOX_SDCARD not a persona,
09-09 13:36:16.086  1013  1317 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7228 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-09 13:36:16.086  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:36:16.086  7144  7204 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:36:16.086  7144  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:16.086  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:36:16.096  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:36:16.096  1013  1317 I ActivityManager: Killing 6392:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,09-09 13:36:16.096  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.106  1013  1317 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,09-09 13:36:16.106  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.106  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.106  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.106  1013  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.106  7212  7235 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 13:36:16.106  7212  7235 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 13:36:16.116  7245  7245 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.116  7245  7245 E Zygote  : v2
09-09 13:36:16.116  7245  7245 I libpersona: KNOX_SDCARD checking this for 10038
09-09 13:36:16.116  7245  7245 I libpersona: KNOX_SDCARD not a persona,
,09-09 13:36:16.126  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:36:16.126  7144  7204 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:36:16.126  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.126  7144  7204 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-09 13:36:16.126  1013  1317 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7245 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,09-09 13:36:16.126  1013  1317 I ActivityManager: Killing 6424:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,09-09 13:36:16.126  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 13:36:16.126  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 13:36:16.126  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.126  7228  7228 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:36:16.156  7144  7204 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:36:16.166  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:16.166  7245  7245 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:16.166  7212  7235 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:36:16.166  7212  7235 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:36:16.166  7212  7235 D SPPClientService: ============PushLog. stop!
,09-09 13:36:16.166  7212  7212 W FileUtils: Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-09 13:36:16.176  7228  7228 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-09 13:36:16.176  7228  7228 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:16.176  7228  7228 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:36:16.176  7228  7228 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.176  7163  7163 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
09-09 13:36:16.176  7228  7228 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 13:36:16.176  7228  7228 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 13:36:16.186  7163  7163 D [0]UMC:AdminManager: init - start
,09-09 13:36:16.186  1477  1477 D Launcher.Model: reloadBadges entered.
09-09 13:36:16.186  1477  1477 D Launcher.Model: reloadBadges entered.
,09-09 13:36:16.186  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.186  7144  7204 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:36:16.186  7144  7204 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:36:16.206  7163  7163 D [0]UMC:AdminManager: loadAdmins
,09-09 13:36:16.216  7245  7245 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.216  7245  7245 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:36:16.216  7144  7204 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 13:36:16.216  7144  7204 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:36:16.216  7144  7204 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:36:16.216  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.216  7144  7204 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:36:16.226  7163  7163 D [0]UMC:AdminManager: init - end
,09-09 13:36:16.226  7163  7163 D GSLBManager: migrateStoredUrlFromOldPref
,09-09 13:36:16.226  7144  7204 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:36:16.226  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:36:16.226  7163  7163 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,09-09 13:36:16.226  7144  7204 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:36:16.226  7144  7204 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 13:36:16.226  7163  7163 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,09-09 13:36:16.236  7163  7163 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,09-09 13:36:16.236  7163  7163 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
09-09 13:36:16.236  7163  7163 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
09-09 13:36:16.236  7163  7163 D [0]UMC:UMCAdmin: isContainer : 0
,09-09 13:36:16.236  1013  1540 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,09-09 13:36:16.236  7163  7163 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,09-09 13:36:16.236  7163  7163 D [0]UMC:UMCAdmin: isContainer : 0
,09-09 13:36:16.246  7163  7163 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,09-09 13:36:16.246  7144  7204 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:36:16.246  7144  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:16.246  7144  7204 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:36:16.246  7144  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:36:16.246  7144  7204 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:36:16.256  1013  2968 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,09-09 13:36:16.256  1013  2968 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,09-09 13:36:16.256  1013  2968 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:16.256  1013  2968 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:16.256  1013  2968 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,09-09 13:36:16.256  7163  7163 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,09-09 13:36:16.256  7163  7163 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
09-09 13:36:16.256  7163  7163 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
09-09 13:36:16.256  7163  7163 D [0]UMC:CoreReceiver: Intent Replacing : false

```
