#### Test 832688932759c28_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 16:52:58.979  1823  4374 I art     : Explicit concurrent mark sweep GC freed 22818(1526KB) AllocSpace objects, 17(272KB) LOS objects, 51% free, 29MB/61MB, paused 2.234ms total 141.197ms
08-30 16:52:59.004  4573  6533 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 308 ms] updated apps [took 308 ms] 
08-30 16:52:59.029  6534  6534 D DocsApplication: Installing DEX configuration.
08-30 16:52:59.048  6534  6534 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 16:52:59.052  6534  6534 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{6be1704 com.google.android.apps.docs}
08-30 16:52:59.069  6534  6534 D TAG     : onCreate()
08-30 16:52:59.089  6534  6534 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 16:52:59.119   309   309 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-30 16:52:59.119   309   309 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
08-30 16:52:59.119   309   309 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 16:52:59.119   309   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-30 16:52:59.188   309   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
08-30 16:52:59.188   309   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-30 16:52:59.188   309   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 22
08-30 16:52:59.188   309   905 I rmt_storage: 
,08-30 16:52:59.191   309   309 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-30 16:52:59.191   903   917 E Diag_Lib: [IMS_FATAL]| 3347 | 917 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-30 16:53:00.091  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 16:53:00.091  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 16:53:00.091  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 16:53:00.093  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
08-30 16:53:00.095  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 16:53:00.095  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-30 16:53:00.096  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-30 16:53:00.096  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 16:53:00.098  1823  4706 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-30 16:53:00.119  1823  4706 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 16:53:00.153  1823  4706 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 16:53:00.179  6565  6565 D AndroidRuntime: 
08-30 16:53:00.179  6565  6565 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 16:53:00.182  6565  6565 D AndroidRuntime: CheckJNI is OFF
08-30 16:53:00.310  6565  6565 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 16:53:00.315  1045  2333 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 16:53:00.340  1953  3910 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 16:53:00.345  1045  2333 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 16:53:00.347  1045  2333 D ActivityManager: setTaskToReturnTo : TaskRecord{3bb4a54 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 16:53:00.347  1045  2333 D ActivityManager: setTaskToReturnTo : TaskRecord{3bb4a54 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 16:53:00.348  1045  2333 D WindowStateEx: AppWindowTokenEx init.. 
08-30 16:53:00.349   348   370 E GBMv2   : DFP En is all cleared set to be enabled
08-30 16:53:00.419  1045  2333 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6600 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 16:53:00.423  6565  6565 D AndroidRuntime: Shutting down VM
08-30 16:53:00.465  1953  1968 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 16:53:00.466  1953  1968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b64bfc0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 16:53:00.466  1953  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 16:53:00.467  1953  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ad254f9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 16:53:00.523  6600  6600 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 16:53:00.603  6600  6600 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 16:53:00.610  6600  6600 I LibraryLoader: Loading: webviewchromium
08-30 16:53:00.613  6600  6600 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2093-2096)
08-30 16:53:00.613  6600  6600 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:53:00.628  6600  6600 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e45db6e}
08-30 16:53:00.629  6600  6600 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:53:00.630  6600  6600 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 16:53:00.639  6600  6600 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 16:53:00.640  6600  6600 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:53:00.659  6600  6600 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 16:53:00.659   329  1381 V AudioPolicyService: registerClient() client 0xb0010020, uid 10118
08-30 16:53:00.659  6600  6600 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 16:53:00.660  6600  6600 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-30 16:53:00.662  1045  1120 D BluetoothManagerService: Message: 20
08-30 16:53:00.662  1045  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25bcf43e:true
08-30 16:53:00.676  6600  6600 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:53:00.676  6600  6600 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:53:00.676  6600  6600 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:53:00.676  6600  6600 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:53:00.676  6600  6600 I Adreno-EGL: Remote Branch: 
08-30 16:53:00.676  6600  6600 I Adreno-EGL: Local Patches: 
08-30 16:53:00.676  6600  6600 I Adreno-EGL: Reconstruct Branch: 
,08-30 16:53:00.738  6534  6534 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:00.738  6534  6534 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:00.757  6600  6629 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 16:53:00.759  6600  6600 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 16:53:00.793  6600  6600 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:53:00.799  6600  6600 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 16:53:00.802  6600  6600 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 16:53:00.805  6600  6600 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 16:53:00.805  6600  6600 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 16:53:00.822  6600  6600 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 16:53:00.832  6600  6600 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 16:53:00.832  6600  6600 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:53:00.857  6600  6643 D OpenGLRenderer: Render dirty regions requested: true
08-30 16:53:00.857  6600  6643 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 16:53:00.862  6600  6643 D OpenGLRenderer: Enabling debug mode 0
08-30 16:53:00.868  6600  6600 D Atlas   : Validating map...
,08-30 16:53:00.872  1045  2012 D SplitWindow: check instance of lgWin Window{37e8e08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 16:53:00.902  6079  6079 I LockScreenSettings: New app installed broadcast received ..
,08-30 16:53:00.905  6079  6079 I LockScreenSettings: Number of installed packages  1
08-30 16:53:00.909  6600  6641 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:00.909  6600  6641 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:53:00.928  6534  6534 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 16:53:00.952  1045  1943 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:53:00.988  1045  1952 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6659 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:01.002  1045  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +538ms (total +652ms)
08-30 16:53:01.003  1045  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{385c6dfd u0 com.test.thalitest/.MainActivity t6} time:102486
08-30 16:53:01.003  6600  6600 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c5b7115 time:102486
,08-30 16:53:01.052  6659  6659 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 16:53:01.052  6659  6659 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-30 16:53:01.086  1045  2011 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6679 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 16:53:01.086  1045  2011 I ActivityManager: Killing 5765:com.google.android.gm/u0a64 (adj 15): empty #17
,08-30 16:53:01.113  6600  6600 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 16:53:01.113  6600  6600 I chromium: 
,08-30 16:53:01.134  6600  6600 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 16:53:01.169  1045  2042 W libprocessgroup: failed to open /acct/uid_10064/pid_5765/cgroup.procs: No such file or directory
,08-30 16:53:01.214  6679  6679 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-30 16:53:01.228  6679  6679 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 16:53:01.228  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-30 16:53:01.258  1045  1728 I ActivityManager: Killing 5809:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 16:53:01.263  6600  6702 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434975744
08-30 16:53:01.274  6600  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 16:53:01.274  6600  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 16:53:01.274  6600  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 16:53:01.274  6600  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 16:53:01.274  6600  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 16:53:01.274  6600  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9059c9 added. We now have 1 listener(s)
,08-30 16:53:01.289  1045  2333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:01.289  1045  1919 W libprocessgroup: failed to open /acct/uid_10072/pid_5809/cgroup.procs: No such file or directory
,08-30 16:53:01.292  6600  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 16:53:01.293  6600  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:01.294  6600  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:01.294  6600  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 16:53:01.299  6600  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d283efc added. We now have 1 listener(s)
08-30 16:53:01.300  6600  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:01.303  1045  1482 D WifiService: New client listening to asynchronous messages
,08-30 16:53:01.306  6600  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:53:01.306  6600  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 16:53:01.306  6600  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 16:53:01.306  6600  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 16:53:01.306  6600  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 16:53:01.310  6600  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:01.310  1045  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:01.311  6600  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 16:53:01.319  6600  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:01.320  6600  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:01.320  6600  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 16:53:01.320  6600  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:01.321  6600  6702 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:53:01.322  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:01.324  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:01.360  6600  6641 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 16:53:01.360  6600  6641 I chromium: 
,08-30 16:53:01.427  6600  6600 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 16:53:02.328   348   372 E GBMv2   : DFP En is all cleared set to be enabled
08-30 16:53:02.328   348   372 E GBMv2   : Set value is all cleared set the max
08-30 16:53:02.328   348   372 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 16:53:02.572  6600  6706 W jxcore-log: Initializing JXcore engine
,08-30 16:53:02.572  6600  6706 W jxcore-log: JXcore engine is ready
,08-30 16:53:02.640  6706  6706 W Thread-751: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8363]" dev="sockfs" ino=8363 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 16:53:02.640  6706  6706 W Thread-751: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 16:53:02.640  6706  6706 W Thread-751: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9969]" dev="sockfs" ino=9969 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 16:53:02.640  6706  6706 W Thread-751: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 16:53:02.640  6706  6706 W Thread-751: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31679]" dev="sockfs" ino=31679 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-30 16:53:02.671  6600  6706 W jxcore-log: Starting JXcore engine
,08-30 16:53:02.826  6600  6706 W jxcore-log: Platform android
08-30 16:53:02.826  6600  6706 W jxcore-log: 
08-30 16:53:02.826  6600  6706 W jxcore-log: Process ARCH arm
08-30 16:53:02.826  6600  6706 W jxcore-log: 
,08-30 16:53:03.241  6600  6706 I jxcore-log: JXcore Cordova bridge is ready!
08-30 16:53:03.241  6600  6706 I jxcore-log: 
08-30 16:53:03.242  6600  6706 W jxcore-log: JXcore engine is started
,08-30 16:53:03.255  6600  6702 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 16:53:03.264  6600  6600 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 16:53:03.887  2786  2786 I MusicWidget: mDelayedStopHandler : unbind
,08-30 16:53:03.889  2166  2166 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-30 16:53:03.889  2166  2166 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-30 16:53:03.890  2166  2166 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 16:53:03.891  2166  2166 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 16:53:03.891  2166  2166 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 16:53:03.891  2166  2166 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 16:53:03.893  2166  2166 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 16:53:03.893  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 16:53:03.907  1045  1952 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3b868acccom.lge.music.MediaPlaybackService$5@3c5b7115
08-30 16:53:03.908  2166  2166 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 16:53:03.908  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.909  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.909  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.910  2166  2166 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@978407a
,08-30 16:53:03.910  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.911  2166  2166 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 16:53:03.911  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.911  2166  2166 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 16:53:03.911  2166  2166 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 16:53:03.912  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.912  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.913  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.913  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.914  2166  2166 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 16:53:03.915  2166  2166 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-30 16:53:03.916  2166  2166 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 16:53:03.916  2166  2166 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 16:53:03.916  2166  2166 V MediaPlayer[Native]: reset
08-30 16:53:03.924  2166  2166 V MediaPlayer[Native]: setListener
08-30 16:53:03.924  2166  2166 V MediaPlayer[Native]: disconnect
08-30 16:53:03.924  2166  2166 V MediaPlayer[Native]: destructor
08-30 16:53:03.924   329  1381 V AudioFlinger: releasing 18 from 2166 for -1
08-30 16:53:03.924   329  1381 V AudioFlinger:  decremented refcount to 0
08-30 16:53:03.924   329  1381 V AudioFlinger: purging stale effects
08-30 16:53:03.924  2166  2166 V MediaPlayer[Native]: disconnect
08-30 16:53:03.925  2166  2166 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 16:53:03.926  2166  2166 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 16:53:03.928  2166  2166 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
,08-30 16:53:03.937  2166  2166 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 16:53:03.937  2166  2166 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 16:53:03.937  2166  2166 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 16:53:03.937  2166  2166 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 446807082
08-30 16:53:03.938  2166  2166 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 446807082
08-30 16:53:03.950  2166  2166 I SmartShareClient: [SmartShareManagerClient] terminate service: 2166/MediaPlaybackService/411541360
08-30 16:53:03.954  2166  2166 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 16:53:03.954  2166  2166 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@10ae1a1b
,08-30 16:53:03.968  2166  2166 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 16:53:03.969  2166  2166 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,08-30 16:53:03.984  2166  2166 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 16:53:03.984  2166  2166 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 16:53:03.985  1045  1735 I ActivityManager: Killing 5608:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 16:53:03.987  2166  2166 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
,08-30 16:53:03.994  5583  5583 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 16:53:03.994  5583  5583 W System.err: android.os.DeadObjectException
08-30 16:53:03.994  5583  5583 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:53:03.994  5583  5583 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:53:03.994  5583  5583 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 16:53:03.994  5583  5583 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 16:53:03.994  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 16:53:03.994  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-30 16:53:03.994  5583  5583 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:53:03.994  5583  5583 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:53:03.994  5583  5583 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:03.994  5583  5583 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:03.994  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:03.994  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:03.995  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-30 16:53:03.995  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 16:53:03.995  5583  5583 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 16:53:03.995  5583  5583 W System.err: android.os.DeadObjectException
08-30 16:53:03.995  5583  5583 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-30 16:53:03.995  5583  5583 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:53:03.995  5583  5583 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 16:53:03.995  5583  5583 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 16:53:03.995  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 16:53:03.995  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 16:53:03.995  5583  5583 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:53:03.995  5583  5583 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:53:03.995  5583  5583 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:03.995  5583  5583 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:03.995  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:03.995  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:03.995  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:03.995  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 16:53:03.995  5583  5583 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 16:53:03.995  5583  5583 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 16:53:04.192  1045  1735 E libprocessgroup: failed to kill 1 processes for processgroup 5608
,08-30 16:53:04.268  1045  2012 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-30 16:53:04.288  5583  5583 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-30 16:53:04.288  5583  5583 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 16:53:04.344  1045  1563 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6722 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:04.346  5583  5583 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 16:53:04.374  1045  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=202768612, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1045
,08-30 16:53:04.400  4457  6743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 16:53:04.410  2622  2622 D [Concierge]Service: onStartCommand(). Type : 9
08-30 16:53:04.440  1045  1045 D PowerManagerServiceEx: releaseWakeLockInternal: lock=202768612 [*alarm*], flags=0x0
,08-30 16:53:04.447  6722  6722 D UEI.SmartControl: Quickset Services start...
08-30 16:53:04.450  6722  6722 I UEI.SmartControl: Manufacture = LGE
08-30 16:53:04.450  6722  6722 D UEI.SmartControl: Id = LGNevo
08-30 16:53:04.451  6722  6722 D UEI.SmartControl: File observer start...
08-30 16:53:04.452  6722  6722 E UEI.SmartControl: IR Port is disabled: false
08-30 16:53:04.452  6722  6722 D UEI.SmartControl: Starting file observer...
08-30 16:53:04.452  6722  6722 D UEI.SmartControl: Extracting JNI libs...
08-30 16:53:04.452  6722  6722 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 16:53:04.533  6722  6722 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 16:53:04.533  6722  6722 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 16:53:04.533  6722  6722 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 16:53:04.565  6722  6722 I UEI.SmartControl: --- Selecting new region: 6
,08-30 16:53:04.568  6722  6722 I UEI.SmartControl: Model = LG-D855
08-30 16:53:04.569  6722  6722 D UEI.SmartControl: QS Service created
08-30 16:53:04.587  6722  6722 I UEI.SmartControl: Service initServices...
,08-30 16:53:04.591  6722  6722 D UEI.SmartControl: QS start get config
08-30 16:53:04.661  6722  6722 D UEI.SmartControl: Loading JNI Libs...
,08-30 16:53:04.835  6534  6534 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 16:53:04.839  1045  1976 I ActivityManager: Killing 5583:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 16:53:04.957  1045  2333 W libprocessgroup: failed to open /acct/uid_10112/pid_5583/cgroup.procs: No such file or directory
,08-30 16:53:05.010  6722  6722 I UEI.SmartControl: Supports setup maps: true
,08-30 16:53:05.014  6722  6722 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 16:53:05.014  6722  6722 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 16:53:05.014  6722  6722 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 16:53:05.014  6722  6722 I UEI.SmartControl: ### init IR Blaster...
08-30 16:53:05.019  6722  6722 D serial_port: Configuring serial port
08-30 16:53:05.022  6722  6722 E UEI.SmartControl: UEIBLaster setting for 616
08-30 16:53:05.022  6722  6722 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 16:53:05.023  6722  6722 I UEI.SmartControl: configuring settings for MAXQ616
08-30 16:53:05.023  6722  6722 I UEI.SmartControl: Get version...
08-30 16:53:05.040  6722  6761 D UEI.SmartControl: serial port data available: 21
,08-30 16:53:05.069  6722  6722 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 16:53:05.069  6722  6722 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 16:53:05.069  6722  6722 I UEI.SmartControl: QS saving settings...
08-30 16:53:05.071  6722  6722 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 16:53:05.089  6722  6761 D UEI.SmartControl: serial port data available: 4
,08-30 16:53:05.125  6722  6764 I UEI.SmartControl: Device manager: loading config....
08-30 16:53:05.126  6722  6764 D UEI.SmartControl: ----------- loading internal config...
,08-30 16:53:05.127  6722  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 16:53:05.135  6722  6722 E UEI.SmartControl: Services init done
08-30 16:53:05.135  6722  6722 D UEI.SmartControl: QS Service init finished
08-30 16:53:05.138  6722  6722 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 16:53:05.138  6722  6722 D UEI.SmartControl: QS Service version code: 201091
08-30 16:53:05.141  6722  6722 D UEI.SmartControl: Service requested: Control
08-30 16:53:05.144  6722  6764 E UEI.SmartControl: Loading SETTINGS...
,08-30 16:53:05.146  6722  6722 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 16:53:05.150  6722  6722 D UEI.SmartControl: Service.onUnbind: IControl
08-30 16:53:05.157  6722  6722 D UEI.SmartControl: Service.onDestroy
08-30 16:53:05.157  6722  6722 D UEI.SmartControl: Lock is in USE false
08-30 16:53:05.157  6722  6722 D UEI.SmartControl: unbind internal service
,08-30 16:53:05.159  6722  6722 D serial_port: close(fd = 25)
08-30 16:53:05.163  6722  6763 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 16:53:05.163  6722  6763 D UEI.SmartControl: -----service ready thread exits
08-30 16:53:05.165  6722  6722 I UEI.SmartControl: Serial port is closed.
08-30 16:53:05.165  6722  6722 I UEI.SmartControl: Serial port is closed.
08-30 16:53:05.165  6722  6722 D UEI.SmartControl: Blaster closed
08-30 16:53:05.165  6722  6722 D UEI.SmartControl: Shut down QS...
08-30 16:53:05.165  6722  6722 D UEI.SmartControl: Stopping QS lib
,08-30 16:53:05.165  6722  6722 D UEI.SmartControl: QS lib stop result = true
08-30 16:53:05.165  6722  6722 D UEI.SmartControl: Stopped QS lib
08-30 16:53:05.166  6722  6722 D UEI.SmartControl: Stopped file observer...
08-30 16:53:05.166  6722  6722 D UEI.SmartControl: QS shutdown complete
08-30 16:53:05.166  6722  6722 D UEI.SmartControl: QS Service created
08-30 16:53:05.167  6722  6764 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 16:53:05.180  6722  6722 I UEI.SmartControl: Service initServices...
08-30 16:53:05.181  6722  6722 D UEI.SmartControl: QS start get config
,08-30 16:53:05.514  6722  6722 I UEI.SmartControl: Supports setup maps: true
,08-30 16:53:05.517  6722  6722 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 16:53:05.517  6722  6722 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 16:53:05.517  6722  6722 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 16:53:05.517  6722  6722 I UEI.SmartControl: ### init IR Blaster...
08-30 16:53:05.522  6722  6722 D serial_port: Configuring serial port
08-30 16:53:05.522  6722  6722 E UEI.SmartControl: UEIBLaster setting for 616
08-30 16:53:05.522  6722  6722 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 16:53:05.522  6722  6722 I UEI.SmartControl: configuring settings for MAXQ616
08-30 16:53:05.522  6722  6722 I UEI.SmartControl: Get version...
08-30 16:53:05.538  6722  6776 D UEI.SmartControl: serial port data available: 21
,08-30 16:53:05.564  6722  6722 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 16:53:05.564  6722  6722 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 16:53:05.564  6722  6722 I UEI.SmartControl: QS saving settings...
08-30 16:53:05.564  6722  6722 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 16:53:05.580  6722  6776 D UEI.SmartControl: serial port data available: 4
,08-30 16:53:05.610  6722  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 16:53:05.612  6722  6779 I UEI.SmartControl: Device manager: loading config....
08-30 16:53:05.612  6722  6779 D UEI.SmartControl: ----------- loading internal config...
08-30 16:53:05.613  6722  6722 E UEI.SmartControl: Services init done
08-30 16:53:05.613  6722  6722 D UEI.SmartControl: QS Service init finished
08-30 16:53:05.615  6722  6722 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 16:53:05.615  6722  6722 D UEI.SmartControl: QS Service version code: 201091
08-30 16:53:05.616  6722  6722 D UEI.SmartControl: Service requested: Control
08-30 16:53:05.623  6722  6779 E UEI.SmartControl: Loading SETTINGS...
,08-30 16:53:05.627  6722  6722 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 16:53:05.631  1045  2042 I ActivityManager: Killing 6266:com.android.calendar/u0a13 (adj 15): empty #17
08-30 16:53:05.635  6722  6779 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 16:53:05.649  6722  6778 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 16:53:05.649  6722  6778 D UEI.SmartControl: -----service ready thread exits
08-30 16:53:05.772  1045  1061 W libprocessgroup: failed to open /acct/uid_10013/pid_6266/cgroup.procs: No such file or directory
,08-30 16:53:05.776  6722  6722 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@978407a that was originally bound here
08-30 16:53:05.776  6722  6722 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@978407a that was originally bound here
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:05.776  6722  6722 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 16:53:05.780  6722  6722 D UEI.SmartControl: Internal service binding...
08-30 16:53:05.824  6534  6637 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 16:53:06.158  6722  6766 D UEI.SmartControl: Internal timer expired: 2
,08-30 16:53:07.939  1823  6437 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 16:53:07.945   325  6786 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 16:53:07.946   325  6786 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 16:53:07.946   325  6786 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-30 16:53:08.150  1823  1823 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 16:53:08.159  1823  1823 I ConfigFetchService: stopping self
08-30 16:53:08.166  2246  2246 I ConfigService: onDestroy
,08-30 16:53:09.438  6722  6733 E UEI.SmartControl: file observer is disposed!
,08-30 16:53:10.596  6722  6777 D serial_port: close(fd = 24)
,08-30 16:53:10.605  6722  6777 I UEI.SmartControl: Serial port is closed.
08-30 16:53:10.611  6722  6780 D UEI.SmartControl: Internal timer expired: 3
08-30 16:53:10.611  6722  6780 D UEI.SmartControl: unbind internal service
08-30 16:53:10.626  6722  6722 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 16:53:10.631  6722  6722 D UEI.SmartControl: Service.onDestroy
,08-30 16:53:10.631  6722  6722 D UEI.SmartControl: Lock is in USE false
,08-30 16:53:10.631  6722  6722 D UEI.SmartControl: unbind internal service
,08-30 16:53:10.632  6722  6722 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2230335d
08-30 16:53:10.632  6722  6722 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,08-30 16:53:10.632  6722  6722 W System.err: ,	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 16:53:10.632  6722  6722 W System.err: ,	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 16:53:10.633  6722  6722 W System.err: ,	at com.uei.control.Service.c(Unknown Source)
,08-30 16:53:10.633  6722  6722 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source),
,08-30 16:53:10.633  6722  6722 W System.err: 	,at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 16:53:10.633  6722  6722 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 16:53:10.633  6722  6722 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 16:53:10.633  6722  6722 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:53:10.633  6722  6722 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:10.633  6722  6722 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:10.633  6722  6722 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:10.634  6722  6722 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:10.634  6722  6722 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:10.634  6722  6722 W System.err: ,	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 16:53:10.634  6722  6722 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2230335d
08-30 16:53:10.634  6722  6722 I UEI.SmartControl: Serial port is closed.,
08-30 16:53:10.634  6722  6722 I UEI.SmartControl: Serial port is closed.
,08-30 16:53:10.634  6722  6722 D UEI.SmartControl: Blaster closed
,08-30 16:53:10.634  6722  6722 D UEI.SmartControl: Shut down QS...
,08-30 16:53:10.637  6722  6722 D UEI.SmartControl: Stopping QS lib
,08-30 16:53:10.637  6722  6722 D UEI.SmartControl: QS lib stop result = true
,08-30 16:53:10.637  6722  6722 D UEI.SmartControl: Stopped QS lib
08-30 16:53:10.637  6722  6722 D UEI.SmartControl: QS shutdown complete,
08-30 16:53:13.101  1045  1114 I ActivityManager: Waited long enough for: ServiceRecord{2fee2f3a u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 16:53:13.249  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-30 16:53:13.249  6600  6706 I jxcore-log: 
,08-30 16:53:13.252  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 16:53:13.252  6600  6706 I jxcore-log: 
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:13.257  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:13.260  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.264  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 16:53:13.264  6600  6706 I jxcore-log: 
,08-30 16:53:13.265  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 16:53:13.265  6600  6706 I jxcore-log: 
08-30 16:53:13.772  6600  6706 D executeNativeTests: Running unit tests
,08-30 16:53:13.852  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:13.852  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 added. We now have 2 listener(s)
,08-30 16:53:13.853  1045  1735 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:13.854  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:13.854  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:13.854  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:13.854  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:13.855  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e added. We now have 2 listener(s)
08-30 16:53:13.855  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:13.855  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:53:13.856  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:13.861  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:13.862  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.863  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:13.864  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:13.865  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:13.872  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:53:13.877  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:53:13.877  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:53:13.879  6600  6706 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 16:53:13.880  6600  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:53:13.880  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:53:13.880  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:53:13.880  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:53:13.881  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.881  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.881  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.882  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:13.882  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.882  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:13.882  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:13.882  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 removed from the list
08-30 16:53:13.882  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.882  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e removed from the list
08-30 16:53:13.882  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:13.882  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.883  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.883  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:53:13.884  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:13.884  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:13.884  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.884  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.887  6600  6706 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 16:53:13.888  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.888  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.888  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.888  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:13.888  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.888  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.888  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:13.888  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.888  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.888  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:13.888  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.888  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.889  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.889  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.889  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:13.889  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:13.889  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.889  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.896  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:53:13.898  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:53:13.899  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:53:13.900  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:53:13.900  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.900  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.900  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.901  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:13.901  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.901  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.901  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:13.901  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.901  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.901  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:13.901  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.901  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.901  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.901  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.902  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:13.902  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:13.902  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.902  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.903  6600  6706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:53:13.904  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:13.906  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:13.907  6600  6706 D io.jxcore.node.JXcore,Extension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.907  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:13.908  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:13.908  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:53:13.908  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:53:13.909  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:13.910  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:13.908  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:13.912  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:53:13.917  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:53:13.917  1045  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:13.922  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:53:13.930  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:53:13.932  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 16:53:13.934  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:53:13.934  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:13.935  6600  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:53:13.935  6600  6706 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:53:13.939  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.939  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.940  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.940  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:13.940  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.940  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:13.940  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:13.940  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:53:13.941  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.941  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:13.941  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.942  6600  6706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:53:13.945  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:13.949  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:13.951  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.951  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:13.951  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:13.951  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:53:13.952  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:53:13.952  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:13.952  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:53:13.957  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:13.959  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:13.962  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:53:13.962  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:13.964  6600  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 16:53:13.965  6600  6706 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:53:13.967  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.967  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.967  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.968  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:13.968  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.968  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:13.968  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:13.968  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.968  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.968  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:13.968  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.968  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.968  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.969  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:13.970  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:13.972  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:13.972  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:13.972  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.972  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.973  6600  6706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:53:13.975  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:13.980  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:13.982  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:13.982  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:13.983  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:13.983  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:53:13.983  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:53:13.983  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:13.983  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:53:13.985  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:13.988  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:13.993  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:53:13.993  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:13.995  6600  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:53:13.995  6600  6706 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:53:13.995  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.995  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.995  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.996  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:13.996  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:13.996  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:13.997  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:13.997  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.997  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:53:13.997  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:13.997  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.997  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:13.997  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:13.997  2166  2166 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
08-30 16:53:13.997  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.998  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:13.998  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:13.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:13.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:13.999  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:13.999  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:13.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:13.999  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.000  6600  6706 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 16:53:14.001  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.001  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.001  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.001  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.001  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.001  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.001  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.001  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.001  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.001  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.001  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.001  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.001  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.001  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.blu,etooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.003  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.003  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:53:14.004  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.004  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.004  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.004  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.005  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:53:14.005  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.006  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.006  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.006  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.006  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.006  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.006  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.006  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.006  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.007  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.007  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.007  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.007  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.007  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.009  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.009  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.010  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.010  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.010  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.010  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.011  6600  6706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 16:53:14.011  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.011  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.011  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already mat,ches the desired outcome of this operation, skipping...
08-30 16:53:14.012  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.012  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.012  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.012  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.012  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.012  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.012  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.012  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.012  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.012  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.012  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.014  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.014  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.017  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.017  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.017  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.017  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.019  6600  6706 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 16:53:14.019  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.020  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.020  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.020  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.020  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.020  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.020  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.020  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.020  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.020  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.021  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.021  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.021  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.021  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.022  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.022  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.022  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.022  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.022  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.023  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.023  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:53:14.025  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:53:14.025  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:53:14.026  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:53:14.026  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:53:14.026  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:53:14.026  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.026  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.026  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.026  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.026  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.026  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.027  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.027  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.027  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.027  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.027  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.027  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.027  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.027  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.032  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.033  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.033  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.033  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.033  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.033  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.035  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:53:14.035  6600  6706 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:53:14.035  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:53:14.042  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:53:14.042  6600  6706 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 16:53:14.042  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:53:14.042  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:53:14.043  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:53:14.044  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:53:14.045  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:53:14.045  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:53:14.045  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:53:14.045  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:53:14.045  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:53:14.045  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:53:14.046  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:53:14.046  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:53:14.046  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:53:14.046  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:53:14.046  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:53:14.046  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 16:53:14.047  6600  6706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:53:14.047  6600  6706 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 16:53:14.047  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:53:14.047  6600  6706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:53:14.048  6600  6706 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 16:53:14.048  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:53:14.048  6600  6706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:53:14.048  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 16:53:14.050  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 16:53:14.052  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 16:53:14.052  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 16:53:14.053  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 16:53:14.053  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 16:53:14.053  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 16:53:14.053  6600  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:53:14.053  6600  6706 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 16:53:14.054  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.054  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.054  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.055  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.055  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.055  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.055  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 16:53:14.057  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.057  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.057  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.057  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.057  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.057  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.058  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.058  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.060  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.060  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.061  6600  6787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 815)
08-30 16:53:14.062  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.062  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.062  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.062  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.063  6600  6706 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 16:53:14.064  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.064  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.064  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.064  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.064  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.064  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.064  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.064  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.064  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.064  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.064  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.064  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.064  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.064  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.066  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.066  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.068  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.069  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.069  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.070  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.073  6600  6706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 16:53:14.074  6600  6788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 815
08-30 16:53:14.074  6600  6788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 815)
08-30 16:53:14.074  6600  6788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 815)
08-30 16:53:14.075  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.075  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.075  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.076  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.076  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.076  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.076  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.076  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.076  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.076  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.076  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.076  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.076  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.076  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.078  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.078  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:53:14.081  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.081  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.081  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.081  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.082  6600  6706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 16:53:14.082  6600  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 16:53:14.082  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:53:14.082  6600  6706 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 16:53:14.082  6600  6706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:53:14.082  6600  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 16:53:14.083  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:53:14.083  6600  6706 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 16:53:14.083  6600  6706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:53:14.083  6600  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:53:14.083  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:53:14.083  6600  6706 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 16:53:14.083  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.083  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.084  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.084  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.084  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.084  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.084  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.084  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.084  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.084  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.084  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.084  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.084  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.084  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.085  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.085  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.086  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.086  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.086  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.086  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.087  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.087  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.087  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.087  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.087  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.087  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.087  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.087  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.087  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.097  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.097  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.097  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.097  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.097  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.097  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.097  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.097  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.097  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.098  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.098  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.098  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.098  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.098  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.098  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.098  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.098  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.098  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.098  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.098  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.099  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.099  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.100  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.100  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.100  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.100  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.105  6600  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 16:53:14.105  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:14.105  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 16:53:14.106  6600  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 16:53:14.106  6600  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 16:53:14.107  6600  6600 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 16:53:14.107  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 16:53:14.107  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:53:14.108  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.108  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 16:53:14.108  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 16:53:14.108  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 16:53:14.108  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.108  6600  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 16:53:14.108  6600  6600 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:53:14.108  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.108  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.108  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:53:14.108  6600  6706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:53:14.108  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:53:14.110  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:53:14.110  6600  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 16:53:14.110  6600  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:53:14.110  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:14.110  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:14.110  6600  6706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:53:14.112  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.112  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.113  6600  6706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:53:14.113  6600  6600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:53:14.113  6600  6600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:53:14.113  6600  6600 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 16:53:14.113  6600  6600 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:53:14.114  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.114  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.114  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.114  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.114  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.114  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.114  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.114  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.114  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.114  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.114  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.114  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.114  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.114  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.114  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.115  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.115  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.115  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.115  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.116  6600  6706 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 16:53:14.116  6600  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:53:14.116  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:53:14.116  6600  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:53:14.116  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.116  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.116  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.117  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.117  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.117  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.117  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.117  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.117  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.117  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.117  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.117  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.117  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.117  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.117  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.117  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.118  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.118  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.118  1045  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:14.119  1045  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:14.121  1045  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:14.122  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.122  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.122  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:53:14.124  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.124  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.125  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.125  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.125  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.125  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.125  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.125  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.125  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.125  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.125  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.126  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.126  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.126  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.126  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.128  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:14.128  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:14.128  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:14.128  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:14.128  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.128  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.128  6600  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3943ac59 not in the list
08-30 16:53:14.128  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.128  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.128  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:14.128  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.128  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.128  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:14.128  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:14.130  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:14.130  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:14.130  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:14.130  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2629b01e not in the list
08-30 16:53:14.132  6600  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 16:53:14.132  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:53:14.132  6600  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 16:53:14.132  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:53:14.132  6600  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 16:53:14.132  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:53:14.138  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:53:14.138  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 16:53:14.138  6600  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 16:53:14.138  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:53:14.138  6600  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 16:53:14.138  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:53:14.139  6600  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 16:53:14.139  6600  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 16:53:14.139  6600  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 16:53:14.139  6600  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 16:53:14.140  6600  6706 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 16:53:14.140  6600  6706 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 16:53:14.140  6600  6706 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 16:53:14.140  6600  6706 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 16:53:14.140  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:14.140  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@101660f7 added. We now have 2 listener(s)
08-30 16:53:14.140  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:14.142  6600  6706 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 16:53:14.143  1045  1061 D WifiServiceImplEx: setWifiEnabled: true pid=6600, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:53:14.143  1045  1061 D WifiService: setWifiEnabled: true pid=6600, uid=10118
08-30 16:53:14.143  1045  1061 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:53:14.144  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:14.144  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@211cbb64 added. We now have 3 listener(s)
08-30 16:53:14.144  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:14.148  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:14.148  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dac71cd added. We now have 4 listener(s)
08-30 16:53:14.148  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:14.149  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:14.149  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea71a82 added. We now have 5 listener(s)
08-30 16:53:14.149  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:14.151  1045  1919 D WifiServiceImplEx: setWifiEnabled: false pid=6600, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:53:14.151  1045  1919 D WifiService: setWifiEnabled: false pid=6600, uid=10118
08-30 16:53:14.151  1045  1919 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:53:14.172  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:14.172  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:14.172  1045  1045 D Ulp_jni : JNI:system_update. Event-4
08-30 16:53:14.173  1045  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:14.173  1045  1642 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2dd6c429 mBinding = false
08-30 16:53:14.173  1045  1424 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:14.173  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:14.174  1045  1424 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:14.174  1045  1424 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:14.175  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:14.176  1045  1424 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 16:53:14.176  1045  1424 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:53:14.176  1045  1424 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:53:14.176  1045  1424 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:53:14.176  1045  1424 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:53:14.184  6600  6787 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 16:53:14.184  6600  6787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 815)
,08-30 16:53:14.188  1045  1424 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:53:14.189  1045  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.189  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.189  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:53:14.189  2645  2645 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:53:14.189  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:53:14.189  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:14.190  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:14.190  1045  2838 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.192   325   889 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:53:14.199  1045  1120 D BluetoothManagerService: Message: 2
08-30 16:53:14.200  1045  1120 D BluetoothManagerService: Sending off request.
08-30 16:53:14.200  3817  3834 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 16:53:14.200  3817  3890 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 16:53:14.200  3817  3890 D BluetoothAdapterProperties: Setting state to 13
08-30 16:53:14.201  3817  3890 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:53:14.201  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 16:53:14.201  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:14.201  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 16:53:14.201  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 16:53:14.201  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:14.201  3817  3890 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 16:53:14.201  3817  3890 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 16:53:14.202  1045  1045 D Ulp_jni : JNI:system_update. Event-4
,08-30 16:53:14.204  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.204  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:14.206  3817  3817 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.206  3817  3817 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:53:14.207  3817  3817 V BluetoothMapService: Handler(): got msg=4
08-30 16:53:14.207  3817  3817 D BluetoothMapService: MAP Service closeService in
08-30 16:53:14.207  3817  3817 D BluetoothMapMasInstance: MAP Service shutdown
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 16:53:14.208  3817  4120 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 16:53:14.208  3817  3817 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:53:14.208  3817  3817 V BluetoothMapService: MAP Service closeService out
08-30 16:53:14.208  3817  3817 V BtOppService: Receiver DISABLED_ACTION 
08-30 16:53:14.208  3817  3817 I BtOppRfcommListener: stopping Accept Thread
,08-30 16:53:14.208  3817  3817 V BtOppRfcommListener: close mBtServerSocket
08-30 16:53:14.209  3817  3817 V BtOppRfcommListener: waiting for thread to terminate
08-30 16:53:14.209  3817  4173 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:14.209  3817  4173 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:53:14.209  3817  3817 V BtOppRfcommListener: done waiting for thread to terminate
08-30 16:53:14.215  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:14.215  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:14.216  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.216  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:14.217  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:53:14.217  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-30 16:53:14.250  1045  1114 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:14.252  3817  3817 V BtOppService: onDestroy
08-30 16:53:14.252  1045  1045 D WifiHS20: hidePasspointNotification off =false
08-30 16:53:14.254  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 16:53:14.256  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.256  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.256  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:14.258  1045  1424 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.258  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.258  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.258  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.258  1045  1375 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@36e5d5bc
08-30 16:53:14.258  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.258  1045  1375 D LGWifiP2pService: P2pDisablingState
08-30 16:53:14.258  1045  1375 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.258  1045  1375 D LGWifiP2pService: p2p socket connection lost
08-30 16:53:14.259  1045  1424 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.259  1045  1375 D LGWifiP2pService: P2pDisabledState
08-30 16:53:14.259  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.259  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.260  1045  1424 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:53:14.260  1045  1424 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.261  1045  1045 D WifiHS20: hidePasspointNotification off =false
08-30 16:53:14.263  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.263  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:14.263  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:14.263  1045  1424 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 16:53:14.263  1045  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.263  1045  1375 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.264  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:53:14.264  2645  2645 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:53:14.264  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:53:14.264  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:14.264  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:14.266   325   889 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:53:14.267  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.267  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.267  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHA,NGED_ACTION [DISCONNECTED]
08-30 16:53:14.267  1045  1045 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 16:53:14.267  1045  1045 D RttService: SCAN_AVAILABLE : 1
08-30 16:53:14.268  1045  1505 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 16:53:14.268  1045  1505 D DSQN    : disableDataServiceNotify
08-30 16:53:14.268  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:53:14.268  1045  1505 D DSQN    : stop dsqn bin
08-30 16:53:14.268  1045  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.268  1045  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.270  1045  1424 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 16:53:14.270  1045  1424 D WifiNative-p2p0: TERMINATE: returned true
08-30 16:53:14.270  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:14.270  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:14.270  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:53:14.270  1953  1953 D WfdsService: WifiP2pState is changed : false
08-30 16:53:14.270  1953  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 16:53:14.270  1953  2345 D WfdsService: Set the WFDS Monitor: false
08-30 16:53:14.271  1953  2345 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:53:14.271  1953  2345 D WfdsService: STATE : WfdsDisabledState - enter
08-30 16:53:14.271  1953  2720 D CtrlSupplicant: Received on exit socket, terminate
08-30 16:53:14.271  1953  2720 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 16:53:14.271  1953  2720 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 16:53:14.271  1953  2720 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 16:53:14.272  1953  2346 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 16:53:14.272  1953  2345 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 16:53:14.273  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:14.273  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:14.276  1045  1045 D WifiHS20: hidePasspointNotification off =false
,08-30 16:53:14.279  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.279  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.279  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:14.280  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 16:53:14.281  1045  1505 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 16:53:14.281  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:14.281  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:14.281  1045  1505 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:14.281  1045  1505 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 16:53:14.282  1045  1505 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 16:53:14.282  1045  1505 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 16:53:14.282  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:53:14.282  1045  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.282  1045  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.282  1045  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 16:53:14.283  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 16:53:14.283  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 16:53:14.283  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:14.283  1045  1045 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 16:53:14.284  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.284  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is B,luetooth enabled: false
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:14.284  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:14.285  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.285  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:14.285  1045  1505 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:14.285  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:53:14.285  1045  1505 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:14.285  1045  1505 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:14.285  1045  1505 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:14.285  1045  1505 D NetworkManagementService: Removing idletimer
08-30 16:53:14.286  1045  1505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.286  1045  1505 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 16:53:14.286  1045  1424 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:14.286  1045  1424 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:14.287  1045  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-30 16:53:14.287  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:14.287  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:53:14.289  1045  1045 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 16:53:14.290  1045  1045 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:53:14.290  1045  1045 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:53:14.290  1045  1045 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:53:14.291  1045  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 16:53:14.292  1045  1045 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-30 16:53:14.293  1045  1045 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:53:14.293  1045  1045 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:53:14.293  1045  1045 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 16:53:14.325  1045  1943 I art     : Explicit concurrent mark sweep GC freed 35641(1762KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.685ms total 122.038ms
,08-30 16:53:14.327  3817  3894 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:53:14.327  3817  3817 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 16:53:14.327  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:14.327  3817  3890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 16:53:14.328  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 16:53:14.328  3817  3966 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 16:53:14.328  3817  4175 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:14.328  3817  3890 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:53:14.329  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.329  3817  4180 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:14.329  3817  4122 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:14.330  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:14.331  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.331  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:14.331  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 16:53:14.332  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 16:53:14.332  3817  3966 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:53:14.336  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state c,hanges
08-30 16:53:14.337  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:14.338  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:14.338  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:14.339  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:14.348  2645  2645 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 16:53:14.366  1045  1728 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6826 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:14.375  2645  2645 I wpa_supplicant: monitor socket send errors count : 1
08-30 16:53:14.375  2645  2645 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1953-2\x00 that cannot receive messages
08-30 16:53:14.376  1045  2714 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 16:53:14.376  1045  2714 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:53:14.379  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:14.379  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:14.379  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:53:14.382  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 16:53:14.382  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:14.383  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.384  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.388  6805  6805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:14.388  6805  6805 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 16:53:14.388  6805  6805 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:14.388  6805  6805 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 16:53:14.389  6805  6805 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 16:53:14.389  6805  6805 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 16:53:14.405  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 16:53:14.405  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.406  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.412  2645  2645 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:53:14.413  2645  2645 W wpa_supplicant: USIM:  scard_deinit function
08-30 16:53:14.413  1045  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 16:53:14.413  1045  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:53:14.413  1045  2714 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:53:14.413  1045  2714 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 16:53:14.413  1045  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:14.414  1045  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:14.414  1045  1120 D Tethering: InitialState.processMessage what=4
08-30 16:53:14.414  1045  1424 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115885
08-30 16:53:14.415  1045  1424 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115886
08-30 16:53:14.415  1045  1424 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=115886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:53:14.415  1045  1424 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=115886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:53:14.416  1045  1424 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:14.416  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 16:53:14.418  1045  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:53:14.425  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:53:14.426  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.427  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:53:14.430  1045  2838 D DhcpStateMachine: StoppedState
08-30 16:53:14.430  1045  2838 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:14.431  1045  1424 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 16:53:14.431  1045  1424 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 16:53:14.436  6826  6826 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:53:14.444  6826  6826 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 16:53:14.444  6826  6826 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:14.446  1045  1642 I ActivityManager: Killing 6237:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-30 16:53:14.485  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 16:53:14.501  1045  1952 W libprocessgroup: failed to open /acct/uid_10014/pid_6237/cgroup.procs: No such file or directory
,08-30 16:53:14.519  2645  2645 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 16:53:14.520  1045  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 16:53:14.520  1045  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 16:53:14.520  1045  2714 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-30 16:53:14.521  3817  3817 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:14.521  3817  3817 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.522  3817  3817 V BluetoothPbapReceiver: ***********state = 13
08-30 16:53:14.522  1045  1424 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 16:53:14.526  3817  3817 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 16:53:14.528  3817  3817 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.529  3817  3817 V BluetoothPbapService: state: 13
08-30 16:53:14.529  3817  3817 V BluetoothPbapService: Pbap Service closeService in
08-30 16:53:14.532  3817  3817 V BluetoothPbapService: successfully stopped pbap service
08-30 16:53:14.533  3817  3817 V BluetoothPbapService: Pbap Service closeService out
08-30 16:53:14.533  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:53:14.534  3817  3817 V BluetoothPbapService: Pbap Service onDestroy
08-30 16:53:14.534  3817  3817 V BluetoothPbapService: Pbap Service closeService in
08-30 16:53:14.534  3817  3817 V BluetoothPbapService: Pbap Service closeService out
08-30 16:53:14.534  3817  3817 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-30 16:53:14.547  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:14.593  6805  6805 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 16:53:14.593  6805  6805 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:53:14.607  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:14.610  1045  1061 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6848 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 16:53:14.615  6600  6600 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 16:53:14.616  1045  1120 D BluetoothManagerService: Message: 20
08-30 16:53:14.616  1045  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32e9d76b:true
08-30 16:53:14.625  1045  1424 D WifiOffDelayIfNotUsed: stopMonitoring
,08-30 16:53:14.625  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:14.625  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:14.625  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 16:53:14.627  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:14.628  1953  1953 D WfdsService: Supplicant Connection state is changed : false
08-30 16:53:14.628  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:53:14.628  1953  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 16:53:14.629  1953  2345 D WfdsService: Set the WFDS Monitor: false
08-30 16:53:14.629  1953  2345 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:53:14.629  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 16:53:14.630  1045  1454 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 16:53:14.630  1045  1454 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 16:53:14.631  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:14.633  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:14.634  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:14.640  1045  1120 D BluetoothManagerService: Message: 30
,08-30 16:53:14.645  1045  1120 D BluetoothManagerService: Message: 30
08-30 16:53:14.648  6805  6805 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 16:53:14.650  6805  6805 D BluetoothMap: Create BluetoothMap proxy object
08-30 16:53:14.650  1045  1120 D BluetoothManagerService: Message: 30
08-30 16:53:14.655  1045  1120 D BluetoothManagerService: Message: 30
,08-30 16:53:14.657  6805  6805 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 16:53:14.658  6805  6805 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 16:53:14.676  6805  6805 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 16:53:14.682  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 16:53:14.691  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:53:14.703  6805  6805 D BluetoothInputDevice: Proxy object connected
08-30 16:53:14.704  6805  6805 D HidProfile: Bluetooth service connected
,08-30 16:53:14.706  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:53:14.707  6805  6805 D PanProfile: Bluetooth service connected
08-30 16:53:14.709  6805  6805 D BluetoothMap: Proxy object connected
08-30 16:53:14.709  6805  6805 D MapProfile: Bluetooth service connected
08-30 16:53:14.709  6805  6805 D BluetoothMap: getConnectedDevices()
08-30 16:53:14.710  6805  6805 D BluetoothMap: Bluetooth is Not enabled
08-30 16:53:14.711  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 16:53:14.769  1045  2012 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6872 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 16:53:14.771  1045  2012 I ActivityManager: Killing 6214:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 16:53:14.839  1045  2042 W libprocessgroup: failed to open /acct/uid_10004/pid_6214/cgroup.procs: No such file or directory
08-30 16:53:14.839  6848  6848 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 16:53:14.840  6848  6848 W LG Account v2.2: No ProfileInfo entries
08-30 16:53:14.840  6848  6848 I LG Account v2.2: isEnabled: false
08-30 16:53:14.841  6848  6848 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 16:53:14.841  6848  6848 I Feature : [Lifetracker]Country: EU
,08-30 16:53:14.841  6848  6848 I Feature : [Lifetracker]Operator: OPEN
08-30 16:53:14.841  6848  6848 I Feature : [Lifetracker]Ranking support: false
08-30 16:53:14.842  6848  6848 I Feature : [Lifetracker]Comfort support: false
08-30 16:53:14.842  6848  6848 I Feature : [Lifetracker]Accessory: true
08-30 16:53:14.842  6848  6848 I Feature : [Lifetracker]Health device: true
08-30 16:53:14.842  6848  6848 I Feature : [Lifetracker]Extra Pedometer: false
08-30 16:53:14.842  6848  6848 I Feature : [Lifetracker]Blood glucose device: false
08-30 16:53:14.843  6848  6848 I Feature : [Lifetracker]Device Number: 3
08-30 16:53:14.865  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:53:14.874  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 16:53:14.877  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:53:14.886  6872  6872 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:14.896  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 16:53:14.899  1045  1952 I ActivityManager: Killing 6449:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 16:53:14.941  3817  3817 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 16:53:14.941  3817  3817 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 16:53:14.942  3817  3817 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 16:53:14.944  1045  1563 W libprocessgroup: failed to open /acct/uid_10008/pid_6449/cgroup.procs: No such file or directory
08-30 16:53:14.951  6872  6872 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 16:53:14.952  3817  3817 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.953  3817  3817 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 16:53:14.955  3817  3817 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:53:14.955  3817  3817 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.956  3817  3817 V BluetoothFtpService: Ftp Service closeService
08-30 16:53:14.956  3817  3817 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 16:53:14.959  3817  3817 V BluetoothFtpService: successfully stopped ftp service
08-30 16:53:14.960  3817  3817 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:14.960  3817  3817 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:14.960  3817  3817 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:14.960  3817  3817 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:14.960  3817  3817 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 16:53:14.960  3817  3817 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:53:14.965  3817  3817 V BluetoothFtpService: Ftp Service onDestroy
08-30 16:53:14.965  3817  3817 V BluetoothFtpService: Ftp Service closeService
,08-30 16:53:15.004  6872  6872 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 16:53:15.005  6872  6872 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 16:53:15.005  6872  6872 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 16:53:15.005  6872  6872 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-30 16:53:15.006  6872  6872 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 16:53:15.011  6872  6872 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 16:53:15.017  6872  6872 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 16:53:15.028  1045  1563 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6891 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:15.031  3817  3817 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:15.031  3817  3817 V BluetoothSapService: state: 13
08-30 16:53:15.031  3817  3817 V BluetoothSapService: Stopping SAP server process
08-30 16:53:15.036  3817  3817 V BluetoothSapService: Sap Service closeSapService in
08-30 16:53:15.036  3817  3817 V BluetoothSapService: Close listen Socket : 
08-30 16:53:15.037  3817  3817 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:53:15.037  3817  3817 V BluetoothSapService: Close sapd  Socket : 
08-30 16:53:15.038  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:15.040  3817  3817 V BluetoothSapService: Sap Service closeSapService out
08-30 16:53:15.040  3817  3817 V BluetoothSapService: Sap Service onDestroy
08-30 16:53:15.041  3817  3817 V BluetoothSapService: Sap Service closeSapService in
08-30 16:53:15.041  3817  3817 V BluetoothSapService: Close listen Socket : 
08-30 16:53:15.041  3817  3817 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:53:15.041  3817  3817 V BluetoothSapService: Close sapd  Socket : 
08-30 16:53:15.041  3817  3817 V BluetoothSapService: Sap Service closeSapService out
,08-30 16:53:15.043  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:15.053   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 21.420ms
08-30 16:53:15.063  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:53:15.065  6872  6872 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 16:53:15.066  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:15.071  6826  6826 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:53:15.071  6826  6826 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:53:15.071  6826  6826 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:15.074  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:53:15.074   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 20.942ms
,08-30 16:53:15.076  6872  6872 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-30 16:53:15.086  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:15.093  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:15.093  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:15.094  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:53:15.094   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 540us total 20.075ms
08-30 16:53:15.097  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:15.100  6826  6826 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:53:15.100  6826  6826 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:53:15.100  6826  6826 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:15.102  6891  6891 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:15.103  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:15.112  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:15.119  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:15.119  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:15.121  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 16:53:15.121  1045  1061 I ActivityManager: Killing 5972:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-30 16:53:15.149  1045  1943 W libprocessgroup: failed to open /acct/uid_10011/pid_5972/cgroup.procs: No such file or directory
,08-30 16:53:15.212  1045  1061 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6911 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 16:53:15.327  6826  6826 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:15.331  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:53:15.337  3817  3894 D bt_hci_bdroid: cleanup
,08-30 16:53:15.338  3817  3968 I bt_lpm  : LPM is already off!!!
08-30 16:53:15.338  3817  3966 W bt-btif : ag scb idx 1 not allocated
08-30 16:53:15.338  3817  3966 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-30 16:53:15.339  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:53:15.340  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:15.340  3817  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 16:53:15.340  3817  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:15.340  3817  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 16:53:15.340  3817  3966 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:53:15.341  3817  4108 I bt_userial_mct: exiting userial_read_thread
,08-30 16:53:15.341  3817  4108 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 16:53:15.341  3817  3894 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-30 16:53:15.347  3817  3968 I bt_vendor: hw_epilog_process
,08-30 16:53:15.348  3817  3894 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 16:53:15.348  3817  3894 D bt_userial_mct: userial_close
08-30 16:53:15.348  3817  3894 E bt_userial_mct: pthread_join() FAILED result:3
08-30 16:53:15.348  3817  3894 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 16:53:15.353  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:15.375  6911  6934 W FormManager: Network not available. Please check & try again.
,08-30 16:53:15.376  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:53:15.376  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:53:15.376  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:53:15.377  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:53:15.377  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 16:53:15.381  6911  6935 V FormManager: Network unavailable.
08-30 16:53:15.383  6911  6935 V FormManager: Network unavailable.
08-30 16:53:15.390  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:53:15.390  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:53:15.390  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:53:15.390  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:53:15.390  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:53:15.391  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 16:53:15.394  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:15.394  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:53:15.396  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:15.398  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:15.406  6826  6826 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 16:53:15.406  6826  6826 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:53:15.406  6826  6826 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:15.411  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:53:15.411  4294  6938 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:15.413  6911  6940 W FormManager: Network not available. Please check & try again.
08-30 16:53:15.417  4294  6942 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:15.417  4294  6942 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:53:15.417  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:15.431  6911  6941 V FormManager: Network unavailable.
,08-30 16:53:15.436  6911  6941 V FormManager: Network unavailable.
08-30 16:53:15.437  3817  3894 D bt_hci_bdroid: set_power 0
08-30 16:53:15.437  3817  3894 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 16:53:15.437  3817  3894 I bt_vendor: bluetooth satus is on
08-30 16:53:15.437  3817  3894 I bt_vendor: bt-vendor : resetting BT status
08-30 16:53:15.437  3817  3894 I bt_vendor: Starting hciattach daemon
08-30 16:53:15.437  3817  3894 I bt_vendor: try to set false
08-30 16:53:15.437  3817  3894 I bt_vendor: Starting hciattach daemon
08-30 16:53:15.437  3817  3894 I bt_vendor: try to set false
08-30 16:53:15.438  3817  3894 I bt_vendor: cleanup
08-30 16:53:15.438  3817  3966 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 16:53:15.440  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 16:53:15.444  1045  2333 I ActivityManager: Killing 5993:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 16:53:15.447  3817  3894 I GKI_LINUX: GKI_exit_task 0 done
08-30 16:53:15.447  3817  3894 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 16:53:15.448  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 16:53:15.448  6872  6872 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 16:53:15.449  3817  3890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 16:53:15.484  6872  6872 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 16:53:15.484  6872  6872 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:53:15.492  6872  6872 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 16:53:15.493  6872  6872 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 16:53:15.493  6872  6872 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-30 16:53:15.493  6872  6872 V SoundPool: doLoad: loading sample sampleID=1
08-30 16:53:15.493  6872  6872 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 16:53:15.494  6872  6949 V SoundPool: Start decode
08-30 16:53:15.494  6872  6949 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-30 16:53:15.495   329  1537 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 16:53:15.495   329  1537 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 16:53:15.495   329  1537 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 16:53:15.495   329  1537 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 16:53:15.495   329  1537 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 16:53:15.495   329  1537 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 16:53:15.495   329  1537 V MediaPlayerService: player type = 3
08-30 16:53:15.495   329  1537 V AwesomePlayer: AwesomePlayer create()
,08-30 16:53:15.496   329  1537 V AwesomePlayer: reset_l() 
08-30 16:53:15.496   329  1537 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:15.496   329  1537 V AwesomePlayer: setAudioSink() 
08-30 16:53:15.496   329  1537 V AwesomePlayer: reset_l() 
08-30 16:53:15.496   329  1537 V AudioCache: notify(0xb54744c0, 8, 0, 0)
08-30 16:53:15.496   329  1537 V AudioCache: ignored
08-30 16:53:15.496   329  1537 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:15.496   329  1537 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 16:53:15.496   329  1537 V AwesomePlayer: setDataSource_l dataSource
08-30 16:53:15.496   329  1537 V LGParserOSAL: SniffLGParser start
08-30 16:53:15.496   329  1537 V LGParserOSAL: MainType:5, SubType=0
08-30 16:53:15.496   329  1537 V LGParserOSAL: #### check Mime : application/ogg
08-30 16:53:15.496   329  1537 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 16:53:15.496   329  1537 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 16:53:15.498  1045  2042 W libprocessgroup: failed to open /acct/uid_10019/pid_5993/cgroup.procs: No such file or directory
08-30 16:53:15.501  3817  3817 D HeadsetService: Received stop request...Stopping profile...
08-30 16:53:15.506  6872  6872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 16:53:15.507  3817  3817 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:53:15.507  3817  3817 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:53:15.507  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.507  3817  3920 D HeadsetStateMachine: Exit Disconnected: -1
08-30 16:53:15.508  6722  6722 D UEI.SmartControl: QS Service created
,08-30 16:53:15.510  1045  1045 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:15.510  1045  1045 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 16:53:15.511  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:15.511  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:15.511  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:15.513  3817  3817 D A2dpService: Received stop request...Stopping profile...
08-30 16:53:15.513  3817  3947 D A2dpStateMachine: Exit Disconnected: -1
08-30 16:53:15.514  3817  3817 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 16:53:15.516  3817  3817 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 16:53:15.516  3817  3817 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:53:15.516  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.518  3817  3890 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 16:53:15.518  3817  3817 D HidService: Received stop request...Stopping profile...
08-30 16:53:15.518  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.519  3817  3817 D HeadsetStateMachine: Unbinding service...
08-30 16:53:15.519  1045  1045 D BluetoothA2dp: Proxy object disconnected
08-30 16:53:15.519  1045  1045 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 16:53:15.521  6872  6872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:53:15.521  3817  3817 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:53:15.521  3817  3817 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:53:15.521  3817  3817 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:53:15.521  3817  3817 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-30 16:53:15.521  6805  6805 D BluetoothInputDevice: Proxy object disconnected
,08-30 16:53:15.521  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 16:53:15.521  3817  3817 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:53:15.521  3817  3817 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:53:15.521  6805  6805 D HidProfile: Bluetooth service disconnected
08-30 16:53:15.521  3817  3817 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:53:15.524  3817  3817 D HealthService: Received stop request...Stopping profile...
,08-30 16:53:15.524  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.527  3817  3817 D PanService: Received stop request...Stopping profile...
08-30 16:53:15.528  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.529  3817  3817 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:53:15.529  6805  6805 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:53:15.529  6805  6805 D PanProfile: Bluetooth service disconnected
08-30 16:53:15.529  3817  3817 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 16:53:15.529  3817  3817 D BtGatt.GattService: stop()
08-30 16:53:15.529  3817  3817 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 16:53:15.530  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.531  3817  3817 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:53:15.531  3817  3817 D BluetoothMapService: stop()
08-30 16:53:15.532  3817  3817 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 16:53:15.532  3817  3817 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 16:53:15.532  3817  3817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ae220f
08-30 16:53:15.533  3817  3817 I BluetoothA2dpServiceJni: cleanupNative
08-30 16:53:15.533  3817  3948 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 16:53:15.533  3817  3817 I GKI_LINUX: GKI_exit_task 2 done
08-30 16:53:15.533  3817  3817 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 16:53:15.533  6805  6805 D BluetoothMap: Proxy object disconnected
08-30 16:53:15.533  6805  6805 D MapProfile: Bluetooth service disconnected
08-30 16:53:15.534  3817  3817 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:53:15.534  3817  3817 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:53:15.534  3817  3817 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:53:15.534  3817  3817 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:53:15.534  3817  3817 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:53:15.534  3817  3817 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:53:15.534  3817  3817 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:53:15.535  3817  3817 V BluetoothMapService: Handler(): got msg=4
08-30 16:53:15.535  3817  3817 D BluetoothMapService: MAP Service closeService in
08-30 16:53:15.535  3817  3817 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:53:15.535  3817  3817 V BluetoothMapService: MAP Service closeService out
08-30 16:53:15.536  3817  3890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 16:53:15.536  3817  3890 D BluetoothAdapterProperties: Setting state to 10
08-30 16:53:15.536  3817  3890 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 16:53:15.536  3817  3817 D BluetoothMapService: cleanup()
08-30 16:53:15.536  3817  3817 D BluetoothMapService: MAP Service closeService in
08-30 16:53:15.536  3817  3817 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:53:15.536  3817  3817 V BluetoothMapService: MAP Service closeService out
08-30 16:53:15.537  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:15.537  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 16:53:15.537  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 16:53:15.539  3817  3890 I BluetoothAdapterState: Entering OffState
08-30 16:53:15.539   329  1537 V LGParserOSAL: supported mime: application/og,g
08-30 16:53:15.539  6805  6823 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:53:15.539   329  1537 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 16:53:15.539   329  1537 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 16:53:15.539   329  1537 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 16:53:15.540   329  1537 V AwesomePlayer: AudioTrack Setting
08-30 16:53:15.540   329  1537 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 16:53:15.540   329  1537 V AwesomePlayer: setAudioSource() 
08-30 16:53:15.540   329  1537 V MediaPlayerService: prepare
08-30 16:53:15.540   329  1537 V AwesomePlayer: prepareAsync_l() 
08-30 16:53:15.540   329  1537 V MediaPlayerService: wait for prepare
08-30 16:53:15.540   329  6951 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 16:53:15.540   329  6951 V AwesomePlayer: initAudioDecoder() 
08-30 16:53:15.540   329  6951 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 16:53:15.540   329  6951 V AudioSystem: isOffloadSupported()
08-30 16:53:15.540   329  6951 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 16:53:15.540   329  6951 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 16:53:15.540   329  6951 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 16:53:15.540   329  6951 V AwesomePlayer: getUseOffload() = 0 
08-30 16:53:15.540   329  6951 V OMXCodec: OMXCodec::Create
08-30 16:53:15.540   329  6951 V OMXCodec: findMatchingCodecs()
08-30 16:53:15.540   329  6951 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 16:53:15.540   329  6951 V OMXCodec: matchingCodecs.size()=1
08-30 16:53:15.540   329  6951 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 16:53:15.541  6722  6722 I UEI.SmartControl: Service initServices...
08-30 16:53:15.541  6722  6722 D UEI.SmartControl: QS start get config
08-30 16:53:15.541  6805  6822 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:53:15.542   329  6951 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 16:53:15.542   329  6951 V LGCodecAdapter: LG Codec Adapter start
,08-30 16:53:15.542   329  6951 V OMXCodec: OMXCodec Createtor
08-30 16:53:15.542   329  6951 V OMXCodec: setComponentRole
08-30 16:53:15.542   329  6951 V OMXCodec: configureCodec protected=0
08-30 16:53:15.542   329  6951 V LGCodecAdapter: called getLGCodecSpecificData
08-30 16:53:15.542   329  6951 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 16:53:15.542   329  6951 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 16:53:15.542   329  6951 V LGCodecOSAL: Called LGconfigureCodecMSG,
08-30 16:53:15.542   329  6951 V LGCodecOSAL: Not support LGCodec
08-30 16:53:15.542   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 16:53:15.542   329  6951 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 16:53:15.542   329  6951 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 16:53:15.542  1045  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:15.542   329  6951 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 16:53:15.543   329  6951 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 16:53:15.543   329  6951 V AudioSystem: isOffloadSupported()
,08-30 16:53:15.543   329  6951 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 16:53:15.543   329  6951 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 16:53:15.543   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 16:53:15.543   329  6951 V OMXCodec: init()
,08-30 16:53:15.543   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 16:53:15.543   329  6951 V OMXCodec: allocateBuffers
08-30 16:53:15.543  6805  6823 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:53:15.543   329  6951 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 16:53:15.543   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f8d0 on input port
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f920 on input port
08-30 16:53:15.544  6805  6822 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f970 on input port
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f9c0 on input port
08-30 16:53:15.544   329  6951 V OMXCodec: allocateBuffersOnPort portIndex=1,
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa10 on output port
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
08-30 16:53:15.544  6872  6872 V LGMDMManager: Create singleton instance
08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb50 on output port
,08-30 16:53:15.544   329  6951 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fc90 on output port
08-30 16:53:15.545   329  6951 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 16:53:15.545  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:15.545  1864  2547 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:15.546  1045  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:53:15.546   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 16:53:15.546   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 16:53:15.546  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:15.546   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 16:53:15.547   329  6951 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-30 16:53:15.547   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 16:53:15.547   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 16:53:15.547   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 16:53:15.547   329  6951 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 16:53:15.547   329  6951 V AwesomePlayer: finishAsyncPrepare_l() 
,08-30 16:53:15.547   329  6951 V AudioCache: notify(0xb54744c0, 5, 0, 0)
08-30 16:53:15.547   329  6951 V AudioCache: ignored
08-30 16:53:15.547   329  6951 V AudioCache: notify(0xb54744c0, 1, 0, 0)
08-30 16:53:15.547   329  6951 V AudioCache: prepared
08-30 16:53:15.547   329  1537 V AudioCache: wait - success,
08-30 16:53:15.547   329  1537 V MediaPlayerService: start
08-30 16:53:15.547   329  1537 V AwesomePlayer: play_l() 
08-30 16:53:15.548   329  1537 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 16:53:15.548   329  1537 V AwesomePlayer: createAudioPlayer_l
,08-30 16:53:15.548   329  1537 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 16:53:15.548  1045  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 16:53:15.548   329  1537 V AwesomePlayer: startAudioPlayer_l() 
08-30 16:53:15.548   329  1537 D AudioPlayer: start of Playback, useOffload 0
08-30 16:53:15.548   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-30 16:53:15.548  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 16:53:15.548   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 16:53:15.550  1045  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 16:53:15.550  1045  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 16:53:15.550  1045  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2dd6c429 mBinding = false
,08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 16:53:15.550  1045  1120 D BluetoothManagerService: Sending unbind request.
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854032
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854192
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854352
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854672
08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 16:53:15.550   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 16:53:15.551   329  6953 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb50 on output port
,08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa10 on output port,
08-30 16:53:15.551  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 16:53:15.551   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000ffb0 on output port,
08-30 16:53:15.552   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 16:53:15.552   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 16:53:15.552   329  1537 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 16:53:15.553   329  1537 V AudioCache: notify(0xb54744c0, 6, 0, 0)
08-30 16:53:15.553   329  1537 V AudioCache: ignored,
08-30 16:53:15.553   329  1537 V MediaPlayerService: wait for playback complete
08-30 16:53:15.554   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.554   329  6954 V AudioCache: memcpy(0xac300000, 0xb57d6000, 4096)
08-30 16:53:15.555   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.555   329  6954 V AudioCache: memcpy(0xac301000, 0xb57d6000, 4096)
08-30 16:53:15.555   329  6954 V AudioCache: write(0xb57d6000, 4096),
08-30 16:53:15.555   329  6954 V AudioCache: memcpy(0xac302000, 0xb57d6000, 4096)
08-30 16:53:15.555   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.555   329  6954 V AudioCache: memcpy(0xac303000, 0xb57d6000, 4096)
08-30 16:53:15.556   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.556   329  6954 V AudioCache: memcpy(0xac304000, 0xb57d6000, 4096),
08-30 16:53:15.557   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.557   329  6954 V AudioCache: memcpy(0xac305000, 0xb57d6000, 4096)
08-30 16:53:15.557   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.557   329  6954 V AudioCache: memcpy(0xac306000, 0xb57d6000, 4096)
08-30 16:53:15.557   329  6954 V AudioCache: write(0xb57d6000, 4096)
,08-30 16:53:15.557   329  6954 V AudioCache: memcpy(0xac307000, 0xb57d6000, 4096)
08-30 16:53:15.557   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.557   329  6954 V AudioCache: memcpy(0xac308000, 0xb57d6000, 4096)
08-30 16:53:15.559   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.559   329  6954 V AudioCache: memcpy(0xac309000, 0xb57d6000, 4096),
08-30 16:53:15.559   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.559   329  6954 V AudioCache: memcpy(0xac30a000, 0xb57d6000, 4096)
08-30 16:53:15.559   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.559   329  6954 V AudioCache: memcpy(0xac30b000, 0xb57d6000, 4096),
08-30 16:53:15.559   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.559   329  6954 V AudioCache: memcpy(0xac30c000, 0xb57d6000, 4096)
08-30 16:53:15.560  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:15.562  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:15.562  1953  2176 D LGBluetoothAPIService: Message: 2
,08-30 16:53:15.563  1953  2176 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@13083c3e mBinding = false
08-30 16:53:15.563  1953  2176 D LGBluetoothAPIService: Sending unbind request.
08-30 16:53:15.563  3817  3894 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 16:53:15.565   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.565   329  6954 V AudioCache: memcpy(0xac30d000, 0xb57d6000, 4096)
,08-30 16:53:15.565   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.565   329  6954 V AudioCache: memcpy(0xac30e000, 0xb57d6000, 4096)
08-30 16:53:15.565   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.565   329  6954 V AudioCache: memcpy(0xac30f000, 0xb57d6000, 4096)
08-30 16:53:15.565   329  6954 V AudioCache: write(0xb57d6000, 4096),
08-30 16:53:15.565   329  6954 V AudioCache: memcpy(0xac310000, 0xb57d6000, 4096)
08-30 16:53:15.566  3817  3817 I GKI_LINUX: GKI_exit_task 1 done
08-30 16:53:15.566  3817  3817 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 16:53:15.566  3817  3817 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 16:53:15.566  3817  3817 I art     : --- WEIRD: removing null entry 246
,08-30 16:53:15.566  3817  3817 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 16:53:15.566  3817  3817 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-30 16:53:15.568  3817  3817 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 16:53:15.568   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.568   329  6954 V AudioCache: memcpy(0xac311000, 0xb57d6000, 4096)
08-30 16:53:15.568   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.568   329  6954 V AudioCache: memcpy(0xac312000, 0xb57d6000, 4096)
08-30 16:53:15.568   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.568   329  6954 V AudioCache: memcpy(0xac313000, 0xb57d6000, 4096)
08-30 16:53:15.568  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:15.568   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: memcpy(0xac314000, 0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: memcpy(0xac315000, 0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: memcpy(0xac316000, 0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.569   329  6954 V AudioCache: memcpy(0xac317000, 0xb57d6000, 4096)
,08-30 16:53:15.570   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.570   329  6954 V AudioCache: memcpy(0xac318000, 0xb57d6000, 4096)
08-30 16:53:15.570   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.570   329  6954 V AudioCache: memcpy(0xac319000, 0xb57d6000, 4096)
08-30 16:53:15.570   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.570   329  6954 V AudioCache: memcpy(0xac31a000, 0xb57d6000, 4096)
08-30 16:53:15.571   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.571   329  6954 V AudioCache: memcpy(0xac31b000, 0xb57d6000, 4096)
08-30 16:53:15.571   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.571   329  6954 V AudioCache: memcpy(0xac31c000, 0xb57d6000, 4096)
08-30 16:53:15.572   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.572   329  6954 V AudioCache: memcpy(0xac31d000, 0xb57d6000, 4096)
08-30 16:53:15.572   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.572   329  6954 V AudioCache: memcpy(0xac31e000, 0xb57d6000, 4096)
08-30 16:53:15.572   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.572   329  6954 V AudioCache: memcpy(0xac31f000, 0xb57d6000, 4096)
08-30 16:53:15.573   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.573   329  6954 V AudioCache: memcpy(0xac320000, 0xb57d6000, 4096)
08-30 16:53:15.573   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.573   329  6954 V AudioCache: memcpy(0xac321000, 0xb57d6000, 4096)
08-30 16:53:15.573   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.573   329  6954 V AudioCache: memcpy(0xac322000, 0xb57d6000, 4096)
08-30 16:53:15.574   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.574   329  6954 V AudioCache: memcpy(0xac323000, 0xb57d6000, 4096)
08-30 16:53:15.574   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.574   329  6954 V AudioCache: memcpy(0xac324000, 0xb57d6000, 4096)
08-30 16:53:15.574   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.574   329  6954 V AudioCache: memcpy(0xac325000, 0xb57d6000, 4096)
08-30 16:53:15.575   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.575   329  6954 V AudioCache: memcpy(0xac326000, 0xb57d6000, 4096)
08-30 16:53:15.575   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.575   329  6954 V AudioCache: memcpy(0xac327000, 0xb57d6000, 4096)
08-30 16:53:15.576   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.576   329  6954 V AudioCache: memcpy(0xac328000, 0xb57d6000, 4096)
08-30 16:53:15.576   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.576   329  6954 V AudioCache: memcpy(0xac329000, 0xb57d6000, 4096)
08-30 16:53:15.576   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.576   329  6954 V AudioCache: memcpy(0xac32a000, 0xb57d6000, 4096)
08-30 16:53:15.577   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.577   329  6954 V AudioCache: memcpy(0xac32b000, 0xb57d6000, 4096)
08-30 16:53:15.577   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.577   329  6954 V AudioCache: memcpy(0xac32c000, 0xb57d6000, 4096)
08-30 16:53:15.579  3817  3817 I art     : System.exit called, status: 0
08-30 16:53:15.579  3817  3817 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 16:53:15.579   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.579   329  6954 V AudioCache: memcpy(0xac32d000, 0xb57d6000, 4096)
08-30 16:53:15.580  6805  6805 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:53:15.580   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.580   329  6954 V AudioCache: memcpy(0xac32e000, 0xb57d6000, 4096)
08-30 16:53:15.580   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.580   329  6954 V AudioCache: memcpy(0xac32f000, 0xb57d6000, 4096)
08-30 16:53:15.580  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 16:53:15.580  680,5  6805 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 16:53:15.580   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.580   329  6954 V AudioCache: memcpy(0xac330000, 0xb57d6000, 4096)
08-30 16:53:15.581   329  6954 V AudioCache: write(0xb57d6000, 4096)
08-30 16:53:15.581   329  6954 V AudioCache: memcpy(0xac331000, 0xb57d6000, 4096)
08-30 16:53:15.581   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 16:53:15.581   329  6954 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 16:53:15.581   329  6954 V AwesomePlayer: postAudioEOS() 
08-30 16:53:15.581   329  6954 V AudioCache: write(0xb57d6000, 280)
08-30 16:53:15.581   329  6954 V AudioCache: memcpy(0xac332000, 0xb57d6000, 280)
08-30 16:53:15.584  1589  1589 D BluetoothAdapter: 232577185: getState() :  mService = null. Returning STATE_OFF
08-30 16:53:15.584  1589  1589 D BluetoothAdapter: 232577185: getState() :  mService = null. Returning STATE_OFF
08-30 16:53:15.584   329  6951 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 16:53:15.584   329  6951 V AwesomePlayer: onStreamDone
08-30 16:53:15.584   329  6951 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 16:53:15.584   329  6951 V AudioCache: notify(0xb54744c0, 2, 0, 0)
08-30 16:53:15.584   329  6951 V AudioCache: playback complete
08-30 16:53:15.584   329  6951 V AwesomePlayer: pause_l() 
08-30 16:53:15.584   329  6951 V AudioCache: notify(0xb54744c0, 7, 0, 0)
08-30 16:53:15.584   329  6951 V AudioCache: ignored
08-30 16:53:15.584   329  6951 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:15.584   329  1537 V AudioCache: wait - success
08-30 16:53:15.584   329  1537 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 16:53:15.585   329  6951 D AudioPlayer: Pause Playback at 1068125
08-30 16:53:15.585   329  1537 V AwesomePlayer: reset_l() 
08-30 16:53:15.585   329  1537 V AudioCache: notify(0xb54744c0, 8, 0, 0)
08-30 16:53:15.585   329  1537 V AudioCache: ignored
08-30 16:53:15.585   329  1537 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:15.585   329  1537 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 16:53:15.585   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 16:53:15.585   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 16:53:15.585   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 16:53:15.585   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f9c0 on port 0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f970 on port 0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f920 on port 0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f8d0 on port 0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000ffb0 on port 1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portInd,ex=1,bufIndex=3
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fa10 on port 1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fab0 on port 1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fb50 on port 1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 16:53:15.586   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 16:53:15.586   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 16:53:15.586   329  6953 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 16:53:15.586   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 16:53:15.587   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 16:53:15.587   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 16:53:15.587  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:15.587   329  1537 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 16:53:15.587   329  1537 D AudioPlayer: AudioPlayer releasing audio source
08-30 16:53:15.587   329  1537 D AudioPlayer: AudioPlayer done releasing audio source
08-30 16:53:15.587   329  1537 V AwesomePlayer: reset_l() 
08-30 16:53:15.587   329  1537 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:15.587   329  1537 V AwesomePlayer: ~AwesomePlayer call
08-30 16:53:15.588   329  1537 V AwesomePlayer: reset_l() 
08-30 16:53:15.588   329  1537 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:15.588  6872  6949 V SoundPool: close(32)
08-30 16:53:15.588  6872  6949 V SoundPool: pointer = 0x9fe7f000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 16:53:15.589  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:53:15.593  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 16:53:15.601   329  1382 V AudioFlinger: 3817 died, releasing its sessions
08-30 16:53:15.601   329  1382 V AudioFlinger:  pid 1864 @ 0
08-30 16:53:15.601   329  1382 V AudioFlinger:  pid 3317 @ 1
08-30 16:53:15.601   329  1382 V AudioFlinger:  pid 3317 @ 2
08-30 16:53:15.602  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 16:53:15.634  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 16:53:15.634  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 16:53:15.787  1045  1728 I ActivityManager: Process com.android.bluetooth (pid 3817) has died
08-30 16:53:15.787  1045  1728 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 16:53:15.791  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:53:15.805  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5890
,08-30 16:53:15.817  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 16:53:15.820  6722  6722 I UEI.SmartControl: Supports setup maps: true
08-30 16:53:15.821  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 16:53:15.821  6805  6805 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 16:53:15.822  6722  6722 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 16:53:15.822  6722  6722 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 16:53:15.822  6722  6722 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 16:53:15.822  6722  6722 I UEI.SmartControl: ### init IR Blaster...
08-30 16:53:15.825  6722  6722 D serial_port: Configuring serial port
08-30 16:53:15.826  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:53:15.826  6722  6722 E UEI.SmartControl: UEIBLaster setting for 616
08-30 16:53:15.826  6722  6722 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 16:53:15.826  6722  6722 I UEI.SmartControl: configuring settings for MAXQ616
08-30 16:53:15.826  6722  6722 I UEI.SmartControl: Get version...
08-30 16:53:15.843  6722  6958 D UEI.SmartControl: serial port data available: 21
,08-30 16:53:15.872  6722  6722 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 16:53:15.872  6722  6722 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 16:53:15.873  6722  6722 I UEI.SmartControl: QS saving settings...
08-30 16:53:15.874  6722  6722 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 16:53:15.891  6722  6958 D UEI.SmartControl: serial port data available: 4
,08-30 16:53:15.897  1045  2012 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6963 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-30 16:53:15.922  6722  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 16:53:15.925  6722  6722 E UEI.SmartControl: Services init done
08-30 16:53:15.925  6722  6722 D UEI.SmartControl: QS Service init finished
08-30 16:53:15.928  6722  6722 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 16:53:15.928  6722  6722 D UEI.SmartControl: QS Service version code: 201091
08-30 16:53:15.928  6722  6722 D UEI.SmartControl: Service requested: Control
08-30 16:53:15.930  6872  6872 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 16:53:15.931  6722  6738 I UEI.SmartControl: ------ IControl API: 11
08-30 16:53:15.931  6722  6738 D UEI.SmartControl: File observer start...
08-30 16:53:15.931  6722  6978 I UEI.SmartControl: Device manager: loading config....
08-30 16:53:15.931  6722  6738 E UEI.SmartControl: IR Port is disabled: false
08-30 16:53:15.931  6722  6738 D UEI.SmartControl: Starting file observer...
08-30 16:53:15.932  6722  6738 I UEI.SmartControl: Registering callback...
08-30 16:53:15.933  6722  6737 I UEI.SmartControl: ------ IControl API: 19
08-30 16:53:15.934  6722  6737 I UEI.SmartControl: Registering Services Ready callback...
,08-30 16:53:15.935  6722  6722 D UEI.SmartControl: Internal service binding...
08-30 16:53:15.947  6722  6978 D UEI.SmartControl: ----------- loading internal config...
,08-30 16:53:15.958  6722  6978 E UEI.SmartControl: Loading SETTINGS...
08-30 16:53:15.971  6722  6978 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 16:53:15.982  6963  6963 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 16:53:15.983  6963  6963 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:15.983  6963  6963 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 16:53:15.984  6963  6963 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 16:53:15.984  6722  6975 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 16:53:15.986  6872  6888 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 16:53:15.987  6722  6975 D UEI.SmartControl: -----service ready thread exits
08-30 16:53:15.987  6872  6947 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,08-30 16:53:15.987  6872  6947 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 16:53:15.987  6872  6872 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 16:53:15.988  6872  6872 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 16:53:15.988  6722  6738 I UEI.SmartControl: ------ IControl API: 8
08-30 16:53:15.993  6872  6872 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 16:53:15.993  6872  6872 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 16:53:15.994  6872  6872 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 16:53:15.995  6872  6872 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 16:53:15.996  6872  6872 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 16:53:15.996  6872  6872 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 16:53:15.999  6872  6872 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 16:53:16.004  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 16:53:16.004  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 16:53:16.007  6872  6872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:53:16.007  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 16:53:16.008  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 16:53:16.009  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 16:53:16.010  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 16:53:16.011  6872  6872 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472568796010]
,08-30 16:53:16.013  6872  6872 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 16:53:16.017  1045  1735 I ActivityManager: Killing 6498:com.lge.email/u0a23 (adj 15): empty #17
,08-30 16:53:16.019  6963  6963 D BluetoothAdapterApp: Loading JNI Library
08-30 16:53:16.042  6872  6984 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 16:53:16.060  6963  6963 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@6be1704 Instance Count = 1
,08-30 16:53:16.066  1045  2012 W libprocessgroup: failed to open /acct/uid_10023/pid_6498/cgroup.procs: No such file or directory
08-30 16:53:16.072  6963  6963 D BluetoothAdapterApp: onCreate
08-30 16:53:16.072  6872  6872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 16:53:16.073  6872  6872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 16:53:16.073  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 16:53:16.073  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 16:53:16.074  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 16:53:16.075  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 16:53:16.075  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-30 16:53:16.084  6872  6872 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 16:53:16.094  6963  6963 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 16:53:16.094  6963  6963 D ProfileConfigQcom: Adding HeadsetService
08-30 16:53:16.094  6963  6963 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 16:53:16.094  6963  6963 D ProfileConfigQcom: Adding A2dpService
08-30 16:53:16.095  6963  6963 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 16:53:16.095  6963  6963 D ProfileConfigQcom: Adding HidService
08-30 16:53:16.095  6963  6963 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 16:53:16.095  6963  6963 D ProfileConfigQcom: Adding HealthService
08-30 16:53:16.096  6963  6963 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 16:53:16.096  6963  6963 D ProfileConfigQcom: [BTUI] PanService is supported
,08-30 16:53:16.096  6963  6963 D ProfileConfigQcom: Adding PanService
,08-30 16:53:16.097  6963  6963 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 16:53:16.097  6963  6963 D ProfileConfigQcom: Adding GattService
08-30 16:53:16.097  6963  6963 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 16:53:16.097  6963  6963 D ProfileConfigQcom: Adding BluetoothMapService
08-30 16:53:16.098  6963  6963 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 16:53:16.099  6963  6963 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 16:53:16.103  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 16:53:16.105  6963  6963 V LGMDMManagerInternal: Create singleton instance
08-30 16:53:16.184  6963  6963 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:53:16.188  6963  6963 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:16.189  6963  6963 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:16.189  6963  6963 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:16.193  6963  6963 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:16.193  6963  6963 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-30 16:53:16.203  6891  6891 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 16:53:16.205  1045  2012 I ActivityManager: Killing 6016:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-30 16:53:16.236  1045  1919 W libprocessgroup: failed to open /acct/uid_10027/pid_6016/cgroup.procs: No such file or directory
,08-30 16:53:16.485  1045  1363 V AlarmManager: RTC_WAKEUP set : Alarm{2e6e5140 type 0 when 1472568793680 com.android.vending} when 1472568793680
,08-30 16:53:16.550  1045  2079 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:53:16.688  6041  6041 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 16:53:17.288  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:17.302  1045  1120 D Tethering: MasterInitialState.processMessage what=3
08-30 16:53:17.318  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:17.323  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:17.325  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:17.329  1045  1120 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:53:17.336  1045  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:17.343  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:17.344  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:17.344  1045  1060 D WifiServiceImplEx: setWifiEnabled: true pid=6600, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:53:17.345  1045  1060 D WifiService: setWifiEnabled: true pid=6600, uid=10118
08-30 16:53:17.345  1045  1060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:53:17.348  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 16:53:17.360  1045  1424 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 16:53:17.360  1045  1424 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 16:53:17.362  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:17.363  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:17.363  1045  1045 D Ulp_jni : JNI:system_update. Event-4
08-30 16:53:17.364  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): pid[1045] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 16:53:17.364  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:53:17.364  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): pid[1045] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 16:53:17.365  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:53:17.365  1045  1424 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 16:53:17.365  1045  1424 E WifiHW  : unknown target_country: EU , set to default
08-30 16:53:17.365  1045  1424 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 16:53:17.365  1045  1424 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 16:53:17.365  1045  1424 I WifiUtil: gEnableBmps=1
08-30 16:53:17.375  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 16:53:17.384  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 16:53:17.388  6403  6430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 16:53:17.414  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:17.454  1045  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:17.485  1045  2011 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7010 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 16:53:17.487  1045  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:17.487  1045  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 16:53:17.559  7010  7010 I AppUp4:AppBoxCP: onCreate
08-30 16:53:17.560  7010  7010 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 16:53:17.571  7010  7010 I AppUp4:DB:  setFingerPrint start
08-30 16:53:17.571  7010  7010 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 16:53:17.582  7010  7010 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-30 16:53:17.582  7010  7010 I AppUp4:DB:  SDK version = 21
08-30 16:53:17.582  7010  7010 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 16:53:17.584  7010  7010 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 16:53:17.585  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:53:17.585  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:17.589  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:53:17.589  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 16:53:17.596  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 16:53:17.640  7010  7010 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:17.640  7010  7010 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:17.648  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e45db6e
,08-30 16:53:17.648  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:53:17.648  7010  7010 D AppUp4:CustFacade: isPhone : true
08-30 16:53:17.649  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:53:17.649  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 16:53:17.650  7010  7010 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 16:53:17.650  7010  7028 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 16:53:17.651  7010  7028 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 16:53:17.651  7010  7028 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 16:53:17.654  1045  1642 I ActivityManager: Killing 6534:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 16:53:17.713  1045  1563 W libprocessgroup: failed to open /acct/uid_10061/pid_6534/cgroup.procs: No such file or directory
08-30 16:53:17.715  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:17.715  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 16:53:17.722  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:17.728  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 16:53:17.736  4294  7032 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:17.741  4294  7033 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:17.741  4294  7033 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:53:17.793  1045  1952 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7037 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 16:53:17.866  7037  7037 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 16:53:17.867  7037  7037 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:17.869  7037  7037 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 16:53:17.870  7037  7037 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:53:17.962  7037  7037 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 16:53:17.979  7037  7037 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 16:53:18.038  7037  7037 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 16:53:18.078  7037  7037 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 16:53:18.078  7037  7037 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:18.128   325   889 D SoftapController: Softap fwReload - Ok
08-30 16:53:18.131  1045  1424 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (761ms)
,08-30 16:53:18.134   325   889 D CommandListener: Setting iface cfg
08-30 16:53:18.134   325   889 D CommandListener: Trying to bring down wlan0
08-30 16:53:18.135   325   889 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:53:18.138  1045  1424 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 16:53:18.140  1045  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:53:18.140  1045  1120 D Tethering: InitialState.processMessage what=4
08-30 16:53:18.130  7063  7063 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:18.130  7063  7063 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 16:53:18.156  1045  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 16:53:18.171  7063  7063 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 16:53:18.204  7063  7063 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:53:18.204  7063  7063 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 16:53:18.238  7037  7037 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 16:53:18.239  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:18.239  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:18.239  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 16:53:18.243  1045  1424 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 16:53:18.243  1045  1424 D WifiMonitor: connecting to supplicant
08-30 16:53:18.245  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 16:53:18.245  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 16:53:18.245  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:18.247  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:18.247  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:18.284  7037  7037 I HubEmail: JNI_OnLoad()
08-30 16:53:18.284  7037  7037 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 16:53:18.284  7037  7037 I HubEmail: registerNatives()
,08-30 16:53:18.284  7037  7037 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 16:53:18.284  7037  7037 I HubEmail: registerNativeMethods()
08-30 16:53:18.284  7037  7037 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 16:53:18.284  7037  7037 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-30 16:53:18.286  7063  7063 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 16:53:18.289  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:53:18.289  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:18.289  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 16:53:18.300  7063  7063 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 16:53:18.307  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:53:18.307  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 16:53:18.308  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:53:18.308  1045  1424 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:53:18.309  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:18.309  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:18.309  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:18.310  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:18.310  1045  1424 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 16:53:18.310  1045  1424 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 16:53:18.311  1045  1424 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 16:53:18.311  1045  1424 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 16:53:18.312  1045  1424 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 16:53:18.323  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-30 16:53:18.323  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 16:53:18.323  1045  7077 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:53:18.329  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 16:53:18.329  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:53:18.329  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 16:53:18.329  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 16:53:18.329  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 16:53:18.330  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:53:18.330  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:53:18.331  1045  1061 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7078 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-30 16:53:18.334  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:18.334  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:18.334  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:53:18.334  1045  1424 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 16:53:18.334  1045  1424 D WifiNative-wlan0: SET update_config 1: returned true
,08-30 16:53:18.335  1045  1424 D WifiConfigStore: Loading config and enabling all networks 
08-30 16:53:18.335  1045  1424 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 16:53:18.335  1045  1424 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 16:53:18.338  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.338  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.338  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.338  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.338  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:18.340  1953  1953 D WfdService: Waiting for WifiP2p enabling
08-30 16:53:18.340  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:18.341  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:18.341  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:18.341  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:18.341  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:18.341  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 16:53:18.342  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:18.342  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:18.342  6600  6600 W org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:18.342  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:18.342  1045  1454 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 16:53:18.344  6911  7073 W FormManager: Network not available. Please check & try again.
08-30 16:53:18.350  7037  7076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.351  1045  1424 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 16:53:18.353  6911  7074 V FormManager: Network unavailable.
,08-30 16:53:18.356  6911  7074 V FormManager: Network unavailable.
08-30 16:53:18.361  1045  1943 I ActivityManager: Killing 6079:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 16:53:18.367  1045  1424 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 16:53:18.367  1045  1424 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 16:53:18.398  1045  1424 D WifiStateMachine: enableVerboseLogging : level 2
08-30 16:53:18.398  1045  1424 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 16:53:18.398  1045  2042 W libprocessgroup: failed to open /acct/uid_10080/pid_6079/cgroup.procs: No such file or directory
,08-30 16:53:18.399  1045  1424 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 16:53:18.399  1045  1424 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 16:53:18.400  1045  1424 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 16:53:18.400  1045  1424 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 16:53:18.400  1045  1424 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 16:53:18.400  1045  1424 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 16:53:18.401  1045  1424 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-30 16:53:18.401  1045  1424 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 16:53:18.401  1045  1424 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 16:53:18.401  1045  1424 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 16:53:18.402  1045  1424 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 16:53:18.402  1045  1424 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 16:53:18.402  1045  1424 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 16:53:18.404  1045  1424 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:53:18.404  1045  1424 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 16:53:18.404  1953  1953 D WfdsService: Supplicant Connection state is changed : true
08-30 16:53:18.404  1953  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 16:53:18.404  1953  2345 D WfdsService: Set the WFDS Monitor: true
08-30 16:53:18.404  1953  2345 D WfdsMonitor: WfdsMonitorThread create
08-30 16:53:18.404  1045  1424 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 16:53:18.405  1045  1424 D WifiNative-HAL: Setting external_sim to 1
08-30 16:53:18.405  1045  1424 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 16:53:18.405  1953  2345 D WfdsMonitor: WFDS Monitor is created and started
08-30 16:53:18.405  1953  2345 D WfdsService: WiFi: Supplicant connection re-established
08-30 16:53:18.405  1045  1424 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 16:53:18.405  1045  1424 I WifiNative-HAL: startHal
08-30 16:53:18.405  1045  1424 D wifi    : setting scan oui 0x9541bbe0
08-30 16:53:18.406  1045  1424 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:53:18.406  1045  1424 I WifiNative-HAL: startHal
08-30 16:53:18.406  1045  1424 D wifi    : setting scan oui 0x9541bbe0
08-30 16:53:18.406  1045  1424 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 16:53:18.406  1953  7095 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 16:53:18.407  1953  7095 E CtrlSupplicant: Succeed to open control connection
08-30 16:53:18.407  1045  1424 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 16:53:18.407  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 16:53:18.407  1953  7095 E CtrlSupplicant: Succeed to open monitor connection
08-30 16:53:18.407  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 16:53:18.407  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 16:53:18.407  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:53:18.408  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:53:18.408  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:53:18.408  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 16:53:18.408  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 16:53:18.408  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 16:53:18.408  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:53:18.408  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:53:18.408  1953  7095 D WfdsMonitor: Supplicant connection established
08-30 16:53:18.409  1953  2345 D WfdsService: Connected to the supplicant for wfds
08-30 16:53:18.409  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:53:18.409  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:53:18.409  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:53:18.409  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:53:18.409  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 16:53:18.409  7063  7063 I wpa_supplicant: android_multicast_filter_startstop : multicast filter ,set
08-30 16:53:18.410  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 16:53:18.410  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:53:18.410  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:53:18.410  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:53:18.411  1045  1424 E WifiNative: : [119,881,701 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 16:53:18.411  1045  1424 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 16:53:18.411  1045  1424 D WifiNative-wlan0: RECONNECT: returned true
08-30 16:53:18.411  1045  1424 D WifiNative-wlan0: doString: [STATUS]
08-30 16:53:18.412  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:53:18.412  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 16:53:18.412  1045  1424 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:53:18.412  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:18.412  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:18.412  1045  1375 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.413  1045  1424 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:53:18.413  1045  1045 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 16:53:18.414  1045  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.414  1045  1543 I WifiNative-HAL: startHal
08-30 16:53:18.414  1045  1543 D wifi    : getting scan capabilities on interface[1] = 0x9541bbe0
08-30 16:53:18.414  1045  1543 D wifi    : failed to get capabilities : -3
08-30 16:53:18.414  1045  1543 E WifiScanningService: could not get scan capabilities
08-30 16:53:18.414  1045  1424 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 16:53:18.414  1045  1045 D RttService: SCAN_AVAILABLE : 3
08-30 16:53:18.414  1045  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.414   325   889 D CommandListener: Setting iface cfg
08-30 16:53:18.414   325   889 D CommandListener: Trying to bring up p2p0
08-30 16:53:18.414  1045  1424 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 16:53:18.414  1045  1375 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:53:18.414  1045  1375 D LGWifiP2pService: P2pEnablingState
08-30 16:53:18.414  1045  1375 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.414  1045  1375 D LGWifiP2pService: P2p socket connection successful
08-30 16:53:18.414  1045  1375 D LGWifiP2pService: P2pEnabledState
08-30 16:53:18.414  1045  1424 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 16:53:18.415  1045  1375 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 16:53:18.415  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=119886  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:53:18.415  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 16:53:18.415  1953  1953 D WfdsService: WifiP2pState is changed : true
08-30 16:53:18.415  1953  2345 D WfdsService: Receive the WFDS_ENABLE Method
08-30 16:53:18.416  1953  2345 D WfdsService: Set the WFDS Monitor: true
08-30 16:53:18.416  1953  2345 D WfdsService: Connected to the supplicant for wfds
08-30 16:53:18.416  1953  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 16:53:18.416  7063  7063 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 16:53:18.416  1953  2345 D WfdsService: selectPreferredScanChannel [36]
08-30 16:53:18.416  1953  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 16:53:18.417  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=119888  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:53:18.417  1045  1424 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 16:53:18.418  1045  1424 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 16:53:18.418  1045  1424 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 16:53:18.418  1045  1424 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 16:53:18.418  7063  7063 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 16:53:18.419  1953  1953 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 16:53:18.419  1045  1424 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 16:53:18.419  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:18.420  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:18.420  1045  1424 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 16:53:18.420  1953  1953 D WfdsService: isConnected: false
08-30 16:53:18.420  1045  1424 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 16:53:18.420  1045  1424 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 16:53:18.420  7063  7063 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 16:53:18.420  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.420  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.421  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:53:18.421  1045  1375 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 16:53:18.421  1045  1424 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 16:53:18.421  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:18.421  1045  1424 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 16:53:18.421  1045  1424 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 16:53:18.421  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 16:53:18.422  1045  1375 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 16:53:18.422  1045  1375 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 16:53:18.423  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 16:53:18.423  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.424  7063  7063 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:53:18.424  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.425  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.425  1953  7095 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.425  1953  7095 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.426  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:53:18.426  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.426  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.426  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.426  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.426  1045  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.426  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.426  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.426  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.426  1045  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.426  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.426  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.427  1045  1424 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 16:53:18.427  1045  1375 D WifiNative-p2p0: SET device_name G3: returned true
08-30 16:53:18.427  1045  1375 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 16:53:18.427  1045  1375 D LGWifiP2pService: before postfix = G3
08-30 16:53:18.427  1045  1375 D WifiServerServiceExt: postfix byte check : 2
08-30 16:53:18.427  1045  1375 D LGWifiP2pService: after postfix = G3
08-30 16:53:18.427  1045  1375 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 16:53:18.427  1045  1424 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:53:18.428  1045  1375 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 16:53:18.428  1045  1375 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 16:53:18.428  1045  1375 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 16:53:18.428  1045  1375 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 16:53:18.428  1045  1424 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:53:18.428  1045  1424 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:53:18.428  1045  1375 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 16:53:18.428  1045  1375 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 16:53:18.428  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 16:53:18.429  1045  1375 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 16:53:18.429  1045  1375 D WifiNative-HAL: p2pGetDeviceAddress
08-30 16:53:18.429  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 16:53:18.429  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:18.429  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 16:53:18.429  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:18.429  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:18.429  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:18.430  1045  1424 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 16:53:18.430  1045  1424 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 16:53:18.431  1045  1424 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 16:53:18.431  1045  1424 D WifiNative-wlan0: doBoolean: SCAN
08-30 16:53:18.431  1045  1424 D WifiNative-wlan0: SCAN: returned false
08-30 16:53:18.432  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=119903  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:53:18.432  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=119904  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:53:18.433  1045  1375 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 16:53:18.434  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.434  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:18.434  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:53:18.434  1045  1375 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 16:53:18.434  1045  1375 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 16:53:18.435  1045  1375 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 16:53:18.435  1045  1375 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 16:53:18.435  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:18.435  1045  1045 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 16:53:18.435  1045  1375 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 16:53:18.435  1045  1375 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 16:53:18.435  1045  1375 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 16:53:18.435  1045  1375 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-30 16:53:18.437  1045  1424 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:18.437  1045  1424 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:18.439  1953  1953 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 16:53:18.439  1953  1953 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 16:53:18.439  1953  1953 D WfdsService: Update P2p Interface State: 3
08-30 16:53:18.442  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:18.442  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:18.443  1045  1424 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:18.443  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:18.443  1045  1424 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:18.443  1045  1424 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:18.444  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:18.444  1045  1045 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 16:53:18.445  1045  1375 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 16:53:18.445  1045  1375 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 16:53:18.445  1045  1375 D LGWifiP2pService: InactiveState
08-30 16:53:18.445  1045  1375 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.445  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.445  1045  1375 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 16:53:18.446  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 16:53:18.446  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.447  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:53:18.447  1953  7095 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:53:18.447  1045  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.447  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.447  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:18.447  7063  7063 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:53:18.447  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.447  1953  7095 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.447  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.447  1045  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.447  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.447  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.448  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.448  1953  7095 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.448  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:18.448  1045  7077 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.448  1045  7077 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.448  1045  7077 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:18.449  1045  1375 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.449  1045  1375 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1375 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1375 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:18.450  1045  1045 E WifiServerServiceExt: No p2p device connected
08-30 16:53:18.451  1953  2345 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 16:53:18.465  7078  7078 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:18.465  7078  7078 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:53:18.467  7078  7078 D PhoneMonitor: Register our PhoneStateListener
08-30 16:53:18.478  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:53:18.480  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 16:53:18.491  7078  7078 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 16:53:18.491  7078  7078 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 16:53:18.492  7078  7078 D TelephonyAutoProfiling: [parse] Load xml
08-30 16:53:18.495  7078  7078 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 16:53:18.495  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 16:53:18.496  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 16:53:18.496  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 16:53:18.496  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 16:53:18.496  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 16:53:18.496  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 16:53:18.496  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 16:53:18.496  7078  7078 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-30 16:53:18.506  7078  7078 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 16:53:18.523  1045  2042 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7098 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 16:53:18.524  1045  2042 I ActivityManager: Killing 6109:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 16:53:18.639  1045  1728 W libprocessgroup: failed to open /acct/uid_10097/pid_6109/cgroup.procs: No such file or directory
,08-30 16:53:18.952  7063  7063 E wpa_supplicant: USIM:  scard_init function
08-30 16:53:18.953  7063  7063 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 16:53:18.955  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 16:53:18.955  1045  7077 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 16:53:18.955  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 16:53:18.955  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-30 16:53:18.955  1045  7077 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 16:53:18.955  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:53:18.955  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 16:53:18.956  1045  1424 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 16:53:18.956  1045  1424 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-30 16:53:18.962  1045  1424 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 16:53:18.962  1045  1424 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 16:53:18.962  1045  1424 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 16:53:18.990  1045  1728 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7125 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 16:53:18.994  1045  1728 I ActivityManager: Killing 6659:com.lge.eula/1000 (adj 15): empty #17
08-30 16:53:19.083  7063  7063 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:53:19.091  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 16:53:19.091  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 16:53:19.091  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 16:53:19.091  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 16:53:19.091  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:19.092  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:19.094  7063  7063 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:53:19.094  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:53:19.099  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:19.099  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:19.099  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 16:53:19.099  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:53:19.099  1045  7077 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:53:19.099  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 16:53:19.099  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:53:19.099  1045  7077 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 16:53:19.103  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:19.106  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:19.109  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120580  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 16:53:19.116  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120587  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 16:53:19.122  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=120593  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:53:19.122  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=120594  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:53:19.123  1045  1424 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120594
08-30 16:53:19.123  1045  1424 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120595
08-30 16:53:19.124  1045  1424 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120595
08-30 16:53:19.124  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120595
08-30 16:53:19.124  1045  1424 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120596
08-30 16:53:19.125  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=120596  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 16:53:19.127  1045  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_6659/cgroup.procs: No such file or directory
08-30 16:53:19.130  1045  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:53:19.138  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.138  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:19.140  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.142  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.142  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.143  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 16:53:19.167  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.167  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.167  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 16:53:19.170  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.170  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:19.172  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=120643  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 16:53:19.173  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=120644  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:53:19.173  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=120644  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:53:19.174  1045  1424 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120645
08-30 16:53:19.174  1045  1424 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120645
08-30 16:53:19.175  1045  1424 D WifiNative-wlan0: doString: [STATUS]
08-30 16:53:19.175  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:19.176  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:19.178  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.178  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.178  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 16:53:19.179  1045  1424 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:53:19.181  1045  1424 I WifiServiceExtension: setVHTCapabilityType  : false
,08-30 16:53:19.191  1045  1424 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 16:53:19.191  1045  1424 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 16:53:19.192  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:53:19.203  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.203  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.203  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:53:19.204  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.204  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.204  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 16:53:19.211  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.211  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:19.215  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.220  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.220  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:53:19.226  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.228  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.228  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:19.231  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.233  1045  1424 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 16:53:19.233  1045  1424 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:53:19.233  1045  1424 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 16:53:19.236  1045  1505 D ConnectivityService: Got NetworkAgent Messenger
08-30 16:53:19.236  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 16:53:19.236  1045  1505 D ConnectivityService: NetworkAgent connected
08-30 16:53:19.237  1045  1424 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:53:19.237  1045  1424 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:53:19.243  1045  1424 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:53:19.243  1045  1424 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:53:19.243  1045  1424 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:53:19.254  1045  1424 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:53:19.254  1045  1424 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 16:53:19.259  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.259  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.259  1045  1375 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.261  1045  1424 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:53:19.263   325   889 D CommandListener: Setting iface cfg
08-30 16:53:19.268  1045  1424 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 16:53:19.268  1045  7156 D DhcpStateMachine: StoppedState
08-30 16:53:19.268  1045  7156 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.268  1045  7156 D DhcpStateMachine: WaitBeforeStartState
08-30 16:53:19.268  1045  1424 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:19.269  1045  1424 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120740  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:19.269  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120740  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 16:53:19.271  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:19.271  1045  1045 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 16:53:19.272  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:19.272  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:19.272  1045  1045 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 16:53:19.272  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:19.273  1045  1424 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:19.273  1045  1424 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:19.274  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:19.274  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:19.275  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:19.275  1045  1045 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 16:53:19.276  1045  1424 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=120747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:19.276  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:19.276  1045  1045 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 16:53:19.276  1045  1424 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=120748  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:19.277  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=120748  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:19.278  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:74673] from screen [on:0 period:-604983250] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 16:53:19.279  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-604983249] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 16:53:19.279  1045  1424 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 16:53:19.283  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.284  1045  1505 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 16:53:19.284  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.284  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.285  1045  1424 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.285  1045  1424 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.286  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.286  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.286  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-30 16:53:19.291  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=116,0,0
08-30 16:53:19.291  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=116,0,0
08-30 16:53:19.292  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 16:53:19.292  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 16:53:19.294  1045  1424 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 16:53:19.294  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 16:53:19.294  1045  1424 D WifiNative-wlan0: SET ps 0: returned true
08-30 16:53:19.294  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 16:53:19.295  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 16:53:19.295  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 16:53:19.295  1045  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2690847e target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.295  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2690847e target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.295  1045  7156 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.295  1045  7156 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 16:53:19.296  1045  1424 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 16:53:19.296  1045  1424 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:53:19.297  1045  1424 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:53:19.298   325   889 D CommandListener: Setting iface cfg
08-30 16:53:19.298   325   889 D CommandListener: Trying to bring up wlan0
,08-30 16:53:19.299  1045  1424 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 16:53:19.300  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:53:19.300  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:53:19.300  1045  1424 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:53:19.301  1045  1424 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:53:19.301  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:53:19.302  1045  1424 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:53:19.332  1045  1919 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7161 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:53:19.333  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.334  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.334  1045  1424 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.334  1045  1424 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.335  1045  1919 I ActivityManager: Killing 6679:com.lge.bnr/1000 (adj 15): empty #17
08-30 16:53:19.335  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.335  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:19.335  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 16:53:19.336  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:53:19.336  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:53:19.336  1045  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.336  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.336  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:53:19.336  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:53:19.337  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:53:19.337  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 16:53:19.337  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 16:53:19.337  1045  1424 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 16:53:19.337  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:19.353  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:19.353  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-30 16:53:19.354  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:53:19.354  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:53:19.354  1045  1424 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 16:53:19.355  1045  1505 D ConnectivityService: ignoring duplicate network state non-change
08-30 16:53:19.400  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:19.400  1045  1045 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:53:19.402  1045  1642 W libprocessgroup: failed to open /acct/uid_1000/pid_6679/cgroup.procs: No such file or directory
,08-30 16:53:19.417  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:53:19.418  1045  1505 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 16:53:19.423  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.423  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.424  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:53:19.424  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.424  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:19.425  1045  1424 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 16:53:19.428  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.431  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.431  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.431  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:53:19.435  1045  1045 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 16:53:19.438  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 16:53:19.438  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.438  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.438  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:53:19.440  1045  1045 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:53:19.444  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.445  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:19.445  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:53:19.447  1045  1505 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 16:53:19.447  1045  1505 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 16:53:19.448  1045  1505 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 16:53:19.449   325   889 E Netd    : netlink response contains error (File exists)
08-30 16:53:19.449  1045  1505 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 16:53:19.449  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.449  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:19.449  1045  1505 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 16:53:19.450  1045  1505 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 16:53:19.450  1045  1505 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 16:53:19.450  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.450  1045  1505 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:53:19.450  1045  1505 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 16:53:19.450  1045  1505 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 16:53:19.450  1045  1505 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 16:53:19.451  1045  1505 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:19.451  1045  1505 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:19.451  1045  1505 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:53:19.451  1045  1505 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:19.451  1045  1505 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 16:53:19.451  1045  1505 D ConnectivityService: currentScore = 0, newScore = 20
08-30 16:53:19.451  1045  1505 D ConnectivityService:    accepting network in place of null
08-30 16:53:19.451  1045  1505 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:19.451  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.451  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 16:53:19.451  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:19.451  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 16:53:19.452  1045  1505 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBa,ndwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 16:53:19.452  1045  1505 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 16:53:19.452  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:53:19.453  1045  1505 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:19.453  1045  1505 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 16:53:19.454  1045  1424 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:19.454  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:19.454  1045  1505 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 16:53:19.454  1045  1424 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:19.454  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:53:19.454  1045  1505 D ConnectivityService: validation of new default Network = false
08-30 16:53:19.454  1045  1505 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 16:53:19.454  1045  1505 D DSQN    : enableDataServiceNotify 
08-30 16:53:19.454  1045  1505 D DSQN    : start dsqn bin
08-30 16:53:19.456  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.456  1045  1045 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 16:53:19.456  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:53:19.456  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.456  1045  1045 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:53:19.456  1045  1045 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:53:19.456  1045  1045 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:53:19.457   325  7182 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 16:53:19.457   325  7182 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 16:53:19.458  1045  1505 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 16:53:19.459  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:19.459  1045  1,505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:19.450  7183  7183 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:19.450  7183  7183 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:19.462  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:19.462  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:53:19.462  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.463  1045  1505 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:19.465  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:53:19.474  7183  7183 E DSQN    : DSQN ssw
08-30 16:53:19.477  1045  1374 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 16:53:19.489  1823  7187 I CheckinService: active receiver: enabled
08-30 16:53:19.496  1823  7187 I CheckinService: Preparing to send checkin request
08-30 16:53:19.496  1823  7187 I EventLogService: Accumulating logs since 1472568735608
08-30 16:53:19.497  1045  7156 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 16:53:19.497  1045  7156 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 16:53:19.497  1045  7156 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 16:53:19.490  7188  7188 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:19.490  7188  7188 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:19.502  7161  7161 I art     : Almond Protected OAT
08-30 16:53:19.503  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:53:19.504  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.505  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:19.506  7188  7188 I dhcpcd  : version 5.5.6 starting
08-30 16:53:19.508  7188  7188 E dhcpcd  : get_duid: m
08-30 16:53:19.508  7188  7188 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 16:53:19.508  7188  7188 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 16:53:19.537  1823  7187 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 16:53:19.545  7188  7188 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 16:53:19.545  7188  7188 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 16:53:19.545  7188  7188 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:53:19.545  7188  7188 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 16:53:19.545  7188  7188 D dhcpcd  : wlan0: sending REQUEST (xid 0x8599dc4d), next in 3.38 seconds
08-30 16:53:19.550  7161  7161 D WeatherApplication: removeAccount
08-30 16:53:19.550  7161  7161 D WeatherApplication: Account.length = 0
,08-30 16:53:19.550  7161  7161 E WeatherApplication: OPERATOR:OPEN
08-30 16:53:19.553  7161  7161 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:19
08-30 16:53:19.556  7161  7161 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:53:19.556  7161  7161 D Weather.Utils: 2 : All the weather widget is gone.
08-30 16:53:19.559  7161  7161 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:53:19.561  7161  7161 D WeatherAncestor: connectivity changed - connection : true
,08-30 16:53:19.562  7161  7161 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 16:53:19.571  7161  7161 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:53:19.571  7161  7161 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:53:19.571  7161  7161 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 16:53:19.577  7188  7188 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 16:53:19.591  7161  7161 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:53:19.591  7161  7161 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:19
,08-30 16:53:19.597  7188  7188 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-30 16:53:19.597  7188  7188 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 16:53:19.597  7188  7188 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 16:53:19.597  7188  7188 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 16:53:19.597  7188  7188 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:53:19.597  7188  7188 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 16:53:19.598  7188  7188 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 16:53:19.598  7188  7188 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 16:53:19.632  1045  2011 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7199 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 16:53:19.685  1045  2333 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7221 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:53:19.687  1045  2333 I ActivityManager: Killing 2166:com.lge.music/u0a34 (adj 15): empty #17
08-30 16:53:19.717   329  1537 V AudioFlinger: 2166 died, releasing its sessions
08-30 16:53:19.717   329  1537 V AudioFlinger:  pid 1864 @ 0
08-30 16:53:19.717   329  1537 V AudioFlinger:  pid 3317 @ 1
,08-30 16:53:19.717   329  1537 V AudioFlinger:  pid 3317 @ 2
,08-30 16:53:19.762  1045  1061 W libprocessgroup: failed to open /acct/uid_10034/pid_2166/cgroup.procs: No such file or directory
08-30 16:53:19.788  7199  7199 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 16:53:19.789  7199  7199 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 16:53:19.819  7199  7199 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 16:53:19.819  7199  7199 I MultiDex: install
08-30 16:53:19.819  7199  7199 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 16:53:19.833  7199  7199 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 16:53:19.873   277   347 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 16:53:19.873   277   347 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 16:53:19.873   277   347 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:53:19.873  7221  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 16:53:19.877   277   347 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 16:53:19.877   277   347 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 16:53:19.878   277   347 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 16:53:19.878  7221  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 16:53:19.888   277   347 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 16:53:19.888   277   347 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 16:53:19.888   277   347 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:53:19.888  7221  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 16:53:19.893   277   347 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 16:53:19.893   277   347 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 16:53:19.893   277   347 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 16:53:19.894  7221  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 16:53:19.899  1045  7156 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 16:53:19.901  1045  7156 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 16:53:19.901  1045  7156 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:53:19.901  1045  7156 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 16:53:19.901  1045  7156 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 16:53:19.901  1045  7156 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:53:19.901  1045  7156 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 16:53:19.901  1045  7156 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 16:53:19.903  1045  7156 D DhcpStateMachine: RunningState
08-30 16:53:20.118  7221  7221 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 16:53:20.127  7221  7221 I LibraryLoader: Loading: webviewchromium
08-30 16:53:20.130  7221  7221 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1609-1613)
08-30 16:53:20.131  7221  7221 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 16:53:20.139  7221  7221 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {220f0991}
08-30 16:53:20.140  7221  7221 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:53:20.141  7221  7221 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 16:53:20.151  7221  7221 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 16:53:20.152  7221  7221 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:53:20.170  7221  7221 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 16:53:20.171  7221  7221 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 16:53:20.171  7221  7221 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-30 16:53:20.184   329   329 V AudioPolicyService: registerClient() client 0xb00102c0, uid 10093
,08-30 16:53:20.187  7221  7279 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 16:53:20.200  7221  7221 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:53:20.200  7221  7221 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:53:20.200  7221  7221 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:53:20.200  7221  7221 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:53:20.200  7221  7221 I Adreno-EGL: Remote Branch: 
08-30 16:53:20.200  7221  7221 I Adreno-EGL: Local Patches: 
08-30 16:53:20.200  7221  7221 I Adreno-EGL: Reconstruct Branch: 
,08-30 16:53:20.275  7199  7216 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:20.276  7199  7216 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:20.288  7221  7221 I NSApplication: Starting up...
,08-30 16:53:20.307   325  7182 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 16:53:20.365  1045  1642 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7292 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 16:53:20.367  1045  1642 I ActivityManager: Killing 6826:com.lge.sync/1000 (adj 15): empty #17
08-30 16:53:20.384   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 353us total 16.232ms
,08-30 16:53:20.399   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 304us total 14.383ms
,08-30 16:53:20.412   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 12.886ms
,08-30 16:53:20.460  1045  1505 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 16:53:20.480  1045  1563 D WifiServiceImplEx: setWifiEnabled: false pid=6600, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:53:20.480  1045  1563 D WifiService: setWifiEnabled: false pid=6600, uid=10118
08-30 16:53:20.480  1045  1563 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:53:20.482  1045  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_6826/cgroup.procs: No such file or directory
08-30 16:53:20.490  1045  1424 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:20.493  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:20.494  1045  1424 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:20.495  1045  1424 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:20.498  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:20.498  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:20.499  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-30 16:53:20.499  1045  1505 D ConnectivityService: identical MTU - not setting
,08-30 16:53:20.499  1045  1505 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:53:20.500  1045  1505 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 16:53:20.500  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:20.500  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:20.501  1045  1505 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:20.504  1045  1424 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:20.504  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 16:53:20.504  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:20.504  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:20.504  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:20.504  1045  1045 D Ulp_jni : JNI:system_update. Event-4
08-30 16:53:20.505  1045  1424 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:20.505  1045  1424 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:20.505  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:53:20.505  1045  1424 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 16:53:20.506  1045  1424 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:53:20.506  1045  1424 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:53:20.506  1045  1424 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:53:20.506  1045  1424 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:53:20.513  1045  1424 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:53:20.513  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:53:20.513  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:53:20.514  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.514  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.514  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:53:20.514  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:20.514  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:20.514   325   889 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:53:20.516  1045  7156 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.536  7309  7309 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 16:53:20.542  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.209.78 (port 80) after 10000ms: isConnected failed: ETIMEDOUT (Connection timed out)
08-30 16:53:20.547  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:53:20.547  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-30 16:53:20.551  1045  1045 D WifiHS20: hidePasspointNotification off =false
08-30 16:53:20.552  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 16:53:20.553  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 16:53:20.553  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:20.554  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.557  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.557  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.557  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:20.558  1045  1045 D WifiHS20: hidePasspointNotification off =false
,08-30 16:53:20.563  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.563  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.563  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:20.564  1045  1424 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:20.564  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:20.564  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 16:53:20.564  1045  1424 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:53:20.564  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.564  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.564  1045  1375 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@36e5d5bc
08-30 16:53:20.564  1045  1375 D LGWifiP2pService: P2pDisablingState
08-30 16:53:20.564  1045  1375 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.564  1045  1375 D LGWifiP2pService: p2p socket connection lost
08-30 16:53:20.564  1045  1375 D LGWifiP2pService: P2pDisabledState
08-30 16:53:20.565  1045  1424 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 16:53:20.565  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:53:20.565  7063  7063 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:53:20.565  1045  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.565  1045  1375 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.565  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:53:20.565  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:20.565  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:20.566  1045  1045 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 16:53:20.566  1045  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.566  1045  1045 D RttService: SCAN_AVAILABLE : 1
08-30 16:53:20.566  1045  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.567  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:53:20.567  1953  1953 D WfdsService: WifiP2pState is changed : false
08-30 16:53:20.567  1953  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 16:53:20.567  1953  2345 D WfdsService: Set the WFDS Monitor: false
08-30 16:53:20.568  1953  2345 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:53:20.568  1953  2345 D WfdsService: STATE : WfdsDisabledState - enter
08-30 16:53:20.577  1953  2346 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 16:53:20.577  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:20.577  1953  7095 D CtrlSupplicant: Received on exit socket, terminate
08-30 16:53:20.577  1953  7095 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 16:53:20.577  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:20.577  1953  7095 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 16:53:20.577  1953  7095 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 16:53:20.577  1953  2345 W WfdsService: DefaultState - msg [9445378] is not handled
,08-30 16:53:20.580  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.600  7309  7309 I dex2oat : dex2oat took 64.047ms (threads: 4)
,08-30 16:53:20.610  7199  7216 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:53:20.610  7199  7216 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:53:20.610  7199  7216 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:53:20.610  7199  7216 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:53:20.610  7199  7216 I Adreno-EGL: Remote Branch: 
08-30 16:53:20.610  7199  7216 I Adreno-EGL: Local Patches: 
08-30 16:53:20.610  7199  7216 I Adreno-EGL: Reconstruct Branch: 
08-30 16:53:20.617   325   889 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:53:20.619  1045  1505 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 16:53:20.619  1045  1505 D DSQN    : disableDataServiceNotify
08-30 16:53:20.619  1045  1505 D DSQN    : stop dsqn bin
08-30 16:53:20.622  1045  1424 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 16:53:20.622  1045  1045 D WifiHS20: hidePasspointNotification off =false
08-30 16:53:20.623  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 16:53:20.623  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.623  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:20.623  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.623  1045  1424 D WifiNative-p2p0: TERMINATE: returned true
08-30 16:53:20.623  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:20.623  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:20.623  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:20.623  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:53:20.625  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 16:53:20.625  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:20.625  1045  1045 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 16:53:20.625  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 16:53:20.626  1045  1505 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 16:53:20.626  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:20.626  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:20.626  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.626  1045  1505 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:20.627  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.627  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.627  1045  7142 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 16:53:20.627  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:20.627  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:20.627  6600  6600 V io.jxcore.,node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:20.627  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:20.627  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 16:53:20.627  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:20.626  1045  1505 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 16:53:20.628  1045  1505 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 16:53:20.628  1045  1505 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 16:53:20.628  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:53:20.628  1045  1505 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:20.628  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:53:20.629  1045  1505 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:20.629  1045  1505 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:20.629  1045  1505 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:20.629  1045  1505 D NetworkManagementService: Removing idletimer
08-30 16:53:20.629  1045  1505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.629  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.629  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:20.629  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:20.629  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:20.629  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:20.629  1045  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 16:53:20.629  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:20.630  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:53:20.631  1045  1045 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 16:53:20.631  1045  1374 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 16:53:20.631  1045  1424 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:20.631  1045  1424 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:20.631  1045  1505 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 16:53:20.631  1045  1045 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 16:53:20.631  1045  1045 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:53:20.631  1045  1045 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:53:20.631  1045  1045 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:53:20.631  1045  1045 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:53:20.631  1045  1045 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:53:20.631  1045  1045 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:53:20.653  1045  1976 I art     : Explicit concurrent mark sweep GC freed 91299(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.789ms total 154.827ms
,08-30 16:53:20.668  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:53:20.669  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.669  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.673  7292  7292 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:20.681  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:53:20.682  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.682  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.696  7199  7216 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:53:20.696  7199  7216 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:53:20.696  7199  7216 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:53:20.696  7199  7216 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:53:20.696  7199  7216 I Adreno-EGL: Remote Branch: 
08-30 16:53:20.696  7199  7216 I Adreno-EGL: Local Patches: 
08-30 16:53:20.696  7199  7216 I Adreno-EGL: Reconstruct Branch: 
,08-30 16:53:20.722  1045  7156 D DhcpStateMachine: StoppedState
,08-30 16:53:20.722  1045  7156 D DhcpStateMachine: StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:20.723  1045  1424 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 16:53:20.724  1045  1424 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 16:53:20.739  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 16:53:20.739  7063  7063 I wpa_supplicant: monitor socket send errors count : 1
08-30 16:53:20.739  7063  7063 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1953-4\x00 that cannot receive messages
,08-30 16:53:20.741  1045  7077 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 16:53:20.741  1045  7077 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:53:20.771  7199  7216 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:53:20.771  7199  7216 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:53:20.771  7199  7216 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:53:20.771  7199  7216 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:53:20.771  7199  7216 I Adreno-EGL: Remote Branch: 
08-30 16:53:20.771  7199  7216 I Adreno-EGL: Local Patches: 
08-30 16:53:20.771  7199  7216 I Adreno-EGL: Reconstruct Branch: 
,08-30 16:53:20.780  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:53:20.782  7063  7063 W wpa_supplicant: USIM:  scard_deinit function
08-30 16:53:20.783  1045  1120 D Tethering: InitialState.processMessage what=4
,08-30 16:53:20.784  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 16:53:20.785  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:53:20.785  1045  7077 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:53:20.785  1045  7077 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 16:53:20.785  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:20.785  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:20.786  1045  1424 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122257
08-30 16:53:20.786  1045  1424 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122257
08-30 16:53:20.787  1045  1424 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122258  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:53:20.787  1045  1424 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122258  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:53:20.791  1045  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:53:20.792  1045  1424 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:20.792  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 16:53:20.920  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 16:53:20.923  6403  6430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 16:53:20.924  6722  6980 D UEI.SmartControl: Internal timer expired: 4
08-30 16:53:20.925  6722  6980 D UEI.SmartControl: unbind internal service
,08-30 16:53:20.926   325  7329 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 16:53:20.927  1045  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 16:53:20.929  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 16:53:20.929  1823  7187 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 16:53:20.933  1045  7077 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 16:53:20.933  1045  7077 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 16:53:20.933  1045  7077 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 16:53:20.933  1045  1424 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-30 16:53:20.936  1045  1424 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 16:53:20.936  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:20.936  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:20.936  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 16:53:20.939  1953  1953 D WfdsService: Supplicant Connection state is changed : false
08-30 16:53:20.939  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:53:20.939  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 16:53:20.939  1953  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 16:53:20.939  1953  2345 D WfdsService: Set the WFDS Monitor: false
08-30 16:53:20.939  1953  2345 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:53:20.939  1045  1454 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 16:53:20.939  1045  1454 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 16:53:20.940  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:20.943  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:20.943  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:20.943  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:20.944  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:20.944  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:53:20.951  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:20.955  1823  7187 I CheckinService: active receiver: disabled
,08-30 16:53:20.969  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:53:20.969  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:20.969  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:53:20.969  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 16:53:20.971  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
08-30 16:53:20.974  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e45db6e
08-30 16:53:20.974  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:53:20.974  7010  7010 D AppUp4:CustFacade: isPhone : true
08-30 16:53:20.974  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:53:20.974  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 16:53:20.977  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:20.978  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 16:53:20.979  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:20.981  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:20.985  4294  7335 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:20.987  7037  7037 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 16:53:20.989  4294  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:20.989  4294  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:53:21.003  7037  7337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:53:21.008  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:53:21.008  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:21.009  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 16:53:21.013  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:53:21.013  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 16:53:21.014  6911  7340 W FormManager: Network not available. Please check & try again.
,08-30 16:53:21.022  6911  7341 V FormManager: Network unavailable.
08-30 16:53:21.024  7161  7161 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:21
08-30 16:53:21.025  7161  7161 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:53:21.025  7161  7161 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 16:53:21.026  6911  7341 V FormManager: Network unavailable.
08-30 16:53:21.027  7161  7161 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:53:21.028  7161  7161 D WeatherAncestor: connectivity changed - connection : true
08-30 16:53:21.028  7161  7161 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c1f429c
08-30 16:53:21.028  7161  7161 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:53:21.028  7161  7161 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:53:21.028  7161  7161 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 16:53:21.028  7161  7161 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:53:21.028  7161  7161 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:21
08-30 16:53:21.051  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:53:21.051  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:53:21.051  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:53:21.051  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:53:21.052  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:53:21.053  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:53:21.053  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:53:21.053  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-30 16:53:21.053  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:53:21.053  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:53:21.053  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:53:21.113  1045  2042 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7345 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:21.120  6911  7343 W FormManager: Network not available. Please check & try again.
08-30 16:53:21.121  6911  7344 V FormManager: Network unavailable.
08-30 16:53:21.123  6911  7344 V FormManager: Network unavailable.
08-30 16:53:21.125  6722  6962 D serial_port: close(fd = 24)
08-30 16:53:21.129  6722  6962 I UEI.SmartControl: Serial port is closed.
,08-30 16:53:21.221  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:21.229  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:53:21.240  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.243  1045  1919 I ActivityManager: Killing 6848:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 16:53:21.301  1045  1735 W libprocessgroup: failed to open /acct/uid_10037/pid_6848/cgroup.procs: No such file or directory
,08-30 16:53:21.330  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:21.338  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:53:21.340  6911  7371 W FormManager: Network not available. Please check & try again.
,08-30 16:53:21.344  6911  7372 V FormManager: Network unavailable.
08-30 16:53:21.348  6911  7372 V FormManager: Network unavailable.
08-30 16:53:21.354  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:21.373  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:21.373  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:53:21.375  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 16:53:21.378  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:21.386  4294  7373 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:21.390  4294  7374 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:21.390  4294  7374 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:53:21.443  1045  1943 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7380 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 16:53:21.550  7380  7380 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 16:53:21.550  7380  7380 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 16:53:21.564  7380  7380 V [BNRBootReceiver]: Boot Receiver Return
08-30 16:53:21.567  7380  7380 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 16:53:21.573  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:21.597  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.615  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.643  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:21.644  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:21.646  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:53:21.649  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:21.662  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.673  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.681  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:21.682  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:21.684  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:53:21.688  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 16:53:21.692  6805  6805 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 16:53:21.697  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:21.708  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.714  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.723  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:21.723  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:21.724  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:53:21.731  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:21.740  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.748  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:21.758  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:21.758  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:21.759  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:53:21.767  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:21.783  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.796  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:21.808  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:21.808  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:21.809  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:53:21.817  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:21.831  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.839  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.849  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:21.849  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:21.850  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:53:21.855  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:21.863  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.872  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.881  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:21.882  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:21.883  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:21.897  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:21.919  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.931  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:21.942  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:21.944  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:21.954  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:21.961  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:21.975  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:21.987  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:22.001  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:22.002  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:22.004  6872  6872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:22.014  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:22.025  7345  7345 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 16:53:22.043  1045  1482 D WifiService: New client listening to asynchronous messages
,08-30 16:53:22.046  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:22.055  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:22.069  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:22.084  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:22.085  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:22.087  6872  6872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 16:53:22.090  6872  6872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:53:22.091  6872  6872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 16:53:22.099  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:22.110  7345  7345 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 16:53:22.113  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:22.121  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:22.131  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:22.142  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:22.143  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:22.145  6872  6872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 16:53:22.147  6872  6872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:53:22.148  6872  6872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 16:53:22.157  1045  1728 I ActivityManager: Killing 6891:com.lge.settings.easy/1000 (adj 15): empty #17
08-30 16:53:22.191  1045  1735 W libprocessgroup: failed to open /acct/uid_1000/pid_6891/cgroup.procs: No such file or directory
,08-30 16:53:22.197  2246  2246 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 16:53:22.211  2246  2246 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 16:53:22.212  2246  2246 D c       : Getting all permits...
08-30 16:53:22.212  2246  2246 D a       : Opening database...
08-30 16:53:22.222  2246  2246 D a       : Opening database auth.proximity.permit_store...
,08-30 16:53:22.225  2246  2246 D a       : Closing database...
,08-30 16:53:22.247  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:22.258  7345  7345 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:53:22.265  7345  7345 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:53:22.265  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:22.276  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:22.286  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:22.290  1045  1424 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-604980242] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 16:53:22.292  1045  1424 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-604980236] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 16:53:22.300  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:22.301  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:22.306  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:53:22.314  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:22.323  7345  7345 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 16:53:22.324  7345  7345 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 16:53:22.324  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:22.332  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:22.342  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:22.354  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:22.354  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:22.357  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 16:53:22.367  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:22.373  7345  7345 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:53:22.374  7345  7345 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:53:22.374  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:22.379  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:22.386  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:22.398  6872  6872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:22.398  6872  6872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:22.402  6872  6872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:53:22.428  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:22.440  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:53:22.442  6911  7404 W FormManager: Network not available. Please check & try again.
,08-30 16:53:22.450  6911  7405 V FormManager: Network unavailable.
08-30 16:53:22.455  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:22.458  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:22.458  1045  1120 D Tethering: MasterInitialState.processMessage what=3
08-30 16:53:22.459  1045  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:22.464  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:22.466  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:22.468  1045  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:22.470  6911  7405 V FormManager: Network unavailable.
,08-30 16:53:22.475  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 16:53:22.490  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:22.490  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:53:22.492  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 16:53:22.496  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:22.502  4294  7406 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:22.506  4294  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:22.507  4294  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:53:22.512  7345  7345 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 16:53:22.512  7345  7345 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:53:22.512  7345  7345 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:22.517  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:53:22.524  6911  7410 V FormManager: Network unavailable.
08-30 16:53:22.525  6911  7409 W FormManager: Network not available. Please check & try again.
08-30 16:53:22.527  6911  7410 V FormManager: Network unavailable.
08-30 16:53:22.528  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:22.545  2246  2246 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 16:53:22.560  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 16:53:22.562  6403  6430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 16:53:22.578  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:22.593  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:53:22.594  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:22.594  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:53:22.594  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 16:53:22.596  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 16:53:22.600  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e45db6e
08-30 16:53:22.600  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:53:22.600  7010  7010 D AppUp4:CustFacade: isPhone : true
08-30 16:53:22.600  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:53:22.601  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 16:53:22.606  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:22.606  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 16:53:22.608  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:22.610  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:22.619  7037  7037 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 16:53:22.619  4294  7411 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 16:53:22.624  4294  7412 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:22.625  4294  7412 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:53:22.658  7037  7413 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:53:22.666  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:53:22.666  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:22.667  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 16:53:22.667  3317  3317 D PhoneState: setPdpRejectCasuse : false
08-30 16:53:22.668  6911  7415 W FormManager: Network not available. Please check & try again.
08-30 16:53:22.671  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:53:22.671  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 16:53:22.676  6911  7416 V FormManager: Network unavailable.
08-30 16:53:22.686  7161  7161 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:22
,08-30 16:53:22.686  6911  7416 V FormManager: Network unavailable.
,08-30 16:53:22.688  7161  7161 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 16:53:22.688  7161  7161 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 16:53:22.689  7161  7161 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:53:22.689  7161  7161 D WeatherAncestor: connectivity changed - connection : true
,08-30 16:53:22.689  7161  7161 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c1f429c
,08-30 16:53:22.689  7161  7161 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-30 16:53:22.690  7161  7161 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-30 16:53:22.690  7161  7161 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 16:53:22.690  7161  7161 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:53:22.690  7161  7161 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:22
08-30 16:53:23.508  1045  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-30 16:53:23.509  1045  2011 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 16:53:23.534  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:23.534  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:23.534  1045  1045 D Ulp_jni : JNI:system_update. Event-4
08-30 16:53:23.537  1045  1120 D BluetoothManagerService: Message: 1
08-30 16:53:23.537  1045  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 16:53:23.568  1045  1120 D BluetoothManagerService: Message: 20
08-30 16:53:23.569  1045  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20b1219f:true
08-30 16:53:23.570  6963  6963 D BluetoothAdapterState: make
08-30 16:53:23.575  6963  6963 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 16:53:23.575  6963  6963 I bluedroid-qcom: init
,08-30 16:53:23.579  6963  7425 I BluetoothAdapterState: Entering OffState
08-30 16:53:23.579  6963  6963 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 16:53:23.580  6963  6963 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 16:53:23.580  6963  6963 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:53:23.580  6963  6963 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:53:23.580  6963  6963 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 16:53:23.581  6963  6963 I bluedroid-qcom: get_profile_interface socket
08-30 16:53:23.581  6963  6963 I bluedroid-qcom: get_profile_interface map_client
08-30 16:53:23.583  6963  7429 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 16:53:23.585  6963  7429 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 16:53:23.580  7428  7428 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:23.580  7428  7428 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:23.594  7428  7428 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 16:53:23.594  7428  7428 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 16:53:23.594  7428  7428 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 16:53:23.601  1045  1045 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:53:23.601  1045  1045 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 16:53:23.603  1045  1045 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 16:53:23.603  1045  1120 D BluetoothManagerService: Message: 40
08-30 16:53:23.603  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 16:53:23.604  6963  6982 I bluedroid-qcom: config_hci_snoop_log
08-30 16:53:23.605  1045  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 16:53:23.605  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 16:53:23.607  7428  7428 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-30 16:53:23.616  6963  7425 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 16:53:23.616  6963  7429 D BluetoothAdapterProperties: Name is: G3
08-30 16:53:23.617  6963  7425 D BluetoothAdapterProperties: Setting state to 11
08-30 16:53:23.617  6963  7425 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 16:53:23.618  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:23.618  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 16:53:23.618  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 16:53:23.619  7428  7428 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 16:53:23.619  7428  7428 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 16:53:23.625  6963  7425 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 16:53:23.630  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:23.630  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:23.632  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:23.636  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:23.638  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:23.641  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 16:53:23.643  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:23.660  1045  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:23.670  1045  1120 D Tethering: MasterInitialState.processMessage what=3
08-30 16:53:23.672  6963  6963 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:23.673  6963  6963 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:23.673  6963  6963 V BluetoothPbapReceiver: ***********state = 11
08-30 16:53:23.679  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:23.681  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:23.682  1045  1120 D Tethering: MasterInitialState.processMessage what=3
08-30 16:53:23.691  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:23.693  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:23.696  6963  7425 D BluetoothBondStateMachine: make
08-30 16:53:23.697  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 16:53:23.698  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:53:23.698  6403  6430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 16:53:23.699  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 16:53:23.700  6963  7425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:23.700  6963  7425 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 16:53:23.700  6963  7425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:23.700  6963  7425 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 16:53:23.701  6963  7425 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 16:53:23.702  6963  7446 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 16:53:23.704  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.753  1045  1060 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7448 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 16:53:23.766  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.768  6963  6963 D HeadsetService: Received start request. Starting profile...
08-30 16:53:23.768  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 16:53:23.769  6963  6963 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:53:23.770  6963  6963 D LGBluetoothHfpAdapter: Version 1.6
,08-30 16:53:23.776  6963  6963 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:53:23.778  6963  6963 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:53:23.779  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.779  6963  6963 D HeadsetStateMachine: make
08-30 16:53:23.785  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.787  1045  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:23.792  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.794  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:23.801  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.807  1045  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:23.807  1045  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:23.810  6963  7425 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:23.811  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:53:23.813  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:23.813  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:53:23.813  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 16:53:23.814  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
08-30 16:53:23.817  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e45db6e
08-30 16:53:23.817  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:53:23.817  7010  7010 D AppUp4:CustFacade: isPhone : true
08-30 16:53:23.817  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:53:23.817  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 16:53:23.819  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:23.820  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:53:23.820  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:23.821  6963  6963 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:23.821  6963  6963 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:53:23.822  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:23.824  6963  7425 V LGMDMManager: Create singleton instance
08-30 16:53:23.826  6963  6963 D HeadsetStateMachine: max_hf_connections = 1
08-30 16:53:23.826  6963  6963 I bluedroid-qcom: get_profile_interface handsfree
08-30 16:53:23.827  6963  7425 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 16:53:23.829  6963  6963 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 16:53:23.829  7037  7037 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 16:53:23.829   329  1537 V AudioPolicyService: registerClient() client 0xb558a420, uid 1002
08-30 16:53:23.829   329   329 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:53:23.829   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:53:23.829   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
,08-30 16:53:23.831  6963  6963 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 16:53:23.832   329  1382 V AudioFlinger: registerClient() client 0xb1433100, pid 6963
08-30 16:53:23.832  6963  6963 V ToneGenerator: Create Track: 0xb4928080
08-30 16:53:23.832  6963  6963 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 16:53:23.832  6963  6963 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 16:53:23.832   329  1537 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:53:23.832   329  1537 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:53:23.832   329  1537 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:53:23.832   329  1537 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:53:23.833   329  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:23.833   329  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:23.833  1589  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 16:53:23.833  1589  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:23.833  4294  7466 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:23.833  1045  1976 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:23.833  1045  1976 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:23.834  6963  6983 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:23.834  6963  6983 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 16:53:23.834  3317  3332 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:23.834  3317  3332 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:23.834  1864  1880 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:23.834  1864  1880 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:23.835   329  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:23.835   329  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:23.835  1045  1919 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:23.835  1045  1919 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:23.835  3317  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:23.835  3317  3333 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:23.835   329   329 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 16:53:23.835  1864  1879 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:23.835  1589  2118 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:23.835  6963  6982 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:23.835  1864  1879 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:23.835  1589  2118 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:23.835   329  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:53:23.835  6963  6982 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 16:53:23.835   329  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 16:53:23.835   329  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:53:23.835   329  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:53:23.836  6963  6963 V AudioSystem: getLatency() output 2, latency 50
08-30 16:53:23.836  6963  6963 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 16:53:23.836  6963  6963 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 16:53:23.837   329  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:53:23.837   329  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:53:23.837   329  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:53:23.837   329  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:53:23.837   329  1381 V AudioFlinger: createTrack() lSessionId: 22
08-30 16:53:23.839  6963  6963 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 16:53:23.839   329  1537 V AudioFlinger: acquiring 22 from 6963, for 6963
08-30 16:53:23.839   329  1537 V AudioFlinger:  added new entry for 22
08-30 16:53:23.839  6963  6963 V ToneGenerator: ToneGenerator INIT OK, time: 125322
08-30 16:53:23.839  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:23.840  6963  7464 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 16:53:23.840  6963  7464 D HeadsetPhoneStat,e: [BTUI] listenForPhoneState : start = false
08-30 16:53:23.840  6963  7464 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:53:23.840  6963  7464 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 16:53:23.840   329   329 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6963
08-30 16:53:23.841  4294  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:23.841  4294  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:53:23.846  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:23.847   329   329 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 16:53:23.847   329   329 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 16:53:23.847   329   329 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 16:53:23.847   329   329 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 16:53:23.847   329   329 V voice   : voice_set_parameters: exit with code(0)
08-30 16:53:23.847   329   329 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 16:53:23.847   329   329 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 16:53:23.847   329   329 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 16:53:23.847   329   329 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 16:53:23.847   329   329 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 16:53:23.847   329   329 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 16:53:23.847  6963  7464 V ToneGenerator: ToneGenerator destructor
08-30 16:53:23.847  6963  7464 V ToneGenerator: stopTone
08-30 16:53:23.847  6963  7464 V ToneGenerator: Delete Track: 0xb4928080
08-30 16:53:23.848  6963  6963 D A2dpService: Received start request. Starting profile...
08-30 16:53:23.848  1045  2079 W Process : Unable to open /proc/7468/status
08-30 16:53:23.848  6963  7464 V AudioTrack: ~AudioTrack, releasing session id from 6963 on behalf of 6963
08-30 16:53:23.848   329  1382 V AudioFlinger: releasing 22 from 6963 for 6963
08-30 16:53:23.848   329  1382 V AudioFlinger:  decremented refcount to 0
08-30 16:53:23.848   329  1382 V AudioFlinger: purging stale effects
08-30 16:53:23.848   329  1382 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 16:53:23.848   329  1382 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 16:53:23.848   329  1259 V AudioPolicyService: AudioCommandThread() waking up
08-30 16:53:23.848   329  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 16:53:23.848   329  1259 V AudioPolicyManager: releaseOutput() 2
08-30 16:53:23.848   329  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 16:53:23.848   329  1382 V AudioFlinger: PlaybackThread::Track destructor
08-30 16:53:23.848   329  1382 V AudioFlinger: removeClient_l() pid 6963, calling pid 329
08-30 16:53:23.849  6963  6963 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:53:23.850  6963  6963 V Avrcp   : make
08-30 16:53:23.850  6963  6963 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 16:53:23.850  6963  6963 I bluedroid-qcom: get_profile_interface avrcp
08-30 16:53:23.853  6911  7472 W FormManager: Network not available. Please check & try again.
,08-30 16:53:23.855  6911  7473 V FormManager: Network unavailable.
08-30 16:53:23.857  6911  7473 V FormManager: Network unavailable.
08-30 16:53:23.859  6963  6963 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 16:53:23.861  6963  6963 E AudioManager: No RCC entry present to update
08-30 16:53:23.861  6963  6963 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:53:23.864  6963  6963 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 16:53:23.864  7037  7469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:23.865  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 16:53:23.865  6963  6963 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 16:53:23.867  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:53:23.867  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:23.867  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 16:53:23.869  7448  7448 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 16:53:23.870  7448  7448 W LG Account v2.2: No ProfileInfo entries
08-30 16:53:23.870  7448  7448 I LG Account v2.2: isEnabled: false
08-30 16:53:23.870  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 16:53:23.870  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Country: EU
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Operator: OPEN
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Ranking support: false
08-30 16:53:23.870  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Comfort support: false
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Accessory: true
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Health device: true
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Extra Pedometer: false
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Blood glucose device: false
08-30 16:53:23.870  7448  7448 I Feature : [Lifetracker]Device Number: 3
08-30 16:53:23.920  7161  7161 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:23
,08-30 16:53:23.926  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 16:53:23.927  7161  7161 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:53:23.927  7161  7161 D Weather.Utils: 2 : All the weather widget is gone.
08-30 16:53:23.929  7161  7161 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:53:23.930  7161  7161 D WeatherAncestor: connectivity changed - connection : true
08-30 16:53:23.930  7161  7161 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c1f429c
08-30 16:53:23.932  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:53:23.933  7161  7161 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:53:23.933  7161  7161 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:53:23.933  7161  7161 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 16:53:23.933  7161  7161 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:53:23.933  7161  7161 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:23
,08-30 16:53:23.975  1045  2012 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:53:23.975  1045  2012 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:53:23.978  6403  6403 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 16:53:23.980  6403  6430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 16:53:24.008  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:24.027  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 16:53:24.028  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:24.028  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:53:24.028  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 16:53:24.033  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
08-30 16:53:24.040  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e45db6e
08-30 16:53:24.040  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:53:24.040  7010  7010 D AppUp4:CustFacade: isPhone : true
,08-30 16:53:24.043  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
,08-30 16:53:24.043  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 16:53:24.050  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:24.051  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:53:24.053  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 16:53:24.057  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 16:53:24.069  7037  7037 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 16:53:24.070  4294  7479 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 16:53:24.082  4294  7480 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:24.082  4294  7480 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:53:24.092  1045  2011 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 16:53:24.099  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 16:53:24.102  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:53:24.103  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 16:53:24.104  6963  6963 I BluetoothA2dpServiceJni: classInitNative
08-30 16:53:24.104  6963  6963 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 16:53:24.104  6963  6963 D A2dpStateMachine: make
08-30 16:53:24.106  7037  7481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:24.106  6963  6963 I bluedroid-qcom: get_profile_interface a2dp
08-30 16:53:24.106  6963  7486 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 16:53:24.109  6963  6963 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:53:24.109  6963  6963 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 16:53:24.111  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:24.112  6963  6963 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 16:53:24.112  6963  7485 D A2dpStateMachine: Enter Disconnected: -2
08-30 16:53:24.115  6963  6963 D HidService: Received start request. Starting profile...
08-30 16:53:24.115  6963  6963 I bluedroid-qcom: get_profile_interface hidhost
08-30 16:53:24.115  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:24.116  6963  6963 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:53:24.116  3317  3317 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:53:24.116  3317  3317 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:24.116  3317  3317 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 16:53:24.118  6963  6963 D HealthService: Received start request. Starting profile...
08-30 16:53:24.120  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:53:24.120  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 16:53:24.120  6963  6963 I bluedroid-qcom: get_profile_interface health
08-30 16:53:24.120  6963  6963 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:53:24.120  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:24.121  6963  6963 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 16:53:24.122  6963  6963 D PanService: Received start request. Starting profile...
08-30 16:53:24.122  6963  6963 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:53:24.122  6963  6963 I bluedroid-qcom: get_profile_interface pan
08-30 16:53:24.124  6911  7483 W FormManager: Network not available. Please check & try again.
08-30 16:53:24.125  6911  7484 V FormManager: Network unavailable.
08-30 16:53:24.131  6963  6963 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 16:53:24.131  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:24.132  6963  6963 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 16:53:24.136  6963  6963 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:53:24.136  6963  6963 D BtGatt.GattService: Received start request. Starting profile...
08-30 16:53:24.136  6963  6963 D BtGatt.GattService: start()
08-30 16:53:24.136  6963  6963 I bluedroid-qcom: get_profile_interface gatt
08-30 16:53:24.136  6963  6963 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:53:24.140  6911  7484 V FormManager: Network unavailable.
08-30 16:53:24.143  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:24.144  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
,08-30 16:53:24.144  6963  6963 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 16:53:24.145  6963  6963 V BluetoothMapService: BluetoothMapBinder()
,08-30 16:53:24.146  6963  6963 D BluetoothMapService: Received start request. Starting profile...
08-30 16:53:24.146  6963  6963 D BluetoothMapService: start()
08-30 16:53:24.146  7161  7161 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:24
08-30 16:53:24.147  7161  7161 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:53:24.147  7161  7161 D Weather.Utils: 2 : All the weather widget is gone.
08-30 16:53:24.148  7161  7161 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:53:24.148  7161  7161 D WeatherAncestor: connectivity changed - connection : true
08-30 16:53:24.148  7161  7161 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c1f429c
08-30 16:53:24.149  7161  7161 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:53:24.149  6963  6963 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 16:53:24.149  7161  7161 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:53:24.149  7161  7161 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 16:53:24.149  7161  7161 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:53:24.149  6963  6963 D BluetoothMapEmailAppObserver: createReceiver()
08-30 16:53:24.149  7161  7161 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:53:24
,08-30 16:53:24.154  6963  6963 D BluetoothMapEmailAppObserver: initObservers()
08-30 16:53:24.154  6963  6963 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 16:53:24.164  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:24.165  6963  6963 D HeadsetStateMachine: Proxy object connected
08-30 16:53:24.165  6963  6963 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 16:53:24.166  6963  6963 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 16:53:24.167  6963  7464 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 16:53:24.167  6963  7464 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:53:24.168  6963  7464 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 16:53:24.171  6963  6963 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:24.175  6963  6963 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:24.178  6963  6963 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 16:53:24.181  6963  6963 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:24.183  6963  6963 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:24.184  6963  6963 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 16:53:24.187  6963  6963 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 16:53:24.187  6963  6963 V BluetoothMapService: Handler(): got msg=1
08-30 16:53:24.188  6963  7425 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 16:53:24.188  6963  7425 I bluedroid-qcom: enable
08-30 16:53:24.188  6963  7494 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 16:53:24.188  6963  7494 I bt-btu  : btu_task pending for preload complete event
08-30 16:53:24.188  6963  7425 I bt_hci_bdroid: init
08-30 16:53:24.189  6963  6963 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:24.190  6963  7425 I bt_vendor: bt-vendor : init
08-30 16:53:24.190  6963  7425 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 16:53:24.190  6963  7425 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 16:53:24.191  6963  7425 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 16:53:24.191  6963  7425 D bt_userial_mct: userial_init
,08-30 16:53:24.192  6963  6963 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:24.192  6963  6963 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:24.192  6963  6963 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:24.192  6963  6963 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:24.192  6963  6963 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 16:53:24.193  6963  7425 D bt_hci_bdroid: set_power 1
08-30 16:53:24.193  6963  7425 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 16:53:24.193  6963  7425 I bt_vendor: Starting hciattach daemon
08-30 16:53:24.193  6963  7425 I bt_vendor: try to set true
08-30 16:53:24.180  7497  7497 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:24.180  7497  7497 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:24.224  7498  7498 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 16:53:24.250  1045  2079 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7501 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:24.304  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 16:53:24.313  7501  7501 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:24.316  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:53:24.330  1045  1563 I ActivityManager: Killing 6041:com.android.vending/u0a44 (adj 15): empty #17
,08-30 16:53:24.338  7524  7524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 16:53:24.349  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 16:53:24.355  1045  1114 W ProcessCpuTracker: Skipping unknown process pid 7521
,08-30 16:53:24.359  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 16:53:24.371  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 16:53:24.389  1045  1060 W libprocessgroup: failed to open /acct/uid_10044/pid_6041/cgroup.procs: No such file or directory
,08-30 16:53:24.391  7529  7529 I libmdmdetect: ESOC framework not supported
08-30 16:53:24.393  7529  7529 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-30 16:53:24.401  7529  7529 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 16:53:24.401  7529  7529 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 16:53:24.401  7529  7529 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 16:53:24.401  7529  7529 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 16:53:24.401  7529  7529 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 16:53:24.401  7529  7529 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-30 16:53:24.402  7529  7529 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 16:53:24.446  7529  7530 E QC-QMI  : qmi_client [7529] 14: failed to locate client data
,08-30 16:53:24.447   493   493 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 16:53:24.447   493   493 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 16:53:24.500  7531  7531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 16:53:24.529  7532  7532 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:53:24.598  6963  7425 I bt_vendor: bluetooth satus is on
,08-30 16:53:24.598  6963  7425 D bt_hci_bdroid: preload
08-30 16:53:24.598  6963  7496 D bt_userial_mct: userial_open(port:0)
08-30 16:53:24.599  6963  7496 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 16:53:24.604  6963  7496 I bt_vendor: Done intiailizing UART
08-30 16:53:24.607  6963  7496 I bt_vendor: Done intiailizing UART
08-30 16:53:24.607  6963  7496 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 16:53:24.608  6963  7496 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 16:53:24.608  6963  7494 I bt-btu  : btu_task received preload complete event
08-30 16:53:24.608  6963  7534 D bt_userial_mct: Entering userial_read_thread()
08-30 16:53:24.609  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 16:53:24.609  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 16:53:24.619  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-30 16:53:24.628  6963  7494 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:53:24.628  6963  7494 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 16:53:24.628  6963  7494 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 16:53:24.628  6963  7494 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:53:24.628  6963  7494 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 16:53:24.628  6963  7494 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:53:24.629  6963  7494 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:53:24.728  6963  7494 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 16:53:24.728  6963  7494 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
,08-30 16:53:24.728  6963  7494 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-30 16:53:24.769  6963  7429 E bt-btif : Calling BTA_HhEnable
08-30 16:53:24.769  6963  7429 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 16:53:24.769  6963  7429 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 16:53:24.772  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 16:53:24.772  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-30 16:53:24.774  1045  1045 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:53:24.774  1045  1045 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 16:53:24.774  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 16:53:24.775  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 16:53:24.775  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 16:53:24.775  6963  7429 D BluetoothAdapterProperties: Name is: G3
08-30 16:53:24.776  6963  7429 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:53:24.777  6963  7429 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:53:24.777  6963  7429 D bt_hci_bdroid: postload
08-30 16:53:24.777  6963  7496 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:24.778  6963  7496 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:24.779  6963  7494 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 16:53:24.779  6963  7496 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 16:53:24.780  6963  7429 D bte_conf: Device ID record 1 : primary
08-30 16:53:24.780  6963  7429 D bte_conf:   vendorId            = 00c4
08-30 16:53:24.780  6963  7429 D bte_conf:   vendorIdSource      = 0001
08-30 16:53:24.780  6963  7429 D bte_conf:   product             = 13a1
08-30 16:53:24.780  6963  7429 D bte_conf:   version             = 1000
08-30 16:53:24.780  6963  7429 D bte_conf:   clientExecutableURL = 
08-30 16:53:24.780  6963  7429 D bte_conf:   serviceDescription  = 
08-30 16:53:24.780  6963  7429 D bte_conf:   documentationURL    = 
08-30 16:53:24.780  6963  7429 D bte_conf: bte_load_did_conf no section named DID2.
08-30 16:53:24.784  6963  7425 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 16:53:24.784  6963  7425 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:53:24.784  6963  7425 D BluetoothAdapterProperties: State =  11
08-30 16:53:24.784  6963  7425 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 16:53:24.785  6963  7425 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 16:53:24.785  6963  7425 D BluetoothAdapterProperties: Setting state to 12
08-30 16:53:24.785  6963  7425 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 16:53:24.791  6963  7429 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:53:24.780  7545  7545 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:24.794  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:24.794  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 16:53:24.794  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 16:53:24.795  6963  7494 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:24.795  6963  7494 W bt-smp  : Plain text(LSB ~ MSB) = 45 64 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:24.795  6963  7494 W bt-smp  : Encrypted text(LSB ~ MSB) = ea cb 94 e8 22 6b c0 5a a6 c2 e3 63 65 da ea 4c 
08-30 16:53:24.795  6963  7496 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:24.795  6963  7494 W bt-btm  : Stopping oneshot timer
08-30 16:53:24.796  6963  7429 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:53:24.790  7545  7545 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:24.800  6963  7534 E bt_mct  : hci lib postload completed
08-30 16:53:24.819  6963  7425 I BluetoothAdapterState: Entering On State
,08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:24.833  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:53:24.840  6963  7494 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:24.840  6963  7494 W bt-smp  : Plain text(LSB ~ MSB) = 17 7c 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:24.840  6963  7494 W bt-smp  : Encrypted text(LSB ~ MSB) = aa ab 10 74 95 8b 09 cf cc 92 cb ee a0 99 f9 d2 
08-30 16:53:24.840  6963  7494 W bt-btm  : Stopping oneshot timer
08-30 16:53:24.841  6963  7429 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:53:24.841  6963  7429 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 16:53:24.842  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:24.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:53:24.855  6963  7494 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:24.857  6963  7494 W bt-smp  : Plain text(LSB ~ MSB) = 0b c9 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:24.857  6963  7494 W bt-smp  : Encrypted text(LSB ~ MSB) = 63 5c 49 88 07 a0 b6 d7 f0 09 08 38 9e bc 77 eb 
08-30 16:53:24.857  6963  7494 W bt-btm  : Stopping oneshot timer
08-30 16:53:24.862  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:24.869  6963  7494 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:24.869  6963  7494 W bt-smp  : Plain text(LSB ~ MSB) = fa c7 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:24.869  6963  7494 W bt-smp  : Encrypted text(LSB ~ MSB) = b2 c7 bf 96 e4 0e 65 0a 99 46 06 bb d2 43 21 da 
,08-30 16:53:24.872  6963  7494 W bt-btm  : Stopping oneshot timer
08-30 16:53:24.876  6963  7425 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 16:53:24.876  6963  7425 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 16:53:24.876  6963  7425 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 16:53:24.879  6963  7425 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 16:53:24.879  6963  7425 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 16:53:24.893  6805  6823 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:53:24.914  7550  7550 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 16:53:24.919  6963  7494 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:24.919  6963  7494 W bt-smp  : Plain text(LSB ~ MSB) = c7 5f 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:24.919  6963  7494 W bt-smp  : Encrypted text(LSB ~ MSB) = 7d ec 40 df f6 db be 76 7d 41 70 4d 19 04 1f 33 
08-30 16:53:24.919  6963  7494 W bt-btm  : Stopping oneshot timer
08-30 16:53:24.923  6805  6822 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:53:24.923  6805  6822 D BluetoothPan: onBluetoothStateChange call bindService
08-30 16:53:24.929  1045  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:53:24.939  1045  1045 D BluetoothHeadset: Proxy object connected
,08-30 16:53:24.940  6805  6823 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:53:24.942  6805  6805 D BluetoothInputDevice: Proxy object connected
08-30 16:53:24.942  6805  6805 D HidProfile: Bluetooth service connected
08-30 16:53:24.946  6805  6822 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:53:24.952  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:53:24.953  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:53:24.953  6805  6805 D PanProfile: Bluetooth service connected
08-30 16:53:24.955  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:53:24.955  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 16:53:24.957  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 16:53:24.957  1045  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:53:24.957  6805  6805 D BluetoothMap: Proxy object connected
08-30 16:53:24.957  6805  6805 D MapProfile: Bluetooth service connected
08-30 16:53:24.957  6805  6805 D BluetoothMap: getConnectedDevices()
08-30 16:53:24.958  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:53:24.959  1045  1045 D BluetoothA2dp: Proxy object connected
08-30 16:53:24.961  6963  6983 V BluetoothMapService: getConnectedDevices()
08-30 16:53:24.961  1864  1864 D BluetoothHeadset: Proxy object connected
,08-30 16:53:24.963  1045  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,08-30 16:53:24.964  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 16:53:24.967  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:24.967  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:24.973  6600  6600 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 16:53:24.976  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:24.977  1953  2176 D LGBluetoothAPIService: Message: 1
,08-30 16:53:24.977  1953  2176 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-30 16:53:24.981  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:24.983  1045  1045 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 16:53:24.984  1045  1120 D BluetoothManagerService: Message: 40
08-30 16:53:24.984  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 16:53:24.985  6805  6805 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 16:53:24.986  6963  6963 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:24.986  6963  6963 D BluetoothMapService: STATE_ON
08-30 16:53:24.986  6963  6963 V BluetoothMapService: Handler(): got msg=1
08-30 16:53:24.986  6963  6963 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 16:53:24.987  1953  2176 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 16:53:24.988  6963  7566 D BluetoothMapMasInstance: MAS initSocket()
08-30 16:53:24.989  6963  7566 D BluetoothMapMasInstance:   masId = 00
08-30 16:53:24.989  6963  7566 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 16:53:24.989  6963  7566 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 16:53:24.989  6963  7566 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 16:53:24.991  1045  1120 D BluetoothManagerService: Message: 30
,08-30 16:53:24.991  1045  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:24.992  6963  7566 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:24.994  6963  7566 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 16:53:24.994  6963  7566 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 16:53:24.994  6963  7566 D BluetoothMapMasInstance: Accepting socket connection...
08-30 16:53:24.997  6963  7429 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:53:24.997  6963  7429 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 16:53:25.003  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:25.004  6805  6805 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 16:53:25.004  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:25.005  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:25.005  6963  6963 V BluetoothPbapService: Pbap Service onCreate
,08-30 16:53:25.005  6963  6963 V BluetoothPbapService: Starting PBAP service
08-30 16:53:25.007  6963  6963 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 16:53:25.007  6963  6963 V BluetoothPbapService: Handler(): got msg=1
08-30 16:53:25.007  1045  1120 D BluetoothManagerService: Message: 30
08-30 16:53:25.008  6963  6963 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 16:53:25.009  6963  7569 V BluetoothPbapService: Pbap Service initSocket
08-30 16:53:25.009  6963  6963 V BluetoothPbapService: Pbap Service onBind
08-30 16:53:25.010  1045  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:25.010  6963  6963 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:25.011  6963  6963 V BluetoothPbapService: state: 12
08-30 16:53:25.012  6963  6963 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 16:53:25.012  6963  6963 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 16:53:25.013  1953  1953 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 16:53:25.014  1953  2176 D LGBluetoothAPIService: Message: 100
08-30 16:53:25.014  1953  2176 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 16:53:25.014  6963  7569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:25.014  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 16:53:25.016  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:53:25.017  6963  7569 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 16:53:25.019  6963  7569 V BluetoothPbapService: Succeed to create listening socket 
08-30 16:53:25.020  6963  7569 V BluetoothPbapService: Accepting socket connection...
,08-30 16:53:25.021  6805  6805 D BluetoothA2dp: Proxy object connected
08-30 16:53:25.021  6805  6805 D A2dpProfile: Bluetooth service connected
08-30 16:53:25.023  6963  6963 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:25.024  6963  6963 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:25.024  6963  6963 V BluetoothPbapReceiver: ***********state = 12
08-30 16:53:25.024  6805  6805 D BluetoothPbap: Proxy object connected
08-30 16:53:25.024  6805  6805 D PbapServerProfile: Bluetooth service connected
08-30 16:53:25.024  6805  6805 D BluetoothHeadset: Proxy object connected
08-30 16:53:25.025  6805  6805 D HeadsetProfile: Bluetooth service connected
08-30 16:53:25.027  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:53:25.027  2246  2246 D c       : Getting all permits...
08-30 16:53:25.027  2246  2246 D a       : Opening database...
08-30 16:53:25.030  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 16:53:25.031  2246  2246 D a       : Opening database auth.proximity.permit_store...
,08-30 16:53:25.033  2246  2246 D a       : Closing database...
08-30 16:53:25.043  6805  6805 D BluetoothPermissionRequest: onReceive
,08-30 16:53:25.045  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 16:53:25.047  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:53:25.051  6963  6963 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 16:53:25.052  6963  6963 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 16:53:25.058  7221  7257 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 16:53:25.058  6963  6963 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 16:53:25.079  6963  6963 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:53:25.079  6963  6963 V BtOppService: onCreate
,08-30 16:53:25.083  6963  6963 V BluetoothOppNotification: send message
08-30 16:53:25.086  6963  6963 V BtOppService: Starting RfcommListener
,08-30 16:53:25.093  6963  6963 D BluetoothOppPreference: Dumping Names:  
08-30 16:53:25.093  6963  6963 D BluetoothOppPreference: {}
08-30 16:53:25.093  6963  6963 D BluetoothOppPreference: Dumping Channels:  
08-30 16:53:25.093  6963  6963 D BluetoothOppPreference: {}
,08-30 16:53:25.095  6963  6963 V BtOppService: onStartCommand
08-30 16:53:25.096  6963  7580 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:53:25.100  6963  6963 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:25.100  6963  6963 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 16:53:25.101  6963  7580 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:53:25.105  6963  6963 V BluetoothOppNotification: new notify threadi!
08-30 16:53:25.106  6963  7577 V BtOppService: Deleted complete outbound shares, number =  0
,08-30 16:53:25.106  6963  6963 V BluetoothOppNotification: send delay message
08-30 16:53:25.107  6963  6963 V BtOppService: start RfcommListener
08-30 16:53:25.108  6963  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 16:53:25.111  6963  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d8ca471 on behalf of 
08-30 16:53:25.113  6963  7577 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 16:53:25.113  6963  7577 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 16:53:25.114  6963  7580 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:53:25.114  6963  7580 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:53:25.114  6963  6963 V BtOppService: RfcommListener started
08-30 16:53:25.114  6963  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f62a256 on behalf of 
08-30 16:53:25.115  6963  7577 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ef982d7 on behalf of 
08-30 16:53:25.115  6963  7582 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 16:53:25.116  1045  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:25.118  6963  7582 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:25.118  6963  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6467c4 on behalf of 
08-30 16:53:25.118  6963  7581 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 16:53:25.119  6963  7580 V BluetoothOppNotification: update too frequent, put in queue
,08-30 16:53:25.120  6963  7582 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-30 16:53:25.120  6963  7582 V BtOppRfcommListener: Started RFCOMM listener....
08-30 16:53:25.120  6963  7582 I BtOppRfcommListener: Accept thread started.
08-30 16:53:25.120  6963  7582 V BtOppRfcommListener: Accepting connection...
08-30 16:53:25.121  6963  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 16:53:25.124  6963  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@af616ad on behalf of 
08-30 16:53:25.124  6963  7580 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:53:25.125  6963  7581 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 16:53:25.127  6963  7581 V BluetoothOppNotification: outbound notification was removed.
08-30 16:53:25.127  6963  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:53:25.129  6963  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c7e8de2 on behalf of 
08-30 16:53:25.130  6963  7581 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:53:25.131  6963  7581 V BluetoothOppNotification: inbound notification was removed.
08-30 16:53:25.131  6963  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 16:53:25.134  6963  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fe97573 on behalf of 
08-30 16:53:25.137  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:25.137  6963  6963 V BluetoothFtpService: Ftp Service onCreate
08-30 16:53:25.137  6963  6963 I BluetoothFtpService: Ftp Service onCreate
08-30 16:53:25.137  6963  6963 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:53:25.137  6963  6963 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:25.137  6963  6963 V BluetoothFtpService: Starting Listening on sockets
08-30 16:53:25.138  6963  6963 V BtOppService: ContentObserver received notification
08-30 16:53:25.138  6963  6963 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:25.138  6963  6963 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:25.138  6963  6963 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:25.138  6963  6963 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:25.138  6963  6963 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 16:53:25.138  6963  6963 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:53:25.140  6963  7583 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:53:25.140  6963  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:53:25.141  6963  6963 V BtOppService: ContentObserver received notification
08-30 16:53:25.141  6963  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@40a70a9 on behalf of 
08-30 16:53:25.141  6963  6963 V BluetoothFtpService: Handler(): got msg=1
08-30 16:53:25.142  6963  7583 V BluetoothOppNotification: update too frequent, put in queue
08-30 16:53:25.142  6963  6963 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 16:53:25.142  6963  6963 V BluetoothFtpService: Ftp Service initSocket
08-30 16:53:25.143  6963  7583 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:53:25.143  6963  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:53:25.155  1045  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:25.156  6963  6963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:53:25.161  6963  6963 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 16:53:25.163  6963  7584 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-30 16:53:25.177  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:25.178  6963  6963 V BluetoothSapService: Sap Service onCreate
,08-30 16:53:25.180  6963  6963 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:25.180  6963  6963 V BluetoothSapService: state: 12
08-30 16:53:25.181  6963  6963 V BluetoothSapService: Starting SAP server process
08-30 16:53:25.183  6963  6963 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 16:53:25.170  7585  7585 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:25.170  7585  7585 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:25.187  6963  7586 V BluetoothSapService: Sap Service initRfcommSocket
08-30 16:53:25.188  1045  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:25.190  6963  7586 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:25.192  6963  7586 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 16:53:25.192  6963  7586 V BluetoothSapService: Succeed to create listening socket 
08-30 16:53:25.192  6963  7586 V BluetoothSapService: Accepting socket connection...
,08-30 16:53:25.196  7585  7585 V BT_SAP  : Event pipe created
,08-30 16:53:25.196  7585  7585 V BT_SAP  : create_server_socket qcom.sap.server
08-30 16:53:25.196  7585  7585 V BT_SAP  : created socket fd 6
08-30 16:53:25.308  1045  2011 I art     : Explicit concurrent mark sweep GC freed 87441(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.220ms total 163.303ms
,08-30 16:53:25.308  6963  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@af06e65 on behalf of 
,08-30 16:53:25.309  6963  7583 V BluetoothOppNotification: update too frequent, put in queue
,08-30 16:53:25.312  6963  7583 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-30 16:53:25.568  1045  1375 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:53:25.568  1045  1375 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:53:25.633  1045  1424 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 16:53:25.634  1045  1424 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 16:53:25.919  1045  1728 I ActivityManager: Killing 7380:com.lge.bnr/1000 (adj 15): empty #17
,08-30 16:53:25.960  1045  2079 W libprocessgroup: failed to open /acct/uid_1000/pid_7380/cgroup.procs: No such file or directory
,08-30 16:53:25.971  1045  1061 I ActivityManager: Killing 6722:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 16:53:25.989  6872  6872 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 16:53:25.990  6872  6872 W System.err: android.os.DeadObjectException
08-30 16:53:25.990  6872  6872 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:53:25.990  6872  6872 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 16:53:25.990  6872  6872 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:25.990  6872  6872 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:25.990  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:25.990  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:25.990  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:25.990  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 16:53:25.991  6872  6872 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 16:53:25.991  6872  6872 W System.err: android.os.DeadObjectException
08-30 16:53:25.991  6872  6872 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:53:25.991  6872  6872 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:53:25.991  6872  6872 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 16:53:25.991  6872  6872 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 16:53:25.991  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 16:53:25.991  6872  6872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 16:53:25.991  6872  6872 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:53:25.991  6872  6872 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:53:25.991  6872  6872 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:25.992  6872  6872 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:25.992  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:25.992  6872  6872 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:25.992  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:25.992  6872  6872 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 16:53:25.992  6872  6872 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 16:53:25.992  6872  6872 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 16:53:26.026  1045  1976 W libprocessgroup: failed to open /acct/uid_1000/pid_6722/cgroup.procs: No such file or directory
08-30 16:53:26.026  1045  1976 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 16:53:26.036  6872  6872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 16:53:26.036  6872  6872 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 16:53:26.089  1045  1728 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7597 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 16:53:26.089  6872  6872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 16:53:26.107  6963  6963 V BluetoothOppNotification: new notify threadi!
08-30 16:53:26.107  6963  6963 V BluetoothOppNotification: send delay message
,08-30 16:53:26.122  6963  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 16:53:26.144  6963  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@311ff73a on behalf of 
08-30 16:53:26.145  6963  7607 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 16:53:26.162  6963  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 16:53:26.169  6963  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18cc1feb on behalf of 
08-30 16:53:26.170  6963  7607 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 16:53:26.200  6963  7607 V BluetoothOppNotification: outbound notification was removed.
08-30 16:53:26.200  6963  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:53:26.202  6963  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b656148 on behalf of 
08-30 16:53:26.202  6963  7607 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:53:26.204  6963  7607 V BluetoothOppNotification: inbound notification was removed.
08-30 16:53:26.204  6963  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:53:26.205  6963  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@137e8be1 on behalf of 
08-30 16:53:26.211  7597  7597 D UEI.SmartControl: Quickset Services start...
,08-30 16:53:26.217  7597  7597 I UEI.SmartControl: Manufacture = LGE
08-30 16:53:26.217  7597  7597 D UEI.SmartControl: Id = LGNevo
08-30 16:53:26.219  7597  7597 D UEI.SmartControl: File observer start...
08-30 16:53:26.221  7597  7597 E UEI.SmartControl: IR Port is disabled: false
,08-30 16:53:26.221  7597  7597 D UEI.SmartControl: Starting file observer...
08-30 16:53:26.221  7597  7597 D UEI.SmartControl: Extracting JNI libs...
08-30 16:53:26.221  7597  7597 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 16:53:26.329  7597  7597 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 16:53:26.330  7597  7597 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 16:53:26.330  7597  7597 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 16:53:26.369  7597  7597 I UEI.SmartControl: --- Selecting new region: 6
,08-30 16:53:26.371  7597  7597 I UEI.SmartControl: Model = LG-D855
,08-30 16:53:26.374  7597  7597 D UEI.SmartControl: QS Service created
,08-30 16:53:26.391  7597  7597 I UEI.SmartControl: Service initServices...
,08-30 16:53:26.396  7597  7597 D UEI.SmartControl: QS start get config
,08-30 16:53:26.445  7597  7597 D UEI.SmartControl: Loading JNI Libs...
,08-30 16:53:26.561  1045  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:26.561  1045  1061 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@aa8ec36 mBinding = false
,08-30 16:53:26.588  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:26.588  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 16:53:26.591  1045  1045 D Ulp_jni : JNI:system_update. Event-4
08-30 16:53:26.592  1045  1120 D BluetoothManagerService: Message: 2
08-30 16:53:26.592  1045  1120 D BluetoothManagerService: Sending off request.
08-30 16:53:26.593  6963  6982 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 16:53:26.594  6963  7425 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 16:53:26.594  6963  7425 D BluetoothAdapterProperties: Setting state to 13
08-30 16:53:26.594  6963  7425 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:53:26.594  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:26.594  6963  7425 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 16:53:26.594  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 16:53:26.594  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 16:53:26.594  6963  7425 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 16:53:26.596  6963  7429 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:53:26.596  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.597  6963  7425 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 16:53:26.598  6963  7582 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:26.598  6963  7425 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:53:26.598  6963  7584 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:26.598  6963  7569 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:26.599  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 16:53:26.599  6963  7586 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:26.600  6963  7494 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 16:53:26.603  6963  7566 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 16:53:26.611  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 16:53:26.611  6963  7494 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:53:26.613  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:26.616  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 16:53:26.618  6963  6963 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.618  6963  6963 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:53:26.618  6963  6963 V BtOppService: Receiver DISABLED_ACTION 
08-30 16:53:26.618  6963  6963 V BluetoothMapService: Handler(): got msg=4
08-30 16:53:26.618  6963  6963 D BluetoothMapService: MAP Service closeService in
08-30 16:53:26.619  6963  6963 D BluetoothMapMasInstance: MAP Service shutdown
08-30 16:53:26.619  6963  6963 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:53:26.619  6963  6963 V BluetoothMapService: MAP Service closeService out
08-30 16:53:26.619  6963  6963 I BtOppRfcommListener: stopping Accept Thread
08-30 16:53:26.619  6963  6963 V BtOppRfcommListener: close mBtServerSocket
08-30 16:53:26.619  6963  6963 V BtOppRfcommListener: waiting for thread to terminate
08-30 16:53:26.621  6963  7582 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 16:53:26.624  6963  6963 V BtOppRfcommListener: done waiting for thread to terminate
08-30 16:53:26.626  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:26.626  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:26.627  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:26.627  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:26.629  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:53:26.632  6963  6963 V BtOppService: onDestroy
08-30 16:53:26.634  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:26.634  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:53:26.636  6600  6600 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:53:26.636  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:26.638  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:26.640  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:26.644  6963  6963 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 16:53:26.646  6963  6963 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:26.646  6963  6963 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.646  6963  6963 V BluetoothPbapReceiver: ***********state = 13
,08-30 16:53:26.649  6963  6963 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 16:53:26.654  6963  6963 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.654  6963  6963 V BluetoothPbapService: state: 13
08-30 16:53:26.654  6963  6963 V BluetoothPbapService: Pbap Service closeService in
08-30 16:53:26.657  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 16:53:26.658  6963  6963 V BluetoothPbapService: successfully stopped pbap service
08-30 16:53:26.658  6963  6963 V BluetoothPbapService: Pbap Service closeService out
08-30 16:53:26.659  6963  6963 V BluetoothPbapService: Pbap Service onDestroy
08-30 16:53:26.659  6963  6963 V BluetoothPbapService: Pbap Service closeService in
08-30 16:53:26.659  6963  6963 V BluetoothPbapService: Pbap Service closeService out
08-30 16:53:26.659  6963  6963 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-30 16:53:26.660  6805  6805 D BluetoothPbap: Proxy object disconnected
08-30 16:53:26.660  6805  6805 D PbapServerProfile: Bluetooth service disconnected
08-30 16:53:26.663  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:53:26.676  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:53:26.680  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 16:53:26.681  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 16:53:26.686  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:53:26.688  6963  6963 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 16:53:26.688  6963  6963 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 16:53:26.689  6963  6963 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-30 16:53:26.692  6963  6963 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.692  6963  6963 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 16:53:26.693  6963  6963 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:53:26.693  6963  6963 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.693  6963  6963 V BluetoothFtpService: Ftp Service closeService
08-30 16:53:26.693  6963  6963 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 16:53:26.694  6963  6963 V BluetoothFtpService: successfully stopped ftp service
08-30 16:53:26.694  6963  6963 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:26.694  6963  6963 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:26.694  6963  6963 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:26.695  6963  6963 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.695  6963  6963 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 16:53:26.695  6963  6963 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:53:26.696  6963  6963 V BluetoothFtpService: Ftp Service onDestroy
08-30 16:53:26.696  6963  6963 V BluetoothFtpService: Ftp Service closeService
08-30 16:53:26.701  6963  6963 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:26.701  6963  6963 V BluetoothSapService: state: 13
08-30 16:53:26.701  1589  1589 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 16:53:26.701  6963  6963 V BluetoothSapService: Stopping SAP server process
08-30 16:53:26.702  1589  1589 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 16:53:26.702  6963  6963 V BluetoothSapService: Sap Service closeSapService in
08-30 16:53:26.702  6963  6963 V BluetoothSapService: Close listen Socket : 
08-30 16:53:26.702  6963  6963 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:53:26.702  6963  6963 V BluetoothSapService: Close sapd  Socket : 
,08-30 16:53:26.711  1589  1589 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 308
08-30 16:53:26.711  1589  1589 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 16:53:26.712  1953  2131 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 16:53:26.712  1953  2131 D LEDHandler: Battery Level Remaining: 100%
08-30 16:53:26.712  1953  2131 D LEDHandler: Battery Temp: 308, mChargingStatus=5, mChargingStop=false
08-30 16:53:26.713  1589  1589 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 16:53:26.715  1045  1482 D WifiController: battery changed pluggedType: 2
08-30 16:53:26.716  6963  6963 V BluetoothSapService: Sap Service closeSapService out
,08-30 16:53:26.716  6963  6963 V BluetoothSapService: Sap Service onDestroy
08-30 16:53:26.716  6963  6963 V BluetoothSapService: Sap Service closeSapService in
08-30 16:53:26.716  6963  6963 V BluetoothSapService: Close listen Socket : 
08-30 16:53:26.716  6963  6963 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:53:26.716  6963  6963 V BluetoothSapService: Close sapd  Socket : 
08-30 16:53:26.716  6963  7464 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 16:53:26.716  6963  6963 V BluetoothSapService: Sap Service closeSapService out
08-30 16:53:26.716  1589  1589 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 16:53:26.717  1589  1589 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 16:53:26.838  7597  7597 I UEI.SmartControl: Supports setup maps: true
,08-30 16:53:26.842  7597  7597 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 16:53:26.842  7597  7597 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 16:53:26.842  7597  7597 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 16:53:26.842  7597  7597 I UEI.SmartControl: ### init IR Blaster...
,08-30 16:53:26.849  7597  7597 D serial_port: Configuring serial port
08-30 16:53:26.852  7597  7597 E UEI.SmartControl: UEIBLaster setting for 616
08-30 16:53:26.852  7597  7597 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 16:53:26.852  7597  7597 I UEI.SmartControl: configuring settings for MAXQ616
08-30 16:53:26.852  7597  7597 I UEI.SmartControl: Get version...
,08-30 16:53:26.869  7597  7652 D UEI.SmartControl: serial port data available: 21
,08-30 16:53:26.896  7597  7597 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 16:53:26.896  7597  7597 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 16:53:26.897  7597  7597 I UEI.SmartControl: QS saving settings...
,08-30 16:53:26.897  7597  7597 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 16:53:26.914  7597  7652 D UEI.SmartControl: serial port data available: 4
,08-30 16:53:26.951  7597  7655 I UEI.SmartControl: Device manager: loading config....
,08-30 16:53:26.952  7597  7655 D UEI.SmartControl: ----------- loading internal config...
,08-30 16:53:26.958  7597  7597 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 16:53:26.961  7597  7597 E UEI.SmartControl: Services init done
08-30 16:53:26.961  7597  7597 D UEI.SmartControl: QS Service init finished
08-30 16:53:26.966  7597  7597 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 16:53:26.967  7597  7597 D UEI.SmartControl: QS Service version code: 201091
,08-30 16:53:26.969  7597  7597 D UEI.SmartControl: Service requested: Control
08-30 16:53:26.982  7597  7655 E UEI.SmartControl: Loading SETTINGS...
,08-30 16:53:26.986  7597  7597 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 16:53:26.990  6872  6872 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 16:53:26.991  7597  7614 I UEI.SmartControl: ------ IControl API: 11
08-30 16:53:26.991  1045  2333 I ActivityManager: Killing 6872:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 16:53:26.994  7597  7614 I UEI.SmartControl: Registering callback...
,08-30 16:53:27.007  7597  7655 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 16:53:27.029  7597  7654 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 16:53:27.029  7597  7654 D UEI.SmartControl: -----service ready thread exits
,08-30 16:53:27.049  1045  1943 W libprocessgroup: failed to open /acct/uid_10112/pid_6872/cgroup.procs: No such file or directory
,08-30 16:53:27.049  7597  7597 D UEI.SmartControl: Internal service binding...
,08-30 16:53:27.509  6963  7429 D bt_hci_bdroid: cleanup
,08-30 16:53:27.516  6963  7496 I bt_lpm  : LPM is already off!!!
08-30 16:53:27.518  6963  7534 I bt_userial_mct: exiting userial_read_thread
08-30 16:53:27.519  6963  7534 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 16:53:27.520  6963  7494 W bt-btif : ag scb idx 1 not allocated
08-30 16:53:27.520  6963  7494 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 16:53:27.520  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:27.520  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:53:27.521  6963  7494 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:53:27.522  6963  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:53:27.522  6963  7494 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:53:27.526  6963  7429 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 16:53:27.529  6963  7496 I bt_vendor: hw_epilog_process
,08-30 16:53:27.532  6963  7429 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 16:53:27.532  6963  7429 D bt_userial_mct: userial_close
08-30 16:53:27.532  6963  7429 E bt_userial_mct: pthread_join() FAILED result:3
08-30 16:53:27.532  6963  7429 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 16:53:27.537  6963  7429 D bt_hci_bdroid: set_power 0
08-30 16:53:27.538  6963  7429 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 16:53:27.538  6963  7429 I bt_vendor: bluetooth satus is on
08-30 16:53:27.538  6963  7429 I bt_vendor: bt-vendor : resetting BT status
08-30 16:53:27.538  6963  7429 I bt_vendor: Starting hciattach daemon
08-30 16:53:27.538  6963  7429 I bt_vendor: try to set false
08-30 16:53:27.540  6963  7429 I bt_vendor: Starting hciattach daemon
08-30 16:53:27.540  6963  7429 I bt_vendor: try to set false
,08-30 16:53:27.544  6963  7429 I bt_vendor: cleanup
08-30 16:53:27.545  6963  7494 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 16:53:27.545  6963  7429 I GKI_LINUX: GKI_exit_task 0 done
08-30 16:53:27.545  6963  7429 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 16:53:27.547  6963  7425 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 16:53:27.554  6963  6963 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:53:27.559  6963  6963 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:53:27.559  6963  6963 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:53:27.559  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.560  6963  7464 D HeadsetStateMachine: Exit Disconnected: -1
08-30 16:53:27.562  6963  7425 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 16:53:27.563  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:27.563  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:27.563  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:27.563  1045  1045 D BluetoothHeadset: Proxy object disconnected
08-30 16:53:27.563  1045  1045 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 16:53:27.565  6963  6963 D A2dpService: Received stop request...Stopping profile...
08-30 16:53:27.566  6963  7485 D A2dpStateMachine: Exit Disconnected: -1
,08-30 16:53:27.570  6963  6963 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 16:53:27.573  6963  6963 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 16:53:27.573  6963  6963 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:53:27.573  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.575  1045  1045 D BluetoothA2dp: Proxy object disconnected
08-30 16:53:27.575  1045  1045 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 16:53:27.575  6963  6963 D HidService: Received stop request...Stopping profile...
08-30 16:53:27.575  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.578  6963  6963 D HealthService: Received stop request...Stopping profile...
,08-30 16:53:27.578  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.582  6963  6963 D PanService: Received stop request...Stopping profile...
08-30 16:53:27.584  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.585  6963  6963 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:53:27.586  6963  6963 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 16:53:27.587  6963  6963 D BtGatt.GattService: stop()
08-30 16:53:27.587  6963  6963 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 16:53:27.588  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.590  6963  6963 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:53:27.590  6963  6963 D BluetoothMapService: stop()
,08-30 16:53:27.593  6963  6963 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 16:53:27.593  6963  6963 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 16:53:27.593  6963  6963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1f429c
08-30 16:53:27.595  6963  6963 D HeadsetStateMachine: Unbinding service...
08-30 16:53:27.596  6963  6963 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:53:27.596  6963  6963 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:53:27.596  6963  6963 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:53:27.596  6963  6963 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:53:27.596  6963  6963 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:53:27.597  6963  6963 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:53:27.597  6963  6963 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:53:27.597  6963  6963 I BluetoothA2dpServiceJni: cleanupNative
08-30 16:53:27.597  6963  7486 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 16:53:27.598  6963  6963 I GKI_LINUX: GKI_exit_task 2 done
08-30 16:53:27.598  6963  6963 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 16:53:27.598  6963  6963 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:53:27.598  6963  6963 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:53:27.599  6963  6963 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:53:27.599  6963  6963 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:53:27.599  6963  6963 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:53:27.599  6963  6963 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:53:27.599  6963  6963 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:53:27.602  6963  6963 V BluetoothMapService: Handler(): got msg=4
08-30 16:53:27.602  6963  6963 D BluetoothMapService: MAP Service closeService in
08-30 16:53:27.602  6963  6963 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:53:27.602  6963  6963 V BluetoothMapService: MAP Service closeService out
,08-30 16:53:27.607  6963  7425 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 16:53:27.607  6963  7425 D BluetoothAdapterProperties: Setting state to 10
08-30 16:53:27.607  6963  7425 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 16:53:27.608  6963  6963 D BluetoothMapService: cleanup()
08-30 16:53:27.608  6963  6963 D BluetoothMapService: MAP Service closeService in
08-30 16:53:27.608  6963  6963 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:53:27.608  6963  6963 V BluetoothMapService: MAP Service closeService out
08-30 16:53:27.610  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:27.610  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 16:53:27.610  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 16:53:27.611  6963  7425 I BluetoothAdapterState: Entering OffState
08-30 16:53:27.611  6805  7551 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:53:27.612  6805  7551 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:53:27.613  1045  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:27.613  6805  7551 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:53:27.614  6805  7551 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:53:27.614  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:53:27.618  1864  2547 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:27.618  1045  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:53:27.618  6805  7551 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:53:27.620  6805  7551 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:27.620  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:53:27.621  1045  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 16:53:27.621  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 16:53:27.623  1045  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 16:53:27.623  1045  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 16:53:27.623  1045  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@aa8ec36 mBinding = false
08-30 16:53:27.624  1045  1120 D BluetoothManagerService: Sending unbind request.
08-30 16:53:27.629  6963  7429 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 16:53:27.631  6963  6963 I GKI_LINUX: GKI_exit_task 1 done
08-30 16:53:27.631  6963  6963 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 16:53:27.633  6963  6963 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 16:53:27.633  6963  6963 I art     : --- WEIRD: removing null entry 248
08-30 16:53:27.633  6963  6963 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 16:53:27.633  6963  6963 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 16:53:27.634  6963  6963 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 16:53:27.635  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 16:53:27.637  6963  6963 I art     : System.exit called, status: 0
08-30 16:53:27.637  6963  6963 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 16:53:27.656   329  1382 V AudioFlinger: 6963 died, releasing its sessions
08-30 16:53:27.656   329  1382 V AudioFlinger:  pid 1864 @ 0
08-30 16:53:27.656   329  1382 V AudioFlinger:  pid 3317 @ 1
08-30 16:53:27.656   329  1382 V AudioFlinger:  pid 3317 @ 2
,08-30 16:53:27.660  1953  1953 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-30 16:53:27.661  1953  2176 D LGBluetoothAPIService: Message: 101
,08-30 16:53:27.661  1953  2176 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 16:53:27.661  1953  2176 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,08-30 16:53:27.661  1953  2176 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-30 16:53:27.662  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 16:53:27.669  1045  2012 I ActivityManager: Process com.android.bluetooth (pid 6963) has died
,08-30 16:53:27.676  1045  2012 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-30 16:53:27.676  1045  2012 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-30 16:53:27.681  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:27.681  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:27.682  1953  2176 D LGBluetoothAPIService: Message: 2
08-30 16:53:27.682  1953  2176 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 16:53:27.683  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:27.684  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:27.685  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 16:53:27.685  6805  6805 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 16:53:27.688  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 16:53:27.691  1589  1589 D BluetoothAdapter: 232577185: getState() :  mService = null. Returning STATE_OFF
08-30 16:53:27.692  1589  1589 D BluetoothAdapter: 232577185: getState() :  mService = null. Returning STATE_OFF
08-30 16:53:27.750  1045  1919 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7686 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 16:53:27.752  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:53:27.811  7686  7686 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 16:53:27.812  7686  7686 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:27.812  7686  7686 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 16:53:27.813  7686  7686 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 16:53:27.832  7686  7686 D BluetoothAdapterApp: Loading JNI Library
,08-30 16:53:27.869  7686  7686 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@6be1704 Instance Count = 1
,08-30 16:53:27.875  7686  7686 D BluetoothAdapterApp: onCreate
08-30 16:53:27.899  7686  7686 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 16:53:27.900  7686  7686 D ProfileConfigQcom: Adding HeadsetService
08-30 16:53:27.900  7686  7686 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-30 16:53:27.900  7686  7686 D ProfileConfigQcom: Adding A2dpService
08-30 16:53:27.900  7686  7686 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 16:53:27.900  7686  7686 D ProfileConfigQcom: Adding HidService
08-30 16:53:27.901  7686  7686 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 16:53:27.901  7686  7686 D ProfileConfigQcom: Adding HealthService
08-30 16:53:27.901  7686  7686 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 16:53:27.902  7686  7686 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 16:53:27.902  7686  7686 D ProfileConfigQcom: Adding PanService
08-30 16:53:27.903  7686  7686 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 16:53:27.903  7686  7686 D ProfileConfigQcom: Adding GattService
08-30 16:53:27.903  7686  7686 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 16:53:27.903  7686  7686 D ProfileConfigQcom: Adding BluetoothMapService
08-30 16:53:27.904  7686  7686 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 16:53:27.905  7686  7686 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:27.906  7686  7686 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:27.906  7686  7686 V BluetoothPbapReceiver: ***********state = 10
08-30 16:53:27.908  7686  7686 V LGMDMManagerInternal: Create singleton instance
08-30 16:53:27.977  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:53:27.979  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 16:53:27.984  7686  7686 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-30 16:53:27.984  7686  7686 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 16:53:27.988  1953  1953 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 16:53:27.988  1953  2176 D LGBluetoothAPIService: Message: 100
08-30 16:53:27.988  1953  2176 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 16:53:28.006  6805  6805 D BluetoothPermissionRequest: onReceive
,08-30 16:53:28.014  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 16:53:28.014  6805  6805 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 16:53:28.025  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 16:53:28.040  7686  7686 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 16:53:28.049  7686  7686 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:53:28.056  7686  7686 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:28.057  7686  7686 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:28.058  7686  7686 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:28.060  7686  7686 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:28.061  7686  7686 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 16:53:28.077  7501  7501 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 16:53:29.566  1045  1365 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 16:53:29.570  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 16:53:29.592  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:29.592  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:53:29.681  1045  1114 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7715 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 16:53:29.703  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 16:53:29.704  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-30 16:53:29.710  1045  1045 D administrator: Handling package changes for user 0
08-30 16:53:29.714  2080  2080 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 16:53:29.736  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 16:53:29.778  7715  7715 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 16:53:29.834  1045  1045 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 16:53:29.835  1045  1045 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 16:53:29.854  7715  7715 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:29.854  7715  7715 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:29.905  1045  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 16:53:29.912  1045  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 16:53:29.920  2080  2080 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 16:53:29.922  2489  2489 V GmsNetworkLocationProvi: DISABLE
,08-30 16:53:29.954  1045  1111 D LocationProviderProxy: applying state to connected service
,08-30 16:53:29.956  2489  2489 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 16:53:29.966  7715  7758 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 16:53:29.966  7715  7758 I Babel   : MmsConfig.loadMmsSettings
,08-30 16:53:29.972  7715  7758 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 16:53:29.973  7715  7758 I Babel   : MmsConfig.loadFromDatabase
,08-30 16:53:29.987  7715  7758 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 16:53:29.987  7715  7758 I Babel   : MmsConfig.loadFromResources
08-30 16:53:29.989  7715  7758 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 16:53:29.990  7715  7758 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 16:53:30.006  7715  7757 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 16:53:30.008  7715  7757 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 16:53:30.012  7715  7757 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 16:53:30.018  7715  7715 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:53:30.034  7715  7757 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 16:53:30.036  7715  7757 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 16:53:30.038  7715  7757 W AudioCapabilities: Unsupported mime audio/evrc
08-30 16:53:30.049  1823  7762 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 16:53:30.049  1823  7762 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 16:53:30.053  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
08-30 16:53:30.058  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3e45db6e
08-30 16:53:30.058  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:53:30.058  7010  7010 D AppUp4:CustFacade: isPhone : true
08-30 16:53:30.059  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:53:30.059  7010  7010 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 16:53:30.061  1823  4706 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-30 16:53:30.065  7715  7757 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 16:53:30.068  7715  7757 W VideoCapabilities: Unsupported mime video/divx
08-30 16:53:30.070  7715  7757 W VideoCapabilities: Unsupported mime video/divx311
08-30 16:53:30.072  7715  7757 W VideoCapabilities: Unsupported mime video/divx4
,08-30 16:53:30.086  7715  7757 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 16:53:30.102  7715  7757 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 16:53:30.107  7715  7757 W AudioCapabilities: Unsupported mime audio/eac3
08-30 16:53:30.108  7715  7757 W AudioCapabilities: Unsupported mime audio/ac3
08-30 16:53:30.109  1045  1919 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7766 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 16:53:30.109  7715  7757 W AudioCapabilities: Unsupported mime audio/g726
08-30 16:53:30.111  7715  7757 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-30 16:53:30.112  1045  1943 I ActivityManager: Killing 7345:com.lge.sync/1000 (adj 15): empty #17
08-30 16:53:30.115  7715  7757 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 16:53:30.118  7715  7757 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 16:53:30.119  7715  7757 W VideoCapabilities: Unsupported mime video/theora
08-30 16:53:30.121  7715  7757 W VideoCapabilities: Unsupported mime video/mjpg
08-30 16:53:30.134  1045  1482 D WifiService: Client connection lost with reason: 4
,08-30 16:53:30.229  1045  1976 W libprocessgroup: failed to open /acct/uid_1000/pid_7345/cgroup.procs: No such file or directory
,08-30 16:53:30.271  7766  7766 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:30.272  7766  7766 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:30.272  7766  7766 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 16:53:30.273  7766  7766 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 16:53:30.274  7766  7766 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 16:53:30.359  7766  7766 I SystemConfig: BUILD Country: EU
08-30 16:53:30.359  7766  7766 I SystemConfig: BUILD Operator: OPEN
,08-30 16:53:30.422  1045  1563 I ActivityManager: Killing 7037:com.lge.email/u0a23 (adj 15): empty #17
,08-30 16:53:30.521  1045  2079 W libprocessgroup: failed to open /acct/uid_10023/pid_7037/cgroup.procs: No such file or directory
,08-30 16:53:30.536  7766  7787 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 16:53:30.536  7766  7787 I SystemConfig: existFile = false
,08-30 16:53:30.537  7766  7787 I SystemConfig: canReadFile = false
08-30 16:53:30.540  7766  7787 I SystemConfig: systemFeature RCS result false
08-30 16:53:30.540  7766  7787 D SystemConfig: refreshRcsSupport() :false
08-30 16:53:30.599  1045  1563 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7789 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 16:53:30.637  1045  1505 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-30 16:53:30.668  7789  7789 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:30.669  7789  7789 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 16:53:30.669  7789  7789 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 16:53:30.669  7789  7789 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 16:53:30.773  7789  7789 I AppConfig: Total System Memory = 2995761152
,08-30 16:53:30.783  7789  7789 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-30 16:53:30.898  1045  1919 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7808 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 16:53:30.900  1045  1919 I ActivityManager: Killing 6911:com.lge.formmanager/u0a26 (adj 15): empty #17
08-30 16:53:31.041  1045  1976 W libprocessgroup: failed to open /acct/uid_10026/pid_6911/cgroup.procs: No such file or directory
,08-30 16:53:31.235  7808  7808 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 16:53:31.354  7808  7808 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:31.355  7808  7808 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:31.412  7808  7808 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 16:53:31.435  7808  7808 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 16:53:31.436  7808  7808 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 16:53:31.460  7808  7808 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 16:53:31.461  7808  7808 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 16:53:31.504  1045  1735 I ActivityManager: Killing 6403:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 16:53:31.570  1045  2011 W libprocessgroup: failed to open /acct/uid_1000/pid_6403/cgroup.procs: No such file or directory
,08-30 16:53:31.617  4573  7851 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 16:53:31.665   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 29.917ms
,08-30 16:53:31.690  1045  1563 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7852 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-30 16:53:31.695   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 26.623ms
08-30 16:53:31.717   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 21.064ms
,08-30 16:53:31.729  2829  2847 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 16:53:31.735  2829  2847 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c2ea43d on behalf of 7808
,08-30 16:53:31.755  7808  7808 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 16:53:31.776  7808  7808 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 16:53:31.786  7852  7852 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-30 16:53:31.811  7852  7852 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 16:53:31.811  7852  7852 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 16:53:31.811  7852  7852 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 16:53:31.811  7852  7852 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 16:53:31.812  7852  7852 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 16:53:31.812  7852  7852 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 16:53:31.830  1045  2042 I ActivityManager: Killing 7078:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 16:53:31.953  7597  7656 D UEI.SmartControl: Internal timer expired: 1
08-30 16:53:31.954  7597  7656 D UEI.SmartControl: unbind internal service
,08-30 16:53:31.959  1045  2079 W libprocessgroup: failed to open /acct/uid_10046/pid_7078/cgroup.procs: No such file or directory
08-30 16:53:31.970  7597  7597 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 16:53:31.971  7597  7597 D UEI.SmartControl: Service.onDestroy
,08-30 16:53:31.971  7597  7597 D UEI.SmartControl: Lock is in USE false
,08-30 16:53:31.971  7597  7597 D UEI.SmartControl: unbind internal service
08-30 16:53:31.972  7597  7597 D serial_port: close(fd = 25)
,08-30 16:53:31.981  7597  7597 I UEI.SmartControl: Serial port is closed.
08-30 16:53:31.981  7597  7597 I UEI.SmartControl: Serial port is closed.
08-30 16:53:31.982  7597  7597 D UEI.SmartControl: Blaster closed
08-30 16:53:31.982  7597  7597 D UEI.SmartControl: Shut down QS...
08-30 16:53:31.982  7597  7597 D UEI.SmartControl: Stopping QS lib
08-30 16:53:31.982  7597  7597 D UEI.SmartControl: QS lib stop result = true
08-30 16:53:31.982  7597  7597 D UEI.SmartControl: Stopped QS lib
08-30 16:53:31.983  7597  7597 D UEI.SmartControl: Stopped file observer...
08-30 16:53:31.983  7597  7597 D UEI.SmartControl: QS shutdown complete
08-30 16:53:32.171  1045  1060 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:53:32.202  4573  7851 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 585 ms] updated apps [took 585 ms] 
,08-30 16:53:32.698  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:53:32.698  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@269c29d0 added. We now have 6 listener(s)
,08-30 16:53:32.698  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:53:32.710  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:32.710  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c1b5dc9 added. We now have 7 listener(s)
08-30 16:53:32.710  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:32.710  6600  6706 I System.out: IsBluetoothEnabled
08-30 16:53:32.711  1045  2333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:32.711  1045  2333 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 16:53:32.712  1045  1120 D BluetoothManagerService: Message: 2
08-30 16:53:32.715  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:32.717  1045  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:32.717  1045  1943 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 16:53:32.737  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:32.737  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:32.737  1045  1045 D Ulp_jni : JNI:system_update. Event-4
08-30 16:53:32.738  1045  1120 D BluetoothManagerService: Message: 1
08-30 16:53:32.738  1045  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 16:53:32.762  1045  1120 D BluetoothManagerService: Message: 20
08-30 16:53:32.762  1045  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c4951b6:true
,08-30 16:53:32.767  7686  7686 D BluetoothAdapterState: make
08-30 16:53:32.771  7686  7686 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 16:53:32.772  7686  7686 I bluedroid-qcom: init
08-30 16:53:32.773  7686  7903 I BluetoothAdapterState: Entering OffState
08-30 16:53:32.773  7686  7686 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 16:53:32.773  7686  7686 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 16:53:32.773  7686  7686 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:53:32.773  7686  7686 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:53:32.773  7686  7686 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 16:53:32.775  7686  7686 I bluedroid-qcom: get_profile_interface socket
08-30 16:53:32.775  7686  7686 I bluedroid-qcom: get_profile_interface map_client
,08-30 16:53:32.779  7686  7907 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 16:53:32.770  7906  7906 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:32.784  7686  7907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 16:53:32.770  7906  7906 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:32.794  1045  1045 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:53:32.794  1045  1045 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 16:53:32.799  1045  1045 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 16:53:32.799  1045  1120 D BluetoothManagerService: Message: 40
08-30 16:53:32.799  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 16:53:32.800  7686  7701 I bluedroid-qcom: config_hci_snoop_log
08-30 16:53:32.802  7906  7906 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 16:53:32.802  7906  7906 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 16:53:32.802  7906  7906 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 16:53:32.803  1045  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 16:53:32.803  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 16:53:32.804  7686  7907 D BluetoothAdapterProperties: Name is: G3
08-30 16:53:32.805  7906  7906 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 16:53:32.811  7906  7906 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 16:53:32.811  7906  7906 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 16:53:32.816  7686  7903 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 16:53:32.817  7686  7903 D BluetoothAdapterProperties: Setting state to 11
08-30 16:53:32.817  7686  7903 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 16:53:32.818  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:32.818  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 16:53:32.818  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 16:53:32.819  7686  7903 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 16:53:32.826  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:53:32.828  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:32.831  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:32.835  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 16:53:32.842  7686  7686 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:32.842  7686  7686 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:32.842  7686  7686 V BluetoothPbapReceiver: ***********state = 11
,08-30 16:53:32.864  7686  7903 D BluetoothBondStateMachine: make
08-30 16:53:32.867  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:53:32.871  7686  7903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:32.872  7686  7903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 16:53:32.872  7686  7903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:32.872  7686  7903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 16:53:32.873  7686  7903 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 16:53:32.875  7686  7920 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 16:53:32.879  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:53:32.885  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 16:53:32.888  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:53:32.893  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:53:32.896  7686  7686 D HeadsetService: Received start request. Starting profile...
08-30 16:53:32.896  7686  7686 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:53:32.897  7686  7686 D LGBluetoothHfpAdapter: Version 1.6
08-30 16:53:32.900  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:32.900  7686  7686 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:53:32.901  7686  7686 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:53:32.902  7686  7686 D HeadsetStateMachine: make
08-30 16:53:32.905  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:53:32.912  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:32.917  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:53:32.922  7686  7903 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:53:32.942  7686  7686 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:32.942  7686  7686 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:32.947  7686  7903 V LGMDMManager: Create singleton instance
08-30 16:53:32.948  7686  7686 D HeadsetStateMachine: max_hf_connections = 1
08-30 16:53:32.948  7686  7686 I bluedroid-qcom: get_profile_interface handsfree
08-30 16:53:32.948  7686  7903 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 16:53:32.950  7686  7686 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 16:53:32.950   329  1537 V AudioPolicyService: registerClient() client 0xb00101e0, uid 1002
08-30 16:53:32.951   329  1382 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:53:32.951   329  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:53:32.951   329  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:53:32.951  7686  7686 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 16:53:32.951   329  1381 V AudioFlinger: registerClient() client 0xb1433238, pid 7686
08-30 16:53:32.952   329  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:32.952   329  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:32.952  1589  2512 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:32.952  1589  2512 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:32.952  3317  3332 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:32.952  3317  3332 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:32.952  1045  1642 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:32.952  1045  1642 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:32.952  7686  7686 V ToneGenerator: Create Track: 0xb4928080
08-30 16:53:32.953  7686  7686 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 16:53:32.953  7686  7686 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 16:53:32.953  1864  2547 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:32.953  1864  2547 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:53:32.953   329  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:32.953   329  1537 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:53:32.953   329  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:32.953   329  1537 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:53:32.953   329  1537 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:53:32.953   329  1537 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:53:32.953  1045  1735 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:32.953  3317  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:32.953  1045  1735 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:32.953  3317  3333 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:32.953  7686  7702 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:53:32.953  7686  7702 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 16:53:32.953  7686  7702 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:32.953  1589  1925 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:53:32.953  1589  1925 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:32.953  7686  7702 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 16:53:32.953  1864  1880 V AudioSystem: ioConfigChanged,() event 0, ioHandle 4
08-30 16:53:32.953  1864  1880 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:53:32.953   329  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 16:53:32.954   329  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:53:32.954   329  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 16:53:32.954   329  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:53:32.954   329  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:53:32.954  7686  7686 V AudioSystem: getLatency() output 2, latency 50
08-30 16:53:32.954  7686  7686 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 16:53:32.954  7686  7686 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 16:53:32.954   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:53:32.954   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:53:32.954   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:53:32.954   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:53:32.954   329   329 V AudioFlinger: createTrack() lSessionId: 23
08-30 16:53:32.955  7686  7686 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 16:53:32.955   329  1537 V AudioFlinger: acquiring 23 from 7686, for 7686
08-30 16:53:32.955   329  1537 V AudioFlinger:  added new entry for 23
08-30 16:53:32.956  7686  7686 V ToneGenerator: ToneGenerator INIT OK, time: 134439
08-30 16:53:32.956  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:32.957  7686  7925 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 16:53:32.957  7686  7925 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:53:32.957  7686  7925 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:53:32.957  7686  7925 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 16:53:32.958   329  1382 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7686
,08-30 16:53:32.960  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:32.960   329  1382 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 16:53:32.960   329  1382 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 16:53:32.960   329  1382 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 16:53:32.960   329  1382 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 16:53:32.960   329  1382 V voice   : voice_set_parameters: exit with code(0)
08-30 16:53:32.960   329  1382 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 16:53:32.960   329  1382 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 16:53:32.960   329  1382 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 16:53:32.960   329  1382 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 16:53:32.960   329  1382 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 16:53:32.960   329  1382 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 16:53:32.961  7686  7925 V ToneGenerator: ToneGenerator destructor
08-30 16:53:32.961  7686  7925 V ToneGenerator: stopTone
08-30 16:53:32.961  7686  7925 V ToneGenerator: Delete Track: 0xb4928080
08-30 16:53:32.962   329   329 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 16:53:32.962   329   329 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 16:53:32.962   329   329 V AudioFlinger: PlaybackThread::Track destructor
08-30 16:53:32.962   329  1259 V AudioPolicyService: AudioCommandThread() waking up
08-30 16:53:32.962   329   329 V AudioFlinger: removeClient_l() pid 7686, calling pid 329
08-30 16:53:32.962   329  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 16:53:32.962   329  1259 V AudioPolicyManager: releaseOutput() 2
08-30 16:53:32.962   329  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 16:53:32.962  7686  7925 V AudioTrack: ~AudioTrack, releasing session id from 7686 on behalf of 7686
08-30 16:53:32.962   329  1382 V AudioFlinger: releasing 23 from 7686 for 7686
08-30 16:53:32.962   329  1382 V AudioFlinger:  decremented refcount to 0
08-30 16:53:32.962   329  1382 V AudioFlinger: purging stale effects
08-30 16:53:32.963  7686  7686 D A2dpService: Received start request. Starting profile...
08-30 16:53:32.963  1045  1728 W Process : Unable to open /proc/7927/status
08-30 16:53:32.964  7686  7686 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:53:32.965  7686  7686 V Avrcp   : make
08-30 16:53:32.965  7686  7686 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 16:53:32.965  7686  7686 I bluedroid-qcom: get_profile_interface avrcp
08-30 16:53:32.975  7686  7686 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 16:53:32.977  7686  7686 E AudioManager: No RCC entry present to update
08-30 16:53:32.978  7686  7686 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:53:32.983  7686  7686 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 16:53:32.985  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 16:53:32.985  7686  7686 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 16:53:32.990  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 16:53:33.121  1045  1735 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:53:33.121  1045  1735 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:53:33.197  1045  1919 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 16:53:33.210  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 16:53:33.215  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:53:33.216  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 16:53:33.217  7686  7686 I BluetoothA2dpServiceJni: classInitNative
08-30 16:53:33.217  7686  7686 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:53:33.217  7686  7686 D A2dpStateMachine: make
08-30 16:53:33.220  7686  7686 I bluedroid-qcom: get_profile_interface a2dp
08-30 16:53:33.220  7686  7935 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 16:53:33.223  7686  7686 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:53:33.223  7686  7686 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 16:53:33.224  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.225  7686  7686 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 16:53:33.226  7686  7686 D HidService: Received start request. Starting profile...
08-30 16:53:33.226  7686  7686 I bluedroid-qcom: get_profile_interface hidhost
08-30 16:53:33.226  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.227  7686  7686 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:53:33.228  7686  7934 D A2dpStateMachine: Enter Disconnected: -2
08-30 16:53:33.228  7686  7686 D HealthService: Received start request. Starting profile...
08-30 16:53:33.231  7686  7686 I bluedroid-qcom: get_profile_interface health
08-30 16:53:33.231  7686  7686 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:53:33.231  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.232  7686  7686 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 16:53:33.233  7686  7686 D PanService: Received start request. Starting profile...
08-30 16:53:33.233  7686  7686 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:53:33.233  7686  7686 I bluedroid-qcom: get_profile_interface pan
,08-30 16:53:33.240  7686  7686 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-30 16:53:33.241  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.241  7686  7686 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 16:53:33.245  7686  7686 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:53:33.246  7686  7686 D BtGatt.GattService: Received start request. Starting profile...
08-30 16:53:33.246  7686  7686 D BtGatt.GattService: start()
08-30 16:53:33.246  7686  7686 I bluedroid-qcom: get_profile_interface gatt
08-30 16:53:33.246  7686  7686 D BtGatt.AdvertiseManager: advertise manager created
08-30 16:53:33.254  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.256  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.257  7686  7686 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-30 16:53:33.258  7686  7686 V BluetoothMapService: BluetoothMapBinder()
,08-30 16:53:33.258  7686  7686 D BluetoothMapService: Received start request. Starting profile...
08-30 16:53:33.258  7686  7686 D BluetoothMapService: start()
08-30 16:53:33.261  7686  7686 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 16:53:33.261  7686  7686 D BluetoothMapEmailAppObserver: createReceiver()
08-30 16:53:33.262  7686  7686 D BluetoothMapEmailAppObserver: initObservers()
08-30 16:53:33.262  7686  7686 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 16:53:33.268  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.268  7686  7686 D HeadsetStateMachine: Proxy object connected
08-30 16:53:33.269  7686  7686 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 16:53:33.269  7686  7686 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 16:53:33.270  7686  7925 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 16:53:33.270  7686  7925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:53:33.270  7686  7925 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 16:53:33.273  7686  7686 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:33.274  7686  7686 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:33.278  7686  7686 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:33.280  7686  7686 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:33.282  7686  7686 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 16:53:33.284  7686  7686 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:53:33.284  7686  7686 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 16:53:33.286  7686  7686 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 16:53:33.286  7686  7686 V BluetoothMapService: Handler(): got msg=1
08-30 16:53:33.287  7686  7903 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 16:53:33.287  7686  7903 I bluedroid-qcom: enable
08-30 16:53:33.287  7686  7903 I bt_hci_bdroid: init
08-30 16:53:33.288  7686  7942 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 16:53:33.288  7686  7686 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:33.288  7686  7686 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:33.288  7686  7686 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:33.288  7686  7686 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:33.288  7686  7686 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 16:53:33.291  7686  7903 I bt_vendor: bt-vendor : init
08-30 16:53:33.291  7686  7903 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 16:53:33.291  7686  7903 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 16:53:33.291  7686  7903 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 16:53:33.291  7686  7903 D bt_userial_mct: userial_init
08-30 16:53:33.293  7686  7942 I bt-btu  : btu_task pending for preload complete event
08-30 16:53:33.294  7686  7903 D bt_hci_bdroid: set_power 1
08-30 16:53:33.294  7686  7903 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 16:53:33.294  7686  7903 I bt_vendor: Starting hciattach daemon
08-30 16:53:33.295  7686  7903 I bt_vendor: try to set true
,08-30 16:53:33.290  7945  7945 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:33.290  7945  7945 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:33.345  7946  7946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 16:53:33.353  1045  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{a69121c type 2 when 134823 com.google.android.gms} when 134823
08-30 16:53:33.362   325  7949 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 16:53:33.363  1045  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 16:53:33.408  1045  2042 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7953 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 16:53:33.435  7967  7967 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 16:53:33.446  7972  7972 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:53:33.483  7974  7974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 16:53:33.495  7975  7975 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 16:53:33.501  7953  7953 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 16:53:33.512  7976  7976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 16:53:33.524  7977  7977 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 16:53:33.537  7953  7953 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 16:53:33.544  7979  7979 I libmdmdetect: ESOC framework not supported
08-30 16:53:33.545  7979  7979 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-30 16:53:33.553  7979  7979 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 16:53:33.553  7979  7979 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 16:53:33.553  7979  7979 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 16:53:33.553  7979  7979 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 16:53:33.553  7979  7979 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 16:53:33.553  7979  7979 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 16:53:33.553  7979  7979 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 16:53:33.578  7953  7953 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 16:53:33.579  7953  7953 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 16:53:33.579  7953  7953 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 16:53:33.580  7953  7953 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 16:53:33.580  7953  7953 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 16:53:33.582  7953  7953 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 16:53:33.591  7979  7980 E QC-QMI  : qmi_client [7979] 15: failed to locate client data
08-30 16:53:33.591  7953  7953 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 16:53:33.592   493   493 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 16:53:33.592   493   493 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-30 16:53:33.600  7953  7953 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 16:53:33.600  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5890
,08-30 16:53:33.606  7953  7953 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 16:53:33.611  7953  7953 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 16:53:33.611  7953  7953 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 16:53:33.612  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 16:53:33.613  7953  7953 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 16:53:33.655  7953  7953 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:33.655  7953  7953 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:33.669  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 16:53:33.673  7953  7953 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 16:53:33.678  7953  7953 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 16:53:33.678  7953  7953 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 16:53:33.678  7953  7953 V SoundPool: doLoad: loading sample sampleID=1
08-30 16:53:33.678  7953  7953 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 16:53:33.682  7597  7597 D UEI.SmartControl: QS Service created
08-30 16:53:33.683  7953  7953 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 16:53:33.685  7953  7953 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:53:33.686  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 16:53:33.695  7984  7984 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:53:33.702  7953  7986 V SoundPool: Start decode
08-30 16:53:33.702  7953  7986 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 16:53:33.703  7953  7953 V LGMDMManager: Create singleton instance
08-30 16:53:33.703   329  1381 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 16:53:33.703   329  1381 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 16:53:33.703   329  1381 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 16:53:33.703   329  1381 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 16:53:33.703   329  1381 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 16:53:33.703   329  1381 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 16:53:33.703   329  1381 V MediaPlayerService: player type = 3
08-30 16:53:33.703   329  1381 V AwesomePlayer: AwesomePlayer create()
08-30 16:53:33.704   329  1381 V AwesomePlayer: reset_l() 
08-30 16:53:33.704   329  1381 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:33.704   329  1381 V AwesomePlayer: setAudioSink() 
08-30 16:53:33.704   329  1381 V AwesomePlayer: reset_l() 
08-30 16:53:33.704   329  1381 V AudioCache: notify(0xb1432180, 8, 0, 0)
08-30 16:53:33.704   329  1381 V AudioCache: ignored
08-30 16:53:33.704   329  1381 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:33.704   329  1381 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 16:53:33.704   329  1381 V AwesomePlayer: setDataSource_l dataSource
08-30 16:53:33.704   329  1381 V LGParserOSAL: SniffLGParser start
08-30 16:53:33.704   329  1381 V LGParserOSAL: MainType:5, SubType=0
08-30 16:53:33.704   329  1381 V LGParserOSAL: #### check Mime : application/ogg
08-30 16:53:33.704   329  1381 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 16:53:33.704   329  1381 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 16:53:33.735  7597  7597 I UEI.SmartControl: Service initServices...
08-30 16:53:33.736  7597  7597 D UEI.SmartControl: QS start get config
,08-30 16:53:33.747   329  1381 V LGParserOSAL: supported mime: application/ogg
08-30 16:53:33.747   329  1381 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 16:53:33.747   329  1381 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 16:53:33.747   329  1381 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 16:53:33.747   329  1381 V AwesomePlayer: AudioTrack Setting
08-30 16:53:33.747   329  1381 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 16:53:33.748   329  1381 V AwesomePlayer: setAudioSource() 
08-30 16:53:33.748   329  1381 V MediaPlayerService: prepare
08-30 16:53:33.748   329  1381 V AwesomePlayer: prepareAsync_l() 
08-30 16:53:33.748  7686  7903 I bt_vendor: bluetooth satus is on
08-30 16:53:33.748  7686  7903 D bt_hci_bdroid: preload
08-30 16:53:33.748  7686  7944 D bt_userial_mct: userial_open(port:0)
08-30 16:53:33.748  7686  7944 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 16:53:33.749   329  1381 V MediaPlayerService: wait for prepare
08-30 16:53:33.749   329  7988 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 16:53:33.749   329  7988 V AwesomePlayer: initAudioDecoder() 
08-30 16:53:33.749   329  7988 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 16:53:33.749   329  7988 V AudioSystem: isOffloadSupported()
08-30 16:53:33.749   329  7988 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 16:53:33.749   329  7988 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 16:53:33.749   329  7988 I AudioFlinger: isAudioPlaybackHookOn() false
,08-30 16:53:33.749   329  7988 V AwesomePlayer: getUseOffload() = 0 
08-30 16:53:33.749   329  7988 V OMXCodec: OMXCodec::Create
08-30 16:53:33.749   329  7988 V OMXCodec: findMatchingCodecs()
08-30 16:53:33.749   329  7988 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 16:53:33.749   329  7988 V OMXCodec: matchingCodecs.size()=1
08-30 16:53:33.749   329  7988 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 16:53:33.751  7686  7944 I bt_vendor: Done intiailizing UART
08-30 16:53:33.752  7686  7944 I bt_vendor: Done intiailizing UART
08-30 16:53:33.752  7686  7944 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 16:53:33.752  7686  7944 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 16:53:33.752  7686  7942 I bt-btu  : btu_task received preload complete event
08-30 16:53:33.752   329  7988 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 16:53:33.752   329  7988 V LGCodecAdapter: LG Codec Adapter start
08-30 16:53:33.752   329  7988 V OMXCodec: OMXCodec Createtor
08-30 16:53:33.752   329  7988 V OMXCodec: setComponentRole
08-30 16:53:33.752   329  7988 V OMXCodec: configureCodec protected=0
08-30 16:53:33.752   329  7988 V LGCodecAdapter: called getLGCodecSpecificData
08-30 16:53:33.752   329  7988 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 16:53:33.753   329  7988 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 16:53:33.753   329  7988 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 16:53:33.753   329  7988 V LGCodecOSAL: Not support LGCodec
08-30 16:53:33.753   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-30 16:53:33.753   329  7988 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 16:53:33.753   329  7988 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 16:53:33.753   329  7988 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 16:53:33.753   329  7988 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 16:53:33.753   329  7988 V AudioSystem: isOffloadSupported()
08-30 16:53:33.753   329  7988 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-30 16:53:33.753   329  7988 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 16:53:33.753   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 16:53:33.753   329  7988 V OMXCodec: init()
08-30 16:53:33.754  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 16:53:33.754  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 16:53:33.756  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:53:33.759  7686  7942 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 16:53:33.760  7686  7990 D bt_userial_mct: Entering userial_read_thread()
08-30 16:53:33.760   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 16:53:33.760   329  7988 V OMXCodec: allocateBuffers
08-30 16:53:33.760   329  7988 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 16:53:33.760   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 16:53:33.764   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f9c0 on input port
08-30 16:53:33.764   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa10 on input port
08-30 16:53:33.764   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa60 on input port
08-30 16:53:33.764   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on input port
08-30 16:53:33.764   329  7988 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 16:53:33.764   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 16:53:33.764   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb50 on output port
08-30 16:53:33.765   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fe20 on output port
08-30 16:53:33.765   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fe70 on output port
08-30 16:53:33.765   329  7988 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000ff60 on output port
08-30 16:53:33.765   329  7988 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 16:53:33.765   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 16:53:33.765   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 16:53:33.765   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 16:53:33.765   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 16:53:33.765   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 16:53:33.765   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 16:53:33.766   329  7988 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 16:53:33.766   329  7988 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 16:53:33.766   329  7988 V AudioCache: notify(0xb1432180, 5, 0, 0)
08-30 16:53:33.766   329  7988 V AudioCache: ignored
08-30 16:53:33.766   329  7988 V AudioCache: notify(0xb1432180, 1, 0, 0)
08-30 16:53:33.766   329  7988 V AudioCache: prepared
08-30 16:53:33.766   329  1381 V AudioCache: wait - success
08-30 16:53:33.766   329  1381 V MediaPlayerService: start
08-30 16:53:33.766   329  1381 V AwesomePlayer: play_l() 
08-30 16:53:33.766   329  1381 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 16:53:33.7,66   329  1381 V AwesomePlayer: createAudioPlayer_l
08-30 16:53:33.766   329  1381 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 16:53:33.766   329  1381 V AwesomePlayer: startAudioPlayer_l() 
08-30 16:53:33.766   329  1381 D AudioPlayer: start of Playback, useOffload 0
08-30 16:53:33.766   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 16:53:33.766   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 16:53:33.769   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 16:53:33.769   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 16:53:33.769   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 16:53:33.769   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 16:53:33.769   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 16:53:33.769   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854352
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952855072
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952855152
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952855392
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 16:53:33.770   329  7991 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fe70 on output port
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fe20 on output port
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb50 on output port
08-30 16:53:33.770   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on output port
08-30 16:53:33.771   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 16:53:33.771   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 16:53:33.773   329  1381 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 16:53:33.773   329  1381 V AudioCache: notify(0xb1432180, 6, 0, 0)
08-30 16:53:33.773   329  1381 V AudioCache: ignored
,08-30 16:53:33.773   329  1381 V MediaPlayerService: wait for playback complete
08-30 16:53:33.774   329  7996 V AudioCache: write(0xb57c8000, 4096),
08-30 16:53:33.774   329  7996 V AudioCache: memcpy(0xac300000, 0xb57c8000, 4096)
,08-30 16:53:33.778   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.778   329  7996 V AudioCache: memcpy(0xac301000, 0xb57c8000, 4096)
08-30 16:53:33.778   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.778   329  7996 V AudioCache: memcpy(0xac302000, 0xb57c8000, 4096)
08-30 16:53:33.780   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.780   329  7996 V AudioCache: memcpy(0xac303000, 0xb57c8000, 4096)
08-30 16:53:33.781   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.781   329  7996 V AudioCache: memcpy(0xac304000, 0xb57c8000, 4096)
08-30 16:53:33.782   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.782   329  7996 V AudioCache: memcpy(0xac305000, 0xb57c8000, 4096)
08-30 16:53:33.783   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.783   329  7996 V AudioCache: memcpy(0xac306000, 0xb57c8000, 4096)
08-30 16:53:33.784   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.784   329  7996 V AudioCache: memcpy(0xac307000, 0xb57c8000, 4096)
08-30 16:53:33.784   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.784   329  7996 V AudioCache: memcpy(0xac308000, 0xb57c8000, 4096)
08-30 16:53:33.785   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.785   329  7996 V AudioCache: memcpy(0xac309000, 0xb57c8000, 4096)
08-30 16:53:33.787   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.787   329  7996 V AudioCache: memcpy(0xac30a000, 0xb57c8000, 4096)
08-30 16:53:33.788   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.788   329  7996 V AudioCache: memcpy(0xac30b000, 0xb57c8000, 4096)
,08-30 16:53:33.790   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.790   329  7996 V AudioCache: memcpy(0xac30c000, 0xb57c8000, 4096)
08-30 16:53:33.791   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.791   329  7996 V AudioCache: memcpy(0xac30d000, 0xb57c8000, 4096)
08-30 16:53:33.792   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.792   329  7996 V AudioCache: memcpy(0xac30e000, 0xb57c8000, 4096)
08-30 16:53:33.793   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.793   329  7996 V AudioCache: memcpy(0xac30f000, 0xb57c8000, 4096)
08-30 16:53:33.794   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.794   329  7996 V AudioCache: memcpy(0xac310000, 0xb57c8000, 4096)
08-30 16:53:33.795   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.795   329  7996 V AudioCache: memcpy(0xac311000, 0xb57c8000, 4096)
08-30 16:53:33.795   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.795   329  7996 V AudioCache: memcpy(0xac312000, 0xb57c8000, 4096)
08-30 16:53:33.796   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.796   329  7996 V AudioCache: memcpy(0xac313000, 0xb57c8000, 4096)
08-30 16:53:33.797   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.797   329  7996 V AudioCache: memcpy(0xac314000, 0xb57c8000, 4096)
08-30 16:53:33.798   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.798   329  7996 V AudioCache: memcpy(0xac315000, 0xb57c8000, 4096)
08-30 16:53:33.798   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.798   329  7996 V AudioCache: memcpy(0xac316000, 0xb57c8000, 4096)
08-30 16:53:33.799   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.799   329  7996 V AudioCache: memcpy(0xac317000, 0xb57c8000, 4096)
,08-30 16:53:33.801   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.801   329  7996 V AudioCache: memcpy(0xac318000, 0xb57c8000, 4096)
08-30 16:53:33.802   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.802   329  7996 V AudioCache: memcpy(0xac319000, 0xb57c8000, 4096)
08-30 16:53:33.803   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.803   329  7996 V AudioCache: memcpy(0xac31a000, 0xb57c8000, 4096)
08-30 16:53:33.804   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.804   329  7996 V AudioCache: memcpy(0xac31b000, 0xb57c8000, 4096)
08-30 16:53:33.805   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.805   329  7996 V AudioCache: memcpy(0xac31c000, 0xb57c8000, 4096)
08-30 16:53:33.806   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.806   329  7996 V AudioCache: memcpy(0xac31d000, 0xb57c8000, 4096)
08-30 16:53:33.807   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.807   329  7996 V AudioCache: memcpy(0xac31e000, 0xb57c8000, 4096)
08-30 16:53:33.808   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.808   329  7996 V AudioCache: memcpy(0xac31f000, 0xb57c8000, 4096)
08-30 16:53:33.808   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.808   329  7996 V AudioCache: memcpy(0xac320000, 0xb57c8000, 4096)
08-30 16:53:33.809   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.809   329  7996 V AudioCache: memcpy(0xac321000, 0xb57c8000, 4096)
08-30 16:53:33.809  7686  7942 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 16:53:33.810  7686  7942 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-30 16:53:33.810  7686  7942 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
08-30 16:53:33.810   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.810   329  7996 V AudioCache: memcpy(0xac322000, 0xb57c8000, 4096)
08-30 16:53:33.810   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.810   329  7996 V AudioCache: memcpy(0xac323000, 0xb57c8000, 4096)
,08-30 16:53:33.812   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.812   329  7996 V AudioCache: memcpy(0xac324000, 0xb57c8000, 4096)
08-30 16:53:33.813   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.813   329  7996 V AudioCache: memcpy(0xac325000, 0xb57c8000, 4096)
08-30 16:53:33.814   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.814   329  7996 V AudioCache: memcpy(0xac326000, 0xb57c8000, 4096)
08-30 16:53:33.814  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 16:53:33.816   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.816   329  7996 V AudioCache: memcpy(0xac327000, 0xb57c8000, 4096)
08-30 16:53:33.816   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.817   329  7996 V AudioCache: memcpy(0xac328000, 0xb57c8000, 4096)
08-30 16:53:33.817   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.817  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 16:53:33.817   329  7996 V AudioCache: memcpy(0xac329000, 0xb57c8000, 4096)
08-30 16:53:33.818   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.818   329  7996 V AudioCache: memcpy(0xac32a000, 0xb57c8000, 4096)
08-30 16:53:33.819   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.819   329  7996 V AudioCache: memcpy(0xac32b000, 0xb57c8000, 4096)
08-30 16:53:33.819  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6031
08-30 16:53:33.820   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.820   329  7996 V AudioCache: memcpy(0xac32c000, 0xb57c8000, 4096)
08-30 16:53:33.820   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.820   329  7996 V AudioCache: memcpy(0xac32d000, 0xb57c8000, 4096)
08-30 16:53:33.821   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.821   329  7996 V AudioCache: memcpy(0xac32e000, 0xb57c8000, 4096)
08-30 16:53:33.822   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.822   329  7996 V AudioCache: memcpy(0xac32f000, 0xb57c8000, 4096)
08-30 16:53:33.822   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.822   329  7996 V AudioCache: memcpy(0xac330000, 0xb57c8000, 4096)
,08-30 16:53:33.824   329  7996 V AudioCache: write(0xb57c8000, 4096)
08-30 16:53:33.824   329  7996 V AudioCache: memcpy(0xac331000, 0xb57c8000, 4096)
08-30 16:53:33.825   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 16:53:33.825   329  7996 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 16:53:33.825   329  7996 V AwesomePlayer: postAudioEOS() 
08-30 16:53:33.825   329  7996 V AudioCache: write(0xb57c8000, 280)
08-30 16:53:33.825   329  7996 V AudioCache: memcpy(0xac332000, 0xb57c8000, 280)
08-30 16:53:33.826   329  7988 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 16:53:33.826   329  7988 V AwesomePlayer: onStreamDone
08-30 16:53:33.826   329  7988 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 16:53:33.826   329  7988 V AudioCache: notify(0xb1432180, 2, 0, 0)
08-30 16:53:33.826   329  7988 V AudioCache: playback complete
08-30 16:53:33.827   329  7988 V AwesomePlayer: pause_l() 
08-30 16:53:33.827   329  7988 V AudioCache: notify(0xb1432180, 7, 0, 0)
08-30 16:53:33.827   329  7988 V AudioCache: ignored
08-30 16:53:33.827   329  7988 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:33.827   329  1381 V AudioCache: wait - success
08-30 16:53:33.827   329  1381 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 16:53:33.827   329  7988 D AudioPlayer: Pause Playback at 1068125
08-30 16:53:33.827  7686  7907 E bt-btif : Calling BTA_HhEnable
08-30 16:53:33.827  7686  7907 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 16:53:33.827   329  1381 V AwesomePlayer: reset_l() 
08-30 16:53:33.827   329  1381 V AudioCache: notify(0xb1432180, 8, 0, 0)
08-30 16:53:33.827   329  1381 V AudioCache: ignored
08-30 16:53:33.827   329  1381 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:33.827   329  1381 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 16:53:33.827   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 16:53:33.827   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 16:53:33.827   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 16:53:33.827  7686  7907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 16:53:33.827   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 16:53:33.828  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 16:53:33.828  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 16:53:33.828  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 16:53:33.828  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 16:53:33.828  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 16:53:33.828   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 16:53:33.828   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 16:53:33.828  1045  1045 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:53:33.828   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 16:53:33.828   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fab0 on port 0
08-30 16:53:33.828   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 16:53:33.828   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fa60 on port 0
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fa10 on port 0
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 16:53:33.829  1045  1045 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] fre,eing buffer 0xb000f9c0 on port 0
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fb50 on port 1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 16:53:33.829  7686  7907 D BluetoothAdapterProperties: Name is: G3
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fe20 on port 1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fe70 on port 1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 16:53:33.829   329  7991 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 16:53:33.829   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 16:53:33.829   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 16:53:33.829   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 16:53:33.830  7686  7907 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:53:33.830  7686  7907 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:53:33.830  7686  7907 D bt_hci_bdroid: postload
08-30 16:53:33.830  7686  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:33.831  7686  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 16:53:33.831  7686  7907 D bte_conf: Device ID record 1 : primary
08-30 16:53:33.831  7686  7907 D bte_conf:   vendorId            = 00c4
08-30 16:53:33.831  7686  7907 D bte_conf:   vendorIdSource      = 0001
08-30 16:53:33.831  7686  7907 D bte_conf:   product             = 13a1
08-30 16:53:33.831  7686  7907 D bte_conf:   version             = 1000
08-30 16:53:33.831  7686  7907 D bte_conf:   clientExecutableURL = 
08-30 16:53:33.831  7686  7907 D bte_conf:   serviceDescription  = 
08-30 16:53:33.831  7686  7907 D bte_conf:   documentationURL    = 
08-30 16:53:33.831  7686  7907 D bte_conf: bte_load_did_conf no section named DID2.
08-30 16:53:33.832   329  1381 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 16:53:33.832   329  1381 D AudioPlayer: AudioPlayer releasing audio source
08-30 16:53:33.832   329  1381 D AudioPlayer: AudioPlayer done releasing audio source
08-30 16:53:33.832   329  1381 V AwesomePlayer: reset_l() 
08-30 16:53:33.832   329  1381 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:33.832   329  1381 V AwesomePlayer: ~AwesomePlayer call
08-30 16:53:33.832   329  1381 V AwesomePlayer: reset_l() 
08-30 16:53:33.832   329  1381 V AwesomePlayer: cancelPlayerEvents
08-30 16:53:33.832  7953  7986 V SoundPool: close(31)
08-30 16:53:33.832  7686  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:33.832  7953  7986 V SoundPool: pointer = 0x9fe7f000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 16:53:33.832  7686  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:33.833  7686  7907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:53:33.833  7686  7903 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 16:53:33.834  7686  7903 D BluetoothA,dapterProperties: ScanMode =  20
08-30 16:53:33.834  7686  7903 D BluetoothAdapterProperties: State =  11
08-30 16:53:33.834  7686  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:33.834  7686  7903 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 16:53:33.834  7686  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:33.834  7686  7903 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 16:53:33.834  7686  7903 D BluetoothAdapterProperties: Setting state to 12
08-30 16:53:33.834  7686  7903 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 16:53:33.835  7686  7907 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:53:33.820  7999  7999 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:33.820  7999  7999 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:33.839  1045  1120 D BluetoothManagerService: Message: 60
08-30 16:53:33.839  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 16:53:33.840  7686  7903 I BluetoothAdapterState: Entering On State
08-30 16:53:33.844  7686  7944 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:53:33.845  7686  7903 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 16:53:33.845  1045  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 16:53:33.845  7686  7903 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 16:53:33.845  7686  7903 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 16:53:33.845  6805  6822 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:53:33.846  7686  7903 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 16:53:33.847  7686  7990 E bt_mct  : hci lib postload completed
08-30 16:53:33.852  6805  6805 D BluetoothInputDevice: Proxy object connected
08-30 16:53:33.852  6805  6805 D HidProfile: Bluetooth service connected
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:33.852  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:33.852  6805  7551 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:53:33.852  6805  7551 D BluetoothPan: onBluetoothStateChange call bindService
08-30 16:53:33.854  1045  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:53:33.854  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:33.854  6805  6822 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:53:33.855  7686  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:33.855  7686  7942 W bt-smp  : Plain text(LSB ~ MSB) = 88 fd 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:33.855  7686  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 79 1c 9c 93 c4 27 86 4d 7a eb 7e 6d d0 6a 37 c8 
08-30 16:53:33.855  7686  7942 W bt-btm  : Stopping oneshot timer
08-30 16:53:33.856  7686  7907 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:53:33.857  7686  7907 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 16:53:33.857  1045  1045 D BluetoothHeadset: Proxy object connected
08-30 16:53:33.859  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:53:33.859  6805  6805 D PanProfile: Bluetooth service connected
,08-30 16:53:33.869  7686  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:33.869  7686  7942 W bt-smp  : Plain text(LSB ~ MSB) = cd 08 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:33.869  7686  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = af a1 e6 0b 9a cb 59 30 ec cd 29 3c a7 ae b2 d6 
08-30 16:53:33.869  7686  7942 W bt-btm  : Stopping oneshot timer
08-30 16:53:33.882  7686  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:33.882  7686  7942 W bt-smp  : Plain text(LSB ~ MSB) = 9b 95 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:33.882  7686  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c 0b 16 1a ca 71 9e e8 cf 93 1d 0b e0 17 86 91 
08-30 16:53:33.882  7686  7942 W bt-btm  : Stopping oneshot timer
08-30 16:53:33.890  7686  7903 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 16:53:33.895  8005  8005 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 16:53:33.895  7686  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:33.895  7686  7942 W bt-smp  : Plain text(LSB ~ MSB) = ad 34 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:33.895  7686  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 48 b3 45 be 74 c8 a6 5a 39 46 47 bf b3 1c 58 
08-30 16:53:33.895  7686  7942 W bt-btm  : Stopping oneshot timer
08-30 16:53:33.908  7686  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:53:33.908  7686  7942 W bt-smp  : Plain text(LSB ~ MSB) = 1d c2 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:53:33.908  7686  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b 85 02 42 b8 5f 33 19 e3 d3 8c 04 56 82 aa 55 
08-30 16:53:33.908  7686  7942 W bt-btm  : Stopping oneshot timer
,08-30 16:53:33.953  1045  1120 I art     : Explicit concurrent mark sweep GC freed 27006(1342KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.723ms total 94.590ms
,08-30 16:53:33.954  6805  7551 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:53:33.956  1864  2547 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:53:33.956  6805  6805 D BluetoothMap: Proxy object connected
08-30 16:53:33.956  6805  6805 D MapProfile: Bluetooth service connected
08-30 16:53:33.956  6805  6805 D BluetoothMap: getConnectedDevices()
08-30 16:53:33.960  7686  7702 V BluetoothMapService: getConnectedDevices()
08-30 16:53:33.960  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:53:33.961  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 16:53:33.962  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 16:53:33.962  1045  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:53:33.962  6805  6822 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:53:33.964  6805  6805 D BluetoothA2dp: Proxy object connected
08-30 16:53:33.964  1045  1045 D BluetoothA2dp: Proxy object connected
08-30 16:53:33.964  6805  6805 D A2dpProfile: Bluetooth service connected
08-30 16:53:33.964  6805  7551 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:53:33.968  6805  6805 D BluetoothHeadset: Proxy object connected
08-30 16:53:33.968  6805  6805 D HeadsetProfile: Bluetooth service connected
08-30 16:53:33.968  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:53:33.976  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 16:53:33.977  1045  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 16:53:33.977  1045  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 16:53:33.980  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:53:33.980  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:33.980  1953  2176 D LGBluetoothAPIService: Message: 1
08-30 16:53:33.980  1953  2176 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 16:53:33.981  1953  2176 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 16:53:33.981  1953  2176 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 16:53:33.982  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:33.982  1045  1045 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 16:53:33.982  1045  1120 D BluetoothManagerService: Message: 40
08-30 16:53:33.982  1045  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 16:53:33.983  7686  7686 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:33.983  7686  7686 D BluetoothMapService: STATE_ON
08-30 16:53:33.983  7686  7686 V BluetoothMapService: Handler(): got msg=1
08-30 16:53:33.983  7686  7686 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 16:53:33.984  7686  8007 D BluetoothMapMasInstance: MAS initSocket()
08-30 16:53:33.984  7686  8007 D BluetoothMapMasInstance:   masId = 00
08-30 16:53:33.984  7686  8007 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 16:53:33.984  7686  8007 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 16:53:33.984  7686  8007 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 16:53:33.986  1045  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:33.988  7686  8007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:33.994  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:33.994  7686  7686 V BluetoothPbapService: Pbap Service onCreate
08-30 16:53:33.994  7686  7686 V BluetoothPbapService: Starting PBAP service
,08-30 16:53:33.997  7686  8007 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 16:53:33.997  7686  8007 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 16:53:33.997  7686  8007 D BluetoothMapMasInstance: Accepting socket connection...
08-30 16:53:33.998  7686  7907 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:53:33.998  7686  7907 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 16:53:33.999  7686  7686 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 16:53:33.999  7686  7686 V BluetoothPbapService: Pbap Service onBind
08-30 16:53:34.000  7686  7686 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:34.000  7686  7686 V BluetoothPbapService: state: 12
08-30 16:53:34.000  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 16:53:34.000  7686  7686 V BluetoothPbapService: Handler(): got msg=1
08-30 16:53:34.001  7686  7686 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 16:53:34.001  7686  8009 V BluetoothPbapService: Pbap Service initSocket
08-30 16:53:34.002  1045  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:34.002  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:34.003  7686  8009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:34.004  7686  8009 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 16:53:34.004  7686  8009 V BluetoothPbapService: Succeed to create listening socket 
08-30 16:53:34.004  7686  8009 V BluetoothPbapService: Accepting socket connection...
08-30 16:53:34.005  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 16:53:34.008  6805  6805 D BluetoothPbap: Proxy object connected
08-30 16:53:34.008  6805  6805 D PbapServerProfile: Bluetooth service connected
08-30 16:53:34.009  7686  7686 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:53:34.009  7686  7686 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:34.009  7686  7686 V BluetoothPbapReceiver: ***********state = 12
08-30 16:53:34.010  6805  6805 D DockEventReceiver: finishStartingService: stopping service
08-30 16:53:34.014  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:53:34.014  2246  2246 D c       : Getting all permits...
08-30 16:53:34.014  2246  2246 D a       : Opening database...
08-30 16:53:34.018  2246  2246 D a       : Opening database auth.proximity.permit_store...
08-30 16:53:34.019  2246  2246 D a       : Closing database...
,08-30 16:53:34.027  6805  6805 D BluetoothPermissionRequest: onReceive
08-30 16:53:34.029  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 16:53:34.031  6805  6805 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:53:34.033  7686  7686 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 16:53:34.034  7686  7686 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 16:53:34.040  7686  7686 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 16:53:34.059  7686  7686 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 16:53:34.060  7686  7686 V BtOppService: onCreate
08-30 16:53:34.063  7686  7686 V BluetoothOppNotification: send message
08-30 16:53:34.067  7686  7686 V BtOppService: Starting RfcommListener
08-30 16:53:34.073  7686  7686 D BluetoothOppPreference: Dumping Names:  
,08-30 16:53:34.073  7686  7686 D BluetoothOppPreference: {}
08-30 16:53:34.073  7686  7686 D BluetoothOppPreference: Dumping Channels:  
08-30 16:53:34.073  7686  7686 D BluetoothOppPreference: {}
08-30 16:53:34.074  7686  7686 V BtOppService: onStartCommand
08-30 16:53:34.077  7686  7686 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:34.077  7686  7686 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 16:53:34.078  7686  8016 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:53:34.079  7686  7686 V BluetoothOppNotification: new notify threadi!
08-30 16:53:34.080  7686  7686 V BluetoothOppNotification: send delay message
08-30 16:53:34.080  7686  7686 V BtOppService: start RfcommListener
08-30 16:53:34.083  7686  7686 V BtOppService: RfcommListener started
08-30 16:53:34.084  7686  8018 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 16:53:34.085  1045  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:34.087  7686  8018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:53:34.087  7686  8018 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 16:53:34.088  7686  8018 V BtOppRfcommListener: Started RFCOMM listener....
,08-30 16:53:34.088  7686  8018 I BtOppRfcommListener: Accept thread started.
08-30 16:53:34.088  7686  8018 V BtOppRfcommListener: Accepting connection...
08-30 16:53:34.092  7686  8017 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 16:53:34.092  7686  8013 V BtOppService: Deleted complete outbound shares, number =  0
08-30 16:53:34.091  7686  8016 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:53:34.094  7686  8013 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 16:53:34.094  7686  8013 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-30 16:53:34.095  7686  8017 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d8ca471 on behalf of 
08-30 16:53:34.096  7686  8013 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f62a256 on behalf of 
08-30 16:53:34.098  7597  7597 I UEI.SmartControl: Supports setup maps: true
08-30 16:53:34.100  7597  7597 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 16:53:34.100  7597  7597 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 16:53:34.100  7597  7597 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 16:53:34.101  7597  7597 I UEI.SmartControl: ### init IR Blaster...
08-30 16:53:34.101  7686  8016 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ef982d7 on behalf of 
08-30 16:53:34.102  7686  8017 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 16:53:34.103  7686  8017 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 16:53:34.104  7686  8016 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:53:34.104  7686  8017 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6467c4 on behalf of 
08-30 16:53:34.105  7597  7597 D serial_port: Configuring serial port
08-30 16:53:34.105  7597  7597 E UEI.SmartControl: UEIBLaster setting for 616
08-30 16:53:34.105  7597  7597 I UEI.SmartControl: Setting serial record hearder size = 2
,08-30 16:53:34.105  7597  7597 I UEI.SmartControl: configuring settings for MAXQ616
08-30 16:53:34.105  7597  7597 I UEI.SmartControl: Get version...
08-30 16:53:34.107  7686  8017 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 16:53:34.108  7686  8017 V BluetoothOppNotification: outbound notification was removed.
08-30 16:53:34.108  7686  8017 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:53:34.109  7686  8017 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@af616ad on behalf of 
08-30 16:53:34.109  7686  8017 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:53:34.109  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:34.109  7686  7686 V BluetoothFtpService: Ftp Service onCreate
08-30 16:53:34.109  7686  7686 I BluetoothFtpService: Ftp Service onCreate
08-30 16:53:34.110  7686  7686 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:53:34.110  7686  7686 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:34.110  7686  7686 V BluetoothFtpService: Starting Listening on sockets
08-30 16:53:34.110  7686  7686 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:53:34.110  7686  7686 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:53:34.110  7686  7686 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:53:34.110  7686  7686 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:34.110  7686  7686 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 16:53:34.111  7686  7686 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:53:34.113  7686  7686 V BtOppService: ContentObserver received notification
08-30 16:53:34.113  7686  7686 V BtOppService: ContentObserver received notification
08-30 16:53:34.114  7686  7686 V BluetoothFtpService: Handler(): got msg=1
08-30 16:53:34.114  7686  8017 V BluetoothOppNotification: inbound notification was removed.
,08-30 16:53:34.114  7686  7686 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-30 16:53:34.114  7686  7686 V BluetoothFtpService: Ftp Service initSocket
08-30 16:53:34.116  1045  2333 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:34.116  7686  8017 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:53:34.117  7686  7686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:34.118  7686  8020 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:53:34.118  7686  7686 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 16:53:34.118  7686  7686 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 16:53:34.120  7686  8021 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 16:53:34.120  7686  8017 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fe97573 on behalf of 
08-30 16:53:34.122  7597  8019 D UEI.SmartControl: serial port data available: 21
08-30 16:53:34.124  7686  8020 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:53:34.125  7686  8020 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32223c30 on behalf of 
08-30 16:53:34.125  7686  8020 V BluetoothOppNotification: update too frequent, put in queue
08-30 16:53:34.126  7686  8020 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:53:34.133  7686  7686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204314a5
08-30 16:53:34.133  7686  7686 V BluetoothSapService: Sap Service onCreate
,08-30 16:53:34.135  7686  7686 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:53:34.135  7686  7686 V BluetoothSapService: state: 12
08-30 16:53:34.135  7686  7686 V BluetoothSapService: Starting SAP server process
08-30 16:53:34.136  7686  7686 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 16:53:34.130  8022  8022 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:34.130  8022  8022 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:34.137  7686  8023 V BluetoothSapService: Sap Service initRfcommSocket
08-30 16:53:34.138  1045  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:34.139  7686  8023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:53:34.140  7686  8023 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 16:53:34.140  7686  8023 V BluetoothSapService: Succeed to create listening socket 
08-30 16:53:34.140  7686  8023 V BluetoothSapService: Accepting socket connection...
08-30 16:53:34.145  8022  8022 V BT_SAP  : Event pipe created
08-30 16:53:34.145  8022  8022 V BT_SAP  : create_server_socket qcom.sap.server
08-30 16:53:34.145  8022  8022 V BT_SAP  : created socket fd 6
,08-30 16:53:34.149  7597  7597 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 16:53:34.149  7597  7597 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 16:53:34.149  7597  7597 I UEI.SmartControl: QS saving settings...
08-30 16:53:34.150  7597  7597 D UEI.SmartControl: IR Blaster version: 25672567
08-30 16:53:34.165  7597  8019 D UEI.SmartControl: serial port data available: 4
,08-30 16:53:34.193  7597  8026 I UEI.SmartControl: Device manager: loading config....
,08-30 16:53:34.194  7597  8026 D UEI.SmartControl: ----------- loading internal config...
,08-30 16:53:34.195  7597  7597 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 16:53:34.196  7597  7597 E UEI.SmartControl: Services init done
08-30 16:53:34.196  7597  7597 D UEI.SmartControl: QS Service init finished
08-30 16:53:34.198  7597  7597 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 16:53:34.198  7597  7597 D UEI.SmartControl: QS Service version code: 201091
,08-30 16:53:34.199  7597  7597 D UEI.SmartControl: Service requested: Control
08-30 16:53:34.202  7597  8026 E UEI.SmartControl: Loading SETTINGS...
08-30 16:53:34.206  7597  7597 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 16:53:34.209  7597  7597 D UEI.SmartControl: Internal service binding...
,08-30 16:53:34.211  7953  7953 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 16:53:34.213  7597  7614 I UEI.SmartControl: ------ IControl API: 11
08-30 16:53:34.213  7597  7614 D UEI.SmartControl: File observer start...
08-30 16:53:34.214  7597  7614 E UEI.SmartControl: IR Port is disabled: false
08-30 16:53:34.215  7597  7614 D UEI.SmartControl: Starting file observer...
08-30 16:53:34.215  7597  7614 I UEI.SmartControl: Registering callback...
08-30 16:53:34.216  7597  7613 I UEI.SmartControl: ------ IControl API: 19
08-30 16:53:34.216  7597  8026 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 16:53:34.218  7597  7613 I UEI.SmartControl: Registering Services Ready callback...
08-30 16:53:34.233  7597  8025 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 16:53:34.233  7597  8025 D UEI.SmartControl: -----service ready thread exits
08-30 16:53:34.234  7953  7970 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 16:53:34.234  7953  7983 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 16:53:34.235  7953  7983 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 16:53:34.235  7953  7953 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 16:53:34.235  7953  7953 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 16:53:34.236  7597  7614 I UEI.SmartControl: ------ IControl API: 8
,08-30 16:53:34.238  7953  7953 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-30 16:53:34.238  7953  7953 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 16:53:34.238  7953  7953 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 16:53:34.239  7953  7953 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 16:53:34.239  7953  7953 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 16:53:34.240  7953  7953 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 16:53:34.242  7953  7953 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 16:53:34.247  7953  7953 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 16:53:34.248  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 16:53:34.250  7953  7953 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:53:34.250  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-30 16:53:34.251  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 16:53:34.253  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-30 16:53:34.253  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 16:53:34.255  7953  7953 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472568814254]
08-30 16:53:34.256  7953  7953 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 16:53:34.265  1045  2333 I ActivityManager: Killing 7098:com.android.chrome/u0a57 (adj 15): empty #17
,08-30 16:53:34.295  7953  8028 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 16:53:34.360  1045  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_7098/cgroup.procs: No such file or directory
,08-30 16:53:34.380  7953  7953 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-30 16:53:34.382  7953  7953 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:53:34.383  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 16:53:34.383  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 16:53:34.384  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 16:53:34.384  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 16:53:34.385  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 16:53:34.395  7953  7953 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:34.771  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:53:34.788  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:53:34.790  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:34.790  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30b05cce added. We now have 8 listener(s)
08-30 16:53:34.790  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:53:34.797  1045  1919 D WifiServiceImplEx: setWifiEnabled: false pid=6600, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:53:34.797  1045  1919 D WifiService: setWifiEnabled: false pid=6600, uid=10118
08-30 16:53:34.797  1045  1919 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:53:34.803  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:34.805  1045  1728 D WifiServiceImplEx: setWifiEnabled: true pid=6600, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:53:34.805  1045  1728 D WifiService: setWifiEnabled: true pid=6600, uid=10118
08-30 16:53:34.805  1045  1728 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:53:34.824  1045  1045 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:53:34.825  1045  1045 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:53:34.825  1045  1045 D Ulp_jni : JNI:system_update. Event-4
,08-30 16:53:34.828  1045  1424 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-30 16:53:34.829  1045  1424 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-30 16:53:34.831  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): pid[1045] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-30 16:53:34.831  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-30 16:53:34.831  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): pid[1045] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-30 16:53:34.831  1045  1424 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:53:34.831  1045  1424 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 16:53:34.831  1045  1424 E WifiHW  : unknown target_country: EU , set to default
08-30 16:53:34.832  1045  1424 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
08-30 16:53:34.832  1045  1424 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 16:53:34.832  1045  1424 I WifiUtil: gEnableBmps=1
08-30 16:53:35.084  7686  7686 V BluetoothOppNotification: new notify threadi!
08-30 16:53:35.084  7686  7686 V BluetoothOppNotification: send delay message
,08-30 16:53:35.101  7686  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 16:53:35.102  7686  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fa6eb5c on behalf of 
08-30 16:53:35.103  7686  8041 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 16:53:35.106  7686  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 16:53:35.108  7686  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@af06e65 on behalf of 
08-30 16:53:35.108  7686  8041 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 16:53:35.112  7686  8041 V BluetoothOppNotification: outbound notification was removed.
,08-30 16:53:35.112  7686  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-30 16:53:35.114  7686  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@311ff73a on behalf of 
08-30 16:53:35.114  7686  8041 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:53:35.117  7686  8041 V BluetoothOppNotification: inbound notification was removed.
08-30 16:53:35.117  7686  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:53:35.119  7686  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18cc1feb on behalf of 
08-30 16:53:35.498   325   889 D SoftapController: Softap fwReload - Ok
,08-30 16:53:35.508  1045  1424 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (668ms)
08-30 16:53:35.515   325   889 D CommandListener: Setting iface cfg
08-30 16:53:35.515   325   889 D CommandListener: Trying to bring down wlan0
,08-30 16:53:35.536   325   889 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:53:35.539  1045  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:53:35.539  1045  1120 D Tethering: InitialState.processMessage what=4
,08-30 16:53:35.560  1045  1424 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 16:53:35.560  1045  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:53:35.550  8049  8049 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 16:53:35.570  8049  8049 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:35.585  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:35.585  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:35.585  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:53:35.606  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:53:35.609  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 16:53:35.617  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:35.617  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 16:53:35.631  1045  1424 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 16:53:35.631  1045  1424 D WifiMonitor: connecting to supplicant
,08-30 16:53:35.637  8049  8049 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 16:53:35.671  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:53:35.671  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:53:35.671  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:53:35.671  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:53:35.674  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 16:53:35.675  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:53:35.675  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:53:35.676  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:53:35.676  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:53:35.676  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:53:35.676  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:53:35.680  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:53:35.680  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:53:35.680  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:53:35.680  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:53:35.681  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:53:35.682  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:53:35.682  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:53:35.682  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:53:35.682  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:53:35.682  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:53:35.682  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:53:35.699  8049  8049 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:53:35.700  8049  8049 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 16:53:35.734  1045  1976 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8067 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 16:53:35.775  8049  8049 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:53:35.839  8049  8049 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 16:53:35.844  8049  8049 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 16:53:35.846  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:53:35.847  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 16:53:35.847  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:53:35.848  1045  1424 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:53:35.848  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 16:53:35.848  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 16:53:35.848  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:53:35.848  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:53:35.848  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:35.848  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:35.849  1045  1424 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:35.849  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:35.850  1045  1424 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 16:53:35.850  1045  1424 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 16:53:35.851  1045  1424 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 16:53:35.851  1045  1424 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 16:53:35.851  1045  1424 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 16:53:35.857  1045  2079 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:53:35.865  1045  1424 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:53:35.865  1045  1424 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:53:35.865  1045  1424 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:53:35.866  1045  1424 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 16:53:35.866  1045  1424 D WifiNative-wlan0: SET update_config 1: returned true
08-30 16:53:35.866  1045  1424 D WifiConfigStore: Loading config and enabling all networks 
08-30 16:53:35.866  1045  1424 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 16:53:35.867  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.868  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.868  1045  1424 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 16:53:35.868  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.868  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.868  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:53:35.869  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:35.870  1953  1953 D WfdService: Waiting for WifiP2p enabling
08-30 16:53:35.870  1045  1045 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 16:53:35.870  1045  1454 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-30 16:53:35.877  1045  1424 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:53:35.877  6600  6600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:53:35.881  6600  6600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:53:35.884  8067  8087 W FormManager: Network not available. Please check & try again.
,08-30 16:53:35.888  8067  8088 V FormManager: Network unavailable.
08-30 16:53:35.889  1045  1424 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 16:53:35.890  1045  1424 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 16:53:35.891  8067  8088 V FormManager: Network unavailable.
08-30 16:53:35.891  1045  1424 D WifiStateMachine: enableVerboseLogging : level 2
08-30 16:53:35.891  1045  1424 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 16:53:35.891  1045  1424 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 16:53:35.891  1045  1424 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 16:53:35.892  1045  1424 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 16:53:35.892  1045  1424 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 16:53:35.892  1045  1424 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 16:53:35.893  1045  1424 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 16:53:35.893  1045  1424 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 16:53:35.893  1045  1424 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 16:53:35.894  1045  1424 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 16:53:35.894  1045  1424 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 16:53:35.894  1045  1424 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 16:53:35.894  1045  1424 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 16:53:35.895  1045  1424 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-30 16:53:35.895  1045  1424 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:53:35.895  1045  1424 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 16:53:35.896  1953  1953 D WfdsService: Supplicant Connection state is changed : true
08-30 16:53:35.896  1953  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 16:53:35.896  1045  1424 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 16:53:35.896  1953  2345 D WfdsService: Set the WFDS Monitor: true
08-30 16:53:35.896  1045  1424 D WifiNative-HAL: Setting external_sim to 1
08-30 16:53:35.896  1953  2345 D WfdsMonitor: WfdsMonitorThread create
08-30 16:53:35.896  1045  1424 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 16:53:35.896  1953  2345 D WfdsMonitor: WFDS Monitor is created and started
08-30 16:53:35.896  1953  2345 D WfdsService: WiFi: Supplicant connection re-established
08-30 16:53:35.897  1045  1424 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 16:53:35.897  1045  1424 I WifiNative-HAL: startHal
08-30 16:53:35.897  1045  1424 D wifi    : setting scan oui 0x9541bbe0
08-30 16:53:35.897  1045  1424 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:53:35.897  1045  1424 I WifiNative-HAL: startHal
08-30 16:53:35.897  1045  1424 D wifi    : setting scan oui 0x9541bbe0
08-30 16:53:35.898  1953  8108 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 16:53:35.898  1045  1424 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 16:53:35.898  1953  8108 E CtrlSupplicant: Succeed to open control connection
08-30 16:53:35.899  1953  8108 E CtrlSupplicant: Succeed to open monitor connection
08-30 16:53:35.899  1045  1424 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 16:53:35.899  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 16:53:35.899  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 16:53:35.899  1953  8108 D WfdsMonitor: Supplicant connection established
08-30 16:53:35.899  7715  7715 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.900  1953  2345 D WfdsService: Connected to the supplicant for wfds
08-30 16:53:35.900  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 16:53:35.900  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:53:35.900  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:53:35.901  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:53:35.901  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 16:53:35.901  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 16:53:35.902  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 16:53:35.902  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:53:35.902  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:53:35.902  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:53:35.902  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:53:35.902  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:53:35.903  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:53:35.903  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 16:53:35.903  8049  8049 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 16:53:35.904  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 16:53:35.904  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:53:35.904  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:53:35.904  1045  1424 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:53:35.905  1045  1424 E WifiNative: : [137,376,207 us] RECONNECT  st,ack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 16:53:35.905  1045  1424 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 16:53:35.906  1045  1424 D WifiNative-wlan0: RECONNECT: returned true
08-30 16:53:35.906  1045  1424 D WifiNative-wlan0: doString: [STATUS]
08-30 16:53:35.906  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:53:35.907  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 16:53:35.907  1045  1424 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:53:35.907  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:53:35.908  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:35.908  1045  1375 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.910   325   889 D CommandListener: Setting iface cfg
08-30 16:53:35.910   325   889 D CommandListener: Trying to bring up p2p0
08-30 16:53:35.910  1045  1375 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:53:35.910  1045  1375 D LGWifiP2pService: P2pEnablingState
,08-30 16:53:35.910  1045  1045 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 16:53:35.910  1045  1375 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.910  1045  1375 D LGWifiP2pService: P2p socket connection successful
08-30 16:53:35.910  1045  1045 D RttService: SCAN_AVAILABLE : 3
08-30 16:53:35.910  1045  1375 D LGWifiP2pService: P2pEnabledState
08-30 16:53:35.911  1045  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.911  1045  1543 I WifiNative-HAL: startHal
08-30 16:53:35.911  1045  1375 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 16:53:35.911  1045  1543 D wifi    : getting scan capabilities on interface[1] = 0x9541bbe0
08-30 16:53:35.911  1045  1543 D wifi    : failed to get capabilities : -3
08-30 16:53:35.911  1045  1543 E WifiScanningService: could not get scan capabilities
08-30 16:53:35.911  1045  1424 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:53:35.911  1045  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.911  1045  1375 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 16:53:35.911  1045  1375 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 16:53:35.912  1045  1375 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 16:53:35.912  1045  1375 D WifiNative-p2p0: SET device_name G3: returned true
08-30 16:53:35.912  1045  1375 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 16:53:35.912  1045  1375 D LGWifiP2pService: before postfix = G3
08-30 16:53:35.912  1045  1375 D WifiServerServiceExt: postfix byte check : 2
08-30 16:53:35.912  1045  1375 D LGWifiP2pService: after postfix = G3
08-30 16:53:35.912  1045  1375 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 16:53:35.913  1045  1375 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 16:53:35.913  1045  1375 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 16:53:35.913  1045  1424 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 16:53:35.913  1045  1375 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 16:53:35.913  1045  1375 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 16:53:35.914  1045  1424 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 16:53:35.914  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 16:53:35.914  1953  1953 D WfdsService: WifiP2pState is changed : true
08-30 16:53:35.914  1045  1375 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 16:53:35.914  1953  1953 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 16:53:35.914  1953  2345 D WfdsService: Receive the WFDS_ENABLE Method
08-30 16:53:35.914  1953  2345 D WfdsService: Set the WFDS Monitor: true
08-30 16:53:35.914  1953  2345 D WfdsService: Connected to the supplicant for wfds
08-30 16:53:35.914  1953  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 16:53:35.914  8049  8049 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 16:53:35.914  1953  1953 D WfdsService: isConnected: false
08-30 16:53:35.915  1953  2345 D WfdsService: selectPreferredScanChannel [36]
08-30 16:53:35.915  1953  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 16:53:35.915  1045  1424 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 16:53:35.914  1045  1375 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 16:53:35.915  1045  1424 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 16:53:35.915  1045  1375 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 16:53:35.915  1045  1375 D WifiNative-HAL: p2pGetDeviceAddress
08-30 16:53:35.916  1045  142,4 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 16:53:35.916  1045  1375 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 16:53:35.917  1045  1424 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 16:53:35.917  1045  1424 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 16:53:35.917  8049  8049 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 16:53:35.918  1045  1424 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 16:53:35.918  1045  1375 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 16:53:35.918  1045  1375 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 16:53:35.918  1045  1424 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 16:53:35.918  1045  1375 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 16:53:35.918  1045  1375 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 16:53:35.918  1045  1424 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 16:53:35.918  1045  1424 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 16:53:35.919  8049  8049 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 16:53:35.919  1045  1375 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 16:53:35.919  1045  1375 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 16:53:35.919  1045  1375 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 16:53:35.919  1045  1375 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 16:53:35.919  1045  1424 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 16:53:35.920  1953  1953 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 16:53:35.920  1953  1953 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 16:53:35.920  1953  1953 D WfdsService: Update P2p Interface State: 3
08-30 16:53:35.920  1045  1424 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 16:53:35.921  1045  1424 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 16:53:35.921  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 16:53:35.927  1045  1728 I ActivityManager: Killing 7125:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 16:53:35.930  1045  1375 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 16:53:35.930  1045  1375 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 16:53:35.931  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 16:53:35.931  8049  8049 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.932  8049  8049 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:53:35.932  8049  8049 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.932  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:53:35.932  1953  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.932  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.932  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.932  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.932  1045  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.932  1045  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.932  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.932  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.932  1045  1424 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 16:53:35.933  8049  8049 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.933  1045  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.933  1953  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.933  1045  1424 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:53:35.933  1045  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.933  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.933  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.934  1045  1424 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:53:35.934  1045  1424 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:53:35.934  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 16:53:35.934  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 16:53:35.934  8049  8049 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:35.935  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 16:53:35.935  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:35.935  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:35.935  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:53:35.935  1045  1424 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 16:53:35.935  1045  1424 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 16:53:35.936  1045  1424 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 16:53:35.936  1045  1424 D WifiNative-wlan0: doBoolean: SCAN
08-30 16:53:35.936  1045  1424 D WifiNative-wlan0: SCAN: returned false
08-30 16:53:35.937  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137408  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:53,:35.956  8089  8089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:35.981  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:53:35.982  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137453  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:53:35.982  1045  1375 D LGWifiP2pService: InactiveState
08-30 16:53:35.982  1045  1375 D LGWifiP2pService: InactiveState{ when=-63ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.983  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-64ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.983  1045  1375 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-30 16:53:35.983  1045  1424 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:35.983  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 16:53:35.985  1045  1424 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:35.985  8049  8049 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.986  1045  1424 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:35.986  1045  1424 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:35.987  1045  1424 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:53:35.988  8049  8049 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:53:35.988  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:35.988  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:35.988  8049  8049 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.988  1045  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:53:35.988  1045  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.988  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.989  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:53:35.989  1045  1375 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 16:53:35.989  1045  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.989  1045  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.989  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.989  1045  1375 D LGWifiP2pService: InactiveState{ when=-57ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.989  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.989  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-57ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.989  1045  1375 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.989  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.989  1045  1375 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.989  1045  2079 W libprocessgroup: failed to open /acct/uid_10062/pid_7125/cgroup.procs: No such file or directory
08-30 16:53:35.990  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.990  1953  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:53:35.990  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:35.990  1953  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.990  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:53:35.990  1045  1375 D LGWifiP2pServi,ce: InactiveState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.990  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.990  1045  1375 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.991  1045  1375 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.991  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.991  8049  8049 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.991  1045  1375 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.991  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:35.991  1045  1375 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.991  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.991  1045  1375 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:35.992  1045  1045 E WifiServerServiceExt: No p2p device connected
08-30 16:53:35.992  1953  2345 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 16:53:35.992  1045  8090 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.992  1045  8090 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.992  1045  8090 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.992  1045  8090 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:53:35.993  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:35.993  1045  1045 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 16:53:35.993  1953  8108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:53:35.997  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:36.004  1045  1952 I ActivityManager: Killing 7161:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 16:53:36.039  1045  2042 W libprocessgroup: failed to open /acct/uid_10085/pid_7161/cgroup.procs: No such file or directory
,08-30 16:53:36.062  8089  8089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:53:36.066  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:53:36.075  8067  8112 W FormManager: Network not available. Please check & try again.
,08-30 16:53:36.077  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:36.100  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:36.100  4294  4294 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 16:53:36.102  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:36.106  4294  4294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:53:36.107  8067  8113 V FormManager: Network unavailable.
08-30 16:53:36.112  4294  8114 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:53:36.118  4294  8115 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:53:36.118  4294  8115 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:53:36.179  1045  2012 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8116 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 16:53:36.183  8067  8113 V FormManager: Network unavailable.
,08-30 16:53:36.297  8116  8116 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 16:53:36.297  8116  8116 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 16:53:36.306  8116  8116 V [BNRBootReceiver]: Boot Receiver Return
,08-30 16:53:36.308  8116  8116 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 16:53:36.381  1045  2079 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8137 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 16:53:36.386  1045  2079 I ActivityManager: Killing 7221:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 16:53:36.513  1045  1976 W libprocessgroup: failed to open /acct/uid_10093/pid_7221/cgroup.procs: No such file or directory
08-30 16:53:36.516  8049  8049 E wpa_supplicant: USIM:  scard_init function
,08-30 16:53:36.517  8049  8049 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 16:53:36.522  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 16:53:36.522  1045  8090 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 16:53:36.523  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 16:53:36.523  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-30 16:53:36.523  1045  8090 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 16:53:36.523  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:53:36.523  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 16:53:36.525  1045  1424 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-30 16:53:36.528  1045  1424 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 16:53:36.528  1045  1424 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 16:53:36.529  1045  1424 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 16:53:36.529  1045  1424 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 16:53:36.537  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138008  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 16:53:36.542  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.542  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:53:36.542  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.543  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.543  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:53:36.547  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.547  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.547  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 16:53:36.548  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138019  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 16:53:36.548  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.549  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:36.549  1045  1045 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 16:53:36.551  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.551  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:36.556  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:53:36.564  8137  8137 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:36.586  8137  8137 D PluginManager: init()
,08-30 16:53:36.636  8049  8049 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 16:53:36.637  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 16:53:36.637  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 16:53:36.637  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 16:53:36.637  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-30 16:53:36.638  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:36.638  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:36.638  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138110  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:53:36.639  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138110  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:53:36.642  1045  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 16:53:36.646  1045  1424 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138117
08-30 16:53:36.648  1045  1424 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138119
08-30 16:53:36.648  1045  1424 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138119
08-30 16:53:36.649  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138120
08-30 16:53:36.649  1045  1424 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138120
08-30 16:53:36.650  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138121  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 16:53:36.658  8049  8049 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:53:36.658  8049  8049 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:53:36.660  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.660  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:36.661  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.661  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.661  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 16:53:36.662  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.662  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.662  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 16:53:36.663  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:36.663  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:36.663  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 16:53:36.664  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:53:36.664  1045  8090 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:53:36.664  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.664  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 16:53:36.664  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:53:36.664  1045  8090 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:53:36.664  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:36.665  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:36.666  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 16:53:36.666  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:36.667  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138137  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 16:53:36.668  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-30 16:53:36.668  1045  1045 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-30 16:53:36.669  1045  1424 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:36.669  1045  1424 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:36.669  1045  1424 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:36.670  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:36.670  1045  1424 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:53:36.671  1045  1424 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138142  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:53:36.671  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138143  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:53:36.672  1045  1424 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138143
08-30 16:53:36.672  1045  1424 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138144
08-30 16:53:36.673  1045  1424 D WifiNative-wlan0: doString: [STATUS]
08-30 16:53:36.674  1045  8090 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:53:36.674  1045  8090 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:53:36.674  1045  1424 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:53:36.675  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.676  1045  1424 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 16:53:36.685  1045  1424 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 16:53:36.685  1045  1424 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 16:53:36.689  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.689  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:36.690  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.691  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.691  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.691  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:53:36.693  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.693  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:36.694  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.695  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.696  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.696  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:53:36.700  1045  1424 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-30 16:53:36.700  1045  1505 D ConnectivityService: Got NetworkAgent Messenger
08-30 16:53:36.700  1045  1424 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:53:36.701  1045  1424 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:53:36.701  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 16:53:36.701  1045  1505 D ConnectivityService: NetworkAgent connected
08-30 16:53:36.701  1045  1424 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:53:36.701  1045  1424 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:53:36.705  1045  1424 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:53:36.705  1045  1424 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:53:36.705  1045  1424 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:53:36.706  1045  1424 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:53:36.706  1045  1424 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:53:36.709  1045  1424 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:53:36.711   325   889 D CommandListener: Setting iface cfg
08-30 16:53:36.714  1045  1424 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 16:53:36.714  1045  1424 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138185  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 16:53:36.715  1045  1424 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138186  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:36.715  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138186  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:36.716  1045  1424 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138187  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:36.717  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:36.717  1045  1045 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 16:53:36.717  1045  1424 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138188  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:36.717  1045  1424 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138188  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:53:36.718  1045  8159 D DhcpStateMachine: StoppedState
08-30 16:53:36.718  1045  8159 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.718  1045  8159 D DhcpStateMachine: WaitBeforeStartState
08-30 16:53:36.718  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14425] from screen [on:0 period:-604965810] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 16:53:36.719  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-604965809] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 16:53:36.719  1045  1424 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 16:53:36.724  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.724  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.724  1045  1424 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.725  1045  1424 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.725  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.725  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.726  1045  1505 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 16:53:36.726  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-30 16:53:36.727  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:36.727  1045  1045 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:53:36.729  1045  1045 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:53:36.729  1045  1045 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:53:36.730  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=121,0,0
08-30 16:53:36.730  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=121,0,0
08-30 16:53:36.731  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 16:53:36.731  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 16:53:36.731  1045  1424 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 16:53:36.731  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 16:53:36.732  1045  1424 D WifiNative-wlan0: SET ps 0: returned true
08-30 16:53:36.732  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 16:53:36.732  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 16:53:36.732  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 16:53:36.732  1045  1424 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 16:53:36.732  1045  1424 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:53:36.732  1045  1424 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:53:36.733  1045  1375 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e0510c2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.733  1045  1375 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e0510c2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.733  1045  8159 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.733  1045  8159 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 16:53:36.734   325   889 D CommandListener: Setting iface cfg
08-30 16:53:36.734   325   889 D CommandListener: Trying to bring up wlan0
08-30 16:53:36.735  1045  1424 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 16:53:36.736  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.736  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.737  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.738  1045  1424 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.738  1045  1424 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.739  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.739  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:53:36.740  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:53:36.741  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:53:36.741  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:53:36.741  1045  1375 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.741  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 16:53:36.741  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:53:36.741  1045  1375 D LGWifiP2pService: P,2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.741  1045  1424 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:53:36.741  1045  1424 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 16:53:36.742  8049  8049 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 16:53:36.742  1045  1424 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 16:53:36.742  1045  1424 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 16:53:36.758  1045  1424 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:53:36.759  1045  1424 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:53:36.760  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:53:36.760  1045  1424 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 16:53:36.760  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 16:53:36.760  1045  1505 D ConnectivityService: ignoring duplicate network state non-change
08-30 16:53:36.762  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.762  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:53:36.764  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.764  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.764  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:53:36.764  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.765  1045  1505 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 16:53:36.765  1045  1505 D ConnectivityService: Adding iface wlan0 to network 102
08-30 16:53:36.770  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.770  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.770  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:53:36.772  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 16:53:36.773  1045  1045 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:53:36.773  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.773  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.773  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-30 16:53:36.779  1045  1045 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:53:36.779  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.779  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:53:36.780  1045  1045 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:53:36.784  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.784  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:53:36.785  1045  1424 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:53:36.786  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.787  1045  1505 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 16:53:36.787  1045  1505 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 16:53:36.788  1045  1505 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 16:53:36.788  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.788  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:53:36.788  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.789   325   889 E Netd    : netlink response contains error (File exists)
,08-30 16:53:36.789  1045  1505 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 16:53:36.790  1045  1505 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 16:53:36.790  1045  1505 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 16:53:36.790  1045  1505 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 16:53:36.790  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:36.790  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:53:36.791  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.791  1045  1505 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:53:36.794  1045  1505 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.794  1045  1505 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.795  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.795  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 16:53:36.795  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:53:36.795  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 16:53:36.796  1045  1505 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.797  1045  1505 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:36.797  1045  1505 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:36.797  1045  1505 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:53:36.797  1045  1505 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.797  1045  1505 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 16:53:36.797  1045  1505 D ConnectivityService: currentScore = 0, newScore = 20
08-30 16:53:36.797  1045  1505 D ConnectivityService:    accepting network in place of null
08-30 16:53:36.797  1045  1505 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.798   325  8164 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-30 16:53:36.799  1045  1424 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.800  1045  1424 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:36.800  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.800  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:53:36.802  1045  1505 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 16:53:36.802  1045  1505 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 16:53:36.802  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:53:36.804  1045  1045 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 16:53:36.804  1045  1045 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:53:36.804  1045  1045 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:53:36.804  1045  1045 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:53:36.804  1045  1505 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:36.804  1045  1505 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 16:53:36.805  1045  1505 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 16:53:36.806  1045  1505 D ConnectivityService: validation of new default Network = false
08-30 16:53:36.806  1045  1505 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 16:53:36.806  1045  1505 D DSQN    : enableDataServiceNotify 
08-30 16:53:36.806  1045  1505 D DSQN    : start dsqn bin
,08-30 16:53:36.813  1045  1505 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.813  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.813  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:36.814  1045  1505 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:36.800  8165  8165 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:36.814  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:53:36.800  8165  8165 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:36.820  1045  1374 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 16:53:36.824  8165  8165 E DSQN    : DSQN ssw
,08-30 16:53:36.834  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:53:36.835  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.836  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:36.842  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:53:36.843  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:36.846  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 16:53:36.846  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 16:53:36.847  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d39c4a0 Bundle[{}]
08-30 16:53:36.848  6600  6706 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:53:36.848  6600  6706 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 16:53:36.848  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 16:53:36.849  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 16:53:36.849  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 16:53:36.850  6600  6706 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 16:53:36.853  6600  6706 I System.out: Running OutgoingSocketThread
,08-30 16:53:36.855  6600  8169 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 846)
,08-30 16:53:36.856  6600  8169 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43631
08-30 16:53:36.856  6600  8169 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 16:53:36.858   325  8164 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 16:53:36.891   325  8164 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 16:53:36.919   325   888 D LGDataListener: argv[0]=dsqncommand
,08-30 16:53:36.919   325   888 D LGDataListener: argv[1]=wlan0
08-30 16:53:36.919   325   888 D LGDataListener: argv[2]=1
08-30 16:53:36.919   325   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 16:53:36.920  1045  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 16:53:36.920  1045  1118 D DSQN    : start to monitor internet connection
08-30 16:53:36.935  1045  8159 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 16:53:36.937  1045  8159 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 16:53:36.937  1045  8159 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 16:53:36.930  8172  8172 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:36.930  8172  8172 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:53:36.946  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:53:36 GMT], X-Android-Received-Millis=[1472568816944], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472568816918]}
08-30 16:53:36.946  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 16:53:36.946  1045  8154 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 16:53:36.947  1045  1505 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.947  1045  1505 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.947  8172  8172 I dhcpcd  : version 5.5.6 starting
08-30 16:53:36.948  1045  1505 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:36.948  1045  1505 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:36.948  1045  1505 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:53:36.948  1045  1505 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 16:53:36.948  1045  1505 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 16:53:36.948  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.949  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:36.949  1045  1505 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 16:53:36.950  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:53:36.950  1045  1505 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.950  1045  1424 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.950  1045  1424 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:53:36.952  8172  8172 E dhcpcd  : get_duid: m
08-30 16:53:36.952  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 16:53:36.953  8172  8172 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 16:53:36.953  8172  8172 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 16:53:36.953  1864  1864 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:36.953  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:53:36.976  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:53:36.976  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:53:36.977  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:37.022  8137  8137 W ExternalStrings: load override strings
08-30 16:53:37.022  8137  8137 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:37.022  8137  8137 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 16:53:37.025  8137  8137 D StatusProvider: onCreate
08-30 16:53:37.041  8172  8172 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 16:53:37.041  8172  8172 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-30 16:53:37.042  8172  8172 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:53:37.042  8172  8172 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 16:53:37.043  8172  8172 D dhcpcd  : wlan0: sending REQUEST (xid 0xc1297d17), next in 3.63 seconds
08-30 16:53:37.060  8137  8137 V Signer  : override build config not found
08-30 16:53:37.061  8137  8137 D Signer  : value of property debug is false
,08-30 16:53:37.083  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-30 16:53:37.083  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 16:53:37.084  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 16:53:37.085  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 16:53:37.085  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 16:53:37.085  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 16:53:37.085  8137  8137 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 16:53:37.092  8137  8137 V LGMDMManager: Create singleton instance
08-30 16:53:37.095  8172  8172 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 16:53:37.127  8137  8137 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 16:53:37.137  8172  8172 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 16:53:37.137  8172  8172 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 16:53:37.138  8172  8172 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 16:53:37.138  8172  8172 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 16:53:37.138  8172  8172 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:53:37.139  8172  8172 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 16:53:37.139  8172  8172 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 16:53:37.139  8172  8172 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 16:53:37.216  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:37.219  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 16:53:37.243  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.250  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.259  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:37.263  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.279  7953  7953 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 16:53:37.284  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 16:53:37.287  6805  6805 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 16:53:37.290  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.291  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 16:53:37.301  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.308  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.314  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.315  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.316  7953  7953 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 16:53:37.435  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:37.436  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 16:53:37.442  8137  8186 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 16:53:37.445  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.453  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.461  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.462  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.462  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:53:37.468  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 16:53:37.468  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:53:37.468  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:53:37.468  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:53:37.469  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:53:37.470  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:53:37.470  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 16:53:37.470  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:53:37.470  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:53:37.470  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:53:37.470  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 16:53:37.470  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:53:37.475  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.475  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 16:53:37.482  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:53:37.488  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:37.493  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:37.494  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.494  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:37.498  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.498  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 16:53:37.504  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.512  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.519  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.520  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:53:37.520  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:37.524  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.525  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 16:53:37.531  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.537  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.540  1045  8159 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 16:53:37.542  1045  8159 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 16:53:37.542  1045  8159 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:53:37.542  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.543  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.543  1045  8159 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 16:53:37.543  1045  8159 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 16:53:37.543  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:37.543  1045  8159 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:53:37.543  1045  8159 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 16:53:37.543  1045  8159 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 16:53:37.544  1045  8159 D DhcpStateMachine: RunningState
08-30 16:53:37.547  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.547  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 16:53:37.554  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.559  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:37.566  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:37.567  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.567  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:53:37.577  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.577  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 16:53:37.596  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.603  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.612  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:53:37.612  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.620  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:37.625  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.625  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 16:53:37.634  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.641  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.648  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.649  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.649  7953  7953 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:53:37.654  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:53:37.655  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 16:53:37.659  8089  8089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 16:53:37.663  8137  8186 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:37.663  8089  8089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:37.663  8137  8186 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:53:37.666  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:53:37.673  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:53:37.680  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.680  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.681  7953  7953 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 16:53:37.682  7953  7953 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:53:37.683  7953  7953 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 16:53:37.688  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:53:37.688  8137  8187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 16:53:37.693  8089  8089 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 16:53:37.694  8089  8089 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:53:37.698  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:53:37.705  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:53:37.713  7953  7953 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:53:37.714  7953  7953 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:53:37.714  7953  7953 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 16:53:37.715  7953  7953 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:53:37.716  7953  7953 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 16:53:37.719  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.721  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.724  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.727  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 16:53:37.729  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.732  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.735  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.737  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.739  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 16:53:37.744  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 16:53:37.746  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 16:53:37.748  1045  1735 I ActivityManager: Killing 7199:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 16:53:37.815  8137  8186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 16:53:37.830  1045  1424 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 16:53:37.831  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:37.833  1045  1424 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:37.834  1045  1424 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:37.835  1045  1424 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:37.836  1045  1424 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:53:37.838  1045  1505 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 16:53:37.838  1045  1505 D ConnectivityService: identical MTU - not setting
08-30 16:53:37.838  1045  1505 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:53:37.839  1045  1505 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 16:53:37.840  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:53:37.840  1045  1505 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:37.841  1045  1505 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:53:37.843  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 16:53:37.855  6600  6706 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 847)
08-30 16:53:37.855  6600  6706 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 847)
08-30 16:53:37.861  6600  6706 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 852)
08-30 16:53:37.862  1045  1060 W libprocessgroup: failed to open /acct/uid_10005/pid_7199/cgroup.procs: No such file or directory
08-30 16:53:37.863  6600  6706 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 16:53:37.863  6600  6706 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 853)
,08-30 16:53:37.872  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:37.872  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb277ef added. We now have 2 listener(s)
08-30 16:53:37.872  1045  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:37.878  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:37.878  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:37.878  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:37.878  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:37.878  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6212fc added. We now have 9 listener(s)
08-30 16:53:37.878  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:37.879  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:53:37.882  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:37.891  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:53:37.895  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:37.895  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:37.895  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:37.896  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f977da added. We now have 3 listener(s)
08-30 16:53:37.896  1045  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:37.899  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:37.899  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:37.899  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:37.899  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:37.899  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3958a40b added. We now have 10 listener(s)
08-30 16:53:37.899  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:37.899  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:37.899  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:37.899  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:37.899  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:37.899  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.899  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:37.899  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:37.900  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb277ef removed from the list
08-30 16:53:37.900  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.900  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6212fc removed from the list
08-30 16:53:37.900  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:37.900  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:37.900  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.901  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.901  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.903  6600  6,706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:37.903  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:37.903  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.903  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6212fc not in the list
08-30 16:53:37.903  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.903  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.904  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:37.905  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:37.905  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:37.905  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.905  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3958a40b removed from the list
08-30 16:53:37.905  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:37.905  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.905  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.905  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:37.905  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f977da removed from the list
08-30 16:53:37.906  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:53:37.906  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@183b62e8 added. We now have 2 listener(s)
08-30 16:53:37.907  1045  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 16:53:37.910  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 16:53:37.910  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:37.910  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:37.910  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:53:37.910  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10dbfd01 added. We now have 9 listener(s)
08-30 16:53:37.910  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:37.912  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:53:37.915  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:37.916  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:37.923  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:37.925  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:37.925  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:37.925  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:37.925  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30eb75e7 added. We now have 3 listener(s)
08-30 16:53:37.925  1045  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 16:53:37.928  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:37.931  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:37.935  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 16:53:37.935  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:37.935  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:37.935  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:37.935  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:37.935  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 16:53:37.935  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29d7c594 added. We now have 10 listener(s)
08-30 16:53:37.936  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:37.936  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:37.936  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 16:53:37.936  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:53:37.936  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:53:37.936  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:37.936  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:53:37.937  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 16:53:37.937  8137  8186 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-30 16:53:37.940  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:53:37.941  1045  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:37.942  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 16:53:37.944  8137  8186 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 16:53:37.950  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:53:37.951  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:53:37.953  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:53:37.954  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:37.956  6600  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 16:53:37.956  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:37.956  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:37.958  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:53:37.958  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:37.958  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:37.958  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:53:37.958  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.958  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:53:37.959  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:53:37.959  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@183b62e8 removed from the list
08-30 16:53:37.959  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:53:37.959  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10dbfd01 removed from the list
,08-30 16:53:37.959  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:37.959  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 16:53:37.959  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.959  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.960  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:53:37.960  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:37.960  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.960  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10dbfd01 not in the list
,08-30 16:53:37.960  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.960  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.961  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:53:37.962  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:37.962  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:37.962  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:53:37.962  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.962  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29d7c594 removed from the list
08-30 16:53:37.962  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:53:37.962  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.962  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.962  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:53:37.962  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30eb75e7 removed from the list
08-30 16:53:37.963  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:37.963  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aef8983 added. We now have 2 listener(s)
,08-30 16:53:37.963  1045  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:37.966  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:37.966  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:53:37.966  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:37.966  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:37.966  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2235a700 added. We now have 9 listener(s)
,08-30 16:53:37.966  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:37.967  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:53:37.969  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:37.973  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:37.974  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:37.974  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:37.975  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-30 16:53:37.976  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1053957e added. We now have 3 listener(s)
08-30 16:53:37.976  1045  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:37.977  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:37.979  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:37.981  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:37.981  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:37.981  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:53:37.981  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:53:37.981  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8973adf added. We now have 10 listener(s)
08-30 16:53:37.981  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:37.982  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:37.982  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:37.982  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:53:37.982  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:53:37.982  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:37.983  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:53:37.985  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:53:37.986  1045  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:37.990  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:53:37.990  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:53:37.992  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:53:37.992  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:37.994  6600  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:53:37.995  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:37.995  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:37.995  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:37.995  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:37.995  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.995  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:37.995  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:37.995  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aef8983 removed from the list
08-30 16:53:37.995  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.995  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.bt,connectorlib.DiscoveryManager@2235a700 removed from the list
08-30 16:53:37.995  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:37.995  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.996  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.996  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:53:37.997  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:37.997  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:37.997  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.998  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2235a700 not in the list
08-30 16:53:37.998  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.998  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.998  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:37.999  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:37.999  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:37.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:37.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:37.999  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8973adf removed from the list
08-30 16:53:37.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:37.999  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:37.999  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:37.999  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:37.999  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1053957e removed from the list
08-30 16:53:38.000  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:38.000  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80f8b8a added. We now have 2 listener(s)
08-30 16:53:38.000  1045  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:38.003  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:38.003  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:38.003  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:38.003  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:38.003  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21dea5fb added. We now have 9 listener(s)
08-30 16:53:38.003  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:38.004  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:53:38.006  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoot,hManager: bind: Binding a new listener
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:38.010  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:53:38.011  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:38.011  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:38.012  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:38.012  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26dd2871 added. We now have 3 listener(s)
08-30 16:53:38.012  1045  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:38.014  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:38.016  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:38.016  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:38.016  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:38.016  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:38.016  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e2d656 added. We now have 10 listener(s)
08-30 16:53:38.016  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:38.016  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:38.016  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:53:38.016  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:53:38.016  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:38.016  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:53:38.017  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:38.019  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:53:38.020  1045  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:38.024  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:53:38.025  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:53:38.027  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:53:38.027  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:38.029  6600  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:53:38.030  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:38.030  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:38.030  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:38.030  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:38.030  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.030  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:38.030  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:38.031  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80f8b8a removed from the list
08-30 16:53:38.031  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:38.031  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21dea5fb removed from the list
08-30 16:53:38.031  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:38.031  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.031  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.031  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.032  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:38.032  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:38.032  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:38.032  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21dea5fb not in the list
08-30 16:53:38.032  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.032  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.033  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:38.034  6600  6706 D BluetoothLeScanner: could not find callback wrapper
08-30 16:53:38.034  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:53:38.034  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:38.034  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:38.034  6600,  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e2d656 removed from the list
08-30 16:53:38.034  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:38.034  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.034  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.034  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:38.034  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26dd2871 removed from the list
08-30 16:53:38.035  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:38.035  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22cadaad added. We now have 2 listener(s)
,08-30 16:53:38.035  1045  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:38.037  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:38.037  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:38.037  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:38.038  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:38.038  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dce01e2 added. We now have 9 listener(s)
08-30 16:53:38.038  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:38.038  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:53:38.041  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:53:38.044  6600  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:53:38.046  6600  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:53:38.046  6600  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:53:38.046  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:53:38.046  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f80d030 added. We now have 3 listener(s)
08-30 16:53:38.047  1045  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:53:38.048  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:53:38.050  6600  6600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:53:38.051  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:53:38.051  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:53:38.051  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:53:38.051  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:53:38.051  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e6774a9 added. We now have 10 listener(s)
08-30 16:53:38.051  6600  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:53:38.051  6600  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:53:38.052  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:38.052  6600  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:53:38.052  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:38.052  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.052  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:53:38.052  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:38.052  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22cadaad removed from the list
08-30 16:53:38.052  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:38.052  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dce01e2 removed from the list
08-30 16:53:38.052  6600  6706 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:53:38.052  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.052  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.052  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.053  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:38.053  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:38.053  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:38.053  6600  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dce01e2 not in the list
08-30 16:53:38.053  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.053  6600  6706 D org.thaliproject.p2p.btconne,ctorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.054  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:53:38.054  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:53:38.054  6600  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:53:38.054  6600  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e6774a9 removed from the list
08-30 16:53:38.054  6600  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:53:38.054  6600  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:53:38.054  6600  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:53:38.054  6600  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:53:38.054  6600  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f80d030 removed from the list
08-30 16:53:38.055  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 16:53:38.055  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:53:38.056  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 16:53:38.056  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:53:38.056  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 16:53:38.056  6600  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:53:38.067  6600  8228 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 860, name: My test thread name)
08-30 16:53:38.067  6600  8228 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 860, thread name: My test thread name)
08-30 16:53:38.067  6600  8228 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 860, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 16:53:38.069  6600  8229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: My test thread name)
08-30 16:53:38.069  6600  8229 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 862, thread name: My test thread name)
08-30 16:53:38.069  6600  8229 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 862, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 16:53:38.072  6600  6706 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 16:53:38.072  6600  6706 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 16:53:38.072  6600  6706 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 16:53:38.072  6600  6706 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 16:53:38.072  6600  6706 D com.test.thalitest.ThaliTestRunner: Total duration: 24222 ms
08-30 16:53:38.073  6600  6706 I jxcore-log: *Native tests were executed*
08-30 16:53:38.073  6600  6706 I jxcore-log: 
08-30 16:53:38.074  6600  6706 I jxcore-log: Total number of executed tests:  80
08-30 16:53:38.074  6600  6706 I jxcore-log: 
08-30 16:53:38.074  6600  6706 I jxcore-log: Number of passed tests:  80
08-30 16:53:38.074  6600  6706 I jxcore-log: 
08-30 16:53:38.074  6600  6706 I jxcore-log: Number of failed tests:  0
08-30 16:53:38.074  6600  6706 I jxcore-log: 
08-30 16:53:38.074  6600  6706 I jxcore-log: Number of ignored tests:  0
08-30 16:53:38.074  6600  6706 I jxcore-log: 
08-30 16:53:38.075  6600  6706 I jxcore-log: Total duration:  24222
08-30 16:53:38.075  6600  6706 I jxcore-log: 
08-30 16:53:38.075  6600  6706 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 16:53:38.075  6600  6706 I jxcore-log: 
08-30 16:53:38.078  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.078  6600  6706 I jxcore-log: 
08-30 16:53:38.081  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.081  6600  6706 I jxcore-log: 
,08-30 16:53:38.082  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.082  6600  6706 I jxcore-log: 
08-30 16:53:38.084  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.084  6600  6706 I jxcore-log: 
08-30 16:53:38.085  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.085  6600  6706 I jxcore-log: 
08-30 16:53:38.086  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.086  6600  6706 I jxcore-log: 
08-30 16:53:38.088  6600  6600 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 16:53:38.090  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.090  6600  6706 I jxcore-log: 
08-30 16:53:38.091  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.091  6600  6706 I jxcore-log: 
08-30 16:53:38.093  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:53:38.093  6600  6706 I jxcore-log: 
08-30 16:53:38.094  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:53:38.094  6600  6706 I jxcore-log: 
08-30 16:53:38.094  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:53:38.094  6600  6706 I jxcore-log: 
08-30 16:53:38.096  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.096  6600  6706 I jxcore-log: 
,08-30 16:53:38.097  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.097  6600  6706 I jxcore-log: 
,08-30 16:53:38.098  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.098  6600  6706 I jxcore-log: 
,08-30 16:53:38.099  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.099  6600  6706 I jxcore-log: 
,08-30 16:53:38.099  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.099  6600  6706 I jxcore-log: 
08-30 16:53:38.100  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.100  6600  6706 I jxcore-log: 
08-30 16:53:38.101  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.101  6600  6706 I jxcore-log: 
08-30 16:53:38.101  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:53:38.101  6600  6706 I jxcore-log: 
08-30 16:53:38.102  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:53:38.102  6600  6706 I jxcore-log: 
08-30 16:53:38.103  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.103  6600  6706 I jxcore-log: 
08-30 16:53:38.104  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.104  6600  6706 I jxcore-log: 
08-30 16:53:38.104  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.104  6600  6706 I jxcore-log: 
08-30 16:53:38.105  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.105  6600  6706 I jxcore-log: 
08-30 16:53:38.106  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.106  6600  6706 I jxcore-log: 
08-30 16:53:38.107  6600  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:53:38.107  6600  6706 I jxcore-log: 
08-30 16:53:38.477  8230  8230 D AndroidRuntime: 
08-30 16:53:38.477  8230  8230 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 16:53:38.481  8230  8230 D AndroidRuntime: CheckJNI is OFF
,08-30 16:53:38.721  8230  8230 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 16:53:38.739  1045  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-30 16:53:38.741  1045  1114 I ActivityManager: Killing 6600:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 16:53:38.815  1045  2012 I WindowState: WIN DEATH: Window{37e8e08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 16:53:38.816  1045  1482 D WifiService: Client connection lost with reason: 4
08-30 16:53:38.833  1045  2012 D InputDispatcher: Window went away: Window{37e8e08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 16:53:38.960  1045  1114 I ActivityManager:   Force finishing activity ActivityRecord{385c6dfd u0 com.test.thalitest/.MainActivity t6}
,08-30 16:53:38.996   348   370 E GBMv2   : DFP En is all cleared set to be enabled
08-30 16:53:39.005  1045  1060 W ActivityManager: Spurious death for ProcessRecord{2966239c 6600:com.test.thalitest/u0a118}, curProc for 6600: null
,08-30 16:53:39.006  1045  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 16:53:39.011  1045  1126 I ActivityManager:   Force finishing activity ActivityRecord{385c6dfd u0 com.test.thalitest/.MainActivity t6 f}
08-30 16:53:39.011  1045  1126 W ActivityManager: Duplicate finish request for ActivityRecord{385c6dfd u0 com.test.thalitest/.MainActivity t6 f}
,08-30 16:53:39.045  2080  2080 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-30 16:53:39.047  2080  2080 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 16:53:39.047  1953  1968 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 16:53:39.048  1953  1968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{125a47b5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 16:53:39.048  2080  2080 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 16:53:39.050  2080  2165 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-30 16:53:39.057  1915  1915 D ActionManagerService: notifyUserLog: 1000003
08-30 16:53:39.057  1953  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 16:53:39.058  1953  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3d47de4a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 16:53:39.058  3755  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 16:53:39.058  2080  2080 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 16:53:39.062  2080  2080 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-30 16:53:39.063  2080  2080 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 16:53:39.065  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 16:53:39.074  1045  1365 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 16:53:39.078  2025  2025 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 16:53:39.078  7686  7686 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 16:53:39.079  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 16:53:39.079  3755  3755 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 16:53:39.086  2489  2617 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 16:53:39.135  4573  4573 I art     : Explicit concurrent mark sweep GC freed 8194(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 375us total 87.232ms
,08-30 16:53:39.141  2080  2080 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 16:53:39.141  8137  8137 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 16:53:39.146  1915  1915 D ActionManagerService: notifyUserLog: 1000004
08-30 16:53:39.146  2080  2080 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-30 16:53:39.148  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 16:53:39.148  3755  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 16:53:39.150  3755  3770 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:53:39.150  1589  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 16:53:39.150  1589  1635 D KeyguardModel: createShortcutInfo...
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , expire_time: 0
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , display: false
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , animation: false }
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , expire_time: 0
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , display: false
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , animation: false }
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , expire_time: 0
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , display: false
08-30 16:53:39.154  2080  2080 I GBoardWebViewUtils: , animation: false }
08-30 16:53:39.160  1589  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 16:53:39.160  1589  1635 D KeyguardModel: createShortcutInfo...
,08-30 16:53:39.163  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 16:53:39.163  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 16:53:39.165  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 16:53:39.166  1589  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:39.166  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 16:53:39.167  2080  8261 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 16:53:39.169  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:53:39.170  1589  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:53:39.170  1589  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 16:53:39.175  1045  1728 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:53:39.176  1589  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 16:53:39.176  1589  1635 D KeyguardModel: createShortcutInfo...
,08-30 16:53:39.181  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 16:53:39.181  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:39.182  1589  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:53:39.182  1589  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 16:53:39.185  2080  2080 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 16:53:39.187  1589  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 16:53:39.188  1589  1635 D KeyguardModel: createShortcutInfo...
,08-30 16:53:39.191  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-30 16:53:39.192  1881  1881 D SplitUIService: removed split : 
08-30 16:53:39.195  1589  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:39.195  1589  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 16:53:39.200  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 16:53:39.200  1589  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:53:39.201  1589  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:53:39.201  1589  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 16:53:39.217  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-30 16:53:39.217  1881  1881 I SplitUIService: split app #11
08-30 16:53:39.222  1589  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 16:53:39.222  1589  1635 D KeyguardModel: createShortcutInfo...
,08-30 16:53:39.227  7597  8027 D UEI.SmartControl: Internal timer expired: 2
08-30 16:53:39.227  7597  8027 D UEI.SmartControl: unbind internal service
08-30 16:53:39.227  4457  4457 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 16:53:39.227  4457  4457 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 16:53:39.227  4457  4457 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 16:53:39.227  4457  4457 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 16:53:39.227  4457  4457 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:53:39.227  4457  4457 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:53:39.227  4457  4457 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:53:39.227  4457  4457 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:53:39.227  4457  4457 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:53:39.227  4457  4457 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:53:39.227  4457  4457 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:53:39.227  4457  4457 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 16:53:39.235  1589  1589 D KeyguardModel: handleShortcutListChanged...
,08-30 16:53:39.235  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 16:53:39.243  1589  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 16:53:39.243  1589  1635 D KeyguardModel: createShortcutInfo...
08-30 16:53:39.251  1589  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 16:53:39.251  1589  1635 D KeyguardModel: createShortcutInfo...
,08-30 16:53:39.253  1589  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:53:39.253  1589  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 16:53:39.254  1589  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 16:53:39.254  1589  1635 D KeyguardModel: createShortcutInfo...
08-30 16:53:39.256  1589  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:53:39.256  1589  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 16:53:39.258  1589  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 16:53:39.258  1589  1635 D KeyguardModel: createShortcutInfo...
08-30 16:53:39.268  2080  2080 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 16:53:39.269  1589  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 16:53:39.269  1589  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 16:53:39.272  2080  2080 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 16:53:39.275  1823  1823 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 16:53:39.284  1589  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 16:53:39.284  1589  1635 D KeyguardModel: createShortcutInfo...
08-30 16:53:39.285  2246  2246 I ConfigService: onCreate
08-30 16:53:39.285  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 16:53:39.288  1823  1823 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 16:53:39.310  2246  2246 I ConfigService: onBind returning update interface
,08-30 16:53:39.318  1045  1045 I art     : Explicit concurrent mark sweep GC freed 79583(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 7.801ms total 285.519ms
08-30 16:53:39.319  1045  1126 I art     : WaitForGcToComplete blocked for 267.150ms for cause Explicit
08-30 16:53:39.319  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 16:53:39.319  2246  2246 I ConfigService: onBind returning config service
,08-30 16:53:39.324  2246  2246 I ConfigService: onDestroy
08-30 16:53:39.325  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-30 16:53:39.325  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 16:53:39.328  1045  1061 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:53:39.328  1045  1061 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:53:39.333  1823  8267 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 16:53:39.373  2080  2080 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 16:53:39.375  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:53:39.376  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 16:53:39.382  1045  1045 D administrator: Handling package changes for user 0
08-30 16:53:39.387  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 16:53:39.388  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 16:53:39.389  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 16:53:39.392  5891  8273 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 16:53:39.392  1045  1563 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 16:53:39.393  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 16:53:39.393  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 16:53:39.393  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 16:53:39.393  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 16:53:39.393  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 16:53:39.394  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:53:39.394  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 16:53:39.394  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 16:53:39.394  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 16:53:39.394  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:53:39.394  7686  7686 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 16:53:39.397  1823  8274 I PeopleContactsSync: CP2 sync disabled
08-30 16:53:39.398  1045  2011 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:53:39.399  1045  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26e40f05 u0 com.lge.launcher2/.Launcher t5} time:140882
08-30 16:53:39.403   341   436 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 16:53:39.403  3215  8276 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 16:53:39.411  7010  7010 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 16:53:39.412  2080  2080 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 16:53:39.412  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 16:53:39.419  1823  4706 I Icing   : doRemovePackageData com.test.thalitest
08-30 16:53:39.420  2080  2283 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 16:53:39.420  2080  2283 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 16:53:39.431  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 16:53:39.431  2080  2080 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 16:53:39.432  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 16:53:39.440  2184  8279 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 16:53:39.442  2080  2080 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 16:53:39.447  1045  1111 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 16:53:39.469  1045  2079 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8281 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 16:53:39.471  2622  2622 D [Concierge]Service: onStartCommand(). Type : 8
08-30 16:53:39.471  2622  2622 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 16:53:39.473  2622  2622 D [Concierge]Service: Update widget ID : 11
08-30 16:53:39.473  2080  2080 D [Concierge]WidgetView: change position of spinner
08-30 16:53:39.474  1823  8272 W GmsApplication: Using Auth Proxy for data requests.
08-30 16:53:39.474  2080  2080 I [Concierge]WidgetView: initWebView(). Time : 1472568819474
08-30 16:53:39.474  2622  2622 D [Concierge]Service: onStartCommand(). Type : 0
08-30 16:53:39.476  7597  8024 D serial_port: close(fd = 24)
08-30 16:53:39.479  7597  8024 I UEI.SmartControl: Serial port is closed.
,08-30 16:53:39.484  1823  8272 W GmsApplication: Using Auth Proxy for data requests.
08-30 16:53:39.487  2080  2080 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 325102881
08-30 16:53:39.488  2080  2080 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 16:53:39.488  2080  2080 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 16:53:39.490  2080  2080 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2070bf6d
08-30 16:53:39.491  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 16:53:39.492  2080  2080 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 16:53:39.492  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:53:39.499  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 16:53:39.500  2080  2080 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-30 16:53:39.500  2080  2080 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472568706904, New one : 1472568819474
08-30 16:53:39.500  2080  2080 D [Concierge]WidgetView: Unregister all receivers
08-30 16:53:39.500  2080  2080 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 16:53:39.501  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:53:39.503  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 16:53:39.504  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 16:53:39.505  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 16:53:39.507  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 16:53:39.508  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 16:53:39.510  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:53:39.510  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 16:53:39.524  2246  4184 I art     : Explicit concurrent mark sweep GC freed 7827(453KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.613ms total 21.132ms
08-30 16:53:39.545  1045  1045 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 16:53:39.545  1045  1045 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 16:53:39.545  1045  1045 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 16:53:39.546  1045  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 16:53:39.549  2080  2080 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 16:53:39.557  2080  2080 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 16:53:39.557  2080  2080 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 16:53:39.559  2080  2080 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 16:53:39.559  2080  2080 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:53:39.562  8281  8281 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:39.562  8281  8281 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:53:39.563  8281  8281 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 16:53:39.563  8281  8281 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:53:39.578  2080  2080 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1fb3f6de time:141061
,08-30 16:53:39.621  8281  8281 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 16:53:39.630  8281  8281 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 16:53:39.646  1045  1126 I art     : Explicit concurrent mark sweep GC freed 10761(585KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.030ms total 313.712ms
,08-30 16:53:39.654  8281  8281 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:53:39.676  8281  8281 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:39.676  8281  8281 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:39.683  1045  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:53:39.687  1045  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 16:53:39.690  2080  2080 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 16:53:39.720  8230  8230 D AndroidRuntime: Shutting down VM
,08-30 16:53:39.726  1045  1424 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=60.5, 0.0, 0.0  rx=57.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-604962802] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 16:53:39.726  1045  1424 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=60.5, 0.0, 0.0  rx=57.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-604962802] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 16:53:39.726  1045  1424 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 16:53:39.735  2080  2080 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-30 16:53:39.757  1045  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8303 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 16:53:39.760  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:53:39.768  8281  8281 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 16:53:39.775  1045  1448 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 16:53:39.778  2080  2928 I GBoardtInterface: onReloaded()
08-30 16:53:39.780  2080  2080 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 16:53:39.781  1045  1976 I ActivityManager: Killing 7715:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 16:53:39.781  3755  3770 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:53:39.806  1045  1505 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:53:39.807  2025  2025 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 16:53:39.807  2025  2025 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-30 16:53:39.809  1045  1919 W libprocessgroup: failed to open /acct/uid_10072/pid_7715/cgroup.procs: No such file or directory
08-30 16:53:39.810  2025  2025 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 16:53:39.811  1045  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 16:53:39.811  1045  1120 D Tethering: MasterInitialState.processMessage what=3
08-30 16:53:39.811  1045  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:53:39.813  1045  2012 I ActivityManager: Killing 7808:com.android.vending/u0a44 (adj 15): empty #17
08-30 16:53:39.815  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-30 16:53:39.828  1045  2042 W libprocessgroup: failed to open /acct/uid_10044/pid_7808/cgroup.procs: No such file or directory
,08-30 16:53:39.830  3755  3771 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:53:39.835  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-30 16:53:39.836  3755  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 16:53:39.836  3755  4448 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 16:53:39.839  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-30 16:53:39.840  3755  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 16:53:39.840  3755  4448 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 16:53:39.840  3755  4448 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 16:53:39.840  3755  4448 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 16:53:39.840  3755  3770 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-30 16:53:39.842  8137  8137 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 16:53:39.844  2080  2080 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 16:53:39.844  2080  2080 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 16:53:39.846  7448  7448 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 16:53:39.846  2080  2080 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 16:53:39.846  2080  2080 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 16:53:39.848  2080  2080 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 16:53:39.848  2080  2080 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 16:53:39.849  6805  6805 D PackageIntentReceiver: Not supported Hotkey customization function 
08-30 16:53:39.857  6805  6805 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 16:53:39.857  6805  6805 D HideNavigationAppsReceiver: replacing : false
,08-30 16:53:39.859  6805  6805 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-30 16:53:39.861  6805  6805 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-30 16:53:39.861  6805  6805 D ButtonCombinationReceiver: replacing : false
08-30 16:53:39.889  1045  1943 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8322 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:53:39.996  8322  8322 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 16:53:40.044  8322  8322 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:53:40.044  8322  8322 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:53:40.071  8322  8322 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-30 16:53:40.081  8322  8322 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 16:53:40.082  8322  8322 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 16:53:40.090  8322  8322 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:53:40.090  8322  8322 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.

```
