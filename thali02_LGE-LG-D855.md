#### Test 814185773fe89cf_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 08:37:26.746  6680  6680 D TAG     : onCreate()
08-29 08:37:26.767  6680  6680 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 08:37:27.693  1817  4792 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-29 08:37:27.865  1817  4792 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-29 08:37:27.947  1817  4792 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-29 08:37:27.995  6706  6706 D AndroidRuntime: 
08-29 08:37:27.995  6706  6706 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 08:37:27.998  6706  6706 D AndroidRuntime: CheckJNI is OFF
08-29 08:37:28.132  6706  6706 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 08:37:28.137  1034  1923 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 08:37:28.171  1941  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 08:37:28.182  1034  1923 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 08:37:28.184  1034  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{5a2cc25 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 08:37:28.184  1034  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{5a2cc25 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 08:37:28.186  1034  1923 D WindowStateEx: AppWindowTokenEx init.. 
08-29 08:37:28.187   338   409 E GBMv2   : DFP En is all cleared set to be enabled
08-29 08:37:28.219  1034  1923 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6741 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 08:37:28.221  6706  6706 D AndroidRuntime: Shutting down VM
08-29 08:37:28.282  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 08:37:28.282  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3cc01ef2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 08:37:28.284  1941  2940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 08:37:28.284  1941  2940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{8671943 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 08:37:28.306  6680  6680 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:28.306  6680  6680 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 08:37:28.336  6741  6741 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 08:37:28.410  6741  6741 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 08:37:28.417  6741  6741 I LibraryLoader: Loading: webviewchromium
08-29 08:37:28.420  6741  6741 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5144-5147)
08-29 08:37:28.420  6741  6741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:37:28.442  6741  6741 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e343b70}
,08-29 08:37:28.443  6741  6741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:37:28.443  6741  6741 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 08:37:28.453  6741  6741 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 08:37:28.454  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 08:37:28.457  6272  6272 I LockScreenSettings: New app installed broadcast received ..
08-29 08:37:28.462  6272  6272 I LockScreenSettings: Number of installed packages  1
08-29 08:37:28.467  6741  6741 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 08:37:28.468  6741  6741 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 08:37:28.468  6741  6741 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 08:37:28.469  6680  6680 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-29 08:37:28.474   315  1399 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-29 08:37:28.480  6741  6741 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 08:37:28.480  6741  6741 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 08:37:28.480  6741  6741 I Adreno-EGL: Build Date: 12/12/14 금
08-29 08:37:28.480  6741  6741 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 08:37:28.480  6741  6741 I Adreno-EGL: Remote Branch: 
08-29 08:37:28.480  6741  6741 I Adreno-EGL: Local Patches: 
08-29 08:37:28.480  6741  6741 I Adreno-EGL: Reconstruct Branch: 
08-29 08:37:28.482  1034  1116 D BluetoothManagerService: Message: 20
,08-29 08:37:28.484  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a92b220:true
08-29 08:37:28.522  1034  1958 V SIM_STK : Menu title from STK is T-Mobile
,08-29 08:37:28.568  1034  1904 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6788 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 08:37:28.581  6741  6776 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 08:37:28.587  6741  6741 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 08:37:28.606  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 08:37:28.611  6741  6741 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 08:37:28.615  6741  6741 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 08:37:28.618  6741  6741 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 08:37:28.618  6741  6741 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-29 08:37:28.634  6741  6741 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 08:37:28.639  6788  6788 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 08:37:28.639  6788  6788 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 08:37:28.674  1034  1995 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6807 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 08:37:28.675  1034  1995 I ActivityManager: Killing 5886:com.google.android.gm/u0a64 (adj 15): empty #17
08-29 08:37:28.676  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 08:37:28.676  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 08:37:28.742  6741  6824 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:28.742  6741  6824 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:28.754  1034  1575 W libprocessgroup: failed to open /acct/uid_10064/pid_5886/cgroup.procs: No such file or directory
,08-29 08:37:28.779  6741  6832 D OpenGLRenderer: Render dirty regions requested: true
08-29 08:37:28.779  6741  6832 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 08:37:28.782  1034  1100 W ActivityManager: Activity pause timeout for ActivityRecord{a2261fa u0 com.test.thalitest/.MainActivity t6}
,08-29 08:37:28.786  6741  6832 D OpenGLRenderer: Enabling debug mode 0
08-29 08:37:28.804  6741  6741 D Atlas   : Validating map...
,08-29 08:37:28.808  1034  1699 D SplitWindow: check instance of lgWin Window{812655a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 08:37:28.851  6807  6807 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 08:37:28.869  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 08:37:28.869  6807  6807 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 08:37:28.906  1034  1575 I ActivityManager: Killing 5930:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 08:37:28.920  6741  6741 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@226f8ff time:105648
,08-29 08:37:29.003  6741  6741 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 08:37:29.008  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +727ms (total +821ms)
08-29 08:37:29.009  1034  2031 W libprocessgroup: failed to open /acct/uid_10072/pid_5930/cgroup.procs: No such file or directory
08-29 08:37:29.009  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a2261fa u0 com.test.thalitest/.MainActivity t6} time:105736
08-29 08:37:29.037  6741  6741 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 08:37:29.037  6741  6741 I chromium: 
,08-29 08:37:29.058  6741  6824 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 08:37:29.058  6741  6824 I chromium: 
,08-29 08:37:29.156  6741  6839 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-29 08:37:29.169  6741  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 08:37:29.169  6741  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 08:37:29.169  6741  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 08:37:29.169  6741  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 08:37:29.169  6741  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 08:37:29.169  6741  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@349f3d93 added. We now have 1 listener(s)
,08-29 08:37:29.174  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:29.177  6741  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 08:37:29.179  6741  6839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:37:29.181  6741  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:37:29.181  6741  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 08:37:29.187  6741  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d99a4ce added. We now have 1 listener(s)
08-29 08:37:29.188  6741  6839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:29.194  1034  1421 D WifiService: New client listening to asynchronous messages
,08-29 08:37:29.197  6741  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:37:29.198  6741  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 08:37:29.199  6741  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 08:37:29.199  6741  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 08:37:29.199  6741  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 08:37:29.203  6741  6839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:29.205  1034  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:29.206  6741  6839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-29 08:37:29.220  6741  6839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:29.221  6741  6839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:29.221  6741  6839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 08:37:29.221  6741  6839 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:37:29.224  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:29.226  6741  6839 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 08:37:29.227  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:29.251  6741  6741 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 08:37:30.118   338   412 E GBMv2   : DFP En is all cleared set to be enabled
08-29 08:37:30.119   338   412 E GBMv2   : Set value is all cleared set the max
08-29 08:37:30.119   338   412 I GBMv2   : DFP Enabled. Ignore VFP set
,08-29 08:37:30.126  2797  2797 I MusicWidget: mDelayedStopHandler : unbind
08-29 08:37:30.132  2148  2148 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-29 08:37:30.136  2148  2148 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 08:37:30.137  2148  2148 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 08:37:30.141  2148  2148 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 08:37:30.141  2148  2148 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 08:37:30.143  2148  2148 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 08:37:30.144  2148  2148 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 08:37:30.144  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-29 08:37:30.146  1034  1049 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3dbb1459com.lge.music.MediaPlaybackService$5@1eb0f81e
08-29 08:37:30.147  2148  2148 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 08:37:30.147  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.148  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.149  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.149  2148  2148 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@35f99e9c
08-29 08:37:30.149  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.150  2148  2148 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 08:37:30.150  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.150  2148  2148 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 08:37:30.151  2148  2148 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 08:37:30.151  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.151  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.151  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.152  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.152  2148  2148 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 08:37:30.153  2148  2148 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 08:37:30.155  2148  2148 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 08:37:30.155  2148  2148 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 08:37:30.155  2148  2148 V MediaPlayer[Native]: reset
08-29 08:37:30.159  2148  2148 V MediaPlayer[Native]: setListener
08-29 08:37:30.159  2148  2148 V MediaPlayer[Native]: disconnect
08-29 08:37:30.159  2148  2148 V MediaPlayer[Native]: destructor
08-29 08:37:30.160   315  1399 V AudioFlinger: releasing 16 from 2148 for -1
08-29 08:37:30.160   315  1399 V AudioFlinger:  decremented refcount to 0
08-29 08:37:30.160   315  1399 V AudioFlinger: purging stale effects
08-29 08:37:30.161  2148  2148 V MediaPlayer[Native]: disconnect
08-29 08:37:30.161  2148  2148 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 08:37:30.162  2148  2148 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 08:37:30.162  2148  2148 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
,08-29 08:37:30.164  2148  2148 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 08:37:30.164  2148  2148 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 08:37:30.165  2148  2148 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 08:37:30.165  2148  2148 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 36108543
08-29 08:37:30.165  2148  2148 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 36108543
08-29 08:37:30.173  2148  2148 I SmartShareClient: [SmartShareManagerClient] terminate service: 2148/MediaPlaybackService/273689378
08-29 08:37:30.175  2148  2148 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 08:37:30.175  2148  2148 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1eafe6cc
08-29 08:37:30.177  2148  2148 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 08:37:30.177  2148  2148 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 08:37:30.178  2148  2148 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 08:37:30.178  2148  2148 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,08-29 08:37:30.180  2148  2148 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
08-29 08:37:30.181  1034  1994 I ActivityManager: Killing 5698:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 08:37:30.204  5677  5677 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 08:37:30.204  5677  5677 W System.err: android.os.DeadObjectException
08-29 08:37:30.205  5677  5677 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 08:37:30.205  5677  5677 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-29 08:37:30.205  5677  5677 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:37:30.205  5677  5677 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 08:37:30.205  5677  5677 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:30.205  5677  5677 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 08:37:30.206  5677  5677 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 08:37:30.206  5677  5677 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 08:37:30.206  5677  5677 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 08:37:30.206  5677  5677 W System.err: android.os.DeadObjectException
08-29 08:37:30.206  5677  5677 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 08:37:30.206  5677  5677 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 08:37:30.206  5677  5677 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:37:30.206  5677  5677 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 08:37:30.207  5677  5677 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:30.207  5677  5677 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 08:37:30.207  5677  5677 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 08:37:30.207  5677  5677 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 08:37:30.207  5677  5677 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 08:37:30.208  5677  5677 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 08:37:30.324  6741  6842 W jxcore-log: Initializing JXcore engine
08-29 08:37:30.324  6741  6842 W jxcore-log: JXcore engine is ready
,08-29 08:37:30.357  6842  6842 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8346]" dev="sockfs" ino=8346 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 08:37:30.357  6842  6842 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 08:37:30.357  6842  6842 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9546]" dev="sockfs" ino=9546 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 08:37:30.357  6842  6842 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 08:37:30.357  6842  6842 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32173]" dev="sockfs" ino=32173 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 08:37:30.380  6741  6842 W jxcore-log: Starting JXcore engine
08-29 08:37:30.434  1034  1699 W libprocessgroup: failed to open /acct/uid_1000/pid_5698/cgroup.procs: No such file or directory
08-29 08:37:30.435  1034  1699 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 08:37:30.441  5677  5677 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 08:37:30.441  5677  5677 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 08:37:30.495  1034  2033 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6851 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 08:37:30.496  5677  5677 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 08:37:30.508  6741  6842 W jxcore-log: Platform android
08-29 08:37:30.508  6741  6842 W jxcore-log: 
08-29 08:37:30.508  6741  6842 W jxcore-log: Process ARCH arm
08-29 08:37:30.508  6741  6842 W jxcore-log: 
,08-29 08:37:30.598  6851  6851 D UEI.SmartControl: Quickset Services start...
08-29 08:37:30.601  6851  6851 I UEI.SmartControl: Manufacture = LGE
08-29 08:37:30.601  6851  6851 D UEI.SmartControl: Id = LGNevo
08-29 08:37:30.602  6851  6851 D UEI.SmartControl: File observer start...
,08-29 08:37:30.603  6851  6851 E UEI.SmartControl: IR Port is disabled: false
08-29 08:37:30.603  6851  6851 D UEI.SmartControl: Starting file observer...
08-29 08:37:30.604  6851  6851 D UEI.SmartControl: Extracting JNI libs...
08-29 08:37:30.604  6851  6851 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 08:37:30.693  6851  6851 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 08:37:30.693  6851  6851 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 08:37:30.693  6851  6851 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 08:37:30.729  6851  6851 I UEI.SmartControl: --- Selecting new region: 6,
,08-29 08:37:30.731  6851  6851 I UEI.SmartControl: Model = LG-D855
08-29 08:37:30.733  6851  6851 D UEI.SmartControl: QS Service created
08-29 08:37:30.750  6851  6851 I UEI.SmartControl: Service initServices...
08-29 08:37:30.754  6851  6851 D UEI.SmartControl: QS start get config
,08-29 08:37:30.817  6851  6851 D UEI.SmartControl: Loading JNI Libs...
,08-29 08:37:30.922  6741  6842 I jxcore-log: JXcore Cordova bridge is ready!
08-29 08:37:30.922  6741  6842 I jxcore-log: 
,08-29 08:37:30.922  6741  6842 W jxcore-log: JXcore engine is started
,08-29 08:37:30.931  6741  6839 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 08:37:30.934  6741  6741 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 08:37:31.218  6851  6851 I UEI.SmartControl: Supports setup maps: true
,08-29 08:37:31.223  6851  6851 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 08:37:31.224  6851  6851 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 08:37:31.224  6851  6851 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 08:37:31.224  6851  6851 I UEI.SmartControl: ### init IR Blaster...
08-29 08:37:31.229  6851  6851 D serial_port: Configuring serial port
08-29 08:37:31.237  6851  6851 E UEI.SmartControl: UEIBLaster setting for 616
08-29 08:37:31.237  6851  6851 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 08:37:31.238  6851  6851 I UEI.SmartControl: configuring settings for MAXQ616
08-29 08:37:31.239  6851  6851 I UEI.SmartControl: Get version...
,08-29 08:37:31.259  6851  6870 D UEI.SmartControl: serial port data available: 21,
,08-29 08:37:31.285  6851  6851 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 08:37:31.285  6851  6851 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 08:37:31.285  6851  6851 I UEI.SmartControl: QS saving settings...
08-29 08:37:31.286  6851  6851 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 08:37:31.303  6851  6870 D UEI.SmartControl: serial port data available: 4
,08-29 08:37:31.339  6851  6873 I UEI.SmartControl: Device manager: loading config....
08-29 08:37:31.340  6851  6873 D UEI.SmartControl: ----------- loading internal config...
08-29 08:37:31.341  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 08:37:31.350  6851  6851 E UEI.SmartControl: Services init done
08-29 08:37:31.350  6851  6851 D UEI.SmartControl: QS Service init finished
08-29 08:37:31.352  6851  6851 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 08:37:31.353  6851  6851 D UEI.SmartControl: QS Service version code: 201091
08-29 08:37:31.354  6851  6851 D UEI.SmartControl: Service requested: Control
08-29 08:37:31.361  6851  6873 E UEI.SmartControl: Loading SETTINGS...
,08-29 08:37:31.366  6851  6851 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 08:37:31.370  5677  5677 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 08:37:31.370  1034  1905 I ActivityManager: Killing 5677:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 08:37:31.372  6851  6866 I UEI.SmartControl: ------ IControl API: 11
08-29 08:37:31.375  6851  6866 I UEI.SmartControl: Registering callback...
,08-29 08:37:31.385  6851  6873 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 08:37:31.397  6851  6872 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 08:37:31.397  6851  6872 D UEI.SmartControl: -----service ready thread exits
,08-29 08:37:31.582  1034  1995 W libprocessgroup: failed to open /acct/uid_10112/pid_5677/cgroup.procs: No such file or directory
08-29 08:37:31.583  6851  6851 D UEI.SmartControl: Internal service binding...
,08-29 08:37:32.399  6680  6680 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 08:37:32.407  1034  2031 I ActivityManager: Killing 5259:com.android.calendar/u0a13 (adj 15): empty #17
08-29 08:37:32.475  1034  1049 W libprocessgroup: failed to open /acct/uid_10013/pid_5259/cgroup.procs: No such file or directory
,08-29 08:37:33.383  6680  6758 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 08:37:36.343  6851  6874 D UEI.SmartControl: Internal timer expired: 1
,08-29 08:37:36.343  6851  6874 D UEI.SmartControl: unbind internal service
,08-29 08:37:36.350  6851  6871 D serial_port: close(fd = 25)
08-29 08:37:36.361  6851  6851 D UEI.SmartControl: Service.onUnbind: IControl
,08-29 08:37:36.364  6851  6851 D UEI.SmartControl: Service.onDestroy
,08-29 08:37:36.364  6851  6851 D UEI.SmartControl: Lock is in USE false
,08-29 08:37:36.364  6851  6851 D UEI.SmartControl: unbind internal service
08-29 08:37:36.365  6851  6851 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35f99e9c
08-29 08:37:36.365  6851  6851 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 08:37:36.365  6851  6851 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 08:37:36.365  6851  6851 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:37:36.365  6851  6851 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 08:37:36.366  6851  6851 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:36.366  6851  6851 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-29 08:37:36.366  6851  6851 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 08:37:36.366  6851  6851 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 08:37:36.366  6851  6851 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35f99e9c
08-29 08:37:36.368  6851  6871 I UEI.SmartControl: Serial port is closed.
,08-29 08:37:36.369  6851  6851 I UEI.SmartControl: Serial port is closed.
08-29 08:37:36.369  6851  6851 I UEI.SmartControl: Serial port is closed.
08-29 08:37:36.369  6851  6851 D UEI.SmartControl: Blaster closed
08-29 08:37:36.369  6851  6851 D UEI.SmartControl: Shut down QS...
08-29 08:37:36.369  6851  6851 D UEI.SmartControl: Stopping QS lib
,08-29 08:37:36.369  6851  6851 D UEI.SmartControl: QS lib stop result = true
08-29 08:37:36.369  6851  6851 D UEI.SmartControl: Stopped QS lib
08-29 08:37:36.370  6851  6851 D UEI.SmartControl: Stopped file observer...
08-29 08:37:36.370  6851  6851 D UEI.SmartControl: QS shutdown complete
,08-29 08:37:40.183  2148  2148 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19995
,08-29 08:37:40.527  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 08:37:40.527  6741  6842 I jxcore-log: 
,08-29 08:37:40.530  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 08:37:40.530  6741  6842 I jxcore-log: 
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:40.535  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:40.537  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:40.540  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 08:37:40.540  6741  6842 I jxcore-log: 
,08-29 08:37:40.542  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 08:37:40.542  6741  6842 I jxcore-log: 
,08-29 08:37:40.887  1034  1100 I ActivityManager: Waited long enough for: ServiceRecord{3ab7338d u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 08:37:41.043  6741  6842 D executeNativeTests: Running unit tests
,08-29 08:37:41.127  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:37:41.127  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 added. We now have 2 listener(s)
,08-29 08:37:41.131  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 08:37:41.133  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 08:37:41.133  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:37:41.133  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:37:41.133  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:37:41.133  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 added. We now have 2 listener(s)
08-29 08:37:41.133  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:41.133  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:37:41.136  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:41.139  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:41.140  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.140  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:41.144  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:37:41.145  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 08:37:41.145  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 08:37:41.147  6741  6842 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 08:37:41.148  6741  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 08:37:41.148  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:37:41.148  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:41.148  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:41.149  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.149  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.150  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.150  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.150  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.150  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:41.150  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:37:41.150  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 removed from the list
08-29 08:37:41.150  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.150  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 removed from the list
08-29 08:37:41.152  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:41.153  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 08:37:41.153  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:41.153  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:41.154  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:41.154  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:41.154  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.154  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 08:37:41.154  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:41.154  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.157  6741  6842 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 08:37:41.158  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:41.158  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.158  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:41.158  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:41.158  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.158  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 08:37:41.158  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list,
,08-29 08:37:41.158  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:41.158  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.158  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:41.158  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.158  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.158  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 08:37:41.158  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.160  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:37:41.160  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:37:41.160  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.160  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:37:41.164  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:37:41.165  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.165  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.165  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:41.165  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.165  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.165  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.165  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.165  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.165  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
,08-29 08:37:41.165  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:41.165  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.165  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.166  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.166  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:41.166  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.166  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.166  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.166  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.167  6741  6842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 08:37:41.169  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:41.171  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:41.172  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.172  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:41.173  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.174  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.175  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:37:41.175  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:37:41.175  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:37:41.175  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.175  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:37:41.178  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:37:41.178  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:41.182  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:37:41.186  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:37:41.187  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 08:37:41.188  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 08:37:41.189  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:41.190  6741  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 08:37:41.190  6741  6842 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:37:41.192  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.192  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:37:41.192  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.192  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.192  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.192  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:41.192  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list,
08-29 08:37:41.192  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.192  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.192  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.193  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.193  6741  6842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-29 08:37:41.194  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:41.196  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:41.197  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.197  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:41.198  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.199  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.199  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:37:41.199  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 08:37:41.199  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:37:41.199  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.199  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:37:41.202  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:37:41.202  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:37:41.203  6741  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 08:37:41.203  6741  6842 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:37:41.204  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.204  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.204  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:41.205  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.205  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.205  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:41.205  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.205  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:41.205  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.205  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.205  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:41.205  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.205  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.206  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.206  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:37:41.207  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.207  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.207  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.207  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.207  6741  6842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 08:37:41.209  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:41.211  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
08-29 08:37:41.211  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.211  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:41.213  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.213  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.214  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:37:41.214  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:37:41.214  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:37:41.214  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.214  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:37:41.216  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 08:37:41.216  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:37:41.217  6741  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
08-29 08:37:41.217  6741  6842 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:37:41.217  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.218  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.218  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:41.218  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.218  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.218  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.218  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.219  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:41.219  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:41.219  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.219  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.219  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.219  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:41.219  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.219  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.219  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.220  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:37:41.220  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.220  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.220  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.220  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.220  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.220  6741  6842 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported,
08-29 08:37:41.221  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.221  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.221  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:41.221  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:41.221  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.221  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.221  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.221  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.221  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.221  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.221  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.221  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.221  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.221  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.222  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.222  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.222  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.222  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.222  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.222  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.223  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 08:37:41.224  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.224  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.224  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.224  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.224  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.224  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.224  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.224  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 08:37:41.224  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.224  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.224  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.224  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.224  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.224  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.224  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.224  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.225  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.225  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.225  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.225  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.225  6741  6842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 08:37:41.225  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.225  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.225  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.226  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.226  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.226  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.226  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.226  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.226  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.226  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.226  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.226  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.226  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.226  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.226  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.226  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.226  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.226  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.226  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.226  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.227  6741  6842 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 08:37:41.227  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.227  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.227  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.227  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.227  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.227  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.227  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.227  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.227  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.227  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.227  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.227  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.227  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.227  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.228  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.228  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.228  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.228  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.228  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.228  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.229  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:37:41.230  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:37:41.230  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:37:41.230  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:41.230  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:37:41.230  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:37:41.230  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.230  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.230  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.230  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.230  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.230  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.230  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.230  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.231  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.231  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.231  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.231  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.231  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.231  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.231  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.231  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.232  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.232  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.232  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.232  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.233  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:41.233  6741  6842 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:37:41.233  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 08:37:41.236  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:41.236  6741  6842 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:37:41.236  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:37:41.237  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:37:41.237  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 08:37:41.237  6741  6842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:37:41.237  6741  6842 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 08:37:41.237  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:41.237  6741  6842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:37:41.237  6741  6842 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 08:37:41.238  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:41.238  6741  6842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:37:41.238  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 08:37:41.241  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 08:37:41.242  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 08:37:41.242  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 08:37:41.242  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 08:37:41.242  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 08:37:41.242  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 08:37:41.244  6741  6842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:41.244  6741  6842 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 08:37:41.246  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.246  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.246  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.247  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.247  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.247  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.247  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 08:37:41.247  6741  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-29 08:37:41.248  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.248  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.248  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.248  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.248  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.248  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.248  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.248  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.250  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.250  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.250  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.250  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.250  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.250  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.251  6741  6842 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 08:37:41.252  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.252  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.252  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.253  6741  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-29 08:37:41.254  6741  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-29 08:37:41.254  6741  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-29 08:37:41.262  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.262  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.262  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.262  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.262  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.262  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.263  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.263  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.263  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.263  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.263  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.264  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.264  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.265  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.265  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.265  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.265  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.266  6741  6842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 08:37:41.267  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.267  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.267  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.267  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.267  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.267  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.268  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.268  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.268  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.268  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.268  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.268  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.268  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.268  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.268  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.268  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.269  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.269  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.269  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.269  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.269  6741  6842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 08:37:41.270  6741  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 08:37:41.270  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:37:41.270  6741  6842 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 08:37:41.270  6741  6842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:37:41.270  6741  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 08:37:41.270  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:37:41.270  6741  6842 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 08:37:41.270  6741  6842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:37:41.270  6741  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:37:41.270  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:37:41.270  6741  6842 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 08:37:41.270  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.270  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.270  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.270  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.270  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.270  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.270  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.270  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.270  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.271  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.271  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.271  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.271  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.271  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.271  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.271  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.272  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.272  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.272  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.272  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.272  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.273  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.273  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.273  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.273  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.273  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.273  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.273  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.273  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.273  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.273  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.273  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.273  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.273  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.273  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.273  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.273  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.273  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.273  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.273  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.273  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.274  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.274  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.274  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.274  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.274  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.274  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.274  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.274  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.274  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.275  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:37:41.275  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.275  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.275  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.275  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.277  6741  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 08:37:41.277  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.278  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 08:37:41.279  6741  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 08:37:41.279  6741  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 08:37:41.279  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 08:37:41.279  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 08:37:41.279  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:37:41.280  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:41.280  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.280  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 08:37:41.280  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 08:37:41.280  6741  6902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:41.280  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 08:37:41.281  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.281  6741  6842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 08:37:41.281  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.281  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 08:37:41.281  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.281  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:37:41.281  6741  6842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:37:41.281  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:37:41.281  3847  3866 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-29 08:37:41.281  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:37:41.282  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:37:41.282  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:41.282  6741  6842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:37:41.282  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.282  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.282  6741  6902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 08:37:41.282  6741  6902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 08:37:41.283  6741  6902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 08:37:41.284  6741  6842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:41.284  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.284  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:41.284  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.284  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:41.284  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.284  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.284  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.284  6741  6741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 08:37:41.284  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.284  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.284  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.285  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.285  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:41.285  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.285  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.285  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.285  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.285  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.285  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.285  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.285  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.285  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.285  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.286  6741  6842 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 08:37:41.286  6741  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 08:37:41.286  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:37:41.287  6741  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:41.287  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.288  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.288  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.288  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.288  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.288  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.288  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.288  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.288  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.288  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.288  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.288  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.288  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.288  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.290  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.290  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.290  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.290  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.291  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:41.292  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:41.292  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:41.293  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.293  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.293  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.293  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.293  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.293  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.294  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.294  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.294  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.294  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.294  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.294  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.294  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.294  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.295  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.295  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.295  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.295  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.295  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:41.295  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:41.296  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:41.296  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:41.296  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.296  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.296  6741  6842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7309a3 not in the list
08-29 08:37:41.296  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.296  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.296  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:41.296  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.296  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.296  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:41.296  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:41.296  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:41.296  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:41.296  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:41.296  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fcf4a0 not in the list
08-29 08:37:41.297  6741  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 08:37:41.298  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:37:41.298  6741  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 08:37:41.298  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:37:41.298  6741  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 08:37:41.298  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:37:41.299  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 08:37:41.299  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 08:37:41.300  6741  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 08:37:41.300  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:37:41.300  6741  6842 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 08:37:41.300  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:37:41.300  6741  6842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 08:37:41.300  6741  6842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 08:37:41.301  6741  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 08:37:41.301  6741  6842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 08:37:41.302  6741  6842 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 08:37:41.302  6741  6842 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 08:37:41.302  6741  6842 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 08:37:41.302  6741  6842 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 08:37:41.303  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:41.303  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19c87991 added. We now have 2 listener(s)
08-29 08:37:41.303  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:41.304  6741  6842 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 08:37:41.305  1034  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 08:37:41.305  1034  1050 D WifiService: setWifiEnabled: true pid=6741, uid=10118
08-29 08:37:41.305  1034  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 08:37:41.306  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:41.306  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@268c20f6 added. We now have 3 listener(s)
08-29 08:37:41.306  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:41.309  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:41.309  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ff92cf7 added. We now have 4 listener(s)
08-29 08:37:41.309  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:41.311  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:41.311  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36d59764 added. We now have 5 listener(s)
08-29 08:37:41.311  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:41.312  1034  1050 D WifiServiceImplEx: setWifiEnabled: false pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 08:37:41.312  1034  1050 D WifiService: setWifiEnabled: false pid=6741, uid=10118
08-29 08:37:41.312  1034  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:37:41.321  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:41.321  1034  1958 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3ba97599 mBinding = false
08-29 08:37:41.321  1034  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:41.322  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:41.322  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:41.323  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:37:41.323  1034  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:41.323  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 08:37:41.323  1034  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:41.324  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:41.324  1034  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 08:37:41.324  1034  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:37:41.324  1034  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-29 08:37:41.325  1034  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 08:37:41.325  1034  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 08:37:41.327  1034  1116 D BluetoothManagerService: Message: 2
08-29 08:37:41.328  1034  1116 D BluetoothManagerService: Sending off request.
08-29 08:37:41.328  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:41.328  3847  3865 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 08:37:41.328  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:37:41.328  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 08:37:41.329  3847  3931 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 08:37:41.329  3847  3931 D BluetoothAdapterProperties: Setting state to 13
08-29 08:37:41.329  3847  3931 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 08:37:41.329  1034  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 08:37:41.329  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 08:37:41.329  3847  3931 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:37:41.329  2743  2743 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 08:37:41.329  3847  3931 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 08:37:41.329  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.329  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.330  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 08:37:41.330  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:37:41.330  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:37:41.331   311   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:37:41.332  3847  3937 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:37:41.332  3847  3931 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 08:37:41.333  3847  4209 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 08:37:41.333  1034  2865 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.333  3847  4244 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:41.333  3847  3931 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 08:37:41.334  3847  4212 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,08-29 08:37:41.335  3847  4247 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:41.335  3847  4258 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:41.338  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 08:37:41.338  3847  4046 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 08:37:41.338  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:41.338  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 08:37:41.339  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 08:37:41.339  3847  4046 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 08:37:41.351  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:41.351  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 08:37:41.351  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 08:37:41.351  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:41.351  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:41.351  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.351  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:41.366  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:37:41.367  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-29 08:37:41.371  1034  1100 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6908 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 08:37:41.375  1034  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:41.375  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:41.375  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:41.375  1034  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 08:37:41.376  1034  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:41.376  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:41.376  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:41.377  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:41.377  1034  1388 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.377  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.377  1034  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@6c82d8e
,08-29 08:37:41.377  1034  1388 D LGWifiP2pService: P2pDisablingState
08-29 08:37:41.377  1034  1388 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.377  1034  1388 D LGWifiP2pService: p2p socket connection lost
08-29 08:37:41.377  1034  1388 D LGWifiP2pService: P2pDisabledState
08-29 08:37:41.380  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:37:41.381  3847  3847 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:41.381  3847  3847 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:37:41.381  3847  3847 V BluetoothMapService: Handler(): got msg=4
,08-29 08:37:41.381  3847  3847 D BluetoothMapService: MAP Service closeService in
08-29 08:37:41.381  3847  3847 D BluetoothMapMasInstance: MAP Service shutdown
08-29 08:37:41.381  3847  3847 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 08:37:41.381  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:41.381  3847  3847 V BluetoothMapService: MAP Service closeService out
08-29 08:37:41.382  3847  3847 V BtOppService: Receiver DISABLED_ACTION 
08-29 08:37:41.382  3847  3847 I BtOppRfcommListener: stopping Accept Thread
08-29 08:37:41.382  3847  3847 V BtOppRfcommListener: close mBtServerSocket
08-29 08:37:41.382  3847  3847 V BtOppRfcommListener: waiting for thread to terminate
08-29 08:37:41.382  3847  4244 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:37:41.383  3847  3847 V BtOppRfcommListener: done waiting for thread to terminate
,08-29 08:37:41.393  1034  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 08:37:41.394  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.394  1034  1388 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.394  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 08:37:41.394  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.394  2743  2743 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-29 08:37:41.394  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 08:37:41.394  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:37:41.394  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:41.396  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:41.397  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:41.397  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:41.397  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.397  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:41.398  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:41.398  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.399  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:41.399  6741  6895 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-29 08:37:41.400  6741  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
08-29 08:37:41.405  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.414  1034  1100 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6927 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 08:37:41.414   311   892 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:37:41.414  3847  3847 V BtOppService: onDestroy
08-29 08:37:41.414  1034  1439 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 08:37:41.414  1034  1439 D DSQN    : disableDataServiceNotify
08-29 08:37:41.414  1034  1439 D DSQN    : stop dsqn bin
08-29 08:37:41.416  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 08:37:41.418  3847  3847 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 08:37:41.418  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 08:37:41.418  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 08:37:41.418  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.418  1941  1941 D WfdsService: WifiP2pState is changed : false
08-29 08:37:41.418  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.418  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:41.418  1941  2257 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 08:37:41.418  1941  2257 D WfdsService: Set the WFDS Monitor: false
08-29 08:37:41.418  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 08:37:41.418  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.418  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.418  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:41.418  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 08:37:41.418  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-29 08:37:41.418  1034  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.419  1941  2257 D WfdsMonitor: WFDS Monitor is stopped
08-29 08:37:41.419  1941  2257 D WfdsService: STATE : WfdsDisabledState - enter
08-29 08:37:41.419  1941  2780 D CtrlSupplicant: Received on exit socket, terminate
08-29 08:37:41.419  1941  2780 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 08:37:41.419  1941  2780 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 08:37:41.419  1941  2780 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 08:37:41.419  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.419  1941  2258 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 08:37:41.420  1941  2257 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 08:37:41.420  1034  1389 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 08:37:41.420  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:41.420  1034  1389 D WifiNative-p2p0: TERMINATE: returned true
08-29 08:37:41.421  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:37:41.421  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:37:41.421  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:37:41.421  1034  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.421  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 08:37:41.424  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.424  1034  1034 W Settings: Setting wifi_sleep_policy has moved, from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.424  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:41.426  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-29 08:37:41.431  1034  1439 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 08:37:41.431  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:41.431  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:41.431  1034  1439 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:41.432  1034  1439 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 08:37:41.432  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 08:37:41.432  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.433  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.433  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:41.433  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:41.433  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 08:37:41.433  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.433  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:41.434  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 08:37:41.434  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:37:41.434  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 08:37:41.434  1034  1439 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 08:37:41.434  1034  1439 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 08:37:41.434  1034  1439 D ConnectivityService: sendStickyBroadcast: ac,tion=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 08:37:41.434  1034  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:41.435  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 08:37:41.435  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:41.435  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:41.435  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 08:37:41.435  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:41.435  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:41.436  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 08:37:41.437  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.437  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:41.437  1034  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:41.437  1034  1439 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:41.437  1034  1439 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:41.438  1034  1439 D NetworkManagementService: Removing idletimer
08-29 08:37:41.438  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:41.438  1034  1439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.438  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 08:37:41.438  1034  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:41.438  1034  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:37:41.438  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-29 08:37:41.441  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.466  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:41.466  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 08:37:41.468  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.472  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 08:37:41.472  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:41.473  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.474  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.483  6927  6927 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 08:37:41.484  6927  6927 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 08:37:41.484  6927  6927 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:37:41.484  6927  6927 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 08:37:41.485  6927  6927 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 08:37:41.485  6927  6927 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 08:37:41.496  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:37:41.496  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.497  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.501  1034  1699 I art     : Explicit concurrent mark sweep GC freed 26798(1374KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.580ms total 145.525ms
,08-29 08:37:41.502  1034  1439 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 08:37:41.503  6908  6908 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 08:37:41.503  6908  6908 W LG Account v2.2: No ProfileInfo entries
08-29 08:37:41.503  6908  6908 I LG Account v2.2: isEnabled: false
08-29 08:37:41.503  6908  6908 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 08:37:41.503  6908  6908 I Feature : [Lifetracker]Country: EU
08-29 08:37:41.503  6908  6908 I Feature : [Lifetracker]Operator: OPEN
08-29 08:37:41.503  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 08:37:41.503  6908  6908 I Feature : [Lifetracker]Ranking support: false
08-29 08:37:41.503  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 08:37:41.503  6908  6908 I Feature : [Lifetracker]Comfort support: false
08-29 08:37:41.503  6908  6908 I Feature : [Lifetracker]Accessory: true
08-29 08:37:41.503  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 08:37:41.504  6908  6908 I Feature : [Lifetracker]Health device: true
08-29 08:37:41.504  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 08:37:41.504  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 08:37:41.504  6908  6908 I Feature : [Lifetracker]Extra Pedometer: false
08-29 08:37:41.504  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 08:37:41.504  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 08:37:41.504  6908  6908 I Feature : [Lifetracker]Blood glucose device: false
08-29 08:37:41.504  6908  6908 I Feature : [Lifetracker]Device Number: 3
08-29 08:37:41.519  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:37:41.519  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:41.519  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.519  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:37:41.543  2743  2743 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 08:37:41.544  2743  2743 I wpa_supplicant: monitor socket send errors count : 1
08-29 08:37:41.544  2743  2743 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-29 08:37:41.545  1034  2777 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 08:37:41.545  1034  2777 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 08:37:41.546  1034  2865 D DhcpStateMachine: StoppedState
08-29 08:37:41.546  1034  2865 D DhcpStateMachine: StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:41.549  1034  1653 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 08:37:41.550  1034  1653 I ActivityManager: Killing 6296:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 08:37:41.563   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 4.869ms total 14.003ms
,08-29 08:37:41.573   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 8.951ms
08-29 08:37:41.581  2743  2743 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 08:37:41.582  1034  2777 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 08:37:41.582  1034  2777 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 08:37:41.582  1034  2777 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 08:37:41.582   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.700ms
08-29 08:37:41.582  1034  2777 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 08:37:41.582  2743  2743 W wpa_supplicant: USIM:  scard_deinit function
08-29 08:37:41.582  1034  2777 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:37:41.582  1034  2777 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:37:41.583  1034  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118296
08-29 08:37:41.584  1034  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118296
08-29 08:37:41.584  1034  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 08:37:41.584  1034  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 08:37:41.584  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 08:37:41.613  1034  1389 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-29 08:37:41.614  1034  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 08:37:41.615  1034  1994 W libprocessgroup: failed to open /acct/uid_10014/pid_6296/cgroup.procs: No such file or directory
08-29 08:37:41.627  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 08:37:41.629  1034  1389 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:41.630  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 08:37:41.664  2743  2743 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 08:37:41.664  1034  2777 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 08:37:41.664  1034  2777 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 08:37:41.664  1034  2777 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 08:37:41.665  1034  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-29 08:37:41.686  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 08:37:41.688  1034  1376 V AlarmManager: RTC_WAKEUP set : Alarm{1657a46a type 0 when 1472452661443 com.android.vending} when 1472452661443
08-29 08:37:41.689  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 08:37:41.690  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:41.702  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 08:37:41.705  3847  3847 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 08:37:41.705  3847  3847 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:41.705  3847  3847 V BluetoothPbapReceiver: ***********state = 13
08-29 08:37:41.707  3847  3847 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 08:37:41.708  3847  3847 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:41.708  3847  3847 V BluetoothPbapService: state: 13
08-29 08:37:41.708  3847  3847 V BluetoothPbapService: Pbap Service closeService in
08-29 08:37:41.709  3847  3847 V BluetoothPbapService: successfully stopped pbap service
08-29 08:37:41.709  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:37:41.709  3847  3847 V BluetoothPbapService: Pbap Service closeService out
08-29 08:37:41.709  3847  3847 V BluetoothPbapService: Pbap Service onDestroy
08-29 08:37:41.709  3847  3847 V BluetoothPbapService: Pbap Service closeService in
08-29 08:37:41.709  3847  3847 V BluetoothPbapService: Pbap Service closeService out
08-29 08:37:41.709  3847  3847 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 08:37:41.720  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:41.746  1034  1995 V SIM_STK : Menu title from STK is T-Mobile
,08-29 08:37:41.754  6927  6927 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:41.754  6927  6927 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:41.762  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:41.766  1034  1389 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 08:37:41.766  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:37:41.766  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:37:41.766  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:37:41.768  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-29 08:37:41.768  1941  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 08:37:41.768  1941  2257 D WfdsService: Set the WFDS Monitor: false
08-29 08:37:41.768  1941  2257 D WfdsMonitor: WFDS Monitor is stopped
08-29 08:37:41.768  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:41.769  1034  1116 D BluetoothManagerService: Message: 20
08-29 08:37:41.769  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@177b3ed1:true
,08-29 08:37:41.770  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 08:37:41.771  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 08:37:41.771  1034  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 08:37:41.772  1034  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 08:37:41.772  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:41.772  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:41.773  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:41.774  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:41.774  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:41.779  1034  1116 D BluetoothManagerService: Message: 30
08-29 08:37:41.785  1034  1116 D BluetoothManagerService: Message: 30
08-29 08:37:41.785  6741  6741 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:37:41.787  6927  6927 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 08:37:41.789  6927  6927 D BluetoothMap: Create BluetoothMap proxy object
08-29 08:37:41.789  1034  1116 D BluetoothManagerService: Message: 30
08-29 08:37:41.797  1034  1116 D BluetoothManagerService: Message: 30
,08-29 08:37:41.801  6927  6927 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 08:37:41.803  6927  6927 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 08:37:41.829  6927  6927 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-29 08:37:41.832  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 08:37:41.843  6927  6927 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:41.853  6927  6927 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 08:37:41.856  6927  6927 D BluetoothInputDevice: Proxy object connected
08-29 08:37:41.857  6927  6927 D HidProfile: Bluetooth service connected
08-29 08:37:41.858  6927  6927 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:37:41.858  6927  6927 D PanProfile: Bluetooth service connected
08-29 08:37:41.859  6927  6927 D BluetoothMap: Proxy object connected
08-29 08:37:41.859  6927  6927 D MapProfile: Bluetooth service connected
08-29 08:37:41.860  6927  6927 D BluetoothMap: getConnectedDevices()
08-29 08:37:41.860  6927  6927 D BluetoothMap: Bluetooth is Not enabled
08-29 08:37:41.860  6927  6927 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 08:37:41.862  6927  6927 D BluetoothPermissionRequest: onReceive
08-29 08:37:41.864  6927  6927 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 08:37:41.870  1034  1887 I ActivityManager: Killing 6433:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 08:37:41.875  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 08:37:41.904  1034  1995 W libprocessgroup: failed to open /acct/uid_10004/pid_6433/cgroup.procs: No such file or directory
,08-29 08:37:41.905  3847  3847 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 08:37:41.905  3847  3847 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 08:37:41.906  3847  3847 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 08:37:41.909  6232  6232 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-29 08:37:41.915  3847  3847 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:41.915  3847  3847 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 08:37:41.990  1034  1887 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6978 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-29 08:37:41.991  1034  1887 I ActivityManager: Killing 6589:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-29 08:37:42.086  3847  3847 V BluetoothFtpService: Ftp Service onStartCommand
,08-29 08:37:42.086  3847  3847 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:42.087  1034  1049 W libprocessgroup: failed to open /acct/uid_10008/pid_6589/cgroup.procs: No such file or directory
08-29 08:37:42.088  3847  3847 V BluetoothFtpService: Ftp Service closeService
08-29 08:37:42.089  3847  3847 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 08:37:42.101  3847  3847 V BluetoothFtpService: successfully stopped ftp service
08-29 08:37:42.102  3847  3847 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:37:42.103  3847  3847 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:37:42.103  3847  3847 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:37:42.103  3847  3847 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:42.103  3847  3847 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 08:37:42.103  3847  3847 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-29 08:37:42.106  3847  3847 V BluetoothFtpService: Ftp Service onDestroy
08-29 08:37:42.106  3847  3847 V BluetoothFtpService: Ftp Service closeService
08-29 08:37:42.107  3847  3847 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:42.107  3847  3847 V BluetoothSapService: state: 13
08-29 08:37:42.107  3847  3847 V BluetoothSapService: Stopping SAP server process
08-29 08:37:42.111  3847  3847 V BluetoothSapService: Sap Service closeSapService in
08-29 08:37:42.113  3847  3847 V BluetoothSapService: Close listen Socket : 
08-29 08:37:42.114  3847  3847 V BluetoothSapService: Close rfcomm Socket : 
08-29 08:37:42.114  3847  3847 V BluetoothSapService: Close sapd  Socket : 
08-29 08:37:42.128  6978  6978 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 08:37:42.171  1034  1994 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6998 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 08:37:42.173  3847  3847 V BluetoothSapService: Sap Service closeSapService out
,08-29 08:37:42.173  3847  3847 V BluetoothSapService: Sap Service onDestroy
08-29 08:37:42.173  3847  3847 V BluetoothSapService: Sap Service closeSapService in
08-29 08:37:42.173  3847  3847 V BluetoothSapService: Close listen Socket : 
08-29 08:37:42.173  3847  3847 V BluetoothSapService: Close rfcomm Socket : 
08-29 08:37:42.173  3847  3847 V BluetoothSapService: Close sapd  Socket : 
08-29 08:37:42.174  3847  3847 V BluetoothSapService: Sap Service closeSapService out
08-29 08:37:42.178  6978  6978 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 08:37:42.220  6978  6978 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 08:37:42.220  6978  6978 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 08:37:42.221  6978  6978 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 08:37:42.221  6978  6978 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 08:37:42.221  6978  6978 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 08:37:42.224  6978  6978 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 08:37:42.231  6978  6978 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-29 08:37:42.237  6998  6998 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:37:42.239  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:42.242  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:42.254  1034  1958 I ActivityManager: Killing 6156:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 08:37:42.284  1034  1575 W libprocessgroup: failed to open /acct/uid_10011/pid_6156/cgroup.procs: No such file or directory
,08-29 08:37:42.284  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 08:37:42.288  6978  6978 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 08:37:42.291  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:42.291  6978  6978 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 08:37:42.296  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 08:37:42.296  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:42.296  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:37:42.303  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:42.310  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:42.318  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:37:42.319  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:42.320  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 08:37:42.324  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:42.329  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 08:37:42.329  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:42.329  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:42.335  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:42.341  3847  4046 W bt-btif : ag scb idx 1 not allocated
08-29 08:37:42.341  3847  3937 D bt_hci_bdroid: cleanup
08-29 08:37:42.341  3847  4052 I bt_lpm  : LPM is already off!!!
08-29 08:37:42.341  3847  4046 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:42.341  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:42.342  3847  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:42.342  3847  4046 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 08:37:42.342  3847  4198 I bt_userial_mct: exiting userial_read_thread
08-29 08:37:42.342  3847  4198 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 08:37:42.343  3847  3937 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 08:37:42.343  3847  4052 I bt_vendor: hw_epilog_process
08-29 08:37:42.344  3847  3937 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 08:37:42.344  3847  3937 D bt_userial_mct: userial_close
08-29 08:37:42.344  3847  3937 E bt_userial_mct: pthread_join() FAILED result:3
08-29 08:37:42.344  3847  3937 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 08:37:42.346  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:42.357  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:42.357  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:42.360  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 08:37:42.373  3847  3937 D bt_hci_bdroid: set_power 0
,08-29 08:37:42.373  3847  3937 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 08:37:42.373  3847  3937 I bt_vendor: bluetooth satus is on
08-29 08:37:42.373  3847  3937 I bt_vendor: bt-vendor : resetting BT status
08-29 08:37:42.374  3847  3937 I bt_vendor: Starting hciattach daemon
08-29 08:37:42.374  3847  3937 I bt_vendor: try to set false
08-29 08:37:42.376  3847  3937 I bt_vendor: Starting hciattach daemon
08-29 08:37:42.376  3847  3937 I bt_vendor: try to set false
08-29 08:37:42.377  3847  3937 I bt_vendor: cleanup
08-29 08:37:42.379  3847  4046 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 08:37:42.379  3847  3937 I GKI_LINUX: GKI_exit_task 0 done
08-29 08:37:42.379  3847  3937 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 08:37:42.383  3847  3931 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 08:37:42.435  1034  1050 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7019 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 08:37:42.442  3847  3847 D HeadsetService: Received stop request...Stopping profile...
08-29 08:37:42.446  3847  3847 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 08:37:42.446  3847  3847 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:37:42.446  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.446  3847  3973 D HeadsetStateMachine: Exit Disconnected: -1
08-29 08:37:42.447  3847  3931 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 08:37:42.448  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:42.448  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:42.449  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:42.449  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:42.449  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 08:37:42.449  3847  3847 D A2dpService: Received stop request...Stopping profile...
08-29 08:37:42.450  3847  4014 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:37:42.450  3847  3847 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 08:37:42.452  3847  3847 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 08:37:42.452  3847  3847 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:37:42.452  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.453  1034  1034 D BluetoothA2dp: Proxy object disconnected
,08-29 08:37:42.454  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 08:37:42.454  3847  3847 D HidService: Received stop request...Stopping profile...
08-29 08:37:42.454  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.457  3847  3847 D HealthService: Received stop request...Stopping profile...
08-29 08:37:42.457  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.457  6927  6927 D BluetoothInputDevice: Proxy object disconnected
08-29 08:37:42.457  6927  6927 D HidProfile: Bluetooth service disconnected
08-29 08:37:42.459  3847  3847 D PanService: Received stop request...Stopping profile...
08-29 08:37:42.459  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.460  3847  3847 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:37:42.461  3847  3847 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 08:37:42.461  3847  3847 D BtGatt.GattService: stop()
08-29 08:37:42.461  3847  3847 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 08:37:42.463  6927  6927 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:37:42.463  6927  6927 D PanProfile: Bluetooth service disconnected
08-29 08:37:42.463  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.465  3847  3847 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:37:42.465  3847  3847 D BluetoothMapService: stop()
08-29 08:37:42.466  3847  3847 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 08:37:42.466  3847  3847 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 08:37:42.466  3847  3847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef99ee9
08-29 08:37:42.468  3847  3847 D HeadsetStateMachine: Unbinding service...
08-29 08:37:42.469  6927  6927 D BluetoothMap: Proxy object disconnected
08-29 08:37:42.469  6927  6927 D MapProfile: Bluetooth service disconnected
08-29 08:37:42.469  3847  3847 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 08:37:42.469  3847  3847 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 08:37:42.469  3847  3847 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 08:37:42.469  3847  3847 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 08:37:42.469  3847  3847 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 08:37:42.469  3847  3847 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:37:42.470  3847  3847 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 08:37:42.470  3847  3847 I BluetoothA2dpServiceJni: cleanupNative
08-29 08:37:42.470  3847  4015 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 08:37:42.470  3847  3847 I GKI_LINUX: GKI_exit_task 2 done
08-29 08:37:42.470  3847  3847 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 08:37:42.471  3847  3847 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:37:42.471  3847  3847 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:37:42.471  3847  3847 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:37:42.472  3847  3847 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:37:42.472  3847  3847 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:37:42.472  3847  3847 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 08:37:42.472  3847  3847 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 08:37:42.473  3847  3847 V BluetoothMapService: Handler(): got msg=4
08-29 08:37:42.473  3847  3847 D BluetoothMapService: MAP Service closeService in
08-29 08:37:42.473  3847  3847 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 08:37:42.473  3847  3847 V BluetoothMapService: MAP Service closeService out
,08-29 08:37:42.473  3847  3847 D BluetoothMapService: cleanup()
08-29 08:37:42.473  3847  3847 D BluetoothMapService: MAP Service closeService in
08-29 08:37:42.473  3847  3847 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 08:37:42.473  3847  3847 V BluetoothMapService: MAP Service closeService out
08-29 08:37:42.473  3847  3931 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 08:37:42.474  3847  3931 D BluetoothAdapterProperties: Setting state to 10
08-29 08:37:42.474  3847  3931 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 08:37:42.475  3847  3931 I BluetoothAdapterState: Entering OffState
08-29 08:37:42.475  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:42.475  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 08:37:42.475  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 08:37:42.475  1852  3942 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:42.476  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:42.476  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:42.477  6927  6945 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:37:42.477  1852  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:42.478  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:37:42.478  6927  6944 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:37:42.479  6927  6945 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:37:42.480  6927  6944 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:37:42.481  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 08:37:42.481  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 08:37:42.483  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 08:37:42.484  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 08:37:42.484  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3ba97599 mBinding = false
08-29 08:37:42.484  1034  1116 D BluetoothManagerService: Sending unbind request.
08-29 08:37:42.486  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-29 08:37:42.490  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:42.491  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:42.492  6927  6927 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 08:37:42.493  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:42.493  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:37:42.495  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 08:37:42.495  3847  3937 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 08:37:42.496  3847  3847 I GKI_LINUX: GKI_exit_task 1 done
08-29 08:37:42.496  3847  3847 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 08:37:42.496  6927  6927 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 08:37:42.497  3847  3847 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 08:37:42.497  3847  3847 I art     : --- WEIRD: removing null entry 246
08-29 08:37:42.497  3847  3847 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 08:37:42.497  3847  3847 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 08:37:42.499  1602  1602 D BluetoothAdapter: 260883617: getState() :  mService = null. Returning STATE_OFF
08-29 08:37:42.499  1602  1602 D BluetoothAdapter: 260883617: getState() :  mService = null. Returning STATE_OFF
08-29 08:37:42.499  1941  2099 D LGBluetoothAPIService: Message: 2
08-29 08:37:42.500  1941  2099 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@a6a5bc0 mBinding = false
08-29 08:37:42.500  1941  2099 D LGBluetoothAPIService: Sending unbind request.
,08-29 08:37:42.503  3847  3847 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 08:37:42.506  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 08:37:42.512  3847  3847 I art     : System.exit called, status: 0
08-29 08:37:42.512  3847  3847 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 08:37:42.514  6927  6927 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:42.539   315  2157 V AudioFlinger: 3847 died, releasing its sessions
08-29 08:37:42.539   315  2157 V AudioFlinger:  pid 1852 @ 0
08-29 08:37:42.539   315  2157 V AudioFlinger:  pid 3444 @ 1
08-29 08:37:42.539   315  2157 V AudioFlinger:  pid 3444 @ 2
08-29 08:37:42.540  6927  6927 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-29 08:37:42.563  1034  1958 I ActivityManager: Process com.android.bluetooth (pid 3847) has died
,08-29 08:37:42.563  1034  1958 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-29 08:37:42.570  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:37:42.588  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:37:42.599  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 08:37:42.611  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:42.612  6927  6927 D BluetoothPermissionRequest: onReceive
,08-29 08:37:42.615  6927  6927 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 08:37:42.615  7019  7045 W FormManager: Network not available. Please check & try again.
08-29 08:37:42.615  6927  6927 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 08:37:42.617  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 08:37:42.689  1034  1887 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7049 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 08:37:42.696  7019  7046 V FormManager: Network unavailable.
08-29 08:37:42.703  7019  7046 V FormManager: Network unavailable.
,08-29 08:37:42.722  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 08:37:42.722  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 08:37:42.723  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-29 08:37:42.724  6927  6927 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 08:37:42.725  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 08:37:42.734  6927  6927 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 08:37:42.734  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 08:37:42.734  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 08:37:42.734  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 08:37:42.734  6927  6927 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 08:37:42.735  6927  6927 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 08:37:42.736  1034  1995 I ActivityManager: Killing 6176:com.android.contacts/u0a19 (adj 15): empty #17
,08-29 08:37:42.764  4505  7067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 08:37:42.831  1034  1699 W libprocessgroup: failed to open /acct/uid_10019/pid_6176/cgroup.procs: No such file or directory
,08-29 08:37:42.847  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:37:42.848  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:42.848  7049  7049 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 08:37:42.849  7049  7049 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:37:42.849  7049  7049 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 08:37:42.850  7049  7049 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 08:37:42.856  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:42.860  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:42.865  4325  7075 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 08:37:42.868  7049  7049 D BluetoothAdapterApp: Loading JNI Library
08-29 08:37:42.874  6949  6949 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 08:37:42.874  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:42.874  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:42.876  4325  7076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:37:42.876  4325  7076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:42.879  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 08:37:42.883  7019  7078 W FormManager: Network not available. Please check & try again.
08-29 08:37:42.884  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:42.889  7019  7079 V FormManager: Network unavailable.
08-29 08:37:42.891  7019  7079 V FormManager: Network unavailable.
,08-29 08:37:42.899  6978  6978 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 08:37:42.899  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 08:37:42.900  6978  6978 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 08:37:42.901  7049  7049 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3f8eb96 Instance Count = 1
,08-29 08:37:42.905  7049  7049 D BluetoothAdapterApp: onCreate
08-29 08:37:42.924  6978  6978 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:42.924  6978  6978 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 08:37:42.924  7049  7049 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 08:37:42.924  7049  7049 D ProfileConfigQcom: Adding HeadsetService
08-29 08:37:42.925  7049  7049 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 08:37:42.925  7049  7049 D ProfileConfigQcom: Adding A2dpService
08-29 08:37:42.926  7049  7049 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 08:37:42.926  7049  7049 D ProfileConfigQcom: Adding HidService
,08-29 08:37:42.927  7049  7049 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 08:37:42.928  6978  6978 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 08:37:42.929  7049  7049 D ProfileConfigQcom: Adding HealthService
08-29 08:37:42.929  6978  6978 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 08:37:42.930  6978  6978 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 08:37:42.930  6978  6978 V SoundPool: doLoad: loading sample sampleID=1
08-29 08:37:42.930  6978  6978 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 08:37:42.931  7049  7049 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 08:37:42.932  6851  6851 D UEI.SmartControl: QS Service created
08-29 08:37:42.932  6978  6978 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 08:37:42.934  6978  6978 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 08:37:42.934  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 08:37:42.935  7049  7049 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 08:37:42.935  6978  7083 V SoundPool: Start decode
08-29 08:37:42.935  6978  7083 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 08:37:42.935  7049  7049 D ProfileConfigQcom: Adding PanService
08-29 08:37:42.935   315  1399 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 08:37:42.935   315  1399 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType,
08-29 08:37:42.936   315  1399 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 08:37:42.936   315  1399 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 08:37:42.936   315  1399 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 08:37:42.936   315  1399 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 08:37:42.936   315  1399 V MediaPlayerService: player type = 3
08-29 08:37:42.936   315  1399 V AwesomePlayer: AwesomePlayer create()
08-29 08:37:42.936   315  1399 V AwesomePlayer: reset_l() 
08-29 08:37:42.936   315  1399 V AwesomePlayer: cancelPlayerEvents
08-29 08:37:42.936   315  1399 V AwesomePlayer: setAudioSink() 
08-29 08:37:42.936  7049  7049 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 08:37:42.936   315  1399 V AwesomePlayer: reset_l() 
08-29 08:37:42.936   315  1399 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-29 08:37:42.936   315  1399 V AudioCache: ignored
08-29 08:37:42.936   315  1399 V AwesomePlayer: cancelPlayerEvents
08-29 08:37:42.936   315  1399 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 08:37:42.936   315  1399 V AwesomePlayer: setDataSource_l dataSource
08-29 08:37:42.936   315  1399 V LGParserOSAL: SniffLGParser start
08-29 08:37:42.936   315  1399 V LGParserOSAL: MainType:5, SubType=0
08-29 08:37:42.936   315  1399 V LGParserOSAL: #### check Mime : application/ogg
08-29 08:37:42.936   315  1399 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 08:37:42.936   315  1399 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 08:37:42.936  7049  7049 D ProfileConfigQcom: Adding GattService
08-29 08:37:42.937  7049  7049 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 08:37:42.937  7049  7049 D ProfileConfigQcom: Adding BluetoothMapService
08-29 08:37:42.938  7049  7049 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 08:37:42.942  7049  7049 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 08:37:42.943  6851  6851 I UEI.SmartControl: Service initServices...
08-29 08:37:42.944  6851  6851 D UEI.SmartControl: QS start get config
08-29 08:37:42.946  6927  6927 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 08:37:42.948  7049  7049 V LGMDMManagerInternal: Create singleton instance
08-29 08:37:42.966   315  1399 V LGParserOSAL: supported mime: application/ogg
08-29 08:37:42.966   315  1399 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 08:37:42.966   315  1399 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 08:37:42.966   315  1399 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 08:37:42.966   315  1399 V AwesomePlayer: AudioTrack Setting
08-29 08:37:42.966   315  1399 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 08:37:42.966   315  1399 V AwesomePlayer: setAudioSource() 
08-29 08:37:42.966   315  1399 V MediaPlayerService: prepare
08-29 08:37:42.966   315  1399 V AwesomePlayer: prepareAsync_l() 
08-29 08:37:42.966   315  1399 V MediaPlayerService: wait for prepare
08-29 08:37:42.966   315  7085 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 08:37:42.966   315  7085 V AwesomePlayer: initAudioDecoder() 
08-29 08:37:42.966   315  7085 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 08:37:42.966   315  7085 V AudioSystem: isOffloadSupported()
08-29 08:37:42.966   315  7085 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 08:37:42.966   315  7085 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 08:37:42.966   315  7085 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 08:37:42.966   315  7085 V AwesomePlayer: getUseOffload() = 0 
08-29 08:37:42.966   315  7085 V OMXCodec: OMXCodec::Create
08-29 08:37:42.966   315  7085 V OMXCodec: findMatchingCodecs()
08-29 08:37:42.966   315  7085 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 08:37:42.966   315  7085 V OMXCodec: matchingCodecs.size()=1
08-29 08:37:42.966   315  7085 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 08:37:42.967   315  7085 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 08:37:42.967   315  7085 V LGCodecAdapter: LG Codec Adapter start
08-29 08:37:42.967   315  7085 V OMXCodec: OMXCodec Createtor
08-29 08:37:42.967   315  7085 V OMXCodec: setComponentRole
08-29 08:37:42.967   315  7085 V OMXCodec: configureCodec protected=0
08-29 08:37:42.967   315  7085 V LGCodecAdapter: called getLGCodecSpecificData
08-29 08:37:42.967   315  7085 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 08:37:42.967   315  7085 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 08:37:42.967   315  7085 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 08:37:42.967   315  7085 V LGCodecOSAL: Not support LGCodec
08-29 08:37:42.967   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 08:37:42.967   315  7085 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 08:37:42.968   315  7085 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 08:37:42.968   315  7085 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 08:37:42.968   315  7085 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 08:37:42.968   315  7085 V AudioSystem: isOffloadSupported()
08-29 08:37:42.968   315  7085 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 08:37:42.968   315  7085 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 08:37:42.968   315  7085 V OMXCodec: init()
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 08:37:42.968   315  7085 V OMXCodec: allocateBuffers
08-29 08:37:42.968   315  7085 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-29 08:37:42.968   315  7085 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-29 08:37:42.968   315  7085 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fec0 on output port
08-29 08:37:42.968   315  7085 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 08:37:42.968   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 08:37:42.968   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 08:37:42.968   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 08:37:42.968   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 08:37:42.968   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 08:37:42.968   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 08:37:42.968   315  7085 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 08:37:42.968   315  7085 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 08:37:42.968   315  7085 V AudioCache: notify(0xb54749c0, 5, 0, 0)
08-29 08:37:42.968   315  7085 V AudioCache: ignored
08-29 08:37:42.968   315  7085 V AudioCache: notify(0xb54749c0, 1, 0, 0)
08-29 08:37:42.968   315  7085 V AudioCache: prepared
08-29 08:37:42.968   315  1399 V AudioCache: wait - success
08-29 08:37:42.968   315  1399 V MediaPlayerService: start
08-29 08:37:42.968   315  1399 V AwesomePlayer: play_l() 
08-29 08:37:42.968   315  1399 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 08:37:42.968   315  1399 V AwesomePlayer: createAudioPlayer_l
08-29 08:37:42.969   315  1399 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 08:37:42.969   315  1399 V AwesomePlayer: startAudioPlayer_l() 
08-29 08:37:42.969   315  1399 D AudioPlayer: start of Playback, useOffload 0
08-29 08:37:42.969   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 08:37:42.969   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Port is dis,abled, freeing buffer 2957048416
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049536
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 08:37:42.970   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 08:37:42.971   315  7087 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on output port
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 08:37:42.971   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 08:37:42.972   315  1399 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 08:37:42.972   315  1399 V AudioCache: notify(0xb54749c0, 6, 0, 0)
08-29 08:37:42.972   315  1399 V AudioCache: ignored
08-29 08:37:42.972   315  1399 V MediaPlayerService: wait for playback complete
08-29 08:37:42.973   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.973   315  7088 V AudioCache: memcpy(0xaf006000, 0xb57bc000, 4096)
08-29 08:37:42.973   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.973   315  7088 V AudioCache: memcpy(0xaf007000, 0xb57bc000, 4096)
08-29 08:37:42.974   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.974   315  7088 V AudioCache: memcpy(0xaf008000, 0xb57bc000, 4096)
08-29 08:37:42.974   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.974   315  7088 V AudioCache: memcpy(0xaf009000, 0xb57bc000, 4096)
08-29 08:37:42.974   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.974   315  7088 V AudioCache: memcpy(0xaf00a000, 0xb57bc000, 4096)
08-29 08:37:42.975   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.975   315  7088 V AudioCache: memcpy(0xaf00b000, 0xb57bc000, 4096)
08-29 08:37:42.975   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.975   315  7088 V AudioCache: memcpy(0xaf00c000, 0xb57bc000, 4096)
08-29 08:37:42.975   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.975   315  7088 V AudioCache: memcpy(0xaf00d000, 0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: memcpy(0xaf00e000, 0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: memcpy(0xaf00f000, 0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: memcpy(0xaf010000, 0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.976   315  7088 V AudioCache: memcpy(0xaf011000, 0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: memcpy(0xaf012000, 0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: memcpy(0xaf013000, 0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: memcpy(0xaf014000, 0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: memcpy(0xaf015000, 0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.977   315  7088 V AudioCache: memcpy(0xaf016000, 0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: memcpy(0xaf017000, 0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: memcpy(0xaf018000, 0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: memcpy(0xaf019000, 0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: memcpy(0xaf01a000, 0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.978   315  7088 V AudioCache: memcpy(0xaf01b000, 0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: memcpy(0xaf01c000, 0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: memcpy(0xaf01d000, 0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: memcpy(0xaf01e000, 0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: memcpy(0xaf01f000, 0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.979   315  7088 V AudioCache: memcpy(0xaf020000, 0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: memcpy(0xaf021000, 0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: memcpy(0xaf022000, 0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: memcpy(0xaf023000, 0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.980   315  7088 V AudioCache: memcpy(0xaf024000, 0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: memcpy(0xaf025000, 0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: memcpy(0xaf026000, 0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: memcpy(0xaf027000, 0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: memcpy(0xaf028000, 0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.981   315  7088 V AudioCache: memcpy(0xaf029000, 0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: memcpy(0xaf02a000, 0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: memcpy(0xaf02b000, 0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: memcpy(0xaf02c000, 0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.982   315  7088 V AudioCache: memcpy(0xaf02d000, 0xb57bc000, 4096)
08-29 08:37:42.993   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.993   315  7088 V AudioCache: memcpy(0xaf02e000, 0xb57bc000, 4096)
08-29 08:37:42.993   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.993   315  7088 V AudioCache: memcpy(0xaf02f000, 0xb57bc000, 4096)
08-29 08:37:42.993   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.993   315  7088 V AudioCache: memcpy(0xaf030000, 0xb57bc000, 4096)
08-29 08:37:42.994   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.994   315  7088 V AudioCache: memcpy(0xaf031000, 0xb57bc000, 4096)
08-29 08:37:42.994   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.994   315  7088 V AudioCache: memcpy(0xaf032000, 0xb57bc000, 4096)
08-29 08:37:42.994  6978  6978 V LGMDMManager: Create singleton instance
08-29 08:37:42.994   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.994   315  7088 V AudioCache: memcpy(0xaf033000, 0xb57bc000, 4096)
08-29 08:37:42.995   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.995   315  7088 V AudioCache: memcpy(0xaf034000, 0xb57bc000, 4096)
08-29 08:37:42.995   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.995   315  7088 V AudioCache: memcpy(0xaf035000, 0xb57bc000, 4096)
08-29 08:37:42.995   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.995   315  7088 V AudioCache: memcpy(0xaf036000, 0xb57bc000, 4096)
08-29 08:37:42.996   315  7088 V AudioCache: write(0xb57bc000, 4096)
08-29 08:37:42.996   315  7088 V AudioCache: memcpy(0xaf037000, 0xb57bc000, 4096)
08-29 08:37:42.996   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 08:37:42.996   315  7088 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 08:37:42.996   315  7088 V AwesomePlayer: postAudioEOS() 
08-29 08:37:42.996   315  7088 V AudioCache: write(0xb57bc000, 280)
08-29 08:37:42.996   315  7088 V AudioCache: memcpy(0xaf038000, 0xb57bc000, 280)
08-29 08:37:43.002   315  7085 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 08:37:43.002   315  7085 V AwesomePlayer: onStreamDone
08-29 08:37:43.002   315  7085 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 08:37:43.002   315  7085 V AudioCache: notify(0xb54749c0, 2, 0, 0)
08-29 08:37:43.002   315  7085 V AudioCache: playback complete
08-29 08:37:43.002   315  7085 V AwesomePlayer: pause_l() 
08-29 08:37:43.002   315  7085 V AudioCache: notify(0xb54749c0, 7, 0, 0)
08-29 08:37:43.002   315  7085 V AudioCache: ignored
08-29 08:37:43.002   315  7085 V AwesomePlayer: cancelPlayerEvents
08-29 08:37:43.002   315  1399 V AudioCache: wait - success
08-29 08:37:43.002   315  1399 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 08:37:43.003   315  7085 D AudioPlayer: Pause Playback at 1068125
08-29 08:37:43.003   315  1399 V AwesomePlayer: reset_l() 
08-29 08:37:43.003   315  1399 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-29 08:37:43.003   315  1399 V AudioCache: ignored
08-29 08:37:43.003   315  1399 V AwesomePlayer: cancelPlayerEvents
08-29 08:37:43.003   315  1399 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 08:37:43.003   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 08:37:43.003   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 08:37:43.003   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 08:37:43.003   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 08:37:43.005   315  7087 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 08:37:43.006   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 08:37:43.006   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 08:37:43.006   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 08:37:43.006   315  1399 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 08:37:43.007   315  1399 D AudioPlayer: AudioPlayer releasing audio source
08-29 08:37:43.007   315  1399 D AudioPlayer: AudioPlayer done releasing audio source
08-29 08:37:43.007   315  1399 V AwesomePlayer: reset_l() 
08-29 08:37:43.007   315  1399 V AwesomePlayer: cancelPlayerEvents
08-29 08:37:43.007   315  1399 V AwesomePlayer: ~AwesomePlayer call
08-29 08:37:43.007   315  1399 V AwesomePlayer: reset_l() 
08-29 08:37:43.007   315  1399 V AwesomePlayer: cancelPlayerEvents
08-29 08:37:43.007  6978  7083 V SoundPool: close(31)
08-29 08:37:43.007  6978  7083 V SoundPool: pointer = 0x9ff2e000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 08:37:43.036  7049  7049 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:43.036  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-29 08:37:43.037  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 08:37:43.039  7049  7049 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:37:43.039  7049  7049 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:37:43.040  7049  7049 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:37:43.040  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3462
08-29 08:37:43.041  7049  7049 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:43.041  7049  7049 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 08:37:43.046  6998  6998 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-29 08:37:43.213  6851  6851 I UEI.SmartControl: Supports setup maps: true
08-29 08:37:43.216  6851  6851 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 08:37:43.216  6851  6851 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 08:37:43.216  6851  6851 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 08:37:43.216  6851  6851 I UEI.SmartControl: ### init IR Blaster...
,08-29 08:37:43.219  6851  6851 D serial_port: Configuring serial port
08-29 08:37:43.219  6851  6851 E UEI.SmartControl: UEIBLaster setting for 616
08-29 08:37:43.219  6851  6851 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 08:37:43.219  6851  6851 I UEI.SmartControl: configuring settings for MAXQ616
08-29 08:37:43.219  6851  6851 I UEI.SmartControl: Get version...
08-29 08:37:43.238  6851  7090 D UEI.SmartControl: serial port data available: 21
,08-29 08:37:43.273  6851  6851 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 08:37:43.273  6851  6851 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 08:37:43.273  6851  6851 I UEI.SmartControl: QS saving settings...
08-29 08:37:43.276  6851  6851 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 08:37:43.293  6851  7090 D UEI.SmartControl: serial port data available: 4
,08-29 08:37:43.336  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 08:37:43.339  6851  6851 E UEI.SmartControl: Services init done
08-29 08:37:43.340  6851  6851 D UEI.SmartControl: QS Service init finished
08-29 08:37:43.342  6851  6851 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 08:37:43.342  6851  6851 D UEI.SmartControl: QS Service version code: 201091
,08-29 08:37:43.346  6851  6851 D UEI.SmartControl: Service requested: Control
,08-29 08:37:43.347  6851  7099 I UEI.SmartControl: Device manager: loading config....
08-29 08:37:43.348  6851  7099 D UEI.SmartControl: ----------- loading internal config...
08-29 08:37:43.351  6978  6978 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 08:37:43.355  6851  6867 I UEI.SmartControl: ------ IControl API: 11
08-29 08:37:43.356  6851  6867 D UEI.SmartControl: File observer start...
,08-29 08:37:43.362  6851  6867 E UEI.SmartControl: IR Port is disabled: false
08-29 08:37:43.364  6851  6867 D UEI.SmartControl: Starting file observer...
08-29 08:37:43.365  6851  6867 I UEI.SmartControl: Registering callback...
08-29 08:37:43.365  6851  6866 I UEI.SmartControl: ------ IControl API: 19
08-29 08:37:43.366  6851  6851 D UEI.SmartControl: Internal service binding...
08-29 08:37:43.366  6851  6866 I UEI.SmartControl: Registering Services Ready callback...
08-29 08:37:43.368  6851  7099 E UEI.SmartControl: Loading SETTINGS...
08-29 08:37:43.372  6851  7099 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 08:37:43.386  6851  7095 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 08:37:43.386  6851  7095 D UEI.SmartControl: -----service ready thread exits
08-29 08:37:43.387  6978  6994 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 08:37:43.387  6978  7081 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 08:37:43.387  6978  7081 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-29 08:37:43.388  6978  6978 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 08:37:43.389  6978  6978 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 08:37:43.389  6851  6867 I UEI.SmartControl: ------ IControl API: 8
08-29 08:37:43.390  6978  6978 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 08:37:43.391  6978  6978 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 08:37:43.391  6978  6978 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 08:37:43.391  6978  6978 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 08:37:43.392  6978  6978 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 08:37:43.393  6978  6978 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 08:37:43.396  6978  6978 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 08:37:43.398  6978  6978 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 08:37:43.399  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-29 08:37:43.401  6978  6978 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 08:37:43.401  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 08:37:43.402  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 08:37:43.403  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 08:37:43.404  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 08:37:43.405  6978  6978 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472452663404]
08-29 08:37:43.409  6978  6978 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 08:37:43.411  1034  1976 I ActivityManager: Killing 6204:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-29 08:37:43.431  6978  7101 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0,
,08-29 08:37:43.503  1034  1976 I ActivityManager: Killing 6638:com.lge.email/u0a23 (adj 15): empty #18
,08-29 08:37:43.561  1034  2031 W libprocessgroup: failed to open /acct/uid_10027/pid_6204/cgroup.procs: No such file or directory
,08-29 08:37:43.567  1034  2050 W libprocessgroup: failed to open /acct/uid_10023/pid_6638/cgroup.procs: No such file or directory
08-29 08:37:43.575  6978  6978 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-29 08:37:43.577  6978  6978 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 08:37:43.578  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 08:37:43.579  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 08:37:43.579  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 08:37:43.580  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 08:37:43.581  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 08:37:43.605  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 08:37:44.403  1034  1923 D WifiServiceImplEx: setWifiEnabled: true pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 08:37:44.405  1034  1923 D WifiService: setWifiEnabled: true pid=6741, uid=10118
,08-29 08:37:44.405  1034  1923 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:37:44.427  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:44.428  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:37:44.428  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-29 08:37:44.431  1034  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 08:37:44.431  1034  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 08:37:44.434  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 08:37:44.434  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 08:37:44.434  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 08:37:44.434  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 08:37:44.434  1034  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 08:37:44.434  1034  1389 E WifiHW  : unknown target_country: EU , set to default
08-29 08:37:44.434  1034  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 08:37:44.434  1034  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 08:37:44.435  1034  1389 I WifiUtil: gEnableBmps=1
08-29 08:37:44.438  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:44.443  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,08-29 08:37:44.456  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:44.461  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.463  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.467  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:44.467  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,08-29 08:37:44.478  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.479  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:44.482  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 08:37:44.486  6543  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 08:37:44.501  5822  5822 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 08:37:44.508  5822  5822 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 08:37:44.532  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:44.568  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:44.629  1034  1958 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7127 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 08:37:44.633  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 08:37:44.634  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 08:37:44.741  7127  7127 I AppUp4:AppBoxCP: onCreate
,08-29 08:37:44.742  7127  7127 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-29 08:37:44.753  7127  7127 I AppUp4:DB:  setFingerPrint start
,08-29 08:37:44.753  7127  7127 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 08:37:44.762  7127  7127 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 08:37:44.762  7127  7127 I AppUp4:DB:  SDK version = 21
08-29 08:37:44.762  7127  7127 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 08:37:44.765  7127  7127 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-29 08:37:44.766  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 08:37:44.766  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:44.769  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 08:37:44.769  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 08:37:44.778  7127  7127 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 08:37:44.835  7127  7127 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 08:37:44.835  7127  7127 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:44.844  7127  7127 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e343b70
08-29 08:37:44.844  7127  7127 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 08:37:44.844  7127  7127 D AppUp4:CustFacade: isPhone : true
08-29 08:37:44.845  7127  7127 D AppUp4:CustModeStarterReceiver: begin check event
08-29 08:37:44.846  7127  7127 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 08:37:44.846  7127  7127 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 08:37:44.847  7127  7147 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-29 08:37:44.847  7127  7147 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 08:37:44.848  7127  7147 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 08:37:44.851  1034  2050 I ActivityManager: Killing 6272:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-29 08:37:44.969  1034  2033 W libprocessgroup: failed to open /acct/uid_10080/pid_6272/cgroup.procs: No such file or directory
,08-29 08:37:44.975  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:44.975  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 08:37:44.977  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 08:37:44.980  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:44.994  4325  7158 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 08:37:44.999  4325  7160 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:44.999  4325  7160 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:45.040  1034  1653 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7165 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 08:37:45.109  7165  7165 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 08:37:45.110  7165  7165 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:37:45.111  7165  7165 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 08:37:45.112  7165  7165 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 08:37:45.163   311   892 D SoftapController: Softap fwReload - Ok
,08-29 08:37:45.169  1034  1389 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (728ms)
08-29 08:37:45.173  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 08:37:45.173  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 08:37:45.176   311   892 D CommandListener: Setting iface cfg
08-29 08:37:45.176   311   892 D CommandListener: Trying to bring down wlan0
08-29 08:37:45.177   311   892 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:37:45.185  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 08:37:45.187  1034  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 08:37:45.187  7189  7189 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:45.187  7189  7189 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:37:45.195  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:37:45.195  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:37:45.195  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:37:45.198  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-29 08:37:45.200  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:45.201  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 08:37:45.206  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:45.206  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:45.207  1034  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 08:37:45.207  1034  1389 D WifiMonitor: connecting to supplicant
08-29 08:37:45.215  7189  7189 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 08:37:45.236  7165  7165 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 08:37:45.243  7189  7189 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 08:37:45.243  7189  7189 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-29 08:37:45.254  7165  7165 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 08:37:45.291  7165  7165 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 08:37:45.329  7165  7165 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:45.329  7165  7165 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:45.367  7189  7189 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:37:45.413  7189  7189 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 08:37:45.427  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 08:37:45.427  7189  7189 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-29 08:37:45.428  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 08:37:45.429  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 08:37:45.429  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-29 08:37:45.429  1034  7199 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 08:37:45.429  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 08:37:45.429  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 08:37:45.429  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 08:37:45.429  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 08:37:45.430  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-29 08:37:45.431  1034  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 08:37:45.431  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:45.432  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 08:37:45.432  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:45.433  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:45.433  1034  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 08:37:45.433  1034  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 08:37:45.434  1034  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-29 08:37:45.434  1034  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 08:37:45.434  1034  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-29 08:37:45.435  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:37:45.435  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:37:45.435  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:37:45.435  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:45.435  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:37:45.435  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:45.435  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:45.435  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:45.435  1034  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 08:37:45.436  1034  1389 D WifiNative-wlan0: SET update_config 1: returned true
,08-29 08:37:45.436  1034  1389 D WifiConfigStore: Loading config and enabling all networks 
08-29 08:37:45.436  1034  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 08:37:45.437  1034  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-29 08:37:45.438  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 08:37:45.438  1034  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 08:37:45.439  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:45.440  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-29 08:37:45.442  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:45.442  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:45.442  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:45.442  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:45.443  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:45.443  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:45.443  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:45.443  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:45.443  1034  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 08:37:45.452  1034  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-29 08:37:45.452  1034  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:37:45.453  1034  1389 D WifiStateMachine: enableVerboseLogging : level 2
08-29 08:37:45.453  1034  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 08:37:45.454  1034  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 08:37:45.454  1034  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 08:37:45.454  1034  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 08:37:45.454  1034  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 08:37:45.455  1034  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 08:37:45.455  1034  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 08:37:45.455  1034  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 08:37:45.455  1034  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 08:37:45.455  1034  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 08:37:45.456  1034  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 08:37:45.456  1034  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 08:37:45.456  1034  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 08:37:45.456  1034  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 08:37:45.457  1034  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:37:45.457  1034  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 08:37:45.457  1034  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 08:37:45.457  1034  1389 D WifiNative-HAL: Setting external_sim to 1
08-29 08:37:45.457  1034  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 08:37:45.458  1034  1389 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 08:37:45.458  1034  1389 I WifiNative-HAL: startHal
08-29 08:37:45.458  1034  1389 D wifi    : setting scan oui 0xaf549120
08-29 08:37:45.458  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-29 08:37:45.458  1941  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 08:37:45.458  1941  2257 D WfdsService: Set the WFDS Monitor: true
08-29 08:37:45.458  1941  2257 D WfdsMonitor: WfdsMonitorThread create
08-29 08:37:45.459  1034  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:37:45.459  1941  2257 D WfdsMonitor: WFDS Monitor is created and started
08-29 08:37:45.459  1034  1389 I WifiNative-HAL: startHal
08-29 08:37:45.459  1941  2257 D WfdsService: WiFi: Supplicant connection re-established
08-29 08:37:45.459  1034  1389 D wifi    : setting scan oui 0xaf549120
08-29 08:37:45.459  1034  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 08:37:45.459  1941  7201 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 08:37:45.459  1034  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 08:37:45.459  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 08:37:45.459  1941  7201 E CtrlSupplicant: Succeed to open control connection
08-29 08:37:45.459  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 08:37:45.460  1941  7201 E CtrlSupplicant: Succeed to open monitor connection
08-29 08:37:45.460  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 08:37:45.460  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 08:37:45.460  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 08:37:45.460  1941  7201 D WfdsMonitor: Supplicant connection established
08-29 08:37:45.460  1941  2257 D WfdsService: Connected to the supplicant for wfds
08-29 08:37:45.460  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 08:37:45.460  1034  ,1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 08:37:45.461  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 08:37:45.461  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 08:37:45.461  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 08:37:45.461  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 08:37:45.461  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 08:37:45.461  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 08:37:45.461  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 08:37:45.462  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 08:37:45.462  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 08:37:45.462  7189  7189 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 08:37:45.462  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 08:37:45.462  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 08:37:45.462  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 08:37:45.462  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 08:37:45.463  1034  1389 E WifiNative: : [122,175,786 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 08:37:45.463  1034  1389 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 08:37:45.464  1034  1389 D WifiNative-wlan0: RECONNECT: returned true
08-29 08:37:45.464  1034  1389 D WifiNative-wlan0: doString: [STATUS]
08-29 08:37:45.464  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 08:37:45.464  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-29 08:37:45.465  1034  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 08:37:45.465  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:37:45.465  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:37:45.465  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.467   311   892 D CommandListener: Setting iface cfg
08-29 08:37:45.467   311   892 D CommandListener: Trying to bring up p2p0
,08-29 08:37:45.467  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 08:37:45.467  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-29 08:37:45.467  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.467  1034  1556 I WifiNative-HAL: startHal
08-29 08:37:45.467  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf549120
08-29 08:37:45.467  1034  1556 D wifi    : failed to get capabilities : -3
08-29 08:37:45.467  1034  1556 E WifiScanningService: could not get scan capabilities
08-29 08:37:45.467  1034  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.468  1034  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 08:37:45.468  1034  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 08:37:45.468  1034  1388 D LGWifiP2pService: P2pEnablingState
08-29 08:37:45.468  1034  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.468  1034  1388 D LGWifiP2pService: P2p socket connection successful
08-29 08:37:45.468  1034  1388 D LGWifiP2pService: P2pEnabledState
08-29 08:37:45.468  1034  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 08:37:45.468  1034  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 08:37:45.469  1034  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 08:37:45.469  1034  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 08:37:45.469  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 08:37:45.469  1941  1941 D WfdsService: WifiP2pState is changed : true
08-29 08:37:45.469  1941  2257 D WfdsService: Receive the WFDS_ENABLE Method
08-29 08:37:45.469  1941  2257 D WfdsService: Set the WFDS Monitor: true
08-29 08:37:45.469  1941  2257 D WfdsService: Connected to the supplicant for wfds
08-29 08:37:45.469  1034  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 08:37:45.469  1941  2257 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 08:37:45.469  7189  7189 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 08:37:45.470  1034  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 08:37:45.470  1034  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 08:37:45.470  1941  2257 D WfdsService: selectPreferredScanChannel [36]
08-29 08:37:45.470  1941  2257 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 08:37:45.470  7189  7189 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 08:37:45.471  1034  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 08:37:45.471  1034  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 08:37:45.471  1034  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 08:37:45.471  1034  1389 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 08:37:45.471  1034  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 08:37:45.471  7189  7189 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 08:37:45.471  7165  7165 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 08:37:45.471  1034  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 08:37:45.472  1034  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 08:37:45.472  1034  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 08:37:45.472  1034  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 08:37:45.472  1034  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 08:37:45.473  1034  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 08:37:45.473  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ,
08-29 08:37:45.473  1034  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-29 08:37:45.473  1034  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 08:37:45.473  1034  1388 D LGWifiP2pService: before postfix = G3
08-29 08:37:45.473  1034  1388 D WifiServerServiceExt: postfix byte check : 2
08-29 08:37:45.473  1034  1388 D LGWifiP2pService: after postfix = G3
08-29 08:37:45.473  1034  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 08:37:45.473  1034  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 08:37:45.473  1034  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 08:37:45.473  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 08:37:45.473  1034  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 08:37:45.473  1034  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 08:37:45.474  1034  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 08:37:45.474  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 08:37:45.474  1941  1941 D WfdsService: isConnected: false
08-29 08:37:45.474  1034  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 08:37:45.474  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-29 08:37:45.474  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 08:37:45.475  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 08:37:45.475  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 08:37:45.476  1034  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 08:37:45.476  1034  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 08:37:45.476  1941  1941 D WfdsService: Update P2p Interface State: 3
08-29 08:37:45.476  1034  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 08:37:45.477  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-29 08:37:45.479  1034  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-29 08:37:45.479  1034  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 08:37:45.479  1034  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 08:37:45.480  1034  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 08:37:45.480  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 08:37:45.481  7189  7189 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.481  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 08:37:45.481  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.481  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.481  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-29 08:37:45.481  7189  7189 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 08:37:45.481  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.481  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.481  1034  7199 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.481  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.481  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.481  1034  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 08:37:45.482  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.482  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.482  1034  7199 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.482  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.482  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.483  1941  7201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.483  1941  7201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.484  1034  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 08:37:45.484  1034  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 08:37:45.486  1034  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 08:37:45.486  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 08:37:45.494  1034  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 08:37:45.494  1034  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 08:37:45.494  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 08:37:45.494  7189  7189 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:37:45.494  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 08:37:45.494  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:37:45.494  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:37:45.494  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:37:45.495  1034  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 08:37:45.495  1034  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 08:37:45.495  1034  1388 D LGWifiP2pService: InactiveState
08-29 08:37:45.495  1034  1388 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.495  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.495  1034  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 08:37:45.495  1034  1389 D WifiNative-wlan0: doBoolean: SCAN
08-29 08:37:45.495  1034  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 08:37:45.496  1034  1389 D WifiNative-wlan0: SCAN: returned false
08-29 08:37:45.496  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122209  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-29 08:37:45.497  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 08:37:45.497  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122210  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 08:37:45.498  1034  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:37:45.498  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.498  1941  7201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 08:37:45.498  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:45.499  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:45.499  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 08:37:45.499  7189  7189 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 08:37:45.499  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.499  1034  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 08:37:45.499  1034  7199 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.499  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.499  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.500  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:37:45.500  1034  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.500  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.500  1034  7199 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.500  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.500  1034  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.500  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.500  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.500  1034  7199 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type,=WORLD
08-29 08:37:45.500  1034  7199 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.500  1034  7199 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:37:45.500  1941  7201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.500  1941  7201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:37:45.500  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:45.500  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:45.501  1034  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:37:45.500  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.501  1034  1388 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.501  1034  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:37:45.501  1941  2257 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 08:37:45.501  1034  1388 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.501  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.501  1034  1388 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:45.502  1034  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:37:45.502  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:45.502  1034  1034 E WifiServerServiceExt: No p2p device connected
08-29 08:37:45.502  1034  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:37:45.503  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:37:45.503  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 08:37:45.510  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 08:37:45.510  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:45.510  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 08:37:45.516  7165  7165 I HubEmail: JNI_OnLoad()
08-29 08:37:45.516  7165  7165 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 08:37:45.516  7165  7165 I HubEmail: registerNatives()
08-29 08:37:45.516  7165  7165 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 08:37:45.516  7165  7165 I HubEmail: registerNativeMethods()
08-29 08:37:45.516  7165  7165 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 08:37:45.516  7165  7165 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 08:37:45.540  1034  1995 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7207 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 08:37:45.546  7019  7203 W FormManager: Network not available. Please check & try again.
08-29 08:37:45.547  7165  7206 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:45.548  7019  7205 V FormManager: Network unavailable.
,08-29 08:37:45.550  7019  7205 V FormManager: Network unavailable.
08-29 08:37:45.555  1034  1653 I ActivityManager: Killing 6680:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 08:37:45.593  1034  1887 W libprocessgroup: failed to open /acct/uid_10061/pid_6680/cgroup.procs: No such file or directory
,08-29 08:37:45.669  7207  7207 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 08:37:45.669  7207  7207 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:45.671  7207  7207 D PhoneMonitor: Register our PhoneStateListener
08-29 08:37:45.687  7207  7207 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 08:37:45.689  7207  7207 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 08:37:45.713  7207  7207 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 08:37:45.714  7207  7207 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 08:37:45.714  7207  7207 D TelephonyAutoProfiling: [parse] Load xml
08-29 08:37:45.716  7207  7207 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 08:37:45.716  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 08:37:45.716  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 08:37:45.716  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 08:37:45.716  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 08:37:45.717  7207  7207 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 08:37:45.717  7207  7207 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-29 08:37:45.723  7207  7207 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-29 08:37:45.764  1034  1050 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7226 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 08:37:45.765  1034  1050 I ActivityManager: Killing 5593:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-29 08:37:45.814  1034  1049 W libprocessgroup: failed to open /acct/uid_10097/pid_5593/cgroup.procs: No such file or directory
,08-29 08:37:46.013  1034  1050 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7247 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 08:37:46.020  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 08:37:46.020  1034  7199 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 08:37:46.020  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 08:37:46.021  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-29 08:37:46.021  1034  7199 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 08:37:46.021  7189  7189 E wpa_supplicant: USIM:  scard_init function
08-29 08:37:46.022  1034  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 08:37:46.022  7189  7189 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 08:37:46.022  1034  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 08:37:46.024  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 08:37:46.024  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 08:37:46.024  1034  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 08:37:46.024  1034  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 08:37:46.024  1034  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 08:37:46.026  1034  1050 I ActivityManager: Killing 6788:com.lge.eula/1000 (adj 15): empty #17
,08-29 08:37:46.077  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122790  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 08:37:46.079  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122791  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 08:37:46.081  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.081  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.081  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 08:37:46.086  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.086  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.086  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.086  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 08:37:46.086  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:37:46.086  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 08:37:46.086  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.090  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:37:46.093  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.093  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.095  1034  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6788/cgroup.procs: No such file or directory
08-29 08:37:46.097  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.142  7189  7189 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 08:37:46.144  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 08:37:46.144  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 08:37:46.144  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 08:37:46.144  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 08:37:46.144  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:37:46.144  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 08:37:46.145  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122858  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 08:37:46.146  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122859  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 08:37:46.147  1034  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122860
08-29 08:37:46.147  1034  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122860
08-29 08:37:46.148  1034  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122861
08-29 08:37:46.148  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122861
08-29 08:37:46.149  1034  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122861
08-29 08:37:46.149  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122862  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 08:37:46.152  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:37:46.152  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:37:46.152  7189  7189 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:37:46.152  7189  7189 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 08:37:46.152  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 08:37:46.152  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:37:46.152  1034  7199 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:37:46.152  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 08:37:46.152  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 08:37:46.152  1034  7199 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 08:37:46.154  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:37:46.154  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:37:46.227  1034  1923 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7268 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 08:37:46.229  1034  1923 I ActivityManager: Killing 6807:com.lge.bnr/1000 (adj 15): empty #17
,08-29 08:37:46.284  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 08:37:46.287  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 08:37:46.296  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6807/cgroup.procs: No such file or directory
,08-29 08:37:46.299  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123011  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 08:37:46.301  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123014  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 08:37:46.303  1034  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123016
08-29 08:37:46.303  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.303  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.304  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.304  1034  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123017
08-29 08:37:46.304  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.304  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 08:37:46.306  1034  1389 D WifiNative-wlan0: doString: [STATUS]
08-29 08:37:46.307  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.307  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.307  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.307  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 08:37:46.307  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:37:46.307  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 08:37:46.307  1034  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 08:37:46.307  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:37:46.307  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:37:46.309  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.309  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.309  1034  1389 I WifiServiceExtension: setVHTCapabilityType  : false
,08-29 08:37:46.311  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.316  1034  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 08:37:46.316  1034  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 08:37:46.321  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.322  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.322  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-29 08:37:46.327  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.327  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.327  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 08:37:46.329  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.329  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.330  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.331  1034  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 08:37:46.331  1034  1439 D ConnectivityService: Got NetworkAgent Messenger
08-29 08:37:46.331  1034  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:37:46.331  1034  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 08:37:46.331  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 08:37:46.331  1034  1439 D ConnectivityService: NetworkAgent connected
08-29 08:37:46.331  1034  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 08:37:46.331  1034  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 08:37:46.332  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.332  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.334  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.336  1034  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 08:37:46.337  1034  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:37:46.337  1034  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-29 08:37:46.338  1034  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 08:37:46.338  1034  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 08:37:46.343  7268  7268 I art     : Almond Protected OAT
08-29 08:37:46.345  1034  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 08:37:46.355   311   892 D CommandListener: Setting iface cfg
,08-29 08:37:46.358  1034  1389 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 08:37:46.358  1034  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123071  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:37:46.359  1034  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123072  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:37:46.359  1034  7288 D DhcpStateMachine: StoppedState
,08-29 08:37:46.360  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123072  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:37:46.360  1034  7288 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.360  1034  7288 D DhcpStateMachine: WaitBeforeStartState
08-29 08:37:46.360  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:46.361  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:46.361  1034  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:46.361  1034  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:46.362  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:46.362  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:46.364  1034  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123076  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:37:46.364  1034  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123077  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:37:46.365  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123077  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:37:46.366  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77251] from screen [on:0 period:-721116162] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 08:37:46.367  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-721116161] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 08:37:46.367  1034  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-29 08:37:46.373  1034  1439 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 08:37:46.373  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:46.374  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:46.374  1034  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:46.375  1034  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:46.375  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:46.376  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:46.376  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 08:37:46.377  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
08-29 08:37:46.377  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
,08-29 08:37:46.377  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 08:37:46.378  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 08:37:46.378  1034  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 08:37:46.378  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 08:37:46.379  1034  1389 D WifiNative-wlan0: SET ps 0: returned true
08-29 08:37:46.379  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 08:37:46.379  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 08:37:46.379  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 08:37:46.379  1034  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 08:37:46.379  1034  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 08:37:46.379  1034  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-29 08:37:46.381   311   892 D CommandListener: Setting iface cfg
08-29 08:37:46.381   311   892 D CommandListener: Trying to bring up wlan0
08-29 08:37:46.381  1034  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.382  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.382  1034  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.382  1034  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d15052e target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.382  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d15052e target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.382  1034  7288 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.382  1034  7288 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 08:37:46.383  1034  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 08:37:46.384  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 08:37:46.384  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 08:37:46.384  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 08:37:46.385  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 08:37:46.385  1034  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.385  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.385  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 08:37:46.385  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 08:37:46.385  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:37:46.385  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 08:37:46.385  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 08:37:46.386  1034  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 08:37:46.386  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:37:46.387  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.398  7268  7268 D WeatherApplication: removeAccount
,08-29 08:37:46.399  7268  7268 D WeatherApplication: Account.length = 0
08-29 08:37:46.399  7268  7268 E WeatherApplication: OPERATOR:OPEN
08-29 08:37:46.404  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:46
08-29 08:37:46.405  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:37:46.406  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 08:37:46.406  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:37:46.407  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 08:37:46.407  1034  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:37:46.407  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 08:37:46.407  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 08:37:46.407  1034  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:37:46.408  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:37:46.408  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:37:46.409  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 08:37:46.409  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 08:37:46.409  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 08:37:46.410  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 08:37:46.410  1034  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 08:37:46.410  1034  1439 D ConnectivityService: ignoring duplicate network state non-change
08-29 08:37:46.412  7268  7268 D WeatherAncestor: connectivity changed - connection : true
,08-29 08:37:46.413  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 08:37:46.419  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 08:37:46.419  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.421  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.424  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 08:37:46.424  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 08:37:46.424  7268  7268 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-29 08:37:46.427  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.428  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.428  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 08:37:46.429  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 08:37:46.431  1034  1439 D ConnectivityService: Adding iface wlan0 to network 101
08-29 08:37:46.439  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.439  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.439  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 08:37:46.443  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 08:37:46.444  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.444  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:46.446  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.447  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 08:37:46.448  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.448  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 08:37:46.448  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.449  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.449  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.449  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-29 08:37:46.451  1034  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 08:37:46.455  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 08:37:46.460  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.460  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:46.460  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 08:37:46.465  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 08:37:46.466  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:46
,08-29 08:37:46.472  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:46.472  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 08:37:46.472  1034  1439 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 08:37:46.472  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.472  1034  1439 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 08:37:46.473  1034  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 08:37:46.473  1034  1439 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 08:37:46.473  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 08:37:46.474  1034  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 08:37:46.474   311   892 E Netd    : netlink response contains error (File exists)
08-29 08:37:46.474  1034  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 08:37:46.474  1034  1439 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 08:37:46.474  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 08:37:46.476  1034  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 08:37:46.476  1034  1439 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 08:37:46.476  1034  1439 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 08:37:46.476  1034  1439 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 08:37:46.508  1034  1995 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7292 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 08:37:46.511  1034  1995 I ActivityManager: Killing 2148:com.lge.music/u0a34 (adj 15): empty #17
08-29 08:37:46.529   342   342 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 392us total 21.006ms
,08-29 08:37:46.535   315  2157 V AudioFlinger: 2148 died, releasing its sessions
08-29 08:37:46.535   315  2157 V AudioFlinger:  pid 1852 @ 0
08-29 08:37:46.535   315  2157 V AudioFlinger:  pid 3444 @ 1
08-29 08:37:46.535   315  2157 V AudioFlinger:  pid 3444 @ 2
08-29 08:37:46.548   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 335us total 18.036ms
,08-29 08:37:46.564   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 345us total 16.346ms
,08-29 08:37:46.585  1034  7288 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 08:37:46.587  1034  7288 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 08:37:46.587  1034  7288 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 08:37:46.587  7310  7310 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:46.594  1034  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 08:37:46.594  1034  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.594  1034  1439 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.594  1034  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.595  1034  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:37:46.595  1034  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:46.587  7310  7310 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:46.595  1034  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 08:37:46.595  1034  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.595  1034  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 08:37:46.595  1034  1439 D ConnectivityService: currentScore = 0, newScore = 20
08-29 08:37:46.595  1034  1439 D ConnectivityService:    accepting network in place of null
08-29 08:37:46.596  1034  1439 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.596  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.596  1034  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.597  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 08:37:46.597  1034  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:37:46.597  1034  1923 W libprocessgroup: failed to open /acct/uid_10034/pid_2148/cgroup.procs: No such file or directory
,08-29 08:37:46.597  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:46.597  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 08:37:46.598  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:37:46.598  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-29 08:37:46.607  7310  7310 I dhcpcd  : version 5.5.6 starting
08-29 08:37:46.608  1034  1439 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 08:37:46.608  1034  1439 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 08:37:46.609  7310  7310 E dhcpcd  : get_duid: m
08-29 08:37:46.609  7310  7310 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 08:37:46.609  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 08:37:46.609  7310  7310 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 08:37:46.614   311  7312 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-29 08:37:46.617  1034  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:46.617  1034  1439 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 08:37:46.618  1034  1439 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 08:37:46.619  1034  1439 D ConnectivityService: validation of new default Network = false
08-29 08:37:46.619  1034  1439 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 08:37:46.619  1034  1439 D DSQN    : enableDataServiceNotify 
08-29 08:37:46.619  1034  1439 D DSQN    : start dsqn bin
08-29 08:37:46.623  1034  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.623  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.623  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:46.623  1034  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:46.617  7315  7315 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:46.617  7315  7315 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:46.626  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 08:37:46.627  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 08:37:46.627  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 08:37:46.627  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 08:37:46.627  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 08:37:46.640  7315  7315 E DSQN    : DSQN ssw
08-29 08:37:46.656  1034  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-29 08:37:46.669  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:37:46.670  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.670   311  7312 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 08:37:46.671  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.675  7310  7310 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 08:37:46.676  7310  7310 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 08:37:46.676  7310  7310 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 08:37:46.676  1817  7322 I CheckinService: active receiver: enabled
08-29 08:37:46.676  7310  7310 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 08:37:46.676  7310  7310 D dhcpcd  : wlan0: sending REQUEST (xid 0x3a0c3040), next in 3.19 seconds
,08-29 08:37:46.686  1817  7322 I CheckinService: Preparing to send checkin request
08-29 08:37:46.686  1817  7322 I EventLogService: Accumulating logs since 1472452602040
08-29 08:37:46.690  1817  7322 W EventLogAggregator: Unknown tag: snet_gcore
08-29 08:37:46.690  1817  7322 W EventLogAggregator: Unknown tag: snet_launch_service
08-29 08:37:46.695  7310  7310 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 08:37:46.707   311  7312 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 08:37:46.722  7310  7310 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 08:37:46.722  7310  7310 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-29 08:37:46.723  7310  7310 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 08:37:46.723  7310  7310 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 08:37:46.723  7310  7310 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 08:37:46.723  7310  7310 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 08:37:46.724  7310  7310 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 08:37:46.724  7310  7310 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-29 08:37:46.735   311   891 D LGDataListener: argv[0]=dsqncommand
08-29 08:37:46.735   311   891 D LGDataListener: argv[1]=wlan0
08-29 08:37:46.735   311   891 D LGDataListener: argv[2]=1
08-29 08:37:46.735   311   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 08:37:46.735  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 08:37:46.736  1034  1114 D DSQN    : start to monitor internet connection
08-29 08:37:46.736  1817  7322 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-29 08:37:46.745   278   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 08:37:46.745   278   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 08:37:46.745   278   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 08:37:46.747  7292  7330 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-29 08:37:46.755   278   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 08:37:46.755   278   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 08:37:46.755   278   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 08:37:46.756  7292  7330 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 08:37:46.764  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 06:37:46 GMT], X-Android-Received-Millis=[1472452666764], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472452666734]}
08-29 08:37:46.764  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-29 08:37:46.764  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 08:37:46.765  1034  1439 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.765  1034  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.765  1034  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:37:46.765  1034  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:46.765  1034  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 08:37:46.765  1034  1439 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-29 08:37:46.765  1034  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:46.765  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.765  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:46.765  1034  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:46.766  1034  1439 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 08:37:46.766  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 08:37:46.766  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 08:37:46.766  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.767  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 08:37:46.767  1034  1389 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:46.767  1034  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:37:46.771   278   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 08:37:46.771   278   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 08:37:46.771   278   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 08:37:46.772  7292  7335 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 08:37:46.774   278   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 08:37:46.774   278   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 08:37:46.774   278   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 08:37:46.775  7292  7335 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 08:37:46.789  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:37:46.790  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:46.790  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:37:46.884  1034  1575 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7351 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 08:37:46.942  7351  7351 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 08:37:46.942  7351  7351 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 08:37:46.973  7351  7351 I MultiDex: VM with version 2.1.0 has multidex support
08-29 08:37:46.973  7351  7351 I MultiDex: install
08-29 08:37:46.973  7351  7351 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 08:37:46.982  7351  7351 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 08:37:46.992  1034  7288 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 08:37:46.994  1034  7288 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 08:37:46.994  1034  7288 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-29 08:37:46.994  1034  7288 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-29 08:37:46.994  1034  7288 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 08:37:46.994  1034  7288 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 08:37:46.994  1034  7288 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 08:37:46.994  1034  7288 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 08:37:46.994  1034  7288 D DhcpStateMachine: RunningState
08-29 08:37:47.033  7292  7292 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 08:37:47.044  7292  7292 I LibraryLoader: Loading: webviewchromium
08-29 08:37:47.049  7292  7292 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3771-3776)
08-29 08:37:47.049  7292  7292 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 08:37:47.056  7292  7292 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {387c261b}
08-29 08:37:47.058  7292  7292 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:37:47.058  7292  7292 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 08:37:47.071  7292  7292 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 08:37:47.073  7292  7292 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 08:37:47.086  7292  7292 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 08:37:47.087  7292  7292 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 08:37:47.087  7292  7292 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 08:37:47.097   315  1400 V AudioPolicyService: registerClient() client 0xb0403d80, uid 10093
,08-29 08:37:47.100  7292  7391 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 08:37:47.114  7292  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 08:37:47.114  7292  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 08:37:47.114  7292  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-29 08:37:47.114  7292  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 08:37:47.114  7292  7292 I Adreno-EGL: Remote Branch: 
08-29 08:37:47.114  7292  7292 I Adreno-EGL: Local Patches: 
08-29 08:37:47.114  7292  7292 I Adreno-EGL: Reconstruct Branch: 
,08-29 08:37:47.199  7292  7292 I NSApplication: Starting up...
,08-29 08:37:47.264  1034  1923 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7404 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 08:37:47.265  1034  1923 I ActivityManager: Killing 6232:com.android.vending/u0a44 (adj 15): empty #17
,08-29 08:37:47.361  7351  7370 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:47.361  7351  7370 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:47.377  1034  1958 W libprocessgroup: failed to open /acct/uid_10044/pid_6232/cgroup.procs: No such file or directory
,08-29 08:37:47.438  1034  1976 D WifiServiceImplEx: setWifiEnabled: false pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 08:37:47.438  1034  1976 D WifiService: setWifiEnabled: false pid=6741, uid=10118
,08-29 08:37:47.438  1034  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 08:37:47.440  7404  7404 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 08:37:47.450  7424  7424 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-29 08:37:47.459  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:47.460  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 08:37:47.464  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 08:37:47.464  1034  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:47.464  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:47.464  1034  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:47.465  1034  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:47.465  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 08:37:47.465  1034  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 08:37:47.465  1034  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:37:47.465  1034  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 08:37:47.466  1034  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 08:37:47.466  1034  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 08:37:47.473  1034  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 08:37:47.473  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 08:37:47.474  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 08:37:47.474  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.474  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.474  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 08:37:47.474  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:37:47.474  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
,08-29 08:37:47.475   311   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:37:47.477  1034  7288 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.500  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:37:47.500  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-29 08:37:47.502  1034  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:47.507  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:47.507  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:47.508  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.509  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 08:37:47.510  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:47.510  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:47.510  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.511  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 08:37:47.512  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.512  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.512  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:47.512  1034  1388 D LGWifiP2pService: InactiveState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.512  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.512  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 08:37:47.512  1034  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@6c82d8e
08-29 08:37:47.512  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.512  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.512  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:47.512  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 08:37:47.512  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-29 08:37:47.512  1034  1388 D LGWifiP2pService: P2pDisablingState
08-29 08:37:47.512  1034  1388 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.512  1034  1388 D LGWifiP2pService: p2p socket connection lost
08-29 08:37:47.512  1034  1388 D LGWifiP2pService: P2pDisabledState
,08-29 08:37:47.515  1034  1557 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.517  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 08:37:47.517  1941  1941 D WfdsService: WifiP2pState is changed : false
08-29 08:37:47.517  1034  1556 D WifiScanningService: DefaultState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.523  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:47.523  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:37:47.524  1034  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 08:37:47.524  1034  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 08:37:47.524  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.524  1034  1388 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.524  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 08:37:47.525  7189  7189 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-29 08:37:47.525  1941  2257 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 08:37:47.526  1941  2257 D WfdsService: Set the WFDS Monitor: false
08-29 08:37:47.533  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 08:37:47.533  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:37:47.534  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:37:47.538  1941  2257 D WfdsMonitor: WFDS Monitor is stopped
08-29 08:37:47.538  1941  2257 D WfdsService: STATE : WfdsDisabledState - enter
08-29 08:37:47.538  1941  7201 D CtrlSupplicant: Received on exit socket, terminate
08-29 08:37:47.538  1941  7201 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 08:37:47.538  1941  7201 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 08:37:47.538  1941  7201 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 08:37:47.538  1941  2258 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 08:37:47.538  1941  2257 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 08:37:47.539  7424  7424 I dex2oat : dex2oat took 87.803ms (threads: 4)
,08-29 08:37:47.553  7351  7370 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 08:37:47.553  7351  7370 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 08:37:47.553  7351  7370 I Adreno-EGL: Build Date: 12/12/14 금
08-29 08:37:47.553  7351  7370 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 08:37:47.553  7351  7370 I Adreno-EGL: Remote Branch: 
08-29 08:37:47.553  7351  7370 I Adreno-EGL: Local Patches: 
08-29 08:37:47.553  7351  7370 I Adreno-EGL: Reconstruct Branch: 
,08-29 08:37:47.556   311   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:37:47.557  1034  1439 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 08:37:47.557  1034  1439 D DSQN    : disableDataServiceNotify
08-29 08:37:47.557  1034  1439 D DSQN    : stop dsqn bin
08-29 08:37:47.559  1034  1389 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 08:37:47.559  1034  1389 D WifiNative-p2p0: TERMINATE: returned true
08-29 08:37:47.559  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:37:47.559  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:37:47.559  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:37:47.560  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 08:37:47.560  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 08:37:47.560  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:37:47.561  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.563  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.563  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.563  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:37:47.563  1034  1439 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:47.563  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:47.563  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:47.564  1034  1439 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:37:47.564  1034  1439 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 08:37:47.564  1034  1439 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 08:37:47.564  1034  1439 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 08:37:47.564  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 08:37:47.564  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 08:37:47.564  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 08:37:47.565  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.565  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
0,8-29 08:37:47.565  1034  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 08:37:47.565  1034  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:47.565  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 08:37:47.566  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 08:37:47.566  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:37:47.566  1034  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:47.566  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 08:37:47.566  1034  1439 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:47.566  1034  1439 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:47.566  1034  1439 D NetworkManagementService: Removing idletimer
08-29 08:37:47.566  1034  1439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.566  1034  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:47.566  1034  1439 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 08:37:47.566  1034  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 08:37:47.566  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:37:47.567  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 08:37:47.567  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:47.567  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:47.567  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:47.567  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 08:37:47.567  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 08:37:47.567  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 08:37:47.567  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 08:37:47.567  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:47.567  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:47.567  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:47.567  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:47.567  1034  1034 D LocSvc_java: Sendin,g msg: 4 arg1:0 arg2:1
08-29 08:37:47.568  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 08:37:47.568  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 08:37:47.568  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 08:37:47.568  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 08:37:47.568  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-29 08:37:47.580  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.598  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:37:47.599  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.600  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:37:47.617  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:37:47.618  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.619  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.623  1034  1439 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-29 08:37:47.641  1034  1976 I art     : Explicit concurrent mark sweep GC freed 115951(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.277ms total 97.953ms
,08-29 08:37:47.645  7351  7370 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 08:37:47.645  7351  7370 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 08:37:47.645  7351  7370 I Adreno-EGL: Build Date: 12/12/14 금
08-29 08:37:47.645  7351  7370 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 08:37:47.645  7351  7370 I Adreno-EGL: Remote Branch: 
08-29 08:37:47.645  7351  7370 I Adreno-EGL: Local Patches: 
08-29 08:37:47.645  7351  7370 I Adreno-EGL: Reconstruct Branch: 
08-29 08:37:47.679  7189  7189 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 08:37:47.679  7189  7189 I wpa_supplicant: monitor socket send errors count : 1
08-29 08:37:47.679  7189  7189 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-29 08:37:47.680  1034  7288 D DhcpStateMachine: StoppedState
08-29 08:37:47.680  1034  7288 D DhcpStateMachine: StoppedState{ when=-146ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:37:47.681  1034  7199 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 08:37:47.681  1034  7199 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 08:37:47.682  1034  1389 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 08:37:47.683  1034  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 08:37:47.683  7351  7370 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 08:37:47.683  7351  7370 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 08:37:47.683  7351  7370 I Adreno-EGL: Build Date: 12/12/14 금
08-29 08:37:47.683  7351  7370 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 08:37:47.683  7351  7370 I Adreno-EGL: Remote Branch: 
08-29 08:37:47.683  7351  7370 I Adreno-EGL: Local Patches: 
08-29 08:37:47.683  7351  7370 I Adreno-EGL: Reconstruct Branch: 
08-29 08:37:47.702  7189  7189 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 08:37:47.703  7189  7189 W wpa_supplicant: USIM:  scard_deinit function
08-29 08:37:47.703  1034  1116 D Tethering: InitialState.processMessage what=4
,08-29 08:37:47.703  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 08:37:47.703  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 08:37:47.703  1034  7199 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 08:37:47.703  1034  7199 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-29 08:37:47.703  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:37:47.703  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:37:47.703  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 08:37:47.704  1034  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124417
08-29 08:37:47.705  1034  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124418
08-29 08:37:47.706  1034  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124418  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 08:37:47.706  1034  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124419  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-29 08:37:47.707  1034  1389 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:47.707  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:37:47.795  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 08:37:47.799  6543  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 08:37:47.810  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:47.820  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 08:37:47.820  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:47.820  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 08:37:47.820  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 08:37:47.821  7127  7127 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 08:37:47.826  7127  7127 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e343b70
08-29 08:37:47.826  7127  7127 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 08:37:47.826  7127  7127 D AppUp4:CustFacade: isPhone : true
08-29 08:37:47.826  7127  7127 D AppUp4:CustModeStarterReceiver: begin check event
08-29 08:37:47.826  7127  7127 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 08:37:47.831  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:47.831  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:47.832  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:47.835  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 08:37:47.844  7165  7165 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 08:37:47.845  4325  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 08:37:47.846  4325  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:47.847  4325  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:47.863  7165  7456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:37:47.867  7189  7189 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 08:37:47.867  1034  7199 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 08:37:47.867  1034  7199 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 08:37:47.867  1034  7199 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 08:37:47.868  1034  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-29 08:37:47.869  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 08:37:47.869  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:47.869  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 08:37:47.872   311  7462 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 08:37:47.873  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 08:37:47.873  7207  7207 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 08:37:47.874  7207  7207 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 08:37:47.874  1817  7322 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-29 08:37:47.875  7019  7459 W FormManager: Network not available. Please check & try again.
,08-29 08:37:47.880  7019  7460 V FormManager: Network unavailable.
08-29 08:37:47.882  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:47
08-29 08:37:47.884  1817  7322 I CheckinService: active receiver: disabled
08-29 08:37:47.885  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 08:37:47.885  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 08:37:47.890  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 08:37:47.890  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 08:37:47.890  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fe9d76e
08-29 08:37:47.891  7019  7460 V FormManager: Network unavailable.
08-29 08:37:47.891  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 08:37:47.891  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 08:37:47.891  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 08:37:47.891  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 08:37:47.891  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:47
08-29 08:37:47.913  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 08:37:47.913  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 08:37:47.913  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 08:37:47.913  6927  6927 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 08:37:47.914  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 08:37:47.915  6927  6927 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 08:37:47.915  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 08:37:47.915  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 08:37:47.915  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 08:37:47.915  6927  6927 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 08:37:47.915  6927  6927 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 08:37:47.922  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:47.925  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 08:37:47.931  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:47.936  7019  7464 W FormManager: Network not available. Please check & try again.
08-29 08:37:47.940  7019  7465 V FormManager: Network unavailable.
,08-29 08:37:47.944  7019  7465 V FormManager: Network unavailable.
08-29 08:37:47.947  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:47.950  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED,
,08-29 08:37:47.955  7019  7466 W FormManager: Network not available. Please check & try again.
08-29 08:37:47.956  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:47.963  7019  7467 V FormManager: Network unavailable.
,08-29 08:37:47.969  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-29 08:37:47.969  1941  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 08:37:47.969  1941  2257 D WfdsService: Set the WFDS Monitor: false
08-29 08:37:47.969  1941  2257 D WfdsMonitor: WFDS Monitor is stopped
08-29 08:37:47.971  1034  1389 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 08:37:47.971  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:37:47.971  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:37:47.971  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:37:47.973  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:37:47.973  7019  7467 V FormManager: Network unavailable.
08-29 08:37:47.973  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:47.973  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 08:37:47.974  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 08:37:47.974  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:47.975  1034  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 08:37:47.975  1034  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 08:37:47.975  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:47.976  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:47.976  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:47.978  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:37:47.978  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:47.989  4325  7468 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 08:37:47.990  4325  7469 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:37:47.990  4325  7469 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:48.031  1034  1887 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7470 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 08:37:48.132  7470  7470 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 08:37:48.132  7470  7470 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 08:37:48.141  7470  7470 V [BNRBootReceiver]: Boot Receiver Return
08-29 08:37:48.142  7470  7470 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 08:37:48.150  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.162  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.171  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.189  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.190  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.193  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 08:37:48.201  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 08:37:48.204  6927  6927 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-29 08:37:48.209  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.227  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.240  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 08:37:48.255  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:37:48.256  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:48.258  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 08:37:48.272  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.287  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.293  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.304  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.304  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:48.305  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 08:37:48.312  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:48.325  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.329  6851  7100 D UEI.SmartControl: Internal timer expired: 2
08-29 08:37:48.329  6851  7100 D UEI.SmartControl: unbind internal service
08-29 08:37:48.334  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.344  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.345  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.345  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:37:48.353  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:48.359  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.365  6851  7094 D serial_port: close(fd = 24)
08-29 08:37:48.368  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.368  6851  7094 I UEI.SmartControl: Serial port is closed.
08-29 08:37:48.374  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.375  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.375  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:37:48.379  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:48.388  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.397  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.406  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.407  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.408  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:37:48.411  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:48.425  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.436  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.448  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:37:48.449  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.450  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:37:48.463  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.482  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.494  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.508  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.508  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.516  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:37:48.526  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.543  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.554  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.567  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:37:48.568  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.569  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:37:48.589  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.598  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 08:37:48.608  1034  1421 D WifiService: New client listening to asynchronous messages
,08-29 08:37:48.611  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:37:48.618  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.625  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.633  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.633  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:48.635  6978  6978 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 08:37:48.636  6978  6978 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 08:37:48.637  6978  6978 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 08:37:48.644  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:48.648  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 08:37:48.649  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:48.654  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.663  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.672  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.672  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:48.673  6978  6978 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 08:37:48.674  6978  6978 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-29 08:37:48.674  6978  6978 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 08:37:48.678  1034  1049 I ActivityManager: Killing 6908:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-29 08:37:48.709  1034  2033 W libprocessgroup: failed to open /acct/uid_10037/pid_6908/cgroup.procs: No such file or directory
,08-29 08:37:48.717  2081  2081 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 08:37:48.735  2081  2081 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 08:37:48.735  2081  2081 D c       : Getting all permits...
08-29 08:37:48.735  2081  2081 D a       : Opening database...
08-29 08:37:48.743  2081  2081 D a       : Opening database auth.proximity.permit_store...
08-29 08:37:48.744  2081  2081 D a       : Closing database...
08-29 08:37:48.756  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.763  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 08:37:48.763  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:48.763  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:48.768  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.775  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.783  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:37:48.784  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:48.786  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 08:37:48.791  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:37:48.795  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 08:37:48.795  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:48.795  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:48.800  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.807  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 08:37:48.815  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:37:48.815  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:37:48.819  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 08:37:48.823  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:37:48.827  6949  6949 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 08:37:48.827  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:48.827  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:37:48.831  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:37:48.838  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.846  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:37:48.851  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:37:48.853  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 08:37:48.863  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:37:48.868  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 08:37:48.878  7019  7498 W FormManager: Network not available. Please check & try again.
,08-29 08:37:48.880  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:37:48.891  7019  7499 V FormManager: Network unavailable.
,08-29 08:37:48.895  7019  7499 V FormManager: Network unavailable.
08-29 08:37:48.900  2081  2081 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-29 08:37:48.917  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:37:48.918  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:48.919  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 08:37:48.922  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:48.928  4325  7500 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 08:37:48.936  6949  6949 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 08:37:48.936  6949  6949 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 08:37:48.936  6949  6949 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:37:48.941  4325  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:37:48.941  4325  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:48.944  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 08:37:48.954  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 08:37:48.955  7019  7508 W FormManager: Network not available. Please check & try again.
08-29 08:37:48.960  7019  7509 V FormManager: Network unavailable.
08-29 08:37:48.968  7019  7509 V FormManager: Network unavailable.
,08-29 08:37:49.376  1034  1389 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-721113153] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 08:37:49.378  1034  1389 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-721113150] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 08:37:49.619  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:49.632  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 08:37:49.642  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:49.646  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:49.650  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 08:37:49.652  6543  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 08:37:49.652  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:49.663  5822  5822 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 08:37:49.683  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:49.728  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 08:37:49.733  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 08:37:49.733  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:49.733  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 08:37:49.733  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 08:37:49.735  7127  7127 I AppUp4:CustModeStarterReceiver: onReceive
08-29 08:37:49.739  7127  7127 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e343b70
08-29 08:37:49.739  7127  7127 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 08:37:49.739  7127  7127 D AppUp4:CustFacade: isPhone : true
08-29 08:37:49.740  7127  7127 D AppUp4:CustModeStarterReceiver: begin check event
08-29 08:37:49.740  7127  7127 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-29 08:37:49.748  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:49.748  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:49.750  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:49.752  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 08:37:49.763  7165  7165 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 08:37:49.794  4325  7539 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 08:37:49.804  7019  7530 W FormManager: Network not available. Please check & try again.
08-29 08:37:49.806  4325  7542 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:49.806  4325  7542 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 08:37:49.809  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 08:37:49.809  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:49.810  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 08:37:49.810  3444  3444 D PhoneState: setPdpRejectCasuse : false
08-29 08:37:49.812  7165  7540 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:49.817  7019  7531 V FormManager: Network unavailable.
08-29 08:37:49.821  7207  7207 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 08:37:49.821  7207  7207 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 08:37:49.824  7019  7531 V FormManager: Network unavailable.
,08-29 08:37:49.835  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:49
,08-29 08:37:49.838  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 08:37:49.838  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 08:37:49.838  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 08:37:49.838  7268  7268 D WeatherAncestor: connectivity changed - connection : true
,08-29 08:37:49.838  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fe9d76e
08-29 08:37:49.839  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 08:37:49.839  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 08:37:49.839  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 08:37:49.839  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 08:37:49.840  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:49
08-29 08:37:50.459  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:50.460  1034  1976 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 08:37:50.485  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:50.485  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:37:50.485  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-29 08:37:50.488  1034  1116 D BluetoothManagerService: Message: 1
,08-29 08:37:50.488  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 08:37:50.519  1034  1116 D BluetoothManagerService: Message: 20
08-29 08:37:50.519  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@396a8fee:true
,08-29 08:37:50.522  7049  7049 D BluetoothAdapterState: make
08-29 08:37:50.527  7049  7049 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 08:37:50.527  7049  7049 I bluedroid-qcom: init
08-29 08:37:50.531  7049  7558 I BluetoothAdapterState: Entering OffState
,08-29 08:37:50.533  7049  7049 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 08:37:50.533  7049  7049 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 08:37:50.533  7049  7049 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:37:50.533  7049  7049 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 08:37:50.533  7049  7049 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 08:37:50.535  7049  7049 I bluedroid-qcom: get_profile_interface socket
08-29 08:37:50.535  7049  7049 I bluedroid-qcom: get_profile_interface map_client
08-29 08:37:50.537  7049  7562 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 08:37:50.539  7049  7562 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 08:37:50.527  7561  7561 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:50.527  7561  7561 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:37:50.554  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 08:37:50.554  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 08:37:50.558  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 08:37:50.558  1034  1116 D BluetoothManagerService: Message: 40
08-29 08:37:50.558  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 08:37:50.559  7049  7066 I bluedroid-qcom: config_hci_snoop_log
08-29 08:37:50.560  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 08:37:50.560  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 08:37:50.562  7561  7561 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 08:37:50.562  7561  7561 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 08:37:50.563  7561  7561 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 08:37:50.566  7561  7561 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-29 08:37:50.569  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.573  7561  7561 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 08:37:50.573  7561  7561 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 08:37:50.584  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:50.588  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:50.588  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.593  7049  7558 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 08:37:50.594  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 08:37:50.600  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,08-29 08:37:50.604  7049  7562 D BluetoothAdapterProperties: Name is: G3
08-29 08:37:50.604  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.605  7049  7558 D BluetoothAdapterProperties: Setting state to 11
08-29 08:37:50.605  7049  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 08:37:50.606  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:50.606  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 08:37:50.606  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 08:37:50.607  7049  7558 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 08:37:50.624  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 08:37:50.626  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:50.628  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:50.628  6543  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 08:37:50.637  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 08:37:50.640  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:50.642  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 08:37:50.643  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:50.644  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:50.647  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.648  7049  7558 D BluetoothBondStateMachine: make
08-29 08:37:50.652  7049  7049 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-29 08:37:50.653  7049  7049 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:50.653  7049  7049 V BluetoothPbapReceiver: ***********state = 11
08-29 08:37:50.654  7049  7558 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:50.654  7049  7558 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 08:37:50.654  7049  7558 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:50.654  7049  7558 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 08:37:50.655  7049  7578 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 08:37:50.655  7049  7558 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 08:37:50.655  5822  5822 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 08:37:50.660  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:50.668  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.700  1034  1699 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7580 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 08:37:50.708  5822  5822 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 08:37:50.709  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:50.710  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:37:50.711  7049  7049 D HeadsetService: Received start request. Starting profile...
08-29 08:37:50.711  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.712  7049  7049 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:37:50.712  7049  7049 D LGBluetoothHfpAdapter: Version 1.6
,08-29 08:37:50.715  7049  7049 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 08:37:50.717  7049  7049 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:37:50.717  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.718  7049  7049 D HeadsetStateMachine: make
08-29 08:37:50.725  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:50.734  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.737  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 08:37:50.737  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.737  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-29 08:37:50.737  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 08:37:50.740  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.741  7127  7127 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 08:37:50.745  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.749  7049  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:50.749  7127  7127 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e343b70
08-29 08:37:50.749  7127  7127 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 08:37:50.750  7127  7127 D AppUp4:CustFacade: isPhone : true
08-29 08:37:50.750  7127  7127 D AppUp4:CustModeStarterReceiver: begin check event
08-29 08:37:50.750  7127  7127 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 08:37:50.750  7049  7049 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:50.751  7049  7049 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 08:37:50.753  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.753  1034  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e866520 type 2 when 127465 com.google.android.gms} when 127465
,08-29 08:37:50.753  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:50.754  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:50.755  7049  7049 D HeadsetStateMachine: max_hf_connections = 1
08-29 08:37:50.755  7049  7049 I bluedroid-qcom: get_profile_interface handsfree
08-29 08:37:50.756  7049  7049 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 08:37:50.757   315  2157 V AudioPolicyService: registerClient() client 0xb558af80, uid 1002
08-29 08:37:50.757   315  1400 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 08:37:50.757   315  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 08:37:50.757   315  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 08:37:50.757  7049  7049 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 08:37:50.758   315   315 V AudioFlinger: registerClient() client 0xb102bb98, pid 7049
08-29 08:37:50.758   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:50.758   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:50.758  7049  7064 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:50.758  7049  7049 V ToneGenerator: Create Track: 0xb4928a80
08-29 08:37:50.758  7049  7064 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 08:37:50.758  1034  1699 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:50.758  7049  7049 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 08:37:50.758  1034  1699 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:50.758  7049  7049 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 08:37:50.758  1602  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:50.758   315  1400 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 08:37:50.758  1602  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:50.758   315  1400 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 08:37:50.758   315  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 08:37:50.758   315  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 08:37:50.758  1852  3945 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:50.758  1852  3945 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:50.759  3444  3463 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:50.759  3444  3463 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-29 08:37:50.759   315  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:50.759   315  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:50.759   315   315 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 08:37:50.759  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:50.759  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:50.759  7049  7066 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:50.759  7049  7066 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 08:37:50.759   315  1400 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 08:37:50.759   315  1400 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 08:37:50.759   315  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 08:37:50.759   315  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 08:37:50.759  7049  7049 V AudioSystem: getLatency() output 2, latency 50
08-29 08:37:50.759  7049  7049 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 08:37:50.759  7049  7049 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 08:37:50.759  1034  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:50.759  1034  1050 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:50.759  1602  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:50.759  1602  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:50.759  3444  3963 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:50.759  3444  3963 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:50.760   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 08:37:50.760   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 08:37:50.760   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 08:37:50.760   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 08:37:50.760   315   315 V AudioFlinger: createTrack() lSessionId: 20
08-29 08:37:50.760  7049  7049 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 08:37:50.760  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:50.760   315  1400 V AudioFlinger: acquiring 20 from 7049, for 7049
08-29 08:37:50.760   315  1400 V AudioFlinger:  added new entry for 20
08-29 08:37:50.761  7049  7049 V ToneGenerator: ToneGenerator INIT OK, time: 127488
08-29 08:37:50.761  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:50.761  7049  7596 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 08:37:50.761  7049  7596 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 08:37:50.761  7049  7596 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 08:37:50.761  7049  7596 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 08:37:50.762   315  1399 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7049
08-29 08:37:50.762   315  1399 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 08:37:50.762   315  1399 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 08:37:50.762   315  1399 V compress_voip: voi,ce_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 08:37:50.762   315  1399 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 08:37:50.762   315  1399 V voice   : voice_set_parameters: exit with code(0)
08-29 08:37:50.762   315  1399 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 08:37:50.762   315  1399 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 08:37:50.762   315  1399 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 08:37:50.762   315  1399 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 08:37:50.762   315  1399 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 08:37:50.762   315  1399 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 08:37:50.762  7049  7596 V ToneGenerator: ToneGenerator destructor
08-29 08:37:50.762  7049  7596 V ToneGenerator: stopTone
08-29 08:37:50.762  7049  7596 V ToneGenerator: Delete Track: 0xb4928a80
08-29 08:37:50.763  7049  7596 V AudioTrack: ~AudioTrack, releasing session id from 7049 on behalf of 7049
08-29 08:37:50.763   315   315 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 08:37:50.763   315   315 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 08:37:50.763   315  2157 V AudioFlinger: releasing 20 from 7049 for 7049
08-29 08:37:50.763   315  2157 V AudioFlinger:  decremented refcount to 0
08-29 08:37:50.763   315  1272 V AudioPolicyService: AudioCommandThread() waking up
08-29 08:37:50.763   315  2157 V AudioFlinger: purging stale effects
08-29 08:37:50.763   315  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 08:37:50.763   315  1272 V AudioPolicyManager: releaseOutput() 2
08-29 08:37:50.763   315  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 08:37:50.763   315   315 V AudioFlinger: PlaybackThread::Track destructor
08-29 08:37:50.763   315   315 V AudioFlinger: removeClient_l() pid 7049, calling pid 315
08-29 08:37:50.764  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:50.766  7049  7049 D A2dpService: Received start request. Starting profile...
08-29 08:37:50.766  7049  7049 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:37:50.767  7165  7165 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 08:37:50.767  7049  7049 V Avrcp   : make
08-29 08:37:50.767  7049  7049 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 08:37:50.767  7049  7049 I bluedroid-qcom: get_profile_interface avrcp
,08-29 08:37:50.773  1034  1575 W Process : Unable to open /proc/7599/status
08-29 08:37:50.774  4325  7600 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 08:37:50.775  4325  7602 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.775  4325  7602 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:50.777  7049  7049 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 08:37:50.777  7049  7558 V LGMDMManager: Create singleton instance
08-29 08:37:50.778  7049  7049 E AudioManager: No RCC entry present to update
08-29 08:37:50.778  7049  7049 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 08:37:50.779  7049  7558 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 08:37:50.781  7049  7049 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 08:37:50.782  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 08:37:50.782  7049  7049 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-29 08:37:50.787  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 08:37:50.789  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 08:37:50.789  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.790  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 08:37:50.827  7207  7207 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 08:37:50.827  7207  7207 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 08:37:50.832  7580  7580 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 08:37:50.832  7580  7580 W LG Account v2.2: No ProfileInfo entries
08-29 08:37:50.832  7580  7580 I LG Account v2.2: isEnabled: false
08-29 08:37:50.832  7165  7606 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:50.832  7580  7580 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 08:37:50.832  7580  7580 I Feature : [Lifetracker]Country: EU
08-29 08:37:50.832  7580  7580 I Feature : [Lifetracker]Operator: OPEN
08-29 08:37:50.832  7580  7580 I Feature : [Lifetracker]Ranking support: false
08-29 08:37:50.834  7580  7580 I Feature : [Lifetracker]Comfort support: false
08-29 08:37:50.834  7580  7580 I Feature : [Lifetracker]Accessory: true
08-29 08:37:50.834  7580  7580 I Feature : [Lifetracker]Health device: true
08-29 08:37:50.834  7580  7580 I Feature : [Lifetracker]Extra Pedometer: false
08-29 08:37:50.834  7580  7580 I Feature : [Lifetracker]Blood glucose device: false
08-29 08:37:50.834  7580  7580 I Feature : [Lifetracker]Device Number: 3
08-29 08:37:50.835  7019  7607 W FormManager: Network not available. Please check & try again.
08-29 08:37:50.841  7019  7608 V FormManager: Network unavailable.
,08-29 08:37:50.848  6927  6927 D BluetoothPermissionRequest: onReceive
08-29 08:37:50.848  7019  7608 V FormManager: Network unavailable.
08-29 08:37:50.854  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 08:37:50.862  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:50
,08-29 08:37:50.866  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 08:37:50.866  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 08:37:50.866  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 08:37:50.866  7268  7268 D WeatherAncestor: connectivity changed - connection : true
,08-29 08:37:50.866  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fe9d76e
08-29 08:37:50.867  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 08:37:50.867  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 08:37:50.867  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 08:37:50.867  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-29 08:37:50.868  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:50
08-29 08:37:50.875  1034  1994 V SIM_STK : Menu title from STK is T-Mobile
08-29 08:37:50.875  1034  1994 V SIM_STK : Menu title from STK is T-Mobile
,08-29 08:37:50.893  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 08:37:50.899  6543  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 08:37:50.911  2081  2081 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:50.926  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 08:37:50.926  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:50.926  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 08:37:50.926  7127  7127 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 08:37:50.929  7127  7127 I AppUp4:CustModeStarterReceiver: onReceive
08-29 08:37:50.932  7127  7127 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e343b70
08-29 08:37:50.932  7127  7127 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 08:37:50.932  7127  7127 D AppUp4:CustFacade: isPhone : true
08-29 08:37:50.933  7127  7127 D AppUp4:CustModeStarterReceiver: begin check event
08-29 08:37:50.933  7127  7127 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 08:37:50.936  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.936  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:37:50.938  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 08:37:50.941  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:37:50.949  4325  7612 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.949  4325  7612 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:37:50.949  7165  7165 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 08:37:50.950  4325  7611 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 08:37:50.969  7165  7613 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:37:50.977  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 08:37:50.977  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 08:37:50.977  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 08:37:50.980  7207  7207 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 08:37:50.980  7207  7207 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 08:37:50.986  1034  1995 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 08:37:50.987  7019  7615 W FormManager: Network not available. Please check & try again.
08-29 08:37:50.993  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 08:37:50.995  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:50
08-29 08:37:50.997  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 08:37:50.998  7019  7617 V FormManager: Network unavailable.
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 08:37:50.998  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 08:37:50.999  7049  7049 I BluetoothA2dpServiceJni: classInitNative
,08-29 08:37:50.999  7049  7049 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:37:50.999  7049  7049 D A2dpStateMachine: make
08-29 08:37:51.000  7019  7617 V FormManager: Network unavailable.
08-29 08:37:51.000  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 08:37:51.000  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 08:37:51.001  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 08:37:51.001  7049  7049 I bluedroid-qcom: get_profile_interface a2dp
08-29 08:37:51.001  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 08:37:51.001  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fe9d76e
08-29 08:37:51.001  7049  7619 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 08:37:51.001  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 08:37:51.001  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 08:37:51.001  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 08:37:51.001  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 08:37:51.002  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:37:51
08-29 08:37:51.004  7049  7049 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:37:51.004  7049  7049 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 08:37:51.005  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:51.006  7049  7049 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 08:37:51.008  7049  7049 D HidService: Received start request. Starting profile...
08-29 08:37:51.008  7049  7049 I bluedroid-qcom: get_profile_interface hidhost
08-29 08:37:51.008  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:51.009  7049  7049 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:37:51.011  7049  7618 D A2dpStateMachine: Enter Disconnected: -2
08-29 08:37:51.012  7049  7049 D HealthService: Received start request. Starting profile...
08-29 08:37:51.013  7049  7049 I bluedroid-qcom: get_profile_interface health
08-29 08:37:51.013  7049  7049 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:37:51.013  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:51.014  7049  7049 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 08:37:51.015  7049  7049 D PanService: Received start request. Starting profile...
08-29 08:37:51.015  7049  7049 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:37:51.015  7049  7049 I bluedroid-qcom: get_profile_interface pan
08-29 08:37:51.021  7049  7049 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 08:37:51.021  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
,08-29 08:37:51.022  7049  7049 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 08:37:51.028  7049  7049 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:37:51.028   311  7626 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 08:37:51.028  7049  7049 D BtGatt.GattService: Received start request. Starting profile...
08-29 08:37:51.029  7049  7049 D BtGatt.GattService: start()
08-29 08:37:51.029  7049  7049 I bluedroid-qcom: get_profile_interface gatt
08-29 08:37:51.029  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 08:37:51.029  7049  7049 D BtGatt.AdvertiseManager: advertise manager created
08-29 08:37:51.031  6978  6978 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-29 08:37:51.031  6978  6978 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3462
,08-29 08:37:51.038  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
,08-29 08:37:51.038  7049  7049 D HeadsetStateMachine: Proxy object connected
08-29 08:37:51.039  7049  7049 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 08:37:51.039  7049  7049 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 08:37:51.041  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:51.041  7049  7049 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 08:37:51.042  7049  7049 V BluetoothMapService: BluetoothMapBinder()
08-29 08:37:51.043  7049  7049 D BluetoothMapService: Received start request. Starting profile...
08-29 08:37:51.043  7049  7049 D BluetoothMapService: start()
08-29 08:37:51.046  7049  7049 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 08:37:51.046  7049  7049 D BluetoothMapEmailAppObserver: createReceiver()
08-29 08:37:51.047  7049  7049 D BluetoothMapEmailAppObserver: initObservers()
08-29 08:37:51.047  7049  7049 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-29 08:37:51.056  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
,08-29 08:37:51.059  7049  7049 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 08:37:51.060  7049  7596 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-29 08:37:51.060  7049  7596 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:37:51.060  7049  7596 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 08:37:51.063  7049  7049 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 08:37:51.065  7049  7049 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 08:37:51.067  7049  7049 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 08:37:51.068  7049  7049 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 08:37:51.070  7049  7049 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 08:37:51.072  7049  7049 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 08:37:51.072  7049  7049 V BluetoothMapService: Handler(): got msg=1
08-29 08:37:51.073  7049  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 08:37:51.074  7049  7558 I bluedroid-qcom: enable
,08-29 08:37:51.075  7049  7558 I bt_hci_bdroid: init
08-29 08:37:51.075  7049  7049 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:51.075  7049  7629 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 08:37:51.075  7049  7629 I bt-btu  : btu_task pending for preload complete event
08-29 08:37:51.077  7049  7049 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:37:51.078  7049  7049 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:37:51.078  7049  7049 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:37:51.078  7049  7558 I bt_vendor: bt-vendor : init
08-29 08:37:51.078  7049  7049 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:51.078  7049  7558 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 08:37:51.078  7049  7049 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 08:37:51.078  7049  7558 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 08:37:51.078  7049  7558 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 08:37:51.078  7049  7558 D bt_userial_mct: userial_init
08-29 08:37:51.079  7049  7558 D bt_hci_bdroid: set_power 1
08-29 08:37:51.079  7049  7558 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 08:37:51.079  7049  7558 I bt_vendor: Starting hciattach daemon
08-29 08:37:51.079  7049  7558 I bt_vendor: try to set true
08-29 08:37:51.067  7632  7632 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:51.077  7632  7632 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:51.114  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 08:37:51.213  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 08:37:51.228  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 08:37:51.267  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 08:37:51.282  7646  7646 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 08:37:51.298  7647  7647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 08:37:51.312  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 08:37:51.348  7650  7650 I libmdmdetect: ESOC framework not supported
08-29 08:37:51.349  7650  7650 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 08:37:51.357  7650  7650 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 08:37:51.357  7650  7650 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-29 08:37:51.357  7650  7650 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 08:37:51.357  7650  7650 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 08:37:51.357  7650  7650 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 08:37:51.357  7650  7650 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 08:37:51.357  7650  7650 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 08:37:51.399  7650  7651 E QC-QMI  : qmi_client [7650] 14: failed to locate client data
08-29 08:37:51.403   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 08:37:51.403   471   471 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-29 08:37:51.469  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 08:37:51.497  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 08:37:51.531  7049  7558 I bt_vendor: bluetooth satus is on
08-29 08:37:51.531  7049  7558 D bt_hci_bdroid: preload
08-29 08:37:51.531  7049  7631 D bt_userial_mct: userial_open(port:0)
08-29 08:37:51.531  7049  7631 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 08:37:51.535  7049  7631 I bt_vendor: Done intiailizing UART
08-29 08:37:51.540  7049  7631 I bt_vendor: Done intiailizing UART
08-29 08:37:51.540  7049  7631 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 08:37:51.540  7049  7631 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 08:37:51.540  7049  7655 D bt_userial_mct: Entering userial_read_thread()
08-29 08:37:51.541  7049  7629 I bt-btu  : btu_task received preload complete event
08-29 08:37:51.541  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 08:37:51.541  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 08:37:51.543  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:37:51.548  7049  7629 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 08:37:51.650  7049  7629 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 08:37:51.650  7049  7629 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d8061 
08-29 08:37:51.650  7049  7629 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d8061 
,08-29 08:37:51.668  7049  7562 E bt-btif : Calling BTA_HhEnable
,08-29 08:37:51.668  7049  7562 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 08:37:51.668  7049  7562 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 08:37:51.672  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 08:37:51.673  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 08:37:51.673  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 08:37:51.675  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 08:37:51.675  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 08:37:51.675  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 08:37:51.676  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 08:37:51.676  7049  7562 D BluetoothAdapterProperties: Name is: G3
08-29 08:37:51.677  7049  7562 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:37:51.677  7049  7562 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:37:51.678  7049  7562 D bt_hci_bdroid: postload
08-29 08:37:51.678  7049  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:37:51.678  7049  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:37:51.679  7049  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 08:37:51.679  7049  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:37:51.679  7049  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:37:51.680  7049  7562 D bte_conf: Device ID record 1 : primary
08-29 08:37:51.680  7049  7562 D bte_conf:   vendorId            = 00c4
08-29 08:37:51.680  7049  7562 D bte_conf:   vendorIdSource      = 0001
08-29 08:37:51.680  7049  7562 D bte_conf:   product             = 13a1
08-29 08:37:51.680  7049  7562 D bte_conf:   version             = 1000
08-29 08:37:51.680  7049  7562 D bte_conf:   clientExecutableURL = 
08-29 08:37:51.680  7049  7562 D bte_conf:   serviceDescription  = 
08-29 08:37:51.680  7049  7562 D bte_conf:   documentationURL    = 
08-29 08:37:51.680  7049  7562 D bte_conf: bte_load_did_conf no section named DID2.
08-29 08:37:51.677  7663  7663 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:37:51.689  7049  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:37:51.689  7049  7629 W bt-smp  : Plain text(LSB ~ MSB) = 7f 28 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:37:51.689  7049  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 31 0f e1 2c 92 af 63 0b b3 0e 0e 63 28 63 d9 
08-29 08:37:51.689  7049  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:37:51.690  7049  7629 W bt-btm  : Stopping oneshot timer
08-29 08:37:51.690  7049  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 08:37:51.690  7049  7558 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:37:51.690  7049  7558 D BluetoothAdapterProperties: State =  11
08-29 08:37:51.690  7049  7558 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 08:37:51.691  7049  7558 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 08:37:51.691  7049  7558 D BluetoothAdapterProperties: Setting state to 12
08-29 08:37:51.691  7049  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 08:37:51.691  7049  7562 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 08:37:51.692  7049  7562 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 08:37:51.693  7049  7655 E bt_mct  : hci lib postload completed
08-29 08:37:51.687  7663  7663 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:51.699  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:51.699  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 08:37:51.699  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-29 08:37:51.719  1852  2454 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:37:51.722  7049  7558 I BluetoothAdapterState: Entering On State
08-29 08:37:51.733  7049  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:37:51.733  7049  7629 W bt-smp  : Plain text(LSB ~ MSB) = b4 37 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:37:51.733  7049  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 81 4d 29 23 14 e1 dd 29 de e8 ee 3d 20 2b c0 
,08-29 08:37:51.735  7049  7629 W bt-btm  : Stopping oneshot timer
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:51.738  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:51.740  7049  7562 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:37:51.741  7049  7562 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 08:37:51.746  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:37:51.749  7049  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:37:51.749  7049  7629 W bt-smp  : Plain text(LSB ~ MSB) = 6d e5 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:37:51.749  7049  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f c0 4f 33 84 28 66 9e e2 af 33 ff b7 61 df 7c 
08-29 08:37:51.749  7049  7629 W bt-btm  : Stopping oneshot timer
08-29 08:37:51.762  7049  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:37:51.762  7049  7629 W bt-smp  : Plain text(LSB ~ MSB) = 79 7e 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:37:51.762  7049  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 7c 86 31 b5 3f 9b 3d e9 19 ba 00 3f 7a d8 fd ae 
,08-29 08:37:51.765  7049  7629 W bt-btm  : Stopping oneshot timer
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:51.769  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:51.784  7049  7558 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 08:37:51.784  7049  7558 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 08:37:51.784  7049  7558 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 08:37:51.788  7049  7558 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 08:37:51.788  7049  7558 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 08:37:51.791  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 08:37:51.791  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:51.792  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:37:51.795  7049  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:37:51.795  7049  7629 W bt-smp  : Plain text(LSB ~ MSB) = c3 e8 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:37:51.795  7049  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f 11 f1 dc 64 a2 6e 8c e5 39 10 29 cd 1a 9b 19 
08-29 08:37:51.795  7049  7629 W bt-btm  : Stopping oneshot timer
08-29 08:37:51.803  1852  1852 D BluetoothHeadset: Proxy object connected
,08-29 08:37:51.806  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:37:51.808  1034  1034 D BluetoothHeadset: Proxy object connected
08-29 08:37:51.829  6927  6944 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 08:37:51.835  7677  7677 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 08:37:51.839  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:37:51.844  6927  6927 D BluetoothInputDevice: Proxy object connected
08-29 08:37:51.844  6927  6927 D HidProfile: Bluetooth service connected
,08-29 08:37:51.846  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 08:37:51.850  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:37:51.851  6927  6945 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:37:51.852  1034  1034 D BluetoothA2dp: Proxy object connected
08-29 08:37:51.853  6927  6944 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:37:51.853  6927  6944 D BluetoothPan: onBluetoothStateChange call bindService
08-29 08:37:51.855  6927  7681 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:37:51.859  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 08:37:51.859  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 08:37:51.859  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-29 08:37:51.861  7292  7337 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-29 08:37:51.864  1034  1116 D BluetoothManagerService: Message: 40
08-29 08:37:51.864  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-29 08:37:51.866  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:51.866  1941  2099 D LGBluetoothAPIService: Message: 1
08-29 08:37:51.866  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:37:51.866  1941  2099 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 08:37:51.879  7049  7049 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:51.879  7049  7049 D BluetoothMapService: STATE_ON
08-29 08:37:51.879  6741  6741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 08:37:51.879  1941  2099 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-29 08:37:51.881  7049  7049 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 08:37:51.881  7049  7049 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 08:37:51.883  6927  6927 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:37:51.883  6927  6927 D PanProfile: Bluetooth service connected
08-29 08:37:51.884  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-29 08:37:51.884  1941  2099 D LGBluetoothAPIService: Message: 100
08-29 08:37:51.884  1941  2099 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 08:37:51.885  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:51.886  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:51.892  6927  6927 D BluetoothMap: Proxy object connected
08-29 08:37:51.892  6927  6927 D MapProfile: Bluetooth service connected
08-29 08:37:51.892  6927  6927 D BluetoothMap: getConnectedDevices()
08-29 08:37:51.894  7049  7064 V BluetoothMapService: getConnectedDevices()
,08-29 08:37:51.896  6927  6927 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 08:37:51.899  1034  1116 D BluetoothManagerService: Message: 30
08-29 08:37:51.901  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:51.901  7049  7049 V BluetoothPbapService: Pbap Service onCreate
08-29 08:37:51.901  7049  7049 V BluetoothPbapService: Starting PBAP service
08-29 08:37:51.901  6927  6927 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 08:37:51.902  7049  7049 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 08:37:51.903  7049  7049 V BluetoothMapService: Handler(): got msg=1
08-29 08:37:51.903  7049  7049 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 08:37:51.904  7049  7049 V BluetoothPbapService: Pbap Service onBind
08-29 08:37:51.904  1034  1116 D BluetoothManagerService: Message: 30
08-29 08:37:51.905  7049  7691 D BluetoothMapMasInstance: MAS initSocket()
08-29 08:37:51.905  7049  7049 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:51.905  7049  7049 V BluetoothPbapService: state: 12
08-29 08:37:51.905  7049  7049 V BluetoothPbapService: Handler(): got msg=1
,08-29 08:37:51.906  7049  7049 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-29 08:37:51.907  7049  7692 V BluetoothPbapService: Pbap Service initSocket
,08-29 08:37:51.909  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:51.909  7049  7691 D BluetoothMapMasInstance:   masId = 00
08-29 08:37:51.909  7049  7691 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 08:37:51.909  7049  7691 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 08:37:51.909  7049  7691 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 08:37:51.909  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:51.911  7049  7692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:51.912  7049  7691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:51.912  7049  7692 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 08:37:51.912  7049  7691 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-29 08:37:51.913  7049  7691 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 08:37:51.913  7049  7691 D BluetoothMapMasInstance: Accepting socket connection...
08-29 08:37:51.913  7049  7692 V BluetoothPbapService: Succeed to create listening socket 
08-29 08:37:51.913  7049  7692 V BluetoothPbapService: Accepting socket connection...
08-29 08:37:51.914  7049  7562 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:37:51.914  7049  7562 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 08:37:51.915  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 08:37:51.917  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 08:37:51.918  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:51.919  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:51.923  6927  6927 D BluetoothA2dp: Proxy object connected
08-29 08:37:51.923  7049  7049 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 08:37:51.923  6927  6927 D A2dpProfile: Bluetooth service connected
08-29 08:37:51.923  7049  7049 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:51.923  7049  7049 V BluetoothPbapReceiver: ***********state = 12
08-29 08:37:51.925  6927  6927 D BluetoothPbap: Proxy object connected
08-29 08:37:51.926  6927  6927 D PbapServerProfile: Bluetooth service connected
,08-29 08:37:51.926  6927  6927 D BluetoothHeadset: Proxy object connected
08-29 08:37:51.926  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:37:51.927  6927  6927 D HeadsetProfile: Bluetooth service connected
08-29 08:37:51.927  2081  2081 D c       : Getting all permits...
08-29 08:37:51.927  2081  2081 D a       : Opening database...
08-29 08:37:51.931  2081  2081 D a       : Opening database auth.proximity.permit_store...
08-29 08:37:51.932  2081  2081 D a       : Closing database...
,08-29 08:37:51.941  6927  6927 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:51.946  6927  6927 D BluetoothPermissionRequest: onReceive
,08-29 08:37:51.948  6927  6927 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 08:37:51.950  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 08:37:51.953  7049  7049 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 08:37:51.955  7049  7049 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 08:37:51.961  7049  7049 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 08:37:51.986  7049  7049 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 08:37:51.986  7049  7049 V BtOppService: onCreate
,08-29 08:37:51.991  7049  7049 V BluetoothOppNotification: send message
08-29 08:37:51.995  7049  7049 V BtOppService: Starting RfcommListener
08-29 08:37:52.003  7049  7049 D BluetoothOppPreference: Dumping Names:  
08-29 08:37:52.003  7049  7049 D BluetoothOppPreference: {}
08-29 08:37:52.004  7049  7049 D BluetoothOppPreference: Dumping Channels:  
08-29 08:37:52.004  7049  7049 D BluetoothOppPreference: {}
08-29 08:37:52.005  7049  7049 V BtOppService: onStartCommand
,08-29 08:37:52.008  7049  7049 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:52.008  7049  7049 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 08:37:52.012  7049  7699 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 08:37:52.013  7049  7049 V BluetoothOppNotification: new notify threadi!
08-29 08:37:52.014  7049  7049 V BluetoothOppNotification: send delay message
,08-29 08:37:52.014  7049  7049 V BtOppService: start RfcommListener
08-29 08:37:52.017  7049  7049 V BtOppService: RfcommListener started
08-29 08:37:52.018  7049  7701 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 08:37:52.019  1034  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:52.020  7049  7701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:37:52.021  7049  7701 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 08:37:52.021  7049  7701 V BtOppRfcommListener: Started RFCOMM listener....
08-29 08:37:52.021  7049  7701 I BtOppRfcommListener: Accept thread started.
08-29 08:37:52.022  7049  7701 V BtOppRfcommListener: Accepting connection...
08-29 08:37:52.024  7049  7699 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 08:37:52.025  7049  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 08:37:52.025  7049  7696 V BtOppService: Deleted complete outbound shares, number =  0
08-29 08:37:52.027  7049  7699 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f8ecdfb on behalf of 
08-29 08:37:52.032  7049  7696 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-29 08:37:52.033  7049  7696 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 08:37:52.033  7049  7699 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 08:37:52.035  7049  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2db25e18 on behalf of 
,08-29 08:37:52.035  7049  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c2d9071 on behalf of 
08-29 08:37:52.039  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:52.039  7049  7049 V BluetoothFtpService: Ftp Service onCreate
08-29 08:37:52.039  7049  7049 I BluetoothFtpService: Ftp Service onCreate
08-29 08:37:52.040  7049  7049 V BluetoothFtpService: Ftp Service onStartCommand
08-29 08:37:52.040  7049  7049 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:52.040  7049  7700 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 08:37:52.040  7049  7049 V BluetoothFtpService: Starting Listening on sockets
08-29 08:37:52.041  7049  7049 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:37:52.041  7049  7049 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:37:52.041  7049  7049 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:37:52.041  7049  7049 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:52.041  7049  7049 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 08:37:52.042  7049  7049 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 08:37:52.042  7049  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 08:37:52.044  7049  7049 V BtOppService: ContentObserver received notification
08-29 08:37:52.044  7049  7049 V BtOppService: ContentObserver received notification
08-29 08:37:52.045  7049  7049 V BluetoothFtpService: Handler(): got msg=1
08-29 08:37:52.045  7049  7702 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 08:37:52.046  7049  7702 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-29 08:37:52.046  7049  7049 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 08:37:52.046  7049  7049 V BluetoothFtpService: Ftp Service initSocket
08-29 08:37:52.048  7049  7702 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24f24ed7 on behalf of 
08-29 08:37:52.048  7049  7702 V BluetoothOppNotification: update too frequent, put in queue
08-29 08:37:52.049  7049  7702 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 08:37:52.053  7049  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@207b43c4 on behalf of 
08-29 08:37:52.054  7049  7700 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 08:37:52.055  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:52.056  7049  7700 V BluetoothOppNotification: outbound notification was removed.
08-29 08:37:52.056  7049  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 08:37:52.057  7049  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10b9c2ad on behalf of 
08-29 08:37:52.057  7049  7049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:52.058  7049  7700 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 08:37:52.059  7049  7049 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
,08-29 08:37:52.059  7049  7049 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 08:37:52.060  7049  7700 V BluetoothOppNotification: inbound notification was removed.
08-29 08:37:52.060  7049  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 08:37:52.061  7049  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3736c9e2 on behalf of 
08-29 08:37:52.062  7049  7703 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 08:37:52.077  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:52.077  7049  7049 V BluetoothSapService: Sap Service onCreate
,08-29 08:37:52.079  7049  7049 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:52.079  7049  7049 V BluetoothSapService: state: 12
08-29 08:37:52.079  7049  7049 V BluetoothSapService: Starting SAP server process
08-29 08:37:52.082  7049  7049 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 08:37:52.077  7704  7704 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:52.083  7049  7705 V BluetoothSapService: Sap Service initRfcommSocket
08-29 08:37:52.077  7704  7704 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:52.084  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:52.085  7049  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:52.086  7049  7705 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-29 08:37:52.086  7049  7705 V BluetoothSapService: Succeed to create listening socket 
08-29 08:37:52.086  7049  7705 V BluetoothSapService: Accepting socket connection...
08-29 08:37:52.100  7704  7704 V BT_SAP  : Event pipe created
08-29 08:37:52.100  7704  7704 V BT_SAP  : create_server_socket qcom.sap.server
08-29 08:37:52.100  7704  7704 V BT_SAP  : created socket fd 6
,08-29 08:37:52.516  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:37:52.521  1034  1388 D LGWifiP2pService: DefaultState{ when=-9ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:37:52.565  1034  1389 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 08:37:52.566  1034  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 08:37:52.797  1034  1049 I ActivityManager: Killing 7470:com.lge.bnr/1000 (adj 15): empty #17
,08-29 08:37:52.828  1034  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_7470/cgroup.procs: No such file or directory
,08-29 08:37:52.844  1034  2033 I ActivityManager: Killing 6949:com.lge.sync/1000 (adj 15): empty #17
,08-29 08:37:52.865  1034  1421 D WifiService: Client connection lost with reason: 4
,08-29 08:37:52.875  1034  1904 W libprocessgroup: failed to open /acct/uid_1000/pid_6949/cgroup.procs: No such file or directory
,08-29 08:37:53.016  7049  7049 V BluetoothOppNotification: new notify threadi!
,08-29 08:37:53.025  7049  7049 V BluetoothOppNotification: send delay message
08-29 08:37:53.029  7049  7715 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 08:37:53.034  7049  7715 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@67ba22e on behalf of 
08-29 08:37:53.037  7049  7715 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 08:37:53.039  7049  7715 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-29 08:37:53.040  7049  7715 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ba241cf on behalf of 
,08-29 08:37:53.041  7049  7715 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 08:37:53.043  7049  7715 V BluetoothOppNotification: outbound notification was removed.
,08-29 08:37:53.043  7049  7715 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-29 08:37:53.044  7049  7715 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@193d475c on behalf of 
,08-29 08:37:53.044  7049  7715 V BluetoothOppNotification: inbound: succ-0  fail-0,
08-29 08:37:53.046  7049  7715 V BluetoothOppNotification: inbound notification was removed.
,08-29 08:37:53.046  7049  7715 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 08:37:53.047  7049  7715 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37fd9a65 on behalf of 
,08-29 08:37:53.507  1034  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 08:37:53.507  1034  1905 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@bbcb24b mBinding = false
,08-29 08:37:53.545  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:53.545  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:37:53.545  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 08:37:53.546  1034  1116 D BluetoothManagerService: Message: 2
08-29 08:37:53.547  1034  1116 D BluetoothManagerService: Sending off request.
08-29 08:37:53.548  7049  7066 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 08:37:53.550  7049  7558 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 08:37:53.550  7049  7558 D BluetoothAdapterProperties: Setting state to 13
08-29 08:37:53.550  7049  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 08:37:53.551  7049  7558 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:37:53.551  7049  7558 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 08:37:53.554  7049  7562 D BluetoothAdapterProperties: Scan Mode:20
,08-29 08:37:53.558  7049  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 08:37:53.559  7049  7558 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 08:37:53.561  7049  7692 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 08:37:53.562  7049  7691 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 08:37:53.563  7049  7703 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:53.563  7049  7701 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:53.564  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 08:37:53.564  7049  7629 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 08:37:53.565  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 08:37:53.565  7049  7629 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 08:37:53.576  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:53.576  6741  6741 V io.jxcore.node.C,onnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:53.576  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:37:53.581  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:53.582  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:53.585  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:53.585  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:53.587  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:53.587  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:53.590  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:53.590  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 08:37:53.590  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-29 08:37:53.595  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.596  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:37:53.602  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:53.606  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:53.607  7049  7049 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.607  7049  7049 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:37:53.607  7049  7049 V BluetoothMapService: Handler(): got msg=4
08-29 08:37:53.607  7049  7049 D BluetoothMapService: MAP Service closeService in
08-29 08:37:53.607  7049  7049 D BluetoothMapMasInstance: MAP Service shutdown
08-29 08:37:53.608  7049  7049 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 08:37:53.608  7049  7049 V BluetoothMapService: MAP Service closeService out
08-29 08:37:53.609  7049  7049 V BtOppService: Receiver DISABLED_ACTION 
08-29 08:37:53.609  7049  7049 I BtOppRfcommListener: stopping Accept Thread
08-29 08:37:53.609  7049  7049 V BtOppRfcommListener: close mBtServerSocket
08-29 08:37:53.610  7049  7701 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:37:53.610  7049  7049 V BtOppRfcommListener: waiting for thread to terminate
08-29 08:37:53.610  7049  7049 V BtOppRfcommListener: done waiting for thread to terminate
08-29 08:37:53.614  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-29 08:37:53.623  7049  7705 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:53.628  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 08:37:53.633  7049  7049 V BtOppService: onDestroy
08-29 08:37:53.634  7049  7049 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 08:37:53.639  7049  7049 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 08:37:53.639  7049  7049 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.639  7049  7049 V BluetoothPbapReceiver: ***********state = 13
08-29 08:37:53.641  7049  7049 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-29 08:37:53.646  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:37:53.651  7049  7049 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.651  7049  7049 V BluetoothPbapService: state: 13
08-29 08:37:53.651  7049  7049 V BluetoothPbapService: Pbap Service closeService in
08-29 08:37:53.654  7049  7049 V BluetoothPbapService: successfully stopped pbap service
08-29 08:37:53.654  7049  7049 V BluetoothPbapService: Pbap Service closeService out
,08-29 08:37:53.657  7049  7049 V BluetoothPbapService: Pbap Service onDestroy
08-29 08:37:53.657  7049  7049 V BluetoothPbapService: Pbap Service closeService in
08-29 08:37:53.657  7049  7049 V BluetoothPbapService: Pbap Service closeService out
08-29 08:37:53.657  7049  7049 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 08:37:53.673  6927  6927 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:53.676  6927  6927 D BluetoothPbap: Proxy object disconnected
08-29 08:37:53.676  6927  6927 D PbapServerProfile: Bluetooth service disconnected
08-29 08:37:53.683  6927  6927 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 08:37:53.688  6927  6927 D BluetoothPermissionRequest: onReceive
08-29 08:37:53.688  6927  6927 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 08:37:53.694  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 08:37:53.698  7049  7049 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 08:37:53.698  7049  7049 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 08:37:53.699  7049  7049 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-29 08:37:53.704  7049  7049 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.704  7049  7049 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 08:37:53.705  7049  7049 V BluetoothFtpService: Ftp Service onStartCommand
08-29 08:37:53.705  7049  7049 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.705  7049  7049 V BluetoothFtpService: Ftp Service closeService
08-29 08:37:53.705  7049  7049 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 08:37:53.709  7049  7049 V BluetoothFtpService: successfully stopped ftp service
08-29 08:37:53.710  7049  7049 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:37:53.710  7049  7049 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:37:53.710  7049  7049 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:37:53.710  7049  7049 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:53.710  7049  7049 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 08:37:53.710  7049  7049 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 08:37:53.711  7049  7049 V BluetoothFtpService: Ftp Service onDestroy
08-29 08:37:53.711  7049  7049 V BluetoothFtpService: Ftp Service closeService
,08-29 08:37:53.716  7049  7049 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:53.716  7049  7049 V BluetoothSapService: state: 13
,08-29 08:37:53.716  7049  7049 V BluetoothSapService: Stopping SAP server process
,08-29 08:37:53.718  7049  7049 V BluetoothSapService: Sap Service closeSapService in
,08-29 08:37:53.718  7049  7049 V BluetoothSapService: Close listen Socket : ,
,08-29 08:37:53.718  7049  7049 V BluetoothSapService: Close rfcomm Socket : 
08-29 08:37:53.718  7049  7049 V BluetoothSapService: Close sapd  Socket : 
,08-29 08:37:53.719  7049  7049 V BluetoothSapService: Sap Service closeSapService out
08-29 08:37:53.720  7049  7049 V BluetoothSapService: Sap Service onDestroy
08-29 08:37:53.720  7049  7049 V BluetoothSapService: Sap Service closeSapService in
08-29 08:37:53.720  7049  7049 V BluetoothSapService: Close listen Socket : 
08-29 08:37:53.720  7049  7049 V BluetoothSapService: Close rfcomm Socket : 
08-29 08:37:53.720  7049  7049 V BluetoothSapService: Close sapd  Socket : 
,08-29 08:37:53.720  7049  7049 V BluetoothSapService: Sap Service closeSapService out,
08-29 08:37:54.553  7049  7562 D bt_hci_bdroid: cleanup
,08-29 08:37:54.574  7049  7655 I bt_userial_mct: exiting userial_read_thread
08-29 08:37:54.574  7049  7655 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 08:37:54.573  7049  7631 I bt_lpm  : LPM is already off!!!
08-29 08:37:54.576  7049  7629 W bt-btif : ag scb idx 1 not allocated
08-29 08:37:54.576  7049  7629 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019,
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 08:37:54.576  7049  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 08:37:54.576  7049  7629 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 08:37:54.577  7049  7562 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 08:37:54.577  7049  7631 I bt_vendor: hw_epilog_process
08-29 08:37:54.578  7049  7562 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 08:37:54.578  7049  7562 D bt_userial_mct: userial_close
,08-29 08:37:54.578  7049  7562 E bt_userial_mct: pthread_join() FAILED result:3
08-29 08:37:54.578  7049  7562 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 08:37:54.583  7049  7562 D bt_hci_bdroid: set_power 0
08-29 08:37:54.583  7049  7562 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 08:37:54.583  7049  7562 I bt_vendor: bluetooth satus is on,
08-29 08:37:54.583  7049  7562 I bt_vendor: bt-vendor : resetting BT status,
,08-29 08:37:54.583  7049  7562 I bt_vendor: Starting hciattach daemon
08-29 08:37:54.583  7049  7562 I bt_vendor: try to set false,
,08-29 08:37:54.593  7049  7562 I bt_vendor: Starting hciattach daemon,
08-29 08:37:54.593  7049  7562 I bt_vendor: try to set false
08-29 08:37:54.596  7049  7562 I bt_vendor: cleanup
08-29 08:37:54.597  7049  7629 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-29 08:37:54.598  7049  7562 I GKI_LINUX: GKI_exit_task 0 done
08-29 08:37:54.598  7049  7562 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
08-29 08:37:54.599  7049  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 08:37:54.608  7049  7049 D HeadsetService: Received stop request...Stopping profile...
08-29 08:37:54.611  7049  7049 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 08:37:54.611  7049  7049 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:37:54.612  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
,08-29 08:37:54.616  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:54.616  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:54.616  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:54.617  7049  7596 D HeadsetStateMachine: Exit Disconnected: -1
08-29 08:37:54.618  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:54.618  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 08:37:54.620  7049  7049 D A2dpService: Received stop request...Stopping profile...
08-29 08:37:54.622  7049  7618 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:37:54.624  7049  7049 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-29 08:37:54.627  7049  7558 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 08:37:54.628  7049  7049 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 08:37:54.628  7049  7049 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:37:54.628  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:54.631  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-29 08:37:54.631  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 08:37:54.632  7049  7049 D HidService: Received stop request...Stopping profile...
08-29 08:37:54.632  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:54.636  7049  7049 D HealthService: Received stop request...Stopping profile...
08-29 08:37:54.636  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
,08-29 08:37:54.642  7049  7049 D PanService: Received stop request...Stopping profile...
08-29 08:37:54.642  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:54.644  7049  7049 D HeadsetStateMachine: Unbinding service...
08-29 08:37:54.644  7049  7049 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 08:37:54.644  7049  7049 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 08:37:54.645  7049  7049 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 08:37:54.645  7049  7049 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 08:37:54.645  7049  7049 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 08:37:54.645  7049  7049 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:37:54.645  7049  7049 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 08:37:54.645  7049  7049 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:37:54.646  7049  7049 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 08:37:54.646  7049  7049 D BtGatt.GattService: stop()
08-29 08:37:54.646  7049  7049 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 08:37:54.647  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:54.649  7049  7049 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:37:54.649  7049  7049 D BluetoothMapService: stop()
,08-29 08:37:54.656  7049  7049 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 08:37:54.656  7049  7049 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 08:37:54.657  7049  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:54.658  7049  7049 I BluetoothA2dpServiceJni: cleanupNative
08-29 08:37:54.658  7049  7619 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 08:37:54.658  7049  7049 I GKI_LINUX: GKI_exit_task 2 done
08-29 08:37:54.659  7049  7049 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 08:37:54.659  7049  7049 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:37:54.659  7049  7049 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:37:54.659  7049  7049 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:37:54.660  7049  7049 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:37:54.660  7049  7049 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:37:54.660  7049  7049 V BluetoothMapService: Handler(): got msg=4
08-29 08:37:54.660  7049  7049 D BluetoothMapService: MAP Service closeService in
08-29 08:37:54.660  7049  7049 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 08:37:54.660  7049  7049 V BluetoothMapService: MAP Service closeService out
08-29 08:37:54.661  7049  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 08:37:54.661  7049  7558 D BluetoothAdapterProperties: Setting state to 10
08-29 08:37:54.661  7049  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-29 08:37:54.664  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:54.664  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 08:37:54.664  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 08:37:54.666  7049  7558 I BluetoothAdapterState: Entering OffState
08-29 08:37:54.666  1852  2454 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:54.668  1852  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:54.668  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:54.668  6927  6945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:54.669  7049  7049 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 08:37:54.669  7049  7049 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 08:37:54.671  7049  7049 D BluetoothMapService: cleanup()
08-29 08:37:54.671  7049  7049 D BluetoothMapService: MAP Service closeService in
08-29 08:37:54.671  7049  7049 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 08:37:54.671  7049  7049 V BluetoothMapService: MAP Service closeService out
08-29 08:37:54.673  6927  6945 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 08:37:54.675  1852  3942 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:54.676  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:37:54.677  6927  6945 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:37:54.678  6927  6945 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:37:54.678  6927  6945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:37:54.679  6927  6945 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:37:54.680  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 08:37:54.680  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 08:37:54.682  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 08:37:54.682  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 08:37:54.682  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@bbcb24b mBinding = false
08-29 08:37:54.683  1034  1116 D BluetoothManagerService: Sending unbind request.
08-29 08:37:54.689  7049  7562 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 08:37:54.691  7049  7049 I GKI_LINUX: GKI_exit_task 1 done
08-29 08:37:54.692  7049  7049 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 08:37:54.692  7049  7049 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 08:37:54.692  7049  7049 I art     : --- WEIRD: removing null entry 248
08-29 08:37:54.693  7049  7049 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 08:37:54.693  7049  7049 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 08:37:54.694  7049  7049 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 08:37:54.695  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 08:37:54.697  7049  7049 I art     : System.exit called, status: 0
08-29 08:37:54.697  7049  7049 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 08:37:54.716  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:54.718  1941  2099 D LGBluetoothAPIService: Message: 2
08-29 08:37:54.719  1941  2099 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@dbdc0f9 mBinding = false
08-29 08:37:54.719  1941  2099 D LGBluetoothAPIService: Sending unbind request.
08-29 08:37:54.724  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:37:54.728  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:54.730  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:54.732   315   315 V AudioFlinger: 7049 died, releasing its sessions
08-29 08:37:54.732   315   315 V AudioFlinger:  pid 1852 @ 0
08-29 08:37:54.732   315   315 V AudioFlinger:  pid 3444 @ 1
08-29 08:37:54.732   315   315 V AudioFlinger:  pid 3444 @ 2
08-29 08:37:54.735  1602  1602 D BluetoothAdapter: 260883617: getState() :  mService = null. Returning STATE_OFF
08-29 08:37:54.735  1602  1602 D BluetoothAdapter: 260883617: getState() :  mService = null. Returning STATE_OFF
08-29 08:37:54.736  6927  6927 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 08:37:54.736  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 08:37:54.736  6927  6927 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 08:37:54.738  1034  1994 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-29 08:37:54.738  1034  1994 W ActivityManager: android.os.DeadObjectException
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-29 08:37:54.738  1034  1994 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 08:37:54.739  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 08:37:54.823  1034  2033 I ActivityManager: Process com.android.bluetooth (pid 7049) has died
08-29 08:37:54.823  1034  2033 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-29 08:37:54.927  1034  1049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7765 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 08:37:54.930  6927  6927 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:55.010  7765  7765 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 08:37:55.011  7765  7765 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:37:55.011  7765  7765 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 08:37:55.012  7765  7765 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 08:37:55.041  7765  7765 D BluetoothAdapterApp: Loading JNI Library
,08-29 08:37:55.076  7765  7765 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3f8eb96 Instance Count = 1
,08-29 08:37:55.160  1034  1100 I art     : Explicit concurrent mark sweep GC freed 73746(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.935ms total 173.029ms
,08-29 08:37:55.163  7765  7765 D BluetoothAdapterApp: onCreate
08-29 08:37:55.193  7765  7765 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 08:37:55.193  7765  7765 D ProfileConfigQcom: Adding HeadsetService
08-29 08:37:55.193  7765  7765 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 08:37:55.193  7765  7765 D ProfileConfigQcom: Adding A2dpService
08-29 08:37:55.194  7765  7765 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 08:37:55.194  7765  7765 D ProfileConfigQcom: Adding HidService
08-29 08:37:55.194  7765  7765 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 08:37:55.194  7765  7765 D ProfileConfigQcom: Adding HealthService
08-29 08:37:55.195  7765  7765 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-29 08:37:55.196  7765  7765 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 08:37:55.196  7765  7765 D ProfileConfigQcom: Adding PanService
08-29 08:37:55.197  7765  7765 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 08:37:55.197  7765  7765 D ProfileConfigQcom: Adding GattService
08-29 08:37:55.197  7765  7765 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 08:37:55.197  7765  7765 D ProfileConfigQcom: Adding BluetoothMapService
08-29 08:37:55.198  7765  7765 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-29 08:37:55.199  7765  7765 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 08:37:55.200  7765  7765 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:55.200  7765  7765 V BluetoothPbapReceiver: ***********state = 10
08-29 08:37:55.202  7765  7765 V LGMDMManagerInternal: Create singleton instance
08-29 08:37:55.298  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:55.303  1034  1699 I ActivityManager: Killing 7127:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 08:37:55.304  6927  6927 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 08:37:55.346  1034  1976 W libprocessgroup: failed to open /acct/uid_10011/pid_7127/cgroup.procs: No such file or directory
,08-29 08:37:55.352  6927  6927 D BluetoothPermissionRequest: onReceive
08-29 08:37:55.354  6927  6927 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 08:37:55.354  6927  6927 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 08:37:55.357  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 08:37:55.363  7765  7765 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 08:37:55.369  7765  7765 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:55.375  7765  7765 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:37:55.376  7765  7765 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-29 08:37:55.377  7765  7765 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 08:37:55.380  7765  7765 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:55.380  7765  7765 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 08:37:55.386  6998  6998 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 08:37:56.625  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 08:37:56.626  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 08:37:56.766  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 08:37:56.803  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 08:37:56.825  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 08:37:56.857  1034  1100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7792 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 08:37:56.876  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 08:37:56.881  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-29 08:37:56.920  1034  1034 D administrator: Handling package changes for user 0
,08-29 08:37:56.936  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 08:37:56.978  7792  7792 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 08:37:57.064  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-29 08:37:57.065  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 08:37:57.080  7792  7792 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:57.080  7792  7792 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:57.127  1034  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 08:37:57.135  1034  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 08:37:57.142  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-29 08:37:57.147  2478  2478 V GmsNetworkLocationProvi: DISABLE
08-29 08:37:57.187  1034  1097 D LocationProviderProxy: applying state to connected service
,08-29 08:37:57.190  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-29 08:37:57.247  7792  7837 I Babel   : MmsConfig: mnc/mcc: 0/0
08-29 08:37:57.248  7792  7837 I Babel   : MmsConfig.loadMmsSettings
08-29 08:37:57.255  7792  7837 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 08:37:57.255  7792  7837 I Babel   : MmsConfig.loadFromDatabase
,08-29 08:37:57.278  7792  7837 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-29 08:37:57.278  7792  7837 I Babel   : MmsConfig.loadFromResources
08-29 08:37:57.281  7792  7837 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-29 08:37:57.282  7792  7837 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 08:37:57.288  7792  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:57.297  7792  7835 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 08:37:57.300  7792  7835 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 08:37:57.302  7792  7835 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 08:37:57.318  1817  7839 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-29 08:37:57.318  1817  7839 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-29 08:37:57.320  7792  7835 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-29 08:37:57.323  7792  7835 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 08:37:57.324  7792  7835 W AudioCapabilities: Unsupported mime audio/evrc
08-29 08:37:57.341  7792  7835 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 08:37:57.345  7792  7835 W VideoCapabilities: Unsupported mime video/divx
08-29 08:37:57.348  7792  7835 W VideoCapabilities: Unsupported mime video/divx311
08-29 08:37:57.350  7792  7835 W VideoCapabilities: Unsupported mime video/divx4
08-29 08:37:57.357  7792  7835 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-29 08:37:57.362  1034  2033 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7843 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 08:37:57.371  1034  2033 I ActivityManager: Killing 7165:com.lge.email/u0a23 (adj 15): empty #17
08-29 08:37:57.381  1817  4792 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-29 08:37:57.391  7792  7835 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-29 08:37:57.396  7792  7835 W AudioCapabilities: Unsupported mime audio/eac3
08-29 08:37:57.398  7792  7835 W AudioCapabilities: Unsupported mime audio/ac3
08-29 08:37:57.399  7792  7835 W AudioCapabilities: Unsupported mime audio/g726
08-29 08:37:57.400  7792  7835 W AudioCapabilities: Unsupported mime audio/wma-voice
08-29 08:37:57.402  7792  7835 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 08:37:57.403  7792  7835 W AudioCapabilities: Unsupported mime audio/adpcm
08-29 08:37:57.405  7792  7835 W VideoCapabilities: Unsupported mime video/theora
08-29 08:37:57.406  7792  7835 W VideoCapabilities: Unsupported mime video/mjpg
08-29 08:37:57.464  1034  1905 W libprocessgroup: failed to open /acct/uid_10023/pid_7165/cgroup.procs: No such file or directory
,08-29 08:37:57.555  7843  7843 I AppUp4:AppBoxCP: onCreate
08-29 08:37:57.556  7843  7843 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-29 08:37:57.566  7843  7843 I AppUp4:DB:  setFingerPrint start
,08-29 08:37:57.566  7843  7843 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 08:37:57.574  7843  7843 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 08:37:57.575  7843  7843 I AppUp4:DB:  SDK version = 21
08-29 08:37:57.575  7843  7843 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 08:37:57.577  7843  7843 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-29 08:37:57.587  7843  7843 I AppUp4:CustModeStarterReceiver: onReceive
08-29 08:37:57.628  7843  7843 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:37:57.628  7843  7843 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:57.636  7843  7843 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b42e0ed
08-29 08:37:57.636  7843  7843 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 08:37:57.636  7843  7843 D AppUp4:CustFacade: isPhone : true
08-29 08:37:57.637  7843  7843 D AppUp4:CustModeStarterReceiver: begin check event
08-29 08:37:57.637  7843  7843 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-29 08:37:57.677  1034  1653 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7863 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 08:37:57.678  1034  1653 I ActivityManager: Killing 7019:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-29 08:37:57.746  1034  2031 W libprocessgroup: failed to open /acct/uid_10026/pid_7019/cgroup.procs: No such file or directory
,08-29 08:37:57.779  7863  7863 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 08:37:57.780  7863  7863 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:37:57.780  7863  7863 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-29 08:37:57.782  7863  7863 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 08:37:57.782  7863  7863 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 08:37:57.893  7863  7863 I SystemConfig: BUILD Country: EU
,08-29 08:37:57.893  7863  7863 I SystemConfig: BUILD Operator: OPEN
,08-29 08:37:57.942  1034  1049 I ActivityManager: Killing 6543:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-29 08:37:57.975  1034  1994 W libprocessgroup: failed to open /acct/uid_1000/pid_6543/cgroup.procs: No such file or directory
,08-29 08:37:58.016  1034  1049 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7885 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-29 08:37:58.019  7863  7883 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 08:37:58.019  7863  7883 I SystemConfig: existFile = false
,08-29 08:37:58.019  7863  7883 I SystemConfig: canReadFile = false
08-29 08:37:58.019  7863  7883 I SystemConfig: systemFeature RCS result false
08-29 08:37:58.019  7863  7883 D SystemConfig: refreshRcsSupport() :false
,08-29 08:37:58.064  7885  7885 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 08:37:58.064  7885  7885 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 08:37:58.064  7885  7885 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 08:37:58.065  7885  7885 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 08:37:58.188  7885  7885 I AppConfig: Total System Memory = 2995761152
,08-29 08:37:58.200  7885  7885 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-29 08:37:58.290  1034  1905 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7908 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 08:37:58.292  1034  1905 I ActivityManager: Killing 7207:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-29 08:37:58.363  1034  1923 W libprocessgroup: failed to open /acct/uid_10046/pid_7207/cgroup.procs: No such file or directory
,08-29 08:37:58.560  7908  7908 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 08:37:58.633  7908  7908 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 08:37:58.633  7908  7908 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:37:58.689  7908  7908 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 08:37:58.713  7908  7908 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 08:37:58.716  7908  7908 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 08:37:58.747  7908  7908 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 08:37:58.747  7908  7908 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-29 08:37:58.767  1034  1905 I ActivityManager: Killing 7226:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 08:37:58.805  1034  2033 W libprocessgroup: failed to open /acct/uid_10057/pid_7226/cgroup.procs: No such file or directory
,08-29 08:37:58.818  2845  3914 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-29 08:37:58.819  4613  7945 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-29 08:37:58.821  2845  3914 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3b1f4d94 on behalf of 7908
08-29 08:37:58.881  1034  1995 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7946 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 08:37:58.912   342   342 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 25.787ms
,08-29 08:37:58.935   342   342 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.702ms
,08-29 08:37:58.958   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 21.574ms
08-29 08:37:58.973  7908  7908 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 08:37:58.998  7908  7908 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-29 08:37:59.008  7946  7946 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 08:37:59.030  7946  7946 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-29 08:37:59.030  7946  7946 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-29 08:37:59.031  7946  7946 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-29 08:37:59.031  7946  7946 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-29 08:37:59.031  7946  7946 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-29 08:37:59.031  7946  7946 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-29 08:37:59.053  1034  1994 I ActivityManager: Killing 7247:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-29 08:37:59.095  1034  1050 W libprocessgroup: failed to open /acct/uid_10062/pid_7247/cgroup.procs: No such file or directory
,08-29 08:37:59.315  1034  1958 V SIM_STK : Menu title from STK is T-Mobile
,08-29 08:37:59.349  4613  7945 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 530 ms] updated apps [took 530 ms] 
,08-29 08:37:59.647  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:37:59.647  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23d15682 added. We now have 6 listener(s)
08-29 08:37:59.647  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:37:59.656  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:59.656  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3309a193 added. We now have 7 listener(s)
08-29 08:37:59.656  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:59.657  6741  6842 I System.out: IsBluetoothEnabled
08-29 08:37:59.658  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:59.658  1034  1995 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 08:37:59.659  1034  1116 D BluetoothManagerService: Message: 2
08-29 08:37:59.662  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:59.662  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:37:59.662  1034  1050 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 08:37:59.676  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:37:59.677  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:37:59.677  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 08:37:59.677  1034  1116 D BluetoothManagerService: Message: 1
08-29 08:37:59.677  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 08:37:59.704  1034  1116 D BluetoothManagerService: Message: 20
08-29 08:37:59.704  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b3b449a:true
,08-29 08:37:59.708  7765  7765 D BluetoothAdapterState: make
08-29 08:37:59.714  7765  7765 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 08:37:59.714  7765  7765 I bluedroid-qcom: init
08-29 08:37:59.715  7765  7990 I BluetoothAdapterState: Entering OffState
08-29 08:37:59.715  7765  7765 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 08:37:59.716  7765  7765 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 08:37:59.716  7765  7765 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:37:59.716  7765  7765 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 08:37:59.716  7765  7765 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 08:37:59.717  7765  7765 I bluedroid-qcom: get_profile_interface socket
08-29 08:37:59.718  7765  7765 I bluedroid-qcom: get_profile_interface map_client
,08-29 08:37:59.722  7765  7994 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 08:37:59.717  7993  7993 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:59.727  7765  7994 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 08:37:59.717  7993  7993 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:37:59.745  7993  7993 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 08:37:59.745  7993  7993 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 08:37:59.745  7993  7993 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 08:37:59.748  7993  7993 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 08:37:59.753  7993  7993 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 08:37:59.753  7993  7993 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 08:37:59.765  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 08:37:59.766  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 08:37:59.766  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 08:37:59.768  1034  1116 D BluetoothManagerService: Message: 40
08-29 08:37:59.768  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 08:37:59.769  7765  7780 I bluedroid-qcom: config_hci_snoop_log
08-29 08:37:59.771  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 08:37:59.771  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 08:37:59.772  7765  7994 D BluetoothAdapterProperties: Name is: G3
08-29 08:37:59.777  7765  7990 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 08:37:59.777  7765  7990 D BluetoothAdapterProperties: Setting state to 11
08-29 08:37:59.777  7765  7990 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 08:37:59.779  7765  7990 I LGBluetoothServiceJni: classInitNative: succeeds
,08-29 08:37:59.785  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:37:59.785  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 08:37:59.785  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 08:37:59.789  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:59.789  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:37:59.792  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:59.803  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-29 08:37:59.808  7765  7990 D BluetoothBondStateMachine: make
08-29 08:37:59.812  7765  7765 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 08:37:59.812  7765  7765 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:59.812  7765  7765 V BluetoothPbapReceiver: ***********state = 11
08-29 08:37:59.815  7765  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:59.815  7765  7990 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 08:37:59.815  7765  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:59.815  7765  7990 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-29 08:37:59.816  7765  7990 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 08:37:59.820  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:37:59.821  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:59.821  7765  8007 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 08:37:59.831  7765  7765 D HeadsetService: Received start request. Starting profile...
08-29 08:37:59.832  7765  7765 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:37:59.832  7765  7765 D LGBluetoothHfpAdapter: Version 1.6
08-29 08:37:59.833  6927  6927 D BluetoothPermissionRequest: onReceive
,08-29 08:37:59.836  7765  7765 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 08:37:59.837  7765  7765 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:37:59.838  7765  7765 D HeadsetStateMachine: make
08-29 08:37:59.838  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 08:37:59.841  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 08:37:59.847  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 08:37:59.853  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:59.858  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:59.863  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 08:37:59.867  7765  7990 E BluetoothAdapterService: File transfer profiles supported!!
08-29 08:37:59.881  7765  7765 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 08:37:59.881  7765  7765 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 08:37:59.881  7765  7990 V LGMDMManager: Create singleton instance
08-29 08:37:59.883  7765  7990 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 08:37:59.886  7765  7765 D HeadsetStateMachine: max_hf_connections = 1
08-29 08:37:59.886  7765  7765 I bluedroid-qcom: get_profile_interface handsfree
08-29 08:37:59.888  7765  7765 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 08:37:59.889   315   315 V AudioPolicyService: registerClient() client 0xb04102e0, uid 1002
08-29 08:37:59.889   315  1399 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 08:37:59.889   315  1399 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 08:37:59.889   315  1399 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 08:37:59.889  7765  7765 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 08:37:59.889   315  2157 V AudioFlinger: registerClient() client 0xb1433640, pid 7765
08-29 08:37:59.890   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:59.890   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:59.890  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:59.890   315  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:59.890  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:59.890   315  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:59.890  1602  2281 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:59.890  3444  3963 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:59.890  1602  2281 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:59.890  3444  3963 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:59.890  1602  2281 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:59.890  3444  3963 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:59.890  1602  2281 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:59.890  3444  3963 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:59.890  1852  2454 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:59.890  1852  2454 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:59.890  7765  7780 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:59.890  7765  7780 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 08:37:59.890  7765  7780 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:59.891  7765  7780 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 08:37:59.891  1034  1887 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 08:37:59.891  1034  1887 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 08:37:59.891  1034  1887 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 08:37:59.891  1034  1887 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 08:37:59.891  7765  7765 V ToneGenerator: Create Track: 0xb4928a80
08-29 08:37:59.891  7765  7765 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 08:37:59.891  7765  7765 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 08:37:59.891   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 08:37:59.891   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, form,at 0, channelMask 3, flags 0
08-29 08:37:59.891   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 08:37:59.891   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 08:37:59.891   315  1399 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 08:37:59.892   315  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 08:37:59.892   315  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 08:37:59.892   315  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 08:37:59.892   315  2157 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 08:37:59.892  7765  7765 V AudioSystem: getLatency() output 2, latency 50
08-29 08:37:59.892  7765  7765 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 08:37:59.892  7765  7765 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 08:37:59.892   315  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 08:37:59.892   315  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 08:37:59.892   315  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 08:37:59.892   315  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 08:37:59.892   315  1400 V AudioFlinger: createTrack() lSessionId: 21
08-29 08:37:59.893  7765  7765 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 08:37:59.894   315   315 V AudioFlinger: acquiring 21 from 7765, for 7765
08-29 08:37:59.894   315   315 V AudioFlinger:  added new entry for 21
08-29 08:37:59.894  7765  7765 V ToneGenerator: ToneGenerator INIT OK, time: 136621
08-29 08:37:59.894  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:59.895  7765  8011 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,08-29 08:37:59.896  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:37:59.895  7765  8011 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 08:37:59.897  7765  8011 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 08:37:59.898  7765  8011 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-29 08:37:59.898  7765  7765 D A2dpService: Received start request. Starting profile...
08-29 08:37:59.898   315  1399 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7765
08-29 08:37:59.899  7765  7765 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:37:59.899   315  1399 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 08:37:59.899   315  1399 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 08:37:59.899   315  1399 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 08:37:59.900   315  1399 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 08:37:59.900   315  1399 V voice   : voice_set_parameters: exit with code(0)
08-29 08:37:59.900   315  1399 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 08:37:59.900   315  1399 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 08:37:59.900  7765  7765 V Avrcp   : make
08-29 08:37:59.900   315  1399 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 08:37:59.900   315  1399 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 08:37:59.900   315  1399 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 08:37:59.900   315  1399 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 08:37:59.900  7765  8011 V ToneGenerator: ToneGenerator destructor
08-29 08:37:59.900  7765  8011 V ToneGenerator: stopTone
08-29 08:37:59.900  7765  8011 V ToneGenerator: Delete Track: 0xb4928a80
08-29 08:37:59.901  7765  7765 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 08:37:59.901  7765  7765 I bluedroid-qcom: get_profile_interface avrcp
08-29 08:37:59.902  7765  8011 V AudioTrack: ~AudioTrack, releasing session id from 7765 on behalf of 7765
08-29 08:37:59.902   315  1400 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 08:37:59.902   315  1400 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 08:37:59.902   315   315 V AudioFlinger: releasing 21 from 7765 for 7765
08-29 08:37:59.902   315   315 V AudioFlinger:  decremented refcount to 0
08-29 08:37:59.902   315   315 V AudioFlinger: purging stale effects
08-29 08:37:59.902   315  1272 V AudioPolicyService: AudioCommandThread() waking up
08-29 08:37:59.902   315  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 08:37:59.902   315  1272 V AudioPolicyManager: releaseOutput() 2
08-29 08:37:59.902   315  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 08:37:59.902   315  1400 V AudioFlinger: PlaybackThread::Track destructor
08-29 08:37:59.902   315  1400 V AudioFlinger: removeClient_l() pid 7765, calling pid 315
08-29 08:37:59.915  7765  7765 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 08:37:59.917  7765  7765 E AudioManager: No RCC entry present to update
08-29 08:37:59.917  7765  7765 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 08:37:59.921  7765  7765 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 08:37:59.922  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 08:37:59.922  7765  7765 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 08:37:59.926  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 08:37:59.999  1034  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e99cb8f type 2 when 136710 com.google.android.gms} when 136710
,08-29 08:38:00.011   311  8019 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 08:38:00.013  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 08:38:00.043  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-29 08:38:00.043  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 08:38:00.043  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 08:38:00.044  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-29 08:38:00.045  1034  1699 V SIM_STK : Menu title from STK is T-Mobile
,08-29 08:38:00.046  1034  1699 V SIM_STK : Menu title from STK is T-Mobile
08-29 08:38:00.047  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 08:38:00.047  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-29 08:38:00.049  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-29 08:38:00.050  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 08:38:00.116  1034  1995 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 08:38:00.122  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 08:38:00.126  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 08:38:00.127  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 08:38:00.127  7765  7765 I BluetoothA2dpServiceJni: classInitNative
08-29 08:38:00.127  7765  7765 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:38:00.127  7765  7765 D A2dpStateMachine: make
08-29 08:38:00.130  7765  7765 I bluedroid-qcom: get_profile_interface a2dp
08-29 08:38:00.130  7765  8021 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 08:38:00.133  7765  7765 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 08:38:00.133  7765  7765 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 08:38:00.134  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.134  7765  8020 D A2dpStateMachine: Enter Disconnected: -2
08-29 08:38:00.134  7765  7765 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 08:38:00.136  7765  7765 D HidService: Received start request. Starting profile...
08-29 08:38:00.136  7765  7765 I bluedroid-qcom: get_profile_interface hidhost
08-29 08:38:00.136  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.136  7765  7765 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:38:00.138  7765  7765 D HealthService: Received start request. Starting profile...
08-29 08:38:00.140  7765  7765 I bluedroid-qcom: get_profile_interface health
08-29 08:38:00.141  7765  7765 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:38:00.141  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.141  7765  7765 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 08:38:00.143  7765  7765 D PanService: Received start request. Starting profile...
08-29 08:38:00.143  7765  7765 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:38:00.143  7765  7765 I bluedroid-qcom: get_profile_interface pan
08-29 08:38:00.150  7765  7765 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 08:38:00.150  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.151  7765  7765 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 08:38:00.155  7765  7765 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:38:00.155  7765  7765 D BtGatt.GattService: Received start request. Starting profile...
08-29 08:38:00.155  7765  7765 D BtGatt.GattService: start()
,08-29 08:38:00.155  7765  7765 I bluedroid-qcom: get_profile_interface gatt
08-29 08:38:00.156  7765  7765 D BtGatt.AdvertiseManager: advertise manager created
08-29 08:38:00.164  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.165  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.165  7765  7765 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 08:38:00.166  7765  7765 V BluetoothMapService: BluetoothMapBinder()
08-29 08:38:00.166  7765  7765 D BluetoothMapService: Received start request. Starting profile...
08-29 08:38:00.166  7765  7765 D BluetoothMapService: start()
08-29 08:38:00.169  7765  7765 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 08:38:00.169  7765  7765 D BluetoothMapEmailAppObserver: createReceiver()
,08-29 08:38:00.170  7765  7765 D BluetoothMapEmailAppObserver: initObservers()
08-29 08:38:00.170  7765  7765 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 08:38:00.175  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:00.175  7765  7765 D HeadsetStateMachine: Proxy object connected
08-29 08:38:00.175  7765  7765 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 08:38:00.175  7765  7765 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 08:38:00.177  7765  8011 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 08:38:00.178  7765  8011 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:38:00.178  7765  8011 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 08:38:00.179  7765  7765 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 08:38:00.183  7765  7765 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:00.187  7765  7765 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 08:38:00.189  7765  7765 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 08:38:00.191  7765  7765 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 08:38:00.192  7765  7765 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 08:38:00.194  7765  7765 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 08:38:00.197  7765  7765 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 08:38:00.197  7765  7765 V BluetoothMapService: Handler(): got msg=1
08-29 08:38:00.198  7765  7765 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 08:38:00.198  7765  7765 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:38:00.198  7765  7765 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:38:00.198  7765  7765 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:00.198  7765  7765 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 08:38:00.198  7765  7990 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 08:38:00.199  7765  7990 I bluedroid-qcom: enable
08-29 08:38:00.199  7765  8028 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 08:38:00.199  7765  8028 I bt-btu  : btu_task pending for preload complete event
08-29 08:38:00.199  7765  7990 I bt_hci_bdroid: init
08-29 08:38:00.202  7765  7990 I bt_vendor: bt-vendor : init
08-29 08:38:00.202  7765  7990 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 08:38:00.202  7765  7990 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 08:38:00.202  7765  7990 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 08:38:00.202  7765  7990 D bt_userial_mct: userial_init
08-29 08:38:00.203  7765  7990 D bt_hci_bdroid: set_power 1
08-29 08:38:00.203  7765  7990 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 08:38:00.203  7765  7990 I bt_vendor: Starting hciattach daemon
08-29 08:38:00.203  7765  7990 I bt_vendor: try to set true
08-29 08:38:00.197  8031  8031 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:38:00.197  8031  8031 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:00.237  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 08:38:00.364  8041  8041 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 08:38:00.379  8042  8042 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 08:38:00.407  8044  8044 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 08:38:00.427  8045  8045 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 08:38:00.441  8046  8046 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 08:38:00.454  8047  8047 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 08:38:00.477  8049  8049 I libmdmdetect: ESOC framework not supported
,08-29 08:38:00.478  8049  8049 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 08:38:00.486  8049  8049 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 08:38:00.486  8049  8049 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 08:38:00.486  8049  8049 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 08:38:00.486  8049  8049 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 08:38:00.486  8049  8049 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 08:38:00.486  8049  8049 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 08:38:00.486  8049  8049 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 08:38:00.523  8049  8050 E QC-QMI  : qmi_client [8049] 15: failed to locate client data
,08-29 08:38:00.528   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-29 08:38:00.528   471   471 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 08:38:00.559  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 08:38:00.582  8058  8058 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 08:38:00.607  7765  7990 I bt_vendor: bluetooth satus is on
08-29 08:38:00.607  7765  7990 D bt_hci_bdroid: preload
,08-29 08:38:00.609  7765  8030 D bt_userial_mct: userial_open(port:0)
08-29 08:38:00.609  7765  8030 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 08:38:00.613  7765  8030 I bt_vendor: Done intiailizing UART
08-29 08:38:00.614  7765  8030 I bt_vendor: Done intiailizing UART
08-29 08:38:00.614  7765  8030 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 08:38:00.614  7765  8030 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 08:38:00.614  7765  8028 I bt-btu  : btu_task received preload complete event
08-29 08:38:00.614  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 08:38:00.614  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 08:38:00.616  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 08:38:00.622  7765  8060 D bt_userial_mct: Entering userial_read_thread()
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 08:38:00.626  7765  8028 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 08:38:00.727  7765  8028 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 08:38:00.727  7765  8028 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d8061 
08-29 08:38:00.727  7765  8028 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d8061 
,08-29 08:38:00.768  7765  7994 E bt-btif : Calling BTA_HhEnable
08-29 08:38:00.768  7765  7994 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 08:38:00.769  7765  7994 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 08:38:00.771  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-29 08:38:00.772  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 08:38:00.772  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 08:38:00.773  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 08:38:00.774  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 08:38:00.774  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 08:38:00.774  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 08:38:00.774  7765  7994 D BluetoothAdapterProperties: Name is: G3
08-29 08:38:00.776  7765  7994 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:38:00.776  7765  7994 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:38:00.776  7765  7994 D bt_hci_bdroid: postload
08-29 08:38:00.776  7765  8030 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:38:00.777  7765  7994 D bte_conf: Device ID record 1 : primary
08-29 08:38:00.777  7765  7994 D bte_conf:   vendorId            = 00c4
08-29 08:38:00.777  7765  7994 D bte_conf:   vendorIdSource      = 0001
08-29 08:38:00.777  7765  7994 D bte_conf:   product             = 13a1
08-29 08:38:00.777  7765  7994 D bte_conf:   version             = 1000
08-29 08:38:00.777  7765  7994 D bte_conf:   clientExecutableURL = 
08-29 08:38:00.777  7765  7994 D bte_conf:   serviceDescription  = 
08-29 08:38:00.777  7765  7994 D bte_conf:   documentationURL    = 
08-29 08:38:00.777  7765  7994 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 08:38:00.778  7765  8028 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 08:38:00.779  7765  8030 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:38:00.782  7765  7990 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 08:38:00.782  7765  7990 D BluetoothAdapterProperties: ScanMode =  20
,08-29 08:38:00.787  7765  7990 D BluetoothAdapterProperties: State =  11
08-29 08:38:00.788  7765  7990 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 08:38:00.788  7765  7990 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 08:38:00.788  7765  7990 D BluetoothAdapterProperties: Setting state to 12
08-29 08:38:00.788  7765  7990 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 08:38:00.789  7765  7994 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 08:38:00.789  7765  7994 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 08:38:00.787  8062  8062 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:00.787  8062  8062 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:00.797  1034  1116 D BluetoothManagerService: Message: 60
08-29 08:38:00.797  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 08:38:00.797  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-29 08:38:00.803  7765  8030 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:38:00.807  7765  8030 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 08:38:00.808  7765  8060 E bt_mct  : hci lib postload completed
08-29 08:38:00.813  7765  8028 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:38:00.814  7765  8028 W bt-smp  : Plain text(LSB ~ MSB) = d7 f6 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:38:00.814  7765  8028 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 ae 9b 6d 07 e0 03 ae cd e2 ad c2 e5 c3 e5 ca 
,08-29 08:38:00.817  7765  8028 W bt-btm  : Stopping oneshot timer
08-29 08:38:00.826  7765  7990 I BluetoothAdapterState: Entering On State
,08-29 08:38:00.829  1852  3942 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:00.843  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:38:00.849  7765  7994 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:38:00.850  7765  7994 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 08:38:00.853  7765  8028 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:38:00.853  7765  8028 W bt-smp  : Plain text(LSB ~ MSB) = 8a bd 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:38:00.853  7765  8028 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 72 c5 07 0d 1d 29 00 fb 8e 62 32 98 24 03 5c 
08-29 08:38:00.853  7765  8028 W bt-btm  : Stopping oneshot timer
08-29 08:38:00.860  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:38:00.866  7765  8028 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:38:00.866  7765  8028 W bt-smp  : Plain text(LSB ~ MSB) = 8c b3 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:38:00.866  7765  8028 W bt-smp  : Encrypted text(LSB ~ MSB) = bb e9 f4 12 de 53 98 8c bf 0a c7 39 d0 5a c3 66 
08-29 08:38:00.866  7765  8028 W bt-btm  : Stopping oneshot timer
08-29 08:38:00.878  7765  8028 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:38:00.878  7765  8028 W bt-smp  : Plain text(LSB ~ MSB) = 12 c5 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:38:00.878  7765  8028 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 f7 f4 c5 02 1d 60 bf d2 e1 04 10 0b 36 1a c4 
,08-29 08:38:00.884  7765  8028 W bt-btm  : Stopping oneshot timer
08-29 08:38:00.887  7765  7990 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 08:38:00.887  7765  7990 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 08:38:00.887  7765  7990 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 08:38:00.893  7765  7990 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 08:38:00.893  7765  7990 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 08:38:00.904  7765  8028 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 08:38:00.904  7765  8028 W bt-smp  : Plain text(LSB ~ MSB) = 7e 44 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 08:38:00.904  7765  8028 W bt-smp  : Encrypted text(LSB ~ MSB) = 1d 10 78 ff 75 bf df dd 87 3a 2e 4a 64 15 2b f2 
08-29 08:38:00.904  7765  8028 W bt-btm  : Stopping oneshot timer
08-29 08:38:00.909  1852  1852 D BluetoothHeadset: Proxy object connected
,08-29 08:38:00.918  8067  8067 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 08:38:00.919  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:00.921  1852  1852 D BluetoothHeadset: Proxy object connected
,08-29 08:38:00.930  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:00.932  1034  1034 D BluetoothHeadset: Proxy object connected
08-29 08:38:00.934  6927  7681 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:38:00.938  6927  6945 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:38:00.937  6927  6927 D BluetoothHeadset: Proxy object connected
08-29 08:38:00.939  6927  6927 D HeadsetProfile: Bluetooth service connected
08-29 08:38:00.941  1852  3945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:00.944  6927  6927 D BluetoothInputDevice: Proxy object connected
08-29 08:38:00.944  6927  6927 D HidProfile: Bluetooth service connected
08-29 08:38:00.945  1852  1852 D BluetoothHeadset: Proxy object connected
08-29 08:38:00.945  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:38:00.947  6927  7681 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:38:00.949  1034  1034 D BluetoothA2dp: Proxy object connected
,08-29 08:38:00.951  6927  6945 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:38:00.951  6927  6945 D BluetoothPan: onBluetoothStateChange call bindService
08-29 08:38:00.954  6927  6944 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:38:00.956  6927  6927 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:38:00.956  6927  6927 D PanProfile: Bluetooth service connected
08-29 08:38:00.956  6927  6945 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:38:00.958  6927  6927 D BluetoothA2dp: Proxy object connected
08-29 08:38:00.958  6927  6927 D A2dpProfile: Bluetooth service connected
08-29 08:38:00.960  6927  6927 D BluetoothMap: Proxy object connected
08-29 08:38:00.960  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 08:38:00.960  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 08:38:00.960  6927  6927 D MapProfile: Bluetooth service connected
08-29 08:38:00.960  6927  6927 D BluetoothMap: getConnectedDevices()
,08-29 08:38:00.962  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 08:38:00.964  7765  8081 V BluetoothMapService: getConnectedDevices()
08-29 08:38:00.966  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:00.966  1941  2099 D LGBluetoothAPIService: Message: 1
08-29 08:38:00.966  1941  2099 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 08:38:00.967  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 08:38:00.968  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:00.968  1034  1116 D BluetoothManagerService: Message: 40
08-29 08:38:00.968  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 08:38:00.976  7765  7765 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:00.976  1941  2099 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 08:38:00.977  7765  7765 D BluetoothMapService: STATE_ON
08-29 08:38:00.980  6927  6927 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 08:38:00.980  7765  7765 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 08:38:00.981  7765  7765 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 08:38:00.981  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 08:38:00.985  7765  7765 V BluetoothMapService: Handler(): got msg=1
08-29 08:38:00.987  7765  7765 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 08:38:00.987  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 08:38:00.987  1941  2099 D LGBluetoothAPIService: Message: 100
08-29 08:38:00.987  1941  2099 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 08:38:00.989  6927  6927 D DockEventReceiver: finishStartingService: stopping service
08-29 08:38:00.994  7765  8086 D BluetoothMapMasInstance: MAS initSocket()
08-29 08:38:00.995  7765  8086 D BluetoothMapMasInstance:   masId = 00
08-29 08:38:00.995  7765  8086 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 08:38:00.995  7765  8086 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 08:38:00.995  7765  8086 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-29 08:38:00.997  1034  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:00.999  7765  8086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:38:01.000  7765  8086 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 08:38:01.000  7765  8086 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 08:38:01.001  7765  8086 D BluetoothMapMasInstance: Accepting socket connection...
08-29 08:38:01.001  7765  7994 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:38:01.001  7765  7994 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 08:38:01.003  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:01.007  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:01.007  7765  7765 V BluetoothPbapService: Pbap Service onCreate
08-29 08:38:01.007  7765  7765 V BluetoothPbapService: Starting PBAP service
,08-29 08:38:01.010  7765  7765 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-29 08:38:01.010  7765  7765 V BluetoothPbapService: Pbap Service onBind
08-29 08:38:01.011  7765  7765 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:01.011  7765  7765 V BluetoothPbapService: state: 12
08-29 08:38:01.012  7765  7765 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 08:38:01.012  7765  7765 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:01.012  7765  7765 V BluetoothPbapReceiver: ***********state = 12
08-29 08:38:01.012  6927  6927 D BluetoothPbap: Proxy object connected
08-29 08:38:01.012  6927  6927 D PbapServerProfile: Bluetooth service connected
08-29 08:38:01.014  7765  7765 V BluetoothPbapService: Handler(): got msg=1
08-29 08:38:01.014  7765  7765 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 08:38:01.015  2081  2081 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:38:01.015  7765  8088 V BluetoothPbapService: Pbap Service initSocket
08-29 08:38:01.016  2081  2081 D c       : Getting all permits...
08-29 08:38:01.016  1034  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:01.016  2081  2081 D a       : Opening database...
08-29 08:38:01.016  7765  8088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:38:01.017  7765  8088 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 08:38:01.017  7765  8088 V BluetoothPbapService: Succeed to create listening socket 
08-29 08:38:01.017  7765  8088 V BluetoothPbapService: Accepting socket connection...
08-29 08:38:01.020  2081  2081 D a       : Opening database auth.proximity.permit_store...
08-29 08:38:01.021  2081  2081 D a       : Closing database...
,08-29 08:38:01.031  6927  6927 D BluetoothPermissionRequest: onReceive
08-29 08:38:01.033  6927  6927 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 08:38:01.034  6927  6927 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 08:38:01.037  7765  7765 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 08:38:01.039  7765  7765 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 08:38:01.047  7765  7765 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 08:38:01.075  7765  7765 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 08:38:01.075  7765  7765 V BtOppService: onCreate
,08-29 08:38:01.082  7765  7765 V BluetoothOppNotification: send message
08-29 08:38:01.087  7765  7765 V BtOppService: Starting RfcommListener
08-29 08:38:01.100  7765  7765 D BluetoothOppPreference: Dumping Names:  
08-29 08:38:01.100  7765  7765 D BluetoothOppPreference: {}
08-29 08:38:01.100  7765  7765 D BluetoothOppPreference: Dumping Channels:  
08-29 08:38:01.100  7765  7765 D BluetoothOppPreference: {}
08-29 08:38:01.101  7765  7765 V BtOppService: onStartCommand
08-29 08:38:01.103  7765  8092 V BtOppService: Deleted complete outbound shares, number =  0
,08-29 08:38:01.107  7765  7765 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:38:01.107  7765  8095 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 08:38:01.107  7765  7765 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 08:38:01.108  7765  8092 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 08:38:01.110  7765  8092 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 08:38:01.110  7765  7765 V BluetoothOppNotification: new notify threadi!
08-29 08:38:01.111  7765  7765 V BluetoothOppNotification: send delay message
08-29 08:38:01.111  7765  8095 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 08:38:01.114  7765  8092 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f8ecdfb on behalf of 
08-29 08:38:01.114  7765  7765 V BtOppService: start RfcommListener
08-29 08:38:01.116  7765  8096 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 08:38:01.121  7765  8095 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2db25e18 on behalf of 
08-29 08:38:01.123  7765  8096 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c2d9071 on behalf of 
08-29 08:38:01.124  7765  8095 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 08:38:01.125  7765  8096 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 08:38:01.125  7765  7765 V BtOppService: RfcommListener started
08-29 08:38:01.126  7765  7765 V BtOppService: ContentObserver received notification
08-29 08:38:01.128  7765  8096 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 08:38:01.128  7765  8097 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 08:38:01.128  7765  7765 V BtOppService: ContentObserver received notification
08-29 08:38:01.129  1034  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 08:38:01.132  7765  8098 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 08:38:01.132  7765  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 08:38:01.133  7765  8096 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19cf1e56 on behalf of 
08-29 08:38:01.135  7765  8097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:38:01.135  7765  8096 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 08:38:01.136  7765  8097 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 08:38:01.137  7765  8097 V BtOppRfcommListener: Started RFCOMM listener....
08-29 08:38:01.137  7765  8097 I BtOppRfcommListener: Accept thread started.
08-29 08:38:01.137  7765  8097 V BtOppRfcommListener: Accepting connection...
08-29 08:38:01.149  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
08-29 08:38:01.149  7765  7765 V BluetoothFtpService: Ftp Service onCreate
08-29 08:38:01.149  7765  7765 I BluetoothFtpService: Ftp Service onCreate
08-29 08:38:01.149  7765  7765 V BluetoothFtpService: Ftp Service onStartCommand
08-29 08:38:01.149  7765  7765 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:01.150  7765  7765 V BluetoothFtpService: Starting Listening on sockets
08-29 08:38:01.150  7765  7765 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 08:38:01.150  7765  7765 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 08:38:01.150  7765  7765 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 08:38:01.150  7765  7765 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:01.150  7765  7765 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 08:38:01.151  7765  7765 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 08:38:01.154  7765  7765 V BluetoothFtpService: Handler(): got msg=1
08-29 08:38:01.155  7765  7765 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 08:38:01.155  7765  7765 V BluetoothFtpService: Ftp Service initSocket
08-29 08:38:01.158  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:01.159  7765  7765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:38:01.161  7765  7765 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-29 08:38:01.161  7765  7765 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-29 08:38:01.163  7765  8099 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 08:38:01.181  7765  7765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fe9d76e
,08-29 08:38:01.181  7765  7765 V BluetoothSapService: Sap Service onCreate
08-29 08:38:01.184  7765  7765 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:01.184  7765  7765 V BluetoothSapService: state: 12
08-29 08:38:01.184  7765  7765 V BluetoothSapService: Starting SAP server process
08-29 08:38:01.186  7765  7765 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 08:38:01.177  8100  8100 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:01.177  8100  8100 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:01.189  7765  8101 V BluetoothSapService: Sap Service initRfcommSocket
08-29 08:38:01.190  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:01.191  7765  8101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:38:01.192  7765  8101 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-29 08:38:01.192  7765  8101 V BluetoothSapService: Succeed to create listening socket 
08-29 08:38:01.193  7765  8101 V BluetoothSapService: Accepting socket connection...
08-29 08:38:01.199  8100  8100 V BT_SAP  : Event pipe created
08-29 08:38:01.199  8100  8100 V BT_SAP  : create_server_socket qcom.sap.server
08-29 08:38:01.199  8100  8100 V BT_SAP  : created socket fd 6
,08-29 08:38:01.281  1034  2031 I art     : Explicit concurrent mark sweep GC freed 24578(1214KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.324ms total 142.813ms
,08-29 08:38:01.282  7765  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa30173 on behalf of 
,08-29 08:38:01.283  7765  8098 V BluetoothOppNotification: update too frequent, put in queue
,08-29 08:38:01.286  7765  8096 V BluetoothOppNotification: outbound notification was removed.
,08-29 08:38:01.286  7765  8096 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 08:38:01.287  7765  8098 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 08:38:01.289  7765  8096 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33cad830 on behalf of 
08-29 08:38:01.291  7765  8096 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 08:38:01.294  7765  8096 V BluetoothOppNotification: inbound notification was removed.
08-29 08:38:01.294  7765  8096 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 08:38:01.296  7765  8096 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5cdca9 on behalf of 
,08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:01.710  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:38:01.725  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:38:01.729  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:01.735  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3506c5d0 added. We now have 8 listener(s)
08-29 08:38:01.735  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:01.739  1034  2033 D WifiServiceImplEx: setWifiEnabled: false pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 08:38:01.739  1034  2033 D WifiService: setWifiEnabled: false pid=6741, uid=10118
08-29 08:38:01.739  1034  2033 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 08:38:01.745  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:01.749  1034  1958 D WifiServiceImplEx: setWifiEnabled: true pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 08:38:01.750  1034  1958 D WifiService: setWifiEnabled: true pid=6741, uid=10118
08-29 08:38:01.750  1034  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:38:01.770  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 08:38:01.770  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 08:38:01.770  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 08:38:01.772  1034  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 08:38:01.772  1034  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 08:38:01.774  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 08:38:01.774  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 08:38:01.775  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 08:38:01.775  1034  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 08:38:01.775  1034  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 08:38:01.775  1034  1389 E WifiHW  : unknown target_country: EU , set to default
08-29 08:38:01.775  1034  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 08:38:01.775  1034  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 08:38:01.775  1034  1389 I WifiUtil: gEnableBmps=1
08-29 08:38:02.112  7765  7765 V BluetoothOppNotification: new notify threadi!
08-29 08:38:02.113  7765  7765 V BluetoothOppNotification: send delay message
,08-29 08:38:02.118  7765  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 08:38:02.119  7765  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@67ba22e on behalf of 
08-29 08:38:02.119  7765  8114 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 08:38:02.120  7765  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 08:38:02.121  7765  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ba241cf on behalf of 
08-29 08:38:02.122  7765  8114 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 08:38:02.123  7765  8114 V BluetoothOppNotification: outbound notification was removed.
08-29 08:38:02.123  7765  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 08:38:02.124  7765  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@193d475c on behalf of 
08-29 08:38:02.125  7765  8114 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 08:38:02.128  7765  8114 V BluetoothOppNotification: inbound notification was removed.
,08-29 08:38:02.129  7765  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 08:38:02.130  7765  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37fd9a65 on behalf of 
08-29 08:38:02.345  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 08:38:02.354   311   892 D SoftapController: Softap fwReload - Ok
08-29 08:38:02.362  1034  1389 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (582ms)
,08-29 08:38:02.367   311   892 D CommandListener: Setting iface cfg
08-29 08:38:02.367   311   892 D CommandListener: Trying to bring down wlan0
08-29 08:38:02.373   311   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:38:02.384  1034  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 08:38:02.377  8122  8122 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:02.387  8122  8122 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:38:02.424  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:38:02.424  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:38:02.424  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:38:02.443  1034  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 08:38:02.443  1034  1389 D WifiMonitor: connecting to supplicant
,08-29 08:38:02.460  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:38:02.463  8122  8122 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 08:38:02.465  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 08:38:02.465  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 08:38:02.471  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:02.472  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-29 08:38:02.473  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 08:38:02.473  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 08:38:02.473  6927  6927 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 08:38:02.474  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 08:38:02.475  6927  6927 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 08:38:02.475  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 08:38:02.475  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 08:38:02.476  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 08:38:02.476  6927  6927 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 08:38:02.476  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 08:38:02.476  6927  6927 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 08:38:02.521  8122  8122 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 08:38:02.521  8122  8122 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 08:38:02.524  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 08:38:02.544  1034  2033 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8139 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 08:38:02.545  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 08:38:02.589  8122  8122 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 08:38:02.656  8122  8122 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 08:38:02.663  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 08:38:02.663  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 08:38:02.664  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 08:38:02.664  1034  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 08:38:02.665  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:02.665  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 08:38:02.665  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 08:38:02.665  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 08:38:02.665  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:02.665  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 08:38:02.665  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 08:38:02.665  1034  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:02.666  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 08:38:02.666  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 08:38:02.666  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:02.666  1034  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 08:38:02.666  1034  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 08:38:02.667  1034  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 08:38:02.667  1034  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 08:38:02.668  1034  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 08:38:02.683  1034  1050 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8162 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 08:38:02.685  1034  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 08:38:02.685  1034  1389 E WifiStateMachine: useWiFiOffloading() : false
08-29 08:38:02.685  1034  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 08:38:02.686  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.686  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.686  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.686  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.686  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 08:38:02.688  1034  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-29 08:38:02.690  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:02.690  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 08:38:02.690  1034  1389 D WifiNative-wlan0: SET update_config 1: returned true
08-29 08:38:02.690  1034  1394 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 08:38:02.690  1034  1389 D WifiConfigStore: Loading config and enabling all networks 
08-29 08:38:02.690  1034  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 08:38:02.691  1034  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 08:38:02.693  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-29 08:38:02.695  8139  8159 W FormManager: Network not available. Please check & try again.
08-29 08:38:02.699  1034  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:02.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:38:02.702  8139  8160 V FormManager: Network unavailable.
08-29 08:38:02.703  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:38:02.706  8139  8160 V FormManager: Network unavailable.
08-29 08:38:02.708  1034  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 08:38:02.709  1034  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:38:02.709  1034  1389 D WifiStateMachine: enableVerboseLogging : level 2
08-29 08:38:02.710  1034  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 08:38:02.710  1034  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 08:38:02.710  1034  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 08:38:02.711  1034  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 08:38:02.711  1034  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 08:38:02.711  1034  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 08:38:02.711  1034  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 08:38:02.712  1034  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 08:38:02.712  1034  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 08:38:02.713  1034  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 08:38:02.713  1034  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-29 08:38:02.713  1034  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 08:38:02.713  1034  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 08:38:02.714  1034  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 08:38:02.716  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-29 08:38:02.716  1941  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 08:38:02.716  1034  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:38:02.716  1941  2257 D WfdsService: Set the WFDS Monitor: true
08-29 08:38:02.716  1034  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 08:38:02.716  1941  2257 D WfdsMonitor: WfdsMonitorThread create
08-29 08:38:02.716  1941  2257 D WfdsMonitor: WFDS Monitor is created and started
08-29 08:38:02.716  1941  2257 D WfdsService: WiFi: Supplicant connection re-established
,08-29 08:38:02.716  1034  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 08:38:02.716  1034  1389 D WifiNative-HAL: Setting external_sim to 1
08-29 08:38:02.716  1034  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 08:38:02.717  7792  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.717  1941  8178 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 08:38:02.717  1034  1389 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 08:38:02.717  1034  1389 I WifiNative-HAL: startHal
08-29 08:38:02.717  1941  8178 E CtrlSupplicant: Succeed to open control connection
,08-29 08:38:02.717  1034  1389 D wifi    : setting scan oui 0xaf549120
08-29 08:38:02.718  1941  8178 E CtrlSupplicant: Succeed to open monitor connection
08-29 08:38:02.718  1034  1389 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:38:02.718  1034  1389 I WifiNative-HAL: startHal
08-29 08:38:02.718  1034  1389 D wifi    : setting scan oui 0xaf549120
08-29 08:38:02.718  1941  8178 D WfdsMonitor: Supplicant connection established
08-29 08:38:02.718  1941  2257 D WfdsService: Connected to the supplicant for wfds
08-29 08:38:02.719  1034  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 08:38:02.719  1034  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 08:38:02.719  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,08-29 08:38:02.719  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 08:38:02.720  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 08:38:02.720  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 08:38:02.720  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 08:38:02.720  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 08:38:02.720  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 08:38:02.720  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 08:38:02.721  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 08:38:02.721  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 08:38:02.721  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 08:38:02.721  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 08:38:02.721  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 08:38:02.721  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 08:38:02.721  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 08:38:02.721  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 08:38:02.721  8122  8122 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 08:38:02.722  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 08:38:02.722  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 08:38:02.722  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 08:38:02.722  1034  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 08:38:02.723  1034  1389 E WifiNative: : [139,435,428 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 08:38:02.723  1034  1389 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 08:38:02.723  1034  1389 D WifiNative-wlan0: RECONNECT: returned true
08-29 08:38:02.723  1034  1389 D WifiNative-wlan0: doString: [STATUS]
08-29 08:38:02.724  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 08:38:02.724  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 08:38:02.724  1034  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 08:38:02.724  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 08:38:02.725  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:38:02.725  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.726   311   892 D CommandListener: Setting iface cfg
08-29 08:38:02.726   311   892 D CommandListener: Trying to bring up p2p0
08-29 08:38:02.726  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 08:38:02.726  1034  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 08:38:02.727  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-29 08:38:02.727  1034  1388 D LGWifiP2pService: P2pEnablingState
08-29 08:38:02.727  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.727  1034  1556 I WifiNative-HAL: startHal
08-29 08:38:02.727  1034  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.727  1034  1388 D LGWifiP2pService: P2p socket connection successful
08-29 08:38:02.727  1034  1388 D LGWifiP2pService: P2pEnabledState
08-29 08:38:02.727  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf549120
08-29 08:38:02.727  1034  1556 D wifi    : failed to, get capabilities : -3
08-29 08:38:02.727  1034  1556 E WifiScanningService: could not get scan capabilities
08-29 08:38:02.727  1034  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.727  1034  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 08:38:02.728  1034  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 08:38:02.728  1034  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 08:38:02.728  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 08:38:02.728  1941  1941 D WfdsService: WifiP2pState is changed : true
08-29 08:38:02.728  1941  2257 D WfdsService: Receive the WFDS_ENABLE Method
08-29 08:38:02.728  1941  2257 D WfdsService: Set the WFDS Monitor: true
08-29 08:38:02.728  1941  2257 D WfdsService: Connected to the supplicant for wfds
08-29 08:38:02.728  1941  2257 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 08:38:02.728  8122  8122 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 08:38:02.729  1941  2257 D WfdsService: selectPreferredScanChannel [36]
08-29 08:38:02.729  1941  2257 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-29 08:38:02.730  1034  1388 D LGWifiP2pService: sending p2p connection changed broadcast
,08-29 08:38:02.731  1034  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 08:38:02.733  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 08:38:02.733  1034  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 08:38:02.733  1941  1941 D WfdsService: isConnected: false
08-29 08:38:02.734  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139446  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 08:38:02.734  1034  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 08:38:02.734  1034  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 08:38:02.734  1034  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-29 08:38:02.734  1034  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 08:38:02.734  1034  1388 D LGWifiP2pService: before postfix = G3
08-29 08:38:02.734  1034  1388 D WifiServerServiceExt: postfix byte check : 2
08-29 08:38:02.734  1034  1388 D LGWifiP2pService: after postfix = G3
08-29 08:38:02.734  1034  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 08:38:02.735  1034  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 08:38:02.735  1034  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 08:38:02.735  1034  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 08:38:02.735  1034  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 08:38:02.736  1034  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 08:38:02.736  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 08:38:02.736  1034  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 08:38:02.736  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-29 08:38:02.736  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 08:38:02.737  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:02.737  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:02.738  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:02.740  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.740  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.740  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 08:38:02.740  1034  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 08:38:02.740  1034  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 08:38:02.741  1034  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 08:38:02.741  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 08:38:02.741  1034  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 08:38:02.741  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 08:38:02.741  1034  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 08:38:02.742  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 08:38:02.742  1941  1941 D WfdsService: Update P2p Interface State: 3
,08-29 08:38:02.742  1034  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 08:38:02.742  1034  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 08:38:02.743  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139455  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 08:38:02.743  1034  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 08:38:02.744  1034  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 08:38:02.744  1034  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 08:38:02.744  1034  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 08:38:02.754  8122  8122 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-29 08:38:02.754  1034  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 08:38:02.754  1034  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 08:38:02.754  1034  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 08:38:02.755  1034  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 08:38:02.755  1034  1389 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 08:38:02.755  1034  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 08:38:02.755  8122  8122 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 08:38:02.756  1034  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 08:38:02.756  1034  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 08:38:02.756  1034  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 08:38:02.757  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 08:38:02.757  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 08:38:02.757  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.758  8122  8122 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 08:38:02.758  1034  1388 D LGWifiP2pService: InactiveState
08-29 08:38:02.758  1034  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 08:38:02.758  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 08:38:02.758  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.758  1034  1388 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.758  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.758  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.758  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.758  1034  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 08:38:02.758  1034  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 08:38:02.759  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 08:38:02.759  1034  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 08:38:02.759  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.759  1034  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 08:38:02.759  1034  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.759  1034  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 08:38:02.759  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.759  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 08:38:02.759  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 08:38:02.759  1941  8178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 08:38:02.760  8122  8122 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 08:38:02.760  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.760  1941  8178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.760  1034  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.760  1034  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRI,VER type=WORLD
08-29 08:38:02.760  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.760  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.760  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.760  1941  8178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.760  1034  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.760  1034  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.760  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.760  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.761  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.761  1941  8178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.761  1034  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.761  1034  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.761  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.761  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.761  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.761  1941  8178 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.762  1034  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 08:38:02.762  1034  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.762  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.762  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 08:38:02.762  1034  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 08:38:02.762  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 08:38:02.762  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:38:02.763  1034  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.763  1034  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 08:38:02.763  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.763  1034  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 08:38:02.763  1034  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.763  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 08:38:02.764  1034  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 08:38:02.764  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:38:02.764  1034  1389 D WifiNative-wlan0: doBoolean: SCAN
08-29 08:38:02.764  1034  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1389 D WifiNative-wlan0: SCAN: returned false
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal,.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139477  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.764  1034  1388 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:02.765  1034  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 08:38:02.765  1034  1034 E WifiServerServiceExt: No p2p device connected
08-29 08:38:02.765  1941  2257 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 08:38:02.765  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139478  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 08:38:02.766  1034  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:38:02.766  1034  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:38:02.767  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.767  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:02.767  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 08:38:02.767  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:02.767  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:02.768  1034  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:38:02.768  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:02.768  1034  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:38:02.769  1034  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 08:38:02.770  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:02.770  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 08:38:02.781  8162  8162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:38:02.783  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:02.786  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:38:02.787  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:38:02.788  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:02.789  1034  1049 I ActivityManager: Killing 7268:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 08:38:02.790  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 08:38:02.791  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 08:38:02.794  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@28bda0d2 Bundle[{}]
08-29 08:38:02.795  6741  6842 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 08:38:02.795  6741  6842 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 08:38:02.795  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 08:38:02.796  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 08:38:02.797  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 08:38:02.797  6741  6842 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 08:38:02.802  6741  6842 I System.out: Running OutgoingSocketThread
08-29 08:38:02.803  6741  8184 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 857)
08-29 08:38:02.804  6741  8184 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60410
08-29 08:38:02.804  6741  8184 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 08:38:02.825  1034  1904 W libprocessgroup: failed to open /acct/uid_10085/pid_7268/cgroup.procs: No such file or directory
,08-29 08:38:02.833  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 08:38:02.833  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 08:38:02.833  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 08:38:02.833  6927  6927 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 08:38:02.834  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 08:38:02.835  6927  6927 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 08:38:02.835  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 08:38:02.835  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 08:38:02.835  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 08:38:02.835  6927  6927 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 08:38:02.835  6927  6927 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 08:38:02.847  8162  8162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:38:02.852  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 08:38:02.863  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:02.863  8139  8186 W FormManager: Network not available. Please check & try again.
08-29 08:38:02.874  8139  8187 V FormManager: Network unavailable.
,08-29 08:38:02.878  8139  8187 V FormManager: Network unavailable.
08-29 08:38:02.882  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 08:38:02.882  4325  4325 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 08:38:02.884  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 08:38:02.887  4325  4325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 08:38:02.896  4325  8188 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 08:38:02.898  4325  8189 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 08:38:02.898  4325  8189 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 08:38:02.967  1034  1994 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8190 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 08:38:03.096  8190  8190 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 08:38:03.097  8190  8190 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 08:38:03.104  8190  8190 V [BNRBootReceiver]: Boot Receiver Return
08-29 08:38:03.105  8190  8190 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 08:38:03.149  1034  1994 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8208 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 08:38:03.149  1034  1994 I ActivityManager: Killing 7292:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-29 08:38:03.257  1034  1050 W libprocessgroup: failed to open /acct/uid_10093/pid_7292/cgroup.procs: No such file or directory
,08-29 08:38:03.308  8122  8122 E wpa_supplicant: USIM:  scard_init function
,08-29 08:38:03.309  8122  8122 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 08:38:03.309  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 08:38:03.317  1034  8161 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 08:38:03.318  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 08:38:03.318  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-29 08:38:03.318  1034  8161 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 08:38:03.318  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 08:38:03.318  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-29 08:38:03.320  1034  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 08:38:03.321  1034  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 08:38:03.323  1034  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 08:38:03.324  1034  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 08:38:03.325  1034  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 08:38:03.325  8208  8208 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:38:03.337  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140050  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 08:38:03.341  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.341  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.343  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.343  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.343  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 08:38:03.343  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.345  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140057  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 08:38:03.346  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:03.346  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 08:38:03.363  8208  8208 D PluginManager: init()
,08-29 08:38:03.431  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 08:38:03.431  8122  8122 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 08:38:03.431  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 08:38:03.431  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 08:38:03.432  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-29 08:38:03.433  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140146  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 08:38:03.434  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140147  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 08:38:03.434  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 08:38:03.435  1034  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140147
08-29 08:38:03.435  1034  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140148
08-29 08:38:03.435  1034  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140148
08-29 08:38:03.436  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140149
08-29 08:38:03.436  1034  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140149
08-29 08:38:03.437  1034  1389 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:03.437  1034  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:03.438  1034  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:03.438  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:03.438  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 08:38:03.438  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:03.438  1034  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 08:38:03.439  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:38:03.439  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:38:03.443  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140156  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 08:38:03.446  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.446  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.446  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:38:03.446  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.446  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 08:38:03.448  8122  8122 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:38:03.448  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 08:38:03.449  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:38:03.449  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:38:03.449  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 08:38:03.449  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:38:03.449  1034  8161 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:38:03.450  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 08:38:03.450  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 08:38:03.450  1034  8161 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 08:38:03.450  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:38:03.450  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:38:03.451  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.451  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.451  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 08:38:03.452  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140164  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 08:38:03.452  1034  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140165  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 08:38:03.453  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140166  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 08:38:03.454  1034  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140166
08-29 08:38:03.454  1034  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140167
08-29 08:38:03.454  1034  1389 D WifiNative-wlan0: doString: [STATUS]
08-29 08:38:03.455  1034  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 08:38:03.455  1034  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 08:38:03.455  1034  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 08:38:03.456  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.457  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.4,57  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.458  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:38:03.460  1034  1389 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 08:38:03.466  1034  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 08:38:03.466  1034  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 08:38:03.469  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.469  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.469  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-29 08:38:03.476  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.476  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.477  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.477  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.477  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 08:38:03.477  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.479  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.479  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.483  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:38:03.488  1034  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 08:38:03.488  1034  1439 D ConnectivityService: Got NetworkAgent Messenger
08-29 08:38:03.488  1034  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:38:03.488  1034  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 08:38:03.488  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 08:38:03.488  1034  1439 D ConnectivityService: NetworkAgent connected
08-29 08:38:03.489  1034  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 08:38:03.489  1034  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 08:38:03.493  1034  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 08:38:03.493  1034  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:38:03.493  1034  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 08:38:03.494  1034  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-29 08:38:03.494  1034  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 08:38:03.497  1034  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 08:38:03.498   311   892 D CommandListener: Setting iface cfg
,08-29 08:38:03.501  1034  1389 E WifiStateMachine: Start Dhcp Watchdog 3
08-29 08:38:03.501  1034  8229 D DhcpStateMachine: StoppedState
08-29 08:38:03.502  1034  8229 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.502  1034  8229 D DhcpStateMachine: WaitBeforeStartState
08-29 08:38:03.502  1034  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140215  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:38:03.503  1034  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140216  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:38:03.504  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140216  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:38:03.504  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:03.504  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 08:38:03.505  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:03.505  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 08:38:03.506  1034  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140219  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:38:03.507  1034  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:38:03.507  1034  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=140220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 08:38:03.508  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14129] from screen [on:0 period:-721099020] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 08:38:03.509  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-721099019] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 08:38:03.509  1034  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 08:38:03.513  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 08:38:03.516  1034  1439 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-29 08:38:03.516  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.517  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.517  1034  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.518  1034  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.519  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.519  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.520  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 08:38:03.520  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=172,0,0
08-29 08:38:03.520  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=172,0,0
08-29 08:38:03.520  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 08:38:03.521  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 08:38:03.521  1034  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 08:38:03.521  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 08:38:03.521  1034  1389 D WifiNative-wlan0: SET ps 0: returned true
08-29 08:38:03.521  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 08:38:03.522  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 08:38:03.522  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 08:38:03.522  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cac712f target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.522  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cac712f target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.522  1034  8229 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.523  1034  8229 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 08:38:03.523  1034  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 08:38:03.524  1034  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 08:38:03.524  1034  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 08:38:03.524   311   892 D CommandListener: Setting iface cfg
08-29 08:38:03.525   311   892 D CommandListener: Trying to bring up wlan0
,08-29 08:38:03.527  1034  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 08:38:03.528  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:03.528  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 08:38:03.530  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 08:38:03.530  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 08:38:03.531  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.531  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.532  1034  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.532  1034  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.533  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.533  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 08:38:03.534  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 08:38:03.535  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 08:38:03.535  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 08:38:03.535  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.535  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.535  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 08:38:03.536  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 08:38:03.536  1034  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 08:38:03.536  1034  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 08:38:03.536  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 08:38:03.537  1034  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 08:38:03.537  1034  1389 D WifiNative-wlan0: doBoolean: SET ps 1
,08-29 08:38:03.553  1034  1389 D WifiNative-wlan0: SET ps 1: returned true
08-29 08:38:03.554  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-29 08:38:03.554  1034  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 08:38:03.555  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 08:38:03.555  1034  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 08:38:03.556  1034  1439 D ConnectivityService: ignoring duplicate network state non-change
08-29 08:38:03.561  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.561  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.561  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.562  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.562  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 08:38:03.563  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.566  1034  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 08:38:03.566  1034  1439 D ConnectivityService: Adding iface wlan0 to network 102
08-29 08:38:03.568  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.568  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 08:38:03.569  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.570  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.570  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.571  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 08:38:03.573  1034  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 08:38:03.574  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 08:38:03.576  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.576  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.576  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 08:38:03.576  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 08:38:03.579  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.579  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:38:03.579  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-29 08:38:03.581  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 08:38:03.586  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.586  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 08:38:03.586  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.589  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 08:38:03.589  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 08:38:03.590  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.594  1034  1439 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 08:38:03.594  1034  1439 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 08:38:03.595  1034  1439 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 08:38:03.596   311   892 E Netd    : netlink response contains error (File exists)
08-29 08:38:03.596  1034  1439 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 08:38:03.597  1034  1439 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 08:38:03.597  1034  1439 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-29 08:38:03.597  1034  1439 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 08:38:03.598  1034  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 08:38:03.598  1034  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.599  1034  1439 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.601  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.601  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 08:38:03.601  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:38:03.602  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 08:38:03.602  1034  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.603  1034  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:38:03.603  1034  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:03.603  1034  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 08:38:03.603  1034  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.603  1034  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 08:38:03.603  1034  1439 D ConnectivityService: currentScore = 0, newScore = 20
08-29 08:38:03.603  1034  1439 D ConnectivityService:    accepting network in place of null
08-29 08:38:03.603  1034  1439 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.603  1034  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.604  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.604  1034  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:38:03.604  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 08:38:03.605  1034  1439 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,] , Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 08:38:03.605  1034  1439 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 08:38:03.605  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 08:38:03.606  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 08:38:03.606  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 08:38:03.606  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 08:38:03.606  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-29 08:38:03.613  1034  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:38:03.613   311  8239 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 08:38:03.613  1034  1439 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 08:38:03.614  1034  1439 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 08:38:03.615  1034  1439 D ConnectivityService: validation of new default Network = false
08-29 08:38:03.615  1034  1439 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 08:38:03.615  1034  1439 D DSQN    : enableDataServiceNotify 
08-29 08:38:03.615  1034  1439 D DSQN    : start dsqn bin
08-29 08:38:03.619  1034  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.620  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.620  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:03.620  1034  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:03.621  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 08:38:03.607  8240  8240 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:38:03.607  8240  8240 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:03.625  1034  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 08:38:03.636  8240  8240 E DSQN    : DSQN ssw
,08-29 08:38:03.644  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:38:03.645  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.646  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.670   311  8239 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 08:38:03.720   311  8239 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 08:38:03.725  1034  8229 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 08:38:03.727  1034  8229 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 08:38:03.727  1034  8229 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 08:38:03.727  8244  8244 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 08:38:03.727  8244  8244 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 08:38:03.754  8244  8244 I dhcpcd  : version 5.5.6 starting
08-29 08:38:03.757  8244  8244 E dhcpcd  : get_duid: m
,08-29 08:38:03.757  8244  8244 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 08:38:03.757  8244  8244 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 08:38:03.773   311   891 D LGDataListener: argv[0]=dsqncommand
,08-29 08:38:03.773   311   891 D LGDataListener: argv[1]=wlan0
08-29 08:38:03.773   311   891 D LGDataListener: argv[2]=1
08-29 08:38:03.773   311   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 08:38:03.776  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 08:38:03.776  1034  1114 D DSQN    : start to monitor internet connection
08-29 08:38:03.807  6741  6842 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 858)
08-29 08:38:03.807  6741  6842 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 858)
08-29 08:38:03.811  6741  6842 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
08-29 08:38:03.812  6741  6842 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 08:38:03.812  6741  6842 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 864)
08-29 08:38:03.813  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 06:38:03 GMT], X-Android-Received-Millis=[1472452683813], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472452683772]}
08-29 08:38:03.813  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 08:38:03.814  1034  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 08:38:03.814  1034  1439 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.814  1034  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.814  1034  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:38:03.814  1034  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 08:38:03.814  1034  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 08:38:03.814  1034  1439 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-29 08:38:03.814  1034  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 08:38:03.814  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.814  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:03.815  1034  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:03.815  1034  1439 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.815  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 08:38:03.815  1034  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 08:38:03.815  1034  1389 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.815  1034  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 08:38:03.817  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:03.818  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 08:38:03.819  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.819  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3307c9c9 added. We now have 2 listener(s)
08-29 08:38:03.820  1034  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.822  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.822  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.822  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.823  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.823  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@344258ce added. We now have 9 listener(s)
08-29 08:38:03.823  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.823  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:38:03.826  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:03.834  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:38:03.837  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.837  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:38:03.837  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.837  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ada6efc added. We now have 3 listener(s)
08-29 08:38:03.837  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.839  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:03.841  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.843  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 08:38:03.843  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.844  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.844  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.844  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.844  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fba3985 added. We now have 10 listener(s)
08-29 08:38:03.844  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.844  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:03.844  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.844  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:03.844  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:03.844  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.844  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.844  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.844  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.844  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3307c9c9 removed from the list
08-29 08:38:03.844  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.844  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@344258ce removed from the list
08-29 08:38:03.844  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:03.844  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.845  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.845  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 08:38:03.845  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.846  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.846  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.846  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.846  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerS,ettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@344258ce not in the list
08-29 08:38:03.846  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.846  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.846  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.846  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.846  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.847  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fba3985 removed from the list
08-29 08:38:03.847  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.847  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.847  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.847  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.847  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ada6efc removed from the list
08-29 08:38:03.847  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.847  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11af33da added. We now have 2 listener(s)
08-29 08:38:03.848  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.850  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.850  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.850  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.850  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.850  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e01b00b added. We now have 9 listener(s)
08-29 08:38:03.850  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.851  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:38:03.854  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:03.857  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:38:03.858  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.858  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:38:03.858  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.858  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2369e901 added. We now have 3 listener(s)
08-29 08:38:03.859  1034  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.859  8244  8244 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 08:38:03.859  8244  8244 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 08:38:03.859  8244  8244 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 08:38:03.859  8244  8244 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 08:38:03.859  8244  8244 D dhcpcd  : wlan0: sending REQUEST (xid 0x34c8f12e), next in 4.22 seconds
08-29 08:38:03.860  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.861  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.861  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.861  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.861  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.861  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.861  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10dcb3a6 added. We now have 10 listener(s)
08-29 08:38:03.861  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.861  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:03.861  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:38:03.861  6741  6,842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:38:03.861  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:03.861  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:38:03.863  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:38:03.864  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.867  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:38:03.869  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:38:03.870  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:38:03.870  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.871  6741  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 08:38:03.871  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:03.871  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:03.872  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:03.873  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:03.873  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:03.873  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.873  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.873  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.873  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.873  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11af33da removed from the list
08-29 08:38:03.873  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.873  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e01b00b removed from the list
08-29 08:38:03.873  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:03.873  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.873  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.873  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.874  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.874  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.874  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.874  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e01b00b not in the list
08-29 08:38:03.874  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.874  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.875  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03,.875  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:38:03.875  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:38:03.875  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.875  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.875  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10dcb3a6 removed from the list
08-29 08:38:03.875  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.875  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.875  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.875  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.875  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2369e901 removed from the list
08-29 08:38:03.876  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.876  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0b143d added. We now have 2 listener(s)
08-29 08:38:03.876  1034  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.878  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.878  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.878  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.878  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.878  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c106432 added. We now have 9 listener(s)
08-29 08:38:03.879  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.879  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:38:03.881  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:03.883  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:38:03.885  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.885  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:38:03.885  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.885  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7f4300 added. We now have 3 listener(s)
08-29 08:38:03.885  1034  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.886  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.887  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.888  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.888  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.888  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.888  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.888  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1499b739 added. We now have 10 listener(s)
08-29 08:38:03.888  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.888  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:03.888  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:03.888  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:38:03.888  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:38:03.888  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:03.889  6741  68,42 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:38:03.890  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:38:03.891  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 08:38:03.892  8244  8244 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 08:38:03.896  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:38:03.896  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:38:03.897  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:38:03.898  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.899  6741  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 08:38:03.899  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:03.899  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:03.899  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:03.900  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.900  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.900  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.900  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.900  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0b143d removed from the list
08-29 08:38:03.900  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.900  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c106432 removed from the list
08-29 08:38:03.900  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:03.900  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.900  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.900  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.901  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.901  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.901  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.901  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c106432 not in the list
08-29 08:38:03.901  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.901  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.902  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.902  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:38:03.903  6741  6842 D org.thaliproject.p2p.b,tconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:38:03.903  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.903  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.903  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1499b739 removed from the list
08-29 08:38:03.903  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.903  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.903  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.903  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.903  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7f4300 removed from the list
08-29 08:38:03.904  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.904  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11158f2c added. We now have 2 listener(s)
,08-29 08:38:03.908  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.910  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.910  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.910  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:38:03.910  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.910  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd58df5 added. We now have 9 listener(s)
08-29 08:38:03.910  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.910  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:38:03.912  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:03.916  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:38:03.917  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:38:03.917  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:38:03.919  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.919  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e2b1fb added. We now have 3 listener(s)
08-29 08:38:03.919  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.919  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.921  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.922  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.922  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.922  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.922  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.922  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2de27218 added. We now have 10 listener(s)
08-29 08:38:03.922  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.922  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:03.922  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:38:03.922  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:38:03.922  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:03.922  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:38:03.926  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:38:03.926  1034  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.930  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:38:03.931  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:38:03.933  8244  8244 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 08:38:03.933  8244  8244 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 08:38:03.933  8244  8244 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 08:38:03.933  8244  8244 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 08:38:03.933  8244  8244 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 08:38:03.933  8244  8244 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 08:38:03.933  8244  8244 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 08:38:03.934  8244  8244 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 08:38:03.934  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:38:03.935  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.937  6741  6842 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 08:38:03.940  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:03.940  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:03.940  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:03.940  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.940  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.940  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.940  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.940  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11158f2c removed from the list
08-29 08:38:03.940  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.941  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd58df5 removed from the list
08-29 08:38:03.941  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:03.941  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.941  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.941  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.942  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.942  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.942  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.942  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd58df5 not in the list
08-29 08:38:03.942  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.943  6741  6842 D org.thaliproject.p2p.btconnectorlib.interna,l.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:38:03.947  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.948  6741  6842 D BluetoothLeScanner: could not find callback wrapper
08-29 08:38:03.948  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:38:03.948  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.948  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.948  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2de27218 removed from the list
08-29 08:38:03.948  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.948  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.948  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.948  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.949  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e2b1fb removed from the list
08-29 08:38:03.949  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.950  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19a072d7 added. We now have 2 listener(s)
08-29 08:38:03.950  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.954  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.954  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.954  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.954  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:03.954  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359897c4 added. We now have 9 listener(s)
08-29 08:38:03.954  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.955  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:38:03.957  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:03.963  6741  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:38:03.966  6741  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:03.966  6741  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:38:03.966  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:03.966  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc63de2 added. We now have 3 listener(s)
08-29 08:38:03.967  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 08:38:03.971  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 08:38:03.971  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:03.971  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:03.971  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:03.972  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360f6573 added. We now have 10 listener(s)
08-29 08:38:03.972  6741  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:03.972  6741  6842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:03.974  8208  8208 W ExternalStrings: load override strings
08-29 08:38:03.974  8208  8208 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 08:38:03.974  8208  8208 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 08:38:03.975  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.976  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:03.976  6741  6842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:03.976  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.976  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.976  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:03.976  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:03.976  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19a072d7 removed from the list
08-29 08:38:03.976  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.976  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnec,torlib.DiscoveryManager@359897c4 removed from the list
08-29 08:38:03.978  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.979  6741  6842 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:03.979  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.982  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.982  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.983  8208  8208 D StatusProvider: onCreate
08-29 08:38:03.984  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.984  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.984  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.984  6741  6842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359897c4 not in the list
08-29 08:38:03.984  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.984  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.985  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:03.985  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:03.985  6741  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:03.985  6741  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360f6573 removed from the list
08-29 08:38:03.985  6741  6842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:03.985  6741  6842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:03.985  6741  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:03.985  6741  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:03.985  6741  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc63de2 removed from the list
08-29 08:38:03.987  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 08:38:03.987  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 08:38:03.987  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 08:38:03.987  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:03.988  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 08:38:03.988  6741  6842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:38:03.999  6741  8257 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
08-29 08:38:04.000  6741  8257 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: My test thread name)
08-29 08:38:04.000  6741  8257 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 08:38:04.003  6741  8258 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: My test thread name)
08-29 08:38:04.003  6741  8258 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 873, thread name: My test thread name)
08-29 08:38:04.003  6741  8258 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 873, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 08:38:04.005  6741  6842 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 08:38:04.006  6741  6842 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 08:38:04.006  6741  6842 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-29 08:38:04.006  6741  6842 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 08:38:04.006  6741  6842 D com.test.thalitest.ThaliTestRunner: Total duration: 22881 ms
08-29 08:38:04.007  6741  6842 I jxcore-log: Total number of executed tests:  80
08-29 08:38:04.007  6741  6842 I jxcore-log: 
08-29 08:38:04.007  6741  6842 I jxcore-log: Number of passed tests:  80
08-29 08:38:04.007  6741  6842 I jxcore-log: 
08-29 08:38:04.008  6741  6842 I jxcore-log: Number of failed tests:  0
08-29 08:38:04.008  6741  6842 I jxcore-log: 
08-29 08:38:04.008  6741  6842 I jxcore-log: Number of ignored tests:  0
08-29 08:38:04.008  6741  6842 I jxcore-log: 
08-29 08:38:04.008  6741  6842 I jxcore-log: Total duration:  22881
08-29 08:38:04.008  6741  6842 I jxcore-log: 
08-29 08:38:04.009  6741  6842 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 08:38:04.009  6741  6842 I jxcore-log: 
08-29 08:38:04.012  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.012  6741  6842 I jxcore-log: 
08-29 08:38:04.015  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.015  6741  6842 I jxcore-log: 
08-29 08:38:04.017  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.017  6741  6842 I jxcore-log: 
08-29 08:38:04.018  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.018  6741  6842 I jxcore-log: 
08-29 08:38:04.019  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.019  6741  6842 I jxcore-log: 
08-29 08:38:04.021  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.021  6741  6842 I jxcore-log: 
08-29 08:38:04.026  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:04.026  6741  6842 I jxcore-log: 
08-29 08:38:04.026  6741  6741 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 08:38:04.028  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:04.028  6741  6842 I jxcore-log: 
08-29 08:38:04.029  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.029  6741  6842 I jxcore-log: 
08-29 08:38:04.030  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.030  6741  6842 I jxcore-log: 
08-29 08:38:04.031  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:38:04.031  6741  6842 I jxcore-log: 
08-29 08:38:04.033  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:04.033  6741  6842 I jxcore-log: 
08-29 08:38:04.034  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:04.034  6741  6842 I jxcore-log: 
08-29 08:38:04.035  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.035  6741  6842 I jxcore-log: 
08-29 08:38:04.036  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.036  6741  6842 I jxcore-log: 
08-29 08:38:04.037  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.037  6741  6842 I jxcore-log: 
08-29 08:38:04.038  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.038  6741  6842 I jxcore-log: 
,08-29 08:38:04.039  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.039  6741  6842 I jxcore-log: 
08-29 08:38:04.040  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.040  6741  6842 I jxcore-log: 
08-29 08:38:04.041  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.041  6741  6842 I jxcore-log: 
08-29 08:38:04.042  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:04.042  6741  6842 I jxcore-log: 
08-29 08:38:04.043  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:38:04.043  6741  6842 I jxcore-log: 
08-29 08:38:04.044  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:38:04.044  6741  6842 I jxcore-log: 
08-29 08:38:04.045  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.045  6741  6842 I jxcore-log: 
08-29 08:38:04.046  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.046  6741  6842 I jxcore-log: 
08-29 08:38:04.047  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.047  6741  6842 I jxcore-log: 
08-29 08:38:04.048  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.048  6741  6842 I jxcore-log: 
08-29 08:38:04.049  6741  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:04.049  6741  6842 I jxcore-log: 
,08-29 08:38:04.064  8208  8208 V Signer  : override build config not found
08-29 08:38:04.064  8208  8208 D Signer  : value of property debug is false
,08-29 08:38:04.102  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-29 08:38:04.103  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-29 08:38:04.103  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-29 08:38:04.103  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-29 08:38:04.103  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-29 08:38:04.103  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-29 08:38:04.104  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-29 08:38:04.104  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-29 08:38:04.104  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-29 08:38:04.104  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-29 08:38:04.104  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-29 08:38:04.105  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-29 08:38:04.105  8208  8208 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-29 08:38:04.120  8208  8208 V LGMDMManager: Create singleton instance
,08-29 08:38:04.207  8208  8208 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-29 08:38:04.257  8270  8270 D AndroidRuntime: 
08-29 08:38:04.257  8270  8270 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 08:38:04.260  8270  8270 D AndroidRuntime: CheckJNI is OFF
08-29 08:38:04.284  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:04.284  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 08:38:04.294  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:38:04.305  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:04.312  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:04.312  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:38:04.313  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 08:38:04.320  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:04.321  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:04.328  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:38:04.333  1034  8229 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 08:38:04.334  1034  8229 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 08:38:04.334  1034  8229 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 08:38:04.334  1034  8229 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 08:38:04.334  1034  8229 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 08:38:04.334  1034  8229 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 08:38:04.334  1034  8229 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 08:38:04.334  1034  8229 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 08:38:04.335  1034  8229 D DhcpStateMachine: RunningState
08-29 08:38:04.337  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:04.343  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:04.343  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 08:38:04.345  6978  6978 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 08:38:04.349  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 08:38:04.352  6927  6927 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 08:38:04.355  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:04.355  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:04.362  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:38:04.367  8270  8270 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 08:38:04.368  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:04.375  1034  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-29 08:38:04.375  1034  1100 I ActivityManager: Killing 6741:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-29 08:38:04.378  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:04.379  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:04.379  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:38:04.411  1034  1976 I WindowState: WIN DEATH: Window{812655a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 08:38:04.411  1034  1421 D WifiService: Client connection lost with reason: 4
08-29 08:38:04.416  1034  1976 D InputDispatcher: Window went away: Window{812655a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 08:38:04.463  8208  8278 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 08:38:04.590  1034  1100 I ActivityManager:   Force finishing activity ActivityRecord{a2261fa u0 com.test.thalitest/.MainActivity t6}
,08-29 08:38:04.622   338   409 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 08:38:04.635  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 08:38:04.635  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 08:38:04.635  6927  6927 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-29 08:38:04.635  6927  6927 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-29 08:38:04.640  1034  1994 W ActivityManager: Spurious death for ProcessRecord{e6f0c70 6741:com.test.thalitest/u0a118}, curProc for 6741: null
08-29 08:38:04.642  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 08:38:04.644  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{a2261fa u0 com.test.thalitest/.MainActivity t6 f}
08-29 08:38:04.645  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{a2261fa u0 com.test.thalitest/.MainActivity t6 f}
,08-29 08:38:04.666  1941  2940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 08:38:04.666  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 08:38:04.666  1941  2940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{317973ec co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 08:38:04.668  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 08:38:04.668  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{269073b5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 08:38:04.670  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 08:38:04.672  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-29 08:38:04.679  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 08:38:04.685  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 08:38:04.686  3797  3797 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-29 08:38:04.686  7765  7765 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 08:38:04.686  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 08:38:04.705  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-29 08:38:04.705  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-29 08:38:04.707  1602  1667 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 08:38:04.707  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.709  2032  2074 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-29 08:38:04.709  4505  4505 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 08:38:04.710  4505  4505 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 08:38:04.710  4505  4505 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 08:38:04.710  4505  4505 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 08:38:04.710  4505  4505 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-29 08:38:04.710  4505  4505 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 08:38:04.710  4505  4505 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:38:04.710  4505  4505 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 08:38:04.710  4505  4505 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:38:04.710  4505  4505 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 08:38:04.710  4505  4505 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 08:38:04.710  4505  4505 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 08:38:04.711  2478  2671 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 08:38:04.711  6927  6927 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 08:38:04.711  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 08:38:04.712  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 08:38:04.712  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 08:38:04.712  6927  6927 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 08:38:04.712  6927  6927 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 08:38:04.712  6927  6927 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 08:38:04.715  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:04.715  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:04.720  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 08:38:04.725  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 08:38:04.729  4613  4613 I art     : Explicit concurrent mark sweep GC freed 8412(477KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 3.242ms total 76.290ms
08-29 08:38:04.731  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 08:38:04.733  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-29 08:38:04.733  3797  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 08:38:04.734  1034  1389 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 08:38:04.735  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 08:38:04.735  1034  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:38:04.737  1034  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:38:04.737  1034  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:38:04.737  1034  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:38:04.738  1034  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 08:38:04.738  1034  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-29 08:38:04.738  1034  1439 D ConnectivityService: identical MTU - not setting
08-29 08:38:04.738  1034  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 08:38:04.738  1034  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 08:38:04.738  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 08:38:04.738  1034  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:04.739  1034  1439 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 08:38:04.739  1602  2113 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 08:38:04.754  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 08:38:04.756  1034  1923 V SIM_STK : Menu title from STK is T-Mobile
08-29 08:38:04.764  1034  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 08:38:04.787  1034  1034 D administrator: Handling package changes for user 0
,08-29 08:38:04.790  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 08:38:04.791  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 08:38:04.798  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 08:38:04.798  1602  1667 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 08:38:04.798  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.799  1906  1906 D ActionManagerService: notifyUserLog: 1000004
,08-29 08:38:04.800  3797  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 08:38:04.800  3797  4495 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 08:38:04.803  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 08:38:04.803  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , display: false
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , animation: false }
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , display: false
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , animation: false }
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , display: false
08-29 08:38:04.805  2032  2032 I GBoardWebViewUtils: , animation: false }
08-29 08:38:04.805  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 08:38:04.806  1602  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 08:38:04.806  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 08:38:04.806  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 08:38:04.809  2032  8302 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 08:38:04.810  1602  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 08:38:04.810  1602  1667 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 08:38:04.818  1602  1667 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-29 08:38:04.818  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.827  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-29 08:38:04.827  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 08:38:04.827  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 08:38:04.828  1869  1869 D SplitUIService: removed split : 
08-29 08:38:04.830  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 08:38:04.831  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-29 08:38:04.833  1602  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 08:38:04.833  1602  1667 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 08:38:04.838  1602  1667 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 08:38:04.838  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.844  1034  1994 V SIM_STK : Menu title from STK is T-Mobile
08-29 08:38:04.844  1034  1994 V SIM_STK : Menu title from STK is T-Mobile
08-29 08:38:04.845  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-29 08:38:04.845  1869  1869 I SplitUIService: split app #11
08-29 08:38:04.846  1602  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 08:38:04.861  1602  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 08:38:04.862  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 08:38:04.862  1602  1667 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 08:38:04.871  1602  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 08:38:04.871  1602  1667 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-29 08:38:04.872  1602  1667 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 08:38:04.872  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.889  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:04.890  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-29 08:38:04.897  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-29 08:38:04.897  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 08:38:04.910  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:04.911  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 08:38:04.925  8208  8278 D LgDataFeature: LgDataFeature() Constructor: none
08-29 08:38:04.926  8208  8278 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 08:38:04.944  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:04.944  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:04.949  1034  1995 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 08:38:04.949  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 08:38:04.950  7765  7765 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-29 08:38:04.959  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-29 08:38:04.961  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:04.963  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 08:38:04.964  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 08:38:04.965  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-29 08:38:04.966  1602  1667 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 08:38:04.966  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.966  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-29 08:38:04.971  1602  1667 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 08:38:04.971  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.973  1602  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 08:38:04.973  1602  1667 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 08:38:04.974  1602  1667 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 08:38:04.974  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.977  1602  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 08:38:04.977  1602  1667 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-29 08:38:04.979  1602  1667 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 08:38:04.979  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.980  1034  1976 V SIM_STK : Menu title from STK is T-Mobile
08-29 08:38:04.981  1602  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 08:38:04.981  1602  1667 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 08:38:04.983  1602  1667 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 08:38:04.983  1602  1667 D KeyguardModel: createShortcutInfo...
08-29 08:38:04.991  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 08:38:04.991  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:04.991  2032  2128 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 08:38:04.992  2032  2128 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-29 08:38:04.996  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 08:38:04.998  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-29 08:38:04.998  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 08:38:04.998  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{33131cd8 u0 com.lge.launcher2/.Launcher t5} time:141726
08-29 08:38:05.001  1034  1122 I art     : Explicit concurrent mark sweep GC freed 77611(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.174ms total 314.062ms
08-29 08:38:05.005  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 08:38:05.006  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 08:38:05.006  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 08:38:05.016  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 08:38:05.018  2578  2578 D [Concierge]Service: onStartCommand(). Type : 8
08-29 08:38:05.018  2578  2578 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 08:38:05.018  2578  2578 D [Concierge]Service: Update widget ID : 11
,08-29 08:38:05.023  2032  2032 D [Concierge]WidgetView: change position of spinner
08-29 08:38:05.026  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1472452685026
08-29 08:38:05.027  2578  2578 D [Concierge]Service: onStartCommand(). Type : 0
,08-29 08:38:05.039  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:05.041  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 347808279
08-29 08:38:05.042  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 08:38:05.042  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 08:38:05.048  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@20b175d8
08-29 08:38:05.048  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-29 08:38:05.051  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 08:38:05.051  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:05.056  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:05.056  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.058  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:38:05.058  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 08:38:05.059  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 08:38:05.061  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472452571765, New one : 1472452685026
,08-29 08:38:05.061  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-29 08:38:05.061  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 08:38:05.062  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:05.062  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:05.063  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 08:38:05.064  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.064  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 08:38:05.065  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 08:38:05.066  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 08:38:05.067  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 08:38:05.068  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:05.068  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:05.070  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 08:38:05.076  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 08:38:05.077  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 08:38:05.077  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 08:38:05.083  1034  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 08:38:05.090  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 08:38:05.094  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:05.094  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.095  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:38:05.107  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:05.108  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.110  8208  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-29 08:38:05.114  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 08:38:05.123  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 08:38:05.126  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 08:38:05.126  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 08:38:05.126  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:05.126  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 08:38:05.128  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 08:38:05.130  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:05.130  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.130  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 08:38:05.140  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:05.140  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.149  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@131cad60 time:141876
,08-29 08:38:05.151  8270  8270 D AndroidRuntime: Shutting down VM
08-29 08:38:05.156  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-29 08:38:05.162  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-29 08:38:05.175  1034  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8308 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 08:38:05.176  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 08:38:05.180  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:05.183  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 08:38:05.187  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-29 08:38:05.196  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:05.196  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.197  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:38:05.199  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-29 08:38:05.200  8208  8278 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-29 08:38:05.202  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-29 08:38:05.205  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.206  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:05.209  8208  8278 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-29 08:38:05.218  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:38:05.227  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:05.229  1034  1653 I ActivityManager: Killing 7351:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-29 08:38:05.237  1034  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 08:38:05.241  1034  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-29 08:38:05.287  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 08:38:05.306  1034  1575 W libprocessgroup: failed to open /acct/uid_10005/pid_7351/cgroup.procs: No such file or directory
,08-29 08:38:05.312  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 08:38:05.320  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:38:05.321  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.324  6978  6978 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 08:38:05.326  2032  2885 I GBoardtInterface: onReloaded()
08-29 08:38:05.328  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 08:38:05.332  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 08:38:05.333  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.334  3797  4495 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 08:38:05.338  8162  8162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 08:38:05.342  3797  3813 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 08:38:05.343  8162  8162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 08:38:05.350  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:38:05.368  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:05.371  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-29 08:38:05.375  3797  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 08:38:05.376  3797  4499 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 08:38:05.377  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 08:38:05.377  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.379  6978  6978 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 08:38:05.379  1906  1906 D ActionManagerService: notifyUserLog: 1000001
,08-29 08:38:05.380  3797  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 08:38:05.380  6978  6978 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 08:38:05.380  3797  4499 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 08:38:05.380  3797  4499 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 08:38:05.380  3797  4499 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 08:38:05.381  6978  6978 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 08:38:05.383  3797  4495 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 08:38:05.386  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 08:38:05.386  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.387  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 08:38:05.387  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 08:38:05.390  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 08:38:05.390  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 08:38:05.390  8162  8162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 08:38:05.391  8162  8162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 08:38:05.393  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 08:38:05.393  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 08:38:05.394  6927  6927 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 08:38:05.407  6927  6927 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 08:38:05.413  6978  6978 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 08:38:05.414  6978  6978 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 08:38:05.414  6978  6978 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 08:38:05.415  6978  6978 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 08:38:05.415  6978  6978 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 08:38:05.420  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 08:38:05.421  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 08:38:05.422  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 08:38:05.424  8208  8208 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 08:38:05.425  8208  8279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 08:38:05.425  1034  1887 I ActivityManager: Killing 7792:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 08:38:05.474  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 08:38:05.474  1034  1958 W libprocessgroup: failed to open /acct/uid_10072/pid_7792/cgroup.procs: No such file or directory
,08-29 08:38:05.486  2081  2081 I ConfigService: onCreate
,08-29 08:38:05.487  2081  2081 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 08:38:05.489  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 08:38:05.492  1817  3936 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-29 08:38:05.495  2081  8332 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at androi,d.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-29 08:38:05.496  2081  8332 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-29 08:38:05.497  2081  8332 W SQLiteOpenHelper: Opened config.db in read-only mode
08-29 08:38:05.498  2081  2081 I ConfigService: onBind returning update interface
,08-29 08:38:05.500  2081  2081 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 08:38:05.500  2081  2081 I ConfigService: onBind returning config service
08-29 08:38:05.505  2081  2081 I ConfigService: onDestroy
08-29 08:38:05.508  1817  8333 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:38:05.534  1817  8337 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:4,63)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
08-29 08:38:05.534  1817  8337 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 08:38:05.535  7843  7843 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error

```
