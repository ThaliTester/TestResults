#### Test 80598852b8a90be_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 18:15:05.516  6623  6623 D DocsApplication: Installing DEX configuration.
08-16 18:15:05.533  6623  6623 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-16 18:15:05.537  6623  6623 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1293d537 com.google.android.apps.docs}
08-16 18:15:05.553  6623  6623 D TAG     : onCreate()
08-16 18:15:05.582  6623  6623 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-16 18:15:06.152   335   402 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 18:15:06.156  3186  6652 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 18:15:06.372  1817  4768 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-16 18:15:06.514  1817  4768 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-16 18:15:06.566  1817  4768 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-16 18:15:06.585   313   313 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-16 18:15:06.585   313   313 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
08-16 18:15:06.585   313   313 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 18:15:06.585   313   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-16 18:15:06.628  6657  6657 D AndroidRuntime: 
08-16 18:15:06.628  6657  6657 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 18:15:06.631  6657  6657 D AndroidRuntime: CheckJNI is OFF
08-16 18:15:06.642   313   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
08-16 18:15:06.642   313   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-16 18:15:06.642   313   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-16 18:15:06.642   313   902 I rmt_storage: 
08-16 18:15:06.644   313   313 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-16 18:15:06.644   900   915 E Diag_Lib: [IMS_FATAL]| 3347 | 915 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-16 18:15:06.766  6657  6657 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 18:15:06.774  1033  2050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 18:15:06.783  1941  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 18:15:06.794  1033  2050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 18:15:06.794  1033  2050 D ActivityManager: setTaskToReturnTo : TaskRecord{3d7ca906 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 18:15:06.795  1033  2050 D ActivityManager: setTaskToReturnTo : TaskRecord{3d7ca906 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 18:15:06.795  1033  2050 D WindowStateEx: AppWindowTokenEx init.. 
08-16 18:15:06.796   341   367 E GBMv2   : DFP En is all cleared set to be enabled
08-16 18:15:06.827  1033  2050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6680 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 18:15:06.827  6657  6657 D AndroidRuntime: Shutting down VM
08-16 18:15:06.861  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 18:15:06.861  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1c6db563 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 18:15:06.862  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 18:15:06.862  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{358c9560 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 18:15:06.888  6680  6680 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 18:15:06.946  6680  6680 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 18:15:06.951  6680  6680 I LibraryLoader: Loading: webviewchromium
08-16 18:15:06.953  6680  6680 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1579-1581)
08-16 18:15:06.953  6680  6680 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:15:06.963  6680  6680 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21a33009}
08-16 18:15:06.966  6680  6680 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:15:06.967  6680  6680 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 18:15:06.975  6680  6680 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 18:15:06.976  6680  6680 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:15:06.984   319  1383 V AudioPolicyService: registerClient() client 0xb1021bc0, uid 10118
08-16 18:15:06.987  1033  1097 D BluetoothManagerService: Message: 20
08-16 18:15:06.987  1033  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20f88d60:true
08-16 18:15:06.993  6680  6680 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 18:15:06.994  6680  6680 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 18:15:06.994  6680  6680 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 18:15:07.024  6680  6680 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:15:07.024  6680  6680 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:15:07.024  6680  6680 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:15:07.024  6680  6680 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:15:07.024  6680  6680 I Adreno-EGL: Remote Branch: 
08-16 18:15:07.024  6680  6680 I Adreno-EGL: Local Patches: 
08-16 18:15:07.024  6680  6680 I Adreno-EGL: Reconstruct Branch: 
,08-16 18:15:07.041  6623  6623 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:07.042  6623  6623 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:07.115  6680  6713 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 18:15:07.117  6680  6680 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 18:15:07.128  6680  6680 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:15:07.131  6680  6680 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 18:15:07.133  6680  6680 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 18:15:07.135  6680  6680 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 18:15:07.135  6680  6680 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 18:15:07.144  6680  6680 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 18:15:07.149  6680  6680 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:15:07.149  6680  6680 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:15:07.170  6147  6147 I LockScreenSettings: New app installed broadcast received ..
,08-16 18:15:07.172  6147  6147 I LockScreenSettings: Number of installed packages  1
08-16 18:15:07.178  6680  6732 D OpenGLRenderer: Render dirty regions requested: true
08-16 18:15:07.178  6680  6732 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 18:15:07.191  6623  6623 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 18:15:07.195  6680  6732 D OpenGLRenderer: Enabling debug mode 0
08-16 18:15:07.203  6680  6680 D Atlas   : Validating map...
,08-16 18:15:07.207  1033  1966 D SplitWindow: check instance of lgWin Window{14cee9a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 18:15:07.212  1033  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-16 18:15:07.233  6680  6728 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:07.234  6680  6728 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:07.281  1033  1782 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6744 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:07.340  1033  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +480ms (total +544ms)
08-16 18:15:07.341  1033  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a37fbc7 u0 com.test.thalitest/.MainActivity t6} time:101969
08-16 18:15:07.346  6680  6680 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a152a6c time:101974
08-16 18:15:07.349  6744  6744 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-16 18:15:07.349  6744  6744 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-16 18:15:07.410  1033  2032 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6766 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 18:15:07.411  1033  2032 I ActivityManager: Killing 5886:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 18:15:07.447  6680  6680 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 18:15:07.447  6680  6680 I chromium: 
,08-16 18:15:07.481  6680  6680 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 18:15:07.524  1033  1956 W libprocessgroup: failed to open /acct/uid_10072/pid_5886/cgroup.procs: No such file or directory
,08-16 18:15:07.549  6680  6728 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 18:15:07.549  6680  6728 I chromium: 
,08-16 18:15:07.620  6766  6766 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-16 18:15:07.643  6766  6766 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 18:15:07.644  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-16 18:15:07.664  6680  6783 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-16 18:15:07.679  6680  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 18:15:07.679  6680  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 18:15:07.679  6680  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 18:15:07.679  6680  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 18:15:07.679  6680  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 18:15:07.679  6680  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23322370 added. We now have 1 listener(s)
08-16 18:15:07.684  1033  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:07.688  6680  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 18:15:07.690  6680  6783 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:07.694  6680  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:07.694  6494  6494 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-16 18:15:07.695  6680  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:15:07.703  1033  1049 I ActivityManager: Killing 5677:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 18:15:07.703  6680  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292d760f added. We now have 1 listener(s)
08-16 18:15:07.704  6680  6783 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:07.708  1033  1543 D WifiService: New client listening to asynchronous messages
,08-16 18:15:07.715  6680  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:15:07.715  6680  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 18:15:07.716  6680  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 18:15:07.716  6680  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 18:15:07.716  6680  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 18:15:07.726  5656  5656 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 18:15:07.726  5656  5656 W System.err: android.os.DeadObjectException
08-16 18:15:07.727  5656  5656 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:07.727  5656  5656 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:07.727  5656  5656 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 18:15:07.727  5656  5656 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-16 18:15:07.728  5656  5656 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 18:15:07.728  5656  5656 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 18:15:07.728  5656  5656 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-16 18:15:07.728  5656  5656 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:15:07.728  5656  5656 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:15:07.728  5656  5656 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:07.728  5656  5656 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:07.729  5656  5656 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:07.731  5656  5656 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:15:07.731  5656  5656 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 18:15:07.731  5656  5656 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 18:15:07.732  5656  5656 W System.err: android.os.DeadObjectException
08-16 18:15:07.732  5656  5656 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:07.732  5656  5656 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 18:15:07.732  5656  5656 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:15:07.732  5656  5656 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:07.732  5656  5656 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:07.732  5656  5656 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:07.732  5656  5656 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:15:07.732  5656  5656 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 18:15:07.732  5656  5656 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 18:15:07.733  5656  5656 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 18:15:07.815  6680  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:07.817  1033  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:07.818   276   276 E lowmemorykiller: Error opening /proc/5677/oom_score_adj; errno=2
,08-16 18:15:07.823  6680  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 18:15:07.832  1033  1886 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-16 18:15:07.832  1033  1886 W ActivityManager: android.os.DeadObjectException
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-16 18:15:07.832  1033  1886 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 18:15:07.837  1033  1996 W libprocessgroup: failed to open /acct/uid_1000/pid_5677/cgroup.procs: No such file or directory
08-16 18:15:07.839  5656  5656 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 18:15:07.840  5656  5656 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 18:15:07.857  6680  6783 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:07.859  6680  6783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:07.859  6680  6783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 18:15:07.859  6680  6783 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:07.863  6680  6783 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 18:15:07.863  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:07.868  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:07.909  6680  6680 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 18:15:07.921  1033  2025 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6792 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:07.921  5656  5656 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 18:15:08.016  6792  6792 D UEI.SmartControl: Quickset Services start...
,08-16 18:15:08.023  6792  6792 I UEI.SmartControl: Manufacture = LGE
08-16 18:15:08.023  6792  6792 D UEI.SmartControl: Id = LGNevo
08-16 18:15:08.025  6792  6792 D UEI.SmartControl: File observer start...
08-16 18:15:08.026  6792  6792 E UEI.SmartControl: IR Port is disabled: false
08-16 18:15:08.026  6792  6792 D UEI.SmartControl: Starting file observer...
08-16 18:15:08.026  6792  6792 D UEI.SmartControl: Extracting JNI libs...
08-16 18:15:08.026  6792  6792 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 18:15:08.127  6792  6792 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 18:15:08.128  6792  6792 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 18:15:08.128  6792  6792 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 18:15:08.161  6792  6792 I UEI.SmartControl: --- Selecting new region: 6
,08-16 18:15:08.164  6792  6792 I UEI.SmartControl: Model = LG-D855
08-16 18:15:08.165  6792  6792 D UEI.SmartControl: QS Service created
08-16 18:15:08.170   341   369 E GBMv2   : DFP En is all cleared set to be enabled
08-16 18:15:08.170   341   369 E GBMv2   : Set value is all cleared set the max
08-16 18:15:08.170   341   369 I GBMv2   : DFP Enabled. Ignore VFP set
08-16 18:15:08.180  6792  6792 I UEI.SmartControl: Service initServices...
,08-16 18:15:08.183  6792  6792 D UEI.SmartControl: QS start get config
08-16 18:15:08.221  6792  6792 D UEI.SmartControl: Loading JNI Libs...
,08-16 18:15:08.456  6792  6792 I UEI.SmartControl: Supports setup maps: true
08-16 18:15:08.459  6792  6792 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 18:15:08.459  6792  6792 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 18:15:08.459  6792  6792 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 18:15:08.460  6792  6792 I UEI.SmartControl: ### init IR Blaster...
,08-16 18:15:08.466  6792  6792 D serial_port: Configuring serial port
08-16 18:15:08.469  6792  6792 E UEI.SmartControl: UEIBLaster setting for 616
08-16 18:15:08.469  6792  6792 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 18:15:08.470  6792  6792 I UEI.SmartControl: configuring settings for MAXQ616
08-16 18:15:08.470  6792  6792 I UEI.SmartControl: Get version...
08-16 18:15:08.486  6792  6810 D UEI.SmartControl: serial port data available: 21
,08-16 18:15:08.515  6792  6792 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 18:15:08.515  6792  6792 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 18:15:08.516  6792  6792 I UEI.SmartControl: QS saving settings...
08-16 18:15:08.517  6792  6792 D UEI.SmartControl: IR Blaster version: 25672567
08-16 18:15:08.534  6792  6810 D UEI.SmartControl: serial port data available: 4
,08-16 18:15:08.541  6680  6791 W jxcore-log: Initializing JXcore engine
08-16 18:15:08.541  6680  6791 W jxcore-log: JXcore engine is ready
08-16 18:15:08.571  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 18:15:08.572  6792  6813 I UEI.SmartControl: Device manager: loading config....
,08-16 18:15:08.572  6792  6813 D UEI.SmartControl: ----------- loading internal config...
08-16 18:15:08.576  6792  6792 E UEI.SmartControl: Services init done
08-16 18:15:08.576  6792  6792 D UEI.SmartControl: QS Service init finished
08-16 18:15:08.580  6792  6792 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 18:15:08.580  6792  6792 D UEI.SmartControl: QS Service version code: 201091
08-16 18:15:08.581  6792  6792 D UEI.SmartControl: Service requested: Control
08-16 18:15:08.574  6791  6791 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8312]" dev="sockfs" ino=8312 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 18:15:08.574  6791  6791 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 18:15:08.574  6791  6791 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8510]" dev="sockfs" ino=8510 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 18:15:08.574  6791  6791 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 18:15:08.574  6791  6791 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32192]" dev="sockfs" ino=32192 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 18:15:08.584  6792  6813 E UEI.SmartControl: Loading SETTINGS...
08-16 18:15:08.586  6792  6792 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 18:15:08.593  1033  1782 I ActivityManager: Killing 5656:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 18:15:08.594  6680  6791 W jxcore-log: Starting JXcore engine
08-16 18:15:08.598  6792  6813 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 18:15:08.607  6792  6812 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 18:15:08.607  6792  6812 D UEI.SmartControl: -----service ready thread exits
08-16 18:15:08.691  6680  6791 W jxcore-log: Platform android
08-16 18:15:08.691  6680  6791 W jxcore-log: 
,08-16 18:15:08.691  6680  6791 W jxcore-log: Process ARCH arm
08-16 18:15:08.691  6680  6791 W jxcore-log: 
08-16 18:15:08.763  1033  1932 W libprocessgroup: failed to open /acct/uid_10112/pid_5656/cgroup.procs: No such file or directory
08-16 18:15:08.763  6792  6792 D UEI.SmartControl: Internal service binding...
,08-16 18:15:08.977  6680  6791 I jxcore-log: JXcore Cordova bridge is ready!
08-16 18:15:08.977  6680  6791 I jxcore-log: 
08-16 18:15:08.977  6680  6791 W jxcore-log: JXcore engine is started
,08-16 18:15:08.981  6680  6783 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 18:15:08.983  6680  6680 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-16 18:15:11.109  6623  6623 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-16 18:15:11.115  1033  1649 I ActivityManager: Killing 6339:com.android.calendar/u0a13 (adj 15): empty #17
08-16 18:15:11.230  1033  1886 W libprocessgroup: failed to open /acct/uid_10013/pid_6339/cgroup.procs: No such file or directory
,08-16 18:15:11.428  2780  2780 I MusicWidget: mDelayedStopHandler : unbind
,08-16 18:15:11.434  2129  2129 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-16 18:15:11.434  2129  2129 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-16 18:15:11.435  2129  2129 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-16 18:15:11.440  2129  2129 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-16 18:15:11.440  2129  2129 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-16 18:15:11.442  2129  2129 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-16 18:15:11.446  2129  2129 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-16 18:15:11.446  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-16 18:15:11.448  1033  1966 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1f636abecom.lge.music.MediaPlaybackService$5@34ce871f
08-16 18:15:11.449  2129  2129 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-16 18:15:11.450  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.452  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.453  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.454  2129  2129 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@545c3c5
08-16 18:15:11.454  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.455  2129  2129 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-16 18:15:11.455  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.455  2129  2129 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-16 18:15:11.456  2129  2129 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-16 18:15:11.456  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.456  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.457  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.458  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.458  2129  2129 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-16 18:15:11.459  2129  2129 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-16 18:15:11.461  2129  2129 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-16 18:15:11.461  2129  2129 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-16 18:15:11.461  2129  2129 V MediaPlayer[Native]: reset
08-16 18:15:11.467  2129  2129 V MediaPlayer[Native]: setListener
08-16 18:15:11.468  2129  2129 V MediaPlayer[Native]: disconnect
08-16 18:15:11.468  2129  2129 V MediaPlayer[Native]: destructor
08-16 18:15:11.468   319  2160 V AudioFlinger: releasing 18 from 2129 for -1
08-16 18:15:11.468   319  2160 V AudioFlinger:  decremented refcount to 0
08-16 18:15:11.468   319  2160 V AudioFlinger: purging stale effects
08-16 18:15:11.468  2129  2129 V MediaPlayer[Native]: disconnect
08-16 18:15:11.473  2129  2129 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-16 18:15:11.474  2129  2129 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-16 18:15:11.474  2129  2129 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-16 18:15:11.475  2129  2129 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-16 18:15:11.475  2129  2129 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-16 18:15:11.476  2129  2129 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-16 18:15:11.476  2129  2129 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 169159276
08-16 18:15:11.476  2129  2129 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 169159276
08-16 18:15:11.489  2129  2129 I SmartShareClient: [SmartShareManagerClient] terminate service: 2129/MediaPlaybackService/172395987
,08-16 18:15:11.493  2129  2129 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-16 18:15:11.493  2129  2129 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@39782835
08-16 18:15:11.496  2129  2129 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-16 18:15:11.496  2129  2129 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-16 18:15:11.497  2129  2129 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-16 18:15:11.497  2129  2129 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-16 18:15:11.499  1033  2025 I ActivityManager: Killing 6268:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 18:15:11.501  2129  2129 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
,08-16 18:15:11.574  1033  1887 W libprocessgroup: failed to open /acct/uid_10014/pid_6268/cgroup.procs: No such file or directory
,08-16 18:15:12.110  6623  6716 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 18:15:13.560  6792  6811 D serial_port: close(fd = 25)
,08-16 18:15:13.567  6792  6811 I UEI.SmartControl: Serial port is closed.
,08-16 18:15:13.572  6792  6814 D UEI.SmartControl: Internal timer expired: 1
,08-16 18:15:13.573  6792  6814 D UEI.SmartControl: unbind internal service
08-16 18:15:13.576  6792  6792 D UEI.SmartControl: Service.onUnbind: IControl
08-16 18:15:13.576  6792  6792 D UEI.SmartControl: Service.onDestroy
,08-16 18:15:13.576  6792  6792 D UEI.SmartControl: Lock is in USE false
08-16 18:15:13.576  6792  6792 D UEI.SmartControl: unbind internal service
08-16 18:15:13.576  6792  6792 I UEI.SmartControl: Serial port is closed.
08-16 18:15:13.576  6792  6792 I UEI.SmartControl: Serial port is closed.
08-16 18:15:13.576  6792  6792 D UEI.SmartControl: Blaster closed
08-16 18:15:13.577  6792  6792 D UEI.SmartControl: Shut down QS...
08-16 18:15:13.577  6792  6792 D UEI.SmartControl: Stopping QS lib
08-16 18:15:13.577  6792  6792 D UEI.SmartControl: QS lib stop result = true
08-16 18:15:13.577  6792  6792 D UEI.SmartControl: Stopped QS lib
08-16 18:15:13.577  6792  6792 D UEI.SmartControl: Stopped file observer...
08-16 18:15:13.577  6792  6792 D UEI.SmartControl: QS shutdown complete
,08-16 18:15:14.554  1817  6532 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 18:15:14.562   315  6830 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 18:15:14.563   315  6830 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 18:15:14.605   315  6830 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 18:15:14.831  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,08-16 18:15:14.836  1817  1817 I ConfigFetchService: stopping self
,08-16 18:15:14.841  2208  2208 I ConfigService: onDestroy
,08-16 18:15:19.157  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 18:15:19.157  6680  6791 I jxcore-log: 
,08-16 18:15:19.160  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 18:15:19.160  6680  6791 I jxcore-log: 
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:19.164  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.166  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.168  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 18:15:19.168  6680  6791 I jxcore-log: 
08-16 18:15:19.169  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 18:15:19.169  6680  6791 I jxcore-log: 
,08-16 18:15:19.496  6680  6791 D ExecuteNativeTests: Running unit tests
,08-16 18:15:19.577  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:15:19.577  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 added. We now have 2 listener(s)
08-16 18:15:19.578  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:19.579  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:19.580  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:15:19.580  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:19.580  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:19.580  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 added. We now have 2 listener(s)
08-16 18:15:19.580  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:19.581  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:19.584  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:19.586  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:19.588  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.588  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:19.590  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:19.593  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:19.593  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:19.593  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.594  6680  6791 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 18:15:19.595  6680  6791 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:15:19.595  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:19.595  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:19.595  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:19.596  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:19.598  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.598  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.598  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.599  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.599  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:19.599  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:19.599  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 removed from the list
08-16 18:15:19.599  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.599  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 removed from the list
08-16 18:15:19.601  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.601  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.601  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.601  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.601  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.603  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.603  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.603  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.604  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.606  6680  6791 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 18:15:19.606  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.606  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.606  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.606  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.606  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.606  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.606  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.606  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.606  6680  6791 E org.thaliproject.p2p.btconnectorlib.,DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.606  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.606  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.606  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.606  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.606  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.607  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.607  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-16 18:15:19.607  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.607  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:15:19.611  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:15:19.611  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.611  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.611  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.612  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.612  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.612  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.612  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.612  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.612  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15,:19.612  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.612  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.612  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.612  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.612  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.612  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.612  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.612  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.612  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.613  6680  6791 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:15:19.614  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:19.616  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.617  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.617  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:19.618  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.619  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.619  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:19.619  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:19.620  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:19.620  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.620  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:19.623  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:15:19.623  1033  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:19.630  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:19.634  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:15:19.636  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 18:15:19.637  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:15:19.637  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:19.639  6680  6791 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:15:19.639  6680  6791 I io.jxcore.node.ConnectionHelper: start: OK
08-16 18:15:19.642  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.642  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.642  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.643  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.643  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.643  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:19.643  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.643  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.643  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.643  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.643  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.643  6680  6791 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:15:19.645  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:19.648  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.649  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.649  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:19.650  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.651  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.651  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:19.651  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:19.651  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:19.651  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.651  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:19.654  1033  1091 I ActivityManager: Waited long enough for: ServiceRecord{8727afc u0 com.google.android.gms/.wearable.service.WearableService}
08-16 18:15:19.655  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:15:19.655  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:19.656  6680  6791 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:15:19.656  6680  6791 I io.jxcore.node.ConnectionHelper: start: OK
08-16 18:15:19.658  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.658  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.658  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.658  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.658  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.658  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:19.659  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.659  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.659  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.659  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.659  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.659  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.659  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.660  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.660  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.661  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.661  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.661  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.661  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.662  6680  6791 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:15:19.663  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:19.665  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.666  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:19.666  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:19.667  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.669  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.669  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:19.669  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:19.669  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:19.669  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.669  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:19.673  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:15:19.673  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:19.674  6680  6791 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:15:19.674  6680  6791 I io.jxcore.node.ConnectionHelper: start: OK
08-16 18:15:19.674  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.674  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.674  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.675  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.675  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.675  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.675  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.675  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.675  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:19.675  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.675  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.675  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.675  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.675  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.676  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.676  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.676  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.676  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.676  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.677  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.677  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.677  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.677  6680  6791 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 18:15:19.677  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.677  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.677  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.678  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.678  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.678  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.678  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.678  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.678  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.678  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.678  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.678  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.678  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.678  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.678  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.679  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.679  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.679  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.679  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.679  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.680  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 18:15:19.680  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.680  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.680  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.680  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.680  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.680  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.680  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.680  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.680  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.680  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.680  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.680  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.680  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.680  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.681  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.681  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.682  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.682  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.682  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.682  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.683  6680  6791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 18:15:19.683  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.683  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.683  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.683  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.684  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.684  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.684  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.684  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.684  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.684  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.684  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.684  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.684  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.684  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.684  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.684  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.685  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.685  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.685  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.685  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.685  6680  6791 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 18:15:19.685  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.685  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.685  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.686  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.686  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.686  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.686  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.686  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.686  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.686  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.686  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.686  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.686  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.686  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.686  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.686  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.687  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.687  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.687  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.687  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.687  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:19.688  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:19.688  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:19.688  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:19.688  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:19.688  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:19.688  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.688  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.688  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.689  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.689  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.689  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.689  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.689  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.689  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.689  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.689  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.689  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.689  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.689  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.689  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.689  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.690  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.690  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.690  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.690  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.690  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:19.691  6680  6791 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:15:19.691  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 18:15:19.695  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:19.695  6680  6791 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 18:15:19.695  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:15:19.696  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:15:19.698  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:15:19.699  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 18:15:19.699  6680  6791 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:19.699  6680  6791 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 18:15:19.700  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:19.700  6680  6791 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:19.700  6680  6791 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 18:15:19.700  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:19.700  6680  6791 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:19.700  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 18:15:19.702  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 18:15:19.703  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 18:15:19.703  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 18:15:19.704  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 18:15:19.704  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 18:15:19.704  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 18:15:19.704  6680  6791 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:19.705  6680  6791 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 18:15:19.705  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.705  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.705  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.706  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.706  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.706  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.706  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 18:15:19.707  6680  6831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-16 18:15:19.708  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.708  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.708  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.708  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.708  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.708  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.708  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.708  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.709  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.709  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.709  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.710  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.710  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.710  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.711  6680  6791 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 18:15:19.711  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.711  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.711  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.713  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.713  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.713  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.713  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.713  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.713  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.713  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.713  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.713  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.714  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.714  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.714  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.714  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.714  6680  6832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
08-16 18:15:19.714  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.714  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.714  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.714  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.715  6680  6832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
08-16 18:15:19.715  6680  6832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
08-16 18:15:19.715  6680  6791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 18:15:19.715  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.715  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.715  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.716  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.716  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.716  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.716  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.716  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.716  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.716  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.716  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.716  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.716  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.716  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.717  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.717  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.717  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.717  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.717  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.717  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.718  6680  6791 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 18:15:19.718  6680  6791 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 18:15:19.718  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:19.718  6680  6791 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 18:15:19.719  6680  6791 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:15:19.719  6680  6791 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 18:15:19.719  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:19.719  6680  6791 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 18:15:19.719  6680  6791 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:15:19.719  6680  6791 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:15:19.719  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:19.719  6680  6791 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 18:15:19.719  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.719  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.719  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.720  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.720  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.720  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.720  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.720  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.720  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.720  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.720  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.720  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.720  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.720  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.721  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.721  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.721  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.722  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.722  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.722  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.722  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.722  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.722  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.722  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.722  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.722  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.722  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.722  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.722  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.723  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.723  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.723  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.723  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.723  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.723  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.723  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.723  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.723  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.723  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.723  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.723  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.723  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.723  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.723  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.723  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.723  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.723  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.723  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.723  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.724  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.724  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.724  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.724  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.724  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.724  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.725  6680  6791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 18:15:19.726  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.726  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 18:15:19.726  6680  6791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 18:15:19.727  6680  6791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 18:15:19.727  6680  6680 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 18:15:19.727  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 18:15:19.727  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:19.729  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.729  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 18:15:19.729  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 18:15:19.729  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 18:15:19.729  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.729  6680  6791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 18:15:19.731  6680  6680 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 18:15:19.731  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.731  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.731  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:19.731  6680  6791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:19.731  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:19.731  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:19.732  6680  6833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:19.733  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:19.734  3897  3915 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 18:15:19.735  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:19.735  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:19.735  6680  6791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 18:15:19.735  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.735  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.735  6680  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 18:15:19.736  6680  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 18:15:19.736  6680  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 18:15:19.737  6680  6791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:19.737  6680  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:19.737  6680  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:19.738  6680  6680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 18:15:19.738  6680  6680 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:19.738  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.738  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.738  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.738  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.738  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.738  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.738  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.739  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.739  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.739  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.739  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.739  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.739  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.739  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.739  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.739  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.739  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.739  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.739  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.740  6680  6791 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 18:15:19.740  6680  6791 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:15:19.740  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:19.741  6680  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:19.742  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.742  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.742  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.742  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.742  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.742  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.742  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.742  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.742  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.742  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.742  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.742  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:19.742  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.742  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.743  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.743  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.743  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.743  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.744  1033  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:19.745  1033  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:19.745  1033  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:19.746  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.746  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.746  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.746  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.746  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.747  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.747  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.747  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.747  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.747  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.747  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.747  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.747  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.747  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.748  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.748  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.748  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.748  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.749  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:19.749  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:19.749  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:19.749  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:19.749  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.749  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.749  6680  6791 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e037e6 not in the list
08-16 18:15:19.749  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.749  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManage,r@2c641127 not in the list
08-16 18:15:19.749  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:19.749  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.749  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.749  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:19.749  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:19.750  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:19.750  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:19.750  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:19.750  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c641127 not in the list
08-16 18:15:19.751  6680  6791 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 18:15:19.751  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
08-16 18:15:19.751  6680  6791 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 18:15:19.751  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:19.752  6680  6791 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2,
08-16 18:15:19.752  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:19.753  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 18:15:19.753  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 18:15:19.753  6680  6791 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 18:15:19.753  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
08-16 18:15:19.754  6680  6791 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 18:15:19.754  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:15:19.754  6680  6791 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2,
08-16 18:15:19.754  6680  6791 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 18:15:19.754  6680  6791 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 18:15:19.754  6680  6791 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-16 18:15:19.754  6680  6791 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 18:15:19.754  6680  6791 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 18:15:19.755  6680  6791 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-16 18:15:19.755  6680  6791 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 18:15:19.755  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:19.755  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1686d56c added. We now have 2 listener(s)
,08-16 18:15:19.755  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:19.756  6680  6791 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 18:15:19.757  1033  1921 D WifiServiceImplEx: setWifiEnabled: true pid=6680, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 18:15:19.757  1033  1921 D WifiService: setWifiEnabled: true pid=6680, uid=10118
08-16 18:15:19.757  1033  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 18:15:19.758  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:19.758  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29f7f735 added. We now have 3 listener(s)
08-16 18:15:19.758  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:19.773  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:19.773  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13e497ca added. We now have 4 listener(s)
08-16 18:15:19.773  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:19.775  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:19.775  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed05d3b added. We now have 5 listener(s)
08-16 18:15:19.775  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:19.777  1033  1921 D WifiServiceImplEx: setWifiEnabled: false pid=6680, uid=10118, package= com.test.thalitest, App Lable : ThaliTest,
08-16 18:15:19.777  1033  1921 D WifiService: setWifiEnabled: false pid=6680, uid=10118
08-16 18:15:19.777  1033  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:15:19.793  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:19.793  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:19.793  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:19.794  1033  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:19.794  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:19.795  1033  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:19.795  1033  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:19.795  1033  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:19.795  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:19.795  1033  2032 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@fd62077 mBinding = false
08-16 18:15:19.796  1033  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 18:15:19.796  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:15:19.796  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:15:19.796  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:15:19.796  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:15:19.803  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:15:19.803  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-16 18:15:19.804  2770  2770 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:15:19.804  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.804  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.804  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:15:19.804  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:15:19.805  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:19.805  1033  2867 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.808   315   893 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:19.825  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:19.825  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:19.826  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:19.826  1033  1097 D BluetoothManagerService: Message: 2
08-16 18:15:19.826  1033  1097 D BluetoothManagerService: Sending off request.
08-16 18:15:19.831  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 18:15:19.831  1033  1050 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 18:15:19.831  1033  1544 D ConnectivityService: ignoring duplicate network state non-change
08-16 18:15:19.832  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 18:15:19.832  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-16 18:15:19.832  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.832  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.832  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 18:15:19.832  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.832  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 18:15:19.834  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:19.834  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:19.835  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.835  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.835  3897  3913 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-16 18:15:19.835  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:19.835  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-16 18:15:19.836  3897  3968 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 18:15:19.836  3897  3968 D BluetoothAdapterProperties: Setting state to 13
08-16 18:15:19.836  3897  3968 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:15:19.837  3897  3968 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 18:15:19.837  3897  3968 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 18:15:19.837  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:19.837  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 18:15:19.837  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 18:15:19.840  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:19.840  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:19.841  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:19.841  1033  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:15:19.842  1033  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.842  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.842  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@12c04fcf
08-16 18:15:19.842  1033  1536 D LGWifiP2pService: P2pDisablingState
08-16 18:15:19.843  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.843  1033  1536 D LGWifiP2pService: p2p socket connection lost
08-16 18:15:19.843  1033  1536 D LGWifiP2pService: P2pDisabledState
08-16 18:15:19.844  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:19.845  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 18:15:19.845  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.845  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.845  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:15:19.846  2770  2770 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-16 18:15:19.849  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:15:19.849  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:15:19.851  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:19.851  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.851  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.852  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:19.852  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:19.852  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:19.853  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:19.860  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:19.864  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-16 18:15:19.870  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 6848
08-16 18:15:19.872  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 18:15:19.872  1941  1941 D WfdsService: WifiP2pState is changed : false
,08-16 18:15:19.873  1941  2293 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 18:15:19.873  1941  2293 D WfdsService: Set the WFDS Monitor: false
08-16 18:15:19.873  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.873  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.873  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:19.873  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 18:15:19.873  1941  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 18:15:19.873  1941  2293 D WfdsService: STATE : WfdsDisabledState - enter
08-16 18:15:19.873  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-16 18:15:19.873  1941  2295 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 18:15:19.873  1941  2808 D CtrlSupplicant: Received on exit socket, terminate
08-16 18:15:19.874  1941  2808 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 18:15:19.874  1941  2808 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 18:15:19.874  1941  2808 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 18:15:19.874  1033  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.874  1033  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.875  1941  2293 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 18:15:19.876  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:19.876  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:19.879  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.880  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:19.881  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.883  6680  6831 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 18:15:19.883  6680  6831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
,08-16 18:15:19.893  1033  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 18:15:19.893  1033  1544 D DSQN    : disableDataServiceNotify
08-16 18:15:19.893  1033  1544 D DSQN    : stop dsqn bin
08-16 18:15:19.900   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:19.900   315  6853 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 18:15:19.901  1033  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 18:15:19.901  1033  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 18:15:19.901  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 18:15:19.901  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:19.901  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:19.901  1033  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:19.902  1033  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 18:15:19.902  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 18:15:19.902  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.902  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.902  1033  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 18:15:19.903  1033  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 18:15:19.903  1033  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 18:15:19.903  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:19.905  1033  1996 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6854 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:19.907  1033  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 18:15:19.907  1033  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:19.907  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:19.907  1033  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:19.907  1033  1538 D WifiNative-p2p0: TERMINATE: returned true
08-16 18:15:19.907  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:19.907  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:19.907  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:15:19.908  1033  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:19.908  1033  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:19.908  1033  1544 D NetworkManagementService: Removing idletimer
08-16 18:15:19.908  1033  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:19.908  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:19.908  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:19.908  1033  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.908  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:15:19.910  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 18:15:19.910  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 18:15:19.911  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 18:15:19.912  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 18:15:19.912  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:19.913  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-16 18:15:19.913  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.913  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.913  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:19.913  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:19.913  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 18:15:19.914  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:19.915  3897  3897 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:19.916  3897  3897 D BluetoothMapService: STATE_TURNING_OFF
08-16 18:15:19.916  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-16 18:15:19.916  389,7  3897 D BluetoothMapService: MAP Service closeService in
08-16 18:15:19.916  3897  3897 D BluetoothMapMasInstance: MAP Service shutdown
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 18:15:19.916  3897  4263 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 18:15:19.917  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:15:19.917  3897  3897 V BluetoothMapService: MAP Service closeService out
08-16 18:15:19.917  3897  3897 V BtOppService: Receiver DISABLED_ACTION 
08-16 18:15:19.917  3897  3897 I BtOppRfcommListener: stopping Accept Thread
08-16 18:15:19.917  3897  3897 V BtOppRfcommListener: close mBtServerSocket
08-16 18:15:19.917  3897  3897 V BtOppRfcommListener: waiting for thread to terminate
08-16 18:15:19.917  3897  4326 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:19.917  3897  4326 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 18:15:19.917  3897  3897 V BtOppRfcommListener: done waiting for thread to terminate
08-16 18:15:19.948  1033  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6871 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:19.949  3897  3897 V BtOppService: onDestroy
08-16 18:15:19.952  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:19.952  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.952  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.952  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:19.954  3897  3897 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 18:15:19.958   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 10.660ms
08-16 18:15:19.958  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:19.958  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:19.958  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.958  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:19.961  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:19.964  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:19.967   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.190ms
08-16 18:15:19.976   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.904ms
,08-16 18:15:19.984  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:19.985  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:19.985  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:19.990  1033  1966 I art     : Explicit concurrent mark sweep GC freed 29405(1508KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.846ms total 174.728ms
,08-16 18:15:19.993  3897  3973 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:15:19.993  3897  3968 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 18:15:19.993  3897  4265 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:19.994  3897  3968 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:15:19.994  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 18:15:19.994  3897  4083 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 18:15:19.994  3897  4327 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:19.994  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 18:15:19.994  3897  4328 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 18:15:19.995  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 18:15:19.995  3897  4083 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 18:15:19.996  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 18:15:19.996  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:19.996  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 18:15:19.996  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:15:19.997  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:15:19.997  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:15:19.997  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:15:19.997  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:15:19.997  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:15:19.998  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:19.998  6680  6680 V io.jxcore.node.Connectivi,tyMonitor:     - is Wi-Fi enabled: false
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:19.998  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:20.000  6871  6871 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:20.000  6871  6871 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 18:15:20.001  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:20.001  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:20.005  6871  6871 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:20.005  6871  6871 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-16 18:15:20.007  6871  6871 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 18:15:20.007  6871  6871 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 18:15:20.013  2770  2770 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 18:15:20.013  2770  2770 I wpa_supplicant: monitor socket send errors count : 1
08-16 18:15:20.013  2770  2770 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-16 18:15:20.013  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:20.014  1033  2800 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 18:15:20.014  1033  2800 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 18:15:20.014  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:20.014  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:20.014  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:20.017  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 18:15:20.022  1033  2867 D DhcpStateMachine: StoppedState
08-16 18:15:20.022  1033  2867 D DhcpStateMachine: StoppedState{ when=-170ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:20.023  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 18:15:20.023  1033  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 18:15:20.025  6854  6854 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:15:20.032  6854  6854 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:20.032  6854  6854 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:20.033  1033  1782 I ActivityManager: Killing 6467:com.lge.clock/u0a10 (adj 15): empty #17
08-16 18:15:20.051  2770  2770 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 18:15:20.052  1033  2800 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 18:15:20.052  1033  2800 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:15:20.052  1033  2800 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:15:20.052  1033  2800 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 18:15:20.052  2770  2770 W wpa_supplicant: USIM:  scard_deinit function
08-16 18:15:20.053  1033  1097 D Tethering: InitialState.processMessage what=4
08-16 18:15:20.053  1033  2800 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:20.053  1033  2800 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:20.053  1033  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=114668
08-16 18:15:20.053  1033  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=114669
08-16 18:15:20.054  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=114669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 18:15:20.054  1033  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=114670  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 18:15:20.073  1033  1649 W libprocessgroup: failed to open /acct/uid_10010/pid_6467/cgroup.procs: No such file or directory
,08-16 18:15:20.075  1033  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:20.076  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:20.076  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:20.129  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 18:15:20.137  3897  3897 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:20.138  3897  3897 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:20.138  3897  3897 V BluetoothPbapReceiver: ***********state = 13
08-16 18:15:20.141  3897  3897 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-16 18:15:20.141  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:20.144  3897  3897 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:20.144  3897  3897 V BluetoothPbapService: state: 13
08-16 18:15:20.144  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-16 18:15:20.146  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:20.146  3897  3897 V BluetoothPbapService: successfully stopped pbap service
08-16 18:15:20.146  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-16 18:15:20.147  3897  3897 V BluetoothPbapService: Pbap Service onDestroy
08-16 18:15:20.147  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-16 18:15:20.147  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-16 18:15:20.147  3897  3897 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 18:15:20.183  2770  2770 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 18:15:20.183  1033  2800 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 18:15:20.183  1033  2800 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 18:15:20.183  1033  2800 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 18:15:20.184  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 18:15:20.186  1033  2032 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6894 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:20.190  6871  6871 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:20.190  6871  6871 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:20.200  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:20.207  1033  1097 D BluetoothManagerService: Message: 20
08-16 18:15:20.207  1033  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@59a4e:true
08-16 18:15:20.216  1033  1097 D BluetoothManagerService: Message: 30
,08-16 18:15:20.219  1033  1097 D BluetoothManagerService: Message: 30
08-16 18:15:20.222  6871  6871 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 18:15:20.223  6871  6871 D BluetoothMap: Create BluetoothMap proxy object
08-16 18:15:20.223  1033  1097 D BluetoothManagerService: Message: 30
08-16 18:15:20.227  1033  1097 D BluetoothManagerService: Message: 30
,08-16 18:15:20.229  6871  6871 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 18:15:20.229  6871  6871 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 18:15:20.238  6680  6680 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:15:20.241  6871  6871 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 18:15:20.245  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-16 18:15:20.260  6871  6871 D DockEventReceiver: finishStartingService: stopping service
08-16 18:15:20.267  6871  6871 D BluetoothInputDevice: Proxy object connected
08-16 18:15:20.268  6871  6871 D HidProfile: Bluetooth service connected
,08-16 18:15:20.268  6871  6871 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:20.269  6871  6871 D PanProfile: Bluetooth service connected
08-16 18:15:20.270  6871  6871 D BluetoothMap: Proxy object connected
08-16 18:15:20.270  6871  6871 D MapProfile: Bluetooth service connected
08-16 18:15:20.270  6871  6871 D BluetoothMap: getConnectedDevices()
08-16 18:15:20.271  6871  6871 D BluetoothMap: Bluetooth is Not enabled
08-16 18:15:20.271  6871  6871 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 18:15:20.314  1033  2025 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6917 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 18:15:20.319  1033  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 18:15:20.319  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:20.319  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:20.319  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:15:20.322  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 18:15:20.323  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:20.323  1033  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 18:15:20.323  1033  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 18:15:20.323  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-16 18:15:20.323  1941  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 18:15:20.323  1941  2293 D WfdsService: Set the WFDS Monitor: false
08-16 18:15:20.323  1941  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 18:15:20.324  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:20.325  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 18:15:20.326  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:20.327  1033  2025 I ActivityManager: Killing 6318:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 18:15:20.327  2500  2500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:20.372  1033  1932 W libprocessgroup: failed to open /acct/uid_10004/pid_6318/cgroup.procs: No such file or directory
08-16 18:15:20.372  6894  6894 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 18:15:20.373  6894  6894 W LG Account v2.2: No ProfileInfo entries
08-16 18:15:20.373  6894  6894 I LG Account v2.2: isEnabled: false
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Country: EU
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Operator: OPEN
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Ranking support: false
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Comfort support: false
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Accessory: true
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Health device: true
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Extra Pedometer: false
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Blood glucose device: false
08-16 18:15:20.373  6894  6894 I Feature : [Lifetracker]Device Number: 3
08-16 18:15:20.382  6871  6871 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 18:15:20.389  6871  6871 D BluetoothPermissionRequest: onReceive
08-16 18:15:20.392  6871  6871 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 18:15:20.399  6917  6917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:20.401  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 18:15:20.404  1033  1887 I ActivityManager: Killing 6540:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-16 18:15:20.443  1033  1990 W libprocessgroup: failed to open /acct/uid_10008/pid_6540/cgroup.procs: No such file or directory
,08-16 18:15:20.444  3897  3897 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 18:15:20.444  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 18:15:20.445  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 18:15:20.447  6917  6917 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 18:15:20.449  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:20.449  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:15:20.450  3897  3897 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:15:20.450  3897  3897 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:20.451  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-16 18:15:20.451  3897  3897 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 18:15:20.454  3897  3897 V BluetoothFtpService: successfully stopped ftp service
08-16 18:15:20.454  3897  3897 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:20.454  3897  3897 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:20.454  3897  3897 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:20.454  3897  3897 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:20.454  3897  3897 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 18:15:20.454  3897  3897 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 18:15:20.456  3897  3897 V BluetoothFtpService: Ftp Service onDestroy
08-16 18:15:20.456  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-16 18:15:20.483  6917  6917 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 18:15:20.484  6917  6917 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 18:15:20.484  6917  6917 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 18:15:20.484  6917  6917 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 18:15:20.485  6917  6917 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 18:15:20.487  6917  6917 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-16 18:15:20.492  6917  6917 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 18:15:20.513  1033  1921 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6940 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:20.516  3897  3897 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:20.516  3897  3897 V BluetoothSapService: state: 13
08-16 18:15:20.516  3897  3897 V BluetoothSapService: Stopping SAP server process
08-16 18:15:20.517  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-16 18:15:20.517  3897  3897 V BluetoothSapService: Close listen Socket : 
08-16 18:15:20.517  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-16 18:15:20.517  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-16 18:15:20.518  3897  3897 V BluetoothSapService: Sap Service closeSapService out
08-16 18:15:20.519  3897  3897 V BluetoothSapService: Sap Service onDestroy
08-16 18:15:20.519  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-16 18:15:20.519  3897  3897 V BluetoothSapService: Close listen Socket : 
08-16 18:15:20.519  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-16 18:15:20.519  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-16 18:15:20.519  3897  3897 V BluetoothSapService: Sap Service closeSapService out
08-16 18:15:20.529  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:15:20.535  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:20.557  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:15:20.560  6917  6917 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 18:15:20.563  6917  6917 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 18:15:20.563  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:20.568  6854  6854 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 18:15:20.572  6854  6854 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:20.572  6854  6854 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:20.575  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:15:20.577  6940  6940 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 18:15:20.585  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:20.592  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:20.593  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:20.595  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:15:20.599  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:20.605  6854  6854 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:15:20.605  6854  6854 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 18:15:20.605  6854  6854 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:20.608  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:15:20.614  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:20.619  1033  2025 I ActivityManager: Killing 6039:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 18:15:20.651  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:15:20.652  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:20.654  1033  1932 W libprocessgroup: failed to open /acct/uid_10011/pid_6039/cgroup.procs: No such file or directory
08-16 18:15:20.662  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:15:20.718  1033  1575 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6960 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 18:15:20.862  6854  6854 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:20.870  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:20.886  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:20.911  6960  6982 W FormManager: Network not available. Please check & try again.
,08-16 18:15:20.915  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:20.915  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:15:20.915  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:15:20.915  6871  6871 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:15:20.916  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:15:20.926  6871  6871 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:15:20.927  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:15:20.927  6960  6983 V FormManager: Network unavailable.
08-16 18:15:20.927  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:15:20.927  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-16 18:15:20.929  6960  6983 V FormManager: Network unavailable.
08-16 18:15:20.930  6871  6871 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:15:20.931  6871  6871 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:15:20.936  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:20.936  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:20.938  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:15:20.940  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:20.949  4304  6986 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:15:20.953  6854  6854 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 18:15:20.953  6854  6854 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:20.953  6854  6854 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:20.956  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:20.961  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:20.964  4304  6987 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:20.965  4304  6987 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:15:20.977  6960  6989 W FormManager: Network not available. Please check & try again.
,08-16 18:15:20.985  6960  6990 V FormManager: Network unavailable.
08-16 18:15:20.987  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 18:15:20.987  6960  6990 V FormManager: Network unavailable.
08-16 18:15:20.988  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 18:15:20.989  6917  6917 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 18:15:20.993  1033  1050 I ActivityManager: Killing 6060:com.android.contacts/u0a19 (adj 15): empty #17
08-16 18:15:20.997  3897  3973 D bt_hci_bdroid: cleanup
,08-16 18:15:20.997  3897  4085 I bt_lpm  : LPM is already off!!!
08-16 18:15:20.997  3897  4235 I bt_userial_mct: exiting userial_read_thread
08-16 18:15:20.997  3897  4235 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 18:15:20.998  3897  3973 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 18:15:20.998  3897  4083 W bt-btif : ag scb idx 1 not allocated
08-16 18:15:20.998  3897  4083 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:20.998  3897  4085 I bt_vendor: hw_epilog_process
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:20.998  3897  4083 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:20.998  3897  3973 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 18:15:20.998  3897  4083 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 18:15:20.998  3897  3973 D bt_userial_mct: userial_close
08-16 18:15:20.998  3897  3973 E bt_userial_mct: pthread_join() FAILED result:3
08-16 18:15:20.998  3897  3973 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 18:15:21.028  6917  6917 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:21.028  6917  6917 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:21.036  6917  6917 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 18:15:21.037  6917  6917 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 18:15:21.037  6917  6917 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 18:15:21.037  6917  6917 V SoundPool: doLoad: loading sample sampleID=1
08-16 18:15:21.038  6917  6917 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 18:15:21.039  6917  7004 V SoundPool: Start decode
08-16 18:15:21.039  6917  7004 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 18:15:21.039   319  1383 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 18:15:21.040   319  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 18:15:21.040   319  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 18:15:21.040   319  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 18:15:21.040   319  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 18:15:21.040   319  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 18:15:21.040   319  1383 V MediaPlayerService: player type = 3
08-16 18:15:21.040   319  1383 V AwesomePlayer: AwesomePlayer create()
08-16 18:15:21.040   319  1383 V AwesomePlayer: reset_l() 
08-16 18:15:21.040   319  1383 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:21.040   319  1383 V AwesomePlayer: setAudioSink() 
08-16 18:15:21.040   319  1383 V AwesomePlayer: reset_l() 
08-16 18:15:21.040   319  1383 V AudioCache: notify(0xb57c9540, 8, 0, 0)
08-16 18:15:21.040   319  1383 V AudioCache: ignored
08-16 18:15:21.040   319  1383 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:21.040   319  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 18:15:21.041   319  1383 V AwesomePlayer: setDataSource_l dataSource
08-16 18:15:21.041   319  1383 V LGParserOSAL: SniffLGParser start
08-16 18:15:21.041   319  1383 V LGParserOSAL: MainType:5, SubType=0
08-16 18:15:21.041   319  1383 V LGParserOSAL: #### check Mime : application/ogg
08-16 18:15:21.041   319  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 18:15:21.041   319  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 18:15:21.074  1033  2050 W libprocessgroup: failed to open /acct/uid_10019/pid_6060/cgroup.procs: No such file or directory
,08-16 18:15:21.081  6792  6792 D UEI.SmartControl: QS Service created
08-16 18:15:21.081  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 18:15:21.085  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 18:15:21.086  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 18:15:21.099  6792  6792 I UEI.SmartControl: Service initServices...
08-16 18:15:21.099  6792  6792 D UEI.SmartControl: QS start get config
08-16 18:15:21.103  6917  6917 V LGMDMManager: Create singleton instance
,08-16 18:15:21.111   319  1383 V LGParserOSAL: supported mime: application/ogg
08-16 18:15:21.111   319  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 18:15:21.111   319  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 18:15:21.111   319  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 18:15:21.112   319  1383 V AwesomePlayer: AudioTrack Setting
08-16 18:15:21.112   319  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 18:15:21.112   319  1383 V AwesomePlayer: setAudioSource() 
08-16 18:15:21.112   319  1383 V MediaPlayerService: prepare
08-16 18:15:21.112   319  1383 V AwesomePlayer: prepareAsync_l() 
08-16 18:15:21.113   319  1383 V MediaPlayerService: wait for prepare
08-16 18:15:21.113   319  7007 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 18:15:21.113   319  7007 V AwesomePlayer: initAudioDecoder() 
08-16 18:15:21.113   319  7007 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 18:15:21.113   319  7007 V AudioSystem: isOffloadSupported()
08-16 18:15:21.113   319  7007 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 18:15:21.113   319  7007 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 18:15:21.113   319  7007 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 18:15:21.113   319  7007 V AwesomePlayer: getUseOffload() = 0 
,08-16 18:15:21.113   319  7007 V OMXCodec: OMXCodec::Create
08-16 18:15:21.113   319  7007 V OMXCodec: findMatchingCodecs()
08-16 18:15:21.113   319  7007 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 18:15:21.113   319  7007 V OMXCodec: matchingCodecs.size()=1
08-16 18:15:21.113   319  7007 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 18:15:21.115   319  7007 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 18:15:21.115   319  7007 V LGCodecAdapter: LG Codec Adapter start
08-16 18:15:21.115   319  7007 V OMXCodec: OMXCodec Createtor
08-16 18:15:21.115   319  7007 V OMXCodec: setComponentRole
08-16 18:15:21.115   319  7007 V OMXCodec: configureCodec protected=0
08-16 18:15:21.115   319  7007 V LGCodecAdapter: called getLGCodecSpecificData
08-16 18:15:21.115   319  7007 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 18:15:21.115   319  7007 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 18:15:21.115   319  7007 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 18:15:21.115   319  7007 V LGCodecOSAL: Not support LGCodec
08-16 18:15:21.115   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 18:15:21.115   319  7007 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 18:15:21.115   319  7007 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
,08-16 18:15:21.115   319  7007 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 18:15:21.115   319  7007 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 18:15:21.115   319  7007 V AudioSystem: isOffloadSupported()
08-16 18:15:21.115   319  7007 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 18:15:21.115   319  7007 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 18:15:21.115   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 18:15:21.115   319  7007 V OMXCodec: init()
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 18:15:21.116   319  7007 V OMXCodec: allocateBuffers
08-16 18:15:21.116   319  7007 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 18:15:21.116   319  7007 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-16 18:15:21.116   319  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-16 18:15:21.116   319  7007 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 18:15:21.122   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 18:15:21.122   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 18:15:21.122   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 18:15:21.122   319  7007 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 18:15:21.122   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 18:15:21.122   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 18:15:21.122   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 18:15:21.122   319  7007 V OMXCodec: init() mAsyncCompletion wait free! 
,08-16 18:15:21.122   319  7007 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 18:15:21.122   319  7007 V AudioCache: notify(0xb57c9540, 5, 0, 0)
08-16 18:15:21.122   319  7007 V AudioCache: ignored
08-16 18:15:21.122   319  7007 V AudioCache: notify(0xb57c9540, 1, 0, 0)
08-16 18:15:21.122   319  7007 V AudioCache: prepared
08-16 18:15:21.122   319  1383 V AudioCache: wait - success
08-16 18:15:21.122   319  1383 V MediaPlayerService: start
,08-16 18:15:21.122   319  1383 V AwesomePlayer: play_l() 
08-16 18:15:21.122   319  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 18:15:21.122   319  1383 V AwesomePlayer: createAudioPlayer_l
08-16 18:15:21.122   319  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 18:15:21.122   319  1383 V AwesomePlayer: startAudioPlayer_l() 
08-16 18:15:21.122   319  1383 D AudioPlayer: start of Playback, useOffload 0
08-16 18:15:21.122   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 18:15:21.122   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-16 18:15:21.125   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 18:15:21.126   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 18:15:21.132   319  7009 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f98d0 on output port
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 18:15:21.132   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 18:15:21.134   319  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 18:15:21.134   319  1383 V AudioCache: notify(0xb57c9540, 6, 0, 0)
08-16 18:15:21.134   319  1383 V AudioCache: ignored
08-16 18:15:21.135   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.135   319  1383 V MediaPlayerService: wait for playback complete
08-16 18:15:21.135   319  7010 V AudioCache: memcpy(0xac300000, 0xb14b4000, 4096)
,08-16 18:15:21.137   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: memcpy(0xac301000, 0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: memcpy(0xac302000, 0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: memcpy(0xac303000, 0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.137   319  7010 V AudioCache: memcpy(0xac304000, 0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: memcpy(0xac305000, 0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: memcpy(0xac306000, 0xb14b4000, 4096)
,08-16 18:15:21.138   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: memcpy(0xac307000, 0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.138   319  7010 V AudioCache: memcpy(0xac308000, 0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: memcpy(0xac309000, 0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: write(0xb14b4000, 4096)
,08-16 18:15:21.140   319  7010 V AudioCache: memcpy(0xac30a000, 0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: memcpy(0xac30b000, 0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.140   319  7010 V AudioCache: memcpy(0xac30c000, 0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: memcpy(0xac30d000, 0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: memcpy(0xac30e000, 0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: memcpy(0xac30f000, 0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.141   319  7010 V AudioCache: memcpy(0xac310000, 0xb14b4000, 4096)
08-16 18:15:21.145   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: memcpy(0xac311000, 0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: write(0xb14b4000, 4096),
08-16 18:15:21.146   319  7010 V AudioCache: memcpy(0xac312000, 0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: memcpy(0xac313000, 0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: memcpy(0xac314000, 0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: memcpy(0xac315000, 0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.146   319  7010 V AudioCache: memcpy(0xac316000, 0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: memcpy(0xac317000, 0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: memcpy(0xac318000, 0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: memcpy(0xac319000, 0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.148   319  7010 V AudioCache: memcpy(0xac31a000, 0xb14b4000, 4096)
08-16 18:15:21.148  3897  3973 D bt_hci_bdroid: set_power 0
08-16 18:15:21.148  3897  3973 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 18:15:21.148  3897  3973 I bt_vendor: bluetooth satus is on
08-16 18:15:21.148  3897  3973 I bt_vendor: bt-vendor : resetting BT status
08-16 18:15:21.148  3897  3973 I bt_vendor: Starting hciattach daemon
08-16 18:15:21.148  3897  3973 I bt_vendor: try to set false
08-16 18:15:21.149  3897  3973 I bt_vendor: Starting hciattach daemon
08-16 18:15:21.149  3897  3973 I bt_vendor: try to set false
08-16 18:15:21.149  3897  3973 I bt_vendor: cleanup
08-16 18:15:21.150  3897  4083 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 18:15:21.150  3897  3973 I GKI_LINUX: GKI_exit_task 0 done
08-16 18:15:21.150  3897  3973 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 18:15:21.151  3897  3968 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 18:15:21.153  3897  3897 D HeadsetService: Received stop request...Stopping profile...
08-16 18:15:21.154  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 18:15:21.154  3897  3897 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:15:21.154  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.155  3897  3995 D HeadsetStateMachine: Exit Disconnected: -1
08-16 18:15:21.155  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:21.155  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:21.156  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:21.157  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:21.157  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 18:15:21.158  3897  3897 D A2dpService: Received stop request...Stopping profile...
08-16 18:15:21.158  3897  3968 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 18:15:21.160  3897  3897 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 18:15:21.161  3897  4071 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:15:21.161   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.161   319  7010 V AudioCache: memcpy(0xac31b000, 0xb14b4000, 4096)
08-16 18:15:21.161   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.161   319  7010 V AudioCache: memcpy(0xac31c000, 0xb14b4000, 4096)
08-16 18:15:21.161   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.161   319  7010 V AudioCache: memcpy(0xac31d000, 0xb14b4000, 4096)
,08-16 18:15:21.162  3897  3897 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 18:15:21.162  3897  3897 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:15:21.162  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.162   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.162   319  7010 V AudioCache: memcpy(0xac31e000, 0xb14b4000, 4096)
08-16 18:15:21.163   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.163   319  7010 V AudioCache: memcpy(0xac31f000, 0xb14b4000, 4096)
08-16 18:15:21.164  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:21.164   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.164  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 18:15:21.164   319  7010 V AudioCache: memcpy(0xac320000, 0xb14b4000, 4096)
08-16 18:15:21.164  3897  3897 D HidService: Received stop request...Stopping profile...
08-16 18:15:21.164  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.165   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.165   319  7010 V AudioCache: memcpy(0xac321000, 0xb14b4000, 4096)
,08-16 18:15:21.165  6871  6871 D BluetoothInputDevice: Proxy object disconnected
08-16 18:15:21.165  6871  6871 D HidProfile: Bluetooth service disconnected
08-16 18:15:21.165   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.165   319  7010 V AudioCache: memcpy(0xac322000, 0xb14b4000, 4096)
08-16 18:15:21.165  3897  3897 D HeadsetStateMachine: Unbinding service...
08-16 18:15:21.166  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:15:21.166  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:15:21.166  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:15:21.166  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:15:21.166  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 18:15:21.166  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:15:21.166  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 18:15:21.166   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.166   319  7010 V AudioCache: memcpy(0xac323000, 0xb14b4000, 4096)
08-16 18:15:21.167  3897  3897 D HealthService: Received stop request...Stopping profile...
08-16 18:15:21.167  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.168  3897  3897 D PanService: Received stop request...Stopping profile...
08-16 18:15:21.168   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.168   319  7010 V AudioCache: memcpy(0xac324000, 0xb14b4000, 4096)
08-16 18:15:21.168  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.169  6871  6871 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:15:21.169  6871  6871 D PanProfile: Bluetooth service disconnected
08-16 18:15:21.169  3897  3897 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:15:21.169   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.169   319  7010 V AudioCache: memcpy(0xac325000, 0xb14b4000, 4096)
08-16 18:15:21.170  3897  3897 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 18:15:21.170  3897  3897 D BtGatt.GattService: stop()
08-16 18:15:21.170  3897  3897 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 18:15:21.170   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.170   319  7010 V AudioCache: memcpy(0xac326000, 0xb14b4000, 4096)
08-16 18:15:21.171  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.171   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.171   319  7010 V AudioCache: memcpy(0xac327000, 0xb14b4000, 4096)
08-16 18:15:21.171  3897  3897 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 18:15:21.171  3897  3897 D BluetoothMapService: stop()
08-16 18:15:21.172  3897  3897 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 18:15:21.172   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.172  3897  3897 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 18:15:21.172   319  7010 V AudioCache: memcpy(0xac328000, 0xb14b4000, 4096)
08-16 18:15:21.173  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b14620e
08-16 18:15:21.173  6871  6871 D BluetoothMap: Proxy object disconnected
08-16 18:15:21.173  6871  6871 D MapProfile: Bluetooth service disconnected
08-16 18:15:21.174   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.174   319  7010 V AudioCache: memcpy(0xac329000, 0xb14b4000, 4096)
08-16 18:15:21.174  3897  3897 I BluetoothA2dpServiceJni: cleanupNative
08-16 18:15:21.174  3897  4072 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:15:21.174  3897  3897 I GKI_LINUX: GKI_exit_task 2 done
,08-16 18:15:21.174  3897  3897 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:15:21.175  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:15:21.175  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:15:21.175  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:15:21.175  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:15:21.175  3897  3897 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:15:21.175   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.175   319  7010 V AudioCache: memcpy(0xac32a000, 0xb14b4000, 4096)
08-16 18:15:21.175  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:15:21.175  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 18:15:21.176   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.176   319  7010 V AudioCache: memcpy(0xac32b000, 0xb14b4000, 4096)
08-16 18:15:21.176   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.176   319  7010 V AudioCache: memcpy(0xac32c000, 0xb14b4000, 4096)
08-16 18:15:21.177  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-16 18:15:21.177  3897  3897 D BluetoothMapService: MAP Service closeService in
08-16 18:15:21.177  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:15:21.177  3897  3897 V BluetoothMapService: MAP Service closeService out
08-16 18:15:21.177  3897  3897 D BluetoothMapService: cleanup()
08-16 18:15:21.177  3897  3897 D BluetoothMapService: MAP Service closeService in
08-16 18:15:21.177  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:15:21.177  3897  3968 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:15:21.177  3897  3897 V BluetoothMapService: MAP Service closeService out
08-16 18:15:21.177  3897  3968 D BluetoothAdapterProperties: Setting state to 10
08-16 18:15:21.177  3897  3968 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:15:21.177   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.177   319  7010 V AudioCache: memcpy(0xac32d000, 0xb14b4000, 4096)
08-16 18:15:21.177  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:21.178  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 18:15:21.178  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 18:15:21.178  3897  3968 I BluetoothAdapterState: Entering OffState
08-16 18:15:21.178  6871  6888 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 18:15:21.178   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.178   319  7010 V AudioCache: memcpy(0xac32e000, 0xb14b4000, 4096)
08-16 18:15:21.178  6871  6886 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:15:21.178  6871  6887 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:15:21.179   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.179   319  7010 V AudioCache: memcpy(0xac32f000, 0xb14b4000, 4096)
08-16 18:15:21.179  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:21.179   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.179   319  7010 V AudioCache: memcpy(0xac330000, 0xb14b4000, 4096)
08-16 18:15:21.179  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:21.180  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:21.180   319  7010 V AudioCache: write(0xb14b4000, 4096)
08-16 18:15:21.180   319  7010 V AudioCache: memcpy(0xac331000, 0xb14b4000, 4096)
08-16 18:15:21.180  1033  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:21.180   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 18:15:21.180   319  7010 V OMXCodec:, [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:15:21.180   319  7010 V AwesomePlayer: postAudioEOS() 
08-16 18:15:21.180  6871  6888 D BluetoothPan: onBluetoothStateChange on: false
08-16 18:15:21.180   319  7010 V AudioCache: write(0xb14b4000, 280)
08-16 18:15:21.180   319  7010 V AudioCache: memcpy(0xac332000, 0xb14b4000, 280)
08-16 18:15:21.180  1033  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:15:21.181  1033  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 18:15:21.181  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 18:15:21.182   319  7007 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 18:15:21.182   319  7007 V AwesomePlayer: onStreamDone
08-16 18:15:21.182   319  7007 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 18:15:21.182   319  7007 V AudioCache: notify(0xb57c9540, 2, 0, 0)
08-16 18:15:21.182   319  7007 V AudioCache: playback complete
08-16 18:15:21.182   319  7007 V AwesomePlayer: pause_l() 
08-16 18:15:21.182   319  7007 V AudioCache: notify(0xb57c9540, 7, 0, 0)
08-16 18:15:21.182   319  7007 V AudioCache: ignored
08-16 18:15:21.182   319  7007 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:21.182   319  7007 D AudioPlayer: Pause Playback at 1068125
08-16 18:15:21.182   319  1383 V AudioCache: wait - success
08-16 18:15:21.182   319  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 18:15:21.182   319  1383 V AwesomePlayer: reset_l() 
08-16 18:15:21.182   319  1383 V AudioCache: notify(0xb57c9540, 8, 0, 0)
08-16 18:15:21.182   319  1383 V AudioCache: ignored
08-16 18:15:21.182   319  1383 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:21.182   319  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 18:15:21.182   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 18:15:21.182   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 18:15:21.182   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 18:15:21.182   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 18:15:21.183  1033  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 18:15:21.183  1033  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 18:15:21.183  1033  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@fd62077 mBinding = false
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 18:15:21.183  1033  1097 D BluetoothManagerService: Sending unbind request.
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f98d0 on port 1
08-16 18:15:21,.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:21.183   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 18:15:21.184   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 18:15:21.184   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 18:15:21.184  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 18:15:21.184   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 18:15:21.184   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 18:15:21.184   319  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 18:15:21.184   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 18:15:21.184   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 18:15:21.184   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 18:15:21.185  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:21.185  1941  2139 D LGBluetoothAPIService: Message: 2
08-16 18:15:21.185  1941  2139 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@a9f0a19 mBinding = false
08-16 18:15:21.185  1941  2139 D LGBluetoothAPIService: Sending unbind request.
08-16 18:15:21.187  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:15:21.187  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:21.188  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:21.190   319  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 18:15:21.190   319  1383 D AudioPlayer: AudioPlayer releasing audio source
08-16 18:15:21.190   319  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-16 18:15:21.191  6871  6871 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:15:21.191  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 18:15:21.191  6871  6871 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 18:15:21.193   319  1383 V AwesomePlayer: reset_l() 
08-16 18:15:21.193   319  1383 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:21.193   319  1383 V AwesomePlayer: ~AwesomePlayer call
08-16 18:15:21.194  3897  3973 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 18:15:21.194  3897  3897 I GKI_LINUX: GKI_exit_task 1 done
08-16 18:15:21.194   319  1383 V AwesomePlayer: reset_l() 
08-16 18:15:21.194   319  1383 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:21.194  3897  3897 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 18:15:21.195  6917  7004 V SoundPool: close(31)
08-16 18:15:21.195  6917  7004 V SoundPool: pointer = 0x9fe42000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 18:15:21.195  3897  3897 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 18:15:21.195  3897  3897 I art     : --- WEIRD: removing null entry 246
08-16 18:15:21.195  3897  3897 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 18:15:21.195  3897  3897 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 18:15:21.195  1602  1602 D BluetoothAdapter: 592452033: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:21.195  1602  1602 D BluetoothAdapter: 592452033: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:21.196  3897  3897 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 18:15:21.196  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 18:15:21.197  3897  3897 I art     : System.exit called, status: 0
08-16 18:15:21.197  3897  3897 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 18:15:21.201  6871  6871 D DockEventReceiver: finishStartingService: stopping service
08-16 18:15:21.213   319   319 V AudioFlinger: 3897 died, releasing its sessions
08-16 18:15:21.213   319   319 V AudioFlinger:  pid 1852 @ 0
08-16 18:15:21.213   319   319 V AudioFlinger:  pid 3502 @ 1
08-16 18:15:21.213   319   319 V AudioFlinger:  pid 3502 @ 2
08-16 18:15:21.213  6871  6871 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 18:15:21.217  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 18:15:21.218  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-16 18:15:21.312  1033  1575 I ActivityManager: Process com.android.bluetooth (pid 3897) has died
,08-16 18:15:21.313  1033  1575 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-16 18:15:21.322  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3911
08-16 18:15:21.323  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:21.342  6871  6871 D BluetoothPermissionRequest: onReceive
,08-16 18:15:21.347  6871  6871 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:15:21.347  6871  6871 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 18:15:21.351  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 18:15:21.408  1033  1049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7013 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 18:15:21.413  6792  6792 I UEI.SmartControl: Supports setup maps: true
08-16 18:15:21.416  6792  6792 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 18:15:21.416  6792  6792 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 18:15:21.416  6792  6792 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 18:15:21.416  6792  6792 I UEI.SmartControl: ### init IR Blaster...
08-16 18:15:21.419  6792  6792 D serial_port: Configuring serial port
08-16 18:15:21.419  6792  6792 E UEI.SmartControl: UEIBLaster setting for 616
08-16 18:15:21.419  6792  6792 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 18:15:21.420  6792  6792 I UEI.SmartControl: configuring settings for MAXQ616
08-16 18:15:21.420  6792  6792 I UEI.SmartControl: Get version...
08-16 18:15:21.434  6792  7022 D UEI.SmartControl: serial port data available: 21
,08-16 18:15:21.460  7013  7013 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 18:15:21.460  6792  6792 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 18:15:21.460  7013  7013 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:21.460  6792  6792 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 18:15:21.460  6792  6792 I UEI.SmartControl: QS saving settings...
08-16 18:15:21.460  7013  7013 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 18:15:21.461  7013  7013 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 18:15:21.462  6792  6792 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 18:15:21.472  7013  7013 D BluetoothAdapterApp: Loading JNI Library
08-16 18:15:21.478  6792  7022 D UEI.SmartControl: serial port data available: 4
,08-16 18:15:21.492  7013  7013 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1293d537 Instance Count = 1
,08-16 18:15:21.497  7013  7013 D BluetoothAdapterApp: onCreate
08-16 18:15:21.503  2129  2129 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19995
08-16 18:15:21.510  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 18:15:21.511  6792  7036 I UEI.SmartControl: Device manager: loading config....
08-16 18:15:21.511  6792  7036 D UEI.SmartControl: ----------- loading internal config...
08-16 18:15:21.513  7013  7013 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 18:15:21.513  7013  7013 D ProfileConfigQcom: Adding HeadsetService
08-16 18:15:21.513  6792  6792 E UEI.SmartControl: Services init done
08-16 18:15:21.513  6792  6792 D UEI.SmartControl: QS Service init finished
08-16 18:15:21.514  7013  7013 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 18:15:21.514  6792  7036 E UEI.SmartControl: Loading SETTINGS...
08-16 18:15:21.514  7013  7013 D ProfileConfigQcom: Adding A2dpService
08-16 18:15:21.515  7013  7013 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 18:15:21.515  7013  7013 D ProfileConfigQcom: Adding HidService
08-16 18:15:21.515  6792  6792 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 18:15:21.516  6792  6792 D UEI.SmartControl: QS Service version code: 201091
08-16 18:15:21.516  7013  7013 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 18:15:21.516  7013  7013 D ProfileConfigQcom: Adding HealthService
08-16 18:15:21.516  6792  6792 D UEI.SmartControl: Service requested: Control
08-16 18:15:21.517  6792  7036 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 18:15:21.517  7013  7013 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 18:15:21.519  7013  7013 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 18:15:21.520  7013  7013 D ProfileConfigQcom: Adding PanService
08-16 18:15:21.520  6917  6917 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 18:15:21.520  7013  7013 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 18:15:21.521  7013  7013 D ProfileConfigQcom: Adding GattService
08-16 18:15:21.521  7013  7013 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 18:15:21.522  6792  6807 I UEI.SmartControl: ------ IControl API: 11
,08-16 18:15:21.522  7013  7013 D ProfileConfigQcom: Adding BluetoothMapService
08-16 18:15:21.522  6792  6807 D UEI.SmartControl: File observer start...
08-16 18:15:21.522  6792  6792 D UEI.SmartControl: Internal service binding...
08-16 18:15:21.522  6792  6807 E UEI.SmartControl: IR Port is disabled: false
08-16 18:15:21.522  6792  6807 D UEI.SmartControl: Starting file observer...
08-16 18:15:21.523  6792  6807 I UEI.SmartControl: Registering callback...
08-16 18:15:21.523  7013  7013 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 18:15:21.523  6792  6808 I UEI.SmartControl: ------ IControl API: 19
08-16 18:15:21.526  6792  6808 I UEI.SmartControl: Registering Services Ready callback...
08-16 18:15:21.526  7013  7013 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 18:15:21.526  6792  6808 I UEI.SmartControl: Notify client services are ready...
08-16 18:15:21.527  6917  6937 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 18:15:21.527  6792  7035 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 18:15:21.527  6792  7035 D UEI.SmartControl: -----service ready thread exits
08-16 18:15:21.528  6917  6937 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 18:15:21.529  6917  7002 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 18:15:21.529  6917  7002 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 18:15:21.530  6917  6917 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 18:15:21.530  6917  6917 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 18:15:21.531  6792  6807 I UEI.SmartControl: ------ IControl API: 8
08-16 18:15:21.531  6917  6917 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 18:15:21.532  6917  6917 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 18:15:21.532  6917  6917 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 18:15:21.532  6917  6917 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 18:15:21.533  6917  6917 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 18:15:21.533  6917  6917 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 18:15:21.533  6871  6871 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 18:15:21.534  6917  6917 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-16 18:15:21.535  7013  7013 V LGMDMManagerInternal: Create singleton instance
08-16 18:15:21.536  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 18:15:21.537  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 18:15:21.537  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:15:21.537  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 18:15:21.538  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 18:15:21.538  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 18:15:21.539  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 18:15:21.540  6917  6917 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471364121539]
08-16 18:15:21.541  6917  6917 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 18:15:21.542  1033  1921 I ActivityManager: Killing 6585:com.lge.email/u0a23 (adj 15): empty #17
08-16 18:15:21.560  6917  7039 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 18:15:21.617  1033  1575 W libprocessgroup: failed to open /acct/uid_10023/pid_6585/cgroup.procs: No such file or directory
,08-16 18:15:21.624  7013  7013 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:21.628  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 18:15:21.629  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:15:21.629  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 18:15:21.630  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 18:15:21.630  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-16 18:15:21.630  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 18:15:21.631  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 18:15:21.633  7013  7013 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:21.633  7013  7013 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:21.633  7013  7013 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:21.635  7013  7013 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:21.635  7013  7013 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 18:15:21.649  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-16 18:15:21.649  6940  6940 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 18:15:21.657  1033  1887 I ActivityManager: Killing 6082:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 18:15:21.749  1033  2032 W libprocessgroup: failed to open /acct/uid_10027/pid_6082/cgroup.procs: No such file or directory
,08-16 18:15:21.885  1033  1426 V AlarmManager: RTC_WAKEUP set : Alarm{263e5347 type 0 when 1471364120156 com.android.vending} when 1471364120156
,08-16 18:15:21.946  4489  7044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:22.089  1033  1996 V SIM_STK : Menu title from STK is T-Mobile
,08-16 18:15:22.314  6109  6109 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-16 18:15:22.857  1033  1956 D WifiServiceImplEx: setWifiEnabled: true pid=6680, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 18:15:22.859  1033  1956 D WifiService: setWifiEnabled: true pid=6680, uid=10118
08-16 18:15:22.859  1033  1956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:15:22.890  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:22.891  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:22.891  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:22.892  1033  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 18:15:22.892  1033  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 18:15:22.895  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 18:15:22.895  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:15:22.895  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 18:15:22.895  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:15:22.895  1033  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 18:15:22.896  1033  1538 E WifiHW  : unknown target_country: EU , set to default
08-16 18:15:22.896  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 18:15:22.896  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 18:15:22.896  1033  1538 I WifiUtil: gEnableBmps=1
08-16 18:15:22.910  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:22.917  1033  1097 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:22.928  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:22.931  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:22.932  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:22.938  1033  1097 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:22.944  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:22.951  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:22.953  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:22.954  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 18:15:22.958  6494  6527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 18:15:22.973  5791  5791 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 18:15:22.981  5791  5791 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:15:22.998  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:23.020  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:23.088  1033  1050 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7084 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-16 18:15:23.090  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:23.090  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:15:23.197  7084  7084 I AppUp4:AppBoxCP: onCreate
,08-16 18:15:23.198  7084  7084 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-16 18:15:23.209  7084  7084 I AppUp4:DB:  setFingerPrint start
08-16 18:15:23.209  7084  7084 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-16 18:15:23.218  7084  7084 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 18:15:23.218  7084  7084 I AppUp4:DB:  SDK version = 21
08-16 18:15:23.219  7084  7084 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-16 18:15:23.221  7084  7084 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 18:15:23.222  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:15:23.222  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:23.225  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:15:23.225  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:15:23.233  7084  7084 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:15:23.296  7084  7084 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 18:15:23.296  7084  7084 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 18:15:23.304  7084  7084 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21a33009
08-16 18:15:23.304  7084  7084 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:15:23.304  7084  7084 D AppUp4:CustFacade: isPhone : true
08-16 18:15:23.305  7084  7084 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:15:23.305  7084  7084 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 18:15:23.306  7084  7084 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 18:15:23.306  7084  7103 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 18:15:23.307  7084  7103 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 18:15:23.307  7084  7103 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 18:15:23.309  1033  2025 I ActivityManager: Killing 6623:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 18:15:23.374  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:23.375  1033  1966 W libprocessgroup: failed to open /acct/uid_10061/pid_6623/cgroup.procs: No such file or directory
08-16 18:15:23.377  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:23.383  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:23.387  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:23.393  4304  7109 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 18:15:23.395  4304  7110 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:23.395  4304  7110 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:23.454  1033  1049 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7111 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 18:15:23.556  7111  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:23.557  7111  7111 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 18:15:23.559  7111  7111 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 18:15:23.559  7111  7111 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 18:15:23.660  7111  7111 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 18:15:23.676  7111  7111 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 18:15:23.739  7111  7111 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 18:15:23.760  1033  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 18:15:23.766  1033  1097 D Tethering: InitialState.processMessage what=4
08-16 18:15:23.767  1033  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:23.775   315   893 D SoftapController: Softap fwReload - Ok
,08-16 18:15:23.779  1033  1538 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (878ms)
08-16 18:15:23.781   315   893 D CommandListener: Setting iface cfg
,08-16 18:15:23.781   315   893 D CommandListener: Trying to bring down wlan0
08-16 18:15:23.782   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:23.784  1033  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 18:15:23.774  7137  7137 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:23.786  7111  7111 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:23.786  7111  7111 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:23.786  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:23.786  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:23.786  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 18:15:23.784  7137  7137 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:23.792  1033  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 18:15:23.793  1033  1538 D WifiMonitor: connecting to supplicant
08-16 18:15:23.803  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-16 18:15:23.804  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:23.806  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 18:15:23.808  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:23.810  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:23.818  7137  7137 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 18:15:23.867  7137  7137 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:23.867  7137  7137 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 18:15:23.918  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 18:15:23.949  7111  7111 I HubEmail: JNI_OnLoad()
08-16 18:15:23.949  7111  7111 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 18:15:23.949  7111  7111 I HubEmail: registerNatives()
08-16 18:15:23.949  7111  7111 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-16 18:15:23.949  7111  7111 I HubEmail: registerNativeMethods()
,08-16 18:15:23.949  7111  7111 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 18:15:23.950  7137  7137 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:23.952  3502  3502 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:15:23.952  3502  3502 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:23.953  3502  3502 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 18:15:23.954  7111  7111 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 18:15:23.966  7137  7137 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 18:15:23.972  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:15:23.972  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 18:15:23.973  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:15:23.973  1033  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:15:23.974  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:23.974  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:23.974  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:23.975  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:23.975  1033  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 18:15:23.975  1033  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 18:15:23.976  1033  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 18:15:23.976  1033  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 18:15:23.976  1033  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 18:15:23.978  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 18:15:23.978  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 18:15:23.978  1033  7151 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 18:15:23.994  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 18:15:23.994  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:15:23.994  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:15:23.994  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 18:15:23.994  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 18:15:23.994  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 18:15:23.994  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-16 18:15:23.996  1033  2050 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7152 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 18:15:23.999  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:23.999  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:23.999  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:15:23.999  1033  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 18:15:24.000  1033  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-16 18:15:24.000  1033  1538 D WifiConfigStore: Loading config and enabling all networks 
08-16 18:15:24.000  1033  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 18:15:24.000  1033  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 18:15:24.003  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.003  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.003  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.003  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.003  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:24.004  1941  1941 D WfdService: Waiting for WifiP2p enabling
,08-16 18:15:24.006  1033  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 18:15:24.005  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.007  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 18:15:24.008  1033  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 18:15:24.008  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:24.008  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:24.008  6960  7147 W FormManager: Network not available. Please check & try again.
08-16 18:15:24.008  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:24.008  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:24.009  7111  7150 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:24.009  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:24.010  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:24.010  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:24.010  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:24.010  6960  7148 V FormManager: Network unavailable.
08-16 18:15:24.015  1033  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 18:15:24.015  1033  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 18:15:24.016  1033  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-16 18:15:24.016  1033  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 18:15:24.016  6960  7148 V FormManager: Network unavailable.
08-16 18:15:24.017  1033  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 18:15:24.017  1033  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 18:15:24.017  1033  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 18:15:24.017  1033  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 18:15:24.017  1033  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 18:15:24.017  1033  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 18:15:24.018  1033  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 18:15:24.018  1033  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 18:15:24.018  1033  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 18:15:24.018  1033  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 18:15:24.019  1033  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 18:15:24.019  1033  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-16 18:15:24.019  1033  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 18:15:24.020  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:24.020  1033  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 18:15:24.020  1033  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 18:15:24.020  1033  1538 D WifiNative-HAL: Setting external_sim to 1
08-16 18:15:24.020  1033  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 18:15:24.020  1033  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 18:15:24.020  1033  1538 I WifiNative-HAL: startHal
08-16 18:15:24.020  1033  1538 D wifi    : setting scan oui 0xaf7260e0
08-16 18:15:24.021  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:24.021  1033  1538 I WifiNative-HAL: startHal
08-16 18:15:24.021  1033  1538 D wifi    : setting scan oui 0xaf7260e0
08-16 18:15:24.021  1033  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 18:15:24.021  1033  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 18:15:24.022  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-16 18:15:24.022  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 18:15:24.022  1941  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 18:15:24.022  1941  2293 D WfdsService: Set the WFDS Monitor: true
08-16 18:15:24.022  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 18:15:24.022  1941  2293 D WfdsMonitor: WfdsMonitorThread create
08-16 18:15:24.022  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 18:15:24.022  1941  2293 D WfdsMonitor: WFDS Monitor is created and started
08-16 18:15:24.022  1941  2293 D WfdsService: WiFi: Supplicant connection re-established
08-16 18:15:24.022  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:15:24.022  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-16 18:15:24.023  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:15:24.023  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 18:15:24.023  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 18:15:24.023  1941  7168 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 18:15:24.023  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 18:15:24.023  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:15:24.023  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:15:24.023  1941  7168 E CtrlSupplicant: Succeed to open control connection
08-16 18:15:24.023  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:15:24.023  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:15:24.023  1941  7168 E CtrlSupplicant: Succeed to open monitor connection
08-16 18:15:24.024  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:15:24.024  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:15:24.024  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 18:15:24.024  7137  7137 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 18:15:24.024  1941  7168 D WfdsMonitor: Supplicant connection established
08-16 18:15:24.024  1941  2293 D WfdsService: Connected to the supplicant for wfds
08-16 18:15:24.024  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 18:15:24.024  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:15:24.025  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:15:24.025  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:15:24.026  1033  1538 E WifiNative: : [118,640,858 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 18:15:24.026  1033  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 18:15:24.026  1033  1538 D WifiNative-wlan0: RECONNECT: returned true
08-16 18:15:24.026  1033  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 18:15:24.026  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:15:24.026  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:15:24.027  1033  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:15:24.027  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:15:24.028  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:24.029  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 18:15:24.029  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-16 18:15:24.029  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.029  1033  1556 I WifiNative-HAL: startHal
08-16 18:15:24.029  1033  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf7260e0
08-16 18:15:24.029  1033  1556 D wifi    : failed to get capabilities : -3
08-16 18:15:24.029  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:15:24.029  1033  1556 E WifiScanningService: could not get scan capabilities
08-16 18:15:24.029  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.030  1033  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 18:15:24.030  1033  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 18:15:24.030  1033  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 18:15:24.030  1033  1557 D RttService: DefaultState got{ when=-1m,s what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.031  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=118646  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:24.032   315   893 D CommandListener: Setting iface cfg
08-16 18:15:24.032   315   893 D CommandListener: Trying to bring up p2p0
,08-16 18:15:24.035  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.035  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:24.035  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=118651  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:24.036  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 18:15:24.036  1033  1536 D LGWifiP2pService: P2pEnablingState
08-16 18:15:24.036  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.036  1033  1536 D LGWifiP2pService: P2p socket connection successful
08-16 18:15:24.036  1033  1536 D LGWifiP2pService: P2pEnabledState
08-16 18:15:24.036  1033  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 18:15:24.036  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 18:15:24.036  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.036  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.037  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.037  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:15:24.037  1033  1956 I ActivityManager: Killing 6147:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 18:15:24.037  1033  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 18:15:24.038  1033  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 18:15:24.038  1033  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 18:15:24.038  7137  7137 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 18:15:24.038  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 18:15:24.038  1941  1941 D WfdsService: WifiP2pState is changed : true
08-16 18:15:24.038  1033  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 18:15:24.038  1941  2293 D WfdsService: Receive the WFDS_ENABLE Method
08-16 18:15:24.038  1941  2293 D WfdsService: Set the WFDS Monitor: true
08-16 18:15:24.039  1941  2293 D WfdsService: Connected to the supplicant for wfds
08-16 18:15:24.039  1941  2293 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 18:15:24.039  7137  7137 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 18:15:24.039  1941  2293 D WfdsService: selectPreferredScanChannel [36]
08-16 18:15:24.039  1941  2293 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 18:15:24.039  1033  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 18:15:24.039  1033  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 18:15:24.040  1033  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 18:15:24.040  7137  7137 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 18:15:24.040  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-16 18:15:24.040  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 18:15:24.041  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 18:15:24.041  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 18:15:24.042  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:15:24.043  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.043  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:15:24.043  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.043  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.043  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.043  7137  7137 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:15:24.044  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.044  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.044  1033  7151 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.044  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.044  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.044  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.045  1033  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 18:15:24.045  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:15:24.045  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:15:24.046  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:15:24.046  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 18:15:24.046  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 18:15:24.046  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:24.047  1941  7168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.047  1941  7168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.047  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.047  1033  7151 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.047  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.047  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.047  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 18:15:24.047  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:24.047  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:24.047  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:24.047  1033  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 18:15:24.047  1033  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 18:15:24.048  1033  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 18:15:24.048  1033  1538 D WifiNative-wlan0: doBoolean: SCAN
08-16 18:15:24.048  1033  1538 D WifiNative-wlan0: SCAN: returned false
08-16 18:15:24.048  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_ST,ATE_CHANGE_EVENT 24 0 rt=118664  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-16 18:15:24.082  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-16 18:15:24.084  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 18:15:24.084  1941  1941 D WfdsService: isConnected: false
08-16 18:15:24.084  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 18:15:24.084  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 18:15:24.085  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-16 18:15:24.085  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 18:15:24.085  1033  1536 D LGWifiP2pService: before postfix = G3
08-16 18:15:24.085  1033  1536 D WifiServerServiceExt: postfix byte check : 2
08-16 18:15:24.085  1033  1536 D LGWifiP2pService: after postfix = G3
08-16 18:15:24.085  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 18:15:24.085  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 18:15:24.085  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 18:15:24.086  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 18:15:24.086  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 18:15:24.086  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 18:15:24.086  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 18:15:24.086  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 18:15:24.086  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-16 18:15:24.087  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 18:15:24.087  1033  1049 W libprocessgroup: failed to open /acct/uid_10080/pid_6147/cgroup.procs: No such file or directory
08-16 18:15:24.089  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=118704  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:24.090  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.090  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:24.091  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.091  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 18:15:24.091  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 18:15:24.091  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.091  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:15:24.092  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.092  1033  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:24.092  1033  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:24.093  1033  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-16 18:15:24.093  1033  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:24.093  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 18:15:24.093  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 18:15:24.093  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 18:15:24.093  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 18:15:24.094  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 18:15:24.094  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 18:15:24.094  1033  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:24.095  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.095  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:15:24.095  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.095  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 18:15:24.096  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 18:15:24.096  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 18:15:24.096  1941  1941 D WfdsService: Update P2p Interface State: 3
08-16 18:15:24.104  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 18:15:24.104  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 18:15:24.104  1033  1536 D LGWifiP2pService: InactiveState
08-16 18:15:24.105  1033  1536 D LGWifiP2pService: InactiveState{ when=-59ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.105  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-59ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.105  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 18:15:24.105  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:15:24.106  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.106  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:15:24.106  1033  7151 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.106  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.106  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:24.106  1941  7168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:15:24.106  7137  7137 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-16 18:15:24.106  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.107  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.107  1941  7168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 18:15:24.107  1941  7168 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.108  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.108  1033  7151 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.108  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.108  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.108  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:24.108  1033  7151 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.108  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 18:15:24.108  1033  7151 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.108  1033  7151 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.108  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.109  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.109  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.109  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.110  1033  1033 E WifiServerServiceExt: No p2p device connected
08-16 18:15:24.111  1941  2293 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 18:15:24.161  7152  7152 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 18:15:24.161  7152  7152 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 18:15:24.165  7152  7152 D PhoneMonitor: Register our PhoneStateListener
08-16 18:15:24.191  7152  7152 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 18:15:24.196  7152  7152 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 18:15:24.220  7152  7152 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 18:15:24.221  7152  7152 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-16 18:15:24.223  7152  7152 D TelephonyAutoProfiling: [parse] Load xml
,08-16 18:15:24.230  7152  7152 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 18:15:24.230  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 18:15:24.231  7152  7152 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 18:15:24.232  7152  7152 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 18:15:24.243  7152  7152 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 18:15:24.267  1033  1996 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7172 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:24.270  1033  1996 I ActivityManager: Killing 6177:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-16 18:15:24.333  1033  2050 W libprocessgroup: failed to open /acct/uid_10097/pid_6177/cgroup.procs: No such file or directory
,08-16 18:15:24.529  1033  1996 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7194 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 18:15:24.541  1033  1996 I ActivityManager: Killing 6744:com.lge.eula/1000 (adj 15): empty #17
08-16 18:15:24.594  7137  7137 E wpa_supplicant: USIM:  scard_init function
,08-16 18:15:24.595  7137  7137 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 18:15:24.597  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 18:15:24.597  1033  7151 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 18:15:24.597  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 18:15:24.597  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-16 18:15:24.598  1033  7151 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 18:15:24.598  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:15:24.598  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 18:15:24.599  1033  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:15:24.599  1033  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:15:24.599  1033  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:15:24.600  1033  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:15:24.600  1033  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 18:15:24.603  1033  2050 W libprocessgroup: failed to open /acct/uid_1000/pid_6744/cgroup.procs: No such file or directory
08-16 18:15:24.612  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119228  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 18:15:24.614  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119229  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 18:15:24.620  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.620  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:24.623  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.626  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.626  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.626  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:15:24.626  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.626  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-16 18:15:24.706  7137  7137 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 18:15:24.710  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 18:15:24.710  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-16 18:15:24.710  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 18:15:24.711  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 18:15:24.711  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:24.711  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:24.712  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=119327  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:15:24.713  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=119328  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:15:24.713  1033  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119329
08-16 18:15:24.714  1033  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119329
08-16 18:15:24.714  1033  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119330
08-16 18:15:24.714  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119330
08-16 18:15:24.715  1033  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119330
08-16 18:15:24.716  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:15:24.719  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:24.719  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:24.720  7137  7137 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:24.720  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:15:24.720  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 18:15:24.720  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:24.720  1033  7151 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:24.720  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 18:15:24.720  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:15:24.720  1033  7151 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-16 18:15:24.722  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-16 18:15:24.722  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:24.733  1033  1966 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7226 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:24.734  1033  1966 I ActivityManager: Killing 6766:com.lge.bnr/1000 (adj 15): empty #17
,08-16 18:15:24.753   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 21.408ms
,08-16 18:15:24.771   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 16.865ms
,08-16 18:15:24.786   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 15.144ms
,08-16 18:15:24.793  1033  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:15:24.796  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.796  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.796  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:15:24.796  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.796  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:24.796  1033  1782 W libprocessgroup: failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
08-16 18:15:24.798  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:24.808  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119422  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:15:24.808  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:24.808  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.808  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 18:15:24.809  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.809  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 18:15:24.810  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=119426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:15:24.813  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=119428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:15:24.814  1033  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119430
08-16 18:15:24.816  1033  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119431
08-16 18:15:24.817  1033  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 18:15:24.818  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:24.818  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:24.818  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.818  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:24.818  1033  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:15:24.819  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.822  7226  7226 I art     : Almond Protected OAT
08-16 18:15:24.823  1033  1538 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 18:15:24.829  1033  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 18:15:24.829  1033  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 18:15:24.832  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.832  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.832  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 18:15:24.835  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.835  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:24.835  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 18:15:24.840  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.840  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:15:24.840  1033  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 18:15:24.840  1033  1544 D ConnectivityService: Got NetworkAgent Messenger
08-16 18:15:24.840  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 18:15:24.841  1033  1544 D ConnectivityService: NetworkAgent connected
08-16 18:15:24.841  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:15:24.841  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:15:24.841  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.841  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:15:24.841  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:15:24.843  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.843  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.843  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.843  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:24.843  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:24.844  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.846  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:15:24.846  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:15:24.846  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:15:24.846  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-16 18:15:24.846  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 18:15:24.851  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:15:24.852   315   893 D CommandListener: Setting iface cfg
08-16 18:15:24.854  1033  1538 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 18:15:24.854  1033  7244 D DhcpStateMachine: StoppedState
08-16 18:15:24.855  1033  7244 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.855  1033  7244 D DhcpStateMachine: WaitBeforeStartState
08-16 18:15:24.855  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119470  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:24.855  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:24.856  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:24.856  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:24.857  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:24.857  1033  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:24.858  1033  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:24.858  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:24.858  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:24.859  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 18:15:24.860  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:24.860  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119476  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:24.861  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.861  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:73629] from screen [on:0 period:-1809657667] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 18:15:24.861  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 18:15:24.863  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1809657665] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 18:15:24.863  1033  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 18:15:24.866  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:24.868  1033  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 18:15:24.869  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:24.869  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:24.870  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:24.870  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:24.871  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:24.872  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:24.872  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 18:15:24.872  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=101,0,0
08-16 18:15:24.872  7226  7226 D WeatherApplication: removeAccount
08-16 18:15:24.873  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=101,0,0
08-16 18:15:24.873  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 18:15:24.873  7226  7226 D WeatherApplication: Account.length = 0
08-16 18:15:24.874  7226  7226 E WeatherApplication: OPERATOR:OPEN
08-16 18:15:24.874  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-16 18:15:24.874  1033  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 18:15:24.874  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 18:15:24.874  1033  1538 D WifiNative-wlan0: SET ps 0: returned true
08-16 18:15:24.874  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 18:15:24.875  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 18:15:24.875  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 18:15:24.875  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ffd065d target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.875  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ffd065d target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.875  1033  7244 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.875  1033  7244 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 18:15:24.876  1033  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 18:15:24.876  1033  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:15:24.876  1033  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:15:24.877   315   893 D CommandListener: Setting iface cfg
08-16 18:15:24.877   315   893 D CommandListener: Trying to bring up wlan0
08-16 18:15:24.877  1033  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 18:15:24.878  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.878  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 18:15:24.878  7226  7226 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:24
08-16 18:15:24.879  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 18:15:24.879  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 18:15:24.879  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.879  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:24.879  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:24.879  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 18:15:24.879  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:15:24.880  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:15:24.880  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:15:24.880  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 18:15:24.880  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 18:15:24.881  1033  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 18:15:24.881  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:15:24.881  7226  7226 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:15:24.881  7226  7226 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:15:24.883  7226  7226 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:15:24.885  7226  7226 D WeatherAncestor: connectivity changed - connection : true
08-16 18:15:24.886  7226  7226 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 18:15:24.894  7226  7226 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 18:15:24.894  7226  7226 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:15:24.894  7226  7226 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 18:15:24.910  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:24.910  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 18:15:24.910  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:24.910  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 18:15:24.911  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 18:15:24.911  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:24.911  7226  7226 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:15:24.911  7226  7226 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:24
08-16 18:15:24.913  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:24.913  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:24.915  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 18:15:24.917  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:15:24.917  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:15:24.918  1033  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:15:24.918  1033  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:15:24.919  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:15:24.920  1033  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:15:24.920  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:15:24.921  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:15:24.921  1033  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 18:15:24.922  1033  1544 D ConnectivityService: ignoring duplicate network state non-change
08-16 18:15:24.969  1033  1886 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7246 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:24.975  1033  1886 I ActivityManager: Killing 2129:com.lge.music/u0a34 (adj 15): empty #17
,08-16 18:15:25.019   319  1383 V AudioFlinger: 2129 died, releasing its sessions
08-16 18:15:25.019   319  1383 V AudioFlinger:  pid 1852 @ 0
08-16 18:15:25.019   319  1383 V AudioFlinger:  pid 3502 @ 1
08-16 18:15:25.019   319  1383 V AudioFlinger:  pid 3502 @ 2
,08-16 18:15:25.078  1033  7244 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 18:15:25.081  1033  7244 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 18:15:25.081  1033  7244 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 18:15:25.084  7263  7263 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 18:15:25.084  7263  7263 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:25.097  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 18:15:25.099  1033  1544 D ConnectivityService: Adding iface wlan0 to network 101
08-16 18:15:25.105  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:25.105  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:15:25.108  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.108  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.109  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:15:25.112  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.114  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.114  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.114  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:15:25.114  1033  1996 W libprocessgroup: failed to open /acct/uid_10034/pid_2129/cgroup.procs: No such file or directory
08-16 18:15:25.119  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:15:25.119  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:15:25.121  7263  7263 I dhcpcd  : version 5.5.6 starting
08-16 18:15:25.124  7263  7263 E dhcpcd  : get_duid: m
08-16 18:15:25.124  7263  7263 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 18:15:25.124  7263  7263 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 18:15:25.125  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.134  1033  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 18:15:25.139  1033  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 18:15:25.140  1033  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 18:15:25.141  1033  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 18:15:25.142   315   893 E Netd    : netlink response contains error (File exists)
08-16 18:15:25.142  1033  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 18:15:25.143  1033  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 18:15:25.143  1033  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 18:15:25.143  1033  1544 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 18:15:25.144  1033  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 18:15:25.144  1033  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.145  1033  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.145  1033  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.145  1033  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:25.145  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.145  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 18:15:25.145  1033  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:25.145  1033  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:15:25.145  1033  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.145  1033  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 18:15:25.145  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.145  1033  1544 D ConnectivityService: currentScore = 0, newScore = 20
08-16 18:15:25.145  1033  1544 D ConnectivityService:    accepting network in place of null
08-16 18:15:25.145  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 18:15:25.145  1033  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.146  1033  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.146  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:25.147  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.147  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:15:25.149  1033  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspec,ified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 18:15:25.149  1033  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 18:15:25.149  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:25.149   315  7269 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 18:15:25.149  1033  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:25.149  1033  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 18:15:25.150  1033  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-16 18:15:25.152  1033  1544 D ConnectivityService: validation of new default Network = false
08-16 18:15:25.152  1033  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 18:15:25.152  1033  1544 D DSQN    : enableDataServiceNotify 
08-16 18:15:25.152  1033  1544 D DSQN    : start dsqn bin
08-16 18:15:25.161  1033  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.161  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.161  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:25.161  1033  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:25.162  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:15:25.154  7271  7271 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:25.154  7271  7271 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:25.178  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7265
,08-16 18:15:25.179  7271  7271 E DSQN    : DSQN ssw
08-16 18:15:25.184  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:25.184  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:15:25.184  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.185  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 18:15:25.185  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 18:15:25.185  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.185  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.185  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 18:15:25.185  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 18:15:25.193  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:25.193  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.193  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 18:15:25.194  7263  7263 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 18:15:25.195  7263  7263 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:15:25.195  7263  7263 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:15:25.195  7263  7263 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 18:15:25.195  7263  7263 D dhcpcd  : wlan0: sending REQUEST (xid 0x25177822), next in 4.46 seconds
08-16 18:15:25.197  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 18:15:25.197  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:15:25.197  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:15:25.197  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:15:25.200   315  7269 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 18:15:25.203  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 18:15:25.211  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:15:25.211  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:15:25.212  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:25.228  1817  7278 I CheckinService: active receiver: enabled
08-16 18:15:25.233  7263  7263 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 18:15:25.235   315  7269 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 18:15:25.242  7263  7263 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 18:15:25.242  7263  7263 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 18:15:25.242  7263  7263 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 18:15:25.242  7263  7263 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 18:15:25.242  7263  7263 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:15:25.242  7263  7263 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 18:15:25.243  7263  7263 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:15:25.243  7263  7263 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 18:15:25.248  1817  7278 I CheckinService: Preparing to send checkin request
08-16 18:15:25.248  1817  7278 I EventLogService: Accumulating logs since 1471364062654
08-16 18:15:25.249  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:25.250  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.251  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.268   315   892 D LGDataListener: argv[0]=dsqncommand
08-16 18:15:25.268   315   892 D LGDataListener: argv[1]=wlan0
08-16 18:15:25.268   315   892 D LGDataListener: argv[2]=1
08-16 18:15:25.268   315   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-16 18:15:25.268  1033  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 18:15:25.268  1033  1095 D DSQN    : start to monitor internet connection
08-16 18:15:25.272   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:15:25.272   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 18:15:25.272   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:15:25.280  7246  7283 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 18:15:25.282   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:15:25.282   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 18:15:25.282   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:15:25.283  7246  7283 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 18:15:25.293   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:15:25.293   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-16 18:15:25.293   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:15:25.293  7246  7293 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 18:15:25.296  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:15:25 GMT], X-Android-Received-Millis=[1471364125296], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471364125267]}
08-16 18:15:25.296  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 18:15:25.296  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 18:15:25.296  1033  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.296  1033  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.296  1033  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:25.297  1033  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:25.297  1033  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:15:25.297  1033  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 18:15:25.297  1033  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 18:15:25.297  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.297  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:25.297   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:15:25.297   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 18:15:25.297  1033  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:25.297   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:15:25.297  1033  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.298  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:15:25.298  7246  7293 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 18:15:25.298  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 18:15:25.298  1033  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.298  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:25.298  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:25.298  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:15:25.303  1817  7278 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 18:15:25.316  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:25.317  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.318  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:25.399  1033  1956 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7318 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 18:15:25.450  7246  7246 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 18:15:25.451  7318  7318 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 18:15:25.451  7318  7318 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 18:15:25.456  7246  7246 I LibraryLoader: Loading: webviewchromium
08-16 18:15:25.458  7246  7246 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 83-86)
08-16 18:15:25.458  7246  7246 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:15:25.462  7246  7246 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28608158}
,08-16 18:15:25.463  7246  7246 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:15:25.464  7246  7246 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 18:15:25.469  7318  7318 I MultiDex: VM with version 2.1.0 has multidex support
08-16 18:15:25.469  7318  7318 I MultiDex: install
08-16 18:15:25.469  7318  7318 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 18:15:25.476  7318  7318 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 18:15:25.476  7246  7246 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 18:15:25.478  7246  7246 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:15:25.487  7246  7246 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 18:15:25.488  7246  7246 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 18:15:25.488  7246  7246 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-16 18:15:25.490  1033  7244 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 18:15:25.491  1033  7244 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 18:15:25.491  1033  7244 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:15:25.492  1033  7244 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 18:15:25.492  1033  7244 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 18:15:25.492  1033  7244 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:15:25.492  1033  7244 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 18:15:25.492  1033  7244 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 18:15:25.493  1033  7244 D DhcpStateMachine: RunningState
08-16 18:15:25.504   319   319 V AudioPolicyService: registerClient() client 0xb1427180, uid 10093
,08-16 18:15:25.506  7246  7345 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 18:15:25.508  7246  7246 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:15:25.508  7246  7246 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:15:25.508  7246  7246 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:15:25.508  7246  7246 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:15:25.508  7246  7246 I Adreno-EGL: Remote Branch: 
08-16 18:15:25.508  7246  7246 I Adreno-EGL: Local Patches: 
08-16 18:15:25.508  7246  7246 I Adreno-EGL: Reconstruct Branch: 
08-16 18:15:25.586  7246  7246 I NSApplication: Starting up...
,08-16 18:15:25.631  1033  1921 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7359 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 18:15:25.632  1033  1921 I ActivityManager: Killing 6854:com.lge.sync/1000 (adj 15): empty #17
,08-16 18:15:25.688  1033  1932 W libprocessgroup: failed to open /acct/uid_1000/pid_6854/cgroup.procs: No such file or directory
,08-16 18:15:25.724  7359  7359 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:25.758  7376  7376 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 18:15:25.812  7376  7376 I dex2oat : dex2oat took 53.934ms (threads: 4)
,08-16 18:15:25.821  7318  7337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:15:25.821  7318  7337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:15:25.821  7318  7337 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:15:25.821  7318  7337 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:15:25.821  7318  7337 I Adreno-EGL: Remote Branch: 
08-16 18:15:25.821  7318  7337 I Adreno-EGL: Local Patches: 
08-16 18:15:25.821  7318  7337 I Adreno-EGL: Reconstruct Branch: 
08-16 18:15:25.895  1033  2050 D WifiServiceImplEx: setWifiEnabled: false pid=6680, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 18:15:25.897  1033  2050 D WifiService: setWifiEnabled: false pid=6680, uid=10118
08-16 18:15:25.898  1033  2050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:15:25.917  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:25.917  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:25.917  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:25.918  1033  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:25.920  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:25.921  1033  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:25.923  1033  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:25.924  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 18:15:25.924  1033  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 18:15:25.924  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:15:25.924  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:15:25.926  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:15:25.926  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 18:15:25.936  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:15:25.936  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:15:25.937  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.937  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.937  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:15:25.938  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:15:25.938  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 18:15:25.939  1033  1886 I art     : Explicit concurrent mark sweep GC freed 95598(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.800ms total 160.499ms
08-16 18:15:25.940  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:25.941  1033  7244 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.941   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:25.969  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 18:15:25.969  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 18:15:25.974  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:25.974  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:25.975  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:25.976  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-16 18:15:25.977  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.977  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.977  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:25.978  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 18:15:25.979  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.979  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.980  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@12c04fcf
08-16 18:15:25.980  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:25.980  1033  1536 D LGWifiP2pService: P2pDisablingState
08-16 18:15:25.980  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.980  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:25.980  1033  1536 D LGWifiP2pService: p2p socket connection lost
08-16 18:15:25.980  1033  1536 D LGWifiP2pService: P2pDisabledState
08-16 18:15:25.982  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:25.983  1033  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:15:25.983  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-16 18:15:25.984  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.984  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.984  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:15:25.984  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:15:25.985  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:15:25.985  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:15:25.985  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:25.986  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-16 18:15:25.989  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.990  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:25.990  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:25.990  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 18:15:25.990  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.990  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-16 18:15:25.991  1033  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:25.992  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 18:15:25.993  1941  1941 D WfdsService: WifiP2pState is changed : false
08-16 18:15:25.993  1941  2293 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 18:15:25.993  1941  2293 D WfdsService: Set the WFDS Monitor: false
08-16 18:15:25.998  1941  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 18:15:25.998  1941  2293 D WfdsService: STATE : WfdsDisabledState - enter
08-16 18:15:25.998  1941  7168 D CtrlSupplicant: Received on exit socket, terminate
08-16 18:15:25.999  1941  7168 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 18:15:25.999  1941  7168 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 18:15:25.999  1941  7168 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 18:15:25.999  1941  2295 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-16 18:15:26.000  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:26.000  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:26.001  1941  2293 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 18:15:26.001  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.019   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:26.021  1033  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 18:15:26.021  1033  1544 D DSQN    : disableDataServiceNotify
08-16 18:15:26.021  1033  1544 D DSQN    : stop dsqn bin
,08-16 18:15:26.022  1033  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 18:15:26.023  1033  1538 D WifiNative-p2p0: TERMINATE: returned true
08-16 18:15:26.023  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:26.023  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:26.023  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:15:26.023  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-16 18:15:26.024  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 18:15:26.024  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:26.024  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:26.024  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:26.024  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:26.025  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.026  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 18:15:26.027  1033  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 18:15:26.027  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:26.027  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:26.027  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 18:15:26.028  1033  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:26.028  1033  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,08-16 18:15:26.028  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.028  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:26.028  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:26.028  1033  7243 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 18:15:26.028  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.028  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:26.028  1033  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 18:15:26.028  1033  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 18:15:26.028  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:26.029  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 18:15:26.030  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.030  1033  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.030  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:26.031  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 18:15:26.031  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 18:15:26.031  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:15:26.031  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningN,etwork: false] info.getType():1
08-16 18:15:26.031  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:15:26.033  1033  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.033  1033  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:26.033  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:26.033  1033  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:26.033  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 18:15:26.033  1033  1544 D NetworkManagementService: Removing idletimer
08-16 18:15:26.033  1033  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:26.033  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.033  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:26.033  1033  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 18:15:26.033  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.033  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:26.034  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:26.034  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:15:26.034  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 18:15:26.035  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 18:15:26.035  1033  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 18:15:26.035  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 18:15:26.035  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:15:26.035  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:15:26.035  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-16 18:15:26.061  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:26.062  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.063  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:26.075  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:26.076  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.076  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.114  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 18:15:26.114  7137  7137 I wpa_supplicant: monitor socket send errors count : 1
08-16 18:15:26.114  7137  7137 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
,08-16 18:15:26.115  1033  7151 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 18:15:26.115  1033  7151 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 18:15:26.128  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 18:15:26.131  6494  6527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:15:26.137  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:15:26.137  7137  7137 W wpa_supplicant: USIM:  scard_deinit function
08-16 18:15:26.138  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-16 18:15:26.138  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:15:26.138  1033  7151 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:15:26.138  1033  7151 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 18:15:26.138  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:26.138  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:26.138  1033  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120754
08-16 18:15:26.139  1033  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120754
08-16 18:15:26.139  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=120754  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 18:15:26.139  1033  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=120755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 18:15:26.139  1033  1097 D Tethering: InitialState.processMessage what=4
08-16 18:15:26.140  1033  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:26.141  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:26.141  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 18:15:26.145  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.151  1033  7244 D DhcpStateMachine: StoppedState
08-16 18:15:26.151  1033  7244 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:26.153  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-16 18:15:26.153  1033  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 18:15:26.159  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:15:26.159  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.159  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:15:26.159  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:15:26.160  7084  7084 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:15:26.162  7084  7084 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21a33009
08-16 18:15:26.162  7084  7084 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:15:26.162  7084  7084 D AppUp4:CustFacade: isPhone : true
08-16 18:15:26.162  1033  1544 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-16 18:15:26.162  7084  7084 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:15:26.162  7084  7084 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:15:26.164  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.164  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 18:15:26.165  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:26.166  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:26.170  4304  7397 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:15:26.170  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:15:26.172  4304  7398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.172  4304  7398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:26.182  7111  7399 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:26.187  3502  3502 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:15:26.187  3502  3502 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:26.188  3502  3502 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 18:15:26.190  7152  7152 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:15:26.190  7152  7152 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:15:26.191  6960  7402 W FormManager: Network not available. Please check & try again.
08-16 18:15:26.196  6960  7404 V FormManager: Network unavailable.
,08-16 18:15:26.197  7226  7226 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:26
08-16 18:15:26.199  7226  7226 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:15:26.199  6960  7404 V FormManager: Network unavailable.
08-16 18:15:26.199  7226  7226 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:15:26.199  7226  7226 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:15:26.199  7226  7226 D WeatherAncestor: connectivity changed - connection : true
08-16 18:15:26.199  7226  7226 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@262342f
08-16 18:15:26.200  7226  7226 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:15:26.200  7226  7226 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:15:26.200  7226  7226 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:15:26.200  7226  7226 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:15:26.200  7226  7226 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:26
08-16 18:15:26.205  7318  7337 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:26.205  7318  7337 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:26.221  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 18:15:26.221  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:15:26.221  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:15:26.221  6871  6871 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:15:26.221  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:15:26.223  6871  6871 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:15:26.223  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:15:26.223  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:15:26.223  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:15:26.223  6871  6871 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:15:26.223  6871  6871 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:15:26.261  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 18:15:26.261  1033  7151 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 18:15:26.261  1033  7151 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 18:15:26.261  1033  7151 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 18:15:26.262  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-16 18:15:26.265  1033  1887 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7411 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 18:15:26.267  6960  7409 W FormManager: Network not available. Please check & try again.
08-16 18:15:26.284  6960  7410 V FormManager: Network unavailable.
,08-16 18:15:26.285  7318  7337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:15:26.285  7318  7337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:15:26.285  7318  7337 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:15:26.285  7318  7337 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:15:26.285  7318  7337 I Adreno-EGL: Remote Branch: 
08-16 18:15:26.285  7318  7337 I Adreno-EGL: Local Patches: 
08-16 18:15:26.285  7318  7337 I Adreno-EGL: Reconstruct Branch: 
08-16 18:15:26.292  6960  7410 V FormManager: Network unavailable.
08-16 18:15:26.313  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:26.316  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:26.319  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.320  1033  1932 I ActivityManager: Killing 6894:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 18:15:26.353  7318  7337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:15:26.353  7318  7337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:15:26.353  7318  7337 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:15:26.353  7318  7337 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:15:26.353  7318  7337 I Adreno-EGL: Remote Branch: 
08-16 18:15:26.353  7318  7337 I Adreno-EGL: Local Patches: 
08-16 18:15:26.353  7318  7337 I Adreno-EGL: Reconstruct Branch: 
,08-16 18:15:26.395  1033  1956 W libprocessgroup: failed to open /acct/uid_10037/pid_6894/cgroup.procs: No such file or directory
,08-16 18:15:26.403  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-16 18:15:26.404  1941  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-16 18:15:26.404  1941  2293 D WfdsService: Set the WFDS Monitor: false
08-16 18:15:26.404  1941  2293 D WfdsMonitor: WFDS Monitor is stopped
08-16 18:15:26.406  1033  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 18:15:26.407  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:26.407  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:26.407  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:15:26.409  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:26.411  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-16 18:15:26.414  2500  2500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:26.417  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 18:15:26.417  1033  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 18:15:26.417  1033  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 18:15:26.434  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.434  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:26.435  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.435  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:26.442  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:26.450  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:26.456  6960  7431 W FormManager: Network not available. Please check & try again.
,08-16 18:15:26.457  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.469  6960  7432 V FormManager: Network unavailable.
,08-16 18:15:26.474  6960  7432 V FormManager: Network unavailable.
08-16 18:15:26.474   315  7434 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 18:15:26.475  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:26.475  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:26.475  1033  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 18:15:26.476  1817  7278 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-16 18:15:26.479  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:26.482  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:15:26.485  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:26.488  1817  7278 I CheckinService: active receiver: disabled
08-16 18:15:26.490  4304  7435 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:15:26.494  4304  7436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:26.494  4304  7436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:15:26.498  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.504  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.509  6792  7038 D UEI.SmartControl: Internal timer expired: 2
08-16 18:15:26.509  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.510  6792  7038 D UEI.SmartControl: unbind internal service
08-16 18:15:26.510  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:26.511  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:15:26.547  1033  1887 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7437 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 18:15:26.579  6792  7031 D serial_port: close(fd = 24)
,08-16 18:15:26.584  6792  7031 I UEI.SmartControl: Serial port is closed.
08-16 18:15:26.652  7437  7437 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 18:15:26.652  7437  7437 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 18:15:26.665  7437  7437 V [BNRBootReceiver]: Boot Receiver Return
,08-16 18:15:26.667  7437  7437 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 18:15:26.672  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:26.688  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.700  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.712  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.712  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:26.715  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:15:26.723  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 18:15:26.730  6871  6871 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 18:15:26.736  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:26.750  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.764  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.775  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.775  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:26.776  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:26.780  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:26.792  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.805  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.818  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.819  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:26.820  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:26.830  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:26.845  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.857  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:15:26.869  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.869  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:26.870  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:26.877  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:26.890  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.900  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.916  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.916  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:26.917  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:26.929  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:26.937  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:26.948  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:26.960  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:26.960  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:26.961  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:26.974  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:27.004  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.015  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.029  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.030  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:27.035  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:27.045  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:27.064  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.079  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.093  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.094  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:27.097  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:27.108  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:27.116  7411  7411 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 18:15:27.135  1033  1543 D WifiService: New client listening to asynchronous messages
,08-16 18:15:27.136  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:27.143  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.158  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.178  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.179  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:27.182  6917  6917 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 18:15:27.185  6917  6917 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:15:27.186  6917  6917 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 18:15:27.198  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:27.206  7411  7411 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 18:15:27.209  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:27.218  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.228  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.238  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.239  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:27.239  6917  6917 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 18:15:27.241  6917  6917 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:15:27.241  6917  6917 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 18:15:27.245  1033  1049 I ActivityManager: Killing 6940:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 18:15:27.295  1033  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6940/cgroup.procs: No such file or directory
,08-16 18:15:27.306  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 18:15:27.327  2208  2208 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 18:15:27.327  2208  2208 D c       : Getting all permits...
,08-16 18:15:27.327  2208  2208 D a       : Opening database...
08-16 18:15:27.335  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-16 18:15:27.337  2208  2208 D a       : Closing database...
08-16 18:15:27.358  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:27.367  7411  7411 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:15:27.375  7411  7411 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:27.375  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:27.384  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.406  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.426  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.427  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:27.432  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:15:27.444  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:27.450  7411  7411 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:15:27.450  7411  7411 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:27.451  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:27.459  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.469  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:15:27.476  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.477  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:27.479  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:15:27.484  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:27.488  7411  7411 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 18:15:27.488  7411  7411 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:27.488  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:27.494  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:27.502  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.512  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:27.513  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:27.515  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:15:27.527  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:27.531  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:27.544  6960  7463 W FormManager: Network not available. Please check & try again.
08-16 18:15:27.544  6960  7464 V FormManager: Network unavailable.
,08-16 18:15:27.549  6960  7464 V FormManager: Network unavailable.
,08-16 18:15:27.551  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.574  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:27.574  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 18:15:27.577  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:27.580  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:27.588  7411  7411 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 18:15:27.589  7411  7411 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:15:27.589  7411  7411 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:27.590  4304  7465 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 18:15:27.593  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:27.596  4304  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:27.597  4304  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:27.602  6960  7468 W FormManager: Network not available. Please check & try again.
,08-16 18:15:27.605  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:27.611  6960  7469 V FormManager: Network unavailable.
08-16 18:15:27.613  6960  7469 V FormManager: Network unavailable.
,08-16 18:15:27.626  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 18:15:27.873  1033  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1809654657] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 18:15:27.877  1033  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1809654652] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 18:15:28.151  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:28.161  1033  1097 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:28.166  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:28.166  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:28.172  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:28.177  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 18:15:28.178  6494  6527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:15:28.190  5791  5791 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 18:15:28.208  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:28.248  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:15:28.254  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:15:28.255  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:28.255  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:15:28.255  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:15:28.257  7084  7084 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 18:15:28.263  7084  7084 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21a33009
08-16 18:15:28.263  7084  7084 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:15:28.263  7084  7084 D AppUp4:CustFacade: isPhone : true
08-16 18:15:28.265  7084  7084 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:15:28.265  7084  7084 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:15:28.270  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:28.270  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:28.272  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:28.274  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:15:28.285  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:15:28.321  7111  7481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:28.331  6960  7488 W FormManager: Network not available. Please check & try again.
08-16 18:15:28.333  4304  7485 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:15:28.337  3502  3502 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:15:28.337  3502  3502 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:28.337  3502  3502 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 18:15:28.337  6960  7489 V FormManager: Network unavailable.
,08-16 18:15:28.337  3502  3502 D PhoneState: setPdpRejectCasuse : false
08-16 18:15:28.340  7152  7152 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:15:28.340  7152  7152 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:15:28.344  4304  7492 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:28.346  4304  7492 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:28.350  6960  7489 V FormManager: Network unavailable.
,08-16 18:15:28.357  7226  7226 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:28
,08-16 18:15:28.358  7226  7226 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 18:15:28.358  7226  7226 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:15:28.359  7226  7226 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 18:15:28.359  7226  7226 D WeatherAncestor: connectivity changed - connection : true
,08-16 18:15:28.359  7226  7226 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@262342f
08-16 18:15:28.360  7226  7226 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:15:28.360  7226  7226 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:15:28.360  7226  7226 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:15:28.360  7226  7226 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false,
08-16 18:15:28.360  7226  7226 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:28
08-16 18:15:28.918  1033  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:28.919  1033  1956 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 18:15:28.949  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:28.950  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:28.950  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-16 18:15:28.953  1033  1097 D BluetoothManagerService: Message: 1
08-16 18:15:28.953  1033  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 18:15:28.982  1033  1097 D BluetoothManagerService: Message: 20
08-16 18:15:28.982  1033  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27590a92:true
08-16 18:15:28.984  7013  7013 D BluetoothAdapterState: make
08-16 18:15:28.989  7013  7013 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 18:15:28.989  7013  7013 I bluedroid-qcom: init
,08-16 18:15:28.992  7013  7501 I BluetoothAdapterState: Entering OffState
08-16 18:15:28.993  7013  7013 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 18:15:28.993  7013  7013 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 18:15:28.993  7013  7013 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 18:15:28.993  7013  7013 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 18:15:28.993  7013  7013 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 18:15:28.995  7013  7013 I bluedroid-qcom: get_profile_interface socket
08-16 18:15:28.995  7013  7013 I bluedroid-qcom: get_profile_interface map_client
08-16 18:15:28.997  7013  7505 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 18:15:28.999  7013  7505 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 18:15:28.984  7504  7504 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 18:15:28.994  7504  7504 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:29.014  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:15:29.015  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 18:15:29.018  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 18:15:29.019  1033  1097 D BluetoothManagerService: Message: 40
08-16 18:15:29.019  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 18:15:29.020  7013  7030 I bluedroid-qcom: config_hci_snoop_log
08-16 18:15:29.021  1033  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 18:15:29.021  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 18:15:29.023  7504  7504 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 18:15:29.023  7504  7504 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 18:15:29.023  7504  7504 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 18:15:29.026  7504  7504 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 18:15:29.031  7504  7504 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 18:15:29.031  7504  7504 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 18:15:29.035  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.037  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.046  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:29.050  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:29.053  7013  7501 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 18:15:29.053  1033  1097 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:29.060  1033  1097 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:15:29.064  7013  7505 D BluetoothAdapterProperties: Name is: G3
08-16 18:15:29.065  7013  7501 D BluetoothAdapterProperties: Setting state to 11
08-16 18:15:29.065  7013  7501 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:15:29.070  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:29.071  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:29.071  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 18:15:29.071  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 18:15:29.079  7013  7501 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 18:15:29.084  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 18:15:29.087  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.090  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:29.092  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:29.094  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:15:29.098  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 18:15:29.101  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:29.102  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:29.104  6494  6527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:15:29.106  7013  7013 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:29.107  7013  7013 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:29.107  7013  7013 V BluetoothPbapReceiver: ***********state = 11
08-16 18:15:29.109  5791  5791 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:15:29.110  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.110  7013  7501 D BluetoothBondStateMachine: make
08-16 18:15:29.115  7013  7523 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 18:15:29.117  7013  7501 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.117  7013  7501 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 18:15:29.118  7013  7501 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
,08-16 18:15:29.118  7013  7501 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 18:15:29.118  7013  7501 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 18:15:29.120  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:29.123  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:29.175  1033  1049 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7524 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:29.186  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:29.186  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:29.186  5791  5791 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:15:29.187  7013  7013 D HeadsetService: Received start request. Starting profile...
08-16 18:15:29.188  7013  7013 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:15:29.188  7013  7013 D LGBluetoothHfpAdapter: Version 1.6
08-16 18:15:29.193  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:15:29.196  7013  7013 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:15:29.199  7013  7013 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:15:29.200  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:29.201  7013  7013 D HeadsetStateMachine: make
,08-16 18:15:29.212  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:15:29.218  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:29.225  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:29.232  7013  7501 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:15:29.239  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.244  7013  7013 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:29.244  7013  7013 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:29.250  7013  7501 V LGMDMManager: Create singleton instance
,08-16 18:15:29.253  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:15:29.253  7013  7013 D HeadsetStateMachine: max_hf_connections = 1
08-16 18:15:29.253  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.253  7013  7013 I bluedroid-qcom: get_profile_interface handsfree
08-16 18:15:29.253  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:15:29.253  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:15:29.255  7013  7013 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 18:15:29.255  7084  7084 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:15:29.256  7013  7501 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 18:15:29.256   319  2160 V AudioPolicyService: registerClient() client 0xb1021f80, uid 1002
08-16 18:15:29.256   319  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 18:15:29.256   319  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:15:29.256   319  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:15:29.257  7013  7013 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 18:15:29.257   319  2159 V AudioFlinger: registerClient() client 0xb101fda8, pid 7013
08-16 18:15:29.257   319  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:29.257   319  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:29.257  7013  7013 V ToneGenerator: Create Track: 0xb4928a80
08-16 18:15:29.257  7013  7013 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 18:15:29.258  7013  7013 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 18:15:29.258  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:29.258  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:29.258  3502  3518 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:29.258  3502  3518 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:29.258   319  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:29.258   319  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:29.258  1033  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:29.258  1033  1575 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:29.258  1033  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-16 18:15:29.258  1033  1575 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:29.258  1852  2448 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:29.258  1852  2448 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:29.258  3502  3517 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:29.258  3502  3517 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-16 18:15:29.259   319  2160 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:15:29.259   319  2160 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 18:15:29.259   319  2160 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:15:29.259   319  2160 V AudioPolicyManagerEx: getOutput() returns output 2
,08-16 18:15:29.259  7013  7013 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 18:15:29.259  7013  7030 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:29.259  7013  7030 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 18:15:29.259  7013  7030 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:29.259  7013  7030 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 18:15:29.259   319  1382 I AudioFlinger: isAudioPlaybackHookOn() false
,08-16 18:15:29.259   319  2159 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:15:29.259   319  2159 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 18:15:29.259   319  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:15:29.259   319  2159 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:15:29.260  7013  7013 V AudioSystem: getLatency() output 2, latency 50
08-16 18:15:29.260  7013  7013 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 18:15:29.260  7013  7013 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 18:15:29.260   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:15:29.260   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 18:15:29.260   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:15:29.260   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 18:15:29.260   319   319 V AudioFlinger: createTrack() lSessionId: 22
08-16 18:15:29.261  7013  7013 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 18:15:29.261   319   319 V AudioFlinger: acquiring 22 from 7013, for 7013
08-16 18:15:29.261   319   319 V AudioFlinger:  added new entry for 22
08-16 18:15:29.261  7013  7013 V ToneGenerator: ToneGenerator INIT OK, time: 123889
08-16 18:15:29.261  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:29.262  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:29.262  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.262  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:29.262  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:29.263  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.265  7013  7013 D A2dpService: Received start request. Starting profile...
08-16 18:15:29.266  7013  7013 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 18:15:29.266  7084  7084 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21a33009
08-16 18:15:29.266  7084  7084 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:15:29.266  7084  7084 D AppUp4:CustFacade: isPhone : true
08-16 18:15:29.267  7084  7084 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:15:29.267  7084  7084 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:15:29.267  7013  7013 V Avrcp   : make
08-16 18:15:29.267  7013  7013 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 18:15:29.267  7013  7013 I bluedroid-qcom: get_profile_interface avrcp
08-16 18:15:29.270  7013  7542 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 18:15:29.270  7013  7542 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:15:29.270  7013  7542 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:15:29.270  7013  7542 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 18:15:29.270   319  2160 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7013
08-16 18:15:29.271   319  2160 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 18:15:29.271   319  2160 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 18:15:29.271   319  2160 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 18:15:29.271   319  2160 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 18:15:29.271   319  2160 V voice   : voice_set_parameters: exit with code(0)
08-16 18:1,5:29.271   319  2160 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 18:15:29.271   319  2160 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 18:15:29.271   319  2160 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 18:15:29.271   319  2160 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 18:15:29.271   319  2160 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 18:15:29.271   319  2160 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 18:15:29.272  7013  7542 V ToneGenerator: ToneGenerator destructor
08-16 18:15:29.272  7013  7542 V ToneGenerator: stopTone
08-16 18:15:29.272  7013  7542 V ToneGenerator: Delete Track: 0xb4928a80
08-16 18:15:29.272  7013  7542 V AudioTrack: ~AudioTrack, releasing session id from 7013 on behalf of 7013
08-16 18:15:29.272   319  2159 V AudioFlinger: releasing 22 from 7013 for 7013
08-16 18:15:29.272   319  2159 V AudioFlinger:  decremented refcount to 0
08-16 18:15:29.272   319  2159 V AudioFlinger: purging stale effects
08-16 18:15:29.273   319  2159 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 18:15:29.273   319  2159 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 18:15:29.273   319  2159 V AudioFlinger: PlaybackThread::Track destructor
08-16 18:15:29.273   319  2159 V AudioFlinger: removeClient_l() pid 7013, calling pid 319
,08-16 18:15:29.274   319  1258 V AudioPolicyService: AudioCommandThread() waking up
08-16 18:15:29.274   319  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 18:15:29.275   319  1258 V AudioPolicyManager: releaseOutput() 2
08-16 18:15:29.275   319  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 18:15:29.276  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.276  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:29.281  7013  7013 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 18:15:29.283  7013  7013 E AudioManager: No RCC entry present to update
08-16 18:15:29.283  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:29.283  7013  7013 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 18:15:29.285  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:15:29.286  7013  7013 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 18:15:29.287  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 18:15:29.287  7013  7013 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 18:15:29.287  7524  7524 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 18:15:29.288  7524  7524 W LG Account v2.2: No ProfileInfo entries
08-16 18:15:29.288  7524  7524 I LG Account v2.2: isEnabled: false
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Country: EU
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Operator: OPEN
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Ranking support: false
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Comfort support: false
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Accessory: true
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Health device: true
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Extra Pedometer: false
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Blood glucose device: false
08-16 18:15:29.288  7524  7524 I Feature : [Lifetracker]Device Number: 3
08-16 18:15:29.291  4304  7548 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:15:29.294  4304  7549 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.295  4304  7549 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:29.299  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:15:29.299  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 18:15:29.354  6871  6871 D BluetoothPermissionRequest: onReceive
,08-16 18:15:29.376  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 18:15:29.379  7111  7550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:29.392  6960  7552 W FormManager: Network not available. Please check & try again.
,08-16 18:15:29.399  3502  3502 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:15:29.399  3502  3502 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.400  3502  3502 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 18:15:29.402  1033  1932 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:29.402  1033  1932 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:29.404  7152  7152 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 18:15:29.404  7152  7152 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:15:29.405  6960  7553 V FormManager: Network unavailable.
08-16 18:15:29.413  6960  7553 V FormManager: Network unavailable.
,08-16 18:15:29.417  7226  7226 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:29
08-16 18:15:29.419  7226  7226 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:15:29.419  7226  7226 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:15:29.420  7226  7226 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:15:29.420  7226  7226 D WeatherAncestor: connectivity changed - connection : true
08-16 18:15:29.421  7226  7226 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@262342f
08-16 18:15:29.421  7226  7226 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:15:29.421  7226  7226 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:15:29.422  7226  7226 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:15:29.422  7226  7226 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:15:29.422  7226  7226 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:29
08-16 18:15:29.443  6494  6494 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 18:15:29.445  6494  6527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:15:29.454  1033  2050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 18:15:29.458  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:29.459  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 18:15:29.462  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:15:29.463  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 18:15:29.463  7013  7013 I BluetoothA2dpServiceJni: classInitNative
08-16 18:15:29.463  7013  7013 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:15:29.463  7013  7013 D A2dpStateMachine: make
08-16 18:15:29.465  7013  7013 I bluedroid-qcom: get_profile_interface a2dp
08-16 18:15:29.465  7013  7556 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:15:29.467  7013  7013 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:15:29.467  7013  7013 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 18:15:29.468  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.468  7013  7555 D A2dpStateMachine: Enter Disconnected: -2
08-16 18:15:29.468  7013  7013 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 18:15:29.469  7013  7013 D HidService: Received start request. Starting profile...
08-16 18:15:29.469  7013  7013 I bluedroid-qcom: get_profile_interface hidhost
08-16 18:15:29.469  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.470  7013  7013 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 18:15:29.470  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:15:29.470  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.471  7013  7013 D HealthService: Received start request. Starting profile...
08-16 18:15:29.471  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:15:29.471  7084  7084 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:15:29.473  7084  7084 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 18:15:29.474  7013  7013 I bluedroid-qcom: get_profile_interface health
08-16 18:15:29.475  7013  7013 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:15:29.475  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.476  7013  7013 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 18:15:29.478  7013  7013 D PanService: Received start request. Starting profile...
08-16 18:15:29.478  7084  7084 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21a33009
08-16 18:15:29.478  7084  7084 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:15:29.478  7013  7013 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:15:29.478  7013  7013 I bluedroid-qcom: get_profile_interface pan
08-16 18:15:29.478  7084  7084 D AppUp4:CustFacade: isPhone : true
08-16 18:15:29.478  7084  7084 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:15:29.479  7084  7084 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:15:29.482  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.482  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:29.484  7013  7013 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 18:15:29.484  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.484  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:29.485  7013  7013 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 18:15:29.487  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:29.489  7013  7013 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:15:29.490  7013  7013 D BtGatt.GattService: Received start request. Starting profile...
08-16 18:15:29.490  7013  7013 D BtGatt.GattService: start()
08-16 18:15:29.490  7013  7013 I bluedroid-qcom: get_profile_interface gatt
08-16 18:15:29.490  7013  7013 D BtGatt.AdvertiseManager: advertise manager created
,08-16 18:15:29.494  4304  7563 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:15:29.495  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.496  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.497  7013  7013 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 18:15:29.497  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:15:29.497  4304  7565 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.497  4304  7565 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:29.497  7013  7013 V BluetoothMapService: BluetoothMapBinder()
08-16 18:15:29.498  7013  7013 D BluetoothMapService: Received start request. Starting profile...
08-16 18:15:29.498  7013  7013 D BluetoothMapService: start()
08-16 18:15:29.501  7013  7013 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 18:15:29.501  7013  7013 D BluetoothMapEmailAppObserver: createReceiver()
08-16 18:15:29.504  7013  7013 D BluetoothMapEmailAppObserver: initObservers()
08-16 18:15:29.504  7013  7013 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 18:15:29.511  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:29.511  7013  7013 D HeadsetStateMachine: Proxy object connected
08-16 18:15:29.512  7013  7013 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 18:15:29.512  7013  7013 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 18:15:29.512  7111  7566 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:29.517  7013  7013 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:29.517  7013  7542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 18:15:29.517  7013  7542 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:15:29.517  7013  7542 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-16 18:15:29.519  7013  7013 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:29.522  3502  3502 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:15:29.522  3502  3502 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:29.522  7013  7013 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:29.524  7013  7013 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:29.526  3502  3502 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 18:15:29.527  7013  7013 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:29.527  6960  7568 W FormManager: Network not available. Please check & try again.
08-16 18:15:29.527  7013  7013 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 18:15:29.529  7013  7013 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 18:15:29.529  7013  7013 V BluetoothMapService: Handler(): got msg=1
,08-16 18:15:29.530  7013  7501 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 18:15:29.531  7013  7501 I bluedroid-qcom: enable
08-16 18:15:29.531  7013  7501 I bt_hci_bdroid: init
08-16 18:15:29.531  7013  7571 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 18:15:29.532  7013  7501 I bt_vendor: bt-vendor : init
08-16 18:15:29.532  7013  7501 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 18:15:29.532  7013  7501 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 18:15:29.532  7013  7501 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 18:15:29.532  7013  7501 D bt_userial_mct: userial_init
08-16 18:15:29.532  7013  7571 I bt-btu  : btu_task pending for preload complete event
08-16 18:15:29.532  7152  7152 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:15:29.533  7013  7501 D bt_hci_bdroid: set_power 1
08-16 18:15:29.533  7013  7501 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 18:15:29.533  7013  7501 I bt_vendor: Starting hciattach daemon
08-16 18:15:29.533  7013  7501 I bt_vendor: try to set true
08-16 18:15:29.533  7152  7152 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:15:29.533  7013  7013 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:29.524  7574  7574 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:29.538  7013  7013 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:29.524  7574  7574 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:29.538  7013  7013 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:29.538  7013  7013 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:29.538  7013  7013 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:29.538  7013  7013 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 18:15:29.541  6960  7569 V FormManager: Network unavailable.
08-16 18:15:29.559  7575  7575 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 18:15:29.582  1033  1649 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7578 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:29.584  6960  7569 V FormManager: Network unavailable.
,08-16 18:15:29.590  7226  7226 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:29
08-16 18:15:29.594  7226  7226 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:15:29.594  7226  7226 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:15:29.595  7226  7226 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:15:29.595  7226  7226 D WeatherAncestor: connectivity changed - connection : true
08-16 18:15:29.595  7226  7226 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@262342f
,08-16 18:15:29.597  7226  7226 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 18:15:29.597  7226  7226 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:15:29.597  7226  7226 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:15:29.598  7226  7226 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:15:29.598  7226  7226 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:29
08-16 18:15:29.622  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 18:15:29.631  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 18:15:29.641  7578  7578 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:29.653  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:15:29.658  1033  2050 I ActivityManager: Killing 6109:com.android.vending/u0a44 (adj 15): empty #17
08-16 18:15:29.661  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 18:15:29.670  7603  7603 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:15:29.679  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 18:15:29.698  7606  7606 I libmdmdetect: ESOC framework not supported
08-16 18:15:29.699  7606  7606 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 18:15:29.709  7606  7606 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 18:15:29.709  7606  7606 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 18:15:29.709  7606  7606 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 18:15:29.709  7606  7606 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 18:15:29.709  7606  7606 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 18:15:29.709  7606  7606 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 18:15:29.709  7606  7606 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 18:15:29.716  1033  1782 W libprocessgroup: failed to open /acct/uid_10044/pid_6109/cgroup.procs: No such file or directory
,08-16 18:15:29.757  7606  7607 E QC-QMI  : qmi_client [7606] 14: failed to locate client data
,08-16 18:15:29.758   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 18:15:29.758   472   472 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 18:15:29.813  7608  7608 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 18:15:29.842  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:15:29.884  7013  7501 I bt_vendor: bluetooth satus is on
,08-16 18:15:29.884  7013  7501 D bt_hci_bdroid: preload
08-16 18:15:29.884  7013  7573 D bt_userial_mct: userial_open(port:0)
08-16 18:15:29.884  7013  7573 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 18:15:29.888  7013  7573 I bt_vendor: Done intiailizing UART
08-16 18:15:29.891  7013  7573 I bt_vendor: Done intiailizing UART
08-16 18:15:29.891  7013  7573 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 18:15:29.891  7013  7573 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 18:15:29.891  7013  7571 I bt-btu  : btu_task received preload complete event
08-16 18:15:29.891  7013  7614 D bt_userial_mct: Entering userial_read_thread()
08-16 18:15:29.893  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 18:15:29.893  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 18:15:29.898  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 18:15:29.904  7013  7571 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 18:15:29.905  7013  7571 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 18:15:30.033  7013  7571 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 18:15:30.033  7013  7571 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0158061 
08-16 18:15:30.033  7013  7571 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0158061 
,08-16 18:15:30.051  7013  7505 E bt-btif : Calling BTA_HhEnable
08-16 18:15:30.051  7013  7505 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 18:15:30.051  7013  7505 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 18:15:30.055  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:15:30.055  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 18:15:30.056  7013  7505 D BluetoothAdapterProperties: Name is: G3
08-16 18:15:30.057  7013  7505 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:15:30.057  7013  7505 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:30.057  7013  7505 D bt_hci_bdroid: postload
08-16 18:15:30.058  7013  7505 D bte_conf: Device ID record 1 : primary
08-16 18:15:30.058  7013  7505 D bte_conf:   vendorId            = 00c4
08-16 18:15:30.058  7013  7505 D bte_conf:   vendorIdSource      = 0001
08-16 18:15:30.058  7013  7505 D bte_conf:   product             = 13a1
08-16 18:15:30.058  7013  7505 D bte_conf:   version             = 1000
08-16 18:15:30.058  7013  7505 D bte_conf:   clientExecutableURL = 
08-16 18:15:30.058  7013  7505 D bte_conf:   serviceDescription  = 
08-16 18:15:30.058  7013  7505 D bte_conf:   documentationURL    = 
08-16 18:15:30.059  7013  7573 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:15:30.059  7013  7505 D bte_conf: bte_load_did_conf no section named DID2.
08-16 18:15:30.054  7622  7622 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 18:15:30.068  7013  7501 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 18:15:30.068  7013  7501 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:15:30.068  7013  7501 D BluetoothAdapterProperties: State =  11
08-16 18:15:30.069  7013  7501 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 18:15:30.069  7013  7501 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 18:15:30.069  7013  7501 D BluetoothAdapterProperties: Setting state to 12
08-16 18:15:30.069  7013  7501 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 18:15:30.071  7013  7505 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:15:30.064  7622  7622 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:30.075  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:30.075  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 18:15:30.075  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 18:15:30.083  7013  7501 I BluetoothAdapterState: Entering On State
,08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:30.112  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:30.116  7013  7505 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:30.116  7013  7505 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 18:15:30.117  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:30.122  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:30.125  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:30.139  7013  7501 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 18:15:30.139  7013  7501 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 18:15:30.139  7013  7501 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 18:15:30.142  7013  7501 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 18:15:30.143  7013  7501 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 18:15:30.143  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 18:15:30.143  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 18:15:30.143  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 18:15:30.144  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 18:15:30.144  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 18:15:30.144  7013  7571 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 18:15:30.144  7013  7505 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 18:15:30.144  7013  7573 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:15:30.172  7013  7573 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 18:15:30.175  6871  6887 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:15:30.176  7627  7627 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 18:15:30.178  7013  7614 E bt_mct  : hci lib postload completed
08-16 18:15:30.182  6871  6887 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:15:30.191  6871  6871 D BluetoothInputDevice: Proxy object connected
08-16 18:15:30.191  6871  6871 D HidProfile: Bluetooth service connected
08-16 18:15:30.196  7013  7571 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:30.196  7013  7571 W bt-smp  : Plain text(LSB ~ MSB) = bd 8e 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:30.196  7013  7571 W bt-smp  : Encrypted text(LSB ~ MSB) = 35 b0 b4 8c b6 45 8b 14 76 3c 4e cf 4a 7a 93 8d 
08-16 18:15:30.197  7013  7571 W bt-btm  : Stopping oneshot timer
08-16 18:15:30.199  6871  6886 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:15:30.203  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:30.206  1852  1852 D BluetoothHeadset: Proxy object connected
08-16 18:15:30.206  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:30.208  1852  1852 D BluetoothHeadset: Proxy object connected
08-16 18:15:30.209  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:30.211  1852  1852 D BluetoothHeadset: Proxy object connected
08-16 18:15:30.211  1033  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:30.212  1033  1033 D BluetoothHeadset: Proxy object connected
08-16 18:15:30.212  6871  6887 D BluetoothPan: onBluetoothStateChange on: true
08-16 18:15:30.212  6871  6887 D BluetoothPan: onBluetoothStateChange call bindService
08-16 18:15:30.215  1033  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:30.216  7013  7571 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:30.216  7013  7571 W bt-smp  : Plain text(LSB ~ MSB) = 6d 21 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:30.216  7013  7571 W bt-smp  : Encrypted text(LSB ~ MSB) = 7a e4 df 2e d1 31 b1 32 6b a9 d1 9c 09 f2 bb bd 
08-16 18:15:30.216  7013  7571 W bt-btm  : Stopping oneshot timer
,08-16 18:15:30.218  1033  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 18:15:30.218  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 18:15:30.219  1033  1033 D BluetoothA2dp: Proxy object connected
08-16 18:15:30.221  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 18:15:30.221  1033  1097 D BluetoothManagerService: Message: 40
08-16 18:15:30.221  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 18:15:30.221  6871  6871 D BluetoothMap: Proxy object connected
08-16 18:15:30.221  6871  6871 D MapProfile: Bluetooth service connected
08-16 18:15:30.221  6871  6871 D BluetoothMap: getConnectedDevices()
08-16 18:15:30.222  7013  7030 V BluetoothMapService: getConnectedDevices()
08-16 18:15:30.222  6871  6871 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:30.223  6871  6871 D PanProfile: Bluetooth service connected
08-16 18:15:30.228  7013  7571 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:30.228  7013  7571 W bt-smp  : Plain text(LSB ~ MSB) = 7a a5 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:30.228  7013  7571 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 ab 2f 10 99 a3 03 0f b1 b2 1c 58 f7 42 ad ed 
08-16 18:15:30.228  7013  7571 W bt-btm  : Stopping oneshot timer
08-16 18:15:30.236  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.236  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 18:15:30.239  7013  7571 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:30.239  7013  7571 W bt-smp  : Plain text(LSB ~ MSB) = 67 e3 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:30.239  7013  7571 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 0f 51 ea 34 7a a9 19 41 08 f6 cf 76 cf 7b 3f 
08-16 18:15:30.239  7013  7571 W bt-btm  : Stopping oneshot timer
08-16 18:15:30.239  1941  2139 D LGBluetoothAPIService: Message: 1
08-16 18:15:30.239  1941  2139 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 18:15:30.244  7013  7013 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.244  7013  7013 D BluetoothMapService: STATE_ON
08-16 18:15:30.244  7013  7013 V BluetoothMapService: Handler(): got msg=1
08-16 18:15:30.245  7013  7013 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 18:15:30.246  7013  7644 D BluetoothMapMasInstance: MAS initSocket()
08-16 18:15:30.247  7013  7644 D BluetoothMapMasInstance:   masId = 00
08-16 18:15:30.247  7013  7644 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 18:15:30.247  7013  7644 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 18:15:30.247  7013  7644 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 18:15:30.247  6680  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 18:15:30.248  7013  7571 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:30.248  7013  7571 W bt-smp  : Plain text(LSB ~ MSB) = 32 ac 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:30.248  7013  7571 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 15 8d 20 60 a4 82 bb 3e b9 5f d4 19 e1 76 ba 
08-16 18:15:30.248  7013  7571 W bt-btm  : Stopping oneshot timer
,08-16 18:15:30.252  1941  2139 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 18:15:30.253  1033  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:30.255  7013  7644 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:30.255  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:30.256  6871  6871 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 18:15:30.256  7013  7644 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 18:15:30.258  7013  7644 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 18:15:30.258  7013  7644 D BluetoothMapMasInstance: Accepting socket connection...
08-16 18:15:30.261  1033  1097 D BluetoothManagerService: Message: 30
08-16 18:15:30.261  7013  7505 D BluetoothAdapterProperties: Scan Mode:21
,08-16 18:15:30.261  7013  7505 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 18:15:30.264  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:30.264  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:30.265  7013  7013 V BluetoothPbapService: Pbap Service onCreate
08-16 18:15:30.265  7013  7013 V BluetoothPbapService: Starting PBAP service
08-16 18:15:30.266  7013  7013 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 18:15:30.267  7013  7013 V BluetoothPbapService: Pbap Service onBind
08-16 18:15:30.267  6871  6871 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 18:15:30.268  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:30.269  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:30.270  1033  1097 D BluetoothManagerService: Message: 30
08-16 18:15:30.272  7013  7013 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.272  7013  7013 V BluetoothPbapService: state: 12
08-16 18:15:30.274  7013  7013 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 18:15:30.274  7013  7013 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 18:15:30.274  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-16 18:15:30.276  7013  7013 V BluetoothPbapService: Handler(): got msg=1
08-16 18:15:30.277  1941  2139 D LGBluetoothAPIService: Message: 100
08-16 18:15:30.277  1941  2139 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 18:15:30.277  7013  7013 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 18:15:30.278  7013  7646 V BluetoothPbapService: Pbap Service initSocket
08-16 18:15:30.279  1033  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:30.280  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 18:15:30.281  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 18:15:30.281  7013  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:30.283  7246  7288 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 18:15:30.284  6871  6871 D BluetoothA2dp: Proxy object connected
08-16 18:15:30.284  7013  7646 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 18:15:30.285  7013  7646 V BluetoothPbapService: Succeed to create listening socket 
08-16 18:15:30.285  7013  7646 V BluetoothPbapService: Accepting socket connection...
08-16 18:15:30.285  6871  6871 D A2dpProfile: Bluetooth service connected
08-16 18:15:30.285  7013  7013 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:30.285  7013  7013 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.285  7013  7013 V BluetoothPbapReceiver: ***********state = 12
,08-16 18:15:30.289  6871  6871 D BluetoothPbap: Proxy object connected
08-16 18:15:30.289  6871  6871 D PbapServerProfile: Bluetooth service connected
08-16 18:15:30.290  6871  6871 D BluetoothHeadset: Proxy object connected
08-16 18:15:30.290  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:30.290  2208  2208 D c       : Getting all permits...
08-16 18:15:30.290  2208  2208 D a       : Opening database...
08-16 18:15:30.290  6871  6871 D HeadsetProfile: Bluetooth service connected
08-16 18:15:30.294  6871  6871 D DockEventReceiver: finishStartingService: stopping service
08-16 18:15:30.294  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-16 18:15:30.298  2208  2208 D a       : Closing database...
,08-16 18:15:30.307  6871  6871 D BluetoothPermissionRequest: onReceive
08-16 18:15:30.309  6871  6871 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 18:15:30.310  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:15:30.313  7013  7013 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 18:15:30.315  7013  7013 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 18:15:30.320  7013  7013 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 18:15:30.333  7013  7013 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 18:15:30.333  7013  7013 V BtOppService: onCreate
08-16 18:15:30.337  7013  7013 V BluetoothOppNotification: send message
,08-16 18:15:30.340  7013  7013 V BtOppService: Starting RfcommListener
08-16 18:15:30.346  7013  7013 D BluetoothOppPreference: Dumping Names:  
08-16 18:15:30.346  7013  7013 D BluetoothOppPreference: {}
08-16 18:15:30.346  7013  7013 D BluetoothOppPreference: Dumping Channels:  
08-16 18:15:30.346  7013  7013 D BluetoothOppPreference: {}
,08-16 18:15:30.352  7013  7013 V BtOppService: onStartCommand
08-16 18:15:30.354  7013  7656 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:15:30.356  7013  7013 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.356  7013  7013 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:15:30.359  7013  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-16 18:15:30.359  7013  7013 V BluetoothOppNotification: new notify threadi!
08-16 18:15:30.361  7013  7013 V BluetoothOppNotification: send delay message
08-16 18:15:30.362  7013  7013 V BtOppService: start RfcommListener
08-16 18:15:30.362  7013  7657 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 18:15:30.364  7013  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cb78bb8 on behalf of 
08-16 18:15:30.365  7013  7657 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f08bd91 on behalf of 
08-16 18:15:30.365  7013  7657 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:15:30.366  7013  7656 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:15:30.366  7013  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:15:30.367  7013  7657 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:30.368  7013  7013 V BtOppService: RfcommListener started
08-16 18:15:30.368  7013  7653 V BtOppService: Deleted complete outbound shares, number =  0
08-16 18:15:30.369  7013  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fa114f6 on behalf of 
08-16 18:15:30.369  7013  7657 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@283d10f7 on behalf of 
08-16 18:15:30.370  7013  7653 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 18:15:30.371  7013  7653 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 18:15:30.371  7013  7657 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 18:15:30.373  7013  7658 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 18:15:30.373  7013  7656 V BluetoothOppNotification: update too frequent, put in queue
,08-16 18:15:30.375  1033  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:30.375  7013  7653 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1335ab64 on behalf of 
08-16 18:15:30.376  7013  7657 V BluetoothOppNotification: outbound notification was removed.
08-16 18:15:30.377  7013  7657 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:30.377  7013  7657 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b6aa1cd on behalf of 
08-16 18:15:30.378  7013  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:30.378  7013  7657 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:15:30.379  7013  7656 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:15:30.379  7013  7658 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 18:15:30.379  7013  7658 V BtOppRfcommListener: Started RFCOMM listener....
08-16 18:15:30.379  7013  7658 I BtOppRfcommListener: Accept thread started.
08-16 18:15:30.379  7013  7658 V BtOppRfcommListener: Accepting connection...
08-16 18:15:30.380  7013  7657 V BluetoothOppNotification: inbound notification was removed.
08-16 18:15:30.380  7013  7657 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 18:15:30.382  7013  7657 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b418a82 on behalf of 
08-16 18:15:30.389  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:30.389  7013  7013 V BluetoothFtpService: Ftp Service onCreate
08-16 18:15:30.389  7013  7013 I BluetoothFtpService: Ftp Service onCreate
08-16 18:15:30.389  7013  7013 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:15:30.389  7013  7013 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.390  7013  7013 V BluetoothFtpService: Starting Listening on sockets
08-16 18:15:30.390  7013  7013 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:30.390  7013  7013 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:30.390  7013  7013 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:30.390  7013  7013 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.390  7013  7013 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 18:15:30.390  7013  7013 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 18:15:30.393  7013  7013 V BtOppService: ContentObserver received notification
08-16 18:15:30.393  7013  7013 V BtOppService: ContentObserver received notification
08-16 18:15:30.393  7013  7013 V BluetoothFtpService: Handler(): got msg=1
08-16 18:15:30.394  7013  7013 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 18:15:30.394  7013  7013 V BluetoothFtpService: Ftp Service initSocket
08-16 18:15:30.398  1033  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:30.399  7013  7013 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:30.400  7013  7659 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:15:30.400  7013  7659 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:15:30.400  7013  7013 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 18:15:30.400  7013  7013 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 18:15:30.402  7013  7660 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 18:15:30.402  7013  7659 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@395419d0 on behalf of 
08-16 18:15:30.403  7013  7659 V BluetoothOppNotification: update too frequent, put in queue
,08-16 18:15:30.405  7013  7659 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:15:30.417  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:30.417  7013  7013 V BluetoothSapService: Sap Service onCreate
,08-16 18:15:30.419  7013  7013 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:30.419  7013  7013 V BluetoothSapService: state: 12
08-16 18:15:30.419  7013  7013 V BluetoothSapService: Starting SAP server process
08-16 18:15:30.420  7013  7013 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 18:15:30.404  7661  7661 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:30.414  7661  7661 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:30.422  7013  7662 V BluetoothSapService: Sap Service initRfcommSocket
08-16 18:15:30.423  1033  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:30.424  7013  7662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:30.425  7013  7662 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 18:15:30.425  7013  7662 V BluetoothSapService: Succeed to create listening socket 
08-16 18:15:30.425  7013  7662 V BluetoothSapService: Accepting socket connection...
08-16 18:15:30.434  7661  7661 V BT_SAP  : Event pipe created
08-16 18:15:30.434  7661  7661 V BT_SAP  : create_server_socket qcom.sap.server
08-16 18:15:30.434  7661  7661 V BT_SAP  : created socket fd 6
,08-16 18:15:30.980  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:30.981  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:31.027  1033  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 18:15:31.029  1033  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 18:15:31.149  1033  2025 I ActivityManager: Killing 7437:com.lge.bnr/1000 (adj 15): empty #17
,08-16 18:15:31.184  1033  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_7437/cgroup.procs: No such file or directory
,08-16 18:15:31.363  7013  7013 V BluetoothOppNotification: new notify threadi!
,08-16 18:15:31.364  7013  7013 V BluetoothOppNotification: send delay message
,08-16 18:15:31.374  7013  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 18:15:31.376  7013  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18a902fc on behalf of 
08-16 18:15:31.377  7013  7672 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:15:31.378  7013  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:31.379  7013  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c73d85 on behalf of 
08-16 18:15:31.380  7013  7672 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 18:15:31.384  7013  7672 V BluetoothOppNotification: outbound notification was removed.
08-16 18:15:31.384  7013  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:31.386  7013  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3871e7da on behalf of 
08-16 18:15:31.386  7013  7672 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:15:31.388  7013  7672 V BluetoothOppNotification: inbound notification was removed.
08-16 18:15:31.388  7013  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 18:15:31.464  1033  2050 I ActivityManager: Killing 6792:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 18:15:31.559  1033  1966 I art     : Explicit concurrent mark sweep GC freed 91096(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.851ms total 163.517ms
,08-16 18:15:31.563  7013  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29c0540b on behalf of 
08-16 18:15:31.570  6917  6917 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 18:15:31.570  6917  6917 W System.err: android.os.DeadObjectException
08-16 18:15:31.570  6917  6917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:31.570  6917  6917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:31.570  6917  6917 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 18:15:31.570  6917  6917 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 18:15:31.570  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 18:15:31.570  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 18:15:31.571  6917  6917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:15:31.571  6917  6917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:15:31.571  6917  6917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:15:31.571  6917  6917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:31.571  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:31.571  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:31.571  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:15:31.571  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 18:15:31.577  6917  6917 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-16 18:15:31.577  6917  6917 W System.err: android.os.DeadObjectException
,08-16 18:15:31.578  6917  6917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:31.578  6917  6917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:31.578  6917  6917 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 18:15:31.578  6917  6917 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 18:15:31.578  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 18:15:31.579  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 18:15:31.579  6917  6917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:15:31.579  6917  6917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:15:31.579  6917  6917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-16 18:15:31.579  6917  6917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:31.579  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:31.579  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:31.579  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-16 18:15:31.579  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 18:15:31.580  6917  6917 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 18:15:31.580  6917  6917 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.,
08-16 18:15:31.684   276   276 E lowmemorykiller: Error opening /proc/6792/oom_score_adj; errno=2
,08-16 18:15:31.694  1033  1049 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-16 18:15:31.694  1033  1049 W ActivityManager: android.os.DeadObjectException
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-16 18:15:31.694  1033  1049 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:31.697  1033  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6792/cgroup.procs: No such file or directory
08-16 18:15:31.700  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 18:15:31.701  6917  6917 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 18:15:31.779  1033  1887 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7684 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:31.781  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 18:15:31.866  7684  7684 D UEI.SmartControl: Quickset Services start...
,08-16 18:15:31.868  7684  7684 I UEI.SmartControl: Manufacture = LGE
,08-16 18:15:31.869  7684  7684 D UEI.SmartControl: Id = LGNevo
08-16 18:15:31.870  7684  7684 D UEI.SmartControl: File observer start...
08-16 18:15:31.871  7684  7684 E UEI.SmartControl: IR Port is disabled: false
08-16 18:15:31.871  7684  7684 D UEI.SmartControl: Starting file observer...
08-16 18:15:31.871  7684  7684 D UEI.SmartControl: Extracting JNI libs...
08-16 18:15:31.871  7684  7684 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-16 18:15:31.965  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:31.965  1033  1049 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1b18e475 mBinding = false
,08-16 18:15:31.972  7684  7684 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 18:15:31.972  7684  7684 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 18:15:31.972  7684  7684 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 18:15:32.003  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 18:15:32.004  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:32.005  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:32.006  1033  1097 D BluetoothManagerService: Message: 2
08-16 18:15:32.007  1033  1097 D BluetoothManagerService: Sending off request.
08-16 18:15:32.009  7013  7643 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 18:15:32.010  7013  7501 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 18:15:32.010  7013  7501 D BluetoothAdapterProperties: Setting state to 13
08-16 18:15:32.010  7013  7501 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:15:32.011  7013  7501 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 18:15:32.011  7013  7501 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 18:15:32.013  7013  7505 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:15:32.013  7013  7501 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 18:15:32.014  7013  7501 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 18:15:32.015  7013  7644 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 18:15:32.015  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 18:15:32.016  7013  7646 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:32.017  7013  7660 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:32.017  7013  7571 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 18:15:32.018  7013  7662 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:32.018  7013  7658 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:32.022  7013  7571 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:32.023  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 18:15:32.023  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 18:15:32.024  7013  7571 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 18:15:32.027  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:32.028  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:32.031  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:32.031  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:32.031  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:32.032  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 18:15:32.033  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 18:15:32.036  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:32.037  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:32.037  6680  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:32.037  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:32.039  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.040  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:15:32.046  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:32.047  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:32.050  7013  7013 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.050  7013  7013 D BluetoothMapService: STATE_TURNING_OFF
08-16 18:15:32.050  7013  7013 V BluetoothMapService: Handler(): got msg=4
08-16 18:15:32.051  7013  7013 D BluetoothMapService: MAP Service closeService in
08-16 18:15:32.051  7013  7013 D BluetoothMapMasInstance: MAP Service shutdown
08-16 18:15:32.051  7013  7013 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:15:32.051  7013  7013 V BluetoothMapService: MAP Service closeService out
08-16 18:15:32.052  7013  7013 V BtOppService: Receiver DISABLED_ACTION 
08-16 18:15:32.052  7013  7013 I BtOppRfcommListener: stopping Accept Thread
08-16 18:15:32.053  7013  7013 V BtOppRfcommListener: close mBtServerSocket
08-16 18:15:32.053  7013  7013 V BtOppRfcommListener: waiting for thread to terminate
08-16 18:15:32.054  7013  7658 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 18:15:32.054  7013  7013 V BtOppRfcommListener: done waiting for thread to terminate
08-16 18:15:32.058  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 18:15:32.059  7684  7684 I UEI.SmartControl: --- Selecting new region: 6
08-16 18:15:32.062  7684  7684 I UEI.SmartControl: Model = LG-D855
08-16 18:15:32.064  7684  7684 D UEI.SmartControl: QS Service created
08-16 18:15:32.066  7013  7013 V BtOppService: onDestroy
,08-16 18:15:32.069  7013  7013 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 18:15:32.072  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 18:15:32.077  7013  7013 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:32.077  7013  7013 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.077  7013  7013 V BluetoothPbapReceiver: ***********state = 13
08-16 18:15:32.079  7013  7013 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 18:15:32.082  7013  7013 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.082  7013  7013 V BluetoothPbapService: state: 13
08-16 18:15:32.082  7013  7013 V BluetoothPbapService: Pbap Service closeService in
,08-16 18:15:32.087  7684  7684 I UEI.SmartControl: Service initServices...
08-16 18:15:32.091  7013  7013 V BluetoothPbapService: successfully stopped pbap service
08-16 18:15:32.091  7013  7013 V BluetoothPbapService: Pbap Service closeService out
08-16 18:15:32.092  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:32.092  7013  7013 V BluetoothPbapService: Pbap Service onDestroy
,08-16 18:15:32.092  7013  7013 V BluetoothPbapService: Pbap Service closeService in
08-16 18:15:32.092  7013  7013 V BluetoothPbapService: Pbap Service closeService out
08-16 18:15:32.092  7013  7013 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 18:15:32.094  7684  7684 D UEI.SmartControl: QS start get config
08-16 18:15:32.101  6871  6871 D DockEventReceiver: finishStartingService: stopping service
08-16 18:15:32.102  6871  6871 D BluetoothPbap: Proxy object disconnected
08-16 18:15:32.102  6871  6871 D PbapServerProfile: Bluetooth service disconnected
08-16 18:15:32.106  6871  6871 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 18:15:32.112  6871  6871 D BluetoothPermissionRequest: onReceive
08-16 18:15:32.112  6871  6871 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 18:15:32.120  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 18:15:32.125  7013  7013 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 18:15:32.125  7013  7013 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 18:15:32.125  7013  7013 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 18:15:32.128  7013  7013 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.128  7013  7013 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:15:32.129  7013  7013 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:15:32.130  7013  7013 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.130  7013  7013 V BluetoothFtpService: Ftp Service closeService
08-16 18:15:32.130  7013  7013 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 18:15:32.131  7013  7013 V BluetoothFtpService: successfully stopped ftp service
08-16 18:15:32.131  7013  7013 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:32.131  7013  7013 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-16 18:15:32.131  7013  7013 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:32.131  7013  7013 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.131  7013  7013 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 18:15:32.131  7013  7013 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 18:15:32.133  7013  7013 V BluetoothFtpService: Ftp Service onDestroy
08-16 18:15:32.133  7013  7013 V BluetoothFtpService: Ftp Service closeService
08-16 18:15:32.140  7013  7013 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.140  7013  7013 V BluetoothSapService: state: 13
08-16 18:15:32.141  7013  7013 V BluetoothSapService: Stopping SAP server process
08-16 18:15:32.141  7013  7013 V BluetoothSapService: Sap Service closeSapService in
08-16 18:15:32.141  7013  7013 V BluetoothSapService: Close listen Socket : 
08-16 18:15:32.141  7013  7013 V BluetoothSapService: Close rfcomm Socket : 
08-16 18:15:32.142  7013  7013 V BluetoothSapService: Close sapd  Socket : 
08-16 18:15:32.143  7013  7013 V BluetoothSapService: Sap Service closeSapService out
08-16 18:15:32.143  7013  7013 V BluetoothSapService: Sap Service onDestroy
08-16 18:15:32.143  7013  7013 V BluetoothSapService: Sap Service closeSapService in
08-16 18:15:32.143  7013  7013 V BluetoothSapService: Close listen Socket : 
08-16 18:15:32.143  7013  7013 V BluetoothSapService: Close rfcomm Socket : 
08-16 18:15:32.143  7013  7013 V BluetoothSapService: Close sapd  Socket : 
08-16 18:15:32.144  7013  7013 V BluetoothSapService: Sap Service closeSapService out
,08-16 18:15:32.179  7684  7684 D UEI.SmartControl: Loading JNI Libs...
,08-16 18:15:32.455  7684  7684 I UEI.SmartControl: Supports setup maps: true
,08-16 18:15:32.460  7684  7684 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 18:15:32.461  7684  7684 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 18:15:32.461  7684  7684 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 18:15:32.461  7684  7684 I UEI.SmartControl: ### init IR Blaster...
08-16 18:15:32.466  7684  7684 D serial_port: Configuring serial port
08-16 18:15:32.470  7684  7684 E UEI.SmartControl: UEIBLaster setting for 616
,08-16 18:15:32.470  7684  7684 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 18:15:32.471  7684  7684 I UEI.SmartControl: configuring settings for MAXQ616
08-16 18:15:32.471  7684  7684 I UEI.SmartControl: Get version...
,08-16 18:15:32.488  7684  7723 D UEI.SmartControl: serial port data available: 21
,08-16 18:15:32.519  7684  7684 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 18:15:32.519  7684  7684 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 18:15:32.519  7684  7684 I UEI.SmartControl: QS saving settings...
,08-16 18:15:32.523  7684  7684 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 18:15:32.541  7684  7723 D UEI.SmartControl: serial port data available: 4
,08-16 18:15:32.574  7684  7726 I UEI.SmartControl: Device manager: loading config....
,08-16 18:15:32.575  7684  7726 D UEI.SmartControl: ----------- loading internal config...
08-16 18:15:32.576  7684  7684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 18:15:32.581  7684  7684 E UEI.SmartControl: Services init done
,08-16 18:15:32.582  7684  7684 D UEI.SmartControl: QS Service init finished
,08-16 18:15:32.583  7684  7684 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 18:15:32.583  7684  7684 D UEI.SmartControl: QS Service version code: 201091
08-16 18:15:32.585  7684  7684 D UEI.SmartControl: Service requested: Control
08-16 18:15:32.591  7684  7684 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 18:15:32.593  1033  1649 I ActivityManager: Killing 6917:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 18:15:32.596  7684  7726 E UEI.SmartControl: Loading SETTINGS...
08-16 18:15:32.604  7684  7726 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 18:15:32.612  7684  7725 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 18:15:32.613  7684  7725 D UEI.SmartControl: -----service ready thread exits
08-16 18:15:32.652  1033  1990 W libprocessgroup: failed to open /acct/uid_10112/pid_6917/cgroup.procs: No such file or directory
08-16 18:15:32.653  7684  7684 D UEI.SmartControl: Internal service binding...
,08-16 18:15:32.926  7013  7505 D bt_hci_bdroid: cleanup
,08-16 18:15:32.933  7013  7573 I bt_lpm  : LPM is already off!!!
,08-16 18:15:32.934  7013  7614 I bt_userial_mct: exiting userial_read_thread
,08-16 18:15:32.934  7013  7614 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-16 18:15:32.935  7013  7571 W bt-btif : ag scb idx 1 not allocated
08-16 18:15:32.935  7013  7571 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 18:15:32.935  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:32.935  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017,
,08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
08-16 18:15:32.936  7013  7571 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:32.937  7013  7571 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif,
08-16 18:15:32.939  7013  7505 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 18:15:32.940  7013  7573 I bt_vendor: hw_epilog_process
,08-16 18:15:32.941  7013  7505 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 18:15:32.941  7013  7505 D bt_userial_mct: userial_close,
,08-16 18:15:32.941  7013  7505 E bt_userial_mct: pthread_join() FAILED result:3
08-16 18:15:32.941  7013  7505 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
,08-16 18:15:32.955  7013  7505 D bt_hci_bdroid: set_power 0
08-16 18:15:32.975  7013  7505 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 18:15:32.975  7013  7505 I bt_vendor: bluetooth satus is on
08-16 18:15:32.976  7013  7505 I bt_vendor: bt-vendor : resetting BT status,
,08-16 18:15:32.977  7013  7505 I bt_vendor: Starting hciattach daemon
08-16 18:15:32.977  7013  7505 I bt_vendor: try to set false
08-16 18:15:32.979  7013  7505 I bt_vendor: Starting hciattach daemon
08-16 18:15:32.979  7013  7505 I bt_vendor: try to set false
,08-16 18:15:32.981  7013  7505 I bt_vendor: cleanup
08-16 18:15:32.984  7013  7571 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 18:15:32.985  7013  7505 I GKI_LINUX: GKI_exit_task 0 done
08-16 18:15:32.985  7013  7505 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 18:15:32.987  7013  7501 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 18:15:32.993  7013  7013 D HeadsetService: Received stop request...Stopping profile...
,08-16 18:15:32.997  7013  7013 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 18:15:32.997  7013  7013 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:15:32.997  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:32.997  7013  7542 D HeadsetStateMachine: Exit Disconnected: -1
08-16 18:15:33.003  7013  7501 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 18:15:33.005  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:33.005  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 18:15:33.006  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:33.006  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-16 18:15:33.006  1852  1852 D BluetoothHeadset: Proxy object disconnected
,08-16 18:15:33.008  7013  7013 D A2dpService: Received stop request...Stopping profile...
08-16 18:15:33.010  7013  7555 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:15:33.012  7013  7013 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 18:15:33.013  7013  7013 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 18:15:33.013  7013  7013 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:15:33.013  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:33.016  7013  7013 D HidService: Received stop request...Stopping profile...
08-16 18:15:33.016  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:33.018  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:33.018  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 18:15:33.021  7013  7013 D HeadsetStateMachine: Unbinding service...
08-16 18:15:33.025  7013  7013 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:15:33.025  7013  7013 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:15:33.025  7013  7013 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:15:33.026  7013  7013 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:15:33.026  7013  7013 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 18:15:33.027  7013  7013 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:15:33.027  7013  7013 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 18:15:33.028  7013  7013 D HealthService: Received stop request...Stopping profile...
08-16 18:15:33.028  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:33.031  7013  7013 D PanService: Received stop request...Stopping profile...
,08-16 18:15:33.034  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:33.035  7013  7013 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:15:33.036  7013  7013 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 18:15:33.036  7013  7013 D BtGatt.GattService: stop()
08-16 18:15:33.036  7013  7013 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 18:15:33.037  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:33.038  7013  7013 D BluetoothMapService: Received stop request...Stopping profile...
08-16 18:15:33.039  7013  7013 D BluetoothMapService: stop()
08-16 18:15:33.039  7013  7013 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 18:15:33.039  7013  7013 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 18:15:33.041  7013  7013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@262342f
08-16 18:15:33.042  7013  7013 I BluetoothA2dpServiceJni: cleanupNative
08-16 18:15:33.043  7013  7556 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:15:33.043  7013  7013 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:15:33.043  7013  7013 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:15:33.043  7013  7013 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:15:33.043  7013  7013 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:15:33.044  7013  7013 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:15:33.044  7013  7013 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:15:33.044  7013  7013 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:15:33.044  7013  7013 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:15:33.044  7013  7013 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 18:15:33.048  7013  7013 V BluetoothMapService: Handler(): got msg=4
08-16 18:15:33.048  7013  7013 D BluetoothMapService: MAP Service closeService in
08-16 18:15:33.048  7013  7013 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:15:33.049  7013  7013 V BluetoothMapService: MAP Service closeService out
08-16 18:15:33.049  7013  7501 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:15:33.049  7013  7501 D BluetoothAdapterProperties: Setting state to 10
08-16 18:15:33.049  7013  7501 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:15:33.050  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:33.050  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 18:15:33.050  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 18:15:33.050  7013  7501 I BluetoothAdapterState: Entering OffState
08-16 18:15:33.051  7013  7013 D BluetoothMapService: cleanup()
08-16 18:15:33.051  7013  7013 D BluetoothMapService: MAP Service closeService in
08-16 18:15:33.051  7013  7013 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:15:33.051  7013  7013 V BluetoothMapService: MAP Service closeService out
08-16 18:15:33.053  6871  6888 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 18:15:33.055  6871  6888 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:15:33.055  6871  6888 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:15:33.056  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 18:15:33.059  1852  2448 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:33.060  1852  2458 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:33.060  6871  6888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:33.061  1033  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:15:33.061  6871  6888 D BluetoothPan: onBluetoothStateChange on: false
08-16 18:15:33.061  6871  6888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:15:33.062  1033  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:15:33.063  1033  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 18:15:33.063  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 18:15:33.065  1033  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 18:15:33.065  1033  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 18:15:33.065  1033  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1b18e475 mBinding = false
08-16 18:15:33.066  1033  1097 D BluetoothManagerService: Sending unbind request.
08-16 18:15:33.071  7013  7505 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 18:15:33.073  7013  7013 I GKI_LINUX: GKI_exit_task 1 done
08-16 18:15:33.073  7013  7013 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 18:15:33.074  7013  7013 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 18:15:33.074  7013  7013 I art     : --- WEIRD: removing null entry 248
08-16 18:15:33.074  7013  7013 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 18:15:33.075  7013  7013 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 18:15:33.075  7013  7013 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 18:15:33.076  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 18:15:33.079  7013  7013 I art     : System.exit called, status: 0
08-16 18:15:33.079  7013  7013 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 18:15:33.098   319  2160 V AudioFlinger: 7013 died, releasing its sessions
08-16 18:15:33.098   319  2160 V AudioFlinger:  pid 1852 @ 0
08-16 18:15:33.098   319  2160 V AudioFlinger:  pid 3502 @ 1
08-16 18:15:33.098   319  2160 V AudioFlinger:  pid 3502 @ 2
,08-16 18:15:33.102  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 18:15:33.102  1941  2139 D LGBluetoothAPIService: Message: 101
08-16 18:15:33.102  1941  2139 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 18:15:33.102  1941  2139 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 18:15:33.102  1941  2139 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 18:15:33.104  6871  6871 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 18:15:33.106  1033  1649 I ActivityManager: Process com.android.bluetooth (pid 7013) has died
08-16 18:15:33.106  1033  1649 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-16 18:15:33.106  1033  1649 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-16 18:15:33.112  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:33.115  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:15:33.115  1941  2139 D LGBluetoothAPIService: Message: 2
08-16 18:15:33.116  1941  2139 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 18:15:33.116  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:33.117  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:33.122  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 18:15:33.122  6871  6871 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 18:15:33.125  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 18:15:33.143  1602  1602 D BluetoothAdapter: 592452033: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:33.143  1602  1602 D BluetoothAdapter: 592452033: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:33.180  1033  1049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7753 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 18:15:33.182  6871  6871 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:33.224  7753  7753 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 18:15:33.225  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:33.225  7753  7753 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-16 18:15:33.225  7753  7753 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:33.240  7753  7753 D BluetoothAdapterApp: Loading JNI Library
,08-16 18:15:33.263  7753  7753 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1293d537 Instance Count = 1
,08-16 18:15:33.267  7753  7753 D BluetoothAdapterApp: onCreate
08-16 18:15:33.286  7753  7753 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-16 18:15:33.286  7753  7753 D ProfileConfigQcom: Adding HeadsetService
,08-16 18:15:33.287  7753  7753 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 18:15:33.287  7753  7753 D ProfileConfigQcom: Adding A2dpService
08-16 18:15:33.288  7753  7753 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 18:15:33.290  7753  7753 D ProfileConfigQcom: Adding HidService
08-16 18:15:33.291  7753  7753 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 18:15:33.291  7753  7753 D ProfileConfigQcom: Adding HealthService
08-16 18:15:33.292  7753  7753 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 18:15:33.293  7753  7753 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 18:15:33.294  7753  7753 D ProfileConfigQcom: Adding PanService
08-16 18:15:33.295  7753  7753 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 18:15:33.295  7753  7753 D ProfileConfigQcom: Adding GattService
08-16 18:15:33.296  7753  7753 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 18:15:33.296  7753  7753 D ProfileConfigQcom: Adding BluetoothMapService
08-16 18:15:33.297  7753  7753 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 18:15:33.299  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:33.301  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.302  7753  7753 V BluetoothPbapReceiver: ***********state = 10
08-16 18:15:33.306  7753  7753 V LGMDMManagerInternal: Create singleton instance
,08-16 18:15:33.392  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:33.394  7753  7753 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-16 18:15:33.395  7753  7753 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 18:15:33.399  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 18:15:33.399  1941  2139 D LGBluetoothAPIService: Message: 100
08-16 18:15:33.399  1941  2139 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 18:15:33.401  6871  6871 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 18:15:33.413  6871  6871 D BluetoothPermissionRequest: onReceive
,08-16 18:15:33.415  6871  6871 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:15:33.415  6871  6871 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 18:15:33.418  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:15:33.421  7753  7753 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 18:15:33.426  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.429  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:33.429  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:33.429  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:33.430  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.430  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 18:15:33.440  7578  7578 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 18:15:35.024  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:15:35.024  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:35.365  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 18:15:35.421  1033  1033 D administrator: Handling package changes for user 0
,08-16 18:15:35.455  1033  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7783 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 18:15:35.477  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 18:15:35.478  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 18:15:35.485  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-16 18:15:35.495  1033  1497 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 18:15:35.527  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 18:15:35.563  7783  7783 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 18:15:35.609  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 18:15:35.610  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 18:15:35.632  7783  7783 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:35.632  7783  7783 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:35.662  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:35.669  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 18:15:35.676  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 18:15:35.678  2500  2500 V GmsNetworkLocationProvi: DISABLE
,08-16 18:15:35.703  1033  1090 D LocationProviderProxy: applying state to connected service
,08-16 18:15:35.705  2500  2500 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 18:15:35.768  7783  7828 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 18:15:35.768  7783  7828 I Babel   : MmsConfig.loadMmsSettings
,08-16 18:15:35.770  7783  7828 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 18:15:35.771  7783  7828 I Babel   : MmsConfig.loadFromDatabase
,08-16 18:15:35.804  7783  7828 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 18:15:35.804  7783  7828 I Babel   : MmsConfig.loadFromResources
08-16 18:15:35.806  7783  7828 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 18:15:35.806  7783  7828 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 18:15:35.813  7783  7783 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:35.833  1817  7830 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 18:15:35.833  1817  7830 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 18:15:35.838  7084  7084 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:15:35.838  7783  7827 W AudioCapabilities: Unsupported mime audio/evrc
08-16 18:15:35.840  7783  7827 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 18:15:35.842  7084  7084 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@21a33009
08-16 18:15:35.842  7084  7084 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:15:35.842  7084  7084 D AppUp4:CustFacade: isPhone : true
08-16 18:15:35.842  7084  7084 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:15:35.842  7084  7084 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 18:15:35.846  1817  4768 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 18:15:35.849  7783  7827 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 18:15:35.861  7783  7827 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 18:15:35.865  7783  7827 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 18:15:35.867  7783  7827 W AudioCapabilities: Unsupported mime audio/evrc
08-16 18:15:35.875  7783  7827 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 18:15:35.877  7783  7827 W VideoCapabilities: Unsupported mime video/divx
08-16 18:15:35.879  7783  7827 W VideoCapabilities: Unsupported mime video/divx311
08-16 18:15:35.880  7783  7827 W VideoCapabilities: Unsupported mime video/divx4
08-16 18:15:35.886  7783  7827 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 18:15:35.888  1033  1990 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7834 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 18:15:35.896  1033  1649 I ActivityManager: Killing 7411:com.lge.sync/1000 (adj 15): empty #17
08-16 18:15:35.909   345   345 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 356us total 18.545ms
,08-16 18:15:35.919  1033  1543 D WifiService: Client connection lost with reason: 4
08-16 18:15:35.925   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 15.529ms
,08-16 18:15:35.925  7783  7827 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 18:15:35.933  7783  7827 W AudioCapabilities: Unsupported mime audio/eac3
08-16 18:15:35.934  7783  7827 W AudioCapabilities: Unsupported mime audio/ac3
08-16 18:15:35.935  7783  7827 W AudioCapabilities: Unsupported mime audio/g726
08-16 18:15:35.936  7783  7827 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 18:15:35.937  7783  7827 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 18:15:35.938  7783  7827 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 18:15:35.938   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 12.980ms
08-16 18:15:35.940  7783  7827 W VideoCapabilities: Unsupported mime video/theora
08-16 18:15:35.942  7783  7827 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 18:15:36.014  1033  1932 W libprocessgroup: failed to open /acct/uid_1000/pid_7411/cgroup.procs: No such file or directory
,08-16 18:15:36.065  7834  7834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:36.066  7834  7834 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:36.066  7834  7834 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 18:15:36.067  7834  7834 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 18:15:36.068  7834  7834 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 18:15:36.182  7834  7834 I SystemConfig: BUILD Country: EU
,08-16 18:15:36.182  7834  7834 I SystemConfig: BUILD Operator: OPEN
08-16 18:15:36.251  1033  1996 I ActivityManager: Killing 7111:com.lge.email/u0a23 (adj 15): empty #17
,08-16 18:15:36.348  1033  1966 W libprocessgroup: failed to open /acct/uid_10023/pid_7111/cgroup.procs: No such file or directory
,08-16 18:15:36.356  1033  1426 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27d2a964 type 2 when 130936 com.google.android.gms} when 130936
08-16 18:15:36.361  7834  7855 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 18:15:36.361  7834  7855 I SystemConfig: existFile = false
08-16 18:15:36.361  7834  7855 I SystemConfig: canReadFile = false
08-16 18:15:36.363  7834  7855 I SystemConfig: systemFeature RCS result false
,08-16 18:15:36.363  7834  7855 D SystemConfig: refreshRcsSupport() :false
08-16 18:15:36.433  1033  1996 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7857 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 18:15:36.516  7857  7857 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:36.516  7857  7857 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 18:15:36.517  7857  7857 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 18:15:36.517  7857  7857 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 18:15:36.621  7857  7857 I AppConfig: Total System Memory = 2995761152
,08-16 18:15:36.632  7857  7857 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 18:15:36.720  1033  1887 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7876 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:36.722  1033  1887 I ActivityManager: Killing 6960:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 18:15:36.777  1033  1049 W libprocessgroup: failed to open /acct/uid_10026/pid_6960/cgroup.procs: No such file or directory
08-16 18:15:36.975  7876  7876 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 18:15:37.063  7876  7876 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:37.063  7876  7876 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:37.110  7876  7876 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 18:15:37.135  7876  7876 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 18:15:37.137  7876  7876 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 18:15:37.156  7876  7876 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:37.156  7876  7876 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-16 18:15:37.178  1033  1782 I ActivityManager: Killing 6494:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 18:15:37.237  1033  1921 W libprocessgroup: failed to open /acct/uid_1000/pid_6494/cgroup.procs: No such file or directory
,08-16 18:15:37.240  3538  3553 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 18:15:37.242  3538  3553 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c3a8d34 on behalf of 7876
08-16 18:15:37.248  4593  7913 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 18:15:37.310  1033  1050 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7914 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:37.343  7876  7876 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 18:15:37.365  7876  7876 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 18:15:37.422  7914  7914 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 18:15:37.447  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 18:15:37.447  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 18:15:37.447  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 18:15:37.447  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 18:15:37.447  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 18:15:37.448  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 18:15:37.464   315  7936 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 18:15:37.464  1033  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 18:15:37.506  1033  1996 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7937 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 18:15:37.511  1033  1782 I ActivityManager: Killing 7152:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 18:15:37.546  1033  1575 W libprocessgroup: failed to open /acct/uid_10046/pid_7152/cgroup.procs: No such file or directory
,08-16 18:15:37.574  7684  7727 D UEI.SmartControl: Internal timer expired: 1
08-16 18:15:37.575  7684  7727 D UEI.SmartControl: unbind internal service
,08-16 18:15:37.576  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:37.578  7684  7684 D UEI.SmartControl: Service.onUnbind: IControl
08-16 18:15:37.580  7684  7684 D UEI.SmartControl: Service.onDestroy
08-16 18:15:37.580  7684  7684 D UEI.SmartControl: Lock is in USE false
08-16 18:15:37.580  7684  7684 D UEI.SmartControl: unbind internal service
08-16 18:15:37.580  7684  7684 D serial_port: close(fd = 25)
08-16 18:15:37.584  7684  7684 I UEI.SmartControl: Serial port is closed.
08-16 18:15:37.584  7684  7684 I UEI.SmartControl: Serial port is closed.
08-16 18:15:37.585  7684  7684 D UEI.SmartControl: Blaster closed
08-16 18:15:37.585  7684  7684 D UEI.SmartControl: Shut down QS...
08-16 18:15:37.585  7684  7684 D UEI.SmartControl: Stopping QS lib
08-16 18:15:37.585  7684  7684 D UEI.SmartControl: QS lib stop result = true
08-16 18:15:37.585  7684  7684 D UEI.SmartControl: Stopped QS lib
08-16 18:15:37.586  7684  7684 D UEI.SmartControl: Stopped file observer...
08-16 18:15:37.586  7684  7684 D UEI.SmartControl: QS shutdown complete
,08-16 18:15:37.622  7937  7937 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 18:15:37.664  7937  7937 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 18:15:37.665  7937  7937 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 18:15:37.665  7937  7937 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 18:15:37.666  7937  7937 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 18:15:37.666  7937  7937 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 18:15:37.667  1033  1050 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:37.668  7937  7937 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 18:15:37.675  7937  7937 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 18:15:37.683  7937  7937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 18:15:37.684  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3911
,08-16 18:15:37.689  7937  7937 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 18:15:37.691  4593  7913 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 443 ms] updated apps [took 443 ms] 
08-16 18:15:37.696  7937  7937 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 18:15:37.697  7937  7937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 18:15:37.698  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 18:15:37.698  7937  7937 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-16 18:15:37.736  7937  7937 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:37.737  7937  7937 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:37.745  7937  7937 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 18:15:37.747  7937  7937 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 18:15:37.747  7937  7937 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 18:15:37.747  7937  7937 V SoundPool: doLoad: loading sample sampleID=1
08-16 18:15:37.747  7937  7937 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 18:15:37.751  7937  7957 V SoundPool: Start decode
08-16 18:15:37.751  7937  7957 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-16 18:15:37.752  7684  7684 D UEI.SmartControl: QS Service created
08-16 18:15:37.752   319  2159 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 18:15:37.753   319  2159 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 18:15:37.753   319  2159 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 18:15:37.753   319  2159 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 18:15:37.753   319  2159 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 18:15:37.753   319  2159 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 18:15:37.753   319  2159 V MediaPlayerService: player type = 3
08-16 18:15:37.753   319  2159 V AwesomePlayer: AwesomePlayer create()
08-16 18:15:37.756   319  2159 V AwesomePlayer: reset_l() 
08-16 18:15:37.756   319  2159 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:37.756   319  2159 V AwesomePlayer: setAudioSink() 
08-16 18:15:37.756   319  2159 V AwesomePlayer: reset_l() 
08-16 18:15:37.756   319  2159 V AudioCache: notify(0xb57c9140, 8, 0, 0)
08-16 18:15:37.757   319  2159 V AudioCache: ignored
08-16 18:15:37.757   319  2159 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:37.757   319  2159 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 18:15:37.757   319  2159 V AwesomePlayer: setDataSource_l dataSource
08-16 18:15:37.758   319  2159 V LGParserOSAL: SniffLGParser start
08-16 18:15:37.758   319  2159 V LGParserOSAL: MainType:5, SubType=0
08-16 18:15:37.758   319  2159 V LGParserOSAL: #### check Mime : application/ogg
08-16 18:15:37.758   319  2159 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 18:15:37.758   319  2159 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 18:15:37.760  7937  7937 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 18:15:37.763  7937  7937 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 18:15:37.764  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 18:15:37.766  7684  7684 I UEI.SmartControl: Service initServices...
08-16 18:15:37.767  7684  7684 D UEI.SmartControl: QS start get config
08-16 18:15:37.787  7937  7937 V LGMDMManager: Create singleton instance
,08-16 18:15:37.817   319  2159 V LGParserOSAL: supported mime: application/ogg
08-16 18:15:37.817   319  2159 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 18:15:37.817   319  2159 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-16 18:15:37.817   319  2159 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 18:15:37.817   319  2159 V AwesomePlayer: AudioTrack Setting
08-16 18:15:37.817   319  2159 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 18:15:37.817   319  2159 V AwesomePlayer: setAudioSource() 
08-16 18:15:37.817   319  2159 V MediaPlayerService: prepare
08-16 18:15:37.817   319  2159 V AwesomePlayer: prepareAsync_l() 
08-16 18:15:37.818   319  2159 V MediaPlayerService: wait for prepare
08-16 18:15:37.821   319  7958 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 18:15:37.821   319  7958 V AwesomePlayer: initAudioDecoder() 
08-16 18:15:37.821   319  7958 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 18:15:37.821   319  7958 V AudioSystem: isOffloadSupported()
08-16 18:15:37.821   319  7958 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 18:15:37.821   319  7958 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 18:15:37.821   319  7958 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 18:15:37.821   319  7958 V AwesomePlayer: getUseOffload() = 0 
08-16 18:15:37.821   319  7958 V OMXCodec: OMXCodec::Create
08-16 18:15:37.821   319  7958 V OMXCodec: findMatchingCodecs()
08-16 18:15:37.821   319  7958 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 18:15:37.821   319  7958 V OMXCodec: matchingCodecs.size()=1
08-16 18:15:37.821   319  7958 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 18:15:37.823   319  7958 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 18:15:37.823   319  7958 V LGCodecAdapter: LG Codec Adapter start
08-16 18:15:37.823   319  7958 V OMXCodec: OMXCodec Createtor
08-16 18:15:37.823   319  7958 V OMXCodec: setComponentRole
08-16 18:15:37.824   319  7958 V OMXCodec: configureCodec protected=0
08-16 18:15:37.824   319  7958 V LGCodecAdapter: called getLGCodecSpecificData
08-16 18:15:37.824   319  7958 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 18:15:37.824   319  7958 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 18:15:37.824   319  7958 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 18:15:37.824   319  7958 V LGCodecOSAL: Not support LGCodec
08-16 18:15:37.824   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 18:15:37.824   319  7958 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 18:15:37.824   319  7958 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 18:15:37.824   319  7958 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 18:15:37.824   319  7958 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 18:15:37.824   319  7958 V AudioSystem: isOffloadSupported()
08-16 18:15:37.824   319  7958 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 18:15:37.824   319  7958 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 18:15:37.824   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 18:15:37.824   319  7958 V OMXCodec: init()
08-16 18:15:37.824   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 18:15:37.824   319  7958 V OMXCodec: allocateBuffers
08-16 18:15:37.824   319  7958 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 18:15:37.824   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on, input port
08-16 18:15:37.824   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 18:15:37.825   319  7958 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 18:15:37.825   319  7958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-16 18:15:37.825   319  7958 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 18:15:37.826   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 18:15:37.826   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 18:15:37.827   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 18:15:37.827   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 18:15:37.827   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 18:15:37.827   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 18:15:37.827   319  7958 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 18:15:37.827   319  7958 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 18:15:37.827   319  7958 V AudioCache: notify(0xb57c9140, 5, 0, 0)
08-16 18:15:37.827   319  7958 V AudioCache: ignored
08-16 18:15:37.827   319  7958 V AudioCache: notify(0xb57c9140, 1, 0, 0)
08-16 18:15:37.827   319  7958 V AudioCache: prepared
08-16 18:15:37.827   319  2159 V AudioCache: wait - success
08-16 18:15:37.827   319  2159 V MediaPlayerService: start
08-16 18:15:37.827   319  2159 V AwesomePlayer: play_l() 
08-16 18:15:37.827   319  2159 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 18:15:37.827   319  2159 V AwesomePlayer: createAudioPlayer_l
08-16 18:15:37.827   319  2159 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 18:15:37.827   319  2159 V AwesomePlayer: startAudioPlayer_l() 
08-16 18:15:37.827   319  2159 D AudioPlayer: start of Playback, useOffload 0
08-16 18:15:37.827   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 18:15:37.829   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google,.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 18:15:37.832   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 18:15:37.832   319  7960 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9880 on output port
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 18:15:37.833   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 18:15:37.842   319  2159 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 18:15:37.842   319  2159 V AudioCache: notify(0xb57c9140, 6, 0, 0)
08-16 18:15:37.842   319  2159 V AudioCache: ignored
08-16 18:15:37.843   319  2159 V MediaPlayerService: wait for playback complete
08-16 18:15:37.844   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.844   319  7965 V AudioCache: memcpy(0xac300000, 0xb16af000, 4096)
08-16 18:15:37.846   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.846   319  7965 V AudioCache: memcpy(0xac301000, 0xb16af000, 4096)
08-16 18:15:37.847   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.847   319  7965 V AudioCache: memcpy(0xac302000, 0xb16af000, 4096)
08-16 18:15:37.848   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.848   319  7965 V AudioCache: memcpy(0xac303000, 0xb16af000, 4096)
08-16 18:15:37.848   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.848   319  7965 V AudioCache: memcpy(0xac304000, 0xb16af000, 4096)
08-16 18:15:37.849   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.849   319  7965 V AudioCache: memcpy(0xac305000, 0xb16af000, 4096)
08-16 18:15:37.850   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.850   319  7965 V AudioCache: memcpy(0xac306000, 0xb16af000, 4096)
08-16 18:15:37.850   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.850   319  7965 V AudioCache: memcpy(0xac307000, 0xb16af000, 4096)
08-16 18:15:37.851   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.851   319  7965 V AudioCache: memcpy(0xac308000, 0xb16af000, 4096)
08-16 18:15:37.852   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.852   319  7965 V AudioCache: memcpy(0xac309000, 0xb16af000, 4096)
08-16 18:15:37.853   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.853   319  7965 V AudioCache: memcpy(0xac30a000, 0xb16af000, 4096)
08-16 18:15:37.853   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.853   319  7965 V AudioCache: memcpy(0xac30b000, 0xb16af000, 4096)
08-16 18:15:37.854   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.854   319  7965 V AudioCache: memcpy(0xac30c000, 0xb16af000, 4096)
08-16 18:15:37.855   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.855   319  7965 V AudioCache: memcpy(0xac30d000, 0xb16af000, 4096)
08-16 18:15:37.856   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.856   319  7965 V AudioCache: memcpy(0xac30e000, 0xb16af000, 4096)
08-16 18:15:37.856   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.856   319  7965 V AudioCache: memcpy(0xac30f000, 0xb16af000, 4096)
08-16 18:15:37.857   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.857   319  7965 V AudioCache: memcpy(0xac310000, 0xb16af000, 4096)
08-16 18:15:37.858   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.858   319  7965 V AudioCache: memcpy(0xac311000, 0xb16af000, 4096)
08-16 18:15:37.859   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.859   319  7965 V AudioCache: memcpy(0xac312000, 0xb16af000, 4096)
08-16 18:15:37.860   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.860   319  7965 V AudioCache: memcpy(0xac313000, 0xb16af000, 4096)
08-16 18:15:37.860   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.860   319  7965 V AudioCache: memcpy(0xac314000, 0xb16af000, 4096)
08-16 18:15:37.861   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.861   319  7965 V AudioCache: memcpy(0xac315000, 0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: memcpy(0xac316000, 0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: memcpy(0xac317000, 0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: memcpy(0xac318000, 0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.862   319  7965 V AudioCache: memcpy(0xac319000, 0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: memcpy(0xac31a000, 0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: memcpy(0xac31b000, 0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: memcpy(0xac31c000, 0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.864   319  7965 V AudioCache: memcpy(0xac31d000, 0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: memcpy(0xac31e000, 0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: memcpy(0xac31f000, 0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: memcpy(0xac320000, 0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: memcpy(0xac321000, 0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.866   319  7965 V AudioCache: memcpy(0xac322000, 0xb16af000, 4096)
08-16 18:15:37.867   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.867   319  7965 V AudioCache: memcpy(0xac323000, 0xb16af000, 4096)
08-16 18:15:37.867   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.867   319  7965 V AudioCache: memcpy(0xac324000, 0xb16af000, 4096)
08-16 18:15:37.868   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.868   319  7965 V AudioCache: memcpy(0xac325000, 0xb16af000, 4096)
08-16 18:15:37.869   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.869   319  7965 V AudioCache: memcpy(0xac326000, 0xb16af000, 4096)
,08-16 18:15:37.869   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.869   319  7965 V AudioCache: memcpy(0xac327000, 0xb16af000, 4096)
08-16 18:15:37.870   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.870   319  7965 V AudioCache: memcpy(0xac328000, 0xb16af000, 4096)
08-16 18:15:37.871   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.871   319  7965 V AudioCache: memcpy(0xac329000, 0xb16af000, 4096)
08-16 18:15:37.872   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.872   319  7965 V AudioCache: memcpy(0xac32a000, 0xb16af000, 4096)
08-16 18:15:37.873  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 18:15:37.874   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.874   319  7965 V AudioCache: memcpy(0xac32b000, 0xb16af000, 4096)
08-16 18:15:37.874   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.874   319  7965 V AudioCache: memcpy(0xac32c000, 0xb16af000, 4096)
08-16 18:15:37.875   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.875   319  7965 V AudioCache: memcpy(0xac32d000, 0xb16af000, 4096)
08-16 18:15:37.875   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.875   319  7965 V AudioCache: memcpy(0xac32e000, 0xb16af000, 4096)
08-16 18:15:37.875   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.875   319  7965 V AudioCache: memcpy(0xac32f000, 0xb16af000, 4096)
08-16 18:15:37.875  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 18:15:37.876   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 18:15:37.876   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.876   319  7965 V AudioCache: memcpy(0xac330000, 0xb16af000, 4096)
08-16 18:15:37.876   319  7965 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:15:37.876   319  7965 V AudioCache: write(0xb16af000, 4096)
08-16 18:15:37.876   319  7965 V AudioCache: memcpy(0xac331000, 0xb16af000, 4096)
08-16 18:15:37.876   319  7965 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:15:37.876   319  7965 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:15:37.876   319  7965 V AwesomePlayer: postAudioEOS() 
08-16 18:15:37.876   319  7965 V AudioCache: write(0xb16af000, 280)
08-16 18:15:37.876   319  7965 V AudioCache: memcpy(0xac332000, 0xb16af000, 280)
08-16 18:15:37.877   319  7958 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 18:15:37.877   319  7958 V AwesomePlayer: onStreamDone
08-16 18:15:37.877   319  7958 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 18:15:37.877   319  7958 V AudioCache: notify(0xb57c9140, 2, 0, 0)
08-16 18:15:37.877   319  7958 V AudioCache: playback complete
08-16 18:15:37.877   319  7958 V AwesomePlayer: pause_l() 
08-16 18:15:37.877   319  7958 V AudioCache: notify(0xb57c9140, 7, 0, 0)
08-16 18:15:37.877   319  7958 V AudioCache: ignored
08-16 18:15:37.877   319  7958 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:37.877   319  2159 V AudioCache: wait - success
08-16 18:15:37.877  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:813
08-16 18:15:37.878   319  2159 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 18:15:37.878   319  7958 D AudioPlayer: Pause Playback at 1068125
08-16 18:15:37.879   319  2159 V AwesomePlayer: reset_l() 
08-16 18:15:37.879   319  2159 V AudioCache: notify(0xb57c9140, 8, 0, 0)
08-16 18:15:37.879   319  2159 V AudioCache: ignored
08-16 18:15:37.879   319  2159 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:37.879   319  2159 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 18:15:37.879   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 18:15:37.879   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 18:15:37.879   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 18:15:37.879   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 18:15:37.879   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 18:15:37.879   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 18:15:37.879   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 18:15:37.879   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 18:15:37.879   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f9880 on port 1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:15:37.880   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 18:15:37.881   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 18:15:37.881   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 18:15:37.881   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 18:15:37.881   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 18:15:37.881   319  7960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 18:15:37.881   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 18:15:37.881   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 18:15:37.881   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 18:15:37.882   319  2159 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 18:15:37.882   319  2159 D AudioPlayer: AudioPlayer releasing audio source
08-16 18:15:37.882   319  2159 D AudioPlayer: AudioPlayer done releasing audio source
08-16 18:15:37.882   319  2159 V AwesomePlayer: reset_l() 
08-16 18:15:37.882   319  2159 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:37.882   319  2159 V AwesomePlayer: ~AwesomePlayer call
08-16 18:15:37.883   319  2159 V AwesomePlayer: reset_l() 
08-16 18:15:37.883   319  2159 V AwesomePlayer: cancelPlayerEvents
08-16 18:15:37.883  7937  7957 V SoundPool: close(31)
08-16 18:15:37.883  7937  7957 V SoundPool: pointer = 0x9fe4c000, size = 205080, sampleRate = 48000, numChannels = 2
,08-16 18:15:38.040  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:38.040  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34bdd1b1 added. We now have 6 listener(s)
08-16 18:15:38.040  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:38.044  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:38.044  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a9c6696 added. We now have 7 listener(s)
08-16 18:15:38.044  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:38.052  6680  6791 I System.out: IsBluetoothEnabled
08-16 18:15:38.053  1033  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:38.053  1033  1990 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-16 18:15:38.054  1033  1097 D BluetoothManagerService: Message: 2
08-16 18:15:38.060  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:38.060  1033  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:38.060  1033  1575 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 18:15:38.084  7684  7684 I UEI.SmartControl: Supports setup maps: true
08-16 18:15:38.087  7684  7684 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 18:15:38.087  7684  7684 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 18:15:38.087  7684  7684 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 18:15:38.087  7684  7684 I UEI.SmartControl: ### init IR Blaster...
,08-16 18:15:38.089  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:38.089  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:38.089  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:38.090  7684  7684 D serial_port: Configuring serial port
08-16 18:15:38.091  7684  7684 E UEI.SmartControl: UEIBLaster setting for 616
08-16 18:15:38.091  7684  7684 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 18:15:38.091  7684  7684 I UEI.SmartControl: configuring settings for MAXQ616
08-16 18:15:38.091  7684  7684 I UEI.SmartControl: Get version...
08-16 18:15:38.091  1033  1097 D BluetoothManagerService: Message: 1
08-16 18:15:38.091  1033  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 18:15:38.105  7684  7970 D UEI.SmartControl: serial port data available: 21
,08-16 18:15:38.120  1033  1097 D BluetoothManagerService: Message: 20
,08-16 18:15:38.120  1033  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@193f9fe2:true
,08-16 18:15:38.121  7753  7753 D BluetoothAdapterState: make
,08-16 18:15:38.126  7753  7753 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
,08-16 18:15:38.127  7753  7972 I BluetoothAdapterState: Entering OffState
,08-16 18:15:38.128  7753  7753 I bluedroid-qcom: init
08-16 18:15:38.128  7753  7753 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 18:15:38.129  7753  7753 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 18:15:38.129  7753  7753 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 18:15:38.129  7753  7753 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 18:15:38.129  7753  7753 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 18:15:38.129  7753  7753 I bluedroid-qcom: get_profile_interface socket
08-16 18:15:38.129  7753  7753 I bluedroid-qcom: get_profile_interface map_client
08-16 18:15:38.129  7753  7975 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 18:15:38.114  7976  7976 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:38.114  7976  7976 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:38.133  7684  7684 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 18:15:38.133  7684  7684 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 18:15:38.133  7684  7684 I UEI.SmartControl: QS saving settings...
08-16 18:15:38.134  7684  7684 D UEI.SmartControl: IR Blaster version: 25672567
08-16 18:15:38.137  7753  7975 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 18:15:38.139  7976  7976 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 18:15:38.139  7976  7976 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 18:15:38.139  7976  7976 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 18:15:38.140  7976  7976 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 18:15:38.140  7753  7975 D BluetoothAdapterProperties: Name is: G3
08-16 18:15:38.140  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:15:38.140  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 18:15:38.141  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 18:15:38.141  1033  1097 D BluetoothManagerService: Message: 40
08-16 18:15:38.141  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 18:15:38.141  7753  7769 I bluedroid-qcom: config_hci_snoop_log
,08-16 18:15:38.142  1033  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 18:15:38.142  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 18:15:38.144  7976  7976 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 18:15:38.144  7976  7976 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 18:15:38.148  7753  7972 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 18:15:38.148  7753  7972 D BluetoothAdapterProperties: Setting state to 11
08-16 18:15:38.148  7753  7972 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:15:38.149  7753  7972 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 18:15:38.152  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:38.152  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 18:15:38.152  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 18:15:38.154  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:38.155  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 18:15:38.155  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:15:38.157  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:38.158  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:38.158  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:38.158  7753  7753 V BluetoothPbapReceiver: ***********state = 11
08-16 18:15:38.159  7684  7970 D UEI.SmartControl: serial port data available: 4
08-16 18:15:38.159  7753  7972 D BluetoothBondStateMachine: make
08-16 18:15:38.161  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:38.163  7753  7972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:38.163  7753  7972 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 18:15:38.163  7753  7972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:38.163  7753  7972 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 18:15:38.164  7753  7972 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 18:15:38.164  7753  7979 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 18:15:38.167  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:15:38.177  7753  7753 D HeadsetService: Received start request. Starting profile...
08-16 18:15:38.178  7753  7753 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:15:38.178  7753  7753 D LGBluetoothHfpAdapter: Version 1.6
08-16 18:15:38.179  6871  6871 D BluetoothPermissionRequest: onReceive
08-16 18:15:38.179  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:38.181  7753  7753 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 18:15:38.182  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:15:38.182  7753  7753 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:15:38.183  7753  7753 D HeadsetStateMachine: make
08-16 18:15:38.186  7684  7982 I UEI.SmartControl: Device manager: loading config....
08-16 18:15:38.187  7684  7982 D UEI.SmartControl: ----------- loading internal config...
08-16 18:15:38.190  7684  7684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 18:15:38.191  7684  7982 E UEI.SmartControl: Loading SETTINGS...
08-16 18:15:38.191  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:38.192  7684  7684 E UEI.SmartControl: Services init done
08-16 18:15:38.192  7684  7684 D UEI.SmartControl: QS Service init finished
08-16 18:15:38.193  7684  7684 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 18:15:38.193  7684  7684 D UEI.SmartControl: QS Service version code: 201091
08-16 18:15:38.193  7684  7684 D UEI.SmartControl: Service requested: Control
,08-16 18:15:38.196  7684  7982 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 18:15:38.197  7937  7937 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 18:15:38.197  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:38.197  7684  7699 I UEI.SmartControl: ------ IControl API: 11
08-16 18:15:38.198  7684  7699 D UEI.SmartControl: File observer start...
08-16 18:15:38.198  7684  7699 E UEI.SmartControl: IR Port is disabled: false
08-16 18:15:38.198  7684  7699 D UEI.SmartControl: Starting file observer...
08-16 18:15:38.199  7684  7699 I UEI.SmartControl: Registering callback...
08-16 18:15:38.202  7684  7700 I UEI.SmartControl: ------ IControl API: 19
08-16 18:15:38.203  7684  7700 I UEI.SmartControl: Registering Services Ready callback...
08-16 18:15:38.203  7684  7700 I UEI.SmartControl: Notify client services are ready...
08-16 18:15:38.204  7937  7952 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 18:15:38.204  7937  7955 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 18:15:38.204  7937  7955 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 18:15:38.204  7937  7937 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 18:15:38.205  7684  7684 D UEI.SmartControl: Internal service binding...
08-16 18:15:38.205  7937  7937 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 18:15:38.205  7684  7700 I UEI.SmartControl: ------ IControl API: 8
08-16 18:15:38.205  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:38.205  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:38.206  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:38.206  7684  7981 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 18:15:38.207  7937  7953 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 18:15:38.207  7684  7981 D UEI.SmartControl: -----service ready thread exits
08-16 18:15:38.209  7753  7753 D HeadsetStateMachine: max_hf_connections = 1
08-16 18:15:38.209  7753  7753 I bluedroid-qcom: get_profile_interface handsfree
08-16 18:15:38.209  7937  7955 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 18:15:38.209  7937  7955 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 18:15:38.209  7937  7937 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 18:15:38.209  7937  7937 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 18:15:38.209  7937  7937 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 18:15:38.210  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:38.210  7937  7937 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 18:15:38.210  7753  7753 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 18:15:38.210  7937  7937 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 18:15:38.210   319  1382 V AudioPolicyService: registerClient() client 0xb558a260, uid 1002
08-16 18:15:38.211   319   319 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 18:15:38.211   319   319 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:15:38.211   319   319 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:15:38.211  7937  7937 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 18:15:38.211  7753  7753 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 18:15:38.211   319  1383 V AudioFlinger: registerClient() client 0xb101fd78, pid 7753
08-16 18:15:38.212  7753  7753 V ToneGenerator: Create Track: 0xb4928a80
08-16 18:15:38.212  7753  7753 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 18:15:38.212  7753  7753 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 18:15:38.212   319  2159 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:15:38.212   319  2159 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 18:15:38.212   319  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:15:38.212   319  2159 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:15:38.212  7753  7753 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 18:15:38.213   319  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:38.213   319  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:38.213  7937  7937 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 18:15:38.213   319  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:38.213   319  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:38.213  7753  7769 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:38.213  7753  7769 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 18:15:38.213   ,319  2159 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 18:15:38.213   319  2160 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:15:38.213   319  2160 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 18:15:38.213   319  2160 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:15:38.213   319  2160 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:15:38.214  1033  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:38.214  1033  1575 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:38.214  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:38.214  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:38.214  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:38.214  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:38.214  3502  3518 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:15:38.214  3502  3518 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:15:38.214  1602  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:38.214  1602  2099 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:38.214  1033  1990 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:38.214  1033  1990 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:38.214  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:38.214  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:38.214  3502  3517 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:38.214  3502  3517 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:15:38.214  7753  7769 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:15:38.214  7753  7769 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 18:15:38.214  7753  7753 V AudioSystem: getLatency() output 2, latency 50
08-16 18:15:38.214  7753  7753 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 18:15:38.214  7753  7753 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 18:15:38.214   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:15:38.214   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 18:15:38.214   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:15:38.214   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-16 18:15:38.214   319   319 V AudioFlinger: createTrack() lSessionId: 23
08-16 18:15:38.215  7753  7753 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 18:15:38.215   319   319 V AudioFlinger: acquiring 23 from 7753, for 7753
08-16 18:15:38.215   319   319 V AudioFlinger:  added new entry for 23
08-16 18:15:38.215  7753  7753 V ToneGenerator: ToneGenerator INIT OK, time: 132843
08-16 18:15:38.215  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:38.215  7937  7937 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-16 18:15:38.216  7753  7980 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 18:15:38.216  7753  7980 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:15:38.216  7753  7980 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:15:38.217  7753  7980 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected,
08-16 18:15:38.217  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:38.219  7753  7753 D A2dpService: Received start request. Starting profile...
,08-16 18:15:38.219   319  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7753
08-16 18:15:38.219   319  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 18:15:38.219   319  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 18:15:38.219   319  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 18:15:38.219   319  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
,08-16 18:15:38.219   319  1383 V voice   : voice_set_parameters: exit with code(0)
08-16 18:15:38.219   319  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 18:15:38.219   319  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 18:15:38.219  7753  7753 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 18:15:38.219  7937  7937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 18:15:38.219   319  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 18:15:38.219   319  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 18:15:38.219   319  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 18:15:38.219   319  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 18:15:38.220  7753  7980 V ToneGenerator: ToneGenerator destructor
08-16 18:15:38.220  7753  7980 V ToneGenerator: stopTone
08-16 18:15:38.220  7753  7980 V ToneGenerator: Delete Track: 0xb4928a80
08-16 18:15:38.220  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 18:15:38.220  7753  7753 V Avrcp   : make
08-16 18:15:38.221  7753  7753 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 18:15:38.221  7753  7753 I bluedroid-qcom: get_profile_interface avrcp
08-16 18:15:38.221  7753  7980 V AudioTrack: ~AudioTrack, releasing session id from 7753 on behalf of 7753
08-16 18:15:38.221   319  2159 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 18:15:38.221   319  2159 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 18:15:38.221   319  2159 V AudioFlinger: PlaybackThread::Track destructor
08-16 18:15:38.221   319  2159 V AudioFlinger: removeClient_l() pid 7753, calling pid 319
08-16 18:15:38.221   319  1258 V AudioPolicyService: AudioCommandThread() waking up
,08-16 18:15:38.221   319  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 18:15:38.221   319  2159 V AudioFlinger: releasing 23 from 7753 for 7753
08-16 18:15:38.221   319  2159 V AudioFlinger:  decremented refcount to 0
08-16 18:15:38.221   319  1258 V AudioPolicyManager: releaseOutput() 2
08-16 18:15:38.221   319  2159 V AudioFlinger: purging stale effects
08-16 18:15:38.221   319  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 18:15:38.223  7753  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:15:38.223  7937  7937 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:15:38.224  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 18:15:38.224  1033  1966 W Process : Unable to open /proc/7984/status
08-16 18:15:38.224  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 18:15:38.227  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 18:15:38.228  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 18:15:38.229  7937  7937 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471364138228]
,08-16 18:15:38.233  7753  7753 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 18:15:38.235  7753  7753 E AudioManager: No RCC entry present to update
08-16 18:15:38.235  7753  7753 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 18:15:38.235  7937  7937 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 18:15:38.236  1033  1886 I ActivityManager: Killing 7172:com.android.chrome/u0a57 (adj 15): empty #17
08-16 18:15:38.237  7753  7753 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 18:15:38.238  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 18:15:38.238  7753  7753 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 18:15:38.243  7753  7972 V LGMDMManager: Create singleton instance
08-16 18:15:38.245  7753  7972 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 18:15:38.249  7937  7986 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-16 18:15:38.274  1033  2050 W libprocessgroup: failed to open /acct/uid_10057/pid_7172/cgroup.procs: No such file or directory
,08-16 18:15:38.277  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 18:15:38.277  7937  7937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 18:15:38.279  7937  7937 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:15:38.279  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 18:15:38.279  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 18:15:38.279  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 18:15:38.280  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 18:15:38.280  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 18:15:38.355  7937  7937 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 18:15:38.417  1033  1966 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:38.417  1033  1966 V SIM_STK : Menu title from STK is T-Mobile
,08-16 18:15:38.540  1033  2050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 18:15:38.551  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 18:15:38.555  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:15:38.556  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 18:15:38.557  7753  7753 I BluetoothA2dpServiceJni: classInitNative
08-16 18:15:38.557  7753  7753 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:15:38.557  7753  7753 D A2dpStateMachine: make
08-16 18:15:38.558  7753  7753 I bluedroid-qcom: get_profile_interface a2dp
08-16 18:15:38.558  7753  7995 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:15:38.561  7753  7753 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 18:15:38.561  7753  7753 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 18:15:38.562  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:38.562  7753  7994 D A2dpStateMachine: Enter Disconnected: -2
08-16 18:15:38.563  7753  7753 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 18:15:38.564  7753  7753 D HidService: Received start request. Starting profile...
08-16 18:15:38.564  7753  7753 I bluedroid-qcom: get_profile_interface hidhost
08-16 18:15:38.564  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:38.565  7753  7753 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:15:38.566  7753  7753 D HealthService: Received start request. Starting profile...
08-16 18:15:38.568  7753  7753 I bluedroid-qcom: get_profile_interface health
,08-16 18:15:38.569  7753  7753 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:15:38.569  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:38.569  7753  7753 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 18:15:38.572  7753  7753 D PanService: Received start request. Starting profile...
,08-16 18:15:38.572  7753  7753 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:15:38.572  7753  7753 I bluedroid-qcom: get_profile_interface pan
,08-16 18:15:38.580  7753  7753 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 18:15:38.581  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:38.581  7753  7753 D HeadsetStateMachine: Proxy object connected
08-16 18:15:38.581  7753  7753 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 18:15:38.581  7753  7753 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 18:15:38.582  7753  7753 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 18:15:38.586  7753  7753 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:15:38.586  7753  7753 D BtGatt.GattService: Received start request. Starting profile...
08-16 18:15:38.586  7753  7753 D BtGatt.GattService: start()
08-16 18:15:38.586  7753  7753 I bluedroid-qcom: get_profile_interface gatt
08-16 18:15:38.587  7753  7753 D BtGatt.AdvertiseManager: advertise manager created
08-16 18:15:38.595  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:38.598  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:38.598  7753  7980 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 18:15:38.599  7753  7980 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:15:38.599  7753  7980 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 18:15:38.600  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:38.601  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:38.601  7753  7753 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 18:15:38.602  7753  7753 V BluetoothMapService: BluetoothMapBinder()
08-16 18:15:38.602  7753  7753 D BluetoothMapService: Received start request. Starting profile...
08-16 18:15:38.602  7753  7753 D BluetoothMapService: start()
08-16 18:15:38.605  7753  7753 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 18:15:38.605  7753  7753 D BluetoothMapEmailAppObserver: createReceiver()
08-16 18:15:38.606  7753  7753 D BluetoothMapEmailAppObserver: initObservers()
08-16 18:15:38.606  7753  7753 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 18:15:38.613  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:38.616  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:38.618  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:38.620  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:38.622  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:15:38.622  7753  7753 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 18:15:38.625  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 18:15:38.625  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:38.625  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:38.625  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:38.625  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:38.625  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 18:15:38.625  7753  7753 V BluetoothMapService: Handler(): got msg=1
,08-16 18:15:38.630  7753  7972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 18:15:38.630  7753  7972 I bluedroid-qcom: enable
08-16 18:15:38.631  7753  8002 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 18:15:38.631  7753  8002 I bt-btu  : btu_task pending for preload complete event
08-16 18:15:38.631  7753  7972 I bt_hci_bdroid: init
08-16 18:15:38.632  7753  7972 I bt_vendor: bt-vendor : init
08-16 18:15:38.632  7753  7972 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 18:15:38.632  7753  7972 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 18:15:38.632  7753  7972 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 18:15:38.632  7753  7972 D bt_userial_mct: userial_init
08-16 18:15:38.632  7753  7972 D bt_hci_bdroid: set_power 1
08-16 18:15:38.632  7753  7972 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 18:15:38.632  7753  7972 I bt_vendor: Starting hciattach daemon
08-16 18:15:38.632  7753  7972 I bt_vendor: try to set true
08-16 18:15:38.624  8005  8005 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:38.624  8005  8005 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:38.655  8006  8006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 18:15:38.704  8012  8012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 18:15:38.712  8013  8013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:15:38.731  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:15:38.739  8016  8016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 18:15:38.748  8017  8017 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:15:38.771  8018  8018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 18:15:38.787  8020  8020 I libmdmdetect: ESOC framework not supported
08-16 18:15:38.788  8020  8020 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 18:15:38.797  8020  8020 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 18:15:38.797  8020  8020 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 18:15:38.797  8020  8020 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 18:15:38.797  8020  8020 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 18:15:38.797  8020  8020 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 18:15:38.797  8020  8020 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 18:15:38.797  8020  8020 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 18:15:38.836  8020  8021 E QC-QMI  : qmi_client [8020] 15: failed to locate client data
08-16 18:15:38.836   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-16 18:15:38.836   472   472 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-16 18:15:38.869  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 18:15:38.898  8023  8023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:15:38.936  7753  7972 I bt_vendor: bluetooth satus is on
08-16 18:15:38.936  7753  7972 D bt_hci_bdroid: preload
08-16 18:15:38.937  7753  8004 D bt_userial_mct: userial_open(port:0)
08-16 18:15:38.937  7753  8004 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 18:15:38.941  7753  8004 I bt_vendor: Done intiailizing UART
,08-16 18:15:38.942  7753  8004 I bt_vendor: Done intiailizing UART
08-16 18:15:38.942  7753  8004 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 18:15:38.942  7753  8004 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 18:15:38.942  7753  8002 I bt-btu  : btu_task received preload complete event
08-16 18:15:38.942  7753  8025 D bt_userial_mct: Entering userial_read_thread()
08-16 18:15:38.943  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 18:15:38.944  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 18:15:38.948  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 18:15:38.954  7753  8002 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 18:15:38.954  7753  8002 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:15:38.954  7753  8002 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 18:15:38.954  7753  8002 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:15:38.954  7753  8002 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:15:38.954  7753  8002 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 18:15:38.955  7753  8002 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 18:15:39.037  7753  8002 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 18:15:39.037  7753  8002 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0158061 
08-16 18:15:39.037  7753  8002 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0158061 
,08-16 18:15:39.097  7753  7975 E bt-btif : Calling BTA_HhEnable
,08-16 18:15:39.097  7753  7975 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 18:15:39.098  7753  7975 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 18:15:39.111  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:15:39.113  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 18:15:39.113  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 18:15:39.113  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 18:15:39.113  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 18:15:39.113  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 18:15:39.116  7753  7975 D BluetoothAdapterProperties: Name is: G3
08-16 18:15:39.123  7753  7975 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:15:39.123  7753  7975 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:39.123  7753  7975 D bt_hci_bdroid: postload
,08-16 18:15:39.126  7753  8004 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:15:39.128  7753  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 18:15:39.128  7753  7975 D bte_conf: Device ID record 1 : primary
08-16 18:15:39.128  7753  7975 D bte_conf:   vendorId            = 00c4
08-16 18:15:39.128  7753  7975 D bte_conf:   vendorIdSource      = 0001
08-16 18:15:39.128  7753  7975 D bte_conf:   product             = 13a1
08-16 18:15:39.128  7753  7975 D bte_conf:   version             = 1000
08-16 18:15:39.128  7753  7975 D bte_conf:   clientExecutableURL = 
08-16 18:15:39.128  7753  7975 D bte_conf:   serviceDescription  = 
08-16 18:15:39.128  7753  7975 D bte_conf:   documentationURL    = 
08-16 18:15:39.128  7753  7975 D bte_conf: bte_load_did_conf no section named DID2.
08-16 18:15:39.129  7753  8004 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:15:39.132  7753  7972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 18:15:39.133  7753  7972 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:15:39.133  7753  7972 D BluetoothAdapterProperties: State =  11
08-16 18:15:39.134  7753  7972 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 18:15:39.134  7753  7972 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 18:15:39.134  7753  7972 D BluetoothAdapterProperties: Setting state to 12
08-16 18:15:39.134  7753  7972 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 18:15:39.134  7753  7975 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 18:15:39.135  7753  7975 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:15:39.124  8030  8030 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 18:15:39.134  8030  8030 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:39.145  1033  1097 D BluetoothManagerService: Message: 60
08-16 18:15:39.145  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 18:15:39.146  1033  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 18:15:39.146  7753  8004 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:15:39.152  7753  7972 I BluetoothAdapterState: Entering On State
,08-16 18:15:39.164  7753  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:39.165  7753  8002 W bt-smp  : Plain text(LSB ~ MSB) = f6 26 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:39.165  7753  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = ab 07 28 f5 ff 9d 05 b1 31 1f 82 d8 85 ab a1 59 
,08-16 18:15:39.167  7753  8004 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:15:39.167  7753  8002 W bt-btm  : Stopping oneshot timer
08-16 18:15:39.168  7753  8025 E bt_mct  : hci lib postload completed
08-16 18:15:39.170  7753  7972 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 18:15:39.170  7753  7972 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 18:15:39.170  7753  7972 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 18:15:39.175  7753  7972 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 18:15:39.184  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:39.195  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:39.198  7753  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:39.198  7753  8002 W bt-smp  : Plain text(LSB ~ MSB) = 78 2d 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:39.198  7753  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 38 e3 05 bf 81 4e f9 25 44 19 20 5e 30 d0 d7 ba 
,08-16 18:15:39.201  7753  8002 W bt-btm  : Stopping oneshot timer
08-16 18:15:39.205  7753  7972 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 18:15:39.219  7753  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:39.219  7753  8002 W bt-smp  : Plain text(LSB ~ MSB) = de 06 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:39.219  7753  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = af a8 84 0c eb 17 27 6b 27 f4 00 97 ba 54 64 cd 
,08-16 18:15:39.221  7753  8002 W bt-btm  : Stopping oneshot timer
08-16 18:15:39.222  7753  7975 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:39.222  7753  7975 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 18:15:39.226  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:39.232  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:39.238  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:39.241  7753  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:39.241  7753  8002 W bt-smp  : Plain text(LSB ~ MSB) = c4 8c 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:39.241  7753  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 5c 86 3c 6a 41 4c ba 06 ff 9a 43 17 7c ee b9 4f 
08-16 18:15:39.241  7753  8002 W bt-btm  : Stopping oneshot timer
08-16 18:15:39.243  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:39.243  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39dd9217 added. We now have 8 listener(s)
08-16 18:15:39.243  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:39.254  6871  6888 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:15:39.283  1033  2032 D WifiServiceImplEx: setWifiEnabled: false pid=6680, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 18:15:39.283  1033  2032 D WifiService: setWifiEnabled: false pid=6680, uid=10118
08-16 18:15:39.283  1033  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:15:39.294  8043  8043 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 18:15:39.298  6871  6871 D BluetoothInputDevice: Proxy object connected
08-16 18:15:39.298  6871  6871 D HidProfile: Bluetooth service connected
08-16 18:15:39.302  6871  6886 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:15:39.303  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:39.304  7753  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:15:39.304  7753  8002 W bt-smp  : Plain text(LSB ~ MSB) = ef 86 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:15:39.304  7753  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a 7a c7 c4 94 a4 87 bd 4c c7 bf 07 fe a9 2d db 
08-16 18:15:39.304  7753  8002 W bt-btm  : Stopping oneshot timer
08-16 18:15:39.304  1033  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6680, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 18:15:39.305  1033  1050 D WifiService: setWifiEnabled: true pid=6680, uid=10118
08-16 18:15:39.305  1033  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:15:39.310  6871  6871 D BluetoothMap: Proxy object connected
08-16 18:15:39.310  6871  6888 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 18:15:39.312  6871  6871 D MapProfile: Bluetooth service connected
08-16 18:15:39.312  6871  6871 D BluetoothMap: getConnectedDevices()
08-16 18:15:39.314  7753  7978 V BluetoothMapService: getConnectedDevices()
08-16 18:15:39.316  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:15:39.316  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:15:39.316  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-16 18:15:39.316  1033  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 18:15:39.316  1033  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 18:15:39.317  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 18:15:39.317  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:15:39.317  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 18:15:39.317  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:15:39.317  1033  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 18:15:39.317  1033  1538 E WifiHW  : unknown target_country: EU , set to default
08-16 18:15:39.317  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 18:15:39.317  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 18:15:39.317  1033  1538 I WifiUtil: gEnableBmps=1
,08-16 18:15:39.407  1033  1097 I art     : Explicit concurrent mark sweep GC freed 27291(1358KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.058ms total 91.269ms
,08-16 18:15:39.411  1852  2458 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 18:15:39.418  1852  1852 D BluetoothHeadset: Proxy object connected
08-16 18:15:39.418  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:39.422  1852  1852 D BluetoothHeadset: Proxy object connected
08-16 18:15:39.422  1852  2458 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 18:15:39.427  1852  1852 D BluetoothHeadset: Proxy object connected
08-16 18:15:39.428  6871  6886 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:39.429  1033  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:15:39.430  1033  1033 D BluetoothHeadset: Proxy object connected
08-16 18:15:39.430  6871  6871 D BluetoothHeadset: Proxy object connected
08-16 18:15:39.430  6871  6871 D HeadsetProfile: Bluetooth service connected
08-16 18:15:39.430  6871  6886 D BluetoothPan: onBluetoothStateChange on: true
08-16 18:15:39.430  6871  6886 D BluetoothPan: onBluetoothStateChange call bindService
08-16 18:15:39.433  6871  6887 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:39.435  6871  6871 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:39.435  6871  6871 D PanProfile: Bluetooth service connected
,08-16 18:15:39.437  6871  6871 D BluetoothA2dp: Proxy object connected
,08-16 18:15:39.437  6871  6871 D A2dpProfile: Bluetooth service connected
08-16 18:15:39.438  1033  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:39.438  1033  1033 D BluetoothA2dp: Proxy object connected
08-16 18:15:39.440  1033  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 18:15:39.440  1033  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 18:15:39.441  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 18:15:39.442  1033  1097 D BluetoothManagerService: Message: 40
08-16 18:15:39.442  1033  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 18:15:39.442  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.442  1941  2139 D LGBluetoothAPIService: Message: 1
08-16 18:15:39.442  1941  2139 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 18:15:39.443  1941  2139 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 18:15:39.443  1941  2139 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 18:15:39.443  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:15:39.453  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:39.456  7753  7753 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:39.456  7753  7753 D BluetoothMapService: STATE_ON
08-16 18:15:39.456  6871  6871 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 18:15:39.457  6871  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 18:15:39.466  6871  6871 D DockEventReceiver: finishStartingService: stopping service
08-16 18:15:39.477  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:39.478  7753  7753 V BluetoothPbapService: Pbap Service onCreate
08-16 18:15:39.478  7753  7753 V BluetoothPbapService: Starting PBAP service
08-16 18:15:39.479  7753  7753 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 18:15:39.479  7753  7753 V BluetoothPbapService: Pbap Service onBind
,08-16 18:15:39.480  7753  7753 V BluetoothMapService: Handler(): got msg=1
08-16 18:15:39.480  6871  6871 D BluetoothPbap: Proxy object connected
08-16 18:15:39.480  6871  6871 D PbapServerProfile: Bluetooth service connected
08-16 18:15:39.480  7753  7753 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 18:15:39.481  7753  7753 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.482  7753  7753 V BluetoothPbapService: state: 12
08-16 18:15:39.482  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:15:39.483  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.483  7753  7753 V BluetoothPbapReceiver: ***********state = 12
08-16 18:15:39.485  7753  7753 V BluetoothPbapService: Handler(): got msg=1
08-16 18:15:39.485  7753  7753 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 18:15:39.486  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:39.486  2208  2208 D c       : Getting all permits...
08-16 18:15:39.486  2208  2208 D a       : Opening database...
08-16 18:15:39.488  7753  8060 D BluetoothMapMasInstance: MAS initSocket()
,08-16 18:15:39.488  7753  8061 V BluetoothPbapService: Pbap Service initSocket
,08-16 18:15:39.489  7753  8060 D BluetoothMapMasInstance:   masId = 00
08-16 18:15:39.489  7753  8060 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 18:15:39.489  7753  8060 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 18:15:39.489  7753  8060 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 18:15:39.490  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-16 18:15:39.490  1033  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:39.490  1033  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:39.490  2208  2208 D a       : Closing database...
08-16 18:15:39.492  7753  8060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:39.493  7753  8061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:39.496  7753  8061 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 18:15:39.496  7753  8061 V BluetoothPbapService: Succeed to create listening socket 
08-16 18:15:39.496  7753  8061 V BluetoothPbapService: Accepting socket connection...
08-16 18:15:39.499  7753  8060 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 18:15:39.499  7753  8060 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 18:15:39.499  7753  8060 D BluetoothMapMasInstance: Accepting socket connection...
08-16 18:15:39.499  7753  7975 D BluetoothAdapterProperties: Scan Mode:21
08-16 18:15:39.500  7753  7975 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 18:15:39.505  6871  6871 D BluetoothPermissionRequest: onReceive
,08-16 18:15:39.509  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:39.515  6871  6871 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:15:39.517  6871  6871 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 18:15:39.525  7753  7753 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 18:15:39.527  7753  7753 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 18:15:39.536  7753  7753 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 18:15:39.577  7753  7753 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:15:39.578  7753  7753 V BtOppService: onCreate
,08-16 18:15:39.586  7753  7753 V BluetoothOppNotification: send message
08-16 18:15:39.593  7753  7753 V BtOppService: Starting RfcommListener
,08-16 18:15:39.599  7753  8064 V BtOppService: Deleted complete outbound shares, number =  0
08-16 18:15:39.603  7753  7753 D BluetoothOppPreference: Dumping Names:  
08-16 18:15:39.603  7753  7753 D BluetoothOppPreference: {}
08-16 18:15:39.603  7753  7753 D BluetoothOppPreference: Dumping Channels:  
08-16 18:15:39.603  7753  7753 D BluetoothOppPreference: {}
08-16 18:15:39.604  7753  8064 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 18:15:39.606  7753  7753 V BtOppService: onStartCommand
08-16 18:15:39.606  7753  8064 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 18:15:39.608  7753  8064 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cb78bb8 on behalf of 
,08-16 18:15:39.613  7753  8067 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:15:39.613  7753  8067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:15:39.614  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.614  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:15:39.615  7753  8067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f08bd91 on behalf of 
08-16 18:15:39.616  7753  8067 V BluetoothOppNotification: update too frequent, put in queue
08-16 18:15:39.618  7753  8067 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:15:39.619  7753  7753 V BluetoothOppNotification: new notify threadi!
08-16 18:15:39.619  7753  7753 V BluetoothOppNotification: send delay message
08-16 18:15:39.620  7753  7753 V BtOppService: start RfcommListener
08-16 18:15:39.621  7753  8068 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 18:15:39.623  7753  7753 V BtOppService: RfcommListener started
08-16 18:15:39.624  7753  7753 V BtOppService: ContentObserver received notification
08-16 18:15:39.624  7753  8068 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fa114f6 on behalf of 
08-16 18:15:39.626  7753  8069 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 18:15:39.626  7753  7753 V BtOppService: ContentObserver received notification
,08-16 18:15:39.629  7753  8068 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:15:39.630  7753  8070 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:15:39.631  7753  8070 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:15:39.631  1033  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:39.632  7753  8068 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:39.633  7753  8068 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@283d10f7 on behalf of 
08-16 18:15:39.634  7753  8069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:39.634  7753  8068 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 18:15:39.635  7753  8069 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 18:15:39.635  7753  8069 V BtOppRfcommListener: Started RFCOMM listener....
08-16 18:15:39.635  7753  8069 I BtOppRfcommListener: Accept thread started.
08-16 18:15:39.635  7753  8069 V BtOppRfcommListener: Accepting connection...
08-16 18:15:39.636  7753  8070 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1335ab64 on behalf of 
08-16 18:15:39.637  7753  8068 V BluetoothOppNotification: outbound notification was removed.
08-16 18:15:39.637  7753  8068 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:39.639  7753  8068 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b6aa1cd on behalf of 
08-16 18:15:39.639  7753  8068 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:15:39.641  7753  8068 V BluetoothOppNotification: inbound notification was removed.
08-16 18:15:39.641  7753  8068 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 18:15:39.641  7753  8070 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-16 18:15:39.642  7753  8068 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b418a82 on behalf of 
,08-16 18:15:39.655  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
08-16 18:15:39.655  7753  7753 V BluetoothFtpService: Ftp Service onCreate
,08-16 18:15:39.655  7753  7753 I BluetoothFtpService: Ftp Service onCreate
08-16 18:15:39.656  7753  7753 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:15:39.656  7753  7753 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.656  7753  7753 V BluetoothFtpService: Starting Listening on sockets
08-16 18:15:39.656  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:15:39.656  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:15:39.656  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:15:39.656  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.656  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 18:15:39.656  7753  7753 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 18:15:39.658  7753  7753 V BluetoothFtpService: Handler(): got msg=1
08-16 18:15:39.659  7753  7753 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 18:15:39.659  7753  7753 V BluetoothFtpService: Ftp Service initSocket
08-16 18:15:39.665  1033  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:39.665  7753  7753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:39.666  7753  7753 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 18:15:39.667  7753  7753 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 18:15:39.668  7753  8071 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 18:15:39.683  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b10ba3c
,08-16 18:15:39.683  7753  7753 V BluetoothSapService: Sap Service onCreate
,08-16 18:15:39.685  7753  7753 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:39.685  7753  7753 V BluetoothSapService: state: 12
08-16 18:15:39.686  7753  7753 V BluetoothSapService: Starting SAP server process
08-16 18:15:39.687  7753  7753 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 18:15:39.674  8072  8072 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:39.674  8072  8072 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:39.688  7753  8073 V BluetoothSapService: Sap Service initRfcommSocket
08-16 18:15:39.689  1033  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:39.690  7753  8073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:39.691  7753  8073 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 18:15:39.691  7753  8073 V BluetoothSapService: Succeed to create listening socket 
08-16 18:15:39.691  7753  8073 V BluetoothSapService: Accepting socket connection...
08-16 18:15:39.707  8072  8072 V BT_SAP  : Event pipe created
08-16 18:15:39.707  8072  8072 V BT_SAP  : create_server_socket qcom.sap.server
08-16 18:15:39.707  8072  8072 V BT_SAP  : created socket fd 6
,08-16 18:15:40.110   315   893 D SoftapController: Softap fwReload - Ok
,08-16 18:15:40.123  1033  1538 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (804ms)
08-16 18:15:40.126   315   893 D CommandListener: Setting iface cfg
08-16 18:15:40.126   315   893 D CommandListener: Trying to bring down wlan0
,08-16 18:15:40.129   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:40.142  1033  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:40.142  1033  1097 D Tethering: InitialState.processMessage what=4
,08-16 18:15:40.159  1033  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 18:15:40.168  1033  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 18:15:40.174  8090  8090 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:40.174  8090  8090 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:40.192  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:40.192  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:40.192  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 18:15:40.212  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:40.217  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 18:15:40.226  1033  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 18:15:40.226  1033  1538 D WifiMonitor: connecting to supplicant
,08-16 18:15:40.241  8090  8090 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 18:15:40.247  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:40.247  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:15:40.247  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:15:40.247  6871  6871 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:15:40.249  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 18:15:40.252  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:15:40.254  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:40.255  6871  6871 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:15:40.255  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:15:40.255  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:15:40.255  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:15:40.256  6871  6871 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:15:40.256  6871  6871 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:15:40.258  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:40.259  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:15:40.259  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:15:40.259  6871  6871 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:15:40.259  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:15:40.260  6871  6871 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:15:40.260  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:15:40.260  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:15:40.260  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:15:40.260  6871  6871 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:15:40.260  6871  6871 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 18:15:40.275  8090  8090 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:40.275  8090  8090 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 18:15:40.305  1033  1966 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8106 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 18:15:40.340  8090  8090 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 18:15:40.396  8090  8090 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 18:15:40.404  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:15:40.405  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 18:15:40.405  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:15:40.406  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 18:15:40.406  1033  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:15:40.406  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:15:40.406  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:15:40.406  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-16 18:15:40.406  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 18:15:40.406  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 18:15:40.406  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 18:15:40.407  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:40.407  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:40.408  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:40.408  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:40.409  1033  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 18:15:40.409  1033  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 18:15:40.410  1033  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 18:15:40.410  1033  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 18:15:40.410  1033  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 18:15:40.439  1033  1050 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8130 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:15:40.442  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:15:40.442  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:15:40.442  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:15:40.443  1033  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 18:15:40.444  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.444  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.444  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.444  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.444  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:15:40.444  1033  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-16 18:15:40.444  1033  1538 D WifiConfigStore: Loading config and enabling all networks 
08-16 18:15:40.444  1033  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 18:15:40.445  1033  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 18:15:40.446  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:40.447  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-16 18:15:40.447  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 18:15:40.448  1033  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:40.451  6680  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:40.451  8106  8128 W FormManager: Network not available. Please check & try again.
,08-16 18:15:40.453  6680  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:40.454  1033  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 18:15:40.466  1033  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 18:15:40.466  1033  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 18:15:40.467  1033  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-16 18:15:40.467  1033  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 18:15:40.467  1033  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 18:15:40.467  1033  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 18:15:40.468  1033  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 18:15:40.468  1033  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 18:15:40.468  1033  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 18:15:40.468  1033  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 18:15:40.469  1033  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 18:15:40.469  1033  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 18:15:40.469  1033  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 18:15:40.469  1033  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 18:15:40.469  1033  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 18:15:40.469  8106  8129 V FormManager: Network unavailable.
08-16 18:15:40.469  1033  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-16 18:15:40.471  1033  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 18:15:40.471  8106  8129 V FormManager: Network unavailable.
08-16 18:15:40.473  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-16 18:15:40.473  1941  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 18:15:40.473  1941  2293 D WfdsService: Set the WFDS Monitor: true
08-16 18:15:40.473  1941  2293 D WfdsMonitor: WfdsMonitorThread create
08-16 18:15:40.473  1941  2293 D WfdsMonitor: WFDS Monitor is created and started
08-16 18:15:40.473  1941  2293 D WfdsService: WiFi: Supplicant connection re-established
08-16 18:15:40.473  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:40.473  7783  7783 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.473  1033  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 18:15:40.474  1033  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,08-16 18:15:40.474  1033  1538 D WifiNative-HAL: Setting external_sim to 1
08-16 18:15:40.474  1033  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 18:15:40.474  1941  8148 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 18:15:40.475  1033  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 18:15:40.475  1033  1538 I WifiNative-HAL: startHal
08-16 18:15:40.475  1033  1538 D wifi    : setting scan oui 0xaf7260e0
08-16 18:15:40.475  1941  8148 E CtrlSupplicant: Succeed to open control connection
08-16 18:15:40.475  1941  8148 E CtrlSupplicant: Succeed to open monitor connection
08-16 18:15:40.475  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:40.475  1033  1538 I WifiNative-HAL: startHal
08-16 18:15:40.475  1033  1538 D wifi    : setting scan oui 0xaf7260e0
08-16 18:15:40.475  1941  8148 D WfdsMonitor: Supplicant connection established
08-16 18:15:40.475  1941  2293 D WfdsService: Connected to the supplicant for wfds
08-16 18:15:40.475  1033  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 18:15:40.476  1033  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 18:15:40.476  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 18:15:40.477  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 18:15:40.477  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 18:15:40.477  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:15:40.477  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:15:40.478  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:15:40.478  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,08-16 18:15:40.478  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 18:15:40.478  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 18:15:40.478  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:15:40.478  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:15:40.479  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:15:40.479  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:15:40.479  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:15:40.480  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-16 18:15:40.480  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-16 18:15:40.480  8090  8090 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 18:15:40.481  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 18:15:40.481  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:15:40.481  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:15:40.481  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:15:40.483  1033  1538 E WifiNative: : [135,097,243 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 18:15:40.483  1033  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 18:15:40.484  1033  1538 D WifiNative-wlan0: RECONNECT: returned true
08-16 18:15:40.484  1033  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 18:15:40.484  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:15:40.484  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:15:40.485  1033  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:15:40.485  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:15:40.485  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:40.486  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.486  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 18:15:40.486  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-16 18:15:40.486  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.486  1033  1556 I WifiNative-HAL: startHal
08-16 18:15:40.486  1033  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf7260e0
08-16 18:15:40.486  1033  1556 D wifi    : failed to get capabilities : -3
08-16 18:15:40.486  1033  1556 E WifiScanningService: could not get scan capabilities
08-16 18:15:40.487  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:15:40.487  1033  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.487   315   893 D CommandListener: Setting iface cfg
08-16 18:15:40.487   315   893 D CommandListener: Trying to bring up p2p0
08-16 18:15:40.487  1033  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 18:15:40.487  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 18:15:40.487  1033  1536 D LGWifiP2pService: P2pEnablingState
08-16 18:15:40.487  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.487  1033  1536 D LGWifiP2pService: P2p socket connection successful
08-16 18:15:40.487  1033  1536 D LGWifiP2pService: P2pEnabledState
08-16 18:15:40.488  1033  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 18:15:40.488  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 18:15:40.488  1033  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 18:15:40.488  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 18:15:40.488  1941  1941 D WfdsService: WifiP2pState is changed : true
08-16 18:15:40.488  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=135104  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:40.489  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 18:15:40.489  1941  2293 D WfdsService: Receive the WFDS_ENABLE Method
08-16 18:15:40.489  1941  2293 D WfdsService: Set the WFDS Monitor: true
08-16 18:15:40.489  1941  2293 D WfdsService: Connected t,o the supplicant for wfds
08-16 18:15:40.489  1941  2293 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 18:15:40.489  8090  8090 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 18:15:40.489  1941  2293 D WfdsService: selectPreferredScanChannel [36]
08-16 18:15:40.489  1941  2293 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 18:15:40.490  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 18:15:40.491  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 18:15:40.491  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-16 18:15:40.491  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 18:15:40.491  1033  1536 D LGWifiP2pService: before postfix = G3
08-16 18:15:40.491  1033  1536 D WifiServerServiceExt: postfix byte check : 2
08-16 18:15:40.491  1033  1536 D LGWifiP2pService: after postfix = G3
08-16 18:15:40.491  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-16 18:15:40.495  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 18:15:40.495  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 18:15:40.495  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 18:15:40.495  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 18:15:40.496  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 18:15:40.496  1941  1941 D WfdsService: isConnected: false
08-16 18:15:40.497  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 18:15:40.497  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 18:15:40.497  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 18:15:40.497  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-16 18:15:40.497  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 18:15:40.498  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=135113  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:40.498  1033  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 18:15:40.499  1033  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 18:15:40.499  1033  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 18:15:40.499  1033  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 18:15:40.499  8090  8090 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 18:15:40.500  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:40.500  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:40.500  1033  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 18:15:40.500  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.500  1033  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 18:15:40.500  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.501  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:15:40.501  1033  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 18:15:40.501  1033  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 18:15:40.501  8090  8090 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 18:15:40.501  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 18:15:40.501  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 18:15:40.501  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 18:15:40.502  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 18:15:40.502  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 18:15:40.502  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:40.502  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 18:15:40.502  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 18:15:40.503  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 18:15:40.503  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 18:15:40.503  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 18:15:40.503  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 18:15:40.503  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 18:15:40.503  1941  1941 I WfdStateTracker: h,andleP2pThisDeviceChanged
08-16 18:15:40.504  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 18:15:40.504  1941  1941 D WfdsService: Update P2p Interface State: 3
,08-16 18:15:40.504  1033  1932 I ActivityManager: Killing 7194:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 18:15:40.512  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 18:15:40.512  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 18:15:40.512  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:15:40.512  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.513  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:15:40.513  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 18:15:40.513  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.513  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.513  8090  8090 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:15:40.513  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.513  1033  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 18:15:40.514  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:15:40.514  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.514  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:15:40.514  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:15:40.515  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 18:15:40.515  1941  8148 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.515  1941  8148 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.515  1033  8125 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.515  1033  8125 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.515  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.515  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.515  1033  8125 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.515  1033  8125 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.515  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.515  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.515  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 18:15:40.515  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:40.516  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 18:15:40.516  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:40.516  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:40.516  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:15:40.516  1033  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 18:15:40.516  1033  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-16 18:15:40.518  1033  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-16 18:15:40.518  1033  1538 D WifiNative-wlan0: doBoolean: SCAN
08-16 18:15:40.518  1033  1538 D WifiNative-wlan0: SCAN: returned false
08-16 18:15:40.519  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=135134  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:40.533  8130  8130 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:40.594  1033  1536 D LGWifiP2pService: InactiveState
,08-16 18:15:40.595  1033  1536 D LGWifiP2pService: InactiveState{ when=-92ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.595  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=135210  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:15:40.595  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-93ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.595  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 18:15:40.595  1033  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:40.596  1033  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:40.596  1033  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:40.597  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:15:40.597  1033  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:40.597  1033  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:15:40.598  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.598  1941  8148 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:15:40.599  1033  8125 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:15:40.599  1033  8125 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.599  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.599  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:15:40.600  8090  8090 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:15:40.600  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:40.600  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:40.600  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.600  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 18:15:40.601  1033  1536 D LGWifiP2pService: InactiveState{ when=-87ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.601  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:40.601  1941  8148 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.602  1033  8125 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.602  1033  8125 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.602  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.602  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.602  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.601  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-88ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.603  1033  1536 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.603  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returnin,g read-only value.
08-16 18:15:40.603  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.603  1033  1536 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.603  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:40.604  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:15:40.604  1033  1536 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.604  1033  1575 W libprocessgroup: failed to open /acct/uid_10062/pid_7194/cgroup.procs: No such file or directory
08-16 18:15:40.604  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.604  1033  1536 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.605  1941  8148 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.605  1033  8125 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:15:40.605  1033  8125 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.605  1033  8125 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.605  1033  8125 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:15:40.606  1941  2293 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 18:15:40.606  1033  1536 D LGWifiP2pService: InactiveState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.606  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.606  1033  1536 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.607  1033  1536 D LGWifiP2pService: InactiveState{ when=-13ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.607  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:40.608  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:40.608  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:15:40.612  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:40.612  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:15:40.615  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:40.607  1033  1536 D LGWifiP2pService: DefaultState{ when=-13ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:40.616  1033  1033 E WifiServerServiceExt: No p2p device connected
08-16 18:15:40.621  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:40.621  7753  7753 V BluetoothOppNotification: new notify threadi!
,08-16 18:15:40.622  7753  7753 V BluetoothOppNotification: send delay message
08-16 18:15:40.623  1033  1990 I ActivityManager: Killing 7226:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 18:15:40.625  7753  8152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 18:15:40.626  7753  8152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cff27ef on behalf of 
08-16 18:15:40.626  7753  8152 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:15:40.627  7753  8152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:40.628  7753  8152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18a902fc on behalf of 
08-16 18:15:40.629  7753  8152 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 18:15:40.631  7753  8152 V BluetoothOppNotification: outbound notification was removed.
08-16 18:15:40.631  7753  8152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:15:40.642  7753  8152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c73d85 on behalf of 
08-16 18:15:40.642  7753  8152 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 18:15:40.643  7753  8152 V BluetoothOppNotification: inbound notification was removed.
08-16 18:15:40.643  7753  8152 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 18:15:40.644  7753  8152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3871e7da on behalf of 
08-16 18:15:40.674  1033  1956 W libprocessgroup: failed to open /acct/uid_10085/pid_7226/cgroup.procs: No such file or directory
,08-16 18:15:40.698  8130  8130 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:40.705  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:40.717  8106  8154 W FormManager: Network not available. Please check & try again.
08-16 18:15:40.717  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:40.722  8106  8155 V FormManager: Network unavailable.
08-16 18:15:40.732  8106  8155 V FormManager: Network unavailable.
,08-16 18:15:40.739  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:40.739  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:15:40.741  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:40.744  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:15:40.749  4304  8156 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 18:15:40.756  4304  8157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:15:40.756  4304  8157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:15:40.802  1033  2025 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8158 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 18:15:40.925  8158  8158 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:40.925  8158  8158 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 18:15:40.934  8158  8158 V [BNRBootReceiver]: Boot Receiver Return
08-16 18:15:40.935  8158  8158 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 18:15:41.008  1033  1782 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8179 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 18:15:41.009  1033  1782 I ActivityManager: Killing 7246:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 18:15:41.074  8090  8090 E wpa_supplicant: USIM:  scard_init function
,08-16 18:15:41.074  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-16 18:15:41.075  8090  8090 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 18:15:41.075  1033  8125 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 18:15:41.075  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-16 18:15:41.075  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-16 18:15:41.075  1033  8125 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 18:15:41.075  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:15:41.075  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 18:15:41.076  1033  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 18:15:41.077  1033  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 18:15:41.078  1033  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 18:15:41.079  1033  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 18:15:41.079  1033  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 18:15:41.190  8090  8090 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 18:15:41.191  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 18:15:41.191  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-16 18:15:41.204  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 18:15:41.204  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 18:15:41.205  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:41.205  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:41.206  8090  8090 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:41.206  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:15:41.208  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:41.208  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:41.208  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 18:15:41.208  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:41.208  1033  8125 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:41.208  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 18:15:41.208  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:15:41.208  1033  8125 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:15:41.209  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:41.209  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:41.218  1033  1887 W libprocessgroup: failed to open /acct/uid_10093/pid_7246/cgroup.procs: No such file or directory
,08-16 18:15:41.228  1033  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:15:41.228  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=135843  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 18:15:41.235  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.235  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:41.237  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.237  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=135853  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 18:15:41.237  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.237  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:15:41.239  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=135853  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:15:41.239  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=135855  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:15:41.239  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.240  1033  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135855
08-16 18:15:41.240  1033  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135856
08-16 18:15:41.241  1033  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135856
08-16 18:15:41.241  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135857
08-16 18:15:41.242  1033  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135857
08-16 18:15:41.242  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=135858  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:15:41.246  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.246  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.246  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:15:41.246  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=135862  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:15:41.247  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=135862  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:15:41.248  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=135863  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:15:41.248  1033  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=135864
08-16 18:15:41.249  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.249  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.249  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 18:15:41.249  1033  1538 E WifiStateMachine:  ConnectModeS,tate NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=135864
08-16 18:15:41.249  1033  1538 D WifiNative-wlan0: doString: [STATUS]
08-16 18:15:41.250  1033  8125 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:15:41.250  1033  8125 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:15:41.251  1033  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:15:41.253  1033  1538 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 18:15:41.259  1033  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 18:15:41.260  1033  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 18:15:41.261  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.261  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:41.263  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.263  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.263  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 18:15:41.265  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.266  8179  8179 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:41.267  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.268  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:41.269  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:41.273  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.273  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:41.275  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.275  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.275  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.275  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 18:15:41.279  1033  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 18:15:41.279  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:15:41.279  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:15:41.279  1033  1544 D ConnectivityService: Got NetworkAgent Messenger
08-16 18:15:41.280  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 18:15:41.280  1033  1544 D ConnectivityService: NetworkAgent connected
08-16 18:15:41.281  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:15:41.281  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:15:41.285  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.285  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:15:41.301  8179  8179 D PluginManager: init()
,08-16 18:15:41.302  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:15:41.302  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:15:41.302  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:15:41.302  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:15:41.303  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:15:41.305  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.308  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:15:41.311   315   893 D CommandListener: Setting iface cfg
08-16 18:15:41.313  1033  1538 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 18:15:41.313  1033  8203 D DhcpStateMachine: StoppedState
08-16 18:15:41.313  1033  8203 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.314  1033  8203 D DhcpStateMachine: WaitBeforeStartState
08-16 18:15:41.314  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=135929  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 18:15:41.314  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=135930  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:41.315  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=135930  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:41.315  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:41.316  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:41.316  1033  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:41.316  1033  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:41.317  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:41.317  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:15:41.318  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:41.318  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 18:15:41.320  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:41.320  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 18:15:41.321  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:41.321  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 18:15:41.324  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:41.324  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 18:15:41.325  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=135940  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:41.325  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=135941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:41.326  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=135941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:15:41.327  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13448] from screen [on:0 period:-1809641201] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 18:15:41.328  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1809641200] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 18:15:41.328  1033  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:41.331  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:41.332  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.333  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:41.337  1033  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 18:15:41.338  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.338  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.338  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.339  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.341  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.341  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.342  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 18:15:41.342  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
08-16 18:15:41.342  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
08-16 18:15:41.342  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-16 18:15:41.343  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 18:15:41.343  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 18:15:41.343  1033  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 18:15:41.343  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 18:15:41.343  1033  1538 D WifiNative-wlan0: SET ps 0: returned true
08-16 18:15:41.343  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 18:15:41.344  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 18:15:41.344  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 18:15:41.344  1033  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 18:15:41.344  1033  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:15:41.344  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e30e9f1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.344  1033  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:15:41.344  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e30e9f1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.344  1033  8203 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.344  1033  8203 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 18:15:41.344  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 18:15:41.346   315   893 D CommandListener: Setting iface cfg
08-16 18:15:41.346   315   893 D CommandListener: Trying to bring up wlan0
,08-16 18:15:41.348  1033  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 18:15:41.349  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:41.349  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 18:15:41.350  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:15:41.350  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 18:15:41.350  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@259e91c3 Bundle[{}]
08-16 18:15:41.351  6680  6791 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 18:15:41.351  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.351  6680  6791 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 18:15:41.352  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.352  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.352  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 18:15:41.353  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.353  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 18:15:41.353  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.354  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:15:41.354  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 18:15:41.354  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 18:15:41.354  6680  6791 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 18:15:41.355  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 18:15:41.355  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 18:15:41.355  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:15:41.355  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.355  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.355  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:15:41.356  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:15:41.357  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 18:15:41.357  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 18:15:41.357  1033  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 18:15:41.357  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 18:15:41.364  6680  6791 I System.out: Running OutgoingSocketThread
08-16 18:15:41.365  6680  8204 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
08-16 18:15:41.366  6680  8204 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44789
08-16 18:15:41.367  6680  8204 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 18:15:41.374  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:15:41.375  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:15:41.375  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 18:15:41.375  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:15:41.375  1033  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-16 18:15:41.377  1033  1544 D ConnectivityService: ignoring duplicate network state non-change
08-16 18:15:41.379  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.379  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:41.381  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.382  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.382  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.382  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:15:41.383  1033  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 18:15:41.384  1033  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 18:15:41.385  1033  1544 D ConnectivityService: Adding iface wlan0 to network 102
08-16 18:15:41.387  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.387  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.387  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:15:41.388  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 18:15:41.389  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 18:15:41.391  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.391  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.391  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 18:15:41.391  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 18:15:41.401  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.401  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:15:41.401  1033  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 18:15:41.401  1033  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 18:15:41.401  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.402  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:41.402  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 18:15:41.402  1033  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 18:15:41.403  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.403   315   893 E Netd    : netlink response contains error (File exists)
08-16 18:15:41.403  1033  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 18:15:41.404  1033  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 18:15:41.404  1033  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 18:15:41.404  1033  1544 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 18:15:41.405  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.405  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:15:41.405  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.406  1033  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 18:15:41.406  1033  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.406  1033  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.406  1033  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.406  1033  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:41.406  1033  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:41.406  1033  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:15:41.406  1033  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.406  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.407  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 18:15:41.407  1033  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 18:15:41.407  1033  1544 D ConnectivityService: currentScore = 0, newScore = 20
08-16 18:15:41.407  1033  1544 D ConnectivityService:    accepting network in place of null
08-16 18:15:41.407  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:41.407  1033  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.407  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 18:15:41.408  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:41.408  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:15:41.409  1033  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.409  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBa,ndwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:41.409  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.409  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.409  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:15:41.409   315  8208 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 18:15:41.410  1033  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 18:15:41.410  1033  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 18:15:41.411  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:41.411  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 18:15:41.412  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:15:41.412  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:15:41.412  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:15:41.412  1033  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:41.412  1033  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 18:15:41.412  1033  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 18:15:41.413  1033  1544 D ConnectivityService: validation of new default Network = false
08-16 18:15:41.413  1033  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 18:15:41.413  1033  1544 D DSQN    : enableDataServiceNotify 
08-16 18:15:41.413  1033  1544 D DSQN    : start dsqn bin
,08-16 18:15:41.420  1033  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.420  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.420  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:41.420  1033  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:41.404  8209  8209 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:41.421  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:15:41.404  8209  8209 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:41.430  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 18:15:41.430  8209  8209 E DSQN    : DSQN ssw
,08-16 18:15:41.442  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 18:15:41.443  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:15:41.444  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.484   315  8208 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 18:15:41.526   315  8208 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 18:15:41.546  1033  8203 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 18:15:41.547  1033  8203 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 18:15:41.547  1033  8203 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 18:15:41.534  8213  8213 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:41.559   315   892 D LGDataListener: argv[0]=dsqncommand
08-16 18:15:41.559   315   892 D LGDataListener: argv[1]=wlan0
08-16 18:15:41.559   315   892 D LGDataListener: argv[2]=1
08-16 18:15:41.559   315   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 18:15:41.560  1033  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 18:15:41.561  1033  1095 D DSQN    : start to monitor internet connection
,08-16 18:15:41.534  8213  8213 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:15:41.572  8213  8213 I dhcpcd  : version 5.5.6 starting
08-16 18:15:41.577  8213  8213 E dhcpcd  : get_duid: m
08-16 18:15:41.577  8213  8213 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 18:15:41.577  8213  8213 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-16 18:15:41.591  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:15:41 GMT], X-Android-Received-Millis=[1471364141591], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471364141559]}
08-16 18:15:41.592  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 18:15:41.592  1033  8196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-16 18:15:41.592  1033  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.592  1033  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.593  1033  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:41.593  1033  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:41.593  1033  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:15:41.593  1033  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,08-16 18:15:41.593  1033  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 18:15:41.593  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.593  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:41.594  1033  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:41.595  1033  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.597  1033  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.597  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:41.598  1033  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 18:15:41.600  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:41.601  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:15:41.601  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:15:41.631  8179  8179 W ExternalStrings: load override strings
08-16 18:15:41.631  8179  8179 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:15:41.631  8179  8179 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 18:15:41.634  8179  8179 D StatusProvider: onCreate
08-16 18:15:41.637  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:15:41.640  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.642  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:15:41.693  8179  8179 V Signer  : override build config not found
08-16 18:15:41.694  8179  8179 D Signer  : value of property debug is false
,08-16 18:15:41.694  8213  8213 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 18:15:41.694  8213  8213 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:15:41.694  8213  8213 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:15:41.695  8213  8213 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 18:15:41.695  8213  8213 D dhcpcd  : wlan0: sending REQUEST (xid 0xa402e41f), next in 4.36 seconds
08-16 18:15:41.731  8213  8213 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 18:15:41.733  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-16 18:15:41.733  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-16 18:15:41.733  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 18:15:41.734  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 18:15:41.734  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 18:15:41.734  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 18:15:41.734  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 18:15:41.735  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 18:15:41.735  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 18:15:41.735  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 18:15:41.735  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 18:15:41.735  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 18:15:41.736  8179  8179 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 18:15:41.745  8179  8179 V LGMDMManager: Create singleton instance
,08-16 18:15:41.772  8213  8213 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-16 18:15:41.772  8213  8213 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-16 18:15:41.773  8213  8213 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 18:15:41.773  8213  8213 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-16 18:15:41.774  8213  8213 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:15:41.774  8213  8213 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 18:15:41.775  8213  8213 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:15:41.775  8213  8213 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 18:15:41.797  8179  8179 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 18:15:41.844  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:41.845  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:41.854  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:15:41.860  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:15:41.866  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:41.868  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:41.876  7937  7937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:15:41.878  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:41.879  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:41.883  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:41.890  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:41.894  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:41.894  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:41.900  7937  7937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:15:41.903  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 18:15:41.908  6871  6871 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 18:15:41.910  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:41.910  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:15:41.910  6871  6871 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:15:41.910  6871  6871 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:15:41.911  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:15:41.911  6871  6871 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:15:41.911  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 18:15:41.911  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:15:41.911  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:15:41.911  6871  6871 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:15:41.911  6871  6871 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 18:15:41.912  6871  6871 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 18:15:42.015  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.016  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 18:15:42.018  8179  8228 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 18:15:42.020  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:15:42.025  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.035  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:42.035  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:42.036  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:42.044  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:15:42.045  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:42.050  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.057  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.063  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:15:42.063  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:42.064  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:42.068  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.069  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:42.078  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.086  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.093  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:42.093  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:42.093  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:42.096  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.097  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:42.104  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.111  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:15:42.118  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:42.118  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:42.119  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:42.124  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.125  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:42.132  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.141  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.148  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:42.148  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:42.148  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:42.151  1033  8203 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 18:15:42.153  1033  8203 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 18:15:42.153  1033  8203 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:15:42.153  1033  8203 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 18:15:42.153  1033  8203 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 18:15:42.153  1033  8203 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:15:42.153  1033  8203 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 18:15:42.153  1033  8203 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 18:15:42.154  1033  8203 D DhcpStateMachine: RunningState
08-16 18:15:42.162  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.162  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 18:15:42.175  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.181  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.190  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:15:42.191  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:42.205  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:15:42.213  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.213  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:42.226  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.238  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.247  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:15:42.248  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:42.250  7937  7937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:15:42.255  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.255  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:15:42.263  8130  8130 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 18:15:42.269  8130  8130 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:15:42.274  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.285  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.296  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:15:42.297  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:15:42.299  7937  7937 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 18:15:42.299  8179  8228 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:42.299  8179  8228 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 18:15:42.300  7937  7937 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:15:42.301  7937  7937 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 18:15:42.308  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:15:42.308  8179  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 18:15:42.318  8130  8130 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 18:15:42.318  8130  8130 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:15:42.328  6871  6871 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:15:42.337  6871  6871 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:15:42.349  7937  7937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:15:42.350  7937  7937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:42.350  7937  7937 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 18:15:42.354  7937  7937 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:15:42.356  7937  7937 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 18:15:42.364  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 18:15:42.366  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.367  6680  6791 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
08-16 18:15:42.367  6680  6791 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
08-16 18:15:42.368  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.370  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.371  6680  6791 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-16 18:15:42.372  6680  6791 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 18:15:42.372  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.372  6680  6791 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
08-16 18:15:42.374  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.375  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.376  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa46604 added. We now have 2 listener(s)
08-16 18:15:42.376  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 18:15:42.376  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.380  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.380  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.380  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.380  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.380  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2cd7ed added. We now have 9 listener(s)
08-16 18:15:42.380  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.382  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:15:42.383  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.385  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.387  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:42.388  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:42.391  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:42.391  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:15:42.392  1033  1921 I ActivityManager: Killing 7318:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-16 18:15:42.394  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.394  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:42.394  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.394  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@281f38b3 added. We now have 3 listener(s)
08-16 18:15:42.396  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.398  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.464  1033  1996 W libprocessgroup: failed to open /acct/uid_10005/pid_7318/cgroup.procs: No such file or directory
08-16 18:15:42.464  1033  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:42.470  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.470  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.470  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.470  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.470  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2603de70 added. We now have 10 listener(s)
08-16 18:15:42.470  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.470  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:42.470  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:42.470  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:42.471  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.471  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.471  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.471  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.471  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa46604 removed from the list
08-16 18:15:42.471  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.472  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2cd7ed removed from the list
08-16 18:15:42.472  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:42.472  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.472  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.472  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.473  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.473  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.473  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.473  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2cd7ed not in the list
08-16 18:15:42.473  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.473  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.474  6680  6791 I org.thaliproj,ect.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.474  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.474  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.475  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2603de70 removed from the list
08-16 18:15:42.475  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.475  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.475  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.475  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.475  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@281f38b3 removed from the list
08-16 18:15:42.476  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.476  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180c05e9 added. We now have 2 listener(s)
08-16 18:15:42.476  1033  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.478  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.478  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.479  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.479  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.479  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2221b26e added. We now have 9 listener(s)
08-16 18:15:42.479  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.479  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:15:42.482  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:42.487  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:42.489  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.489  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:42.489  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.489  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea0719c added. We now have 3 listener(s)
08-16 18:15:42.490  1033  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.493  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.494  8179  8228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 18:15:42.495  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.495  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.495  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.495  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.495  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279617a5 added. We now have 10 listener(s)
08-16 18:15:42.495  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.495  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:42.495  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:42.495  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:42.495  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:42.495  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:42.498  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.499  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:15:42.500  1033  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.504  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:42.505  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:15:42.508  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:42.508  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.510  6680  6791 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:15:42.510  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:42.510  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:42.513  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:42.513  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:42.513  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:42.513  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.513  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.513  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.513  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.514  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180c05e9 removed from the list
08-16 18:15:42.514  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.514  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2221b26e removed from the list
08-16 18:15:42.514  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:42.514  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.514  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.514  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.515  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.515  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.515  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.515  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2221b26e not in the list
08-16 18:15:42.515  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.515  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.516  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.516  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:42.516  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:42.517  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.517  6680  6791 I org.thal,iproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.517  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279617a5 removed from the list
08-16 18:15:42.517  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.517  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.517  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.517  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.517  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea0719c removed from the list
08-16 18:15:42.518  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.518  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29110b88 added. We now have 2 listener(s)
08-16 18:15:42.518  1033  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.521  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.521  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.521  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.521  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.522  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f58921 added. We now have 9 listener(s)
08-16 18:15:42.522  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.522  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:42.527  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:42.529  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:42.532  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:42.534  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.534  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:42.534  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:15:42.534  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15f12f07 added. We now have 3 listener(s)
08-16 18:15:42.534  1033  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.537  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.539  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.539  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.539  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.539  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.539  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.539  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6f5834 added. We now have 10 listener(s)
08-16 18:15:42.539  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.539  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:42.540  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:42.541  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 18:15:42.541  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:42.541  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:42.541  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:42.541  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:42.542  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 18:15:42.543  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 18:15:42.545  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 18:15:42.546  8179  8228 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 18:15:42.546  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing,...
08-16 18:15:42.546  1033  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:15:42.550  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:42.551  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:15:42.553  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:15:42.553  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.555  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 18:15:42.555  6680  6791 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:15:42.555  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:42.555  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:42.555  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:42.555  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.555  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.556  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.556  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.556  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29110b88 removed from the list
08-16 18:15:42.556  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.556  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f58921 removed from the list
08-16 18:15:42.556  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:42.556  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.558  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.558  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.559  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.559  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.559  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.559  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f58921 not in the list
08-16 18:15:42.559  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.559  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:42.561  8179  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 18:15:42.561  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.562  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:42.562  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:42.562  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.562  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.562  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6f5834 removed from the list
08-16 18:15:42.562  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.562  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:42.562  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.562  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.562  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15f12f07 removed from the list
08-16 18:15:42.563  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.563  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de7b4a3 added. We now have 2 listener(s)
08-16 18:15:42.563  1033  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.566  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.566  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.566  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.566  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.566  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3c3a0 added. We now have 9 listener(s)
08-16 18:15:42.566  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.566  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:15:42.574  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:42.578  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:42.580  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.580  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:42.580  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.580  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1815931e added. We now have 3 listener(s)
08-16 18:15:42.580  1033  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.583  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.583  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.583  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.583  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.583  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b36f7ff added. We now have 10 listener(s)
08-16 18:15:42.583  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.584  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:42.584  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:42.584  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:42.584  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:42.584  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:42.586  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.587  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:15:42.588  1033  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.588  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:42.592  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:42.593  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:15:42.595  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:15:42.595  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.597  6680  6791 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:15:42.600  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:42.600  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:42.600  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:42.600  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:15:42.600  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.600  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.601  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.601  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de7b4a3 removed from the list
08-16 18:15:42.601  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.601  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3c3a0 removed from the list
08-16 18:15:42.601  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:42.601  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.602  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.602  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.603  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.603  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.603  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.603  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3c3a0 not in the list
08-16 18:15:42.603  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.603  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.604  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.604  6680  6791 D BluetoothLeScanner: could not find callback wrapper
08-16 18:15:42.605  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:42.605  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.605  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.605  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b36f7ff removed from the list
08-16 18:15:42.605  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.605  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.605  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.605  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.605  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1815931e removed from the list
08-16 18:15:42.606  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.606  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a83c,32a added. We now have 2 listener(s)
08-16 18:15:42.607  1033  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.609  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.609  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.609  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.609  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.609  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0d151b added. We now have 9 listener(s)
08-16 18:15:42.610  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.610  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:42.614  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:42.618  6680  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:42.619  6680  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:42.619  6680  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:42.620  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:42.620  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1501fc91 added. We now have 3 listener(s)
08-16 18:15:42.620  1033  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:15:42.622  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.624  6680  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:42.624  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:15:42.625  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:42.625  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:42.625  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:42.625  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2e7f6 added. We now have 10 listener(s)
08-16 18:15:42.625  6680  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:42.625  6680  6791 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:42.626  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:42.626  6680  6791 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:42.626  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.626  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.626  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:42.626  6680  6791 I org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.626  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a83c32a removed from the list
08-16 18:15:42.626  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.626  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0d151b removed from the list
08-16 18:15:42.626  6680  6791 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:42.626  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.627  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.627  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.627  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.628  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.628  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.628  6680  6791 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c0d151b not in the list
08-16 18:15:42.628  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.628  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:42.629  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:42.629  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:42.629  6680  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:42.629  6680  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2e7f6 removed from the list
08-16 18:15:42.629  6680  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:42.629  6680  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:42.629  6680  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:42.629  6680  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:42.629  6680  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1501fc91 removed from the list
08-16 18:15:42.630  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 18:15:42.631  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 18:15:42.631  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 18:15:42.631  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:42.631  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 18:15:42.631  6680  6791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:42.645  6680  8263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
08-16 18:15:42.645  6680  8263 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
08-16 18:15:42.646  6680  8263 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:15:42.650  6680  8264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
08-16 18:15:42.650  6680  8264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
08-16 18:15:42.650  6680  8264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:15:42.652  6680  6791 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 18:15:42.652  6680  6791 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 18:15:42.652  6680  6791 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 18:15:42.652  6680  6791 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 18:15:42.653  6680  6791 D com.test.thalitest.ThaliTestRunner: Total duration: 23077 ms
08-16 18:15:42.654  6680  6791 I jxcore-log: Total number of executed tests:  80
08-16 18:15:42.654  6680  6791 I jxcore-log: 
08-16 18:15:42.654  6680  6791 I jxcore-log: Number of passed tests:  80
08-16 18:15:42.654  6680  6791 I jxcore-log: 
08-16 18:15:42.654  6680  6791 I jxcore-log: Number of failed tests:  0
08-16 18:15:42.654  6680  6791 I jxcore-log: 
08-16 18:15:42.655  6680  6791 I jxcore-log: Number of ignored tests:  0
08-16 18:15:42.655  6680  6791 I jxcore-log: 
08-16 18:15:42.655  6680  6791 I jxcore-log: Total duration:  23077
08-16 18:15:42.655  6680  6791 I jxcore-log: 
08-16 18:15:42.656  6680  6791 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 18:15:42.656  6680  6791 I jxcore-log: 
,08-16 18:15:42.663  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.663  6680  6791 I jxcore-log: 
08-16 18:15:42.666  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.666  6680  6791 I jxcore-log: 
08-16 18:15:42.668  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.668  6680  6791 I jxcore-log: 
08-16 18:15:42.669  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.669  6680  6791 I jxcore-log: 
08-16 18:15:42.670  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.670  6680  6791 I jxcore-log: 
,08-16 18:15:42.673  6680  6680 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-16 18:15:42.675  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:42.675  6680  6791 I jxcore-log: 
08-16 18:15:42.679  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.679  6680  6791 I jxcore-log: 
08-16 18:15:42.681  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.681  6680  6791 I jxcore-log: 
08-16 18:15:42.682  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:42.682  6680  6791 I jxcore-log: 
08-16 18:15:42.684  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:42.684  6680  6791 I jxcore-log: 
,08-16 18:15:42.685  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:42.685  6680  6791 I jxcore-log: 
08-16 18:15:42.686  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.686  6680  6791 I jxcore-log: 
08-16 18:15:42.687  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.687  6680  6791 I jxcore-log: 
08-16 18:15:42.688  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.688  6680  6791 I jxcore-log: 
08-16 18:15:42.689  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.689  6680  6791 I jxcore-log: 
08-16 18:15:42.690  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.690  6680  6791 I jxcore-log: 
08-16 18:15:42.691  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.691  6680  6791 I jxcore-log: 
08-16 18:15:42.692  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.692  6680  6791 I jxcore-log: 
08-16 18:15:42.693  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:42.693  6680  6791 I jxcore-log: 
08-16 18:15:42.694  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:42.694  6680  6791 I jxcore-log: 
,08-16 18:15:42.695  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:42.695  6680  6791 I jxcore-log: 
08-16 18:15:42.696  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.696  6680  6791 I jxcore-log: 
08-16 18:15:42.697  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.697  6680  6791 I jxcore-log: 
08-16 18:15:42.698  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.698  6680  6791 I jxcore-log: 
08-16 18:15:42.699  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.699  6680  6791 I jxcore-log: 
08-16 18:15:42.700  6680  6791 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:42.700  6680  6791 I jxcore-log: 
08-16 18:15:42.916  1033  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:42.917  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:42.918  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:42.919  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:42.920  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:15:42.921  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 18:15:42.923  1033  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 18:15:42.923  1033  1544 D ConnectivityService: identical MTU - not setting
08-16 18:15:42.924  1033  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 18:15:42.924  1033  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 18:15:42.924  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:42.924  1033  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:42.926  1033  1544 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:15:42.927  1602  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 18:15:43.021  8267  8267 D AndroidRuntime: 
08-16 18:15:43.021  8267  8267 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 18:15:43.026  8267  8267 D AndroidRuntime: CheckJNI is OFF
08-16 18:15:43.187  7684  7983 D UEI.SmartControl: Internal timer expired: 2
08-16 18:15:43.187  7684  7983 D UEI.SmartControl: unbind internal service
,08-16 18:15:43.195  8267  8267 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 18:15:43.208  1033  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 18:15:43.209  1033  1091 I ActivityManager: Killing 6680:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 18:15:43.247  1033  1921 I WindowState: WIN DEATH: Window{14cee9a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 18:15:43.248  1033  1543 D WifiService: Client connection lost with reason: 4
,08-16 18:15:43.253  1033  1921 D InputDispatcher: Window went away: Window{14cee9a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 18:15:43.376  1033  1091 I ActivityManager:   Force finishing activity ActivityRecord{2a37fbc7 u0 com.test.thalitest/.MainActivity t6}
,08-16 18:15:43.407   341   367 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 18:15:43.419  1033  2032 W ActivityManager: Spurious death for ProcessRecord{211782d3 6680:com.test.thalitest/u0a118}, curProc for 6680: null
08-16 18:15:43.420  1033  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-16 18:15:43.424  1033  1116 I ActivityManager:   Force finishing activity ActivityRecord{2a37fbc7 u0 com.test.thalitest/.MainActivity t6 f}
08-16 18:15:43.425  1033  1116 W ActivityManager: Duplicate finish request for ActivityRecord{2a37fbc7 u0 com.test.thalitest/.MainActivity t6 f}
,08-16 18:15:43.451  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-16 18:15:43.452  1941  2539 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 18:15:43.453  1941  2539 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2315a78c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 18:15:43.454  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 18:15:43.455  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b8d2ed5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 18:15:43.455  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-16 18:15:43.462  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 18:15:43.463  2033  2126 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-16 18:15:43.467  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 18:15:43.468  1905  1905 D ActionManagerService: notifyUserLog: 1000003
,08-16 18:15:43.469  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 18:15:43.470  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 18:15:43.471  3764  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 18:15:43.485  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-16 18:15:43.488  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 18:15:43.488  3764  3764 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 18:15:43.490  7753  7753 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 18:15:43.490  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 18:15:43.496  4593  4593 I art     : Explicit concurrent mark sweep GC freed 8188(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 522us total 52.039ms
,08-16 18:15:43.499  2500  2661 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 18:15:43.504  4489  4489 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 18:15:43.505  4489  4489 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 18:15:43.505  4489  4489 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 18:15:43.505  4489  4489 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 18:15:43.505  4489  4489 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:15:43.505  4489  4489 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:15:43.505  4489  4489 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:15:43.505  4489  4489 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:43.505  4489  4489 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:43.505  4489  4489 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:43.505  4489  4489 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:15:43.505  4489  4489 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 18:15:43.507  8179  8179 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 18:15:43.532  1033  1497 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 18:15:43.545  1033  1956 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:43.546  7684  7977 D serial_port: close(fd = 24)
08-16 18:15:43.548  7684  7977 I UEI.SmartControl: Serial port is closed.
,08-16 18:15:43.555  1033  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
08-16 18:15:43.569  1033  1033 D administrator: Handling package changes for user 0
,08-16 18:15:43.599  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-16 18:15:43.605  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 18:15:43.614  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-16 18:15:43.615  3764  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-16 18:15:43.615  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 18:15:43.630  1602  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 18:15:43.630  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.631  3764  4478 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:15:43.632  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-16 18:15:43.638  1602  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 18:15:43.638  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.645  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-16 18:15:43.646  1602  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:43.646  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 18:15:43.647  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 18:15:43.651  2208  2208 I ConfigService: onCreate
08-16 18:15:43.651  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 18:15:43.655  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:15:43.655  1602  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 18:15:43.656  1602  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 18:15:43.656  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.657  1869  1869 D SplitUIManager: split_name #11 / not available #0
,08-16 18:15:43.657  1869  1869 D SplitUIService: removed split : 
08-16 18:15:43.658  2208  2208 I ConfigService: onBind returning update interface
08-16 18:15:43.662  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 18:15:43.662  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , display: false
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , animation: false }
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , display: false
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , animation: false }
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , display: false
08-16 18:15:43.663  2033  2033 I GBoardWebViewUtils: , animation: false }
08-16 18:15:43.663  1033  2032 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:43.663  1033  2032 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:15:43.665  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:15:43.665  1602  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 18:15:43.669  2033  8298 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-16 18:15:43.673  1602  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 18:15:43.673  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.673  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 18:15:43.673  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 18:15:43.679  1602  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:43.679  1602  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 18:15:43.679  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 18:15:43.679  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 18:15:43.686  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:15:43.686  1602  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 18:15:43.692  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 18:15:43.692  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 18:15:43.692  2208  2208 I ConfigService: onBind returning config service
08-16 18:15:43.693  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 18:15:43.696  1602  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 18:15:43.696  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.698  1817  1817 I ConfigFetchService: service connected
,08-16 18:15:43.726  1033  1966 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:15:43.728  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 18:15:43.728  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-16 18:15:43.728  1869  1869 I SplitUIService: split app #11
08-16 18:15:43.732  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-16 18:15:43.732  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 18:15:43.740  2208  2208 I ConfigService: onDestroy
,08-16 18:15:43.743  1817  8300 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 18:15:43.749  1602  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 18:15:43.749  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.751  1602  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 18:15:43.751  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.752  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:15:43.752  1602  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 18:15:43.753  1602  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 18:15:43.753  1602  1662 D KeyguardModel: createShortcutInfo...
,08-16 18:15:43.754  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:15:43.754  1602  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 18:15:43.757  1602  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 18:15:43.757  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.765  5969  8305 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 18:15:43.772  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:15:43.772  1602  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 18:15:43.773  1602  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 18:15:43.773  1602  1662 D KeyguardModel: createShortcutInfo...
08-16 18:15:43.776  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 18:15:43.777  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 18:15:43.777  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 18:15:43.778  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 18:15:43.779  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 18:15:43.784  1033  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-16 18:15:43.788  1817  4768 I Icing   : doRemovePackageData com.test.thalitest
08-16 18:15:43.788  1817  8308 I PeopleContactsSync: CP2 sync disabled
08-16 18:15:43.800  1033  1649 V SIM_STK : Menu title from STK is T-Mobile
,08-16 18:15:43.800  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-16 18:15:43.800  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 18:15:43.809  1817  8306 W GmsApplication: Using Auth Proxy for data requests.
08-16 18:15:43.816  1817  8306 W GmsApplication: Using Auth Proxy for data requests.
08-16 18:15:43.822   335   402 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 18:15:43.823  3186  8310 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-16 18:15:43.835  7084  7084 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-16 18:15:43.849  2380  8312 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 18:15:43.862  1033  1116 I art     : Explicit concurrent mark sweep GC freed 84843(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 5.017ms total 255.479ms
,08-16 18:15:43.866  1033  2050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8313 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 18:15:43.876  2208  2228 I art     : Explicit concurrent mark sweep GC freed 6890(398KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 658us total 30.909ms
,08-16 18:15:43.889  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-16 18:15:43.891  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:43.892  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 18:15:43.893  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 18:15:43.895  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 18:15:43.896  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-16 18:15:43.913  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 18:15:43.913  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 18:15:43.915  1033  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{376b13a7 u0 com.lge.launcher2/.Launcher t5} time:138543
08-16 18:15:43.921  2033  2172 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 18:15:43.921  2033  2172 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 18:15:43.923  8267  8267 D AndroidRuntime: Shutting down VM
08-16 18:15:43.934  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-16 18:15:43.934  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 18:15:43.934  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:43.958  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-16 18:15:43.965  8313  8313 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:43.966  8313  8313 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:15:43.967  8313  8313 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 18:15:43.967  8313  8313 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 18:15:43.983  1033  1116 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8334 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 18:15:43.988  2033  2033 D [Concierge]WidgetView: change position of spinner
08-16 18:15:43.988  2578  2578 D [Concierge]Service: onStartCommand(). Type : 8
08-16 18:15:43.988  2578  2578 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 18:15:43.988  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1471364143988
08-16 18:15:43.989  2578  2578 D [Concierge]Service: Update widget ID : 11
08-16 18:15:43.989  2578  2578 D [Concierge]Service: onStartCommand(). Type : 0
08-16 18:15:44.007  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 32964004
,08-16 18:15:44.007  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 18:15:44.007  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 18:15:44.010  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@34ab21ea
08-16 18:15:44.010  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 18:15:44.011  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-16 18:15:44.011  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:44.016  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 18:15:44.017  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 18:15:44.017  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 18:15:44.017  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471364033286, New one : 1471364143988
08-16 18:15:44.017  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-16 18:15:44.018  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 18:15:44.018  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:44.019  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 18:15:44.020  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 18:15:44.021  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 18:15:44.023  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 18:15:44.024  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-16 18:15:44.028  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:44.029  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:44.031  1033  1996 I ActivityManager: Killing 7783:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 18:15:44.037  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:44.042  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 18:15:44.064  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 18:15:44.071  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 18:15:44.071  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 18:15:44.072  1033  1050 W libprocessgroup: failed to open /acct/uid_10072/pid_7783/cgroup.procs: No such file or directory
08-16 18:15:44.073  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:15:44.074  8313  8313 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 18:15:44.084  8313  8313 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 18:15:44.089  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 18:15:44.093  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dd77b39 time:138721
08-16 18:15:44.105  8313  8313 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 18:15:44.123  8313  8313 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:15:44.123  8313  8313 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:15:44.169  8313  8313 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 18:15:44.178  1033  1049 I ActivityManager: Killing 7876:com.android.vending/u0a44 (adj 15): empty #17
08-16 18:15:44.210  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 18:15:44.243  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 18:15:44.243  1033  1887 W libprocessgroup: failed to open /acct/uid_10044/pid_7876/cgroup.procs: No such file or directory
08-16 18:15:44.243  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-16 18:15:44.245  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 18:15:44.248  2033  2868 I GBoardtInterface: onReloaded()
08-16 18:15:44.250  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 18:15:44.251  3764  4478 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:15:44.251  8179  8179 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 18:15:44.254  8179  8179 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 18:15:44.254  3764  3780 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 18:15:44.257  7524  7524 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-16 18:15:44.260  6871  6871 D PackageIntentReceiver: Not supported Hotkey customization function 
08-16 18:15:44.267  6871  6871 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-16 18:15:44.267  6871  6871 D HideNavigationAppsReceiver: replacing : false
08-16 18:15:44.268  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,08-16 18:15:44.269  3764  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 18:15:44.270  3764  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 18:15:44.272  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-16 18:15:44.273  3764  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 18:15:44.273  3764  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 18:15:44.273  3764  4481 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 18:15:44.273  3764  4481 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 18:15:44.273  3764  4478 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:15:44.275  6871  6871 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-16 18:15:44.275  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 18:15:44.275  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 18:15:44.276  6871  6871 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-16 18:15:44.276  6871  6871 D ButtonCombinationReceiver: replacing : false
08-16 18:15:44.277  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 18:15:44.277  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 18:15:44.279  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 18:15:44.279  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-16 18:15:44.304  1033  2032 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8358 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
