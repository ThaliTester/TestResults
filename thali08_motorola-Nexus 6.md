#### Test 7968977568865f7_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-02 10:40:53.586  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:40:53.591  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-02 10:40:53.623  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-02 10:40:53.623  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:40:53.623  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:40:53.623  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-02 10:40:53.642  3494  3749 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 10:40:53.642  3494  3749 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at blb.a(PG:3937)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at czp.a(PG:18188)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:40:53.642  3494  3749 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	... 12 more
08-02 10:40:53.642  3494  3749 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at fal.a(PG:38)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:40:53.642  3494  3749 E HttpOperation: 	... 14 more
08-02 10:40:53.693  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-02 10:40:53.693  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:40:53.693  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:40:53.693  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-02 10:40:53.706  3494  3749 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 10:40:53.706  3494  3749 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at hec.a(PG:42)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at hee.a(PG:102)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at czr.a(PG:65)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at kka.a(PG:108)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at czp.a(PG:19176)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:40:53.706  3494  3749 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	... 15 more
08-02 10:40:53.706  3494  3749 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at fal.a(PG:38)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:40:53.706  3494  3749 E HttpOperation: 	... 17 more
08-02 10:40:53.707  3494  3749 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 10:40:53.707  3494  3749 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at hec.a(PG:42)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at hee.a(PG:102)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at czr.a(PG:65)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at kka.a(PG:108)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	... 15 more
08-02 10:40:53.707  3494  3749 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at fal.a(PG:38)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 10:40:53.707  3494  3749 E ExperimentLoader: 	... 17 more
08-02 10:40:53.855   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 248514, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
08-02 10:40:54.195  3750  3750 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-02 10:40:54.199  3750  3750 D AndroidRuntime: CheckJNI is OFF
08-02 10:40:54.236  3750  3750 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-02 10:40:54.280  3750  3750 I Radio-JNI: register_android_hardware_Radio DONE
08-02 10:40:54.301  3750  3750 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-02 10:40:54.306   871  1698 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-02 10:40:54.353   871  1698 I ActivityManager: Start proc 3760:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-02 10:40:54.356  3750  3750 D AndroidRuntime: Shutting down VM
08-02 10:40:54.462  3760  3760 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-02 10:40:54.509  3760  3760 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-02 10:40:54.519  3760  3760 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9780-9785)
08-02 10:40:54.520  3760  3760 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-02 10:40:54.540  3760  3760 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38e2893}
08-02 10:40:54.541  3760  3760 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-02 10:40:54.541  3760  3760 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-02 10:40:54.548  3760  3760 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-02 10:40:54.550  3760  3760 E SysUtils: ApplicationContext is null in ApplicationStatus
08-02 10:40:54.574  3760  3760 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-02 10:40:54.589  3760  3760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-02 10:40:54.589  3760  3760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-02 10:40:54.589  3760  3760 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-02 10:40:54.589  3760  3760 I Adreno  : Build Date                       : 10/20/15
08-02 10:40:54.589  3760  3760 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-02 10:40:54.589  3760  3760 I Adreno  : Local Branch                     : M14
08-02 10:40:54.589  3760  3760 I Adreno  : Remote Branch                    : 
08-02 10:40:54.589  3760  3760 I Adreno  : Remote Branch                    : 
08-02 10:40:54.589  3760  3760 I Adreno  : Reconstruct Branch               : 
,08-02 10:40:54.673   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e77b6e0:true
,08-02 10:40:54.734  3760  3760 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-02 10:40:54.754  3760  3760 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-02 10:40:54.839  3760  3797 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-02 10:40:54.859  3760  3784 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-02 10:40:54.917  3760  3797 I OpenGLRenderer: Initialized EGL, version 1.4
,08-02 10:40:54.973   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms (total +633ms)
,08-02 10:40:54.976  1648  1648 I Keyboard.Facilitator: onFinishInput()
,08-02 10:40:54.981   871   880 I art     : Background partial concurrent mark sweep GC freed 35230(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.421ms total 104.522ms
,08-02 10:40:55.019  3760  3760 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3760
,08-02 10:40:55.104  3760  3760 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-02 10:40:55.331  3760  3800 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1688532688
,08-02 10:40:55.341  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-02 10:40:55.341  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-02 10:40:55.341  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-02 10:40:55.341  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-02 10:40:55.341  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-02 10:40:55.341  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73f4966 added. We now have 1 listener(s)
,08-02 10:40:55.346  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-02 10:40:55.347  3760  3800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 10:40:55.348  3760  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 10:40:55.348  3760  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-02 10:40:55.354  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@777f4fd added. We now have 1 listener(s)
08-02 10:40:55.355  3760  3800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 10:40:55.363   871  1302 D WifiService: New client listening to asynchronous messages
,08-02 10:40:55.366  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:40:55.367  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-02 10:40:55.367  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-02 10:40:55.368  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-02 10:40:55.369  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-02 10:40:55.376  3760  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:40:55.376  3760  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-02 10:40:55.389  3760  3800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:40:55.389  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:40:55.389  3760  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-02 10:40:55.389  3760  3800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-02 10:40:55.391  3760  3800 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-02 10:40:55.399  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:40:55.409  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:40:55.437  3760  3760 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-02 10:40:56.159  3760  3806 W jxcore-log: Initializing JXcore engine
,08-02 10:40:56.159  3760  3806 W jxcore-log: JXcore engine is ready
,08-02 10:40:56.207  3806  3806 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-02 10:40:56.207  3806  3806 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12759]" dev="sockfs" ino=12759 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-02 10:40:56.207  3806  3806 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-02 10:40:56.207  3806  3806 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27983]" dev="sockfs" ino=27983 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-02 10:40:56.218  3760  3806 W jxcore-log: Starting JXcore engine
,08-02 10:40:56.298  3760  3806 W jxcore-log: Platform android
08-02 10:40:56.298  3760  3806 W jxcore-log: 
08-02 10:40:56.298  3760  3806 W jxcore-log: Process ARCH arm
08-02 10:40:56.298  3760  3806 W jxcore-log: 
,08-02 10:40:56.459  3760  3806 I jxcore-log: JXcore Cordova bridge is ready!
08-02 10:40:56.459  3760  3806 I jxcore-log: 
,08-02 10:40:56.460  3760  3806 W jxcore-log: JXcore engine is started
,08-02 10:40:56.469  3760  3800 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-02 10:40:56.475  3760  3760 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-02 10:41:06.246  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-02 10:41:06.246  3760  3806 I jxcore-log: 
,08-02 10:41:06.249  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-02 10:41:06.249  3760  3806 I jxcore-log: 
,08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.262  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:06.269  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 10:41:06.272  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-02 10:41:06.272  3760  3806 I jxcore-log: 
,08-02 10:41:06.274  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-02 10:41:06.274  3760  3806 I jxcore-log: 
,08-02 10:41:06.599  3760  3806 D ExecuteNativeTests: Running unit tests
,08-02 10:41:06.659  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-02 10:41:06.659  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 added. We now have 2 listener(s)
08-02 10:41:06.660  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 10:41:06.660  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 10:41:06.660  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:06.661  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:06.661  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d added. We now have 2 listener(s)
,08-02 10:41:06.661  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:06.661  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:41:06.665  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.679  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:06.684  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.684  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-02 10:41:06.686  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-02 10:41:06.688  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-02 10:41:06.688  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-02 10:41:06.690  3760  3806 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-02 10:41:06.690  3760  3806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-02 10:41:06.690  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-02 10:41:06.690  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-02 10:41:06.690  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-02 10:41:06.691  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-02 10:41:06.691  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-02 10:41:06.691  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.691  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.695  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:06.695  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.695  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:06.695  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:06.695  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 removed from the list
08-02 10:41:06.695  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.695  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d removed from the list
08-02 10:41:06.700  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.701  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.701  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.701  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.701  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:06.704  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.704  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-02 10:41:06.704  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.704  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
,08-02 10:41:06.706  3760  3806 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-02 10:41:06.706  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-02 10:41:06.706  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-02 10:41:06.706  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.707  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:06.707  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-02 10:41:06.707  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.707  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.707  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:06.707  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.707  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.707  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.707  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.707  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.707  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.708  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.708  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.708  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:06.708  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.712  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-02 10:41:06.712  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-02 10:41:06.712  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-02 10:41:06.713  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-02 10:41:06.714  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-02 10:41:06.714  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.714  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.714  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.714  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.714  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.714  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.714  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.715  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.715  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.715  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.715  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.715  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:06.715  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.715  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.716  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.716  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.716  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.716  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.716  3760  3806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-02 10:41:06.717  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.722  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:06.724  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.724  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 10:41:06.724  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:06.724  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 10:41:06.724  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 10:41:06.724  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.724  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-02 10:41:06.726  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.728  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-02 10:41:06.728  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-02 10:41:06.728  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:06.733  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-02 10:41:06.735  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-02 10:41:06.735  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-02 10:41:06.739  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-02 10:41:06.743  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-02 10:41:06.743  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-02 10:41:06.743  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-02 10:41:06.744  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-02 10:41:06.746  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:06.756  2615  2628 D BtGatt.GattService: registerClient() - UUID=75cf8f4e-870c-4e4a-a19b-2a6388d2abbf
,08-02 10:41:06.757  2615  2635 D BtGatt.GattService: onClientRegistered() - UUID=75cf8f4e-870c-4e4a-a19b-2a6388d2abbf, clientIf=5
,08-02 10:41:06.758  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-02 10:41:06.762  2615  2627 D BtGatt.GattService: start scan with filters
,08-02 10:41:06.769  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-02 10:41:06.769  2615  2638 D BtGatt.ScanManager: handling starting scan
,08-02 10:41:06.769  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-02 10:41:06.769  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-02 10:41:06.769  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-02 10:41:06.770  2615  2638 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:06.771  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:06.772  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:06.772  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-02 10:41:06.773  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-02 10:41:06.776  3760  3806 I io.jxcore.node.ConnectionHelper: start: OK
08-02 10:41:06.778  2615  2635 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-02 10:41:06.778  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:06.778  2615  2638 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-02 10:41:06.779  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.779  3760  3806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-02 10:41:06.779  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.779  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-02 10:41:06.779  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-02 10:41:06.779  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 10:41:06.779  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 10:41:06.779  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-02 10:41:06.779  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-02 10:41:06.779  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:06.780  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-02 10:41:06.780  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-02 10:41:06.780  3760  3806 D BluetoothAdapter: STATE_ON
08-02 10:41:06.781  2615  2628 D BtGatt.GattService: stopScan() - queue size =1
,08-02 10:41:06.781  2615  2786 D BtGatt.GattService: unregisterClient() - clientIf=5
08-02 10:41:06.782  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-02 10:41:06.782  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-02 10:41:06.782  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-02 10:41:06.782  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-02 10:41:06.782  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-02 10:41:06.782  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.783  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-02 10:41:06.783  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-02 10:41:06.783  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 10:41:06.783  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-02 10:41:06.784  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.784  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.784  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.784  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.784  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.785  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-02 10:41:06.785  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.785  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:06.785  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
,08-02 10:41:06.785  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
,08-02 10:41:06.785  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:06.785  3760  3806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-02 10:41:06.786  2615  2635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-02 10:41:06.786  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.787  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 10:41:06.787  2615  2638 D BtGatt.ScanManager: Starting BLE batch scan
08-02 10:41:06.787  2615  2638 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.792  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:06.795  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.795  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-02 10:41:06.796  2615  2635 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-02 10:41:06.796  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.797  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:06.797  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-02 10:41:06.797  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 10:41:06.797  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.798  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.798  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-02 10:41:06.800  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.803  2615  2635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-02 10:41:06.803  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:06.808  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-02 10:41:06.808  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-02 10:41:06.810  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-02 10:41:06.811  2615  2635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-02 10:41:06.811  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.811  2615  2638 D BtGatt.ScanManager: stopping BLe Batch
08-02 10:41:06.811  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-02 10:41:06.811  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-02 10:41:06.815  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-02 10:41:06.815  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-02 10:41:06.815  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-02 10:41:06.815  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:06.818  2615  2786 D BtGatt.GattService: registerClient() - UUID=e0b198be-d7a5-4e4e-b4a5-6cc3356dbb3b
08-02 10:41:06.818  2615  2635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-02 10:41:06.818  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.818  2615  2638 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-02 10:41:06.818  2615  2635 D BtGatt.GattService: onClientRegistered() - UUID=e0b198be-d7a5-4e4e-b4a5-6cc3356dbb3b, clientIf=5
08-02 10:41:06.818  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-02 10:41:06.819  2615  2785 D BtGatt.GattService: start scan with filters
,08-02 10:41:06.821  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-02 10:41:06.821  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-02 10:41:06.821  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-02 10:41:06.821  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-02 10:41:06.823  2615  2635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-02 10:41:06.823  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:06.825  2615  2638 D BtGatt.ScanManager: handling starting scan
08-02 10:41:06.823  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:06.825  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:06.825  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-02 10:41:06.826  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-02 10:41:06.829  3760  3806 I io.jxcore.node.ConnectionHelper: start: OK
,08-02 10:41:06.831  2615  2635 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-02 10:41:06.831  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:06.831  2615  2638 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-02 10:41:06.833  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-02 10:41:06.833  3760  3806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-02 10:41:06.833  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.833  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-02 10:41:06.833  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.834  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 10:41:06.834  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 10:41:06.834  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 10:41:06.834  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 10:41:06.834  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:06.834  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-02 10:41:06.834  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-02 10:41:06.835  3760  3806 D BluetoothAdapter: STATE_ON
08-02 10:41:06.835  2615  2786 D BtGatt.GattService: stopScan() - queue size =1
08-02 10:41:06.836  2615  2785 D BtGatt.GattService: unregisterClient() - clientIf=5
08-02 10:41:06.836  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-02 10:41:06.836  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-02 10:41:06.836  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-02 10:41:06.836  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-02 10:41:06.836  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-02 10:41:06.837  2615  2635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-02 10:41:06.837  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.837  2615  2638 D BtGatt.ScanManager: Starting BLE batch scan
08-02 10:41:06.837  2615  2638 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-02 10:41:06.837  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.838  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-02 10:41:06.838  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-02 10:41:06.838  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 10:41:06.839  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:06.841  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.841  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.841  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.841  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.841  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.841  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:06.841  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.841  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.841  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.841  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.841  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.842  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.843  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.844  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.844  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.844  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.844  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.845  2615  2635 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-02 10:41:06.845  3760  3806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-02 10:41:06.845  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.848  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.850  2615  2635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-02 10:41:06.850  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.853  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:06.856  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.856  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 10:41:06.856  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:06.856  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 10:41:06.856  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 10:41:06.856  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.857  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-02 10:41:06.858  2615  2635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-02 10:41:06.859  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.860  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-02 10:41:06.861  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-02 10:41:06.861  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.858  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.861  2615  2638 D BtGatt.ScanManager: stopping BLe Batch
08-02 10:41:06.864  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-02 10:41:06.865  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-02 10:41:06.865  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-02 10:41:06.867  2615  2635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-02 10:41:06.867  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.867  2615  2638 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-02 10:41:06.869  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-02 10:41:06.869  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-02 10:41:06.869  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-02 10:41:06.869  3760  3806 D BluetoothAdapter: STATE_ON
08-02 10:41:06.871  2615  2785 D BtGatt.GattService: registerClient() - UUID=fe198aa0-cf40-41f0-8792-b5cacbd39af4
08-02 10:41:06.871  2615  2635 D BtGatt.GattService: onClientRegistered() - UUID=fe198aa0-cf40-41f0-8792-b5cacbd39af4, clientIf=5
08-02 10:41:06.871  3760  3770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-02 10:41:06.871  2615  2627 D BtGatt.GattService: start scan with filters
08-02 10:41:06.873  2615  2635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-02 10:41:06.873  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.874  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-02 10:41:06.874  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-02 10:41:06.874  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-02 10:41:06.874  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-02 10:41:06.875  2615  2638 D BtGatt.ScanManager: handling starting scan
08-02 10:41:06.876  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:06.876  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-02 10:41:06.876  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:06.877  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-02 10:41:06.880  3760  3806 I io.jxcore.node.ConnectionHelper: start: OK
08-02 10:41:06.880  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.880  3760  3806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-02 10:41:06.880  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.880  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-02 10:41:06.880  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.880  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 10:41:06.880  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 10:41:06.880  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 10:41:06.880  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 10:41:06.880  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:06.880  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-02 10:41:06.880  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-02 10:41:06.881  3760  3806 D BluetoothAdapter: STATE_ON
08-02 10:41:06.881  2615  2627 D BtGatt.GattService: stopScan() - queue size =1
08-02 10:41:06.882  2615  2786 D BtGatt.GattService: unregisterClient() - clientIf=5
08-02 10:41:06.882  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-02 10:41:06.882  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-02 10:41:06.882  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-02 10:41:06.882  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-02 10:41:06.882  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-02 10:41:06.883  2615  2635 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-02 10:41:06.883  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.883  2615  2638 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-02 10:41:06.883  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.884  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-02 10:41:06.884  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-02 10:41:06.884  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 10:41:06.884  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:06.885  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.885  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.885  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.886  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.886  3760  3806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-02 10:41:06.886  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.886  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.886  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.886  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.886  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:06.886  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.886  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.886  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.886  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.886  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.887  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.887  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.887  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.887  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.887  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.887  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.888  3760  3806 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-02 10:41:06.888  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.888  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.888  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.888  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.888  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.889  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.889  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.889  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.889  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.889  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.889  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.889  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.889  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.889  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.889  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.889  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.890  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.890  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.890  2615  2635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-02 10:41:06.890  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.890  2615  2638 D BtGatt.ScanManager: Starting BLE batch scan
08-02 10:41:06.890  2615  2638 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-02 10:41:06.890  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-02 10:41:06.890  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.891  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.891  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.891  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.891  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.891  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.891  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.891  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.891  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.891  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.891  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.891  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.891  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.891  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.892  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.892  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.892  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.892  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.893  3760  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-02 10:41:06.893  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.893  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.893  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.893  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.893  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.893  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.893  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.893  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.893  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.893  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.893  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.894  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.894  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.894  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.895  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.895  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.895  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.895  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.895  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-02 10:41:06.895  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.895  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.895  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.895  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.895  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.896  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.896  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.896  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.896  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.896  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.896  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.896  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.896  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.896  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.897  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.897  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.897  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.897  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.897  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-02 10:41:06.898  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-02 10:41:06.898  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-02 10:41:06.899  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-02 10:41:06.899  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-02 10:41:06.899  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-02 10:41:06.899  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.899  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.899  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.899  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.899  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.900  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.900  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.900  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.900  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.900  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
,08-02 10:41:06.900  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-02 10:41:06.900  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.900  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.900  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-02 10:41:06.902  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.902  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.902  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.902  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
,08-02 10:41:06.903  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 10:41:06.903  3760  3806 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-02 10:41:06.903  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-02 10:41:06.903  2615  2635 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-02 10:41:06.903  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.906  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 10:41:06.906  3760  3806 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-02 10:41:06.906  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-02 10:41:06.907  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-02 10:41:06.908  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-02 10:41:06.908  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-02 10:41:06.908  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-02 10:41:06.908  3760  3806 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-02 10:41:06.908  3760  3806 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-02 10:41:06.908  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 10:41:06.909  3760  3806 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-02 10:41:06.909  3760  3806 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-02 10:41:06.909  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 10:41:06.909  3760  3806 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-02 10:41:06.909  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-02 10:41:06.910  2615  2635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-02 10:41:06.910  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:06.912  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-02 10:41:06.913  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-02 10:41:06.913  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-02 10:41:06.913  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-02 10:41:06.913  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-02 10:41:06.913  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-02 10:41:06.914  3760  3806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 10:41:06.914  3760  3806 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-02 10:41:06.914  3760  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
,08-02 10:41:06.914  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.914  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.914  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.914  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.914  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.915  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:06.915  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-02 10:41:06.915  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.915  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.915  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.915  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.915  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.915  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.915  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.915  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.916  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.916  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.916  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.916  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.916  3760  3807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-02 10:41:06.917  3760  3806 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-02 10:41:06.917  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.917  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.917  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.917  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.917  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.917  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.917  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.917  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.918  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.918  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.918  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.918  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.918  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMa,nager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.918  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.919  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.919  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.919  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.919  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.919  3760  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-02 10:41:06.919  3760  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
08-02 10:41:06.919  3760  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-02 10:41:06.919  3760  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
08-02 10:41:06.919  3760  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-02 10:41:06.919  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.919  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.919  2615  2762 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-02 10:41:06.920  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.920  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.920  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.920  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.920  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.920  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.920  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.920  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.920  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.920  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.920  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.920  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.921  2615  2635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-02 10:41:06.921  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.921  2615  2638 D BtGatt.ScanManager: stopping BLe Batch
08-02 10:41:06.921  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.921  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.921  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.921  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.922  3760  3806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-02 10:41:06.922  3760  3806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-02 10:41:06.922  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-02 10:41:06.923  3760  3806 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-02 10:41:06.923  3760  3806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-02 10:41:06.923  3760  3806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-02 10:41:06.924  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-02 10:41:06.924  3760  3806 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-02 10:41:06.924  3760  3806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-02 10:41:06.924  3760  3806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-02 10:41:06.924  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-02 10:41:06.924  3760  3806 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-02 10:41:06.924  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.924  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.924  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.924  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.924  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.924  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.924  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.924  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.925  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.925  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.925  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.925  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.925  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.925  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.926  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.926  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.926  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.926  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.926  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.926  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.926  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.926  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.926  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.927  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.927  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.927  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.927  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.927  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.927  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.927  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.927  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.927  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.927  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.927  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.927  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.928  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.928  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.928  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.928  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.928  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.928  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.928  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.928  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.928  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.928  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.928  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.928  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.929  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.929  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.929  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.929  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.930  3760  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-02 10:41:06.930  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.931  2615  2635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-02 10:41:06.931  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.931  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-02 10:41:06.931  2615  2638 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-02 10:41:06.932  3760  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-02 10:41:06.932  3760  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-02 10:41:06.932  3760  3760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-02 10:41:06.932  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-02 10:41:06.932  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 10:41:06.932  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.933  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-02 10:41:06.933  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-02 10:41:06.933  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-02 10:41:06.933  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.933  3760  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-02 10:41:06.933  3760  3760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-02 10:41:06.933  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.933  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.933  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 10:41:06.933  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 10:41:06.933  3760  3809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-02 10:41:06.933  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:06.933  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.933  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.934  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.934  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.934  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:06.934  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:06.934  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.935  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.935  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.935  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.935  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.935  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.935  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.935  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.935  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.935  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.935  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.935  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.935  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.935  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.935  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.936  3760  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-02 10:41:06.936  3760  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-02 10:41:06.936  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.936  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.936  3760  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-02 10:41:06.936  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.936  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.936  3760  3760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-02 10:41:06.937  3760  3806 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-02 10:41:06.937  3760  3806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-02 10:41:06.937  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-02 10:41:06.938  2615  2635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-02 10:41:06.938  2615  2635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:06.939  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-02 10:41:06.939  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.939  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.939  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.939  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.939  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.939  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.939  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.939  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.939  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.939  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.939  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.939  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.940  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.940  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.941  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.941  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.941  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.941  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.943  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.943  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.943  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.943  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.943  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.943  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.943  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.943  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.944  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.944  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.944  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.944  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.944  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.944  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.945  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.945  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.945  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.945  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.945  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:06.945  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:06.945  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:06.946  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:06.946  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.946  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.946  3760  3806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c09e24 not in the list
08-02 10:41:06.946  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.946  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.946  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:06.946  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.946  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.946  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:06.946  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:06.947  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:06.947  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:06.947  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:06.947  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a7d8d not in the list
08-02 10:41:06.947  3760  3806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-02 10:41:06.947  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-02 10:41:06.947  3760  3806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-02 10:41:06.947  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-02 10:41:06.948  3760  3806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-02 10:41:06.948  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-02 10:41:06.949  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-02 10:41:06.949  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-02 10:41:06.949  3760  3806 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-02 10:41:06.949  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-02 10:41:06.949  3760  3806 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-02 10:41:06.950  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-02 10:41:06.950  3760  3806 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-02 10:41:06.950  3760  3806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-02 10:41:06.950  3760  3806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-02 10:41:06.950  3760  3806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-02 10:41:06.950  3760  3806 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-02 10:41:06.951  3760  3806 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-02 10:41:06.951  3760  3806 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-02 10:41:06.951  3760  3806 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-02 10:41:06.951  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:06.951  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a731ba7 added. We now have 2 listener(s)
08-02 10:41:06.951  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:06.952  3760  3806 D BluetoothAdapter: enable(): BT is already enabled..!
08-02 10:41:06.953   871   881 D WifiService: setWifiEnabled: true pid=3760, uid=10000
08-02 10:41:06.953   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-02 10:41:06.953  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:06.953  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f99d854 added. We now have 3 listener(s)
08-02 10:41:06.953  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:06.958  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:06.958  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@962e3fd added. We now have 4 listener(s)
08-02 10:41:06.958  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:06.960  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:06.961  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34058f2 added. We now have 5 listener(s)
08-02 10:41:06.961  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:06.964   871  1730 D WifiService: setWifiEnabled: false pid=3760, uid=10000
08-02 10:41:06.964   871  1730 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 10:41:06.968  2615  2631 D BluetoothAdapterState: Current state: ON, message: 23
08-02 10:41:06.968  2615  2631 D BluetoothAdapterProperties: Setting state to 13
08-02 10:41:06.968  2615  2631 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-02 10:41:06.968  2615  2631 D BluetoothAdapterProperties: onBluetoothDisable()
08-02 10:41:06.969  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:06.970  2615  2615 D BluetoothMapService: onReceive
08-02 10:41:06.970  2615  2615 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-02 10:41:06.970  2615  2615 D BluetoothMapService: STATE_TURNING_OFF
08-02 10:41:06.971  2615  2631 I BluetoothAdapterState: Entering PendingCommandState
08-02 10:41:06.971  2615  2615 D BluetoothMapService: MAP Service closeService in
08-02 10:41:06.971  2615  2615 D BluetoothMapMasInstance0: MAP Service shutdown
08-02 10:41:06.971  2615  2615 D ObexServerSockets0: shutdown(block = true)
08-02 10:41:06.971  2615  2615 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 10:41:06.972  2615  2615 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 10:41:06.972  2615  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-02 10:41:06.972  2615  2762 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-02 10:41:06.972  2615  2788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-02 10:41:06.973  2615  2615 I BtOppRfcommListener: stopping Accept Thread
08-02 10:41:06.973  2615  3380 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-02 10:41:06.973  2615  3380 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-02 10:41:06.976  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.976  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:06.977  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:06.977  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.977  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 10:41:06.981   871   884 I ActivityManager: Start proc 3812:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-02 10:41:06.981  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.982  2615  2635 D BluetoothAdapterProperties: Scan Mode:20
08-02 10:41:06.982  2615  2631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-02 10:41:06.983  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.983  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-02 10:41:06.985   871  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-02 10:41:06.985   871  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-02 10:41:06.986   871  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-02 10:41:06.986   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-02 10:41:06.988  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:06.988  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:06.988  2615  2615 D HeadsetService: Received stop request...Stopping profile...
08-02 10:41:06.988  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:06.988  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:06.991  1358  1385 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:06.992   871   871 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:06.992  1713  1725 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:06.994  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.993   871   871 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:06.994   871   871 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:06.996   871  1301 E native  : do suspend true
08-02 10:41:06.996  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.993  2615  2615 D A2dpService: Received stop request...Stopping profile...
08-02 10:41:06.999  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:06.999  2615  2768 D A2dpStateMachine: Exit Disconnected: -1
08-02 10:41:07.000  1358  1358 D HeadsetProfile: Bluetooth service disconnected
08-02 10:41:07.001   871   871 D BluetoothA2dp: Proxy object disconnected
08-02 10:41:07.001  1358  1358 D BluetoothA2dp: Proxy object disconnected
08-02 10:41:07.002  2615  2615 D HidService: Received stop request...Stopping profile...
08-02 10:41:07.002  2615  2615 D HidService: Stopping Bluetooth HidService
08-02 10:41:07.003  1358  1358 D BluetoothInputDevice: Proxy object disconnected
08-02 10:41:07.003  1358  1358 D HidProfile: Bluetooth service disconnected
08-02 10:41:07.003  2615  2615 D HealthService: Received stop request...Stopping profile...
,08-02 10:41:07.005  2615  2615 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:07.005  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.005  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:07.005  2615  2615 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:07.006  2615  2615 D PanService: Received stop request...Stopping profile...
,08-02 10:41:07.006   871  2012 D DhcpClient: Clearing IP address
,08-02 10:41:07.006   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-02 10:41:07.007  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-02 10:41:07.007  1358  1358 D PanProfile: Bluetooth service disconnected
08-02 10:41:07.008  2615  2615 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-02 10:41:07.008  2615  2615 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-02 10:41:07.008  2615  2635 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-02 10:41:07.009   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:07.008  2615  2738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:07.009  2615  2738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:07.009  2615  2738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-02 10:41:07.009  2615  2635 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-02 10:41:07.009  2615  2615 D BluetoothMapService: Received stop request...Stopping profile...
08-02 10:41:07.010  2615  2615 D BluetoothMapService: stop()
,08-02 10:41:07.010  2615  2615 D BluetoothMapAppObserver: deinitObservers()
08-02 10:41:07.010  2615  2615 D BluetoothMapAppObserver: removeReceiver()
08-02 10:41:07.012  1358  1358 D BluetoothMap: Proxy object disconnected
08-02 10:41:07.012  1358  1358 D MapProfile: Bluetooth service disconnected
08-02 10:41:07.012  2615  2615 V BluetoothAdapterState: isTurningOff()=true
,08-02 10:41:07.012  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.012  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:07.012  2615  2615 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:07.013  2615  2738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:07.013  2615  2738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:07.013  2615  2738 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-02 10:41:07.014  2615  2738 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-02 10:41:07.014  2615  2738 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-02 10:41:07.014  2615  2738 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-02 10:41:07.014  2615  2635 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-02 10:41:07.014  2615  2615 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:07.014  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.014  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:07.014  2615  2615 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:07.014  2615  2615 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-02 10:41:07.015  2615  2635 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-02 10:41:07.015  2615  2615 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-02 10:41:07.015  2615  2615 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:07.015  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.015  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:07.015  2615  2615 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:07.015  2615  2615 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-02 10:41:07.015  2615  2635 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-02 10:41:07.016  2615  2615 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-02 10:41:07.016  2615  2615 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:07.016  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.016  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 10:41:07.016  2615  2615 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:07.017  2615  2615 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-02 10:41:07.017  1513  2239 V NativeCrypto: Read error: ssl=0xaa27b200: I/O error during system call, Connection timed out
08-02 10:41:07.017  2615  2615 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-02 10:41:07.018  2615  2615 D BluetoothMapService: MAP Service closeService in
08-02 10:41:07.018  2615  2615 V BluetoothAdapterState: isTurningOff()=true
,08-02 10:41:07.018  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.018  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:07.018  2615  2615 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:07.019  2615  2631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-02 10:41:07.019  2615  2631 D BluetoothAdapterProperties: Setting state to 15
08-02 10:41:07.019  2615  2631 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-02 10:41:07.019  2615  2631 I BluetoothAdapterState: Entering BleOnState
08-02 10:41:07.019  1513  2239 V NativeCrypto: SSL shutdown failed: ssl=0xaa27b200: I/O error during system call, Broken pipe
08-02 10:41:07.020   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-02 10:41:07.021   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-02 10:41:07.022  2615  2615 D BluetoothMapService: cleanup()
08-02 10:41:07.022  2615  2615 D BluetoothMapService: MAP Service closeService in
08-02 10:41:07.023   403   403 E Parcel  : Reading a NULL string not supported here.
08-02 10:41:07.023   871  2019 D DhcpClient: Receive thread stopped
08-02 10:41:07.024  1358  1817 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 10:41:07.025   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:07.025   871  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-02 10:41:07.025  1358  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-02 10:41:07.026   871  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-02 10:41:07.026   871  1301 E native  : do suspend true
08-02 10:41:07.027  1358  1817 D BluetoothPbap: onBluetoothStateChange: up=false
08-02 10:41:07.028  1358  1382 D BluetoothMap: onBluetoothStateChange: up=false
08-02 10:41:07.028   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:07.028   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-02 10:41:07.029  1358  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:07.029  1713  1906 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:07.029   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:07.029  1358  1985 D BluetoothPan: onBluetoothStateChange on: false
08-02 10:41:07.030  2615  2631 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-02 10:41:07.030  2615  2631 D BluetoothAdapterProperties: Setting state to 16
08-02 10:41:07.030  2615  2631 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-02 10:41:07.031  2615  2631 D BluetoothAdapterProperties: onBleDisable
08-02 10:41:07.031  2615  2631 I BluetoothAdapterState: Entering PendingCommandState
,08-02 10:41:07.031  2615  2632 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-02 10:41:07.031  2615  2738 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-02 10:41:07.032  2615  2738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:07.033  2615  2635 D BluetoothAdapterProperties: Scan Mode:20
08-02 10:41:07.034  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:07.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:07.030   871  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-02 10:41:07.035  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.035  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:07.037  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:07.037  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:07.038  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.038  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:07.038   370   869 D CommandListener: Clearing all IP addresses on wlan0
08-02 10:41:07.039  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:07.039   871  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-02 10:41:07.040  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:07.056   871  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 10:41:07.059  1844  2072 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-02 10:41:07.059  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:07.059  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:07.059  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.060  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:07.061  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:07.061  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 10:41:07.061   871  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-02 10:41:07.061  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:07.061  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:07.066  3812  3812 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-02 10:41:07.068   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:07.076  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 10:41:07.080   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85397a5:true
,08-02 10:41:07.082  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 10:41:07.096   871  1691 I ActivityManager: Start proc 3828:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-02 10:41:07.102   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:07.103   871  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-02 10:41:07.103   871  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:07.105   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-02 10:41:07.108  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:07.109  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:07.115  3366  3366 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@93384a7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-02 10:41:07.115  1798  1798 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-02 10:41:07.125  3812  3812 D LocalBluetoothProfileManager: Adding local MAP profile
,08-02 10:41:07.127  3812  3812 D BluetoothMap: Create BluetoothMap proxy object
,08-02 10:41:07.133  3828  3828 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-02 10:41:07.136  3812  3812 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-02 10:41:07.153  3812  3812 D DockEventReceiver: finishStartingService: stopping service
,08-02 10:41:07.156   871  1771 I ActivityManager: Killing 2959:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-02 10:41:07.172   370   869 E Netd    : netlink response contains error (No such file or directory)
,08-02 10:41:07.173   871  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-02 10:41:07.234  2615  2635 I bt_hci  : shut_down
,08-02 10:41:07.235  2615  2639 D bt_hwcfg: hw_epilog_process
,08-02 10:41:07.236  2615  2639 I bt_vendor: low_power_mode_cb
,08-02 10:41:07.267  2615  2639 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-02 10:41:07.267  2615  2639 I bt_vendor: epilog_cb
08-02 10:41:07.267  2615  2639 I bt_hci  : epilog_finished_callback
08-02 10:41:07.272  2615  2635 I bt_hci_h4: hal_close
08-02 10:41:07.272  2615  2635 I bt_userial_vendor: device fd = 51 close
,08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.exists(File.java:361)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.e.b(PG:170)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.k.d(PG:583)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.e.b(PG:170)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.exists(File.java:361)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.exists(File.java:361)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287,  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 10:41:07.287  3828  3828 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 10:41:07.287  3828  3828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 10:41:07.293  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-02 10:41:07.303  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.,STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-02 10:41:07.305  3812  3812 D DockEventReceiver: finishStartingService: stopping service
08-02 10:41:07.311   871  1366 I ActivityManager: Killing 3366:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-02 10:41:07.432   871  1366 I ActivityManager: Start proc 3863:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-02 10:41:07.435  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-02 10:41:07.442  2615  2632 D bt_stack_manager: event_shut_down_stack finished.
,08-02 10:41:07.443  2615  2631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-02 10:41:07.447  2615  2631 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-02 10:41:07.449  2615  2615 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-02 10:41:07.451  2615  2615 D BtGatt.GattService: Received stop request...Stopping profile...
08-02 10:41:07.451  2615  2615 D BtGatt.GattService: stop()
,08-02 10:41:07.451  2615  2615 D BtGatt.AdvertiseManager: advertise clients cleared
,08-02 10:41:07.455  2615  2615 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:07.455  2615  2615 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:07.456  2615  2615 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:07.456  2615  2615 V BluetoothAdapterState: isBleTurningOff()=true
,08-02 10:41:07.457  2615  2631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-02 10:41:07.457  2615  2631 D BluetoothAdapterProperties: Setting state to 10
,08-02 10:41:07.458  2615  2631 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-02 10:41:07.462   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-02 10:41:07.462  2615  2631 I BluetoothAdapterState: Entering OffState
,08-02 10:41:07.469  2615  2615 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-02 10:41:07.469  2615  2615 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-02 10:41:07.469  2615  2615 I BluetoothServiceJni: cleanupNative: return from cleanup
08-02 10:41:07.470  2615  2632 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-02 10:41:07.472  2615  2632 D bt_stack_manager: event_clean_up_stack finished.
,08-02 10:41:07.474  2615  2615 I art     : System.exit called, status: 0
,08-02 10:41:07.474  2615  2615 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-02 10:41:07.506  3863  3863 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-02 10:41:07.541   871  1698 I ActivityManager: Process com.android.bluetooth (pid 2615) has died
,08-02 10:41:07.619  3863  3863 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-02 10:41:07.654  1832  1832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-02 10:41:07.657  1832  1832 D SystemUpdateService: onCreate
08-02 10:41:07.662  1832  1832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-02 10:41:07.666  1832  3890 I SystemUpdateService: active receiver: enabled
08-02 10:41:07.670  1832  3890 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-02 10:41:07.672  1832  3890 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-02 10:41:07.672  1832  3890 I SystemUpdateService: now status is 0 (complete)
08-02 10:41:07.672  3828  3858 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-02 10:41:07.672  1832  3890 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-02 10:41:07.672  1832  3890 I SystemUpdateService: file has been verified
08-02 10:41:07.672  1832  1832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-02 10:41:07.675  1832  2342 I iu.UploadsManager: num queued entries: 0
08-02 10:41:07.675  1832  2342 I iu.UploadsManager: num updated entries: 0
08-02 10:41:07.672  1832  3890 I SystemUpdateService: OTA package size = 12249756
,08-02 10:41:07.684  1832  3890 I SystemUpdateService: showing system update notification
,08-02 10:41:07.685  1832  2342 I iu.SyncManager: NEXT; no task
08-02 10:41:07.686  1832  1832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-02 10:41:07.686  1832  1832 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-02 10:41:07.695   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d46de8:true
,08-02 10:41:07.700   871  1767 I ActivityManager: Start proc 3892:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-02 10:41:07.726  1832  1832 D SystemUpdateService: onDestroy
,08-02 10:41:07.733  3892  3892 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-02 10:41:07.736  3892  3892 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:07.741  3892  3892 D SprintDMHelper: simOperator: 
,08-02 10:41:07.741  3892  3892 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-02 10:41:07.753   871  1771 I ActivityManager: Start proc 3904:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-02 10:41:07.754   871  1771 I ActivityManager: Killing 3414:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-02 10:41:07.874  2370  3918 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-02 10:41:07.880   871  1698 I ActivityManager: Start proc 3919:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-02 10:41:07.882   871   881 I ActivityManager: Killing 3009:android.process.acore/u0a5 (adj 15): empty #17
,08-02 10:41:07.965  3919  3919 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-02 10:41:08.018  3919  3919 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-02 10:41:08.018  3919  3919 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-02 10:41:08.018  3919  3919 I GAv4    :   adb logcat -s GAv4
,08-02 10:41:08.033  3919  3919 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-02 10:41:08.039  3919  3919 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-02 10:41:08.068  3919  3936 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-02 10:41:08.161  3919  3919 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-02 10:41:08.191  3919  3919 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-02 10:41:08.197  3919  3919 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3461-3464)
,08-02 10:41:08.198  3919  3919 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-02 10:41:08.217  3919  3919 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {930e597}
,08-02 10:41:08.218  3919  3919 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-02 10:41:08.218  3919  3919 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-02 10:41:08.224  3919  3919 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-02 10:41:08.226  3919  3919 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-02 10:41:08.242  3919  3919 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-02 10:41:08.252  3919  3919 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-02 10:41:08.252  3919  3919 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-02 10:41:08.252  3919  3919 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-02 10:41:08.252  3919  3919 I Adreno  : Build Date                       : 10/20/15
08-02 10:41:08.252  3919  3919 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-02 10:41:08.252  3919  3919 I Adreno  : Local Branch                     : M14
08-02 10:41:08.252  3919  3919 I Adreno  : Remote Branch                    : 
08-02 10:41:08.252  3919  3919 I Adreno  : Remote Branch                    : 
08-02 10:41:08.252  3919  3919 I Adreno  : Reconstruct Branch               : 
,08-02 10:41:08.323  3919  3965 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-02 10:41:08.367  3919  3919 I NSApplication: Starting up...
,08-02 10:41:08.413   871   881 I ActivityManager: Start proc 3970:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-02 10:41:08.415   871   881 I ActivityManager: Killing 3596:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-02 10:41:08.505  3970  3970 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-02 10:41:08.673   871  1526 I ActivityManager: Killing 3611:com.android.musicfx/u0a18 (adj 15): empty #17
,08-02 10:41:09.980   871  1767 D WifiService: setWifiEnabled: true pid=3760, uid=10000
08-02 10:41:09.980   871  1767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 10:41:09.995   871  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-02 10:41:10.002  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:10.003  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:10.003  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 10:41:10.003  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:10.007  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:10.008  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 10:41:10.008  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:10.008  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:10.030   871  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-02 10:41:10.030   871  1301 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-02 10:41:10.031   871  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-02 10:41:10.031   871  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-02 10:41:10.032   871  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-02 10:41:10.033   871  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-02 10:41:10.033   871  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-02 10:41:10.033   871  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-02 10:41:10.058   871  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-02 10:41:10.058   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-02 10:41:10.061   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:10.068   871  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-02 10:41:10.068   871  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-02 10:41:10.070   871  1301 E native  : do suspend true
,08-02 10:41:10.078   871  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-02 10:41:10.078   871  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-02 10:41:10.089   871  1301 D WifiConfigStore: Retrieve network priorities after PNO.,
,08-02 10:41:11.473   871  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-02 10:41:11.513   871  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.38 rxSuccessRate=54.88 delta 1000 -> 994
,08-02 10:41:11.515   871  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-02 10:41:11.515   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 10:41:11.535   871  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-02 10:41:11.592   871  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-02 10:41:11.596  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-02 10:41:12.022  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-02 10:41:12.062  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-02 10:41:12.063  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-02 10:41:12.068   871  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 10:41:12.079   871  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-02 10:41:12.080   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-02 10:41:12.080   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-02 10:41:12.107   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 10:41:12.122   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:12.122   871  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-02 10:41:12.129   871  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-02 10:41:12.169   871  3995 D DhcpClient: Receive thread started
,08-02 10:41:12.257   871  1301 E native  : do suspend false
,08-02 10:41:12.268   871  2012 D DhcpClient: Broadcasting DHCPDISCOVER
,08-02 10:41:12.279   871  3995 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172555, domain null
,08-02 10:41:12.280   871  2012 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172555 seconds
08-02 10:41:12.280   871  2012 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-02 10:41:12.292   871  3995 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-02 10:41:12.292   871  2012 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-02 10:41:12.296   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:12.304   871  2012 D DhcpClient: Scheduling renewal in 86399s
,08-02 10:41:12.305   871  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-02 10:41:12.308   871  1301 E native  : do suspend true
,08-02 10:41:12.331   871  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-02 10:41:12.333   871  1301 D WifiConfigStore: No blacklist allowed without epno enabled
08-02 10:41:12.335   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-02 10:41:12.337   871  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-02 10:41:12.350   871  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-02 10:41:12.417   871  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-02 10:41:12.417   871  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-02 10:41:12.419   871  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-02 10:41:12.422   871  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-02 10:41:12.425   871  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-02 10:41:12.441   871  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-02 10:41:12.447   871  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-02 10:41:12.447   871  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-02 10:41:12.448   871  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-02 10:41:12.448   871  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-02 10:41:12.448   871  1303 D ConnectivityService:    accepting network in place of null
08-02 10:41:12.448   871  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-02 10:41:12.450   871  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-02 10:41:12.459   871  3994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267725, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-02 10:41:12.509   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:12.529   871  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-02 10:41:12.572   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:12.577   871  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-02 10:41:12.577   871  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:12.580   871  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-02 10:41:12.585   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-02 10:41:12.594   871  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Aug 2016 08:41:12 GMT], X-Android-Received-Millis=[1470127272593], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470127272572]}
,08-02 10:41:12.594  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:12.594  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:12.594  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:12.594  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:12.594   871  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-02 10:41:12.595   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-02 10:41:12.595   871  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-02 10:41:12.596   871  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-02 10:41:12.598  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:12.598  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:12.598  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:12.599  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:12.600  1798  1798 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-02 10:41:12.604  1832  1832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-02 10:41:12.609  1832  1832 D SystemUpdateService: onCreate
08-02 10:41:12.611  1832  1832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-02 10:41:12.613  1832  4008 I SystemUpdateService: active receiver: enabled
,08-02 10:41:12.615  1832  4008 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-02 10:41:12.618  1832  4008 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-02 10:41:12.618  1832  4008 I SystemUpdateService: now status is 0 (complete)
08-02 10:41:12.618  1832  4008 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-02 10:41:12.618  1832  4008 I SystemUpdateService: file has been verified
08-02 10:41:12.619  1832  4008 I SystemUpdateService: OTA package size = 12249756
,08-02 10:41:12.623  1832  4008 I SystemUpdateService: showing system update notification
,08-02 10:41:12.627  1832  1832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-02 10:41:12.630  1832  2342 I iu.UploadsManager: num queued entries: 0
,08-02 10:41:12.631  1832  2342 I iu.UploadsManager: num updated entries: 0
,08-02 10:41:12.634  1832  2342 I iu.SyncManager: NEXT; no task
,08-02 10:41:12.637  1832  1832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-02 10:41:12.639  1832  1832 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-02 10:41:12.640  1832  1832 D SystemUpdateService: onDestroy
,08-02 10:41:12.640  3892  3892 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:12.643  1832  4013 I MDM     : [212] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-02 10:41:12.643  1832  4013 W BaseAppContext: Using Auth Proxy for data requests.
08-02 10:41:12.644  3892  3892 D SprintDMHelper: simOperator: 
,08-02 10:41:12.644  1832  4013 V GoogleAuthProtoRequest: [212] a.<init>: mAccountName set to: thalitester@gmail.com
,08-02 10:41:12.644  3892  3892 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-02 10:41:12.652  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:41:12.654  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:41:12.678  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-02 10:41:12.678  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-02 10:41:12.678  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:41:12.679  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:41:12.694  1832  4013 E MDM     : [212] SitrepService.a: Error sending sitrep.
,08-02 10:41:12.739  2370  4015 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-02 10:41:12.745   871  1729 I ActivityManager: Killing 2042:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-02 10:41:12.987   871  1698 D WifiService: setWifiEnabled: false pid=3760, uid=10000
,08-02 10:41:12.988   871  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 10:41:13.014  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-02 10:41:13.021   871  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-02 10:41:13.021   871  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-02 10:41:13.022   871  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-02 10:41:13.022   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 10:41:13.045   871  1301 E native  : do suspend true
,08-02 10:41:13.051   871  2012 D DhcpClient: Clearing IP address
,08-02 10:41:13.052   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-02 10:41:13.054   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:13.060  1513  4020 V NativeCrypto: Read error: ssl=0x9b0b3400: I/O error during system call, Connection timed out
,08-02 10:41:13.061  1513  4020 V NativeCrypto: SSL shutdown failed: ssl=0x9b0b3400: I/O error during system call, Broken pipe
,08-02 10:41:13.064   871  1691 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-02 10:41:13.065   871  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-02 10:41:13.065   871  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-02 10:41:13.066   871  3995 D DhcpClient: Receive thread stopped
,08-02 10:41:13.070   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-02 10:41:13.070   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-02 10:41:13.075   871  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-02 10:41:13.077   403   403 E Parcel  : Reading a NULL string not supported here.
08-02 10:41:13.079   871  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
08-02 10:41:13.086   871  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-02 10:41:13.086   871  1301 E native  : do suspend true
,08-02 10:41:13.090   871  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-02 10:41:13.094   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-02 10:41:13.097   871  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-02 10:41:13.110   871  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 10:41:13.113  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:13.113  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 10:41:13.113  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:13.113  1844  2072 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-02 10:41:13.113  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:13.114   871  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-02 10:41:13.115  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:13.115  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 10:41:13.115  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 10:41:13.115  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:13.118   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:13.156   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:13.157   871  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-02 10:41:13.157   871  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:13.160   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-02 10:41:13.165  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:13.167  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:13.169  1798  1798 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-02 10:41:13.179  1832  1832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-02 10:41:13.183  1832  1832 D SystemUpdateService: onCreate
08-02 10:41:13.189  1832  1832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-02 10:41:13.202  1832  1832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-02 10:41:13.210  1832  4029 I SystemUpdateService: active receiver: enabled
,08-02 10:41:13.213  1832  1832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-02 10:41:13.214  1832  1832 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-02 10:41:13.216  3892  3892 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:13.210  1832  2342 I iu.UploadsManager: num queued entries: 0
,08-02 10:41:13.222  3892  3892 D SprintDMHelper: simOperator: 
,08-02 10:41:13.222  3892  3892 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-02 10:41:13.237   370   869 E Netd    : netlink response contains error (No such file or directory)
,08-02 10:41:13.238   871  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-02 10:41:13.238   871  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-02 10:41:13.252  1832  2342 I iu.UploadsManager: num updated entries: 0
,08-02 10:41:13.261  2370  4034 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-02 10:41:13.268  1832  4029 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-02 10:41:13.268  1832  2342 I iu.SyncManager: NEXT; no task
,08-02 10:41:13.269  1832  4029 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-02 10:41:13.269  1832  4029 I SystemUpdateService: now status is 0 (complete)
08-02 10:41:13.269  1832  4029 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-02 10:41:13.270  1832  4029 I SystemUpdateService: file has been verified
,08-02 10:41:13.270  1832  4029 I SystemUpdateService: OTA package size = 12249756
,08-02 10:41:13.275  1832  4029 I SystemUpdateService: showing system update notification
,08-02 10:41:13.284  1832  1832 D SystemUpdateService: onDestroy
,08-02 10:41:13.577   871  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-02 10:41:16.046   871   888 I ActivityManager: Start proc 4036:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-02 10:41:16.164  4036  4036 D AdapterServiceConfig: Adding HeadsetService
,08-02 10:41:16.164  4036  4036 D AdapterServiceConfig: Adding A2dpService
08-02 10:41:16.164  4036  4036 D AdapterServiceConfig: Adding HidService
08-02 10:41:16.164  4036  4036 D AdapterServiceConfig: Adding HealthService
,08-02 10:41:16.164  4036  4036 D AdapterServiceConfig: Adding PanService
08-02 10:41:16.164  4036  4036 D AdapterServiceConfig: Adding GattService
08-02 10:41:16.165  4036  4036 D AdapterServiceConfig: Adding BluetoothMapService
,08-02 10:41:16.177  4036  4036 D BluetoothAdapterState: make() - Creating AdapterState
,08-02 10:41:16.177   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb8031c:true
,08-02 10:41:16.182  4036  4036 I bt_bluedroid: init
,08-02 10:41:16.183  4036  4048 I BluetoothAdapterState: Entering OffState
08-02 10:41:16.188  4036  4049 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-02 10:41:16.189  4036  4049 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-02 10:41:16.189  4036  4049 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-02 10:41:16.189  4036  4049 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-02 10:41:16.191  4036  4036 I bt_bluedroid: get_profile_interface socket
,08-02 10:41:16.194  4036  4036 I bt_bluedroid: get_profile_interface sdp
,08-02 10:41:16.197  4036  4052 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 10:41:16.197  4036  4047 I bt_bluedroid: config_hci_snoop_log
08-02 10:41:16.200  4036  4052 D BluetoothAdapterProperties: Name is: Nexus 6
08-02 10:41:16.200   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-02 10:41:16.206  4036  4048 D BluetoothAdapterState: Current state: OFF, message: 0
,08-02 10:41:16.207  4036  4048 D BluetoothAdapterProperties: Setting state to 14
08-02 10:41:16.207  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-02 10:41:16.211  4036  4048 D BluetoothBondStateMachine: make
,08-02 10:41:16.216  4036  4053 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-02 10:41:16.221  4036  4048 I BluetoothAdapterState: Entering PendingCommandState
,08-02 10:41:16.222  4036  4036 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-02 10:41:16.225  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:16.225  4036  4036 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-02 10:41:16.226  4036  4036 D BtGatt.GattService: Received start request. Starting profile...
,08-02 10:41:16.226  4036  4036 D BtGatt.GattService: start()
08-02 10:41:16.226  4036  4036 I bt_bluedroid: get_profile_interface gatt
08-02 10:41:16.227  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:16.227  4036  4036 D BtGatt.AdvertiseManager: advertise manager created
,08-02 10:41:16.235  4036  4036 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:16.235  4036  4036 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:16.235  4036  4036 V BluetoothAdapterState: isBleTurningOn()=true
08-02 10:41:16.235  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:16.235  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-02 10:41:16.236  4036  4048 I bt_bluedroid: enable
,08-02 10:41:16.236  4036  4049 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-02 10:41:16.239  4036  4049 I bt_hci  : start_up
,08-02 10:41:16.258  4036  4049 I bt_vendor: alloc value 0xb3a7c189
,08-02 10:41:16.258  4036  4049 I bt_vendor: init
08-02 10:41:16.258  4036  4049 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-02 10:41:16.259  4036  4049 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-02 10:41:16.370  4036  4049 D bt_hci  : start_up starting async portion
,08-02 10:41:16.371  4036  4056 I bt_hci  : event_finish_startup
,08-02 10:41:16.371  4036  4056 I bt_hci_h4: hal_open
08-02 10:41:16.371  4036  4056 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-02 10:41:16.383  4036  4056 I bt_userial_vendor: device fd = 51 open
,08-02 10:41:16.411  4036  4056 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 10:41:16.443  4036  4056 D bt_hwcfg: Chipset BCM4354A2
,08-02 10:41:16.443  4036  4056 D bt_hwcfg: Target name = [BCM4354A2]
,08-02 10:41:16.444  4036  4056 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-02 10:41:17.103  4036  4056 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-02 10:41:17.104  4036  4056 D bt_hwcfg: Settlement delay -- 100 ms
08-02 10:41:17.105  4036  4056 I bt_hwcfg: Setting fw settlement delay to 100 
,08-02 10:41:17.221  4036  4056 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 10:41:17.223  4036  4056 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-02 10:41:17.252  4036  4056 I bt_hwcfg: vendor lib fwcfg completed
,08-02 10:41:17.252  4036  4056 I bt_vendor: firmware callback
08-02 10:41:17.252  4036  4056 I bt_hci  : firmware_config_callback
,08-02 10:41:17.264  4036  4058 I bt_btu  : btu_task pending for preload complete event
,08-02 10:41:17.264  4036  4058 I bt_btu_task: Bluetooth chip preload is complete
,08-02 10:41:17.265  4036  4058 I bt_btu  : btu_task received preload complete event
,08-02 10:41:17.275  4036  4058 I         : BTE_InitTraceLevels -- TRC_HCI
08-02 10:41:17.275  4036  4058 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-02 10:41:17.275  4036  4058 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-02 10:41:17.276  4036  4058 I         : BTE_InitTraceLevels -- TRC_AVDT
08-02 10:41:17.276  4036  4058 I         : BTE_InitTraceLevels -- TRC_AVRC
08-02 10:41:17.276  4036  4058 I         : BTE_InitTraceLevels -- TRC_A2D
,08-02 10:41:17.277  4036  4058 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-02 10:41:17.277  4036  4058 I         : BTE_InitTraceLevels -- TRC_BTM
08-02 10:41:17.277  4036  4058 I         : BTE_InitTraceLevels -- TRC_GAP
08-02 10:41:17.278  4036  4058 I         : BTE_InitTraceLevels -- TRC_PAN
,08-02 10:41:17.278  4036  4058 I         : BTE_InitTraceLevels -- TRC_SDP
08-02 10:41:17.278  4036  4058 I         : BTE_InitTraceLevels -- TRC_GATT
,08-02 10:41:17.278  4036  4058 I         : BTE_InitTraceLevels -- TRC_SMP
08-02 10:41:17.278  4036  4058 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-02 10:41:17.279  4036  4058 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-02 10:41:17.412  4036  4058 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f9d9d
,08-02 10:41:17.412  4036  4058 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f9d9d 
,08-02 10:41:17.436  4036  4052 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-02 10:41:17.438  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-02 10:41:17.439  4036  4052 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 10:41:17.442  4036  4052 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 10:41:17.445  4036  4052 D BluetoothAdapterProperties: Scan Mode:20
08-02 10:41:17.446  4036  4052 D BluetoothAdapterProperties: Discoverable Timeout:120
08-02 10:41:17.446  4036  4052 D bt_hci  : do_postload posting postload work item
08-02 10:41:17.448  4036  4056 I bt_hci  : event_postload
08-02 10:41:17.448  4036  4056 I bt_vendor: sco_config_cb
08-02 10:41:17.449  4036  4056 I bt_hci  : sco_config_callback postload finished.
08-02 10:41:17.450  4036  4052 D bt_bte_conf: Device ID record 1 : primary
,08-02 10:41:17.450  4036  4052 D bt_bte_conf:   vendorId            = 000f
08-02 10:41:17.450  4036  4052 D bt_bte_conf:   vendorIdSource      = 0001
,08-02 10:41:17.451  4036  4052 D bt_bte_conf:   product             = 1200
,08-02 10:41:17.451  4036  4052 D bt_bte_conf:   version             = 1436
08-02 10:41:17.451  4036  4052 D bt_bte_conf:   clientExecutableURL = 
,08-02 10:41:17.451  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:17.452  4036  4052 D bt_bte_conf:   serviceDescription  = 
,08-02 10:41:17.452  4036  4052 D bt_bte_conf:   documentationURL    = 
08-02 10:41:17.452  4036  4052 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-02 10:41:17.453  4036  4049 D bt_stack_manager: event_start_up_stack finished
08-02 10:41:17.455  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:17.456  4036  4056 I bt_vendor: low_power_mode_cb
08-02 10:41:17.457  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-02 10:41:17.458  4036  4048 D BluetoothAdapterProperties: Setting state to 15
08-02 10:41:17.458  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-02 10:41:17.459  4036  4048 I BluetoothAdapterState: Entering BleOnState
08-02 10:41:17.465  4036  4048 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-02 10:41:17.465  4036  4048 D BluetoothAdapterProperties: Setting state to 11
08-02 10:41:17.465  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-02 10:41:17.477  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:17.481  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:17.482  4036  4036 D HeadsetService: Received start request. Starting profile...
,08-02 10:41:17.484  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:17.487  4036  4036 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-02 10:41:17.488  4036  4036 D HeadsetStateMachine: make
,08-02 10:41:17.493  4036  4048 I BluetoothAdapterState: Entering PendingCommandState
,08-02 10:41:17.502  4036  4036 D HeadsetStateMachine: max_hf_connections = 1
,08-02 10:41:17.503  4036  4036 I bt_bluedroid: get_profile_interface handsfree
08-02 10:41:17.503  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-02 10:41:17.503  4036  4052 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-02 10:41:17.509  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:17.509  4036  4036 D A2dpService: Received start request. Starting profile...
,08-02 10:41:17.510  4036  4036 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-02 10:41:17.510  4036  4036 I bt_bluedroid: get_profile_interface avrcp
,08-02 10:41:17.516  4036  4036 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-02 10:41:17.516  4036  4036 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-02 10:41:17.516  4036  4036 D A2dpStateMachine: make
,08-02 10:41:17.517  4036  4036 I bt_bluedroid: get_profile_interface a2dp
08-02 10:41:17.518  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-02 10:41:17.519  4036  4067 D A2dpStateMachine: Enter Disconnected: -2
,08-02 10:41:17.520  4036  4036 I BluetoothHidServiceJni: classInitNative: succeeds
,08-02 10:41:17.521  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:17.522  4036  4036 D HidService: Received start request. Starting profile...
,08-02 10:41:17.522  4036  4036 I bt_bluedroid: get_profile_interface hidhost
08-02 10:41:17.522  4036  4052 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39db3e5
08-02 10:41:17.522  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-02 10:41:17.522  4036  4036 D HidService: setHidService(): set to: null
,08-02 10:41:17.523  4036  4036 I BluetoothHealthServiceJni: classInitNative: succeeds
08-02 10:41:17.523  3812  3812 D BluetoothInputDevice: Proxy object connected
,08-02 10:41:17.524  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:17.524  4036  4036 D HealthService: Received start request. Starting profile...
,08-02 10:41:17.525  3812  3812 D HidProfile: Bluetooth service connected
,08-02 10:41:17.526  4036  4036 I bt_bluedroid: get_profile_interface health
,08-02 10:41:17.528  4036  4036 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-02 10:41:17.529  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:17.529  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-02 10:41:17.531  3812  3812 D BluetoothPan: BluetoothPAN Proxy object connected
08-02 10:41:17.531  4036  4036 D PanService: Received start request. Starting profile...
08-02 10:41:17.531  4036  4036 D BluetoothPanServiceJni: initializeNative(L110): pan
08-02 10:41:17.531  4036  4036 I bt_bluedroid: get_profile_interface pan
08-02 10:41:17.532  4036  4052 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-02 10:41:17.534  4036  4036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:17.535  4036  4036 D BluetoothMapService: Received start request. Starting profile...
08-02 10:41:17.535  4036  4036 D BluetoothMapService: start()
08-02 10:41:17.537  4036  4036 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-02 10:41:17.537  4036  4036 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-02 10:41:17.538  4036  4036 D BluetoothMapAppObserver: createReceiver()
,08-02 10:41:17.538  4036  4036 D BluetoothMapAppObserver: initObservers()
08-02 10:41:17.538  4036  4036 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-02 10:41:17.531  3812  3812 D PanProfile: Bluetooth service connected
,08-02 10:41:17.541  3812  3812 D BluetoothMap: Proxy object connected
,08-02 10:41:17.541  3812  3812 D MapProfile: Bluetooth service connected
08-02 10:41:17.542  3812  3812 D BluetoothMap: getConnectedDevices()
,08-02 10:41:17.543  3812  3812 D BluetoothMap: Bluetooth is Not enabled
,08-02 10:41:17.548  4036  4036 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:17.548  4036  4036 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:17.548  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:17.548  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:17.551  4036  4065 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-02 10:41:17.551  4036  4036 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:17.551  4036  4036 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:17.551  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:17.551  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isTurningOn()=true
,08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 10:41:17.552  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:17.553  4036  4036 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:17.553  4036  4036 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:17.553  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:17.553  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:17.554  4036  4036 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:17.554  4036  4036 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:17.554  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:17.554  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:17.554  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-02 10:41:17.554  4036  4048 D BluetoothAdapterProperties: ScanMode =  20
,08-02 10:41:17.554  4036  4048 D BluetoothAdapterProperties: State =  11
08-02 10:41:17.555  4036  4048 D BluetoothAdapterProperties: Setting state to 12
08-02 10:41:17.555  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-02 10:41:17.556  4036  4048 I BluetoothAdapterState: Entering OnState
,08-02 10:41:17.558  3812  3822 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-02 10:41:17.558  4036  4052 D BluetoothAdapterProperties: Scan Mode:21
08-02 10:41:17.558  4036  4052 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-02 10:41:17.559  1358  1382 D BluetoothA2dp: onBluetoothStateChange: up=true
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:17.562  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:17.562   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:17.562  1358  1817 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-02 10:41:17.563  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:17.564  1358  1358 D BluetoothInputDevice: Proxy object connected
08-02 10:41:17.564  1358  1358 D HidProfile: Bluetooth service connected
,08-02 10:41:17.565  1358  1385 D BluetoothPbap: onBluetoothStateChange: up=true
,08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:17.567  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 10:41:17.567  3812  3823 D BluetoothMap: onBluetoothStateChange: up=true
,08-02 10:41:17.568  3812  3822 D BluetoothPbap: onBluetoothStateChange: up=true
,08-02 10:41:17.568  1358  1358 D BluetoothA2dp: Proxy object connected
,08-02 10:41:17.570  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:17.570  4036  4036 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-02 10:41:17.570  1358  1985 D BluetoothMap: onBluetoothStateChange: up=true
,08-02 10:41:17.571  4036  4036 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-02 10:41:17.572  1358  1358 D BluetoothMap: Proxy object connected
,08-02 10:41:17.572  1358  1358 D MapProfile: Bluetooth service connected
08-02 10:41:17.573  1358  1358 D BluetoothMap: getConnectedDevices()
08-02 10:41:17.573   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:17.573   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-02 10:41:17.573  4036  4036 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:17.574   871   871 D BluetoothA2dp: Proxy object connected
08-02 10:41:17.575  3812  3823 D BluetoothPan: onBluetoothStateChange on: true
,08-02 10:41:17.575  1358  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:17.575  4036  4036 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:17.576  1713  1728 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:17.576   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:17.576  1358  1382 D BluetoothPan: onBluetoothStateChange on: true
,08-02 10:41:17.577  4036  4036 D ObexServerSockets: Succeed to create listening sockets 
08-02 10:41:17.577  4036  4036 D ObexServerSockets0: startAccept()
08-02 10:41:17.577  4036  4036 D ObexServerSockets0: prepareForNewConnect()
,08-02 10:41:17.579  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
,08-02 10:41:17.579  1358  1358 D PanProfile: Bluetooth service connected
,08-02 10:41:17.579  4036  4036 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-02 10:41:17.579  4036  4036 D BluetoothSdpJni: SDP Create record success - handle: 0
08-02 10:41:17.580   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-02 10:41:17.581  4036  4073 D ObexServerSockets0: Accepting socket connection...
08-02 10:41:17.581  4036  4036 D BluetoothMapService: onReceive
08-02 10:41:17.581  4036  4036 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-02 10:41:17.581  4036  4036 D BluetoothMapService: STATE_ON
08-02 10:41:17.582  4036  4074 D ObexServerSockets0: Accepting socket connection...
,08-02 10:41:17.583  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:17.584  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:17.585  3812  3812 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-02 10:41:17.591  3812  3812 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-02 10:41:17.597  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 10:41:17.599  3812  3812 D BluetoothA2dp: Proxy object connected
,08-02 10:41:17.602  4036  4036 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-02 10:41:17.602  4036  4036 D ObexServerSockets0: prepareForNewConnect()
,08-02 10:41:17.604  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 10:41:17.611  3812  3812 D DockEventReceiver: finishStartingService: stopping service
,08-02 10:41:17.613  1358  1358 D BluetoothPbap: Proxy object connected
,08-02 10:41:17.613  3812  3812 D BluetoothPbap: Proxy object connected
08-02 10:41:17.613  1358  1358 D PbapServerProfile: Bluetooth service connected
08-02 10:41:17.614  3812  3812 D PbapServerProfile: Bluetooth service connected
,08-02 10:41:17.621  4036  4078 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:17.637  4036  4082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:17.639  4036  4082 I BtOppRfcommListener: Accept thread started.
,08-02 10:41:17.664  1358  1382 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.664  1358  1358 D HeadsetProfile: Bluetooth service connected
08-02 10:41:17.664   871   871 D BluetoothHeadset: Proxy object connected
08-02 10:41:17.664  1713  1906 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.665   871   871 D BluetoothHeadset: Proxy object connected
08-02 10:41:17.665   871   871 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.673   871   888 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.675  1358  1985 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.676  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-02 10:41:17.676  1713  1973 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.676   871   888 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.694  3812  3822 D BluetoothHeadset: Proxy object connected
,08-02 10:41:17.695  3812  3812 D HeadsetProfile: Bluetooth service connected
,08-02 10:41:19.007  4036  4048 D BluetoothAdapterState: Current state: ON, message: 23
,08-02 10:41:19.008  4036  4048 D BluetoothAdapterProperties: Setting state to 13
08-02 10:41:19.008  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-02 10:41:19.010  4036  4048 D BluetoothAdapterProperties: onBluetoothDisable()
08-02 10:41:19.017  4036  4048 I BluetoothAdapterState: Entering PendingCommandState
08-02 10:41:19.021  4036  4036 D BluetoothMapService: onReceive
08-02 10:41:19.021  4036  4036 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-02 10:41:19.021  4036  4036 D BluetoothMapService: STATE_TURNING_OFF
08-02 10:41:19.022  4036  4036 D BluetoothMapService: MAP Service closeService in
08-02 10:41:19.023  4036  4036 D BluetoothMapMasInstance0: MAP Service shutdown
08-02 10:41:19.023  4036  4036 D ObexServerSockets0: shutdown(block = true)
08-02 10:41:19.024  4036  4073 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-02 10:41:19.025  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:19.025  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:19.025  4036  4036 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 10:41:19.026  4036  4074 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-02 10:41:19.026  4036  4060 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-02 10:41:19.026  4036  4036 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 10:41:19.027  4036  4036 I BtOppRfcommListener: stopping Accept Thread
08-02 10:41:19.027  4036  4082 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-02 10:41:19.027  4036  4082 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-02 10:41:19.027  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 10:41:19.028  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:19.029  4036  4052 D BluetoothAdapterProperties: Scan Mode:20
08-02 10:41:19.029  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-02 10:41:19.034  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:19.035  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:19.035  4036  4036 D HeadsetService: Received stop request...Stopping profile...
08-02 10:41:19.037  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 10:41:19.037  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:19.038  1358  1385 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:19.038   871   871 D BluetoothHeadset: Proxy object disconnected
,08-02 10:41:19.039  3812  3823 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:19.039  4036  4036 D A2dpService: Received stop request...Stopping profile...
08-02 10:41:19.039  4036  4067 D A2dpStateMachine: Exit Disconnected: -1
08-02 10:41:19.039  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 10:41:19.040  1713  1725 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:19.040   871   871 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:19.040   871   871 D BluetoothHeadset: Proxy object disconnected
08-02 10:41:19.041   871   871 D BluetoothA2dp: Proxy object disconnected
,08-02 10:41:19.041  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:19.042  4036  4036 D HidService: Received stop request...Stopping profile...
08-02 10:41:19.042  4036  4036 D HidService: Stopping Bluetooth HidService
08-02 10:41:19.043  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:19.044  4036  4036 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:19.044  4036  4036 V BluetoothAdapterState: isTurningOn()=false
,08-02 10:41:19.044  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:19.044  1358  1358 D HeadsetProfile: Bluetooth service disconnected
08-02 10:41:19.044  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:19.045  1358  1358 D BluetoothA2dp: Proxy object disconnected
08-02 10:41:19.045  1358  1358 D BluetoothInputDevice: Proxy object disconnected
08-02 10:41:19.045  1358  1358 D HidProfile: Bluetooth service disconnected
08-02 10:41:19.047  4036  4036 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-02 10:41:19.047  4036  4036 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-02 10:41:19.047  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-02 10:41:19.047  4036  4058 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:19.047  4036  4058 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:19.048  4036  4058 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:19.048  4036  4052 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-02 10:41:19.048  4036  4036 D HealthService: Received stop request...Stopping profile...
,08-02 10:41:19.052  4036  4036 D PanService: Received stop request...Stopping profile...
,08-02 10:41:19.052  3812  3812 D HeadsetProfile: Bluetooth service disconnected
08-02 10:41:19.053  3812  3812 D BluetoothA2dp: Proxy object disconnected
08-02 10:41:19.054  3812  3812 D BluetoothInputDevice: Proxy object disconnected
08-02 10:41:19.054  3812  3812 D HidProfile: Bluetooth service disconnected
,08-02 10:41:19.054  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-02 10:41:19.054  1358  1358 D PanProfile: Bluetooth service disconnected
08-02 10:41:19.055  4036  4036 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:19.055  4036  4036 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:19.055  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:19.055  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:19.057  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-02 10:41:19.057  4036  4058 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:19.057  4036  4058 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 10:41:19.057  4036  4058 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-02 10:41:19.057  4036  4058 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-02 10:41:19.057  4036  4058 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-02 10:41:19.057  4036  4058 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-02 10:41:19.059  4036  4036 D BluetoothMapService: Received stop request...Stopping profile...
08-02 10:41:19.059  4036  4036 D BluetoothMapService: stop()
,08-02 10:41:19.060  4036  4036 D BluetoothMapAppObserver: deinitObservers()
,08-02 10:41:19.060  4036  4036 D BluetoothMapAppObserver: removeReceiver()
08-02 10:41:19.061  3812  3812 D DockEventReceiver: finishStartingService: stopping service
08-02 10:41:19.062  4036  4036 V BluetoothAdapterState: isTurningOff()=true
,08-02 10:41:19.062  4036  4036 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:19.062  1358  1358 D BluetoothMap: Proxy object disconnected
08-02 10:41:19.062  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:19.062  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:19.062  1358  1358 D MapProfile: Bluetooth service disconnected
,08-02 10:41:19.062  4036  4036 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-02 10:41:19.063  4036  4052 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-02 10:41:19.063  4036  4036 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-02 10:41:19.063  3812  3812 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-02 10:41:19.063  4036  4036 V BluetoothAdapterState: isTurningOff()=true
,08-02 10:41:19.063  4036  4036 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:19.063  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:19.063  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:19.064  4036  4036 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-02 10:41:19.063  3812  3812 D PanProfile: Bluetooth service disconnected
08-02 10:41:19.064  4036  4052 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-02 10:41:19.064  4036  4036 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-02 10:41:19.065  4036  4036 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:19.065  4036  4036 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:19.065  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:19.065  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:19.066  3812  3812 D BluetoothMap: Proxy object disconnected
,08-02 10:41:19.066  3812  3812 D MapProfile: Bluetooth service disconnected
,08-02 10:41:19.067  4036  4036 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-02 10:41:19.067  4036  4036 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-02 10:41:19.068  4036  4036 D BluetoothMapService: MAP Service closeService in
08-02 10:41:19.068  4036  4036 V BluetoothAdapterState: isTurningOff()=true
08-02 10:41:19.068  4036  4036 V BluetoothAdapterState: isTurningOn()=false
,08-02 10:41:19.068  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:19.068  4036  4036 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:19.069  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-02 10:41:19.069  4036  4048 D BluetoothAdapterProperties: Setting state to 15
08-02 10:41:19.069  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-02 10:41:19.069  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-02 10:41:19.069  4036  4036 D BluetoothMapService: cleanup()
08-02 10:41:19.069  4036  4036 D BluetoothMapService: MAP Service closeService in
,08-02 10:41:19.070  3812  3822 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-02 10:41:19.070  4036  4048 I BluetoothAdapterState: Entering BleOnState
08-02 10:41:19.072  1358  1382 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 10:41:19.072  1358  1358 D BluetoothPbap: Proxy object disconnected
08-02 10:41:19.072  1358  1358 D PbapServerProfile: Bluetooth service disconnected
08-02 10:41:19.073   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:19.073  1358  1817 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-02 10:41:19.074  1358  1985 D BluetoothPbap: onBluetoothStateChange: up=false
08-02 10:41:19.076  3812  3822 D BluetoothMap: onBluetoothStateChange: up=false
,08-02 10:41:19.078  3812  3823 D BluetoothPbap: onBluetoothStateChange: up=false
,08-02 10:41:19.079  1358  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-02 10:41:19.080   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:19.080   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-02 10:41:19.082  3812  3822 D BluetoothPan: onBluetoothStateChange on: false
,08-02 10:41:19.083  1358  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-02 10:41:19.084  3812  3823 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-02 10:41:19.085  1713  1728 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-02 10:41:19.085   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 10:41:19.086  3812  3822 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-02 10:41:19.086  1358  1817 D BluetoothPan: onBluetoothStateChange on: false
,08-02 10:41:19.088  4036  4048 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-02 10:41:19.088  4036  4048 D BluetoothAdapterProperties: Setting state to 16
08-02 10:41:19.088  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-02 10:41:19.088  4036  4048 D BluetoothAdapterProperties: onBleDisable
,08-02 10:41:19.089  4036  4049 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-02 10:41:19.090  4036  4058 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-02 10:41:19.090  4036  4058 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-02 10:41:19.091  4036  4048 I BluetoothAdapterState: Entering PendingCommandState
,08-02 10:41:19.094  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:19.095  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:19.097  4036  4052 D BluetoothAdapterProperties: Scan Mode:20
,08-02 10:41:19.097  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 10:41:19.099  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:19.101  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:19.102  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 10:41:19.107  3812  3812 D DockEventReceiver: finishStartingService: stopping service
,08-02 10:41:19.290  4036  4052 I bt_hci  : shut_down
08-02 10:41:19.291  4036  4056 D bt_hwcfg: hw_epilog_process
,08-02 10:41:19.303  4036  4056 I bt_vendor: low_power_mode_cb
,08-02 10:41:19.332  4036  4056 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-02 10:41:19.332  4036  4056 I bt_vendor: epilog_cb
08-02 10:41:19.333  4036  4056 I bt_hci  : epilog_finished_callback
,08-02 10:41:19.340  4036  4052 I bt_hci_h4: hal_close
,08-02 10:41:19.341  4036  4052 I bt_userial_vendor: device fd = 51 close
,08-02 10:41:19.472  4036  4049 D bt_stack_manager: event_shut_down_stack finished.
,08-02 10:41:19.475  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-02 10:41:19.484  4036  4036 D BtGatt.DebugUtils: handleDebugAction() action=null
08-02 10:41:19.484  4036  4048 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-02 10:41:19.485  4036  4036 D BtGatt.GattService: Received stop request...Stopping profile...
,08-02 10:41:19.486  4036  4036 D BtGatt.GattService: stop()
,08-02 10:41:19.486  4036  4036 D BtGatt.AdvertiseManager: advertise clients cleared
08-02 10:41:19.491  4036  4036 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:19.491  4036  4036 V BluetoothAdapterState: isTurningOn()=false
,08-02 10:41:19.491  4036  4036 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 10:41:19.492  4036  4036 V BluetoothAdapterState: isBleTurningOff()=true
,08-02 10:41:19.492  4036  4048 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25,
08-02 10:41:19.492  4036  4048 D BluetoothAdapterProperties: Setting state to 10
08-02 10:41:19.492  4036  4048 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-02 10:41:19.493  4036  4048 I BluetoothAdapterState: Entering OffState
08-02 10:41:19.494   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-02 10:41:19.517  4036  4036 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-02 10:41:19.518  4036  4036 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-02 10:41:19.518  4036  4049 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-02 10:41:19.520  4036  4036 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-02 10:41:19.526  4036  4049 D bt_stack_manager: event_clean_up_stack finished.
,08-02 10:41:19.531  4036  4036 I art     : System.exit called, status: 0
,08-02 10:41:19.531  4036  4036 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-02 10:41:19.591   871  1732 I ActivityManager: Process com.android.bluetooth (pid 4036) has died
,08-02 10:41:20.454   871  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-02 10:41:22.005  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:22.005  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:25.013  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:25.014  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be625c0 added. We now have 6 listener(s)
08-02 10:41:25.014  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 10:41:25.018  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:25.019  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fec2f9 added. We now have 7 listener(s)
08-02 10:41:25.019  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 10:41:25.021  3760  3806 I System.out: IsBluetoothEnabled
,08-02 10:41:25.033  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:25.085   871   888 I ActivityManager: Start proc 4093:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-02 10:41:25.227  4093  4093 D AdapterServiceConfig: Adding HeadsetService
08-02 10:41:25.227  4093  4093 D AdapterServiceConfig: Adding A2dpService
08-02 10:41:25.228  4093  4093 D AdapterServiceConfig: Adding HidService
08-02 10:41:25.228  4093  4093 D AdapterServiceConfig: Adding HealthService
08-02 10:41:25.228  4093  4093 D AdapterServiceConfig: Adding PanService
,08-02 10:41:25.228  4093  4093 D AdapterServiceConfig: Adding GattService
08-02 10:41:25.228  4093  4093 D AdapterServiceConfig: Adding BluetoothMapService
,08-02 10:41:25.244  4093  4093 D BluetoothAdapterState: make() - Creating AdapterState
,08-02 10:41:25.244   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9137f29:true
,08-02 10:41:25.249  4093  4093 I bt_bluedroid: init
,08-02 10:41:25.250  4093  4105 I BluetoothAdapterState: Entering OffState
,08-02 10:41:25.256  4093  4106 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-02 10:41:25.256  4093  4106 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-02 10:41:25.256  4093  4106 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-02 10:41:25.257  4093  4106 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-02 10:41:25.259  4093  4093 I bt_bluedroid: get_profile_interface socket
,08-02 10:41:25.262  4093  4109 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 10:41:25.264  4093  4109 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 10:41:25.264  4093  4093 I bt_bluedroid: get_profile_interface sdp
,08-02 10:41:25.270  4093  4104 I bt_bluedroid: config_hci_snoop_log
,08-02 10:41:25.273   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-02 10:41:25.281  4093  4105 D BluetoothAdapterState: Current state: OFF, message: 0
,08-02 10:41:25.282  4093  4105 D BluetoothAdapterProperties: Setting state to 14
,08-02 10:41:25.282  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-02 10:41:25.287  4093  4105 D BluetoothBondStateMachine: make
,08-02 10:41:25.292  4093  4110 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-02 10:41:25.300  4093  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-02 10:41:25.304  4093  4093 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-02 10:41:25.313  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:25.315  4093  4093 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-02 10:41:25.317  4093  4093 D BtGatt.GattService: Received start request. Starting profile...
08-02 10:41:25.317  4093  4093 D BtGatt.GattService: start()
,08-02 10:41:25.318  4093  4093 I bt_bluedroid: get_profile_interface gatt
,08-02 10:41:25.320  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:25.320  4093  4093 D BtGatt.AdvertiseManager: advertise manager created
,08-02 10:41:25.334  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:25.334  4093  4093 V BluetoothAdapterState: isTurningOn()=false
08-02 10:41:25.335  4093  4093 V BluetoothAdapterState: isBleTurningOn()=true
08-02 10:41:25.335  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:25.336  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-02 10:41:25.337  4093  4105 I bt_bluedroid: enable
08-02 10:41:25.338  4093  4106 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-02 10:41:25.339  4093  4106 I bt_hci  : start_up
,08-02 10:41:25.358  4093  4106 I bt_vendor: alloc value 0xb3a7c189
08-02 10:41:25.358  4093  4106 I bt_vendor: init
,08-02 10:41:25.358  4093  4106 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-02 10:41:25.358  4093  4106 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-02 10:41:25.466  4093  4106 D bt_hci  : start_up starting async portion
08-02 10:41:25.467  4093  4113 I bt_hci  : event_finish_startup
,08-02 10:41:25.467  4093  4113 I bt_hci_h4: hal_open
08-02 10:41:25.467  4093  4113 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-02 10:41:25.479  4093  4113 I bt_userial_vendor: device fd = 51 open
,08-02 10:41:25.509  4093  4113 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 10:41:25.540  4093  4113 D bt_hwcfg: Chipset BCM4354A2
08-02 10:41:25.540  4093  4113 D bt_hwcfg: Target name = [BCM4354A2]
,08-02 10:41:25.541  4093  4113 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-02 10:41:26.402  4093  4113 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-02 10:41:26.404  4093  4113 D bt_hwcfg: Settlement delay -- 100 ms
08-02 10:41:26.404  4093  4113 I bt_hwcfg: Setting fw settlement delay to 100 
,08-02 10:41:26.522  4093  4113 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
08-02 10:41:26.524  4093  4113 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-02 10:41:26.551  4093  4113 I bt_hwcfg: vendor lib fwcfg completed
,08-02 10:41:26.552  4093  4113 I bt_vendor: firmware callback
08-02 10:41:26.552  4093  4113 I bt_hci  : firmware_config_callback
,08-02 10:41:26.567  4093  4115 I bt_btu  : btu_task pending for preload complete event
,08-02 10:41:26.567  4093  4115 I bt_btu_task: Bluetooth chip preload is complete
08-02 10:41:26.567  4093  4115 I bt_btu  : btu_task received preload complete event
,08-02 10:41:26.577  4093  4115 I         : BTE_InitTraceLevels -- TRC_HCI
,08-02 10:41:26.578  4093  4115 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-02 10:41:26.578  4093  4115 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-02 10:41:26.578  4093  4115 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-02 10:41:26.579  4093  4115 I         : BTE_InitTraceLevels -- TRC_AVRC
08-02 10:41:26.579  4093  4115 I         : BTE_InitTraceLevels -- TRC_A2D
08-02 10:41:26.579  4093  4115 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-02 10:41:26.579  4093  4115 I         : BTE_InitTraceLevels -- TRC_BTM
08-02 10:41:26.580  4093  4115 I         : BTE_InitTraceLevels -- TRC_GAP
08-02 10:41:26.580  4093  4115 I         : BTE_InitTraceLevels -- TRC_PAN
08-02 10:41:26.580  4093  4115 I         : BTE_InitTraceLevels -- TRC_SDP
,08-02 10:41:26.580  4093  4115 I         : BTE_InitTraceLevels -- TRC_GATT
08-02 10:41:26.581  4093  4115 I         : BTE_InitTraceLevels -- TRC_SMP
08-02 10:41:26.581  4093  4115 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-02 10:41:26.581  4093  4115 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-02 10:41:26.732  4093  4115 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f9d9d
,08-02 10:41:26.733  4093  4115 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f9d9d 
,08-02 10:41:26.746  4093  4109 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-02 10:41:26.747  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-02 10:41:26.748  4093  4109 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 10:41:26.757  4093  4109 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 10:41:26.760  4093  4109 D BluetoothAdapterProperties: Scan Mode:20
,08-02 10:41:26.764  4093  4109 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-02 10:41:26.764  4093  4109 D bt_hci  : do_postload posting postload work item
,08-02 10:41:26.765  4093  4113 I bt_hci  : event_postload
,08-02 10:41:26.765  4093  4113 I bt_vendor: sco_config_cb
08-02 10:41:26.765  4093  4113 I bt_hci  : sco_config_callback postload finished.
,08-02 10:41:26.767  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:26.772  4093  4109 D bt_bte_conf: Device ID record 1 : primary
,08-02 10:41:26.772  4093  4109 D bt_bte_conf:   vendorId            = 000f
08-02 10:41:26.772  4093  4109 D bt_bte_conf:   vendorIdSource      = 0001
,08-02 10:41:26.772  4093  4109 D bt_bte_conf:   product             = 1200
08-02 10:41:26.772  4093  4109 D bt_bte_conf:   version             = 1436
08-02 10:41:26.773  4093  4109 D bt_bte_conf:   clientExecutableURL = 
,08-02 10:41:26.773  4093  4109 D bt_bte_conf:   serviceDescription  = 
08-02 10:41:26.773  4093  4109 D bt_bte_conf:   documentationURL    = 
08-02 10:41:26.774  4093  4109 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-02 10:41:26.774  4093  4106 D bt_stack_manager: event_start_up_stack finished
08-02 10:41:26.775  4093  4113 I bt_vendor: low_power_mode_cb
08-02 10:41:26.775  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-02 10:41:26.776  4093  4105 D BluetoothAdapterProperties: Setting state to 15
08-02 10:41:26.776  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-02 10:41:26.778  4093  4105 I BluetoothAdapterState: Entering BleOnState
08-02 10:41:26.785  4093  4105 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-02 10:41:26.785  4093  4105 D BluetoothAdapterProperties: Setting state to 11
08-02 10:41:26.785  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-02 10:41:26.796  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:26.802  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:26.804  4093  4093 D HeadsetService: Received start request. Starting profile...
,08-02 10:41:26.809  4093  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-02 10:41:26.811  4093  4093 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-02 10:41:26.811  4093  4093 D HeadsetStateMachine: make
,08-02 10:41:26.825  4093  4093 D HeadsetStateMachine: max_hf_connections = 1
,08-02 10:41:26.826  4093  4093 I bt_bluedroid: get_profile_interface handsfree
,08-02 10:41:26.827  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-02 10:41:26.828  4093  4109 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-02 10:41:26.832  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:26.832  4093  4093 D A2dpService: Received start request. Starting profile...
08-02 10:41:26.833  4093  4093 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-02 10:41:26.833  4093  4093 I bt_bluedroid: get_profile_interface avrcp
,08-02 10:41:26.834  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 10:41:26.841  4093  4093 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-02 10:41:26.842  4093  4093 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-02 10:41:26.842  4093  4093 D A2dpStateMachine: make
,08-02 10:41:26.845  4093  4093 I bt_bluedroid: get_profile_interface a2dp
,08-02 10:41:26.847  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-02 10:41:26.848  4093  4093 I BluetoothHidServiceJni: classInitNative: succeeds
08-02 10:41:26.848  4093  4125 D A2dpStateMachine: Enter Disconnected: -2
,08-02 10:41:26.849  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:26.850  4093  4093 D HidService: Received start request. Starting profile...
08-02 10:41:26.850  4093  4093 I bt_bluedroid: get_profile_interface hidhost
,08-02 10:41:26.850  4093  4093 D HidService: setHidService(): set to: null
08-02 10:41:26.851  4093  4109 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39db3e5
08-02 10:41:26.851  4093  4093 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-02 10:41:26.851  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-02 10:41:26.852  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:26.853  4093  4093 D HealthService: Received start request. Starting profile...
,08-02 10:41:26.856  4093  4093 I bt_bluedroid: get_profile_interface health
,08-02 10:41:26.857  4093  4093 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-02 10:41:26.858  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:26.859  4093  4093 D PanService: Received start request. Starting profile...
,08-02 10:41:26.859  4093  4093 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-02 10:41:26.859  4093  4093 I bt_bluedroid: get_profile_interface pan
,08-02 10:41:26.861  4093  4109 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-02 10:41:26.862  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
,08-02 10:41:26.863  4093  4093 D BluetoothMapService: Received start request. Starting profile...
08-02 10:41:26.863  4093  4093 D BluetoothMapService: start()
,08-02 10:41:26.867  4093  4093 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-02 10:41:26.867  4093  4093 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-02 10:41:26.868  4093  4093 D BluetoothMapAppObserver: createReceiver()
08-02 10:41:26.869  4093  4093 D BluetoothMapAppObserver: initObservers()
08-02 10:41:26.869  4093  4093 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-02 10:41:26.879  4093  4123 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-02 10:41:26.879  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:26.879  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:26.879  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:26.879  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isTurningOn()=true
,08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:26.884  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 10:41:26.885  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:26.886  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-02 10:41:26.886  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-02 10:41:26.886  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 10:41:26.886  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-02 10:41:26.886  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-02 10:41:26.887  4093  4105 D BluetoothAdapterProperties: ScanMode =  20
08-02 10:41:26.887  4093  4105 D BluetoothAdapterProperties: State =  11
08-02 10:41:26.887  4093  4105 D BluetoothAdapterProperties: Setting state to 12
08-02 10:41:26.887  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-02 10:41:26.888  4093  4105 I BluetoothAdapterState: Entering OnState
08-02 10:41:26.888  3812  3822 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-02 10:41:26.888  4093  4109 D BluetoothAdapterProperties: Scan Mode:21
08-02 10:41:26.889  4093  4109 D BluetoothAdapterProperties: Discoverable Timeout:120
08-02 10:41:26.892  1358  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
08-02 10:41:26.893  3812  3812 D BluetoothInputDevice: Proxy object connected
08-02 10:41:26.893  3812  3812 D HidProfile: Bluetooth service connected
08-02 10:41:26.894   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:26.895  1358  1817 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:26.895  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:26.896  1358  1358 D BluetoothA2dp: Proxy object connected
08-02 10:41:26.898  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:26.899  1358  1817 D BluetoothPbap: onBluetoothStateChange: up=true
08-02 10:41:26.898  4093  4093 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-02 10:41:26.899  1358  1358 D BluetoothInputDevice: Proxy object connected
08-02 10:41:26.899  1358  1358 D HidProfile: Bluetooth service connected
08-02 10:41:26.900  4093  4093 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-02 10:41:26.902  3812  3822 D BluetoothMap: onBluetoothStateChange: up=true
08-02 10:41:26.904  4093  4093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:26.909  4093  4093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:26.909  3812  3823 D BluetoothPbap: onBluetoothStateChange: up=true
,08-02 10:41:26.913  1358  1985 D BluetoothMap: onBluetoothStateChange: up=true
,08-02 10:41:26.914   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-02 10:41:26.914   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true,
,08-02 10:41:26.915   871   871 D BluetoothA2dp: Proxy object connected
,08-02 10:41:26.915  3812  3822 D BluetoothPan: onBluetoothStateChange on: true
,08-02 10:41:26.917  4093  4093 D ObexServerSockets: Succeed to create listening sockets 
08-02 10:41:26.917  4093  4093 D ObexServerSockets0: startAccept()
,08-02 10:41:26.917  4093  4093 D ObexServerSockets0: prepareForNewConnect()
08-02 10:41:26.919  1358  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:26.919  3812  3823 D BluetoothA2dp: onBluetoothStateChange: up=true
08-02 10:41:26.920  4093  4093 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-02 10:41:26.920  4093  4093 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-02 10:41:26.921  4093  4130 D ObexServerSockets0: Accepting socket connection...
08-02 10:41:26.921  4093  4131 D ObexServerSockets0: Accepting socket connection...
,08-02 10:41:26.926  1358  1358 D BluetoothMap: Proxy object connected
,08-02 10:41:26.926  1358  1358 D MapProfile: Bluetooth service connected
08-02 10:41:26.926  1358  1358 D BluetoothMap: getConnectedDevices()
08-02 10:41:26.927  3812  3812 D BluetoothMap: Proxy object connected
08-02 10:41:26.927  3812  3812 D MapProfile: Bluetooth service connected
,08-02 10:41:26.927  3812  3812 D BluetoothMap: getConnectedDevices()
,08-02 10:41:26.928  1713  1906 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:26.930   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 10:41:26.930  3812  3822 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-02 10:41:26.931  1358  1817 D BluetoothPan: onBluetoothStateChange on: true
,08-02 10:41:26.934  3812  3812 D BluetoothPan: BluetoothPAN Proxy object connected
08-02 10:41:26.934  3812  3812 D PanProfile: Bluetooth service connected
08-02 10:41:26.934  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-02 10:41:26.934  1358  1358 D PanProfile: Bluetooth service connected
08-02 10:41:26.935   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-02 10:41:26.936  4093  4093 D BluetoothMapService: onReceive
,08-02 10:41:26.936  4093  4093 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-02 10:41:26.936  4093  4093 D BluetoothMapService: STATE_ON
08-02 10:41:26.938  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:26.934  3812  3812 D BluetoothA2dp: Proxy object connected
,08-02 10:41:26.948  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 10:41:26.955  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 10:41:26.956  3812  3812 D DockEventReceiver: finishStartingService: stopping service
,08-02 10:41:26.966  3812  3812 D BluetoothPbap: Proxy object connected
,08-02 10:41:26.966  1358  1358 D BluetoothPbap: Proxy object connected
08-02 10:41:26.966  3812  3812 D PbapServerProfile: Bluetooth service connected
08-02 10:41:26.966  1358  1358 D PbapServerProfile: Bluetooth service connected
,08-02 10:41:26.966  4093  4093 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-02 10:41:26.966  4093  4093 D ObexServerSockets0: prepareForNewConnect()
,08-02 10:41:26.976  4093  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:26.996  4093  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 10:41:26.997  1358  1817 D BluetoothHeadset: Proxy object connected
08-02 10:41:26.997  1358  1358 D HeadsetProfile: Bluetooth service connected
08-02 10:41:26.997   871   871 D BluetoothHeadset: Proxy object connected
,08-02 10:41:26.998  3812  4132 D BluetoothHeadset: Proxy object connected
,08-02 10:41:26.998  3812  3812 D HeadsetProfile: Bluetooth service connected
08-02 10:41:26.998  4093  4141 I BtOppRfcommListener: Accept thread started.
08-02 10:41:26.999  1713  1973 D BluetoothHeadset: Proxy object connected
,08-02 10:41:26.999   871   871 D BluetoothHeadset: Proxy object connected
08-02 10:41:26.999   871   871 D BluetoothHeadset: Proxy object connected
,08-02 10:41:27.014   871   888 D BluetoothHeadset: Proxy object connected
,08-02 10:41:27.019  1358  1985 D BluetoothHeadset: Proxy object connected
08-02 10:41:27.020  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-02 10:41:27.030  1713  1725 D BluetoothHeadset: Proxy object connected
,08-02 10:41:27.030   871   888 D BluetoothHeadset: Proxy object connected
08-02 10:41:27.031  3812  3823 D BluetoothHeadset: Proxy object connected
08-02 10:41:27.031  3812  3812 D HeadsetProfile: Bluetooth service connected
,08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:27.049  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:27.052  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:27.052  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:27.053  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b77123e added. We now have 8 listener(s)
,08-02 10:41:27.053  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:27.054   871   881 D WifiService: setWifiEnabled: false pid=3760, uid=10000
,08-02 10:41:27.054   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 10:41:27.061  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:27.061   871  1366 D WifiService: setWifiEnabled: true pid=3760, uid=10000
08-02 10:41:27.061   871  1366 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 10:41:27.064   871  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:27.071  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 10:41:27.075  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 10:41:27.076  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 10:41:27.078  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-02 10:41:27.082  3760  4145 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-02 10:41:27.082  3760  4145 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-02 10:41:27.089   871  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-02 10:41:27.089   871  1301 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-02 10:41:27.090   871  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-02 10:41:27.090   871  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-02 10:41:27.091   871  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-02 10:41:27.091   871  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-02 10:41:27.091   871  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-02 10:41:27.091   871  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-02 10:41:27.100   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-02 10:41:27.100   871  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-02 10:41:27.101   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:27.155   871  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-02 10:41:27.155   871  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-02 10:41:27.161   871  1301 E native  : do suspend true
,08-02 10:41:27.164   871  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-02 10:41:27.177   871  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-02 10:41:27.203   871  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 10:41:28.576   871  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-02 10:41:28.716   871  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.12 rxSuccessRate=56.44 delta 1000 -> 994
,08-02 10:41:28.718   871  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-02 10:41:28.718   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 10:41:28.734   871  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-02 10:41:28.773   871  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-02 10:41:28.775  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-02 10:41:29.218  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-02 10:41:29.264  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-02 10:41:29.265  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-02 10:41:29.273   871  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 10:41:29.288   871  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-02 10:41:29.288   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 10:41:29.288   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-02 10:41:29.319   871  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 10:41:29.335   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:29.336   871  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-02 10:41:29.344   871  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-02 10:41:29.387   871  4150 D DhcpClient: Receive thread started
,08-02 10:41:29.474   871  1301 E native  : do suspend false
,08-02 10:41:29.493   871  2012 D DhcpClient: Broadcasting DHCPDISCOVER
,08-02 10:41:29.506   871  4150 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-02 10:41:29.507   871  2012 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-02 10:41:29.511   871  2012 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-02 10:41:29.523   871  4150 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-02 10:41:29.524   871  2012 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-02 10:41:29.529   370   869 D CommandListener: Setting iface cfg
,08-02 10:41:29.540   871  2012 D DhcpClient: Scheduling renewal in 86399s
,08-02 10:41:29.541   871  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-02 10:41:29.544   871  1301 E native  : do suspend true
,08-02 10:41:29.562   871  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-02 10:41:29.566   871  1301 D WifiConfigStore: No blacklist allowed without epno enabled
08-02 10:41:29.567   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-02 10:41:29.570   871  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-02 10:41:29.570   871  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-02 10:41:29.654   871  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-02 10:41:29.655   871  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-02 10:41:29.658   871  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-02 10:41:29.661   871  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-02 10:41:29.664   871  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-02 10:41:29.684   871  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-02 10:41:29.698   871  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-02 10:41:29.698   871  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-02 10:41:29.699   871  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-02 10:41:29.700   871  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-02 10:41:29.700   871  1303 D ConnectivityService:    accepting network in place of null
08-02 10:41:29.701   871  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-02 10:41:29.701   871  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-02 10:41:29.710   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284975, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-02 10:41:29.734   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:29.766   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 10:41:29.775   871  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-02 10:41:29.776   871  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-02 10:41:29.777   871  4148 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-02 10:41:29.790   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-02 10:41:29.809   871  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:29.811  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 10:41:29.813  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 10:41:29.830  3146  4158 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 10:41:29.835  1798  1798 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-02 10:41:29.837   871  4148 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Aug 2016 08:41:29 GMT], X-Android-Received-Millis=[1470127289836], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470127289816]}
,08-02 10:41:29.838   871  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-02 10:41:29.838  1832  1832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-02 10:41:29.838   871  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-02 10:41:29.838   871  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-02 10:41:29.839   871  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-02 10:41:29.844  1832  1832 D SystemUpdateService: onCreate
,08-02 10:41:29.847  1832  1832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-02 10:41:29.866  1832  4161 I SystemUpdateService: active receiver: enabled
,08-02 10:41:29.870  1832  1832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-02 10:41:29.873  1832  2342 I iu.UploadsManager: num queued entries: 0
,08-02 10:41:29.884  1832  1832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-02 10:41:29.885  1832  1832 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-02 10:41:29.887  3892  3892 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-02 10:41:29.890  1832  4163 I MDM     : [217] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-02 10:41:29.891  1832  4163 W BaseAppContext: Using Auth Proxy for data requests.
08-02 10:41:29.892  1832  4163 V GoogleAuthProtoRequest: [217] a.<init>: mAccountName set to: thalitester@gmail.com
,08-02 10:41:29.878  1832  4161 I SystemUpdateService: Already downloaded, skipping offpeak checks.,
,08-02 10:41:29.894  1832  2342 I iu.UploadsManager: num updated entries: 0
,08-02 10:41:29.895  1832  2342 I iu.SyncManager: NEXT; no task
08-02 10:41:29.895  3892  3892 D SprintDMHelper: simOperator: 
08-02 10:41:29.895  3892  3892 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-02 10:41:29.912  1832  4161 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-02 10:41:29.912  1832  4161 I SystemUpdateService: now status is 0 (complete)
08-02 10:41:29.912  1832  4161 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-02 10:41:29.916  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:41:29.918  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:41:29.920  1832  4161 I SystemUpdateService: file has been verified
08-02 10:41:29.920  1832  4161 I SystemUpdateService: OTA package size = 12249756
,08-02 10:41:29.924  3146  4167 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 10:41:29.965  1832  4161 I SystemUpdateService: showing system update notification
,08-02 10:41:29.972  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-02 10:41:29.972  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-02 10:41:29.972  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:41:29.972  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:41:30.014  2370  4166 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-02 10:41:30.024  1513  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:41:30.024  1513  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:41:30.025  1513  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:41:30.025  1513  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:41:30.036  3146  4167 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-02 10:41:30.037  3146  4158 E BooksSync: Soft error
08-02 10:41:30.037  3146  4158 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:41:30.037  3146  4158 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-02 10:41:30.037  3146  4158 E BooksSync: Sync error
08-02 10:41:30.037  3146  4158 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:41:30.037  3146  4158 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:41:30.037  3146  4158 I BooksSync: Finished books sync
,08-02 10:41:30.046  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-02 10:41:30.046  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-02 10:41:30.046  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:41:30.046  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:41:30.055   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 283613, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:41:30.065  1832  1832 D SystemUpdateService: onDestroy
,08-02 10:41:30.078  1832  4163 E MDM     : [217] SitrepService.a: Error sending sitrep.
,08-02 10:41:30.083  3760  4173 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-02 10:41:30.083  3760  4145 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-02 10:41:30.084  3760  4145 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-02 10:41:30.084  3760  4173 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-02 10:41:30.084  3760  4145 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-02 10:41:30.084  3760  4173 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-02 10:41:30.084  3760  4145 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-02 10:41:30.084  3760  4173 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-02 10:41:30.085  3760  4145 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-02 10:41:30.086  3760  4173 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-02 10:41:30.087  3760  4176 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Sender)
08-02 10:41:30.087  3760  4175 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Sender)
,08-02 10:41:30.087  3760  4178 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Receiver)
08-02 10:41:30.088  3760  4178 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: IncomingSocketThread/Receiver)
08-02 10:41:30.088  3760  4177 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Receiver)
08-02 10:41:30.088  3760  4178 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-02 10:41:30.088  3760  4178 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-02 10:41:30.088  3760  4177 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: OutgoingSocketThread/Receiver)
08-02 10:41:30.088  3760  4177 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-02 10:41:30.088  3760  4177 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-02 10:41:33.091  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-02 10:41:33.095  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-02 10:41:33.102  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7e82801 Bundle[{}]
,08-02 10:41:33.102  3760  3806 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-02 10:41:33.102  3760  3806 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-02 10:41:33.103  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-02 10:41:33.104  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-02 10:41:33.104  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-02 10:41:33.105  3760  3806 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-02 10:41:33.109  3760  3806 I System.out: Running OutgoingSocketThread
08-02 10:41:33.113  3760  4183 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-02 10:41:33.113  3760  4183 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-02 10:41:36.123  3760  4184 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-02 10:41:36.123  3760  4184 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-02 10:41:36.124  3760  4184 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-02 10:41:36.123  3760  4183 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-02 10:41:36.124  3760  4183 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-02 10:41:36.125  3760  4184 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-02 10:41:36.125  3760  4183 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-02 10:41:36.127  3760  4186 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: IncomingSocketThread/Sender)
,08-02 10:41:36.130  3760  4184 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-02 10:41:36.133  3760  4183 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-02 10:41:36.134  3760  4187 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Receiver)
,08-02 10:41:36.135  3760  4187 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: IncomingSocketThread/Receiver)
08-02 10:41:36.135  3760  4187 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-02 10:41:36.136  3760  4188 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: OutgoingSocketThread/Sender)
08-02 10:41:36.136  3760  4187 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-02 10:41:36.136  3760  4183 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-02 10:41:36.137  3760  4189 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: OutgoingSocketThread/Receiver)
08-02 10:41:36.138  3760  4189 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: OutgoingSocketThread/Receiver)
08-02 10:41:36.138  3760  4189 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-02 10:41:36.138  3760  4189 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-02 10:41:37.706   871  1303 D ConnectivityService: handlePromptUnvalidated 102
,08-02 10:41:39.125  3760  3806 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 455)
,08-02 10:41:39.127  3760  3806 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-02 10:41:39.127  3760  3806 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 456)
,08-02 10:41:39.133  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-02 10:41:39.133  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@335d89f added. We now have 2 listener(s)
08-02 10:41:39.135  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 10:41:39.136  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 10:41:39.136  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.136  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:39.136  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe7ddec added. We now have 9 listener(s)
08-02 10:41:39.136  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.137  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:41:39.142  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:39.156  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:39.162  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 10:41:39.162  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-02 10:41:39.163  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.164  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cce144a added. We now have 3 listener(s)
,08-02 10:41:39.169  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.170  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 10:41:39.170  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 10:41:39.171  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.171  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:39.171  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9295fbb added. We now have 10 listener(s)
08-02 10:41:39.172  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 10:41:39.172  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:39.172  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:39.173  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:39.173  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:39.173  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.173  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:39.174  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.174  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@335d89f removed from the list
08-02 10:41:39.174  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.174  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe7ddec removed from the list
,08-02 10:41:39.177  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.177  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:39.178  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.179  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.180  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.182  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:39.182  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-02 10:41:39.182  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.183  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe7ddec not in the list
08-02 10:41:39.183  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.183  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.186  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.186  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:39.187  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:39.187  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9295fbb removed from the list
08-02 10:41:39.187  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:39.187  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.188  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.188  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.188  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cce144a removed from the list
,08-02 10:41:39.190  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-02 10:41:39.191  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76aecd8 added. We now have 2 listener(s)
,08-02 10:41:39.196  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 10:41:39.197  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 10:41:39.197  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.198  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:39.198  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0d831 added. We now have 9 listener(s)
08-02 10:41:39.198  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.199  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:41:39.206  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:39.220  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:39.228  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 10:41:39.228  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-02 10:41:39.233  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.233  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1043c97 added. We now have 3 listener(s)
,08-02 10:41:39.239  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.241  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 10:41:39.242  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 10:41:39.242  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.242  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:39.243  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0dfe84 added. We now have 10 listener(s)
,08-02 10:41:39.243  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.244  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:39.244  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 10:41:39.244  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-02 10:41:39.245  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:39.245  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-02 10:41:39.249  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.255  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-02 10:41:39.255  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-02 10:41:39.263  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-02 10:41:39.264  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-02 10:41:39.264  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-02 10:41:39.271  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-02 10:41:39.271  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-02 10:41:39.271  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-02 10:41:39.272  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:39.279  4093  4103 D BtGatt.GattService: registerClient() - UUID=1391bbbc-0266-4a88-88d7-64d730c9c9c0
,08-02 10:41:39.282  4093  4109 D BtGatt.GattService: onClientRegistered() - UUID=1391bbbc-0266-4a88-88d7-64d730c9c9c0, clientIf=5
,08-02 10:41:39.283  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-02 10:41:39.284  4093  4104 D BtGatt.GattService: start scan with filters
,08-02 10:41:39.289  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-02 10:41:39.289  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-02 10:41:39.290  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-02 10:41:39.290  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-02 10:41:39.290  4093  4112 D BtGatt.ScanManager: handling starting scan
,08-02 10:41:39.292  4093  4112 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e828885
08-02 10:41:39.294  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:39.294  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-02 10:41:39.294  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-02 10:41:39.296  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-02 10:41:39.299  3760  3806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-02 10:41:39.300  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:39.300  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-02 10:41:39.300  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.300  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 10:41:39.300  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-02 10:41:39.300  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 10:41:39.300  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 10:41:39.300  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:39.302  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-02 10:41:39.302  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-02 10:41:39.303  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:39.305  4093  4103 D BtGatt.GattService: stopScan() - queue size =1
,08-02 10:41:39.306  4093  4104 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-02 10:41:39.307  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-02 10:41:39.306  4093  4109 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-02 10:41:39.307  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-02 10:41:39.307  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-02 10:41:39.307  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.307  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-02 10:41:39.307  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-02 10:41:39.308  4093  4112 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-02 10:41:39.309  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:39.309  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-02 10:41:39.309  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-02 10:41:39.309  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-02 10:41:39.310  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-02 10:41:39.312  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:39.312  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:39.313  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-02 10:41:39.316  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:39.316  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-02 10:41:39.316  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:39.317  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:39.317  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.317  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:39.317  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.317  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76aecd8 removed from the list
08-02 10:41:39.317  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:39.318  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0d831 removed from the list
08-02 10:41:39.318  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:39.318  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.319  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.319  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.320  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:39.320  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-02 10:41:39.320  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.320  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0d831 not in the list
08-02 10:41:39.321  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.321  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.322  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.322  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:39.322  4093  4109 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-02 10:41:39.322  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.323  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0dfe84 removed from the list
08-02 10:41:39.323  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.323  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:39.324  4093  4112 D BtGatt.ScanManager: Starting BLE batch scan
08-02 10:41:39.324  4093  4112 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-02 10:41:39.324  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.324  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.324  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.326  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1043c97 removed from the list
,08-02 10:41:39.327  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.327  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ae7ef0 added. We now have 2 listener(s)
,08-02 10:41:39.330  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 10:41:39.331  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 10:41:39.331  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.331  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:39.331  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6995c69 added. We now have 9 listener(s)
08-02 10:41:39.331  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.332  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:41:39.336  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:39.348  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:39.351  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 10:41:39.351  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 10:41:39.352  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-02 10:41:39.352  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cc278f added. We now have 3 listener(s)
08-02 10:41:39.354  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.354  4093  4109 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-02 10:41:39.354  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.355  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 10:41:39.355  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 10:41:39.355  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.356  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 10:41:39.356  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@949a1c added. We now have 10 listener(s)
08-02 10:41:39.357  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.357  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:39.357  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:39.358  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-02 10:41:39.358  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 10:41:39.358  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 10:41:39.358  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:39.358  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-02 10:41:39.363  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-02 10:41:39.363  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-02 10:41:39.366  4093  4109 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-02 10:41:39.366  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.368  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-02 10:41:39.368  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-02 10:41:39.368  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-02 10:41:39.373  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-02 10:41:39.374  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-02 10:41:39.374  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-02 10:41:39.375  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:39.378  4093  4121 D BtGatt.GattService: registerClient() - UUID=097bab8e-d2a6-4eb7-b6ec-7fdcefa98b43
,08-02 10:41:39.379  4093  4109 D BtGatt.GattService: onClientRegistered() - UUID=097bab8e-d2a6-4eb7-b6ec-7fdcefa98b43, clientIf=5
08-02 10:41:39.379  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-02 10:41:39.379  4093  4133 D BtGatt.GattService: start scan with filters
,08-02 10:41:39.384  4093  4109 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-02 10:41:39.384  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-02 10:41:39.384  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.384  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-02 10:41:39.384  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-02 10:41:39.384  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-02 10:41:39.384  4093  4112 D BtGatt.ScanManager: stopping BLe Batch
,08-02 10:41:39.387  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:39.387  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-02 10:41:39.387  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-02 10:41:39.389  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-02 10:41:39.393  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-02 10:41:39.393  3760  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-02 10:41:39.394  4093  4109 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-02 10:41:39.394  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.394  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 10:41:39.394  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:39.394  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:39.394  4093  4112 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-02 10:41:39.394  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:39.394  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-02 10:41:39.394  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 10:41:39.394  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.394  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ae7ef0 removed from the list
08-02 10:41:39.395  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:39.395  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6995c69 removed from the list
08-02 10:41:39.395  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:39.395  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-02 10:41:39.396  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.396  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-02 10:41:39.396  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.397  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:39.398  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-02 10:41:39.398  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.398  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 10:41:39.398  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6995c69 not in the list
08-02 10:41:39.399  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 10:41:39.399  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 10:41:39.399  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:39.399  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-02 10:41:39.400  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-02 10:41:39.401  3760  3806 D BluetoothAdapter: STATE_ON
08-02 10:41:39.402  4093  4104 D BtGatt.GattService: stopScan() - queue size =0
08-02 10:41:39.403  4093  4103 D BtGatt.GattService: unregisterClient() - clientIf=5
08-02 10:41:39.403  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-02 10:41:39.404  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-02 10:41:39.404  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-02 10:41:39.404  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-02 10:41:39.404  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-02 10:41:39.405  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:39.405  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-02 10:41:39.405  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-02 10:41:39.405  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 10:41:39.406  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.406  4093  4109 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-02 10:41:39.406  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.408  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.408  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-02 10:41:39.408  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.408  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@949a1c removed from the list
08-02 10:41:39.408  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:39.408  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.408  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.408  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:39.408  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.408  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:39.409  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cc278f removed from the list
,08-02 10:41:39.409  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:39.409  4093  4112 D BtGatt.ScanManager: handling starting scan
08-02 10:41:39.409  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.409  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f3c08 added. We now have 2 listener(s)
08-02 10:41:39.412  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 10:41:39.412  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 10:41:39.412  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.412  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 10:41:39.412  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c072fa1 added. We now have 9 listener(s)
08-02 10:41:39.412  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.413  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:41:39.420  4093  4109 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-02 10:41:39.420  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.419  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:39.421  4093  4112 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:39.428  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:39.432  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 10:41:39.432  4093  4109 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-02 10:41:39.432  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 10:41:39.432  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.433  4093  4112 D BtGatt.ScanManager: Starting BLE batch scan
,08-02 10:41:39.433  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.433  4093  4112 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-02 10:41:39.433  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b577987 added. We now have 3 listener(s)
08-02 10:41:39.435  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 10:41:39.436  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 10:41:39.436  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.436  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 10:41:39.436  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b010b4 added. We now have 10 listener(s)
,08-02 10:41:39.436  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.437  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:39.437  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 10:41:39.437  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 10:41:39.437  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:39.437  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-02 10:41:39.437  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.443  3760  3806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-02 10:41:39.443  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-02 10:41:39.444  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.448  4093  4109 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-02 10:41:39.449  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.450  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-02 10:41:39.451  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-02 10:41:39.451  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-02 10:41:39.457  4093  4109 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-02 10:41:39.457  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.457  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-02 10:41:39.457  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-02 10:41:39.457  3760  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-02 10:41:39.459  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:39.463  4093  4133 D BtGatt.GattService: registerClient() - UUID=4bdb5258-7134-4102-b2d3-ffe6d509d56b
,08-02 10:41:39.464  4093  4109 D BtGatt.GattService: onClientRegistered() - UUID=4bdb5258-7134-4102-b2d3-ffe6d509d56b, clientIf=5
08-02 10:41:39.465  3760  3770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-02 10:41:39.465  4093  4104 D BtGatt.GattService: start scan with filters
,08-02 10:41:39.467  4093  4109 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-02 10:41:39.468  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.468  4093  4112 D BtGatt.ScanManager: stopping BLe Batch
,08-02 10:41:39.473  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-02 10:41:39.474  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-02 10:41:39.474  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-02 10:41:39.474  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-02 10:41:39.477  4093  4109 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-02 10:41:39.477  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.478  4093  4112 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-02 10:41:39.479  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-02 10:41:39.480  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-02 10:41:39.480  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-02 10:41:39.483  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-02 10:41:39.488  4093  4109 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-02 10:41:39.488  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.491  4093  4112 D BtGatt.ScanManager: handling starting scan
,08-02 10:41:39.499  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-02 10:41:39.499  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-02 10:41:39.499  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:39.500  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:39.500  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.500  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 10:41:39.500  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.500  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f3c08 removed from the list
,08-02 10:41:39.500  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.501  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c072fa1 removed from the list
,08-02 10:41:39.501  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:39.501  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 10:41:39.502  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.502  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-02 10:41:39.502  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.502  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-02 10:41:39.502  4093  4109 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-02 10:41:39.502  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.503  4093  4112 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-02 10:41:39.504  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:39.504  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.504  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-02 10:41:39.504  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c072fa1 not in the list
08-02 10:41:39.504  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-02 10:41:39.504  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 10:41:39.505  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 10:41:39.505  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-02 10:41:39.505  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-02 10:41:39.507  3760  3806 D BluetoothAdapter: STATE_ON
,08-02 10:41:39.508  4093  4122 D BtGatt.GattService: stopScan() - queue size =1
08-02 10:41:39.509  4093  4133 D BtGatt.GattService: unregisterClient() - clientIf=5
08-02 10:41:39.511  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-02 10:41:39.511  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-02 10:41:39.511  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-02 10:41:39.512  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-02 10:41:39.512  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-02 10:41:39.513  4093  4109 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-02 10:41:39.513  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.514  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:39.514  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-02 10:41:39.514  3760  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-02 10:41:39.514  4093  4112 D BtGatt.ScanManager: Starting BLE batch scan
08-02 10:41:39.514  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 10:41:39.514  4093  4112 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-02 10:41:39.516  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.519  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.519  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-02 10:41:39.519  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.519  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b010b4 removed from the list
08-02 10:41:39.519  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:39.520  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 10:41:39.519  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:39.520  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.520  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.520  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 10:41:39.520  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.521  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b577987 removed from the list
,08-02 10:41:39.523  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.523  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6978420 added. We now have 2 listener(s)
,08-02 10:41:39.530  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 10:41:39.530  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 10:41:39.530  4093  4109 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-02 10:41:39.530  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.530  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.531  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 10:41:39.531  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98531d9 added. We now have 9 listener(s)
08-02 10:41:39.531  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 10:41:39.532  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-02 10:41:39.536  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 10:41:39.537  4093  4109 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-02 10:41:39.538  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 10:41:39.544  3760  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 10:41:39.548  4093  4109 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-02 10:41:39.549  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-02 10:41:39.549  3760  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-02 10:41:39.549  4093  4112 D BtGatt.ScanManager: stopping BLe Batch
08-02 10:41:39.549  3760  3806 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 10:41:39.550  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 10:41:39.550  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cc127f added. We now have 3 listener(s)
08-02 10:41:39.554  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 10:41:39.554  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 10:41:39.555  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-02 10:41:39.555  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 10:41:39.555  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 10:41:39.555  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c0c24c added. We now have 10 listener(s)
,08-02 10:41:39.555  3760  3806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 10:41:39.555  3760  3806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-02 10:41:39.556  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-02 10:41:39.556  3760  3806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 10:41:39.556  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-02 10:41:39.556  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.556  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-02 10:41:39.556  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
,08-02 10:41:39.556  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6978420 removed from the list
,08-02 10:41:39.556  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.557  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98531d9 removed from the list
,08-02 10:41:39.559  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 10:41:39.559  3760  3806 D io.jxcore.node.ConnectivityMonitor: stop
08-02 10:41:39.559  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.560  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-02 10:41:39.560  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 10:41:39.561  4093  4109 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-02 10:41:39.561  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.561  4093  4112 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-02 10:41:39.562  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 10:41:39.562  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-02 10:41:39.562  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.562  3760  3806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98531d9 not in the list
08-02 10:41:39.562  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 10:41:39.562  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.563  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 10:41:39.564  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-02 10:41:39.564  3760  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 10:41:39.564  3760  3806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c0c24c removed from the list
08-02 10:41:39.564  3760  3806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 10:41:39.564  3760  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-02 10:41:39.564  3760  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 10:41:39.564  3760  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 10:41:39.564  3760  3806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cc127f removed from the list
08-02 10:41:39.565  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-02 10:41:39.566  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-02 10:41:39.566  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-02 10:41:39.566  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:39.566  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-02 10:41:39.566  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:39.574  4093  4109 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-02 10:41:39.574  4093  4109 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-02 10:41:39.576  3760  4190 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,08-02 10:41:39.814  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-02 10:41:39.909  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-02 10:41:40.022  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-02 10:41:41.576  3760  3806 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 464
,08-02 10:41:41.576  3760  3806 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 464, name: My test thread name)
,08-02 10:41:41.585  3760  4191 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,08-02 10:41:41.585  3760  4191 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 465, thread name: My test thread name)
08-02 10:41:41.586  3760  4191 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-02 10:41:41.594  3760  3806 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-02 10:41:41.601  3760  4190 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-02 10:41:41.604  3760  4192 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: My test thread name)
,08-02 10:41:41.605  3760  4192 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 469, thread name: My test thread name): Test exception.
08-02 10:41:41.606  3760  4192 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 469, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-02 10:41:41.608  3760  3806 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
,08-02 10:41:41.609  3760  3806 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
,08-02 10:41:41.610  3760  3806 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-02 10:41:41.610  3760  3806 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-02 10:41:41.611  3760  3806 D com.test.thalitest.ThaliTestRunner: Total duration: 34951 ms
,08-02 10:41:41.616  3760  3806 I jxcore-log: Total number of executed tests:  82
08-02 10:41:41.616  3760  3806 I jxcore-log: 
,08-02 10:41:41.617  3760  3806 I jxcore-log: Number of passed tests:  82
08-02 10:41:41.617  3760  3806 I jxcore-log: 
,08-02 10:41:41.617  3760  3806 I jxcore-log: Number of failed tests:  0
08-02 10:41:41.617  3760  3806 I jxcore-log: 
,08-02 10:41:41.619  3760  3806 I jxcore-log: Number of ignored tests:  0
08-02 10:41:41.619  3760  3806 I jxcore-log: 
,08-02 10:41:41.619  3760  3806 I jxcore-log: Total duration:  34951
08-02 10:41:41.619  3760  3806 I jxcore-log: 
,08-02 10:41:41.629  3760  3806 I jxcore-log: Unit Test app is loaded
08-02 10:41:41.629  3760  3806 I jxcore-log: 
,08-02 10:41:41.649  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.649  3760  3806 I jxcore-log: 
,08-02 10:41:41.657  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.657  3760  3806 I jxcore-log: 
,08-02 10:41:41.659  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.659  3760  3806 I jxcore-log: 
,08-02 10:41:41.660  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.660  3760  3806 I jxcore-log: 
,08-02 10:41:41.661  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.661  3760  3806 I jxcore-log: 
,08-02 10:41:41.662  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.662  3760  3806 I jxcore-log: 
,08-02 10:41:41.665  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.665  3760  3806 I jxcore-log: 
,08-02 10:41:41.667  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-02 10:41:41.667  3760  3806 I jxcore-log: 
,08-02 10:41:41.668  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-02 10:41:41.668  3760  3806 I jxcore-log: 
,08-02 10:41:41.669  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.669  3760  3806 I jxcore-log: 
08-02 10:41:41.669  3760  3760 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-02 10:41:41.670  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.670  3760  3806 I jxcore-log: 
,08-02 10:41:41.671  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-02 10:41:41.671  3760  3806 I jxcore-log: 
08-02 10:41:41.673  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-02 10:41:41.673  3760  3806 I jxcore-log: 
,08-02 10:41:41.673  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-02 10:41:41.673  3760  3806 I jxcore-log: 
,08-02 10:41:41.674  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.674  3760  3806 I jxcore-log: 
,08-02 10:41:41.675  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.675  3760  3806 I jxcore-log: 
,08-02 10:41:41.676  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.676  3760  3806 I jxcore-log: 
,08-02 10:41:41.677  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.677  3760  3806 I jxcore-log: 
,08-02 10:41:41.678  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.678  3760  3806 I jxcore-log: 
08-02 10:41:41.679  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.679  3760  3806 I jxcore-log: 
,08-02 10:41:41.679  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.679  3760  3806 I jxcore-log: 
,08-02 10:41:41.680  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.680  3760  3806 I jxcore-log: 
,08-02 10:41:41.681  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.681  3760  3806 I jxcore-log: 
,08-02 10:41:41.682  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-02 10:41:41.682  3760  3806 I jxcore-log: 
,08-02 10:41:41.683  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-02 10:41:41.683  3760  3806 I jxcore-log: 
,08-02 10:41:41.684  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-02 10:41:41.684  3760  3806 I jxcore-log: 
,08-02 10:41:41.684  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.684  3760  3806 I jxcore-log: 
,08-02 10:41:41.685  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.685  3760  3806 I jxcore-log: 
,08-02 10:41:41.686  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.686  3760  3806 I jxcore-log: 
,08-02 10:41:41.687  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.687  3760  3806 I jxcore-log: 
08-02 10:41:41.688  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.688  3760  3806 I jxcore-log: 
,08-02 10:41:41.688  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-02 10:41:41.688  3760  3806 I jxcore-log: 
,08-02 10:41:41.689  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-02 10:41:41.689  3760  3806 I jxcore-log: 
,08-02 10:41:41.690  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-02 10:41:41.690  3760  3806 I jxcore-log: 
,08-02 10:41:41.691  3760  3806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-02 10:41:41.691  3760  3806 I jxcore-log: 
,08-02 10:41:41.696  3760  3806 I jxcore-log: My device name is: motorola-Nexus 6
08-02 10:41:41.696  3760  3806 I jxcore-log: 
,08-02 10:41:41.697  3760  3806 I jxcore-log: WARN testUtils: myNameCallback not set!
08-02 10:41:41.697  3760  3806 I jxcore-log: 
,08-02 10:41:45.648  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-02 10:41:45.648  3760  3806 I jxcore-log: 
,08-02 10:41:45.790  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-02 10:41:45.790  3760  3806 I jxcore-log: 
,08-02 10:41:45.814  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-02 10:41:45.814  3760  3806 I jxcore-log: 
,08-02 10:41:45.818  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-02 10:41:45.818  3760  3806 I jxcore-log: 
,08-02 10:41:45.822  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-02 10:41:45.822  3760  3806 I jxcore-log: 
,08-02 10:41:45.838  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-02 10:41:45.838  3760  3806 I jxcore-log: 
,08-02 10:41:45.842  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-02 10:41:45.842  3760  3806 I jxcore-log: 
,08-02 10:41:46.488  1513  2006 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-02 10:41:47.833  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-02 10:41:47.833  3760  3806 I jxcore-log: 
,08-02 10:41:47.846  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-02 10:41:47.846  3760  3806 I jxcore-log: 
,08-02 10:41:47.855  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-02 10:41:47.855  3760  3806 I jxcore-log: 
,08-02 10:41:48.015  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-02 10:41:48.015  3760  3806 I jxcore-log: 
,08-02 10:41:48.834  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-02 10:41:48.834  3760  3806 I jxcore-log: 
,08-02 10:41:48.892  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-02 10:41:48.892  3760  3806 I jxcore-log: 
,08-02 10:41:48.899  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-02 10:41:48.899  3760  3806 I jxcore-log: 
,08-02 10:41:49.104  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-02 10:41:49.104  3760  3806 I jxcore-log: 
,08-02 10:41:49.127  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-02 10:41:49.127  3760  3806 I jxcore-log: 
,08-02 10:41:49.132  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-02 10:41:49.132  3760  3806 I jxcore-log: 
,08-02 10:41:49.138  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-02 10:41:49.138  3760  3806 I jxcore-log: 
,08-02 10:41:49.154  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-02 10:41:49.154  3760  3806 I jxcore-log: 
,08-02 10:41:49.175  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-02 10:41:49.175  3760  3806 I jxcore-log: 
,08-02 10:41:49.264  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-02 10:41:49.264  3760  3806 I jxcore-log: 
,08-02 10:41:49.270  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-02 10:41:49.270  3760  3806 I jxcore-log: 
,08-02 10:41:49.298  3760  3806 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-02 10:41:49.298  3760  3806 I jxcore-log: 
,08-02 10:41:49.312  3760  3806 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-02 10:41:49.314  3760  3806 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-02 10:41:49.314  3760  3806 I jxcore-log: 
,08-02 10:41:49.364  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 10:41:49.365  3760  3806 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,08-02 10:41:49.365  3760  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 10:41:49.365  3760  3806 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-02 10:41:51.738   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307004, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:41:55.017  1648  1684 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-02 10:41:55.017  1648  1684 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-02 10:41:55.068  1513  1513 I ConfigService: onCreate
,08-02 10:42:00.144  1513  1513 I ConfigService: onDestroy
,08-02 10:42:00.850  3146  4196 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 10:42:00.897  3146  4197 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 10:42:00.934  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:00.940  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:00.992  1513  2014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:42:00.992  1513  2014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-02 10:42:00.992  1513  2014 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:42:00.992  1513  2014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:42:01.029  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:01.035  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:01.075  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:42:01.075  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:42:01.075  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:42:01.075  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:42:01.100  3146  4197 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-02 10:42:01.101  3146  4196 E BooksSync: Soft error
08-02 10:42:01.101  3146  4196 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:42:01.101  3146  4196 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:42:01.101  3146  4196 E BooksSync: Sync error
08-02 10:42:01.101  3146  4196 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:42:01.101  3146  4196 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:42:01.102  3146  4196 I BooksSync: Finished books sync
,08-02 10:42:01.110   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 315871, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:42:27.605  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:27.626  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:27.628  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:42:27.675  1513  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-02 10:42:27.675  1513  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 10:42:27.675  1513  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:42:27.676  1513  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:42:27.703  1513  2076 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 10:42:27.703  1513  2076 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 10:42:27.703  1513  2076 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 10:42:27.703  1513  2076 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 10:42:27.703  1513  2076 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 10:42:27.703  1513  2076 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 10:42:27.703  1513  2076 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 10:42:27.705  3455  3486 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-02 10:42:27.705  3455  3486 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 10:42:27.705  3455  3486 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 10:42:27.705  3455  3486 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 10:42:27.705  3455  3486 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 10:42:27.705  3455  3486 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 10:42:27.705  3455  3486 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 10:42:31.310  3046  4203 V KeepSync: Connecting to GoogleApiClient
,08-02 10:42:31.310   871  1526 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 10:42:31.408  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-02 10:42:31.408  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.,
08-02 10:42:31.408  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:42:31.408  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:42:31.446  1832  4204 V BaseAuthAsyncOperation: access token request failed
,08-02 10:42:31.448  3046  4203 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 10:42:31.534  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-02 10:42:31.534  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-02 10:42:31.535  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:42:31.535  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:42:31.558  3046  4203 E KeepSync: IOException
08-02 10:42:31.558  3046  4203 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 10:42:31.558  3046  4203 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:42:31.558  3046  4203 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 10:42:31.558  3046  4203 E KeepSync: 	... 10 more
,08-02 10:42:31.558  3046  4203 W KeepSync: Sync result 2
,08-02 10:42:31.572   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 321378, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:42:32.732   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-02 10:42:49.584   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=364850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:43:02.301  3146  4207 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 10:43:02.355  3146  4208 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 10:43:02.382  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:43:02.389  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:43:02.463  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:43:02.463  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-02 10:43:02.464  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:43:02.464  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:43:02.525  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:43:02.530  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:43:02.559  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-02 10:43:02.559  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:43:02.560  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:43:02.560  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:43:02.582  3146  4208 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-02 10:43:02.583  3146  4207 E BooksSync: Soft error
08-02 10:43:02.583  3146  4207 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:43:02.583  3146  4207 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:43:02.583  3146  4207 E BooksSync: Sync error
08-02 10:43:02.583  3146  4207 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:43:02.583  3146  4207 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:43:02.583  3146  4207 I BooksSync: Finished books sync
,08-02 10:43:02.591   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 377477, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:43:02.764  3046  4209 V KeepSync: Connecting to GoogleApiClient
,08-02 10:43:02.765   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 10:43:02.812  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:43:02.818  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:43:02.848  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-02 10:43:02.848  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-02 10:43:02.848  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:43:02.848  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:43:02.870  1832  4210 V BaseAuthAsyncOperation: access token request failed
,08-02 10:43:02.871  3046  4209 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 10:43:02.932  1513  2014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-02 10:43:02.932  1513  2014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-02 10:43:02.932  1513  2014 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:43:02.932  1513  2014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:43:02.953  3046  4209 E KeepSync: IOException
08-02 10:43:02.953  3046  4209 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 10:43:02.953  3046  4209 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:43:02.953  3046  4209 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 10:43:02.953  3046  4209 E KeepSync: 	... 10 more
08-02 10:43:02.953  3046  4209 W KeepSync: Sync result 2
,08-02 10:43:02.964   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 377632, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:43:33.651   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=408917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-02 10:43:55.931   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:44:04.662  3046  4213 V KeepSync: Connecting to GoogleApiClient
,08-02 10:44:04.663   871  1729 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 10:44:04.741  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:44:04.745  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:44:04.791  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-02 10:44:04.791  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-02 10:44:04.791  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:44:04.792  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:44:04.831  1832  4214 V BaseAuthAsyncOperation: access token request failed
,08-02 10:44:04.835  3046  4213 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 10:44:04.918  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-02 10:44:04.918  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-02 10:44:04.918  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:44:04.918  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:44:04.944  3046  4213 E KeepSync: IOException
08-02 10:44:04.944  3046  4213 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 10:44:04.944  3046  4213 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:44:04.944  3046  4213 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 10:44:04.944  3046  4213 E KeepSync: 	... 10 more
,08-02 10:44:04.944  3046  4213 W KeepSync: Sync result 2
,08-02 10:44:04.952   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 439818, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:44:56.015  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:44:56.019  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:44:56.069  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:44:56.069  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:44:56.069  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:44:56.069  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:44:56.090  3494  4218 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 10:44:56.090  3494  4218 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at blb.a(PG:3937)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at czp.a(PG:18188)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:44:56.090  3494  4218 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	... 12 more
08-02 10:44:56.090  3494  4218 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at fal.a(PG:38)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:44:56.090  3494  4218 E HttpOperation: 	... 14 more
,08-02 10:44:56.131  1513  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:44:56.131  1513  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:44:56.131  1513  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:44:56.131  1513  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:44:56.165  3494  4218 E HttpOperation: [getmobileexperiments] Unexpected exception,
08-02 10:44:56.165  3494  4218 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at hec.a(PG:42)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at hee.a(PG:102)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at czr.a(PG:65)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at kka.a(PG:108)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at czp.a(PG:19176)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:44:56.165  3494  4218 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	... 15 more
08-02 10:44:56.165  3494  4218 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at fal.a(PG:38)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:44:56.165  3494  4218 E HttpOperation: 	... 17 more
08-02 10:44:56.165  3494  4218 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 10:44:56.165  3494  4218 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at hec.a(PG:42)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at hee.a(PG:102)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at czr.a(PG:65)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at kka.a(PG:108)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 10:44:56.1,65  3494  4218 E ExperimentLoader: 	... 15 more
08-02 10:44:56.165  3494  4218 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at fal.a(PG:38)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 10:44:56.165  3494  4218 E ExperimentLoader: 	... 17 more
,08-02 10:44:56.315   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 490937, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:45:17.692   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=512957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-02 10:45:26.373   871   871 I ActivityManager: Start proc 4222:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-02 10:45:26.493  3146  4234 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 10:45:26.511  4222  4222 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-02 10:45:26.538  4222  4222 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-02 10:45:26.538  4222  4222 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-02 10:45:26.538  4222  4222 I GAv4    :   adb logcat -s GAv4
,08-02 10:45:26.574  4222  4222 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-02 10:45:26.578  4222  4222 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-02 10:45:26.591  3146  4239 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 10:45:26.595  4222  4238 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-02 10:45:26.600  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:45:26.602  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:45:26.629  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:45:26.629  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-02 10:45:26.629  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:45:26.630  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:45:26.668  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-02 10:45:26.669  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:45:26.692  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:45:26.693  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:45:26.693  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:45:26.693  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:45:26.716  3146  4239 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-02 10:45:26.716  3146  4234 E BooksSync: Soft error
08-02 10:45:26.716  3146  4234 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:45:26.716  3146  4234 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-02 10:45:26.717  3146  4234 E BooksSync: Sync error
08-02 10:45:26.717  3146  4234 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:45:26.717  3146  4234 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:45:26.717  3146  4234 I BooksSync: Finished books sync
,08-02 10:45:26.726   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 500058, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:45:26.729   871  1730 I ActivityManager: Killing 3639:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-02 10:45:39.238   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=534503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:45:57.105  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:45:57.106  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:45:57.138  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:45:57.138  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:45:57.138  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:45:57.139  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:45:57.156  3494  4242 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 10:45:57.156  3494  4242 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at blb.a(PG:3937)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at czp.a(PG:18188)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:45:57.156  3494  4242 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	... 12 more
08-02 10:45:57.156  3494  4242 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at fal.a(PG:38)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:45:57.156  3494  4242 E HttpOperation: 	... 14 more
,08-02 10:45:57.239  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:45:57.239  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:45:57.239  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:45:57.239  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:45:57.256  3494  4242 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 10:45:57.256  3494  4242 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at hec.a(PG:42)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at hee.a(PG:102)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at czr.a(PG:65)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at kka.a(PG:108)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at czp.a(PG:19176)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:45:57.256  3494  4242 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	... 15 more
08-02 10:45:57.256  3494  4242 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at fal.a(PG:38)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:45:57.256  3494  4242 E HttpOperation: 	... 17 more
,08-02 10:45:57.256  3494  4242 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 10:45:57.256  3494  4242 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at hec.a(PG:42)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at hee.a(PG:102)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at czr.a(PG:65)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at kka.a(PG:108)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	... 15 more
08-02 10:45:57.256  3494  4242 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at fal.a(PG:38)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 10:45:57.256  3494  4242 E ExperimentLoader: 	... 17 more
,08-02 10:45:57.422   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 522976, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:46:27.580  3046  4246 V KeepSync: Connecting to GoogleApiClient
,08-02 10:46:27.580   871  1771 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 10:46:27.643  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:46:27.649  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:46:27.690  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-02 10:46:27.691  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-02 10:46:27.691  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:46:27.691  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:46:27.717  1832  4247 V BaseAuthAsyncOperation: access token request failed
08-02 10:46:27.718  3046  4246 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 10:46:27.794  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-02 10:46:27.794  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-02 10:46:27.794  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:46:27.794  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:46:27.818  3046  4246 E KeepSync: IOException
08-02 10:46:27.818  3046  4246 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 10:46:27.818  3046  4246 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:46:27.818  3046  4246 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 10:46:27.818  3046  4246 E KeepSync: 	... 10 more
,08-02 10:46:27.818  3046  4246 W KeepSync: Sync result 2
,08-02 10:46:27.829   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 563394, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:46:33.198   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=588463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-02 10:46:54.918   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=610184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:47:00.502  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:47:00.505  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:47:00.537  1513  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:47:00.537  1513  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:47:00.537  1513  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:47:00.537  1513  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:47:00.557  3494  4250 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 10:47:00.557  3494  4250 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at blb.a(PG:3937)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at czp.a(PG:18188)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:47:00.557  3494  4250 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	... 12 more
08-02 10:47:00.557  3494  4250 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at fal.a(PG:38)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:47:00.557  3494  4250 E HttpOperation: 	... 14 more
,08-02 10:47:00.610  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:47:00.610  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-02 10:47:00.610  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:47:00.610  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:47:00.626  3494  4250 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 10:47:00.626  3494  4250 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at hec.a(PG:42)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at hee.a(PG:102)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at czr.a(PG:65)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at kka.a(PG:108)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at czp.a(PG:19176)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:47:00.626  3494  4250 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jdm.a(PG:77)
,08-02 10:47:00.626  3494  4250 E HttpOperation: 	... 15 more
08-02 10:47:00.626  3494  4250 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at fal.a(PG:38)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:47:00.626  3494  4250 E HttpOperation: 	... 17 more
08-02 10:47:00.627  3494  4250 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 10:47:00.627  3494  4250 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at hec.a(PG:42)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at hee.a(PG:102)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at czr.a(PG:65)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at kka.a(PG:108)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	... 15 more
08-02 10:47:00.627  3494  4250 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at fal.a(PG:38)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 10:47:00.627  3494  4250 E ExperimentLoader: 	... 17 more
,08-02 10:47:00.754   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 615478, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:47:05.211   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=620477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-02 10:47:26.758   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=642024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:47:33.051   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=648317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-02 10:47:54.598   871  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=669864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-02 10:47:57.295  1513  2006 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-02 10:49:06.701  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:49:06.704  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:49:06.756  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-02 10:49:06.756  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:49:06.756  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:49:06.757  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:49:06.782  3494  4262 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 10:49:06.782  3494  4262 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at blb.a(PG:3937)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at czp.a(PG:18188)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:49:06.782  3494  4262 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	... 12 more
08-02 10:49:06.782  3494  4262 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at fal.a(PG:38)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:49:06.782  3494  4262 E HttpOperation: 	... 14 more
,08-02 10:49:06.843  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:49:06.843  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:49:06.843  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:49:06.843  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:49:06.860  3494  4262 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 10:49:06.860  3494  4262 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at hec.a(PG:42)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at hee.a(PG:102)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at czr.a(PG:65)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at kka.a(PG:108)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at czp.a(PG:19176)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:49:06.860  3494  4262 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	... 15 more
08-02 10:49:06.860  3494  4262 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at fal.a(PG:38)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:49:06.860  3494  4262 E HttpOperation: 	... 17 more
,08-02 10:49:06.861  3494  4262 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 10:49:06.861  3494  4262 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at hec.a(PG:42)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at hee.a(PG:102)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at czr.a(PG:65)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at kka.a(PG:108)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	... 15 more
08-02 10:49:06.861  3494  4262 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at fal.a(PG:38)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 10:49:06.861  3494  4262 E ExperimentLoader: 	... 17 more
,08-02 10:49:06.998   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 741601, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:49:37.100  3146  4265 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 10:49:37.135  3146  4266 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 10:49:37.147  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:49:37.149  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:49:37.185  1513  2014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:49:37.185  1513  2014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:49:37.186  1513  2014 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:49:37.186  1513  2014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:49:37.221  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:49:37.226  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:49:37.270  1513  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:49:37.270  1513  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:49:37.271  1513  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:49:37.271  1513  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:49:37.301  3146  4266 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-02 10:49:37.303  3146  4265 E BooksSync: Soft error
08-02 10:49:37.303  3146  4265 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:49:37.303  3146  4265 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-02 10:49:37.303  3146  4265 E BooksSync: Sync error
08-02 10:49:37.303  3146  4265 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:49:37.303  3146  4265 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:49:37.306  3146  4265 I BooksSync: Finished books sync
,08-02 10:49:37.313   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 766393, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:50:34.339  3046  4269 V KeepSync: Connecting to GoogleApiClient
,08-02 10:50:34.341   871   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 10:50:34.422  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:50:34.427  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:50:34.462  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-02 10:50:34.462  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-02 10:50:34.462  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:50:34.462  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:50:34.482  1832  4270 V BaseAuthAsyncOperation: access token request failed
08-02 10:50:34.483  3046  4269 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 10:50:34.520  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-02 10:50:34.520  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-02 10:50:34.520  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:50:34.520  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:50:34.537  3046  4269 E KeepSync: IOException
08-02 10:50:34.537  3046  4269 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 10:50:34.537  3046  4269 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:50:34.537  3046  4269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 10:50:34.537  3046  4269 E KeepSync: 	... 10 more
08-02 10:50:34.537  3046  4269 W KeepSync: Sync result 2
,08-02 10:50:34.551   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 829447, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:53:18.584  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:53:18.589  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:53:18.653  1513  2014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 10:53:18.654  1513  2014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:53:18.654  1513  2014 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:53:18.654  1513  2014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:53:18.684  3494  4280 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 10:53:18.684  3494  4280 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at blb.a(PG:3937)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at czp.a(PG:18188)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:53:18.684  3494  4280 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	... 12 more
08-02 10:53:18.684  3494  4280 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at fal.a(PG:38)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:53:18.684  3494  4280 E HttpOperation: 	... 14 more
,08-02 10:53:18.770  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-02 10:53:18.770  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 10:53:18.770  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 10:53:18.770  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:53:18.797  3494  4280 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 10:53:18.797  3494  4280 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jdm.a(PG:82)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jcs.o(PG:406)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jcn.a(PG:1379)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jcs.i(PG:143)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at hec.a(PG:42)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at hee.a(PG:102)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at czr.a(PG:65)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at kka.a(PG:108)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at czp.a(PG:19176)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at czp.a(PG:9081)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at czq.run(PG:1686)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:53:18.797  3494  4280 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jdj.a(PG:4091)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jdj.a(PG:1125)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jdm.a(PG:77)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	... 15 more
08-02 10:53:18.797  3494  4280 E HttpOperation: Caused by: faj: BadAuthentication
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at fal.a(PG:38)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	at jdj.a(PG:4089)
08-02 10:53:18.797  3494  4280 E HttpOperation: 	... 17 more
,08-02 10:53:18.798  3494  4280 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 10:53:18.798  3494  4280 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at hec.a(PG:42)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at hee.a(PG:102)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at czr.a(PG:65)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at kka.a(PG:108)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	... 15 more
08-02 10:53:18.798  3494  4280 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at fal.a(PG:38)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 10:53:18.798  3494  4280 E ExperimentLoader: 	... 17 more
,08-02 10:53:18.965   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 993424, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:57:03.249   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,08-02 10:57:46.224  3146  4293 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 10:57:46.255  3146  4294 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 10:57:46.275  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:57:46.283  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:57:46.350  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 10:57:46.351  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:57:46.351  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:57:46.351  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:57:46.421  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:57:46.428  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:57:46.487  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-02 10:57:46.488  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 10:57:46.488  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:57:46.488  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:57:46.516  3146  4294 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-02 10:57:46.518  3146  4293 E BooksSync: Soft error
08-02 10:57:46.518  3146  4293 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:57:46.518  3146  4293 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:57:46.519  3146  4293 E BooksSync: Sync error
08-02 10:57:46.519  3146  4293 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 10:57:46.519  3146  4293 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 10:57:46.519  3146  4293 I BooksSync: Finished books sync
,08-02 10:57:46.532   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1261380, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 10:58:47.544  3046  4298 V KeepSync: Connecting to GoogleApiClient
,08-02 10:58:47.545   871  3694 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 10:58:47.619  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:58:47.624  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 10:58:47.684  1513  2014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-02 10:58:47.685  1513  2014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-02 10:58:47.685  1513  2014 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:58:47.685  1513  2014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:58:47.723  1832  4299 V BaseAuthAsyncOperation: access token request failed
,08-02 10:58:47.725  3046  4298 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 10:58:47.817  1513  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-02 10:58:47.817  1513  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-02 10:58:47.817  1513  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 10:58:47.818  1513  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 10:58:47.852  3046  4298 E KeepSync: IOException
08-02 10:58:47.852  3046  4298 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 10:58:47.852  3046  4298 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 10:58:47.852  3046  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 10:58:47.852  3046  4298 E KeepSync: 	... 10 more
,08-02 10:58:47.852  3046  4298 W KeepSync: Sync result 2
,08-02 10:58:47.865   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 1322522, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-02 11:01:41.691  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 11:01:41.694  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 11:01:41.737  1513  2014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 11:01:41.737  1513  2014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 11:01:41.737  1513  2014 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 11:01:41.737  1513  2014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 11:01:41.756  3494  4308 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 11:01:41.756  3494  4308 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jdm.a(PG:82)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jcs.o(PG:406)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jcn.a(PG:1379)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jcs.i(PG:143)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at blb.a(PG:3937)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at czp.a(PG:18188)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at czp.a(PG:9081)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at czq.run(PG:1686)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 11:01:41.756  3494  4308 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jdj.a(PG:4091)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jdj.a(PG:1125)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jdm.a(PG:77)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	... 12 more
08-02 11:01:41.756  3494  4308 E HttpOperation: Caused by: faj: BadAuthentication
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at fal.a(PG:38)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	at jdj.a(PG:4089)
08-02 11:01:41.756  3494  4308 E HttpOperation: 	... 14 more
,08-02 11:01:41.830  1513  1891 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 11:01:41.831  1513  1891 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 11:01:41.831  1513  1891 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 11:01:41.831  1513  1891 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 11:01:41.850  3494  4308 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 11:01:41.850  3494  4308 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jdm.a(PG:82)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jcs.o(PG:406)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jcn.a(PG:1379)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jcs.i(PG:143)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at hec.a(PG:42)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at hee.a(PG:102)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at czr.a(PG:65)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at kka.a(PG:108)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at czp.a(PG:19176)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at czp.a(PG:9081)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at czq.run(PG:1686)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 11:01:41.850  3494  4308 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jdj.a(PG:4091)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jdj.a(PG:1125)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jdm.a(PG:77)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	... 15 more
08-02 11:01:41.850  3494  4308 E HttpOperation: Caused by: faj: BadAuthentication
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at fal.a(PG:38)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	at jdj.a(PG:4089)
08-02 11:01:41.850  3494  4308 E HttpOperation: 	... 17 more
08-02 11:01:41.850  3494  4308 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 11:01:41.850  3494  4308 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at hec.a(PG:42)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at hee.a(PG:102)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at czr.a(PG:65)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at kka.a(PG:108)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	... 15 more
08-02 11:01:41.850  3494  4308 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at fal.a(PG:38)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 11:01:41.850  3494  4308 E ExperimentLoader: 	... 17 more
,08-02 11:01:42.016   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1496552, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),08-02 11:04:25.249  4316  4316 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-02 11:04:25.254  4316  4316 D AndroidRuntime: CheckJNI is OFF
08-02 11:04:25.290  4316  4316 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-02 11:04:25.332  4316  4316 I Radio-JNI: register_android_hardware_Radio DONE
08-02 11:04:25.354  4316  4316 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-02 11:04:25.367   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-02 11:04:25.368   871   884 I ActivityManager: Killing 3760:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-02 11:04:25.480   871  1302 D WifiService: Client connection lost with reason: 4
08-02 11:04:25.481   871  3694 D GraphicsStats: Buffer count: 2
08-02 11:04:25.481   871  1771 I WindowState: WIN DEATH: Window{9d69810 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-02 11:04:25.497   871   894 W PackageSettings: Skipping PackageSetting{567839e com.example.hello/10273} due to missing metadata
08-02 11:04:25.526   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-02 11:04:25.526   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-02 11:04:25.527   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-02 11:04:25.527   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-02 11:04:25.527   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:25.527   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.527   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:25.527   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-02 11:04:25.527   871   884 I ActivityManager:   Force finishing activity ActivityRecord{efafde5 u0 com.test.thalitest/.MainActivity t2}
08-02 11:04:25.529   871   894 I art     : Starting a blocking GC Explicit
08-02 11:04:25.541   871  1691 W ActivityManager: Spurious death for ProcessRecord{9d4187a 0:com.test.thalitest/u0a0}, curProc for 3760: null
08-02 11:04:25.588   871   894 I art     : Explicit concurrent mark sweep GC freed 48491(2MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 29MB/43MB, paused 775us total 58.046ms
08-02 11:04:25.612   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-02 11:04:25.615  4316  4316 I art     : System.exit called, status: 0
08-02 11:04:25.615  4316  4316 I AndroidRuntime: VM exiting with result code 0.
08-02 11:04:25.622   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-02 11:04:25.630   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-02 11:04:25.633  4093  4093 D BluetoothMapAppObserver: onReceive
08-02 11:04:25.633  4093  4093 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-02 11:04:25.637   871  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-02 11:04:25.639  1844  2016 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-02 11:04:25.644  3582  3582 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-02 11:04:25.645  1648  1648 I Keyboard.Facilitator: resetDictionaries() : en_US
08-02 11:04:25.669   871   881 I ActivityManager: Start proc 4332:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-02 11:04:25.670  1713  1713 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-02 11:04:25.688  1648  4331 I Keyboard.Facilitator.DecoderInitializer: run()
08-02 11:04:25.691  1648  4331 I Decoder : createOrResetDecoder
08-02 11:04:25.723   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-02 11:04:25.728  4332  4332 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-02 11:04:25.733  1513  1513 I ConfigService: onCreate
08-02 11:04:25.740  1513  4346 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-02 11:04:25.750   871  1732 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3760 uid 10000
08-02 11:04:25.750  1648  1648 I Keyboard.Facilitator: onFinishInput()
08-02 11:04:25.765  1648  4331 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-02 11:04:25.770   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-02 11:04:25.770   871   883 E PackageManager: Failed to write settings, restoring backup
08-02 11:04:25.770   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-02 11:04:25.770   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-02 11:04:25.770   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-02 11:04:25.770   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-02 11:04:25.770   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-02 11:04:25.770   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:25.770   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.770   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:25.774   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-02 11:04:25.774   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-02 11:04:25.774   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 11:04:25.774   871   884 E DropBoxManagerService: 	... 13 more
08-02 11:04:25.796  1648  4331 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-02 11:04:25.798  4332  4332 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-02 11:04:25.801  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-02 11:04:25.801  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-02 11:04:25.809  1733  1828 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-02 11:04:25.811  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-02 11:04:25.811  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-02 11:04:25.812  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-02 11:04:25.813  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-02 11:04:25.814  1648  4331 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-02 11:04:25.814  1648  4331 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-02 11:04:25.814  1648  4331 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-02 11:04:25.815  1648  4331 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-02 11:04:25.815  1648  4331 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-02 11:04:25.815  1648  4331 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.819  4332  4348 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.819  4332  4348 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:25.829   871  3143 I ActivityManager: Start proc 4351:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-02 11:04:25.829  1733  1828 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-02 11:04:25.829  1733  1828 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1733
08-02 11:04:25.829  1733  1828 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.829  1733  1828 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:25.832   871  1715 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-02 11:04:25.832   871  4356 E DropBoxManagerService: Can't write: system_app_crash
08-02 11:04:25.832   871  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 11:04:25.832   871  4356 E DropBoxManagerService: 	... 5 more
08-02 11:04:25.835  1733  1828 I Process : Sending signal. PID: 1733 SIG: 9
08-02 11:04:25.854  4332  4364 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-02 11:04:25.855   871  1698 I ActivityManager: Start proc 4365:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-02 11:04:25.888  4365  4365 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-02 11:04:25.896   871  1771 D GraphicsStats: Buffer count: 1
08-02 11:04:25.896   871  1691 I WindowState: WIN DEATH: Window{b479104 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-02 11:04:25.902   871  1771 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1733) has died
08-02 11:04:25.902   871  1771 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-02 11:04:25.903   871  1771 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-02 11:04:25.923  4332  4348 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-02 11:04:25.929   871   884 I ActivityManager: Start proc 4380:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-02 11:04:25.952  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-02 11:04:25.953  1513  1513 D AndroidRuntime: Shutting down VM
08-02 11:04:25.954  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
08-02 11:04:25.954  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
08-02 11:04:25.954  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-02 11:04:25.954  1513  1513 E AndroidRuntime: 	... 8 more
08-02 11:04:25.962  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
08-02 11:04:25.964   871  4394 E DropBoxManagerService: Can't write: system_app_crash
08-02 11:04:25.964   871  4394 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 11:04:25.964   871  4394 E DropBoxManagerService: 	... 5 more
08-02 11:04:25.980   871  1715 I ActivityManager: Killing 1798:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 11:04:25.983  4380  4380 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 11:04:25.984  4380  4380 D AndroidRuntime: Shutting down VM
08-02 11:04:25.995   871  1302 D WifiService: Client connection lost with reason: 4
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:26.002  4332  4364 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-02 11:04:26.003  4332  4364 E AndroidRuntime: Process: android.process.acore, PID: 4332
08-02 11:04:26.003  4332  4364 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:26.003  4332  4364 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 11:04:26.003  4332  4348 I Process : Sending signal. PID: 4332 SIG: 9
08-02 11:04:26.034   871  4396 E DropBoxManagerService: Can't write: system_app_crash
08-02 11:04:26.034   871  4396 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 11:04:26.034   871  4396 E DropBoxManagerService: 	... 5 more
08-02 11:04:26.037  4380  4380 E AndroidRuntime: FATAL EXCEPTION: main
08-02 11:04:26.037  4380  4380 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4380
08-02 11:04:26.037  4380  4380 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-02 11:04:26.037  4380  4380 E AndroidRuntime: 	... 10 more
08-02 11:04:26.039   871  1730 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-02 11:04:26.040  4380  4380 I Process : Sending signal. PID: 4380 SIG: 9
08-02 11:04:26.041   871  4397 E DropBoxManagerService: Can't write: system_app_crash
08-02 11:04:26.041   871  4397 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 11:04:26.041   871  4397 E DropBoxManagerService: 	... 5 more
08-02 11:04:26.043   871  1302 D WifiService: Client connection lost with reason: 4
08-02 11:04:26.046  1832  4395 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@8536929
08-02 11:04:26.052   871  3143 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
08-02 11:04:26.053   871  3143 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-02 11:04:26.053   871  3143 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-02 11:04:26.053   871  3143 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-02 11:04:26.054   278   278 E lowmemorykiller: Error opening /proc/4332/oom_score_adj; errno=2
08-02 11:04:26.056   871   881 I ActivityManager: Process android.process.acore (pid 4332) has died
08-02 11:04:26.056   871   881 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30997ms
08-02 11:04:26.064  1832  1832 W RocketImpressions: ClearcutLogger connection suspended: 1
08-02 11:04:26.072   871  1732 I ActivityManager: Start proc 4398:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-02 11:04:26.078   871   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4380) has died
08-02 11:04:26.079   871   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-02 11:04:26.094   871   884 I ActivityManager: Start proc 4411:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-02 11:04:26.122  4398  4398 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-02 11:04:26.129  4398  4398 I GservicesProvider: Gservices pushing to system: true; secure/global: true

```
