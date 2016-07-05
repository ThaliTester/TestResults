#### Test 7214543196063dc_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
,07-05 14:04:35.478  6488  6488 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
07-05 14:04:35.611  6488  6488 D LgDataFeature: LgDataFeature() Constructor: none
07-05 14:04:35.611  6488  6488 D LgDataFeature: LgDataFeature() Constructor Done, null
07-05 14:04:35.673  6488  6488 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
07-05 14:04:35.697  6488  6488 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 14:04:35.699  6488  6488 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 14:04:35.725  6488  6488 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-05 14:04:35.725  6488  6488 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
07-05 14:04:35.744  1035  1984 I ActivityManager: Killing 6084:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-05 14:04:35.821  1035  1886 W libprocessgroup: failed to open /acct/uid_10080/pid_6084/cgroup.procs: No such file or directory
07-05 14:04:35.845  5061  6535 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 14:04:35.903  3416  3436 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-05 14:04:35.903  1035  1576 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6536 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 14:04:35.908  6527  6527 D AndroidRuntime: 
07-05 14:04:35.908  6527  6527 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:04:35.911  6527  6527 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:35.912  3416  3436 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d5023c0 on behalf of 6488
07-05 14:04:35.935  1035  1885 V SIM_STK : Menu title from STK is T-Mobile
07-05 14:04:35.961  6488  6488 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-05 14:04:35.975  6488  6488 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-05 14:04:36.024  5061  6535 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 179 ms] updated apps [took 179 ms] 
07-05 14:04:36.038  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 14:04:36.038  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 14:04:36.044  1035  1545 D WifiController: battery changed pluggedType: 2
07-05 14:04:36.044  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-05 14:04:36.045  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:04:36.046  1940  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 14:04:36.046  1940  2071 D LEDHandler: Battery Level Remaining: 100%
07-05 14:04:36.046  1940  2071 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-05 14:04:36.046  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:04:36.047  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:04:36.047  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:04:36.047  4323  4443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:04:36.048  5593  5593 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 14:04:36.052  6527  6527 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:04:36.056  1035  1984 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:04:36.066  1940  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-05 14:04:36.068  1035  1984 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-05 14:04:36.069  1035  1984 D ActivityManager: setTaskToReturnTo : TaskRecord{825e798 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 14:04:36.069  1035  1984 D ActivityManager: setTaskToReturnTo : TaskRecord{825e798 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 14:04:36.070  1035  1984 D WindowStateEx: AppWindowTokenEx init.. 
07-05 14:04:36.070   344   364 E GBMv2   : DFP En is all cleared set to be enabled
07-05 14:04:36.102  1035  1984 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6580 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 14:04:36.104  6527  6527 D AndroidRuntime: Shutting down VM
07-05 14:04:36.156  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-05 14:04:36.156  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3e43525f co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 14:04:36.157  1940  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-05 14:04:36.157  1940  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a3d34ac co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 14:04:36.159  6536  6536 D DocsApplication: Installing DEX configuration.
07-05 14:04:36.175  6536  6536 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-05 14:04:36.178  6536  6536 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{184e973 com.google.android.apps.docs}
07-05 14:04:36.204  6536  6536 D TAG     : onCreate()
07-05 14:04:36.207  6580  6580 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 14:04:36.231  6536  6536 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-05 14:04:36.277  6580  6580 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-05 14:04:36.284  6580  6580 I LibraryLoader: Loading: webviewchromium
07-05 14:04:36.286  6580  6580 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 900-902)
07-05 14:04:36.286  6580  6580 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:36.298  6580  6580 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f904265}
,07-05 14:04:36.299  6580  6580 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:36.299  6580  6580 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:36.307  6580  6580 I BrowserStartupController: Initializing chromium process, renderers=0
07-05 14:04:36.307  6580  6580 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:36.319  6580  6580 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-05 14:04:36.321  6580  6580 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-05 14:04:36.321  6580  6580 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-05 14:04:36.324   329   329 V AudioPolicyService: registerClient() client 0xb1003920, uid 10118
07-05 14:04:36.332  6580  6580 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 14:04:36.332  6580  6580 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 14:04:36.332  6580  6580 I Adreno-EGL: Build Date: 12/12/14 금
07-05 14:04:36.332  6580  6580 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-05 14:04:36.332  6580  6580 I Adreno-EGL: Remote Branch: 
07-05 14:04:36.332  6580  6580 I Adreno-EGL: Local Patches: 
07-05 14:04:36.332  6580  6580 I Adreno-EGL: Reconstruct Branch: 
,07-05 14:04:36.334  1035  1097 D BluetoothManagerService: Message: 20
07-05 14:04:36.334  1035  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f520762:true
07-05 14:04:36.397  6580  6613 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-05 14:04:36.402  6580  6580 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-05 14:04:36.423  6580  6580 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:36.427  6580  6580 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 14:04:36.430  6580  6580 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,07-05 14:04:36.432  6580  6580 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 14:04:36.432  6580  6580 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 14:04:36.450  6580  6580 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-05 14:04:36.455  6580  6580 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:36.455  6580  6580 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:36.525  6580  6629 D OpenGLRenderer: Render dirty regions requested: true
07-05 14:04:36.525  6580  6629 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:04:36.529  6580  6629 D OpenGLRenderer: Enabling debug mode 0
,07-05 14:04:36.536  6580  6580 D Atlas   : Validating map...
07-05 14:04:36.540  1035  1950 D SplitWindow: check instance of lgWin Window{def7a55 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-05 14:04:36.560  6580  6623 D LgDataFeature: LgDataFeature() Constructor: none
,07-05 14:04:36.560  6580  6623 D LgDataFeature: LgDataFeature() Constructor Done, null
07-05 14:04:36.641  1035  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +485ms (total +570ms)
07-05 14:04:36.641  6580  6580 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a899078 time:131258
,07-05 14:04:36.642  1035  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c441bf1 u0 com.test.thalitest/.MainActivity t12} time:131259
07-05 14:04:36.766  6580  6580 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-05 14:04:36.766  6580  6580 I chromium: 
,07-05 14:04:36.804  6580  6580 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:04:36.986  6580  6636 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,07-05 14:04:36.999  6580  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:36.999  6580  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:36.999  6580  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:36.999  6580  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:36.999  6580  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 14:04:36.999  6580  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10ffebbc added. We now have 1 listener(s)
07-05 14:04:37.000  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-05 14:04:37.005  6580  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-05 14:04:37.006  6580  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-05 14:04:37.007  6580  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:04:37.007  6580  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:37.013  6580  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37dfe3cb added. We now have 1 listener(s)
07-05 14:04:37.013  6580  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 14:04:37.020  1035  1545 D WifiService: New client listening to asynchronous messages
,07-05 14:04:37.024  6580  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 14:04:37.024  1816  5209 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-05 14:04:37.027  6580  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 14:04:37.027  6580  6636 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 14:04:37.029  6580  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 14:04:37.030  1035  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 14:04:37.030  6580  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:37.037  6580  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 14:04:37.037  6580  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:37.037  6580  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 14:04:37.038  6580  6636 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 14:04:37.038  6580  6580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:37.039  6580  6580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:37.089  6580  6580 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:37.117  6580  6623 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-05 14:04:37.117  6580  6623 I chromium: 
07-05 14:04:37.125  1816  5209 I art     : Explicit concurrent mark sweep GC freed 31027(1928KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 1.340ms total 69.578ms
,07-05 14:04:37.159  1816  5209 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,07-05 14:04:37.183  1816  5209 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,07-05 14:04:37.205   344   366 E GBMv2   : DFP En is all cleared set to be enabled
,07-05 14:04:37.205   344   366 E GBMv2   : Set value is all cleared set the max
07-05 14:04:37.205   344   366 I GBMv2   : DFP Enabled. Ignore VFP set
07-05 14:04:37.323  6536  6536 D LgDataFeature: LgDataFeature() Constructor: none
,07-05 14:04:37.323  6536  6536 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 14:04:37.492  1035  2009 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6656 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
07-05 14:04:37.501  6536  6536 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:37.561  6656  6656 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-05 14:04:37.575  6656  6656 I LockScreenSettings: New app installed broadcast received ..
,07-05 14:04:37.579  6656  6656 I LockScreenSettings: Number of installed packages  1
07-05 14:04:37.633  1035  1939 V SIM_STK : Menu title from STK is T-Mobile
,07-05 14:04:37.698  6580  6639 W jxcore-log: Initializing JXcore engine
07-05 14:04:37.698  6580  6639 W jxcore-log: JXcore engine is ready
,07-05 14:04:37.713  1035  1914 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6678 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-05 14:04:37.715  1035  1914 I ActivityManager: Killing 5593:com.lge.bnr/1000 (adj 15): empty #17
,07-05 14:04:37.726  6639  6639 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8280]" dev="sockfs" ino=8280 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-05 14:04:37.726  6639  6639 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 14:04:37.726  6639  6639 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9892]" dev="sockfs" ino=9892 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-05 14:04:37.726  6639  6639 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-05 14:04:37.726  6639  6639 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32017]" dev="sockfs" ino=32017 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-05 14:04:37.750  6580  6639 W jxcore-log: Starting JXcore engine
,07-05 14:04:37.822  6580  6639 W jxcore-log: Platform android
07-05 14:04:37.822  6580  6639 W jxcore-log: 
07-05 14:04:37.822  6580  6639 W jxcore-log: Process ARCH arm
07-05 14:04:37.822  6580  6639 W jxcore-log: 
,07-05 14:04:37.827  1035  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_5593/cgroup.procs: No such file or directory
,07-05 14:04:37.879  6678  6678 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-05 14:04:37.879  6678  6678 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-05 14:04:37.928  1035  1914 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6695 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-05 14:04:37.930  1035  1914 I ActivityManager: Killing 6152:com.google.android.gm/u0a64 (adj 15): empty #17
07-05 14:04:37.955   358   358 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 904us total 28.100ms
,07-05 14:04:37.974   358   358 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 395us total 19.444ms
,07-05 14:04:37.996   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 20.469ms
,07-05 14:04:38.031  6580  6639 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:38.031  6580  6639 I jxcore-log: 
07-05 14:04:38.031  6580  6639 W jxcore-log: JXcore engine is started
,07-05 14:04:38.032  1035  1885 W libprocessgroup: failed to open /acct/uid_10064/pid_6152/cgroup.procs: No such file or directory
07-05 14:04:38.043  6580  6636 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:04:38.050  6580  6580 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-05 14:04:38.085  6695  6695 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,07-05 14:04:38.108  6695  6695 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 14:04:38.113  6367  6367 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-05 14:04:38.143  6367  6367 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,07-05 14:04:38.144  1035  2019 I ActivityManager: Killing 5934:com.google.android.talk/u0a72 (adj 15): empty #17
07-05 14:04:38.307  1035  1051 W libprocessgroup: failed to open /acct/uid_10072/pid_5934/cgroup.procs: No such file or directory
07-05 14:04:38.444  1035  1914 I ActivityManager: Killing 5719:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-05 14:04:38.466  5698  5698 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-05 14:04:38.466  5698  5698 W System.err: android.os.DeadObjectException
07-05 14:04:38.466  5698  5698 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 14:04:38.466  5698  5698 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 14:04:38.466  5698  5698 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-05 14:04:38.466  5698  5698 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-05 14:04:38.467  5698  5698 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-05 14:04:38.467  5698  5698 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-05 14:04:38.467  5698  5698 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:38.467  5698  5698 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:38.467  5698  5698 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 14:04:38.467  5698  5698 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 14:04:38.467  5698  5698 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:38.467  5698  5698 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:38.467  5698  5698 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 14:04:38.467  5698  5698 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 14:04:38.467  5698  5698 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-05 14:04:38.467  5698  5698 W System.err: android.os.DeadObjectException
07-05 14:04:38.468  5698  5698 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 14:04:38.468  5698  5698 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-05 14:04:38.468  5698  5698 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 14:04:38.468  5698  5698 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 14:04:38.468  5698  5698 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:38.468  5698  5698 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:38.468  5698  5698 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 14:04:38.468  5698  5698 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 14:04:38.468  5698  5698 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-05 14:04:38.469  5698  5698 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-05 14:04:38.695  1035  1886 W libprocessgroup: failed to open /acct/uid_1000/pid_5719/cgroup.procs: No such file or directory
07-05 14:04:38.696  1035  1886 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-05 14:04:38.708  5698  5698 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-05 14:04:38.709  5698  5698 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-05 14:04:38.758  1035  1650 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6724 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-05 14:04:38.758  5698  5698 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-05 14:04:38.968  1035  1984 I art     : Explicit concurrent mark sweep GC freed 23743(1190KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.769ms total 159.340ms
,07-05 14:04:38.994  6724  6724 D UEI.SmartControl: Quickset Services start...
07-05 14:04:38.995  6724  6724 I UEI.SmartControl: Manufacture = LGE
07-05 14:04:38.996  6724  6724 D UEI.SmartControl: Id = LGNevo
07-05 14:04:38.996  6724  6724 D UEI.SmartControl: File observer start...
07-05 14:04:38.997  6724  6724 E UEI.SmartControl: IR Port is disabled: false
07-05 14:04:38.997  6724  6724 D UEI.SmartControl: Starting file observer...
07-05 14:04:38.997  6724  6724 D UEI.SmartControl: Extracting JNI libs...
07-05 14:04:38.997  6724  6724 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,07-05 14:04:39.064  6724  6724 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-05 14:04:39.064  6724  6724 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-05 14:04:39.064  6724  6724 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-05 14:04:39.101  6724  6724 I UEI.SmartControl: --- Selecting new region: 6
07-05 14:04:39.103  6724  6724 I UEI.SmartControl: Model = LG-D855
,07-05 14:04:39.105  6724  6724 D UEI.SmartControl: QS Service created
07-05 14:04:39.121  6724  6724 I UEI.SmartControl: Service initServices...
,07-05 14:04:39.127  6724  6724 D UEI.SmartControl: QS start get config
,07-05 14:04:39.197  6724  6724 D UEI.SmartControl: Loading JNI Libs...
,07-05 14:04:39.473  6724  6724 I UEI.SmartControl: Supports setup maps: true
,07-05 14:04:39.477  6724  6724 D UEI.SmartControl: QS start statue = true Error code = 0
07-05 14:04:39.477  6724  6724 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-05 14:04:39.477  6724  6724 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-05 14:04:39.477  6724  6724 I UEI.SmartControl: ### init IR Blaster...
07-05 14:04:39.482  6724  6724 D serial_port: Configuring serial port
07-05 14:04:39.485  6724  6724 E UEI.SmartControl: UEIBLaster setting for 616
07-05 14:04:39.485  6724  6724 I UEI.SmartControl: Setting serial record hearder size = 2
07-05 14:04:39.486  6724  6724 I UEI.SmartControl: configuring settings for MAXQ616
07-05 14:04:39.486  6724  6724 I UEI.SmartControl: Get version...
,07-05 14:04:39.507  6724  6751 D UEI.SmartControl: serial port data available: 21
,07-05 14:04:39.534  6724  6724 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-05 14:04:39.534  6724  6724 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-05 14:04:39.534  6724  6724 I UEI.SmartControl: QS saving settings...
07-05 14:04:39.535  6724  6724 D UEI.SmartControl: IR Blaster version: 25672567
,07-05 14:04:39.552  6724  6751 D UEI.SmartControl: serial port data available: 4
,07-05 14:04:39.585  6724  6754 I UEI.SmartControl: Device manager: loading config....
07-05 14:04:39.586  6724  6754 D UEI.SmartControl: ----------- loading internal config...
,07-05 14:04:39.583  6724  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-05 14:04:39.594  6724  6724 E UEI.SmartControl: Services init done
07-05 14:04:39.594  6724  6724 D UEI.SmartControl: QS Service init finished
07-05 14:04:39.594  6724  6724 D UEI.SmartControl: QS Service version name: 2.1.91
07-05 14:04:39.595  6724  6724 D UEI.SmartControl: QS Service version code: 201091
07-05 14:04:39.595  6724  6724 D UEI.SmartControl: Service requested: Control
07-05 14:04:39.597  6724  6754 E UEI.SmartControl: Loading SETTINGS...
07-05 14:04:39.600  6724  6724 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-05 14:04:39.603  1035  1939 I ActivityManager: Killing 5698:com.lge.qremote/u0a112 (adj 15): empty #17
07-05 14:04:39.604  6724  6754 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-05 14:04:39.632  6724  6753 I UEI.SmartControl: Notify AllClients services are ready: 0
07-05 14:04:39.632  6724  6753 D UEI.SmartControl: -----service ready thread exits
,07-05 14:04:39.694  1035  1914 W libprocessgroup: failed to open /acct/uid_10112/pid_5698/cgroup.procs: No such file or directory
,07-05 14:04:39.696  6724  6724 D UEI.SmartControl: Internal service binding...
07-05 14:04:41.406  6536  6536 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-05 14:04:41.412  1035  1653 I ActivityManager: Killing 5637:com.android.calendar/u0a13 (adj 15): empty #17
,07-05 14:04:41.545  1035  1576 W libprocessgroup: failed to open /acct/uid_10013/pid_5637/cgroup.procs: No such file or directory
,07-05 14:04:42.388  6536  6647 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:44.538  1816  6404 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-05 14:04:44.559   325  6768 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-05 14:04:44.560   325  6768 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-05 14:04:44.560   325  6768 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-05 14:04:44.583  6724  6755 D UEI.SmartControl: Internal timer expired: 1
07-05 14:04:44.583  6724  6755 D UEI.SmartControl: unbind internal service
,07-05 14:04:44.595  6724  6724 D UEI.SmartControl: Service.onUnbind: IControl
,07-05 14:04:44.603  6724  6724 D UEI.SmartControl: Service.onDestroy
07-05 14:04:44.603  6724  6724 D UEI.SmartControl: Lock is in USE false
07-05 14:04:44.603  6724  6724 D UEI.SmartControl: unbind internal service
07-05 14:04:44.604  6724  6724 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@24479fe1
07-05 14:04:44.604  6724  6724 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-05 14:04:44.604  6724  6724 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-05 14:04:44.604  6724  6724 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 14:04:44.604  6724  6724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 14:04:44.604  6724  6724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:44.604  6724  6724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:44.604  6724  6724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 14:04:44.604  6724  6724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 14:04:44.604  6724  6724 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@24479fe1
07-05 14:04:44.609  6724  6724 D serial_port: close(fd = 25)
07-05 14:04:44.614  6724  6724 I UEI.SmartControl: Serial port is closed.
07-05 14:04:44.614  6724  6724 I UEI.SmartControl: Serial port is closed.
07-05 14:04:44.614  6724  6724 D UEI.SmartControl: Blaster closed
07-05 14:04:44.614  6724  6724 D UEI.SmartControl: Shut down QS...
07-05 14:04:44.614  6724  6724 D UEI.SmartControl: Stopping QS lib
07-05 14:04:44.615  6724  6724 D UEI.SmartControl: QS lib stop result = true
07-05 14:04:44.615  6724  6724 D UEI.SmartControl: Stopped QS lib
,07-05 14:04:44.618  6724  6724 D UEI.SmartControl: Stopped file observer...
,07-05 14:04:44.618  6724  6724 D UEI.SmartControl: QS shutdown complete
07-05 14:04:44.788  1816  1816 I ConfigFetchService: fetch service done; releasing wakelock
,07-05 14:04:44.795  1816  1816 I ConfigFetchService: stopping self
,07-05 14:04:44.798  2120  2120 I ConfigService: onDestroy
,07-05 14:04:46.537  2149  2149 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-05 14:04:46.544  2149  2149 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,07-05 14:04:48.438  6580  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:48.438  6580  6639 I jxcore-log: 
,07-05 14:04:48.441  6580  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:48.441  6580  6639 I jxcore-log: 
,07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:48.446  6580  6639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:48.448  6580  6639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:04:48.450  6580  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:48.450  6580  6639 I jxcore-log: 
,07-05 14:04:48.452  6580  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:48.452  6580  6639 I jxcore-log: 
,07-05 14:04:48.822  6580  6639 I jxcore-log: Unit Test app is loaded
07-05 14:04:48.822  6580  6639 I jxcore-log: 
,07-05 14:04:48.829  6580  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:48.829  6580  6639 I jxcore-log: 
07-05 14:04:48.832  6580  6639 I jxcore-log: My device name is: LGE-LG-D855
07-05 14:04:48.832  6580  6639 I jxcore-log: 
07-05 14:04:48.834  6580  6639 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 14:04:48.834  6580  6639 I jxcore-log: 
07-05 14:04:48.851  6580  6580 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:49.610  1035  1093 I ActivityManager: Waited long enough for: ServiceRecord{12c9be52 u0 com.google.android.gms/.wearable.service.WearableService}
,07-05 14:04:52.807  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:52.807  6580  6639 I jxcore-log: 
,07-05 14:04:53.202  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:53.202  6580  6639 I jxcore-log: 
,07-05 14:04:53.230  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:53.230  6580  6639 I jxcore-log: 
,07-05 14:04:53.235  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:53.235  6580  6639 I jxcore-log: 
,07-05 14:04:53.250  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:53.250  6580  6639 I jxcore-log: 
,07-05 14:04:53.255  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:53.255  6580  6639 I jxcore-log: 
,07-05 14:04:53.337  1035  1380 V AlarmManager: RTC_WAKEUP set : Alarm{234127ca type 0 when 1467720290730 com.android.vending} when 1467720290730
,07-05 14:04:53.394  4947  6769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:53.445  1035  1984 V SIM_STK : Menu title from STK is T-Mobile
,07-05 14:04:53.610  6488  6488 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-05 14:04:55.608  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:55.608  6580  6639 I jxcore-log: 
,07-05 14:04:55.620  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:55.620  6580  6639 I jxcore-log: 
07-05 14:04:55.628  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:55.628  6580  6639 I jxcore-log: 
,07-05 14:04:55.781  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:55.781  6580  6639 I jxcore-log: 
,07-05 14:04:55.871  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:55.871  6580  6639 I jxcore-log: 
,07-05 14:04:55.924  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:55.924  6580  6639 I jxcore-log: 
,07-05 14:04:55.931  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:55.931  6580  6639 I jxcore-log: 
07-05 14:04:56.119  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:56.119  6580  6639 I jxcore-log: 
,07-05 14:04:56.141  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:56.141  6580  6639 I jxcore-log: 
,07-05 14:04:56.146  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:56.146  6580  6639 I jxcore-log: 
07-05 14:04:56.151  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:56.151  6580  6639 I jxcore-log: 
07-05 14:04:56.166  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:56.166  6580  6639 I jxcore-log: 
,07-05 14:04:56.185  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:56.185  6580  6639 I jxcore-log: 
,07-05 14:04:56.267  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:56.267  6580  6639 I jxcore-log: 
,07-05 14:04:56.273  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:56.273  6580  6639 I jxcore-log: 
07-05 14:04:56.299  6580  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:56.299  6580  6639 I jxcore-log: 
,07-05 14:04:56.311  6580  6639 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-05 14:04:56.312  6580  6639 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 14:04:56.312  6580  6639 I jxcore-log: 
,07-05 14:05:00.045  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:05:00.045  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:05:00.045  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:05:00.046  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:05:00.060  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:05:00.060  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:05:00.062  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:05:00.066  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:05:33.737  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 14:05:33.737  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 14:06:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:06:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 14:06:00.055  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:06:00.056  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:06:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:06:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:06:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:06:00.075  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:06:33.905  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 14:06:33.905  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 14:06:33.921  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:06:33.921  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:06:33.924  1035  1545 D WifiController: battery changed pluggedType: 2
07-05 14:06:33.925  4323  4443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:06:33.927  1940  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 14:06:33.927  1940  2071 D LEDHandler: Battery Level Remaining: 100%
07-05 14:06:33.928  1940  2071 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
07-05 14:06:33.929  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
07-05 14:06:33.929  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:06:33.931  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:06:33.937  6695  6695 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 14:07:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:07:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:07:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:07:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:07:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:07:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 14:07:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:07:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:07:04.407  1035  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,07-05 14:07:04.420  1035  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2d19ad3b type 2 when 251035 android} when 251035
07-05 14:07:04.460  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:07:04.491  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
,07-05 14:07:59.229  1035  3465 I LocationManagerService: remove 3e095d06
,07-05 14:07:59.236  1035  3465 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 14:07:59.236  1035  3465 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 14:07:59.238  1035  3465 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 14:07:59.240  1035  3465 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 14:07:59.241  1035  3465 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 14:08:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:08:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:08:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:08:00.052  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:08:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:08:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 14:08:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:08:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:08:17.001  1035  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,07-05 14:08:17.055  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:08:17.088  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
,07-05 14:09:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:09:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:09:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 14:09:00.062  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-05 14:09:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:09:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:09:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:09:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:09:34.386  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 14:09:34.386  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 14:09:34.401  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:09:34.401  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:09:34.404  1035  1545 D WifiController: battery changed pluggedType: 2
07-05 14:09:34.407  1940  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 14:09:34.407  1940  2071 D LEDHandler: Battery Level Remaining: 100%
07-05 14:09:34.407  1940  2071 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
07-05 14:09:34.409  4323  4443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:09:34.410  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
07-05 14:09:34.410  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:09:34.411  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:09:34.417  6695  6695 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 14:10:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:10:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:10:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:10:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:10:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:10:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:10:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:10:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:11:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:11:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:11:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:11:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:11:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:11:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:11:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:11:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:12:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:12:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:12:00.056  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
07-05 14:12:00.056  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:12:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:12:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:12:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 14:12:00.081  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:13:00.061  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:13:00.061  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:13:00.061  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:13:00.062  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:13:00.075  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:13:00.075  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:13:00.077  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:13:00.079  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:14:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:14:00.051  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:14:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:14:00.052  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:14:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:14:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:14:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:14:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:14:34.007  1035  1100 D KnockOnPowerController: LPWG WAKEUP isScreenOn = false, TimeAfterSleep = 686062
,07-05 14:14:34.015  1035  1100 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 14:14:34.016  1603  1603 D KeyguardModel: mReceiver, received action: com.lge.android.intent.action.ACTION_KNOCK_ON, sendingUserId:-1
07-05 14:14:34.016  1603  1603 D KeyguardModel: LGIntent.ACTION_KNOCK_ON
07-05 14:14:34.017  1035  1100 D KnockOnPowerController: [updateScreenState] screen on = true
07-05 14:14:34.017  1035  1100 D KnockOnPowerController: disable proximity sensor
07-05 14:14:34.017  1035  1035 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@3d58ec58)
07-05 14:14:34.017  1035  1035 V SmartCoverServiceDelegate: onScreenTurnedOn()
07-05 14:14:34.017  1035  1100 I SensorManager: removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.android.server.power.ProximitySensorListener.disable():117
07-05 14:14:34.017  1035  1100 I sensors_hal_Ctx: activate: handle is 70, disable
07-05 14:14:34.017  1035  1100 V sensors_hal_Ctx: activate sensors is 0
07-05 14:14:34.017  1035  1100 D sensors_hal_KnockOnProx: enable: handle=70
07-05 14:14:34.017  1035  1100 D sensors_hal_KnockOnProx: enable: Disabling sensor handle=70
07-05 14:14:34.017  1035  1100 I sensors_hal_SAM: sendCancel:sensor() Sending cancel to svc no:33
07-05 14:14:34.019  1035  1100 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-05 14:14:34.020  1035  1060 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 0, txn Id 69
07-05 14:14:34.020  1035  1060 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_DISABLE/CANCEL_RESP_V01
07-05 14:14:34.020  1559  2235 D SmartCoverViewMediator: onScreenTurnedOn, seq = 0
07-05 14:14:34.020  1559  2235 D SmartCoverViewMediator: notifyScreenOnLocked
,07-05 14:14:34.022  1559  1559 D SmartCoverViewMediator: handleNotifyScreenOn
07-05 14:14:34.022  1559  1559 I QuickCircle: onScreenTurnedOn
07-05 14:14:34.023  1559  1559 D QuickCircleViewManager: applyCoverState:0
07-05 14:14:34.024  1603  2738 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-05 14:14:34.024  1603  2738 D KeyguardViewMediator: notifyScreenOnLocked
07-05 14:14:34.024  1603  1603 D KeyguardViewMediator: handleNotifyScreenOn
07-05 14:14:34.024  1603  1603 D KeyguardViewBase: screen on, instance 33df957a
07-05 14:14:34.024  1603  1603 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-05 14:14:34.024  1603  1603 D KeyguardSecurityView: showSecurityScreen(None)
07-05 14:14:34.024  1603  1603 D quilt lockscreen LightParticleRenderer: resume()
07-05 14:14:34.024  1603  1603 D quilt lockscreen LightParticleRenderer: initRenderer()
07-05 14:14:34.028  1603  1603 D LgeKeyguardWallpaperContainer: queryReferenceOfBackground isPortrait : true ,queryObject : com.lge.lockscreen.widget.draglayer.EffectBridgeImpl@2d75d2c9
07-05 14:14:34.028  1603  1603 D KeyguardModel: cache file exits
07-05 14:14:34.028  1603  1603 D ScreenTurnOffBySensor: registerProximitySensor
07-05 14:14:34.029  1603  1603 I SensorManager: registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.lge.lockscreen.model.ScreenTurnOffBySensor@37b83bde] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.registerProximitySensor():54
07-05 14:14:34.031  1035  1576 I sensors_hal_Ctx: batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
07-05 14:14:34.031  1035  1576 D sensors_hal_SAM: batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
07-05 14:14:34.031  1035  1576 D sensors_hal_SAM: batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
07-05 14:14:34.031  1035  1576 I sensors_hal_Ctx: activate: handle is 70, enable
07-05 14:14:34.031  1035  1576 D sensors_hal_Util: waitForResponse: timeout=1000
,07-05 14:14:34.034  1035  1056 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-05 14:14:34.034  1035  1056 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 2, txn Id 1
07-05 14:14:34.034  1035  1056 D sensors_hal_Time: tsOffsetIs: Apps: 728648000195; DSPS: 24017236; Offset : -4312757134
07-05 14:14:34.034  1035  1576 V sensors_hal_Ctx: activate sensors is 0
07-05 14:14:34.034  1035  1576 D sensors_hal_KnockOnProx: enable: handle=70
07-05 14:14:34.034  1035  1576 I sensors_hal_SAM: sendEnableReq:sensor() Sending enable to svc no:33
07-05 14:14:34.034  1035  1576 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 14:14:34.036  1035  1060 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 2, txn Id 0
07-05 14:14:34.036  1035  1060 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_ENABLE_RESP_V01
07-05 14:14:34.036  1035  1576 D sensors_hal_KnockOnProx: enable: Received response: 0
07-05 14:14:34.037  1603  1603 I SensorManager: registerListenerImpl() [Sensor: LGE Light, Rate: 200000, SensorEventListener: com.lge.lockscreen.model.ScreenTurnOffBySensor@37b83bde] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.registerProximitySensor():55
07-05 14:14:34.037  1035  2031 I sensors_hal_Ctx: batch: handle:1 flags:0x0 period_ns 200000000, timeout 0
07-05 14:14:34.037  1035  2031 D sensors_hal_SMGR: batch:sensor(android.sensor.light) handle:1 flags:0x0 period_ns 200000000
07-05 14:14:34.037  1035  2031 D sensors_hal_SMGR: batch:sensor(android.sensor.light) sample_rate=20Hz report_rate_f=0.000000Hz curr sample rate:20 cur rpt rate:0 max:20.000000 min:1.000000
07-05 14:14:34.037  1035  2031 D sensors_hal_SMGR: batch: current sample rate, report rate & buffering are equal to requested (0.000000,0.000000,0)
07-05 14:14:34.037  1035  2031 I sensors_hal_Ctx: activate: handle is 1, enable
07-05 14:14:34.037  1035  2031 V sensors_hal_Ctx: activate sensors is 2
07-05 14:14:34.037  1035  2031 D sensors_hal_SMGR: enable:sensor(android.sensor.light) handle 1, freq=20 report_rate=0 batched=0
07-05 14:14:34.037  1035  2031 I sensors_hal_SMGR: SMGRReportAdd:sensor(android.sensor.light) handle=1, sample_rate=20 report_rate=0 buffer=0
07-05 14:14:34.037  1035  2031 D sensors_hal_SMGR: SMGRPrepareAddMsg:sensor android.sensor.light 
07-05 14:14:34.038  1035  2031 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 14:14:34.038  1035  1100 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=10000 (718654 ms ago)
07-05 14:14:34.038  1035  1100 D KnockOnPowerController: disable proximity sensor
07-05 14:14:34.038  1035  1035 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
07-05 14:14:34.040  1035  1100 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-05 14:14:34.043  1940  2071 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 14:14:34.043  1603  3208 D quilt lockscreen LockScreenRenderer: onSurfaceCreated()
,07-05 14:14:34.045  1035  1100 I SensorManager: registerListenerImpl() [Sensor: Motion Accel, Rate: 66667, SensorEventListener: com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@56e82e9] bycom.android.internal.policy.impl.WindowOrientationListener.enable():147
07-05 14:14:34.047  1940  2071 V LEDService: startInternal : pkg=KnockOn, recordId=0 : LGLedRecord{3b240575 flags=2 patternId=2 color=0 priority=2 recordId=0 pkg=KnockOn mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
07-05 14:14:34.047  1940  2071 D qdlights: set_light_notifications: 3,0,0,0,3
07-05 14:14:34.047  1940  2071 D qdlights: [pattern_id] = 0
07-05 14:14:34.048  1035  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 1, Sn 0, msg Id 33, txn Id 1
07-05 14:14:34.048  1035  1057 D sensors_hal_SMGR: processResp: 33
07-05 14:14:34.048  1035  1057 I sensors_hal_SMGR: processBufferingResp: Id: 1 Resp: 1 txn id 1
07-05 14:14:34.048  1035  2031 D sensors_hal_SMGR: SMGRReportAdd: Received Response: 0
07-05 14:14:34.048  1035  1100 I sensors_hal_Ctx: batch: handle:46 flags:0x0 period_ns 66667000, timeout 0
07-05 14:14:34.048  1035  1100 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 flags:0x0 period_ns:66667000 timeout:0
07-05 14:14:34.048  1035  1100 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 freq:1 report_rate:1 max:1.000000 min:0.000000
07-05 14:14:34.048  1035  1100 I sensors_hal_Ctx: activate: handle is 46, enable
07-05 14:14:34.048  1035  1100 V sensors_hal_Ctx: activate sensors is 400000000002
07-05 14:14:34.048  1035  1100 D sensors_hal_LP2: enable: handle=46
07-05 14:14:34.048  1035  1100 I sensors_hal_SAM: sendEnableReq:sensor(com.qti.sensor.motion_accel) Sending enable to svc no:49
07-05 14:14:34.048   509   924 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
07-05 14:14:34.049  1035  1100 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 14:14:34.049   509   924 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req f54afd3e
07-05 14:14:34.049  1603  1603 V KeyguardStatusView: Enable transport text marquee
07-05 14:14:34.050  1035  1984 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 14:14:34.050  1035  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 2, txn Id 0
07-05 14:14:34.050  1035  1086 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_ENABLE_RESP_V01
07-05 14:14:34.050  1035  1100 D sensors_hal_LP2: enable: Received response: 0
07-05 14:14:34.050  1035  1100 D KnockOnPowerController: sendResult : 1
07-05 14:14:34.051  1035  1035 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-05 14:14:34.051  1035  1539 E WifiStateMachine:  ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
07-05 14:14:34.052   329  2165 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 1035
07-05 14:14:34.052  1035  1577 I QCOM PowerHAL: Got set_interactive hint
07-05 14:14:34.053   282   282 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6482000
07-05 14:14:34.053   282   282 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 14:14:34.053   329  2165 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:14:34.053   329  2165 V voice   : voice_set_parameters: enter: screen_state=on
07-05 14:14:34.053   329  2165 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-05 14:14:34.053   329  2165 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 14:14:34.053   329  2165 V voice   : voice_set_parameters: exit with code(0)
07-05 14:14:34.053   329  2165 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-05 14:14:34.053   329  2165 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 14:14:34.053   329  2165 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 14:14:34.053   329  2165 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 14:14:34.054   329  2165 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-05 14:14:34.054   329  2165 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 14:14:34.054   329  2165 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-05 14:14:34.059  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
07-05 14:14:34.059  1035  1539 E WifiStateMachine:  ConnectModeState CMD_SCREEN_STATE_CHANGED 1 0
07-05 14:14:34.059  1035  1539 E WifiStateMachine:  DriverStartedState CMD_SCREEN_STATE_CHANGED 1 0
07-05 14:14:34.059  1035  1539 E WifiStateMachine:  SupplicantStartedState CMD_SCREEN_STATE_CHANGED 1 0
,07-05 14:14:34.064  1035  1098 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 14:14:34.064  1035  1539 E WifiStateMachine:  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
07-05 14:14:34.067   344   364 E GBMv2   : Set value is all cleared set the max
07-05 14:14:34.067   344   364 I GBMv2   : VFP is [12]
07-05 14:14:34.067  1035  1539 E WifiStateMachine:  ConnectedState !what:132097 0 0
07-05 14:14:34.067  1035  1539 E WifiStateMachine:  L2ConnectedState !what:132097 0 0
07-05 14:14:34.067  1035  1539 E WifiStateMachine:  ConnectModeState !what:132097 0 0
07-05 14:14:34.068  1035  1539 E WifiStateMachine:  DriverStartedState !what:132097 0 0
07-05 14:14:34.068  1035  1539 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
07-05 14:14:34.069  1940  2071 I LEDService: getCurrentHighestLGLedRecord : size = 2
07-05 14:14:34.069  1851  1851 D DSDPConnection: Display #0 changed.
07-05 14:14:34.069  1940  2071 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 14:14:34.074  1035  1539 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-05 14:14:34.074  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-05 14:14:34.074  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-05 14:14:34.075  1940  2071 I LEDService: updateLightsLocked : turn on led
07-05 14:14:34.078  1035  1035 V ActivityManager: Display changed displayId=0
07-05 14:14:34.081  1940  2071 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
07-05 14:14:34.082  1603  3208 D lockscreen_weather: lock_settings_weather_animation = 1
07-05 14:14:34.085  1940  6836 D qdlights: set_light_notifications: 2,ff00ffff,500,0,1
07-05 14:14:34.085  1940  6836 D qdlights: [Current] = 255, R = 0, G = 255, B = 255
,07-05 14:14:34.090  1035  1539 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-05 14:14:34.090  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-05 14:14:34.091  1035  1539 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
07-05 14:14:34.091  1035  1539 E WifiStateMachine:  ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-05 14:14:34.091  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-05 14:14:34.092  1035  1539 E WifiStateMachine:  ConnectModeState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-05 14:14:34.092  1603  3208 D lockscreen_weather: R.bool.weather_service_default_auto_update = true
07-05 14:14:34.092  1603  3208 D lockscreen_weather: weather RefreshPeriod = 3
07-05 14:14:34.092  1603  3208 D lockscreen_weather: com.lge.sizechangable.weather_preferences = true
07-05 14:14:34.092  1603  3208 D lockscreen_weather: getCurrentWeather returns, { city=null weatherText=null weatherCode=0 temperature=null weatherIconResID=-1 }
07-05 14:14:34.092  1603  3208 D quilt lockscreen LockScreenRenderer: onSurfaceChanged() : width = 1440, height = 2560
07-05 14:14:34.092  1035  1539 E WifiStateMachine:  DriverStartedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-05 14:14:34.092  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,07-05 14:14:34.113   327   534 E QMI_FW  : [LGE_VSS_QCCI][AP] Enter qcci_qmi_lge_vss_send_cmd().....
07-05 14:14:34.113   327   534 E QMI_FW  : [LGE_VSS_QCCI][AP] Common sendind MSG = 0x60a
07-05 14:14:34.115  1851  1851 V TelephonyAutoProfiling: [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
07-05 14:14:34.116   509  1028 I Sensors : sns_pwr.c(273):acquiring wakelock
07-05 14:14:34.116   327   534 E QMI_FW  : [LGE_VSS_QCCI][AP] Enter qcci_qmi_lge_vss_send_cmd().....
07-05 14:14:34.116   327   534 E QMI_FW  : [LGE_VSS_QCCI][AP] Common sendind MSG = 0x60a
07-05 14:14:34.116  1035  1060 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 33, msg Id 5, txn Id 0
07-05 14:14:34.116  1035  1060 D sensors_hal_KnockOnProx: processInd: SNS_SAM_KNOCK_REPORT_IND_V01
07-05 14:14:34.116  1035  1060 D sensors_hal_KnockOnProx: processInd: handle 70, count=1
07-05 14:14:34.116  1035  1060 I sensors_hal_KnockOnProx: processInd : knock-on state changed - FAR
07-05 14:14:34.116  1035  1090 D sensors_hal_Ctx: poll:polldata:1, sensor:70, type:499898103, x:5.000000 y:-0.000007 z:0.000000
07-05 14:14:34.116  1035  1090 D sensors_hal_Ctx: poll: count: 36
07-05 14:14:34.116  1035  1090 D sensors_hal_Util: waitForResponse: timeout=0
07-05 14:14:34.125  1603  3208 W Adreno-ES20: <__load_uniform_float:825>: GL_INVALID_OPERATION
07-05 14:14:34.125  1851  1851 D PhoneInterfaceManager: [PhoneIntfMgr] mSigLevel = 3
,07-05 14:14:34.131  1603  1603 I [SystemUI]StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 8 0 -98 -95 -120 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0 level=3
07-05 14:14:34.131  1603  1603 D TelephonyIcons: updateDataType sub=0, type=0, inetCondition=1 showAtLeast3G=false show4GforLte=true hspaDistinguishable=false
07-05 14:14:34.131  1603  1603 D TelephonyIcons: data type item name: array/telephony_data_type_sim1
07-05 14:14:34.131  1603  1603 D TelephonyIcons: data type item id: 2131623942
07-05 14:14:34.132  1603  1603 D TelephonyIcons: updateDataType mSelectedDataTypeIcon[0]=0, mSelectedDataActivityIndex=0
07-05 14:14:34.132  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-05 14:14:34.133  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-05 14:14:34.146  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-05 14:14:34.148  1851  1851 D PhoneInterfaceManager: [PhoneIntfMgr] handleMessage : 2
,07-05 14:14:34.152  1851  1851 D PhoneInterfaceManager: [PhoneIntfMgr] handleMessage : 3
07-05 14:14:34.158  2714  2714 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-05 14:14:34.158  1035  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-05 14:14:34.158  1035  1539 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-05 14:14:34.159  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-05 14:14:34.159  1035  1539 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
07-05 14:14:34.159  1035  1539 D WifiNative-wlan0: doBoolean: BLACKLIST clear
07-05 14:14:34.159  1035  1539 D WifiNative-wlan0: BLACKLIST clear: returned true
,07-05 14:14:34.190   282   790 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 14:14:34.213  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:14:34.213  1603  1603 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-05 14:14:34.219  1035  1100 I DisplayPowerController: Unblocked screen on after 179 ms
07-05 14:14:34.220  1035  1100 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 14:14:34.268   282   282 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-05 14:14:34.268  1035  1577 D SurfaceControl: Excessive delay in setPowerMode(): 215ms
07-05 14:14:34.318  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 14:14:34.319  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,07-05 14:14:34.320  1940  2071 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
07-05 14:14:34.321  1940  1940 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-05 14:14:34.321  1940  1940 D Cliptray Service: lockStatus = 1
07-05 14:14:34.322  1035  1035 D Ulp_jni : JNI:system_update. Event-0
07-05 14:14:34.324  1922  1922 D LNfcService: action : android.intent.action.SCREEN_ON
07-05 14:14:34.327  1851  1851 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-05 14:14:34.337  1922  6855 D NfcServiceNXP: mScreenState : 2
,07-05 14:14:34.345  1603  1603 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
,07-05 14:14:34.351  1603  1603 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,07-05 14:14:34.355  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:14:34.355  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:14:34.355  1035  1035 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
07-05 14:14:34.374  1922  2786 E NxpNfcJni: getReconnectState = 0x0
,07-05 14:14:34.379  3786  3786 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_SCREEN_ON !!!
07-05 14:14:34.381  5450  5450 D AppCleanupService: android.intent.action.SCREEN_ON
07-05 14:14:34.400  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:14:34.404  1922  6855 D LNfcService: isRequireNfcCRouting() return true
07-05 14:14:34.404  1922  6855 D LNfcService: isHCERoutingtoHost() return true
07-05 14:14:34.404  1922  6855 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-05 14:14:34.404  1922  6855 D NfcService: mEnableLPD: true
07-05 14:14:34.404  1922  6855 D NfcService: mEnableReader: false
07-05 14:14:34.404  1922  6855 D NfcService: mEnableHostRouting: true
07-05 14:14:34.404  1922  6855 D NfcService: newParams.techmask= mTechMask: 0
07-05 14:14:34.404  1922  6855 D NfcService: mEnableLPD: true
07-05 14:14:34.404  1922  6855 D NfcService: mEnableReader: false
07-05 14:14:34.404  1922  6855 D NfcService: mEnableHostRouting: true
07-05 14:14:34.405  1922  6855 D NfcService: screenState= 2
07-05 14:14:34.405  1922  6855 D NfcService: Discovery configuration equal, not updating.
07-05 14:14:34.413  1035  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
07-05 14:14:34.413  1035  1057 D sensors_hal_SMGR: processBufferingInd: Samples_len=1 Items=1 max_reports_per_index=1
07-05 14:14:34.413  1035  1057 V sensors_hal_SMGR: processReportInd: St: 0 ReportId: 1 Rate: 0, Len: 1
07-05 14:14:34.413  1035  1057 V sensors_hal_SMGR: processReportInd: Id: PROX_LIGHT_DATA: Ty: 1 Q: 0
07-05 14:14:34.413  1035  1057 V sensors_hal_Light: processReportInd:sensor android.sensor.light 
07-05 14:14:34.413  1035  1057 V sensors_hal_Light: processReportInd: 110000 17.000000
,07-05 14:14:34.413  1035  1057 D sensors_hal_SMGR: processReportInd: handle:1 SMGR TS:24029520 HAL TS:729009996772 elapsedRealtimeNano:729017036394
07-05 14:14:34.413  1035  1090 D sensors_hal_Ctx: poll:polldata:1, sensor:1, type:5, x:17.000000 y:0.000000 z:0.000000
07-05 14:14:34.413  1035  1090 D sensors_hal_Ctx: poll: count: 36
07-05 14:14:34.413  1035  1090 D sensors_hal_Util: waitForResponse: timeout=0
07-05 14:14:34.422  1035  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
07-05 14:14:34.422  1035  1086 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-05 14:14:34.422  1035  1086 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-05 14:14:34.422  1035  1086 V sensors_hal_LP2: processInd: X: -0.107117 Y: 0.571625 Z: 9.691833 
07-05 14:14:34.422  1035  1090 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.107117 y:0.571625 z:9.691833
07-05 14:14:34.422  1035  1090 D sensors_hal_Ctx: poll: count: 36
07-05 14:14:34.422  1035  1090 D sensors_hal_Util: waitForResponse: timeout=0
07-05 14:14:34.423  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
07-05 14:14:34.472  1035  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
07-05 14:14:34.472  1035  1086 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-05 14:14:34.472  1035  1086 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-05 14:14:34.472  1035  1086 V sensors_hal_LP2: processInd: X: -0.120972 Y: 0.562576 Z: 9.700150 
07-05 14:14:34.472  1035  1090 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.120972 y:0.562576 z:9.700150
07-05 14:14:34.472  1035  1090 D sensors_hal_Ctx: poll: count: 36
07-05 14:14:34.472  1035  1090 D sensors_hal_Util: waitForResponse: timeout=0
,07-05 14:14:34.594  1940  6836 D qdlights: set_light_notifications: 2,f700f7f7,10,0,1
07-05 14:14:34.594  1940  6836 D qdlights: [Current] = 247, R = 0, G = 247, B = 247
,07-05 14:14:34.605  1940  6836 D qdlights: set_light_notifications: 2,ef00efef,10,0,1
07-05 14:14:34.606  1940  6836 D qdlights: [Current] = 239, R = 0, G = 239, B = 239
,07-05 14:14:34.617  1940  6836 D qdlights: set_light_notifications: 2,e700e7e7,10,0,1
07-05 14:14:34.617  1940  6836 D qdlights: [Current] = 231, R = 0, G = 231, B = 231
,07-05 14:14:34.628  1940  6836 D qdlights: set_light_notifications: 2,df00dfdf,10,0,1
07-05 14:14:34.628  1940  6836 D qdlights: [Current] = 223, R = 0, G = 223, B = 223
,07-05 14:14:34.640  1940  6836 D qdlights: set_light_notifications: 2,d700d7d7,10,0,1
07-05 14:14:34.640  1940  6836 D qdlights: [Current] = 215, R = 0, G = 215, B = 215
,07-05 14:14:34.652  1940  6836 D qdlights: set_light_notifications: 2,cf00cfcf,10,0,1
07-05 14:14:34.652  1940  6836 D qdlights: [Current] = 207, R = 0, G = 207, B = 207
,07-05 14:14:34.664  1940  6836 D qdlights: set_light_notifications: 2,c700c7c7,10,0,1
07-05 14:14:34.664  1940  6836 D qdlights: [Current] = 199, R = 0, G = 199, B = 199
,07-05 14:14:34.676  1940  6836 D qdlights: set_light_notifications: 2,bf00bfbf,10,0,1
07-05 14:14:34.676  1940  6836 D qdlights: [Current] = 191, R = 0, G = 191, B = 191
,07-05 14:14:34.688  1940  6836 D qdlights: set_light_notifications: 2,b700b7b7,10,0,1
07-05 14:14:34.688  1940  6836 D qdlights: [Current] = 183, R = 0, G = 183, B = 183
,07-05 14:14:34.700  1940  6836 D qdlights: set_light_notifications: 2,af00afaf,10,0,1
07-05 14:14:34.700  1940  6836 D qdlights: [Current] = 175, R = 0, G = 175, B = 175
07-05 14:14:34.712  1940  6836 D qdlights: set_light_notifications: 2,a200a2a2,10,0,1
07-05 14:14:34.712  1940  6836 D qdlights: [Current] = 162, R = 0, G = 162, B = 162
,07-05 14:14:34.723  1940  6836 D qdlights: set_light_notifications: 2,97009797,10,0,1
,07-05 14:14:34.723  1940  6836 D qdlights: [Current] = 151, R = 0, G = 151, B = 151
07-05 14:14:34.735  1940  6836 D qdlights: set_light_notifications: 2,8c008c8c,10,0,1
07-05 14:14:34.735  1940  6836 D qdlights: [Current] = 140, R = 0, G = 140, B = 140
,07-05 14:14:34.747  1940  6836 D qdlights: set_light_notifications: 2,81008181,10,0,1
07-05 14:14:34.747  1940  6836 D qdlights: [Current] = 129, R = 0, G = 129, B = 129
,07-05 14:14:34.758  1940  6836 D qdlights: set_light_notifications: 2,76007676,10,0,1
07-05 14:14:34.758  1940  6836 D qdlights: [Current] = 118, R = 0, G = 118, B = 118
07-05 14:14:34.769  1940  6836 D qdlights: set_light_notifications: 2,6b006b6b,10,0,1
,07-05 14:14:34.769  1940  6836 D qdlights: [Current] = 107, R = 0, G = 107, B = 107
07-05 14:14:34.781  1940  6836 D qdlights: set_light_notifications: 2,60006060,10,0,1
07-05 14:14:34.781  1940  6836 D qdlights: [Current] = 96, R = 0, G = 96, B = 96
,07-05 14:14:34.792  1940  6836 D qdlights: set_light_notifications: 2,55005555,10,0,1
07-05 14:14:34.792  1940  6836 D qdlights: [Current] = 85, R = 0, G = 85, B = 85
,07-05 14:14:34.803  1940  6836 D qdlights: set_light_notifications: 2,4a004a4a,10,0,1
,07-05 14:14:34.803  1940  6836 D qdlights: [Current] = 74, R = 0, G = 74, B = 74
,07-05 14:14:34.815  1940  6836 D qdlights: set_light_notifications: 2,3f003f3f,10,0,1
07-05 14:14:34.815  1940  6836 D qdlights: [Current] = 63, R = 0, G = 63, B = 63
,07-05 14:14:34.826  1940  6836 D qdlights: set_light_notifications: 2,35003636,10,0,1
,07-05 14:14:34.826  1940  6836 D qdlights: [Current] = 53, R = 0, G = 54, B = 54
07-05 14:14:34.838  1940  6836 D qdlights: set_light_notifications: 2,30003131,10,0,1
07-05 14:14:34.838  1940  6836 D qdlights: [Current] = 48, R = 0, G = 49, B = 49
,07-05 14:14:34.850  1940  6836 D qdlights: set_light_notifications: 2,2b002c2c,10,0,1
,07-05 14:14:34.850  1940  6836 D qdlights: [Current] = 43, R = 0, G = 44, B = 44
07-05 14:14:34.861  1940  6836 D qdlights: set_light_notifications: 2,26002727,10,0,1
,07-05 14:14:34.861  1940  6836 D qdlights: [Current] = 38, R = 0, G = 39, B = 39
07-05 14:14:34.872  1940  6836 D qdlights: set_light_notifications: 2,21002222,10,0,1
07-05 14:14:34.872  1940  6836 D qdlights: [Current] = 33, R = 0, G = 34, B = 34
,07-05 14:14:34.884  1940  6836 D qdlights: set_light_notifications: 2,1c001d1d,10,0,1
07-05 14:14:34.884  1940  6836 D qdlights: [Current] = 28, R = 0, G = 29, B = 29
,07-05 14:14:34.895  1940  6836 D qdlights: set_light_notifications: 2,17001818,10,0,1
07-05 14:14:34.895  1940  6836 D qdlights: [Current] = 23, R = 0, G = 24, B = 24
,07-05 14:14:34.906  1940  6836 D qdlights: set_light_notifications: 2,12001313,10,0,1
,07-05 14:14:34.906  1940  6836 D qdlights: [Current] = 18, R = 0, G = 19, B = 19
,07-05 14:14:34.918  1940  6836 D qdlights: set_light_notifications: 2,d000e0e,10,0,1
07-05 14:14:34.918  1940  6836 D qdlights: [Current] = 13, R = 0, G = 14, B = 14
,07-05 14:14:34.929  1940  6836 D qdlights: set_light_notifications: 2,8000909,10,0,1
,07-05 14:14:34.930  1940  6836 D qdlights: [Current] = 8, R = 0, G = 9, B = 9
,07-05 14:14:34.941  1940  2071 D LEDHandler: handleMessage() repeat = false, whichLed = 1
,07-05 14:14:34.942  1940  2071 D qdlights: set_light_notifications: 0,0,0,0,1
,07-05 14:14:34.943  1940  2071 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 14:14:34.943  1940  2071 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 14:14:34.945  1940  2071 I LEDService: updateLightsLocked : turn off led
07-05 14:14:34.945  1940  2071 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 14:14:35.053  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-05 14:14:35.221   509   924 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
,07-05 14:14:35.289   344   366 E GBMv2   : DFP En is all cleared set to be enabled
,07-05 14:14:35.289   344   366 E GBMv2   : Set value is all cleared set the max
07-05 14:14:35.290   344   366 I GBMv2   : DFP Enabled. Ignore VFP set
,07-05 14:14:35.616   509   520 I Sensors : sns_pwr.c(301):releasing wakelock
,07-05 14:14:36.343  1035  2009 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-05 14:14:36.348  1035  1051 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
07-05 14:14:37.063  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-05 14:14:37.094  1035  1539 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:686049] from screen [on:0 period:-1157938138] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 14:14:37.095  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1157938137] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 14:14:37.095  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-05 14:14:37.636   338   425 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-05 14:14:38.079  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-05 14:14:38.343  1035  1653 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-05 14:14:38.352   329   329 V AudioPolicyService: registerClient() client 0xb558a4e0, uid 10003
,07-05 14:14:40.093  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-05 14:14:40.112  1035  1539 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=50.5, 0.0, 0.0  rx=45.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1157935120] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 14:14:40.120  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=50.5, 0.0, 0.0  rx=45.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1157935112] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 14:14:40.120  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-05 14:14:40.343  1035  2019 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-05 14:14:41.100  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-05 14:14:41.641   338   425 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-05 14:14:42.015  1035  1100 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=10000 (726631 ms ago)
,07-05 14:14:42.343  1035  1886 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-05 14:14:42.392  1035  1050 I ActivityManager: Killing 6209:com.android.providers.calendar/u0a14 (adj 15): empty #17
,07-05 14:14:42.452  1035  1950 W libprocessgroup: failed to open /acct/uid_10014/pid_6209/cgroup.procs: No such file or directory
,07-05 14:14:43.115  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-05 14:14:43.137  1035  1539 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=25.2, 0.0, 0.0  rx=23.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1157932095] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 14:14:43.139  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=25.2, 0.0, 0.0  rx=23.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1157932093] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 14:14:43.139  1035  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-05 14:14:44.016  1035  1100 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=10000 (728633 ms ago)
07-05 14:14:44.017  1035  1100 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 14:14:44.017  1035  1100 D KnockOnPowerController: [updateScreenState] screen on = false
07-05 14:14:44.017  1035  1100 D KnockOnPowerController: disable proximity sensor
07-05 14:14:44.017  1035  1100 D KnockOnPowerController: enable proximity sensor
07-05 14:14:44.018  1035  1100 I SensorManager: registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3472c199] bycom.android.server.power.ProximitySensorListener.enable():107
,07-05 14:14:44.021  1035  1100 I sensors_hal_Ctx: flush: handle is 70
07-05 14:14:44.021  1035  1100 I sensors_hal_SAM: flush:sensor() handle:70
07-05 14:14:44.023  1035  1100 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-05 14:14:44.043  1035  1100 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=10000 (728659 ms ago)
,07-05 14:14:44.045  1035  1035 I SensorManager: removeAllSensors() [Sensor: Motion Accel] bycom.android.internal.policy.impl.WindowOrientationListener.disable():166
07-05 14:14:44.045  1035  1035 I sensors_hal_Ctx: activate: handle is 46, disable
07-05 14:14:44.045  1035  1035 V sensors_hal_Ctx: activate sensors is 2
07-05 14:14:44.045  1035  1035 D sensors_hal_LP2: enable: handle=46
07-05 14:14:44.045  1035  1035 D sensors_hal_LP2: enable: Disabling sensor handle=46
,07-05 14:14:44.045  1035  1035 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-05 14:14:44.047  1559  2235 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-05 14:14:44.047  1559  2235 D SmartCoverViewMediator: notifyScreenOffLocked
07-05 14:14:44.048  1559  1559 D SmartCoverViewMediator: handleNotifyScreenOFF
07-05 14:14:44.048  1603  2182 D KeyguardViewMediator: onScreenTurnedOff(3)
07-05 14:14:44.048  1559  1559 I QuickCircle: onScreenTurnedOff
07-05 14:14:44.048  1603  2182 D KeyguardViewMediator: notifyScreenOffLocked
07-05 14:14:44.048  1559  1559 D LgeQuickCoverOverlayWindow: updateVisibility:hideSmartLighting
07-05 14:14:44.048  1559  1559 D LgeQuickCoverOverlayWindow: updateVisibility:hideNotification
07-05 14:14:44.048  1559  1559 D QuickCircleViewManager: applyCoverState:1
07-05 14:14:44.048  1559  1559 D QuickCircleViewManager: getState: 0
07-05 14:14:44.048  1559  1559 D QuickCircleViewManager: applyCoverState:LCD Off -> go to lock
07-05 14:14:44.048  1603  2182 E KeyguardViewMediator: resetStateLocked
,07-05 14:14:44.048  1559  1559 D QuickCircleViewManager: getState: 0
07-05 14:14:44.048  1603  1603 D KeyguardViewMediator: handleNotifyScreenOff
07-05 14:14:44.048  1603  1603 D KeyguardViewBase: screen off, instance 33df957a at 738665
07-05 14:14:44.048  1603  1603 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=true)
07-05 14:14:44.049  1603  1603 D KeyguardSecurityView: showSecurityScreen(None)
07-05 14:14:44.049  1603  1603 V LockDragLayerEffect: reset() : resets state to STATE_RESET_LOCK
07-05 14:14:44.049  1603  1603 D quilt lockscreen LightParticleRenderer: pause()
07-05 14:14:44.049  1603  1603 D quilt lockscreen LightParticleRenderer: initRenderer()
07-05 14:14:44.050  1035  1100 D KnockOnPowerController: proximity onSensorChanged : proximity = 1
07-05 14:14:44.050  1035  1100 I KnockOnPowerController: current mode = 1  value = 1 1
07-05 14:14:44.051  1035  1100 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-05 14:14:44.061  1035  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
07-05 14:14:44.061  1035  1057 D sensors_hal_SMGR: processBufferingInd: Samples_len=1 Items=1 max_reports_per_index=1
07-05 14:14:44.061  1035  1057 V sensors_hal_SMGR: processReportInd: St: 0 ReportId: 1 Rate: 0, Len: 1
07-05 14:14:44.061  1035  1057 V sensors_hal_SMGR: processReportInd: Id: PROX_LIGHT_DATA: Ty: 1 Q: 0
07-05 14:14:44.061  1035  1057 V sensors_hal_Light: processReportInd:sensor android.sensor.light 
07-05 14:14:44.061  1035  1057 V sensors_hal_Light: processReportInd: 120000 18.000000
07-05 14:14:44.061  1035  1057 D sensors_hal_SMGR: processReportInd: handle:1 SMGR TS:24345679 HAL TS:738658427689 elapsedRealtimeNano:738665526129
07-05 14:14:44.062  1035  1090 D sensors_hal_Ctx: poll:polldata:1, sensor:1, type:5, x:18.000000 y:0.000000 z:0.000000
07-05 14:14:44.062  1035  1090 D sensors_hal_Ctx: poll: count: 36
07-05 14:14:44.062  1035  1090 D sensors_hal_Util: waitForResponse: timeout=0
07-05 14:14:44.065  1035  1539 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 14:14:44.067  1035  1539 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,07-05 14:14:44.073  1035  1539 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 14:14:44.073   329  2165 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 1035
07-05 14:14:44.075  1035  1100 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.power.PowerManagerServiceEx$3.run:1231 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
07-05 14:14:44.076  1035  1100 I PowerManagerService: Sleeping (uid 1000)...
07-05 14:14:44.076  1035  1100 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=10000 (728693 ms ago)
07-05 14:14:44.077  1035  1539 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 14:14:44.077   329  2165 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 14:14:44.077   329  2165 V voice   : voice_set_parameters: enter: screen_state=off
07-05 14:14:44.077   329  2165 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-05 14:14:44.077   329  2165 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 14:14:44.077   329  2165 V voice   : voice_set_parameters: exit with code(0)
07-05 14:14:44.078   329  2165 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-05 14:14:44.078   329  2165 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 14:14:44.078   329  2165 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 14:14:44.078   329  2165 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 14:14:44.078   329  2165 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 14:14:44.078  1035  1539 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 14:14:44.078   329  2165 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,07-05 14:14:44.078  1035  1539 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 14:14:44.079  1035  1539 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-05 14:14:44.084  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-05 14:14:44.085  1035  1539 E WifiStateMachine:  ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-05 14:14:44.085  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-05 14:14:44.086  1035  1539 E WifiStateMachine:  ConnectModeState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,07-05 14:14:44.086  1035  1539 E WifiStateMachine:  DriverStartedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-05 14:14:44.086  1035  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-05 14:14:44.090  1035  1545 D WifiController: CMD_SCREEN_OFF 
07-05 14:14:44.090  1035  1545 D WifiController: shouldWifiStayAwake TRUE
,07-05 14:14:44.094  1035  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-05 14:14:44.094  1035  1086 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
07-05 14:14:44.096  1035  1092 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-05 14:14:44.104  1603  1603 D ScreenTurnOffBySensor: unregisterProximitySensor
07-05 14:14:44.105  1603  1603 I SensorManager: removeAllSensors() [Sensor: LGE Light] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.unregisterProximitySensor():63
07-05 14:14:44.105  1035  1885 I sensors_hal_Ctx: activate: handle is 1, disable
07-05 14:14:44.105  1035  1885 V sensors_hal_Ctx: All sensors stop, stop the time_service.
07-05 14:14:44.105  1035  1885 D sensors_hal_Time: send stop time_service command
,07-05 14:14:44.109  1035  1056 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-05 14:14:44.109  1035  1056 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 0, txn Id 1
07-05 14:14:44.112  2714  2714 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-05 14:14:44.113  1035  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,07-05 14:14:44.114  1035  1885 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 14:14:44.114  1035  1885 V sensors_hal_Ctx: activate sensors is 0
07-05 14:14:44.114  1035  1885 D sensors_hal_SMGR: enable:sensor(android.sensor.light) Deactivating sensor handle=1
07-05 14:14:44.115  1035  1885 I sensors_hal_SMGR: SMGRReportDelete:sensor(android.sensor.light) handle=1
07-05 14:14:44.116  1035  1885 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 14:14:44.117  1035  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 1, Sn 0, msg Id 33, txn Id 1
07-05 14:14:44.117  1035  1057 D sensors_hal_SMGR: processResp: 33
07-05 14:14:44.117  1035  1057 I sensors_hal_SMGR: processBufferingResp: Id: 1 Resp: 0 txn id 1
07-05 14:14:44.117  1035  1885 D sensors_hal_SMGR: SMGRReportDelete: Rcvd success response from request
07-05 14:14:44.125  1603  1603 I SensorManager: removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.unregisterProximitySensor():63
07-05 14:14:44.126  1035  1984 I sensors_hal_Ctx: batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
07-05 14:14:44.126  1035  1984 D sensors_hal_SAM: batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
07-05 14:14:44.126  1035  1984 D sensors_hal_SAM: batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
07-05 14:14:44.127  1603  1603 D KeyguardViewMediator: handleReset
,07-05 14:14:44.138  1603  1603 D KeyguardBackground: updateKeyguardState mState ? 1 ,goingToFullShade ? false ,fromShadeLocked ? false
07-05 14:14:44.138  1603  1603 D KeyguardBackground: Backdrop animation start. dest Alpha : 1
07-05 14:14:44.138  1603  1603 D KeyguardBackground: setKeyguardBackground isPortrait ? true
07-05 14:14:44.143  1603  1603 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO BACK HOME RECENT clock SEARCH >
,07-05 14:14:44.144  1603  1603 D StatusBarKeyguardViewManager: adjustCameraSliderVisibility: shouldVisible = false, mGlanceViewNow = false
07-05 14:14:44.144  1603  1603 D StatusBarWindowView: onScreenTurnedOff why = 3
07-05 14:14:44.144  1603  1603 V KeyguardStatusView: Disable transport text marquee
07-05 14:14:44.168  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,07-05 14:14:44.173  1940  2071 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 14:14:44.173  1940  2071 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 14:14:44.176  1940  2071 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 14:14:44.176  1940  2071 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 14:14:44.179  1940  1940 D VolumeVibrator: clear
07-05 14:14:44.180  1940  2071 I LEDService: updateLightsLocked : turn on led
07-05 14:14:44.180  1940  2071 D qdlights: set_light_notifications: 3,4,0,0,1
07-05 14:14:44.180  1940  2071 D qdlights: [pattern_id] = 4
07-05 14:14:44.182  1940  2071 D LEDHandler: RESTART MSG
07-05 14:14:44.183  1940  1940 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,07-05 14:14:44.190  1922  1922 D LNfcService: action : android.intent.action.SCREEN_OFF
07-05 14:14:44.193  1922  2516 D NfcServiceNXP: mScreenState : 1
,07-05 14:14:44.202  1851  1851 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
07-05 14:14:44.206  2032  2032 I [LGHome]EVENT: [Launcher.java:1836:onReceive()]Screen Off
07-05 14:14:44.218  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:14:44.218  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:14:44.218  1035  1035 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
,07-05 14:14:44.230  3786  3786 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_SCREEN_OFF !!!
07-05 14:14:44.231  3786  3786 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]case 9 : com.test.thalitest
,07-05 14:14:44.234  1922  2786 E NxpNfcJni: getReconnectState = 0x0
07-05 14:14:44.253  3786  4936 D LIA_MrGDBLogger_LoggerThread: [dreamwood]App Usage Logging
07-05 14:14:44.255  3786  3786 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]scheduledExecutorService is stopped
,07-05 14:14:44.260  5450  5450 D AppCleanupService: android.intent.action.SCREEN_OFF
07-05 14:14:44.261  1958  1958 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
07-05 14:14:44.261  5450  6879 D AppCleanupService: AppUsageStatsSaveTask
07-05 14:14:44.266  1922  2516 D LNfcService: isRequireNfcCRouting() return true
07-05 14:14:44.266  1922  2516 D LNfcService: isHCERoutingtoHost() return true
,07-05 14:14:44.266  1922  2516 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-05 14:14:44.266  1922  2516 D NfcService: mEnableLPD: true
07-05 14:14:44.266  1922  2516 D NfcService: mEnableReader: false
07-05 14:14:44.266  1922  2516 D NfcService: mEnableHostRouting: true
07-05 14:14:44.266  1922  2516 D NfcService: newParams.techmask= mTechMask: 0
07-05 14:14:44.266  1922  2516 D NfcService: mEnableLPD: true
07-05 14:14:44.266  1922  2516 D NfcService: mEnableReader: false
07-05 14:14:44.266  1922  2516 D NfcService: mEnableHostRouting: true
07-05 14:14:44.266  1922  2516 D NfcService: screenState= 1
07-05 14:14:44.266  1922  2516 D NfcService: Discovery configuration equal, not updating.
07-05 14:14:44.555  1035  1098 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 14:14:44.557  1035  1035 V ActivityManager: Display changed displayId=0
07-05 14:14:44.558   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
07-05 14:14:44.558   282   282 D qdhwcomposer: hwc_blank: Blanking display: 0
07-05 14:14:44.569  1851  1851 D DSDPConnection: Display #0 changed.
,07-05 14:14:44.644   338   425 E ThermalEngine: [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 578000000
,07-05 14:14:44.839   282   790 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 14:14:44.841   282   282 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-05 14:14:44.842  1035  1577 D SurfaceControl: Excessive delay in setPowerMode(): 287ms
,07-05 14:14:44.846  1035  1577 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:14:46.157  1035  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1157929076] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 14:14:46.159  1035  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1157929073] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 14:15:00.004  1035  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,07-05 14:15:00.054  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:15:00.069  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:15:00.069  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:15:00.069  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 14:15:00.072  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-05 14:15:00.074  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:15:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:15:00.075  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:15:00.077  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:15:00.119  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
,07-05 14:15:12.866  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 14:15:12.866  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 14:15:12.879  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:15:12.880  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:15:12.882  1035  1545 D WifiController: battery changed pluggedType: 2
07-05 14:15:12.886  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
07-05 14:15:12.886  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:15:12.887  1940  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 14:15:12.887  1940  2071 D LEDHandler: Battery Level Remaining: 100%
07-05 14:15:12.887  1940  2071 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
07-05 14:15:12.888  4323  4443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:15:12.889  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:15:12.894  6695  6695 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 14:16:00.002  1035  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,07-05 14:16:00.073  1035  1093 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6892 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-05 14:16:00.085  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:16:00.085  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:16:00.085  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:16:00.085  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:16:00.088  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:16:00.089  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:16:00.089  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:16:00.092  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:16:00.124  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:16:00.237  6892  6892 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-05 14:16:00.242  6892  6892 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1294aa2e
07-05 14:16:00.242  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
07-05 14:16:00.243  1035  1650 I ActivityManager: Killing 2149:com.lge.music/u0a34 (adj 15): empty #17
07-05 14:16:00.276   329  2166 V AudioFlinger: 2149 died, releasing its sessions
07-05 14:16:00.276   329  2166 V AudioFlinger:  pid 1851 @ 0
,07-05 14:16:00.277   329  2166 V AudioFlinger:  pid 3310 @ 1
07-05 14:16:00.277   329  2166 V AudioFlinger:  pid 3310 @ 2
07-05 14:16:00.299  1035  1576 W libprocessgroup: failed to open /acct/uid_10034/pid_2149/cgroup.procs: No such file or directory
,07-05 14:16:00.309  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-05 14:16:00.309  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 14:17:00.038  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:17:00.038  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:17:00.038  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:17:00.039  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:17:00.053  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:17:00.053  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 14:17:00.056  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:17:00.058  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:18:00.095  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:18:00.095  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:18:00.096  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:18:00.096  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:18:00.112  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:18:00.112  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:18:00.116  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 14:18:00.118  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:18:13.179  1035  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,07-05 14:18:13.198  1035  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b31f696 type 2 when 947780 com.android.bluetooth} when 947780
,07-05 14:18:13.205  4323  4508 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-05 14:18:13.205  4323  4508 W bt-smp  : Plain text(LSB ~ MSB) = 38 82 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-05 14:18:13.206  4323  4508 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 fe 16 22 7c 24 94 06 79 87 d9 4a 95 14 02 ba 
07-05 14:18:13.206  4323  4508 W bt-btm  : Stopping oneshot timer
07-05 14:18:13.234  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:18:13.260  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
,07-05 14:19:00.056  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:19:00.057  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 14:19:00.057  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:19:00.057  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:19:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:19:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:19:00.075  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:19:00.079  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:19:35.977  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-05 14:19:35.987  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 14:19:35.997  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:19:35.997  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:19:36.000  1035  1545 D WifiController: battery changed pluggedType: 2
07-05 14:19:36.001  4323  4443 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:19:36.004  1940  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 14:19:36.004  1940  2071 D LEDHandler: Battery Level Remaining: 100%
07-05 14:19:36.004  1940  2071 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
07-05 14:19:36.005  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
07-05 14:19:36.006  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:19:36.007  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 14:19:36.012  6695  6695 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 14:20:00.058  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:20:00.058  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:20:00.058  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 14:20:00.059  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:20:00.072  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 14:20:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:20:00.075  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-05 14:20:00.076  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:20:45.144  1035  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=133954963, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,07-05 14:20:45.159  1035  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b6be217 type 2 when 976351 com.google.android.gms} when 976351
07-05 14:20:45.162  1035  1380 V AlarmManager: RTC_WAKEUP set : Alarm{209c7604 type 0 when 1467721178431 com.google.android.gms} when 1467721178431
,07-05 14:20:45.199  2626  2626 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 14:20:45.235  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=133954963 [*alarm*], flags=0x0
,07-05 14:20:45.250  1816  6936 I EventLogService: Aggregate from 1467720188210 (log), 1467719378355 (data)
,07-05 14:20:45.340  2120  6251 D GCM     : Message class com.google.e.a.a.h
,07-05 14:21:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:21:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:21:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 14:21:00.061  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-05 14:21:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:21:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:21:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:21:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:22:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:22:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 14:22:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:22:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:22:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:22:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:22:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:22:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:22:45.384  1035  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:23:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:23:00.058  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 14:23:00.058  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:23:00.060  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:23:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:23:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:23:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:23:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:24:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 14:24:00.051  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:24:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:24:00.052  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:24:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:24:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:24:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:24:00.076  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:25:00.059  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:25:00.059  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 14:25:00.059  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:25:00.060  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:25:00.074  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:25:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:25:00.077  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:25:00.082  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:26:00.074  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:26:00.075  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 14:26:00.075  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:26:00.075  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:26:00.089  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:26:00.090  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:26:00.092  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:26:00.095  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:27:00.075  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:27:00.076  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:27:00.076  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 14:27:00.076  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-05 14:27:00.090  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 14:27:00.090  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:27:00.093  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-05 14:27:00.095  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:28:00.108  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 14:28:00.108  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 14:28:00.109  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 14:28:00.109  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
