#### Test 833712394bbb446_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 03:01:18.866  4624  6676 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
--------- beginning of system
08-31 03:01:18.910  1035  1767 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6677 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 03:01:18.976  1035  1578 V SIM_STK : Menu title from STK is T-Mobile
08-31 03:01:19.153  4624  6676 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 287 ms] updated apps [took 287 ms] 
08-31 03:01:19.190  6677  6677 D DocsApplication: Installing DEX configuration.
08-31 03:01:19.209  6677  6677 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 03:01:19.213  6677  6677 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{165d7947 com.google.android.apps.docs}
08-31 03:01:19.231  6677  6677 D TAG     : onCreate()
08-31 03:01:19.254  6677  6677 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-31 03:01:20.044  6715  6715 D AndroidRuntime: 
08-31 03:01:20.044  6715  6715 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 03:01:20.047  6715  6715 D AndroidRuntime: CheckJNI is OFF
08-31 03:01:20.156  1844  4713 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-31 03:01:20.177  6715  6715 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 03:01:20.182  1035  1578 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 03:01:20.196  1969  2773 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 03:01:20.200  1035  1578 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 03:01:20.201  1035  1578 D ActivityManager: setTaskToReturnTo : TaskRecord{280d69bf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 03:01:20.201  1035  1578 D ActivityManager: setTaskToReturnTo : TaskRecord{280d69bf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 03:01:20.202  1035  1578 D WindowStateEx: AppWindowTokenEx init.. 
08-31 03:01:20.203   348   361 E GBMv2   : DFP En is all cleared set to be enabled
08-31 03:01:20.207  2791  2791 I MusicWidget: mDelayedStopHandler : unbind
08-31 03:01:20.229  1035  1578 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6736 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 03:01:20.230  6715  6715 D AndroidRuntime: Shutting down VM
08-31 03:01:20.233  2183  2183 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 03:01:20.233  2183  2183 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 03:01:20.233  2183  2183 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-31 03:01:20.240  2183  2183 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 03:01:20.241  2183  2183 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 03:01:20.241  2183  2183 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-31 03:01:20.244  2183  2183 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 03:01:20.244  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-31 03:01:20.244  1035  1051 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@f5e830ecom.lge.music.MediaPlaybackService$5@200412f
08-31 03:01:20.245  2183  2183 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 03:01:20.245  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.245  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.246  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.247  2183  2183 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@382c7055
08-31 03:01:20.247  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.247  2183  2183 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 03:01:20.248  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.248  2183  2183 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-31 03:01:20.248  2183  2183 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 03:01:20.248  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.249  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.249  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.250  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.250  2183  2183 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 03:01:20.251  2183  2183 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-31 03:01:20.252  2183  2183 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-31 03:01:20.255  2183  2183 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 03:01:20.255  2183  2183 V MediaPlayer[Native]: reset
08-31 03:01:20.279  2183  2183 V MediaPlayer[Native]: setListener
08-31 03:01:20.279  2183  2183 V MediaPlayer[Native]: disconnect
08-31 03:01:20.279  2183  2183 V MediaPlayer[Native]: destructor
08-31 03:01:20.280   328  1785 V AudioFlinger: releasing 18 from 2183 for -1
08-31 03:01:20.280   328  1785 V AudioFlinger:  decremented refcount to 0
08-31 03:01:20.280   328  1785 V AudioFlinger: purging stale effects
08-31 03:01:20.285  2183  2183 V MediaPlayer[Native]: disconnect
08-31 03:01:20.285  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 03:01:20.285  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f5e4673 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 03:01:20.286  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 03:01:20.287  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{348d3930 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 03:01:20.288  2183  2183 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-31 03:01:20.289  2183  2183 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 03:01:20.292  2183  2183 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 03:01:20.293  2183  2183 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 03:01:20.294  2183  2183 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-31 03:01:20.294  2183  2183 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 03:01:20.294  2183  2183 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 122831676
08-31 03:01:20.294  2183  2183 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 122831676
08-31 03:01:20.299  2183  2183 I SmartShareClient: [SmartShareManagerClient] terminate service: 2183/MediaPlaybackService/191783651
08-31 03:01:20.301  2183  2183 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 03:01:20.301  2183  2183 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2aeb18c5
08-31 03:01:20.310  2183  2183 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-31 03:01:20.310  2183  2183 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 03:01:20.310  2183  2183 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 03:01:20.311  2183  2183 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 03:01:20.311  1035  1993 I ActivityManager: Killing 5526:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 03:01:20.312  2183  2183 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
08-31 03:01:20.340  1844  4713 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-31 03:01:20.468  1035  1597 W libprocessgroup: failed to open /acct/uid_10005/pid_5526/cgroup.procs: No such file or directory
,08-31 03:01:20.478  6736  6736 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 03:01:20.540  1844  4713 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-31 03:01:20.556  6736  6736 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-31 03:01:20.564  6736  6736 I LibraryLoader: Loading: webviewchromium
08-31 03:01:20.567  6736  6736 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7617-7620)
,08-31 03:01:20.567  6736  6736 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 03:01:20.604  6736  6736 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5453399}
08-31 03:01:20.606  6736  6736 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 03:01:20.607  6736  6736 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 03:01:20.628  6736  6736 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 03:01:20.630  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 03:01:20.648  6736  6736 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 03:01:20.649  6736  6736 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 03:01:20.649  6736  6736 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-31 03:01:20.660   328  1392 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-31 03:01:20.665  1035  1109 D BluetoothManagerService: Message: 20
08-31 03:01:20.665  1035  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@133ee051:true
,08-31 03:01:20.684  6736  6736 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 03:01:20.684  6736  6736 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 03:01:20.684  6736  6736 I Adreno-EGL: Build Date: 12/12/14 금
08-31 03:01:20.684  6736  6736 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 03:01:20.684  6736  6736 I Adreno-EGL: Remote Branch: 
08-31 03:01:20.684  6736  6736 I Adreno-EGL: Local Patches: 
08-31 03:01:20.684  6736  6736 I Adreno-EGL: Reconstruct Branch: 
,08-31 03:01:20.784  1035  1092 W ActivityManager: Activity pause timeout for ActivityRecord{2ca8688c u0 com.test.thalitest/.MainActivity t6}
,08-31 03:01:20.799  6736  6777 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-31 03:01:20.801  6736  6736 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 03:01:20.815  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 03:01:20.821  6736  6736 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 03:01:20.824  6736  6736 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 03:01:20.827  6736  6736 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 03:01:20.827  6736  6736 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 03:01:20.839  6736  6736 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 03:01:20.844  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 03:01:20.844  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 03:01:20.898  6736  6797 D OpenGLRenderer: Render dirty regions requested: true
08-31 03:01:20.898  6736  6797 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 03:01:20.903  6736  6797 D OpenGLRenderer: Enabling debug mode 0
08-31 03:01:20.909  6736  6736 D Atlas   : Validating map...
08-31 03:01:20.912  1035  2017 D SplitWindow: check instance of lgWin Window{f50f643 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 03:01:20.932  6736  6791 D LgDataFeature: LgDataFeature() Constructor: none
08-31 03:01:20.932  6736  6791 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 03:01:20.992  1035  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +708ms (total +788ms)
08-31 03:01:20.993  1035  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2ca8688c u0 com.test.thalitest/.MainActivity t6} time:108047
,08-31 03:01:20.997  6736  6736 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@752433c time:108051
08-31 03:01:21.074  6677  6677 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 03:01:21.074  6677  6677 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 03:01:21.113  6736  6736 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 03:01:21.113  6736  6736 I chromium: 
,08-31 03:01:21.130  6736  6736 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 03:01:21.190  6192  6192 I LockScreenSettings: New app installed broadcast received ..
08-31 03:01:21.191  6192  6192 I LockScreenSettings: Number of installed packages  1
08-31 03:01:21.198  6677  6677 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-31 03:01:21.233  1035  2055 V SIM_STK : Menu title from STK is T-Mobile
,08-31 03:01:21.236  6736  6810 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
08-31 03:01:21.257  6736  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 03:01:21.257  6736  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 03:01:21.257  6736  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 03:01:21.257  6736  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 03:01:21.257  6736  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 03:01:21.257  6736  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fae340 added. We now have 1 listener(s)
,08-31 03:01:21.267  1035  2117 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6819 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 03:01:21.268  1035  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 03:01:21.270  6736  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 03:01:21.271  6736  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 03:01:21.272  6736  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 03:01:21.272  6736  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 03:01:21.278  6736  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@289d41f added. We now have 1 listener(s)
08-31 03:01:21.278  6736  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 03:01:21.281  1035  1546 D WifiService: New client listening to asynchronous messages
08-31 03:01:21.284  6736  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 03:01:21.284  6736  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 03:01:21.284  6736  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 03:01:21.284  6736  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 03:01:21.284  6736  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 03:01:21.287  6736  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 03:01:21.287  1035  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 03:01:21.288  6736  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 03:01:21.296  6736  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:01:21.296  6736  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 03:01:21.296  6736  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 03:01:21.296  6736  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 03:01:21.297  6736  6810 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 03:01:21.299  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 03:01:21.301  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 03:01:21.330  6736  6791 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 03:01:21.330  6736  6791 I chromium: 
,08-31 03:01:21.350  6819  6819 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 03:01:21.351  6819  6819 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-31 03:01:21.401  6736  6736 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 03:01:21.406  1035  2116 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6840 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 03:01:21.407  1035  2116 I ActivityManager: Killing 5946:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 03:01:21.578  1035  1050 W libprocessgroup: failed to open /acct/uid_10072/pid_5946/cgroup.procs: No such file or directory
,08-31 03:01:21.649  6840  6840 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-31 03:01:21.667  6840  6840 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 03:01:21.672  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 03:01:21.727  1035  2096 I ActivityManager: Killing 5734:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-31 03:01:21.742   348   363 E GBMv2   : DFP En is all cleared set to be enabled
08-31 03:01:21.742   348   363 E GBMv2   : Set value is all cleared set the max
08-31 03:01:21.742   348   363 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 03:01:21.768  5710  5710 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-31 03:01:21.769  5710  5710 W System.err: android.os.DeadObjectException
08-31 03:01:21.770  5710  5710 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 03:01:21.770  5710  5710 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 03:01:21.770  5710  5710 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 03:01:21.770  5710  5710 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 03:01:21.770  5710  5710 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:21.770  5710  5710 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:01:21.770  5710  5710 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 03:01:21.770  5710  5710 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 03:01:21.770  5710  5710 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 03:01:21.770  5710  5710 W System.err: android.os.DeadObjectException
08-31 03:01:21.771  5710  5710 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 03:01:21.771  5710  5710 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 03:01:21.771  5710  5710 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 03:01:21.771  5710  5710 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 03:01:21.771  5710  5710 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:21.771  5710  5710 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:01:21.771  5710  5710 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 03:01:21.771  5710  5710 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 03:01:21.771  5710  5710 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 03:01:21.772  5710  5710 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 03:01:21.978  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_5734/cgroup.procs: No such file or directory
,08-31 03:01:21.979  1035  1051 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-31 03:01:21.981  5710  5710 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 03:01:21.981  5710  5710 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 03:01:22.033  1035  2117 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6862 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 03:01:22.034  5710  5710 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 03:01:22.090  6862  6862 D UEI.SmartControl: Quickset Services start...
08-31 03:01:22.092  6862  6862 I UEI.SmartControl: Manufacture = LGE
08-31 03:01:22.092  6862  6862 D UEI.SmartControl: Id = LGNevo
,08-31 03:01:22.093  6862  6862 D UEI.SmartControl: File observer start...
08-31 03:01:22.095  6862  6862 E UEI.SmartControl: IR Port is disabled: false
08-31 03:01:22.095  6862  6862 D UEI.SmartControl: Starting file observer...
08-31 03:01:22.095  6862  6862 D UEI.SmartControl: Extracting JNI libs...
08-31 03:01:22.095  6862  6862 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 03:01:22.140  6736  6838 W jxcore-log: Initializing JXcore engine
08-31 03:01:22.140  6736  6838 W jxcore-log: JXcore engine is ready
,08-31 03:01:22.180  6862  6862 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 03:01:22.180  6862  6862 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 03:01:22.180  6862  6862 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 03:01:22.176  6838  6838 W Thread-766: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9810]" dev="sockfs" ino=9810 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 03:01:22.176  6838  6838 W Thread-766: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 03:01:22.176  6838  6838 W Thread-766: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8769]" dev="sockfs" ino=8769 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 03:01:22.176  6838  6838 W Thread-766: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 03:01:22.176  6838  6838 W Thread-766: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30450]" dev="sockfs" ino=30450 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 03:01:22.199  6736  6838 W jxcore-log: Starting JXcore engine
,08-31 03:01:22.230  6862  6862 I UEI.SmartControl: --- Selecting new region: 6
,08-31 03:01:22.236  6862  6862 I UEI.SmartControl: Model = LG-D855
08-31 03:01:22.238  6862  6862 D UEI.SmartControl: QS Service created
08-31 03:01:22.261  6862  6862 I UEI.SmartControl: Service initServices...
,08-31 03:01:22.268  6862  6862 D UEI.SmartControl: QS start get config
08-31 03:01:22.340  6862  6862 D UEI.SmartControl: Loading JNI Libs...
,08-31 03:01:22.368  6736  6838 W jxcore-log: Platform android
08-31 03:01:22.368  6736  6838 W jxcore-log: 
08-31 03:01:22.368  6736  6838 W jxcore-log: Process ARCH arm
08-31 03:01:22.368  6736  6838 W jxcore-log: 
,08-31 03:01:22.618  6736  6838 I jxcore-log: JXcore Cordova bridge is ready!
08-31 03:01:22.618  6736  6838 I jxcore-log: 
08-31 03:01:22.619  6736  6838 W jxcore-log: JXcore engine is started
,08-31 03:01:22.626  6736  6810 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 03:01:22.630  6736  6736 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 03:01:22.711  6862  6862 I UEI.SmartControl: Supports setup maps: true
,08-31 03:01:22.717  6862  6862 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 03:01:22.717  6862  6862 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 03:01:22.718  6862  6862 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 03:01:22.718  6862  6862 I UEI.SmartControl: ### init IR Blaster...
08-31 03:01:22.723  6862  6862 D serial_port: Configuring serial port
,08-31 03:01:22.729  6862  6862 E UEI.SmartControl: UEIBLaster setting for 616
08-31 03:01:22.729  6862  6862 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 03:01:22.729  6862  6862 I UEI.SmartControl: configuring settings for MAXQ616
08-31 03:01:22.730  6862  6862 I UEI.SmartControl: Get version...
08-31 03:01:22.746  6862  6880 D UEI.SmartControl: serial port data available: 21
,08-31 03:01:22.773  6862  6862 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 03:01:22.774  6862  6862 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 03:01:22.774  6862  6862 I UEI.SmartControl: QS saving settings...
08-31 03:01:22.775  6862  6862 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 03:01:22.793  6862  6880 D UEI.SmartControl: serial port data available: 4
,08-31 03:01:22.830  6862  6883 I UEI.SmartControl: Device manager: loading config....
,08-31 03:01:22.833  6862  6883 D UEI.SmartControl: ----------- loading internal config...
,08-31 03:01:22.834  6862  6862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 03:01:22.837  6862  6862 E UEI.SmartControl: Services init done
08-31 03:01:22.838  6862  6862 D UEI.SmartControl: QS Service init finished
08-31 03:01:22.839  6862  6862 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 03:01:22.840  6862  6862 D UEI.SmartControl: QS Service version code: 201091
08-31 03:01:22.844  6862  6862 D UEI.SmartControl: Service requested: Control
,08-31 03:01:22.847  6862  6883 E UEI.SmartControl: Loading SETTINGS...
08-31 03:01:22.849  6862  6862 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 03:01:22.851  5710  5710 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 03:01:22.854  6862  6877 I UEI.SmartControl: ------ IControl API: 11
08-31 03:01:22.856  6862  6883 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 03:01:22.856  1035  1932 I ActivityManager: Killing 5710:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 03:01:22.857  6862  6877 I UEI.SmartControl: Registering callback...
08-31 03:01:22.866  6862  6882 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 03:01:22.867  6862  6882 D UEI.SmartControl: -----service ready thread exits
,08-31 03:01:22.927  6862  6862 D UEI.SmartControl: Internal service binding...
08-31 03:01:22.927  1035  2096 W libprocessgroup: failed to open /acct/uid_10112/pid_5710/cgroup.procs: No such file or directory
,08-31 03:01:25.151  6677  6677 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 03:01:25.157  1035  2017 I ActivityManager: Killing 6338:com.android.calendar/u0a13 (adj 15): empty #17
08-31 03:01:25.264  1035  1932 W libprocessgroup: failed to open /acct/uid_10013/pid_6338/cgroup.procs: No such file or directory
,08-31 03:01:26.148  6677  6802 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 03:01:27.816  6862  6881 D serial_port: close(fd = 25)
,08-31 03:01:27.823  6862  6881 I UEI.SmartControl: Serial port is closed.
08-31 03:01:27.829  6862  6884 D UEI.SmartControl: Internal timer expired: 1
08-31 03:01:27.830  6862  6884 D UEI.SmartControl: unbind internal service
,08-31 03:01:27.841  6862  6862 D UEI.SmartControl: Service.onUnbind: IControl
08-31 03:01:27.842  6862  6862 D UEI.SmartControl: Service.onDestroy
08-31 03:01:27.842  6862  6862 D UEI.SmartControl: Lock is in USE false
08-31 03:01:27.842  6862  6862 D UEI.SmartControl: unbind internal service
08-31 03:01:27.843  6862  6862 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@382c7055
08-31 03:01:27.844  6862  6862 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 03:01:27.844  6862  6862 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 03:01:27.844  6862  6862 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 03:01:27.844  6862  6862 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 03:01:27.844  6862  6862 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 03:01:27.844  6862  6862 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 03:01:27.844  6862  6862 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 03:01:27.844  6862  6862 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 03:01:27.844  6862  6862 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:01:27.845  6862  6862 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 03:01:27.845  6862  6862 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 03:01:27.845  6862  6862 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:27.845  6862  6862 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:01:27.845  6862  6862 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 03:01:27.845  6862  6862 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 03:01:27.845  6862  6862 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@382c7055
08-31 03:01:27.845  6862  6862 I UEI.SmartControl: Serial port is closed.
08-31 03:01:27.845  6862  6862 I UEI.SmartControl: Serial port is closed.
,08-31 03:01:27.853  6862  6862 D UEI.SmartControl: Blaster closed
,08-31 03:01:27.854  6862  6862 D UEI.SmartControl: Shut down QS...
08-31 03:01:27.855  6862  6862 D UEI.SmartControl: Stopping QS lib
08-31 03:01:27.855  6862  6862 D UEI.SmartControl: QS lib stop result = true
08-31 03:01:27.855  6862  6862 D UEI.SmartControl: Stopped QS lib
08-31 03:01:27.856  6862  6862 D UEI.SmartControl: Stopped file observer...
08-31 03:01:27.856  6862  6862 D UEI.SmartControl: QS shutdown complete
,08-31 03:01:30.317  2183  2183 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19994
,08-31 03:01:33.152  1035  1092 I ActivityManager: Waited long enough for: ServiceRecord{1d6fa53d u0 com.google.android.gms/.wearable.service.WearableService}
,08-31 03:01:36.390  6736  6838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 03:01:36.390  6736  6838 I jxcore-log: 
,08-31 03:01:36.394  6736  6838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 03:01:36.394  6736  6838 I jxcore-log: 
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:01:36.399  6736  6838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 03:01:36.402  6736  6838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 03:01:36.404  6736  6838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 03:01:36.404  6736  6838 I jxcore-log: 
,08-31 03:01:36.406  6736  6838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 03:01:36.406  6736  6838 I jxcore-log: 
,08-31 03:01:36.752  6736  6838 I jxcore-log: Running unit tests
08-31 03:01:36.752  6736  6838 I jxcore-log: 
,08-31 03:01:36.753  6736  6838 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests,
,08-31 03:01:36.753  6736  6838 I jxcore-log: Failed to execute UT.
08-31 03:01:36.753  6736  6838 I jxcore-log: 
,08-31 03:01:36.755  6736  6838 I jxcore-log: Unit Test app is loaded
08-31 03:01:36.755  6736  6838 I jxcore-log: 
,08-31 03:01:36.761  6736  6838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 03:01:36.761  6736  6838 I jxcore-log: 
08-31 03:01:36.766  6736  6838 I jxcore-log: My device name is: LGE-LG-D855
08-31 03:01:36.766  6736  6838 I jxcore-log: 
08-31 03:01:36.767  6736  6838 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 03:01:36.767  6736  6838 I jxcore-log: 
,08-31 03:01:36.781  6736  6736 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 03:01:37.117  1035  1380 V AlarmManager: RTC_WAKEUP set : Alarm{17497487 type 0 when 1472605293789 com.android.vending} when 1472605293789
,08-31 03:01:37.184  1035  2017 V SIM_STK : Menu title from STK is T-Mobile
,08-31 03:01:37.191  4515  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-31 03:01:37.449  6153  6153 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 03:01:39.300  6736  6838 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 03:01:39.300  6736  6838 I jxcore-log: 
,08-31 03:01:39.748  6736  6838 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 03:01:39.748  6736  6838 I jxcore-log: 
,08-31 03:01:39.774  6736  6838 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 03:01:39.774  6736  6838 I jxcore-log: 
,08-31 03:01:41.132  6736  6838 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 03:01:41.132  6736  6838 I jxcore-log: 
,08-31 03:01:41.365  6736  6838 I jxcore-log: ERROR runTests: 
08-31 03:01:41.365  6736  6838 I jxcore-log: 
,08-31 03:01:41.368  6736  6838 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:01:41.368  6736  6838 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 03:01:41.370  6736  6838 I jxcore-log: WARN testUtils: logCallback not set!
08-31 03:01:41.370  6736  6838 I jxcore-log: 
,08-31 03:01:41.380  6736  6838 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _functionName: 'loadFile',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _lineNumber: '26',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _columnNumber: '11',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 03:01:41.380  6736  6838 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _functionName: '',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _lineNumber: '38',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _columnNumber: '7',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 03:01:41.380  6736  6838 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _functionName: '',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _lineNumber: '35',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _columnNumber: '3',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 03:01:41.380  6736  6838 I jxcore-log:   { _fileName: 'module.js',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _lineNumber: '621',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _columnNumber: '8',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 03:01:41.380  6736  6838 I jxcore-log:   { _fileName: 'module.js',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _lineNumber: '651',
08-31 03:01:41.380  6736  6838 I jxcore-log:     _columnNumber: '1',
08-31 03:01:41.380  6736  6838 I jxcore-log:    
,08-31 03:01:41.380  6736  6838 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 03:01:41.380  6736  6838 I jxcore-log: 
08-31 03:01:41.380  6736  6838 E jxcore-log: Error: 
,08-31 03:01:41.380  6736  6838 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:01:41.380  6736  6838 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 03:01:41.380  6736  6838 E jxcore-log: 
,08-31 03:01:41.732  6916  6916 D AndroidRuntime: 
08-31 03:01:41.732  6916  6916 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 03:01:41.739  6916  6916 D AndroidRuntime: CheckJNI is OFF
08-31 03:01:41.950  6916  6916 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 03:01:41.968  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 03:01:41.968  1035  1092 I ActivityManager: Killing 6736:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-31 03:01:42.050  1035  1578 I WindowState: WIN DEATH: Window{f50f643 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 03:01:42.053  1035  1546 D WifiService: Client connection lost with reason: 4
08-31 03:01:42.064  1035  1578 D InputDispatcher: Window went away: Window{f50f643 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 03:01:42.118  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{2ca8688c u0 com.test.thalitest/.MainActivity t6}
,08-31 03:01:42.186   348   361 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 03:01:42.203  1035  1932 W ActivityManager: Spurious death for ProcessRecord{3331efb4 6736:com.test.thalitest/u0a118}, curProc for 6736: null
,08-31 03:01:42.237  2098  2098 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 03:01:42.238  2098  2098 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-31 03:01:42.242  2098  2098 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 03:01:42.244  2098  2182 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-31 03:01:42.250  1933  1933 D ActionManagerService: notifyUserLog: 1000003
,08-31 03:01:42.252  3803  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 03:01:42.253  2098  2098 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-31 03:01:42.255  2098  2098 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 03:01:42.269  2098  2098 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 03:01:42.271  1969  2773 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-31 03:01:42.272  1969  2773 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12ae29a9 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 03:01:42.276  2098  2098 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 03:01:42.277  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 03:01:42.278  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{268f6b2e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 03:01:42.286  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-31 03:01:42.286  2098  2098 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 03:01:42.287  1933  1933 D ActionManagerService: notifyUserLog: 1000004
08-31 03:01:42.288  3803  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 03:01:42.288  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{2ca8688c u0 com.test.thalitest/.MainActivity t6 f}
08-31 03:01:42.289  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2ca8688c u0 com.test.thalitest/.MainActivity t6 f}
,08-31 03:01:42.337  4624  4624 I art     : Explicit concurrent mark sweep GC freed 455(31KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 642us total 38.032ms
,08-31 03:01:42.341  3803  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-31 03:01:42.349  1585  1585 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 03:01:42.360  1035  1382 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 03:01:42.365  2500  2634 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 03:01:42.367  3855  3855 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 03:01:42.367  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 03:01:42.371  2041  2041 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 03:01:42.372  3803  3803 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-31 03:01:42.421  4515  4515 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-31 03:01:42.424  4515  4515 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 03:01:42.424  4515  4515 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 03:01:42.424  4515  4515 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 03:01:42.424  4515  4515 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:01:42.424  4515  4515 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:01:42.424  4515  4515 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 03:01:42.425  4515  4515 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 03:01:42.425  4515  4515 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:42.425  4515  4515 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:01:42.425  4515  4515 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 03:01:42.425  4515  4515 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 03:01:42.441  1898  1898 D SplitUIManager: split_name #11 / not available #0
08-31 03:01:42.442  1898  1898 D SplitUIService: removed split : 
,08-31 03:01:42.457  1035  1092 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6951 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 03:01:42.462  1585  1585 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , expire_time: 0
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , display: false
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , animation: false }
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , expire_time: 0
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , display: false
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , animation: false }
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , expire_time: 0
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , display: false
08-31 03:01:42.463  2098  2098 I GBoardWebViewUtils: , animation: false }
08-31 03:01:42.463  1585  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 03:01:42.463  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.465  2098  6961 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 03:01:42.479  1585  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 03:01:42.479  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.483  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 03:01:42.483  1585  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 03:01:42.483  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 03:01:42.486  1898  1898 D SplitUIManager: split_name #11 / not available #0
08-31 03:01:42.486  1898  1898 I SplitUIService: split app #11
,08-31 03:01:42.489  2098  2098 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 03:01:42.489  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 03:01:42.492  1585  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 03:01:42.493  1585  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 03:01:42.493  1035  1035 I art     : Explicit concurrent mark sweep GC freed 36160(2011KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.025ms total 166.774ms
08-31 03:01:42.493  1035  2096 I art     : WaitForGcToComplete blocked for 99.497ms for cause Explicit
08-31 03:01:42.504  1585  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 03:01:42.504  1585  1650 D KeyguardModel: createShortcutInfo...
,08-31 03:01:42.522  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 03:01:42.522  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 03:01:42.527  1585  1585 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 03:01:42.527  1585  1585 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 03:01:42.530  1585  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 03:01:42.531  1585  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 03:01:42.532  1585  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 03:01:42.532  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.535  1585  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 03:01:42.536  1585  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 03:01:42.536  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 03:01:42.536  1585  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 03:01:42.536  1585  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 03:01:42.536  1585  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-31 03:01:42.538  1585  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 03:01:42.538  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.556  1585  1585 D KeyguardModel: handleShortcutListChanged...
08-31 03:01:42.556  1585  1585 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 03:01:42.562  1585  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 03:01:42.562  1585  1650 D KeyguardModel: createShortcutInfo...
,08-31 03:01:42.565  2098  2098 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 03:01:42.565  1585  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 03:01:42.565  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.568  2098  2098 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 03:01:42.589  1585  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 03:01:42.590  1585  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-31 03:01:42.600  2098  2113 I art     : Background partial concurrent mark sweep GC freed 6922(305KB) AllocSpace objects, 3(324KB) LOS objects, 28% free, 79MB/111MB, paused 18.722ms total 41.716ms
,08-31 03:01:42.603  1585  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 03:01:42.603  1585  1650 D KeyguardModel: createShortcutInfo...
,08-31 03:01:42.617  6951  6951 I art     : Almond Protected OAT
08-31 03:01:42.618  1585  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 03:01:42.618  1585  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-31 03:01:42.619  1035  1992 V SIM_STK : Menu title from STK is T-Mobile
08-31 03:01:42.619  1035  1992 V SIM_STK : Menu title from STK is T-Mobile
08-31 03:01:42.620  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-31 03:01:42.621  1585  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 03:01:42.621  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.622  1035  1035 D administrator: Handling package changes for user 0
08-31 03:01:42.624  1585  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 03:01:42.624  1585  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 03:01:42.625  1035  2096 I art     : Explicit concurrent mark sweep GC freed 3994(388KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.733ms total 129.127ms
08-31 03:01:42.626  1585  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 03:01:42.626  1585  1650 D KeyguardModel: createShortcutInfo...
08-31 03:01:42.636  1035  1124 I art     : WaitForGcToComplete blocked for 289.933ms for cause Explicit
,08-31 03:01:42.636  1585  1585 D KeyguardModel: handleShortcutListChanged...
08-31 03:01:42.638  1585  1585 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 03:01:42.659  2098  2098 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-31 03:01:42.662  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 03:01:42.664  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 03:01:42.665  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 03:01:42.666  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 03:01:42.667  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 03:01:42.668  1035  2091 V SIM_STK : Menu title from STK is T-Mobile
08-31 03:01:42.681  1035  1594 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 03:01:42.681  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-31 03:01:42.684  6951  6951 D WeatherApplication: removeAccount
08-31 03:01:42.686  2098  2098 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 03:01:42.686  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.688  2098  2202 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 03:01:42.688  2098  2202 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 03:01:42.696  6951  6951 D WeatherApplication: Account.length = 0
,08-31 03:01:42.696  6951  6951 E WeatherApplication: OPERATOR:OPEN
08-31 03:01:42.700  6951  6951 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:1:42
08-31 03:01:42.701  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 03:01:42.702  2098  2098 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 03:01:42.702  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.703  1035  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21173eec u0 com.lge.launcher2/.Launcher t5} time:129757
08-31 03:01:42.705  6951  6951 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 03:01:42.705  6951  6951 D Weather.Utils: 2 : All the weather widget is gone.
08-31 03:01:42.707  6951  6951 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 03:01:42.709  6951  6951 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 03:01:42.709  6951  6951 D Weather.Utils: 2 : All the weather widget is gone.
08-31 03:01:42.709  6951  6951 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:1:42
08-31 03:01:42.713  2098  2098 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 03:01:42.718  6543  6543 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 03:01:42.720  2598  2598 D [Concierge]Service: onStartCommand(). Type : 8
08-31 03:01:42.720  2598  2598 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 03:01:42.721  2598  2598 D [Concierge]Service: Update widget ID : 11
08-31 03:01:42.722  2098  2098 D [Concierge]WidgetView: change position of spinner
,08-31 03:01:42.724  1035  2096 I ActivityManager: Killing 6298:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-31 03:01:42.745  1035  2017 V SIM_STK : Menu title from STK is T-Mobile
,08-31 03:01:42.777  1844  1844 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-31 03:01:42.788  1035  2091 W libprocessgroup: failed to open /acct/uid_10014/pid_6298/cgroup.procs: No such file or directory
,08-31 03:01:42.789  1035  1124 I art     : Explicit concurrent mark sweep GC freed 6918(415KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.721ms total 151.206ms
08-31 03:01:42.789  2098  2098 I [Concierge]WidgetView: initWebView(). Time : 1472605302789
08-31 03:01:42.790  2598  2598 D [Concierge]Service: onStartCommand(). Type : 0
08-31 03:01:42.800  2267  2267 I ConfigService: onCreate
,08-31 03:01:42.800  2267  2267 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 03:01:42.806  2267  2267 I ConfigService: onBind returning update interface
08-31 03:01:42.807  1844  1844 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 03:01:42.809  2267  2267 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 03:01:42.809  2267  2267 I ConfigService: onBind returning config service
08-31 03:01:42.809  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 03:01:42.809  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 03:01:42.810  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 03:01:42.812  1035  1582 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-31 03:01:42.822  1844  1844 I ConfigFetchService: service connected
,08-31 03:01:42.825  2267  2267 I ConfigService: onDestroy
08-31 03:01:42.829  1844  6974 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 03:01:42.831  2098  2098 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 573117176
08-31 03:01:42.831  2098  2098 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 03:01:42.832  2098  2098 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 03:01:42.835  2098  2098 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@179e7fc7
08-31 03:01:42.835  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-31 03:01:42.837  2098  2098 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 03:01:42.837  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.842  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 03:01:42.843  2098  2098 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 03:01:42.843  2098  2098 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472605201623, New one : 1472605302789
08-31 03:01:42.844  2098  2098 D [Concierge]WidgetView: Unregister all receivers
08-31 03:01:42.844  2098  2098 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 03:01:42.845  2098  2098 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 03:01:42.845  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.848  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 03:01:42.849  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 03:01:42.850  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 03:01:42.851  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 03:01:42.853  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-31 03:01:42.854  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.855  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.860  6018  6979 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-31 03:01:42.883  1844  6981 I PeopleContactsSync: CP2 sync disabled
,08-31 03:01:42.888  2098  2098 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 03:01:42.894  1844  6980 W GmsApplication: Using Auth Proxy for data requests.
08-31 03:01:42.896  2098  2098 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-31 03:01:42.897  2098  2098 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 03:01:42.898  2098  2098 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 03:01:42.899  1844  6980 W GmsApplication: Using Auth Proxy for data requests.
08-31 03:01:42.901  1844  4713 I Icing   : doRemovePackageData com.test.thalitest
08-31 03:01:42.918  2098  2098 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@122392c9 time:129972
,08-31 03:01:42.931  6916  6916 D AndroidRuntime: Shutting down VM
,08-31 03:01:42.949  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 03:01:42.954  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-31 03:01:42.970  2098  2098 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 03:01:42.979  6085  6085 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-31 03:01:42.991  6637  6637 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-31 03:01:42.992  2203  6984 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 03:01:43.005  2041  2041 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-31 03:01:43.005  2041  2041 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-31 03:01:43.007  2041  2041 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-31 03:01:43.012  6543  6543 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 03:01:43.070  1035  2116 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6987 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 03:01:43.097  2098  2098 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-31 03:01:43.099   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 32.352ms
08-31 03:01:43.116   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 330us total 16.230ms
,08-31 03:01:43.132   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 14.711ms
,08-31 03:01:43.137  2098  2905 I GBoardtInterface: onReloaded()
08-31 03:01:43.138  2098  2098 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 03:01:43.139  6987  6987 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 03:01:43.139  6987  6987 W LG Account v2.2: No ProfileInfo entries
08-31 03:01:43.139  6987  6987 I LG Account v2.2: isEnabled: false
08-31 03:01:43.139  6987  6987 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 03:01:43.139  6987  6987 I Feature : [Lifetracker]Country: EU
08-31 03:01:43.139  6987  6987 I Feature : [Lifetracker]Operator: OPEN
08-31 03:01:43.139  6987  6987 I Feature : [Lifetracker]Ranking support: false
08-31 03:01:43.139  6987  6987 I Feature : [Lifetracker]Comfort support: false
08-31 03:01:43.139  6987  6987 I Feature : [Lifetracker]Accessory: true
08-31 03:01:43.140  3803  4499 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 03:01:43.141  6987  6987 I Feature : [Lifetracker]Health device: true
08-31 03:01:43.141  6987  6987 I Feature : [Lifetracker]Extra Pedometer: false
08-31 03:01:43.141  6987  6987 I Feature : [Lifetracker]Blood glucose device: false
08-31 03:01:43.141  6987  6987 I Feature : [Lifetracker]Device Number: 3
08-31 03:01:43.141  6987  6987 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-31 03:01:43.142  3803  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-31 03:01:43.174  1035  1051 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 03:01:43.175  1035  1051 I ActivityManager: Killing 6399:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-31 03:01:43.198  1035  1124 W ActivityManager: Application dead when creating service ServiceRecord{3c86558 u0 com.android.defcontainer/.DefaultContainerService}
08-31 03:01:43.198  1035  1124 W libprocessgroup: failed to open /acct/uid_10004/pid_6399/cgroup.procs: No such file or directory
08-31 03:01:43.199  1035  1124 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 1000ms
,08-31 03:01:43.202  1035  1124 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 4000ms
08-31 03:01:43.203  1035  2055 W ActivityManager: Spurious death for ProcessRecord{254426b1 0:com.android.defcontainer/u0a4}, curProc for 6399: null
08-31 03:01:43.218  1933  1933 D ActionManagerService: notifyUserLog: 1000001
,08-31 03:01:43.219  3803  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 03:01:43.219  3803  4505 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 03:01:43.223  1933  1933 D ActionManagerService: notifyUserLog: 1000001
08-31 03:01:43.224  3803  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 03:01:43.224  3803  4505 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 03:01:43.224  3803  4505 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-31 03:01:43.225  3803  4505 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-31 03:01:43.225  3803  4499 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 03:01:43.227  2098  2098 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-31 03:01:43.227  2098  2098 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-31 03:01:43.229  2098  2098 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-31 03:01:43.229  2098  2098 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 03:01:43.231  2098  2098 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-31 03:01:43.232  2098  2098 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-31 03:01:43.232  7006  7006 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 03:01:43.232  7006  7006 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 03:01:43.232  7006  7006 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 03:01:43.233  7006  7006 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 03:01:43.234  7006  7006 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 03:01:43.234  7006  7006 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 03:01:43.271  70,06  7006 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 03:01:43.271  7006  7006 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 03:01:43.272  7006  7006 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-31 03:01:43.272  7006  7006 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:01:43.272  7006  7006 E AndroidRuntime: Process: com.android.settings, PID: 7006
08-31 03:01:43.272  7006  7006 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-31 03:01:43.272  7006  7006 E AndroidRuntime: 	... 11 more
08-31 03:01:43.281  7006  7006 I Process : Sending signal. PID: 7006 SIG: 9
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: Can't write: system_app_crash
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:01:43.284  1035  7025 E DropBoxManagerService: 	... 5 more
,08-31 03:01:43.331   281   778 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
