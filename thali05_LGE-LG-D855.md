#### Test 757892681403989_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-05 12:00:09.674  6696  6696 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-05 12:00:09.734  4634  6743 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 144 ms] updated apps [took 144 ms] 
07-05 12:00:09.782  6744  6744 D DocsApplication: Installing DEX configuration.
07-05 12:00:09.802  6744  6744 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-05 12:00:09.808  6744  6744 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{6c25e03 com.google.android.apps.docs}
07-05 12:00:09.826  6744  6744 D TAG     : onCreate()
,07-05 12:00:09.850  6744  6744 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-05 12:00:10.743  1845  4774 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-05 12:00:10.747  6772  6772 D AndroidRuntime: 
07-05 12:00:10.747  6772  6772 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:00:10.749  6772  6772 D AndroidRuntime: CheckJNI is OFF
07-05 12:00:10.802  1845  4774 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-05 12:00:10.877  6772  6772 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 12:00:10.881  1032  2023 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:00:10.889  1845  4774 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-05 12:00:10.889  1974  2169 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-05 12:00:10.892  1032  2023 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-05 12:00:10.892  1032  2023 D ActivityManager: setTaskToReturnTo : TaskRecord{305d432 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:00:10.893  1032  2023 D ActivityManager: setTaskToReturnTo : TaskRecord{305d432 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:00:10.894  1032  2023 D WindowStateEx: AppWindowTokenEx init.. 
07-05 12:00:10.894   342   353 E GBMv2   : DFP En is all cleared set to be enabled
07-05 12:00:10.932  1032  2023 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6797 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:00:10.934  6772  6772 D AndroidRuntime: Shutting down VM
07-05 12:00:10.972  1974  1990 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-05 12:00:10.973  1974  1990 D SplitWindowPolicy: topRunningActivity=ActivityInfo{212e1bef co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 12:00:10.974  1974  1991 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-05 12:00:10.974  1974  1991 D SplitWindowPolicy: topRunningActivity=ActivityInfo{36fee6fc co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 12:00:11.012  6797  6797 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 12:00:11.072  6797  6797 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-05 12:00:11.080  6797  6797 I LibraryLoader: Loading: webviewchromium
07-05 12:00:11.083  6797  6797 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8787-8790)
07-05 12:00:11.083  6797  6797 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:11.105  6797  6797 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26b39275}
07-05 12:00:11.106  6797  6797 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:11.106  6797  6797 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:00:11.112  6797  6797 I BrowserStartupController: Initializing chromium process, renderers=0
07-05 12:00:11.113  6797  6797 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:11.122  6797  6797 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-05 12:00:11.122  6797  6797 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,07-05 12:00:11.123  6797  6797 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-05 12:00:11.123   317  1785 V AudioPolicyService: registerClient() client 0xb0410340, uid 10118
07-05 12:00:11.128  1032  1097 D BluetoothManagerService: Message: 20
07-05 12:00:11.128  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3edf7f2c:true
07-05 12:00:11.135  6797  6797 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:00:11.135  6797  6797 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:00:11.135  6797  6797 I Adreno-EGL: Build Date: 12/12/14 금
07-05 12:00:11.135  6797  6797 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-05 12:00:11.135  6797  6797 I Adreno-EGL: Remote Branch: 
07-05 12:00:11.135  6797  6797 I Adreno-EGL: Local Patches: 
07-05 12:00:11.135  6797  6797 I Adreno-EGL: Reconstruct Branch: 
07-05 12:00:11.183  6797  6828 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-05 12:00:11.184  6797  6797 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-05 12:00:11.201  6797  6797 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:00:11.205  6797  6797 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 12:00:11.208  6797  6797 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 12:00:11.210  6797  6797 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 12:00:11.210  6797  6797 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 12:00:11.224  6797  6797 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-05 12:00:11.231  6797  6797 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:11.231  6797  6797 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:11.248  6744  6744 D LgDataFeature: LgDataFeature() Constructor: none
,07-05 12:00:11.248  6744  6744 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 12:00:11.264  6797  6840 D OpenGLRenderer: Render dirty regions requested: true
,07-05 12:00:11.264  6797  6840 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 12:00:11.268  6797  6840 D OpenGLRenderer: Enabling debug mode 0
07-05 12:00:11.274  6797  6797 D Atlas   : Validating map...
07-05 12:00:11.277  1032  1992 D SplitWindow: check instance of lgWin Window{20b56d06 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-05 12:00:11.345  6797  6838 D LgDataFeature: LgDataFeature() Constructor: none
,07-05 12:00:11.346  6797  6838 D LgDataFeature: LgDataFeature() Constructor Done, null
07-05 12:00:11.394  6797  6797 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6925fc8 time:139102
,07-05 12:00:11.434  1032  2050 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6856 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-05 12:00:11.435  1032  2050 I ActivityManager: Killing 5215:com.android.calendar/u0a13 (adj 15): empty #17
,07-05 12:00:11.500  6797  6797 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:00:11.553  6797  6797 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 12:00:11.560  1032  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +589ms (total +665ms)
07-05 12:00:11.560  1032  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20cec583 u0 com.test.thalitest/.MainActivity t12} time:139268
,07-05 12:00:11.569  1032  2359 W libprocessgroup: failed to open /acct/uid_10013/pid_5215/cgroup.procs: No such file or directory
07-05 12:00:11.582  6744  6744 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 12:00:11.600  6856  6856 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-05 12:00:11.609  6856  6856 I LockScreenSettings: New app installed broadcast received ..
07-05 12:00:11.611  6856  6856 I LockScreenSettings: Number of installed packages  1
07-05 12:00:11.621  6797  6878 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,07-05 12:00:11.630  6797  6878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:00:11.630  6797  6878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:00:11.630  6797  6878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:00:11.630  6797  6878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:00:11.630  6797  6878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:00:11.631  6797  6878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@327e9a0c added. We now have 1 listener(s)
07-05 12:00:11.670  1032  1994 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6880 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:00:11.672  1032  1748 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-05 12:00:11.683  6797  6878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-05 12:00:11.684  6797  6878 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-05 12:00:11.686  6797  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 12:00:11.686  6797  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:00:11.693  6797  6878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b83e25b added. We now have 1 listener(s)
07-05 12:00:11.694  6797  6878 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 12:00:11.697  1032  1543 D WifiService: New client listening to asynchronous messages
,07-05 12:00:11.700  6797  6878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 12:00:11.705  6797  6878 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 12:00:11.705  6797  6878 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 12:00:11.710  6797  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 12:00:11.710  1032  1761 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:00:11.711  6797  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:00:11.718  6797  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 12:00:11.718  6797  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:00:11.718  6797  6878 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:00:11.720  6797  6797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 12:00:11.721  6797  6878 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 12:00:11.722  6797  6797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:00:11.764  6797  6838 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-05 12:00:11.764  6797  6838 I chromium: ,
,07-05 12:00:11.765  6880  6880 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:00:11.821  6797  6797 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:00:11.918  6797  6797 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-05 12:00:11.918  6797  6797 I chromium: 
,07-05 12:00:12.051  1032  2092 V SIM_STK : Menu title from STK is T-Mobile
,07-05 12:00:12.069   342   355 E GBMv2   : DFP En is all cleared set to be enabled
07-05 12:00:12.070   342   355 E GBMv2   : Set value is all cleared set the max
07-05 12:00:12.070   342   355 I GBMv2   : DFP Enabled. Ignore VFP set
,07-05 12:00:12.110  1032  2092 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6911 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-05 12:00:12.184  6911  6911 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-05 12:00:12.185  6911  6911 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-05 12:00:12.188  6426  6426 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-05 12:00:12.207  1032  1575 I ActivityManager: Killing 6313:com.lge.clock/u0a10 (adj 15): empty #17
,07-05 12:00:12.358  1032  1992 W libprocessgroup: failed to open /acct/uid_10010/pid_6313/cgroup.procs: No such file or directory
,07-05 12:00:12.366  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
07-05 12:00:12.369  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-05 12:00:12.389  1032  1436 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 12:00:12.390  1032  1032 D administrator: Handling package changes for user 0
,07-05 12:00:12.401  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-05 12:00:12.416  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-05 12:00:12.416  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-05 12:00:12.429  1032  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-05 12:00:12.433  1032  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6929 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-05 12:00:12.435  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-05 12:00:12.437  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-05 12:00:12.437  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-05 12:00:12.439  2479  2479 V GmsNetworkLocationProvi: DISABLE
07-05 12:00:12.440  6797  6898 W jxcore-log: Initializing JXcore engine
07-05 12:00:12.440  6797  6898 W jxcore-log: JXcore engine is ready
,07-05 12:00:12.477  6929  6929 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 12:00:12.486  1032  1091 D LocationProviderProxy: applying state to connected service
07-05 12:00:12.489  2479  2479 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-05 12:00:12.482  6898  6898 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8906]" dev="sockfs" ino=8906 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-05 12:00:12.482  6898  6898 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 12:00:12.482  6898  6898 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7626]" dev="sockfs" ino=7626 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-05 12:00:12.482  6898  6898 W Thread-802: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-05 12:00:12.482  6898  6898 W Thread-802: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33816]" dev="sockfs" ino=33816 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-05 12:00:12.505  6797  6898 W jxcore-log: Starting JXcore engine
,07-05 12:00:12.579  6797  6898 W jxcore-log: Platform android
07-05 12:00:12.579  6797  6898 W jxcore-log: 
07-05 12:00:12.579  6797  6898 W jxcore-log: Process ARCH arm
07-05 12:00:12.579  6797  6898 W jxcore-log: 
,07-05 12:00:12.602  1032  1032 I art     : Explicit concurrent mark sweep GC freed 37706(1856KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.482ms total 109.482ms
,07-05 12:00:12.628  6929  6929 D LgDataFeature: LgDataFeature() Constructor: none
07-05 12:00:12.628  6929  6929 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 12:00:12.698  6929  6956 I Babel   : MmsConfig: mnc/mcc: 0/0
07-05 12:00:12.698  6929  6956 I Babel   : MmsConfig.loadMmsSettings
,07-05 12:00:12.700  6929  6956 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-05 12:00:12.700  6929  6956 I Babel   : MmsConfig.loadFromDatabase
,07-05 12:00:12.715  6929  6956 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-05 12:00:12.715  6929  6956 I Babel   : MmsConfig.loadFromResources
07-05 12:00:12.717  6929  6956 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-05 12:00:12.718  6929  6956 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-05 12:00:12.750  6929  6955 W AudioCapabilities: Unsupported mime audio/evrc
,07-05 12:00:12.750  6929  6929 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:00:12.757  6929  6955 W AudioCapabilities: Unsupported mime audio/qcelp
,07-05 12:00:12.759  6929  6955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:00:12.773  6797  6898 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:00:12.773  6797  6898 I jxcore-log: 
07-05 12:00:12.773  6797  6898 W jxcore-log: JXcore engine is started
,07-05 12:00:12.775  6929  6955 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-05 12:00:12.778  1845  6959 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-05 12:00:12.778  1845  6959 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-05 12:00:12.779  6929  6955 W AudioCapabilities: Unsupported mime audio/qcelp
07-05 12:00:12.782  6929  6955 W AudioCapabilities: Unsupported mime audio/evrc
07-05 12:00:12.789  1845  4774 I Icing   : updateResources: need to parse e{com.google.android.gms}
,07-05 12:00:12.791  6622  6622 I AppUp4:CustModeStarterReceiver: onReceive
07-05 12:00:12.793  6929  6955 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-05 12:00:12.795  6929  6955 W VideoCapabilities: Unsupported mime video/divx
07-05 12:00:12.796  6929  6955 W VideoCapabilities: Unsupported mime video/divx311
07-05 12:00:12.797  6929  6955 W VideoCapabilities: Unsupported mime video/divx4
07-05 12:00:12.801  6929  6955 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-05 12:00:12.817  6622  6622 D LgDataFeature: LgDataFeature() Constructor: none
07-05 12:00:12.817  6622  6622 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 12:00:12.821  6929  6955 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-05 12:00:12.821  6622  6622 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12f1d3fe
07-05 12:00:12.821  6622  6622 D AppUp4:CustFacade: isCustomizationCompleted : false
07-05 12:00:12.821  6622  6622 D AppUp4:CustFacade: isPhone : true
07-05 12:00:12.822  6622  6622 D AppUp4:CustModeStarterReceiver: begin check event
07-05 12:00:12.822  6622  6622 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-05 12:00:12.824  6929  6955 W AudioCapabilities: Unsupported mime audio/eac3
07-05 12:00:12.825  6929  6955 W AudioCapabilities: Unsupported mime audio/ac3
07-05 12:00:12.825  6929  6955 W AudioCapabilities: Unsupported mime audio/g726
07-05 12:00:12.826  6929  6955 W AudioCapabilities: Unsupported mime audio/wma-voice
07-05 12:00:12.826  1032  2360 I ActivityManager: Killing 6372:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
07-05 12:00:12.827  6929  6955 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-05 12:00:12.828  6929  6955 W AudioCapabilities: Unsupported mime audio/adpcm
07-05 12:00:12.830  6929  6955 W VideoCapabilities: Unsupported mime video/theora
,07-05 12:00:12.832  6929  6955 W VideoCapabilities: Unsupported mime video/mjpg
,07-05 12:00:12.958  1032  1992 W libprocessgroup: failed to open /acct/uid_10085/pid_6372/cgroup.procs: No such file or directory
07-05 12:00:13.026  4634  6965 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 12:00:13.040  6856  6856 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-05 12:00:13.040  6856  6856 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-05 12:00:13.040  6856  6856 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-05 12:00:13.040  6856  6856 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-05 12:00:13.040  6856  6856 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-05 12:00:13.040  6856  6856 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-05 12:00:13.321  1032  2360 V SIM_STK : Menu title from STK is T-Mobile
,07-05 12:00:13.331  4634  6965 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 305 ms] updated apps [took 305 ms] 
07-05 12:00:15.337  6744  6744 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-05 12:00:15.346  1032  1774 I ActivityManager: Killing 6409:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-05 12:00:15.375  1032  1761 W libprocessgroup: failed to open /acct/uid_1000/pid_6409/cgroup.procs: No such file or directory
,07-05 12:00:16.328  6744  6841 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 12:00:17.006  1032  1738 I ActivityManager: Killing 6456:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-05 12:00:17.037  1032  2092 W libprocessgroup: failed to open /acct/uid_10046/pid_6456/cgroup.procs: No such file or directory
,07-05 12:00:18.129  1845  6587 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-05 12:00:18.136   313  6980 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-05 12:00:18.136   313  6980 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-05 12:00:18.136   313  6980 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-05 12:00:18.386  1845  1845 I ConfigFetchService: fetch service done; releasing wakelock
,07-05 12:00:18.396  1845  1845 I ConfigFetchService: stopping self
07-05 12:00:18.407  2208  2208 I ConfigService: onDestroy
,07-05 12:00:23.188  1032  1092 I ActivityManager: Waited long enough for: ServiceRecord{2b55bf70 u0 com.google.android.gms/.wearable.service.WearableService}
,07-05 12:00:29.598  1032  1379 V AlarmManager: RTC_WAKEUP set : Alarm{3163b0ac type 0 when 1467712824457 com.android.vending} when 1467712824457
,07-05 12:00:29.704  1032  1761 V SIM_STK : Menu title from STK is T-Mobile
,07-05 12:00:29.873  6696  6696 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-05 12:01:00.077  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:01:00.077  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:01:00.077  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:01:00.078  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:01:00.089  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:01:00.089  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:01:00.092  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:01:00.095  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:02:00.086  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:02:00.086  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:02:00.086  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:02:00.087  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:02:00.098  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:02:00.098  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:02:00.100  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:02:00.103  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:02:30.774  1032  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=889615164, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,07-05 12:02:30.784  1032  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{384ed175 type 2 when 258293 android} when 258293
07-05 12:02:30.828  2619  2619 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 12:02:30.861  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=889615164 [*alarm*], flags=0x0
,07-05 12:03:00.069  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:03:00.069  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:03:00.069  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:03:00.070  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:03:00.080  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:03:00.080  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:03:00.083  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:03:00.085  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:03:00.972  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:03:00.972  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:03:00.985  1974  2151 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:03:00.985  1974  2151 D LEDHandler: Battery Level Remaining: 100%
07-05 12:03:00.985  1974  2151 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,07-05 12:03:00.987  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
07-05 12:03:00.988  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:03:00.989  1032  1543 D WifiController: battery changed pluggedType: 2
07-05 12:03:00.991  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:03:00.993  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:03:00.993  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:03:00.995  3928  4041 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:03:01.000  6426  6426 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 12:03:27.777  1032  3572 I LocationManagerService: remove 30cee46b
07-05 12:03:27.778  1032  3572 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 12:03:27.778  1032  3572 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 12:03:27.779  1032  3572 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:03:27.788  1032  3572 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 12:03:27.789  1032  3572 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 12:03:38.142  1032  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=889615164, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,07-05 12:03:38.191  2619  2619 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 12:03:38.217  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=889615164 [*alarm*], flags=0x0
,07-05 12:04:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:04:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:04:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:04:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:04:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:04:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:04:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:04:00.069  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:05:00.085  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:05:00.086  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:05:00.086  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:05:00.086  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:05:00.098  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:05:00.098  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:05:00.101  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:05:00.104  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:06:00.094  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:06:00.094  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:06:00.094  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:06:00.095  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:06:00.106  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:06:00.106  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:06:00.109  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:06:00.111  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:07:00.103  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:07:00.103  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:07:00.103  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:07:00.104  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:07:00.117  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:07:00.117  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:07:00.119  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:07:00.121  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:08:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:08:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:08:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:08:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:08:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:08:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:08:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:08:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:09:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:09:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:09:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:09:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:09:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:09:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:09:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:09:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:10:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:10:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:10:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:10:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:10:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:10:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:10:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:10:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:10:16.348  1032  1738 I ActivityManager: Killing 5846:com.android.providers.calendar/u0a14 (adj 15): empty #17
,07-05 12:10:16.405  1032  1992 W libprocessgroup: failed to open /acct/uid_10014/pid_5846/cgroup.procs: No such file or directory
,07-05 12:11:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:11:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:11:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:11:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:11:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:11:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:11:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:11:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:12:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:12:00.051  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:12:00.051  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:12:00.052  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:12:00.064  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:12:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:12:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:12:00.069  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:13:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:13:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:13:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:13:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:13:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:13:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:13:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:13:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:13:32.031  1032  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=889615164, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,07-05 12:13:32.049  1032  1379 V AlarmManager: RTC_WAKEUP set : Alarm{32df050a type 0 when 1467713440224 com.google.android.gms} when 1467713440224
,07-05 12:13:32.054  1032  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c3a617b type 2 when 929117 com.google.android.gms} when 929117
,07-05 12:13:32.095  2619  2619 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 12:13:32.127  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=889615164 [*alarm*], flags=0x0
,07-05 12:13:32.143  1845  7018 I EventLogService: Aggregate from 1467712802295 (log), 1467711640039 (data)
,07-05 12:13:32.427  2208  2952 D GCM     : Message class com.google.e.a.a.h
07-05 12:13:34.148  1032  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c480ff1 type 2 when 941825 com.android.bluetooth} when 941825
,07-05 12:13:34.164  3928  4096 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-05 12:13:34.164  3928  4096 W bt-smp  : Plain text(LSB ~ MSB) = 18 ef 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-05 12:13:34.164  3928  4096 W bt-smp  : Encrypted text(LSB ~ MSB) = d7 2c f5 79 e4 94 25 bf fe 5e 06 98 fb 73 14 5e 
07-05 12:13:34.164  3928  4096 W bt-btm  : Stopping oneshot timer
,07-05 12:14:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:14:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:14:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:14:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:14:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:14:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:14:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:14:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:15:00.108  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:15:00.108  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:15:00.108  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:15:00.109  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:15:00.121  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:15:00.121  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:15:00.124  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:15:00.125  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:15:01.205  1032  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=889615164, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,07-05 12:15:01.279  1032  1092 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7038 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-05 12:15:01.323  2619  2619 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 12:15:01.445  7038  7038 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-05 12:15:01.450  7038  7038 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@12f1d3fe
07-05 12:15:01.450  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=889615164 [*alarm*], flags=0x0
07-05 12:15:01.452  1032  2360 I ActivityManager: Killing 6244:com.android.defcontainer/u0a4 (adj 15): empty #17
07-05 12:15:01.514  1032  1761 W libprocessgroup: failed to open /acct/uid_10004/pid_6244/cgroup.procs: No such file or directory
,07-05 12:16:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:16:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:16:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:16:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:16:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 12:16:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:16:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:16:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:17:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:17:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:17:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:17:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:17:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:17:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:17:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:17:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:18:00.050  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:18:00.051  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:18:00.051  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:18:00.051  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:18:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:18:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:18:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:18:00.069  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:18:12.227  1032  1091 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 12:19:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:19:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:19:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:19:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:19:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:19:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:19:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:19:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:19:03.533  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:19:03.533  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:19:03.544  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
07-05 12:19:03.544  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:19:03.546  1032  1543 D WifiController: battery changed pluggedType: 2
,07-05 12:19:03.550  1974  2151 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:19:03.550  1974  2151 D LEDHandler: Battery Level Remaining: 100%
07-05 12:19:03.550  1974  2151 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
07-05 12:19:03.551  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:19:03.553  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:19:03.553  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:19:03.555  3928  4041 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:19:03.561  6426  6426 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 12:20:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:20:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:20:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 12:20:00.058  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-05 12:20:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:20:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:20:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 12:20:00.075  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:21:00.060  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:21:00.060  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:21:00.060  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:21:00.061  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:21:00.072  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:21:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:21:00.075  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:21:00.077  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:22:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:22:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:22:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:22:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:22:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:22:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:22:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:22:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:23:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:23:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:23:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 12:23:00.059  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-05 12:23:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:23:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:23:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1401000ms)
```
