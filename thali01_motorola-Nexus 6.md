#### Test 80761374e9ed5ae_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-13 18:39:29.610   872  1841 D NetlinkSocketObserver: NeighborEvent{elapsedMs=314292, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-13 18:39:30.133  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-13 18:39:30.135  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-13 18:39:30.197  1530  2978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-13 18:39:30.197  1530  2978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-13 18:39:30.197  1530  2978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-13 18:39:30.197  1530  2978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-13 18:39:30.225  3589  3975 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-13 18:39:30.225  3589  3975 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jdm.a(PG:82)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jcs.o(PG:406)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jcn.a(PG:1379)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jcs.i(PG:143)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at blb.a(PG:3937)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at czp.a(PG:18188)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at czp.a(PG:9081)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at czq.run(PG:1686)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-13 18:39:30.225  3589  3975 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jdj.a(PG:4091)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jdj.a(PG:1125)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jdm.a(PG:77)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	... 12 more
08-13 18:39:30.225  3589  3975 E HttpOperation: Caused by: faj: BadAuthentication
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at fal.a(PG:38)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	at jdj.a(PG:4089)
08-13 18:39:30.225  3589  3975 E HttpOperation: 	... 14 more
08-13 18:39:30.306  1530  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-13 18:39:30.307  1530  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-13 18:39:30.307  1530  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-13 18:39:30.307  1530  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-13 18:39:30.326  3589  3975 E HttpOperation: [getmobileexperiments] Unexpected exception
08-13 18:39:30.326  3589  3975 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jdm.a(PG:82)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jcs.o(PG:406)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jcn.a(PG:1379)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jcs.i(PG:143)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at hec.a(PG:42)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at hee.a(PG:102)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at czr.a(PG:65)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at kka.a(PG:108)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at czp.a(PG:19176)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at czp.a(PG:9081)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at czq.run(PG:1686)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-13 18:39:30.326  3589  3975 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jdj.a(PG:4091)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jdj.a(PG:1125)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jdm.a(PG:77)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	... 15 more
08-13 18:39:30.326  3589  3975 E HttpOperation: Caused by: faj: BadAuthentication
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at fal.a(PG:38)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	at jdj.a(PG:4089)
08-13 18:39:30.326  3589  3975 E HttpOperation: 	... 17 more
08-13 18:39:30.326  3589  3975 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-13 18:39:30.326  3589  3975 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jdm.a(PG:82)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jcs.o(PG:406)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jcn.a(PG:1379)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jcs.i(PG:143)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at hec.a(PG:42)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at hee.a(PG:102)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at czr.a(PG:65)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at kka.a(PG:108)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at czp.a(PG:19176)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at czp.a(PG:9081)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at czq.run(PG:1686)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jdj.a(PG:4091)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jdj.a(PG:1125)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jdm.a(PG:77)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	... 15 more
08-13 18:39:30.326  3589  3975 E ExperimentLoader: Caused by: faj: BadAuthentication
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at fal.a(PG:38)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	at jdj.a(PG:4089)
08-13 18:39:30.326  3589  3975 E ExperimentLoader: 	... 17 more
08-13 18:39:30.446   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 288594, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
08-13 18:39:30.450  3972  3972 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-13 18:39:30.455  3972  3972 D AndroidRuntime: CheckJNI is OFF
08-13 18:39:30.491  3972  3972 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-13 18:39:30.531  3972  3972 I Radio-JNI: register_android_hardware_Radio DONE
08-13 18:39:30.550  3972  3972 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-13 18:39:30.558   872  2122 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-13 18:39:30.640   872  2122 I ActivityManager: Start proc 3984:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-13 18:39:30.650  3972  3972 D AndroidRuntime: Shutting down VM
08-13 18:39:30.795  3984  3984 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-13 18:39:30.820  3984  3984 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-13 18:39:30.827  3984  3984 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5507-5509)
08-13 18:39:30.827  3984  3984 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-13 18:39:30.844  3984  3984 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fec7d8f}
08-13 18:39:30.845  3984  3984 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-13 18:39:30.845  3984  3984 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-13 18:39:30.853  3984  3984 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-13 18:39:30.855  3984  3984 E SysUtils: ApplicationContext is null in ApplicationStatus
08-13 18:39:30.875  3984  3984 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-13 18:39:30.885  3984  3984 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-13 18:39:30.885  3984  3984 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-13 18:39:30.885  3984  3984 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-13 18:39:30.885  3984  3984 I Adreno  : Build Date                       : 10/20/15
08-13 18:39:30.885  3984  3984 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-13 18:39:30.885  3984  3984 I Adreno  : Local Branch                     : M14
08-13 18:39:30.885  3984  3984 I Adreno  : Remote Branch                    : 
08-13 18:39:30.885  3984  3984 I Adreno  : Remote Branch                    : 
08-13 18:39:30.885  3984  3984 I Adreno  : Reconstruct Branch               : 
,08-13 18:39:30.943   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f905af2:true
,08-13 18:39:30.994  3984  3984 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-13 18:39:31.010  3984  3984 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-13 18:39:31.072  3984  4022 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-13 18:39:31.086  3984  4009 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-13 18:39:31.123  3984  4022 I OpenGLRenderer: Initialized EGL, version 1.4
,08-13 18:39:31.146  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-13 18:39:31.232   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +502ms (total +626ms)
,08-13 18:39:31.253  3984  3984 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3984
,08-13 18:39:31.469  3984  3984 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-13 18:39:31.617  3984  4023 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1657837264
,08-13 18:39:31.623  3984  4023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-13 18:39:31.623  3984  4023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-13 18:39:31.623  3984  4023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-13 18:39:31.623  3984  4023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-13 18:39:31.623  3984  4023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-13 18:39:31.623  3984  4023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca51512 added. We now have 1 listener(s)
,08-13 18:39:31.628  3984  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-13 18:39:31.629  3984  4023 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-13 18:39:31.630  3984  4023 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-13 18:39:31.630  3984  4023 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-13 18:39:31.634  3984  4023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff4599 added. We now have 1 listener(s)
,08-13 18:39:31.634  3984  4023 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:39:31.640   872  1317 D WifiService: New client listening to asynchronous messages
,08-13 18:39:31.641  3984  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-13 18:39:31.642  3984  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-13 18:39:31.642  3984  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-13 18:39:31.642  3984  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-13 18:39:31.642  3984  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-13 18:39:31.646  3984  4023 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:39:31.647  3984  4023 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-13 18:39:31.652  3984  4023 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:39:31.652  3984  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:39:31.652  3984  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-13 18:39:31.652  3984  4023 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:39:31.653  3984  4023 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-13 18:39:31.658  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:31.661  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:31.680  3984  3984 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-13 18:39:32.765  3984  4031 W jxcore-log: Initializing JXcore engine
,08-13 18:39:32.765  3984  4031 W jxcore-log: JXcore engine is ready
,08-13 18:39:32.803  4031  4031 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-13 18:39:32.803  4031  4031 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11901]" dev="sockfs" ino=11901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-13 18:39:32.803  4031  4031 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-13 18:39:32.803  4031  4031 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27408]" dev="sockfs" ino=27408 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-13 18:39:32.818  3984  4031 W jxcore-log: Starting JXcore engine
,08-13 18:39:32.899  3984  4031 W jxcore-log: Platform android
08-13 18:39:32.899  3984  4031 W jxcore-log: 
,08-13 18:39:32.900  3984  4031 W jxcore-log: Process ARCH arm
08-13 18:39:32.900  3984  4031 W jxcore-log: 
,08-13 18:39:33.126  3984  4031 I jxcore-log: JXcore Cordova bridge is ready!
08-13 18:39:33.126  3984  4031 I jxcore-log: 
,08-13 18:39:33.127  3984  4031 W jxcore-log: JXcore engine is started
,08-13 18:39:33.139  3984  4023 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-13 18:39:33.144  3984  3984 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-13 18:39:42.128   872  1841 D NetlinkSocketObserver: NeighborEvent{elapsedMs=326810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-13 18:39:48.926  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-13 18:39:48.926  3984  4031 I jxcore-log: 
,08-13 18:39:48.928  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-13 18:39:48.928  3984  4031 I jxcore-log: 
,08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:39:48.939  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:39:48.944  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:39:48.946  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-13 18:39:48.946  3984  4031 I jxcore-log: 
,08-13 18:39:48.948  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-13 18:39:48.948  3984  4031 I jxcore-log: 
,08-13 18:39:49.286  3984  4031 I jxcore-log: Running unit tests
08-13 18:39:49.286  3984  4031 I jxcore-log: 
,08-13 18:39:49.287  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-13 18:39:49.287  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5cafb3 added. We now have 2 listener(s)
08-13 18:39:49.288  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-13 18:39:49.288  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:39:49.288  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:39:49.288  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:39:49.288  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b718970 added. We now have 2 listener(s)
08-13 18:39:49.288  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-13 18:39:49.289  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-13 18:39:49.291  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:39:49.310  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:39:49.314  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-13 18:39:49.314  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:39:49.315  3984  4031 D ExecuteNativeTests: Running unit tests
,08-13 18:39:49.322  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:49.330  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:54.377  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-13 18:39:54.378  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e added. We now have 3 listener(s)
,08-13 18:39:54.385  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-13 18:39:54.385  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:39:54.386  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:39:54.386  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:39:54.387  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff added. We now have 3 listener(s)
,08-13 18:39:54.387  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-13 18:39:54.389  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-13 18:39:54.404  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:39:54.417  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:39:54.424  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:39:54.425  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:39:54.431  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:54.435  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-13 18:39:54.438  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-13 18:39:54.438  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-13 18:39:54.439  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-13 18:39:54.439  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:54.446  3984  4031 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-13 18:39:54.448  3984  4031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-13 18:39:54.448  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-13 18:39:54.448  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-13 18:39:54.449  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-13 18:39:54.449  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-13 18:39:54.450  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:39:54.452  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:39:54.452  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:39:54.454  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:39:54.455  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:39:54.455  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:39:54.455  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-13 18:39:54.455  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e removed from the list
08-13 18:39:54.455  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:39:54.456  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff removed from the list
08-13 18:39:54.456  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
,08-13 18:39:54.456  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.457  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.457  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.458  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:39:54.458  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:39:54.458  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:39:54.458  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:39:54.460  3984  4031 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-13 18:39:54.461  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:39:54.461  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:39:54.461  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:39:54.461  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:39:54.461  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.461  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.462  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:39:54.462  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:39:54.462  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:39:54.462  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:39:54.462  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.462  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.462  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.462  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.463  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:39:54.463  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:39:54.464  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:39:54.464  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:39:54.471  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-13 18:39:54.471  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-13 18:39:54.471  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-13 18:39:54.471  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-13 18:39:54.472  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-13 18:39:54.472  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-13 18:39:54.472  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-13 18:39:54.472  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-13 18:39:54.472  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-13 18:39:54.472  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-13 18:39:54.473  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-13 18:39:54.474  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-13 18:39:54.474  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:39:54.475  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:39:54.475  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:39:54.475  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:39:54.475  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.475  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.475  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:39:54.475  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:39:54.475  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:39:54.475  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:39:54.476  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.476  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:39:54.476  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:54.476  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:39:54.478  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:39:54.478  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:39:54.478  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:39:54.479  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:39:54.481  3984  4031 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-13 18:39:54.484  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:39:54.495  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:39:54.500  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:39:54.501  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-13 18:39:54.501  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:39:54.502  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-13 18:39:54.502  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-13 18:39:54.502  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:39:54.503  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-13 18:39:54.503  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:54.507  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:39:54.511  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-13 18:39:54.511  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-13 18:39:54.519  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-13 18:39:54.521  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-13 18:39:54.522  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-13 18:39:54.525  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-13 18:39:54.530  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-13 18:39:54.531  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-13 18:39:54.531  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-13 18:39:54.532  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-13 18:39:54.533  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:39:54.542  2700  2870 D BtGatt.GattService: registerClient() - UUID=dc005905-fc2b-453e-ba5d-65db1470f526
,08-13 18:39:54.543  2700  2754 D BtGatt.GattService: onClientRegistered() - UUID=dc005905-fc2b-453e-ba5d-65db1470f526, clientIf=5
08-13 18:39:54.546  3984  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-13 18:39:54.547  2700  2882 D BtGatt.GattService: start scan with filters
,08-13 18:39:54.552  2700  2757 D BtGatt.ScanManager: handling starting scan
,08-13 18:39:54.552  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-13 18:39:54.553  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-13 18:39:54.553  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-13 18:39:54.554  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-13 18:39:54.555  2700  2757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:39:54.560  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-13 18:39:54.561  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-13 18:39:54.563  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-13 18:39:54.564  2700  2754 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-13 18:39:54.564  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:39:54.565  2700  2757 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-13 18:39:54.568  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-13 18:39:54.573  2700  2754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-13 18:39:54.573  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:39:54.574  2700  2757 D BtGatt.ScanManager: Starting BLE batch scan
08-13 18:39:54.574  2700  2757 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-13 18:39:54.575  3984  4031 I io.jxcore.node.ConnectionHelper: start: OK
,08-13 18:39:54.601  2700  2754 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-13 18:39:54.602  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:39:54.620  2700  2754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-13 18:39:54.620  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:39:55.064  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-13 18:39:55.065  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-13 18:39:55.065  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:39:56.126  2700  2700 D BtGatt.ScanManager: awakened up at time 340808
,08-13 18:39:56.130  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:39:56.178  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-13 18:39:56.178  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:39:56.178  2700  2754 D BtGatt.GattService: current time is 340860895447
,08-13 18:39:56.178  2700  2754 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-13 18:39:56.180  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-13 18:39:56.181  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-13 18:39:56.181  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-13 18:39:56.182  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-13 18:39:57.176  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:39:57.199  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:39:57.206  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:39:57.290  1530  1546 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-13 18:39:57.291  1530  1546 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-13 18:39:57.291  1530  1546 I GLSUser : [GLSUser] Extracting token using key: Auth
08-13 18:39:57.292  1530  1546 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-13 18:39:57.341  1530  1546 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-13 18:39:57.341  1530  1546 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-13 18:39:57.341  1530  1546 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-13 18:39:57.341  1530  1546 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-13 18:39:57.341  1530  1546 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-13 18:39:57.341  1530  1546 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-13 18:39:57.341  1530  1546 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-13 18:39:57.360  3549  3581 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-13 18:39:57.360  3549  3581 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-13 18:39:57.360  3549  3581 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-13 18:39:57.360  3549  3581 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-13 18:39:57.360  3549  3581 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-13 18:39:57.360  3549  3581 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-13 18:39:57.360  3549  3581 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-13 18:39:57.679  2700  2700 D BtGatt.ScanManager: awakened up at time 342362
,08-13 18:39:57.681  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:39:57.705  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-13 18:39:57.705  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:39:57.706  2700  2754 D BtGatt.GattService: current time is 342388324951
,08-13 18:39:57.707  2700  2754 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-13 18:39:57.708  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-13 18:39:57.710  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-13 18:39:59.210  2700  2700 D BtGatt.ScanManager: awakened up at time 343892
,08-13 18:39:59.212  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:39:59.225  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-13 18:39:59.226  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:39:59.585  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:39:59.585  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-13 18:39:59.586  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-13 18:39:59.586  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:39:59.586  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-13 18:39:59.586  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-13 18:39:59.587  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-13 18:39:59.587  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-13 18:39:59.587  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-13 18:39:59.590  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-13 18:39:59.591  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-13 18:39:59.594  3984  4031 D BluetoothAdapter: STATE_ON
08-13 18:39:59.596  2700  2870 D BtGatt.GattService: stopScan() - queue size =1
08-13 18:39:59.599  2700  2882 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-13 18:39:59.601  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-13 18:39:59.601  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-13 18:39:59.601  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-13 18:39:59.602  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-13 18:39:59.602  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-13 18:39:59.606  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:39:59.608  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-13 18:39:59.608  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-13 18:39:59.609  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-13 18:39:59.610  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-13 18:39:59.613  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-13 18:39:59.614  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:39:59.614  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:39:59.614  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-13 18:39:59.614  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:39:59.614  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:39:59.614  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:39:59.615  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-13 18:39:59.615  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:39:59.615  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:39:59.615  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:39:59.618  2700  2754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-13 18:39:59.619  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:39:59.619  2700  2757 D BtGatt.ScanManager: stopping BLe Batch
,08-13 18:39:59.627  2700  2754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-13 18:39:59.628  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:39:59.628  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:39:59.636  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-13 18:39:59.636  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:00.116  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-13 18:40:04.617  3984  4031 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-13 18:40:04.625  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:04.639  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:40:04.646  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:40:04.647  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:40:04.648  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:40:04.649  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-13 18:40:04.650  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-13 18:40:04.650  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:40:04.650  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-13 18:40:04.657  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:04.662  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-13 18:40:04.663  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-13 18:40:04.667  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:04.675  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-13 18:40:04.676  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-13 18:40:04.677  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-13 18:40:04.680  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-13 18:40:04.680  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-13 18:40:04.680  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-13 18:40:04.682  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:40:04.685  2700  2711 D BtGatt.GattService: registerClient() - UUID=d7b8afb6-8c5d-4813-b8a2-b3f2c0eb0bd8
,08-13 18:40:04.685  2700  2754 D BtGatt.GattService: onClientRegistered() - UUID=d7b8afb6-8c5d-4813-b8a2-b3f2c0eb0bd8, clientIf=5
08-13 18:40:04.686  3984  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-13 18:40:04.687  2700  2870 D BtGatt.GattService: start scan with filters
,08-13 18:40:04.690  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-13 18:40:04.690  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-13 18:40:04.690  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-13 18:40:04.690  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-13 18:40:04.691  2700  2757 D BtGatt.ScanManager: handling starting scan
,08-13 18:40:04.694  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-13 18:40:04.694  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-13 18:40:04.694  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-13 18:40:04.695  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-13 18:40:04.700  2700  2754 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-13 18:40:04.700  3984  4031 I io.jxcore.node.ConnectionHelper: start: OK
08-13 18:40:04.700  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.700  2700  2757 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-13 18:40:04.702  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:40:04.702  3984  4031 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-13 18:40:04.702  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:04.702  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-13 18:40:04.703  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:04.703  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-13 18:40:04.703  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-13 18:40:04.703  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-13 18:40:04.703  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-13 18:40:04.703  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-13 18:40:04.703  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-13 18:40:04.703  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-13 18:40:04.704  3984  4031 D BluetoothAdapter: STATE_ON
08-13 18:40:04.705  2700  2711 D BtGatt.GattService: stopScan() - queue size =1
08-13 18:40:04.705  2700  2870 D BtGatt.GattService: unregisterClient() - clientIf=5
08-13 18:40:04.706  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-13 18:40:04.706  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-13 18:40:04.706  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-13 18:40:04.706  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-13 18:40:04.706  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-13 18:40:04.708  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-13 18:40:04.708  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-13 18:40:04.708  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-13 18:40:04.708  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-13 18:40:04.708  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:40:04.709  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:04.709  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:04.710  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:40:04.710  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:04.710  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:04.710  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:40:04.710  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:04.710  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:04.710  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:04.710  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:40:04.711  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:40:04.711  2700  2754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-13 18:40:04.711  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.712  2700  2757 D BtGatt.ScanManager: Starting BLE batch scan
08-13 18:40:04.712  2700  2757 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-13 18:40:04.712  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:04.712  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:04.713  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:04.713  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-13 18:40:04.713  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:04.713  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:04.714  3984  4031 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-13 18:40:04.716  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:04.720  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-13 18:40:04.722  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:40:04.722  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-13 18:40:04.723  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:40:04.723  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-13 18:40:04.723  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-13 18:40:04.723  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:40:04.723  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-13 18:40:04.723  2700  2754 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-13 18:40:04.724  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.727  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:04.729  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:04.730  2700  2754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-13 18:40:04.730  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:04.733  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-13 18:40:04.733  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-13 18:40:04.737  2700  2754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-13 18:40:04.737  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.737  2700  2757 D BtGatt.ScanManager: stopping BLe Batch
08-13 18:40:04.738  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-13 18:40:04.739  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-13 18:40:04.739  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-13 18:40:04.742  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-13 18:40:04.742  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-13 18:40:04.742  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-13 18:40:04.743  2700  2754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-13 18:40:04.743  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.743  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:40:04.743  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:40:04.745  2700  2714 D BtGatt.GattService: registerClient() - UUID=56f8b546-d703-4bf6-bfa4-da5d57386b4d
,08-13 18:40:04.745  2700  2754 D BtGatt.GattService: onClientRegistered() - UUID=56f8b546-d703-4bf6-bfa4-da5d57386b4d, clientIf=5
08-13 18:40:04.746  3984  3994 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-13 18:40:04.746  2700  2882 D BtGatt.GattService: start scan with filters
,08-13 18:40:04.748  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-13 18:40:04.748  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.748  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-13 18:40:04.748  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-13 18:40:04.748  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-13 18:40:04.749  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-13 18:40:04.750  2700  2757 D BtGatt.ScanManager: handling starting scan
08-13 18:40:04.751  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-13 18:40:04.751  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-13 18:40:04.751  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-13 18:40:04.753  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-13 18:40:04.755  3984  4031 I io.jxcore.node.ConnectionHelper: start: OK
08-13 18:40:04.755  2700  2754 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-13 18:40:04.756  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.756  2700  2757 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-13 18:40:04.761  2700  2754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-13 18:40:04.761  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:04.761  2700  2757 D BtGatt.ScanManager: Starting BLE batch scan
08-13 18:40:04.761  2700  2757 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-13 18:40:04.769  2700  2754 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-13 18:40:04.769  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:04.774  2700  2754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-13 18:40:04.774  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:05.252  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-13 18:40:05.253  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:40:05.253  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:40:06.282  2700  2700 D BtGatt.ScanManager: awakened up at time 350965
,08-13 18:40:06.291  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:40:06.338  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-13 18:40:06.338  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:06.338  2700  2754 D BtGatt.GattService: current time is 351020969035
08-13 18:40:06.338  2700  2754 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -90, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-13 18:40:06.339  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-13 18:40:06.339  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-13 18:40:06.339  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-13 18:40:06.339  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-13 18:40:06.340  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-13 18:40:07.844  2700  2700 D BtGatt.ScanManager: awakened up at time 352527
,08-13 18:40:07.847  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:40:07.892  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-13 18:40:07.892  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:07.893  2700  2754 D BtGatt.GattService: current time is 352575340249
08-13 18:40:07.893  2700  2754 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -91, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -91, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-13 18:40:07.894  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-13 18:40:07.895  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-13 18:40:07.896  2700  2754 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-13 18:40:09.395  2700  2700 D BtGatt.ScanManager: awakened up at time 354077
,08-13 18:40:09.399  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:40:09.411  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-13 18:40:09.411  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:09.756  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:40:09.756  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-13 18:40:09.757  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-13 18:40:09.757  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:09.758  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-13 18:40:09.758  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-13 18:40:09.758  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-13 18:40:09.759  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-13 18:40:09.759  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-13 18:40:09.760  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-13 18:40:09.760  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-13 18:40:09.763  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:40:09.766  2700  2714 D BtGatt.GattService: stopScan() - queue size =1
08-13 18:40:09.773  2700  2882 D BtGatt.GattService: unregisterClient() - clientIf=5
08-13 18:40:09.775  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-13 18:40:09.775  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-13 18:40:09.775  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-13 18:40:09.775  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-13 18:40:09.775  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-13 18:40:09.777  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:40:09.777  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-13 18:40:09.778  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-13 18:40:09.778  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-13 18:40:09.779  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-13 18:40:09.782  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:40:09.782  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:40:09.782  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-13 18:40:09.787  2700  2754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-13 18:40:09.787  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:09.788  2700  2757 D BtGatt.ScanManager: stopping BLe Batch
,08-13 18:40:09.798  2700  2754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-13 18:40:09.798  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:40:09.799  2700  2757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:40:09.807  2700  2754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-13 18:40:09.808  2700  2754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:40:10.283  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-13 18:40:10.284  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:10.284  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:40:14.783  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:40:14.784  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.784  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-13 18:40:14.785  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.785  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.785  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-13 18:40:14.785  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.786  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.786  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.786  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
,08-13 18:40:14.787  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.788  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.789  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.792  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:40:14.792  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.792  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.793  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.795  3984  4031 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-13 18:40:14.797  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:40:14.798  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.798  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-13 18:40:14.798  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.799  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.799  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.799  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.799  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.800  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.800  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.800  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.801  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:14.801  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.801  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.803  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.803  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.803  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:14.803  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:14.804  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-13 18:40:14.804  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:40:14.804  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.804  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.805  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-13 18:40:14.805  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.805  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.805  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.805  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.805  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:14.805  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.805  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.805  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.805  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.805  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.807  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:40:14.807  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.807  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.807  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.807  3984  4031 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-13 18:40:14.808  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:40:14.808  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.808  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.808  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.808  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.808  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.808  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
,08-13 18:40:14.808  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.808  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.809  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
,08-13 18:40:14.809  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.809  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:14.809  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.809  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.810  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.810  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.810  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.811  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.811  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-13 18:40:14.811  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:14.812  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.812  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.812  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.812  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.812  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.812  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.812  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.812  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.812  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.812  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.812  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.813  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:40:14.813  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.814  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.814  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.814  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.814  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.814  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-13 18:40:14.815  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-13 18:40:14.815  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-13 18:40:14.815  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-13 18:40:14.815  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-13 18:40:14.815  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-13 18:40:14.815  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-13 18:40:14.815  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-13 18:40:14.816  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-13 18:40:14.816  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:14.816  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.816  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.816  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.816  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.816  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.816  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.816  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.816  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.817  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.817  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.817  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.817  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.817  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.819  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.819  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.819  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.819  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.820  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-13 18:40:14.820  3984  4031 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-13 18:40:14.821  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-13 18:40:14.826  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-13 18:40:14.826  3984  4031 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-13 18:40:14.826  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-13 18:40:14.826  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-13 18:40:14.828  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-13 18:40:14.828  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-13 18:40:14.828  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-13 18:40:14.828  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-13 18:40:14.829  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-13 18:40:14.829  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-13 18:40:14.829  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-13 18:40:14.829  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-13 18:40:14.830  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-13 18:40:14.830  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-13 18:40:14.830  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-13 18:40:14.831  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-13 18:40:14.831  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-13 18:40:14.831  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-13 18:40:14.831  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-13 18:40:14.832  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-13 18:40:14.832  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-13 18:40:14.832  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-13 18:40:14.832  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-13 18:40:14.833  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-13 18:40:14.833  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-13 18:40:14.833  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-13 18:40:14.833  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-13 18:40:14.834  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-13 18:40:14.834  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-13 18:40:14.834  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-13 18:40:14.835  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-13 18:40:14.835  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-13 18:40:14.835  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-13 18:40:14.836  3984  4031 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-13 18:40:14.836  3984  4031 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-13 18:40:14.837  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-13 18:40:14.837  3984  4031 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-13 18:40:14.837  3984  4031 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-13 18:40:14.838  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-13 18:40:14.838  3984  4031 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-13 18:40:14.838  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-13 18:40:14.842  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-13 18:40:14.844  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-13 18:40:14.845  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-13 18:40:14.846  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-13 18:40:14.847  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-13 18:40:14.847  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-13 18:40:14.847  3984  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
08-13 18:40:14.848  3984  4031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-13 18:40:14.848  3984  4031 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-13 18:40:14.849  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:14.849  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.849  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.849  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.849  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.849  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.849  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-13 18:40:14.850  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
,08-13 18:40:14.850  3984  4038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-13 18:40:14.850  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.850  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.850  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.850  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.850  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.851  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.851  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.851  3984  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
08-13 18:40:14.851  3984  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 390)
08-13 18:40:14.851  3984  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 390)
08-13 18:40:14.852  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.852  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.852  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.852  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.853  3984  4031 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-13 18:40:14.853  3984  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
08-13 18:40:14.853  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:14.854  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.854  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.854  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.854  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.854  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.854  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.854  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.854  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.854  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.854  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.854  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.855  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.855  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.856  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.856  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.856  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.856  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.857  3984  4031 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-13 18:40:14.857  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:14.857  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.857  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.857  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.857  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.857  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.858  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.858  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.858  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.858  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.858  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.858  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.858  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.858  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.859  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.859  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.859  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.859  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.860  3984  4031 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-13 18:40:14.860  3984  4031 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-13 18:40:14.860  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-13 18:40:14.860  3984  4031 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-13 18:40:14.861  3984  4031 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-13 18:40:14.861  3984  4031 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-13 18:40:14.861  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-13 18:40:14.861  3984  4031 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-13 18:40:14.861  3984  4031 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-13 18:40:14.861  3984  4031 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-13 18:40:14.861  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-13 18:40:14.861  3984  4031 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-13 18:40:14.861  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:14.862  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:14.862  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:14.862  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.862  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.862  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.862  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.862  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.862  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.862  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.862  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.862  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.862  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.863  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.864  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:14.864  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:14.864  3984  4031 I org.thaliproject.p2p.btconnecto,rlib.DiscoveryManager: dispose
08-13 18:40:14.864  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.864  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:14.865  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.865  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:14.865  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:14.865  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:14.865  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:14.865  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:14.865  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:14.865  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:19.866  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:19.866  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.867  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:19.867  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:40:19.867  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.868  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:19.868  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:19.869  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-13 18:40:19.869  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:19.869  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-13 18:40:19.870  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:40:19.870  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.870  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
,08-13 18:40:19.871  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:19.871  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:19.871  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:19.871  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.872  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.872  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.872  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.876  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:19.877  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:19.877  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.877  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:19.884  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-13 18:40:19.885  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:40:19.886  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-13 18:40:19.887  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-13 18:40:19.887  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-13 18:40:19.888  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-13 18:40:19.888  3984  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-13 18:40:19.888  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-13 18:40:19.889  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:19.889  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-13 18:40:19.889  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-13 18:40:19.889  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-13 18:40:19.890  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-13 18:40:19.890  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-13 18:40:19.890  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:19.890  3984  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-13 18:40:19.890  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-13 18:40:19.890  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-13 18:40:19.890  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-13 18:40:19.890  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-13 18:40:19.890  3984  4040 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-13 18:40:19.891  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.891  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.892  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-13 18:40:19.893  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:40:19.893  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:40:19.893  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.893  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-13 18:40:19.893  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:19.893  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:19.893  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-13 18:40:19.893  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:19.893  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.893  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.894  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list,
08-13 18:40:19.894  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.894  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.894  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:19.894  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-13 18:40:19.894  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.894  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.894  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:19.895  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:19.896  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:19.896  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.896  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:19.896  3984  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-13 18:40:19.897  3984  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-13 18:40:19.898  3984  4031 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-13 18:40:19.898  3984  4031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-13 18:40:19.898  3984  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-13 18:40:19.898  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-13 18:40:19.899  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-13 18:40:19.899  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-13 18:40:19.899  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:19.899  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:19.899  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:19.899  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-13 18:40:19.899  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.899  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.900  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:19.900  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:19.900  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.900  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:19.900  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.900  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:19.901  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.901  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.902  3984  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-13 18:40:19.905  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:40:19.905  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:19.905  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:19.906  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.913  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:19.913  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:19.913  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-13 18:40:19.913  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:19.913  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.913  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-13 18:40:19.913  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
08-13 18:40:19.914  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.914  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:19.914  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:19.914  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.914  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.914  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:40:19.914  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.915  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:19.915  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-13 18:40:19.915  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.915  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.916  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:40:19.916  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:40:19.916  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:40:19.916  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:40:19.917  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.917  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.917  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd761e not in the list
,08-13 18:40:19.917  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.917  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
08-13 18:40:19.917  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:19.917  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.917  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.917  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:19.917  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:40:19.919  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:40:19.919  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:40:19.919  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:40:19.919  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1c9eff not in the list
,08-13 18:40:19.977  2700  2838 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-13 18:40:19.978  2700  2865 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-13 18:40:20.393  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-13 18:40:24.922  3984  4031 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-13 18:40:24.923  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-13 18:40:24.924  3984  4031 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-13 18:40:24.924  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-13 18:40:24.924  3984  4031 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-13 18:40:24.925  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-13 18:40:24.935  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-13 18:40:24.935  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-13 18:40:24.938  3984  4031 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-13 18:40:24.938  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-13 18:40:24.939  3984  4031 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-13 18:40:24.939  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-13 18:40:24.939  3984  4031 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-13 18:40:24.940  3984  4031 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-13 18:40:24.942  3984  4031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-13 18:40:24.943  3984  4031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-13 18:40:24.945  3984  4031 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-13 18:40:24.945  3984  4031 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-13 18:40:24.945  3984  4031 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-13 18:40:24.946  3984  4031 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-13 18:40:29.950  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:40:29.951  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56dfbc9 added. We now have 3 listener(s)
08-13 18:40:29.952  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:40:29.958  3984  4031 D BluetoothAdapter: enable(): BT is already enabled..!
08-13 18:40:29.959   872  1955 D WifiService: setWifiEnabled: true pid=3984, uid=10000
08-13 18:40:29.959   872  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-13 18:40:29.963  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:40:29.964  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@901a2ce added. We now have 4 listener(s)
,08-13 18:40:29.965  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:40:29.986  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:29.987  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@901a2ce removed from the list
08-13 18:40:29.987  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:29.988  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:29.988  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:29.991  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:40:29.991  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea145ef added. We now have 4 listener(s)
08-13 18:40:29.992  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:40:29.996  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:40:29.997  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea145ef removed from the list
,08-13 18:40:29.998  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:40:29.998  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:40:29.998  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:40:30.002  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-13 18:40:30.003  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d3c8fc added. We now have 4 listener(s)
,08-13 18:40:30.005  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:40:30.015   872  2120 D WifiService: setWifiEnabled: false pid=3984, uid=10000,
08-13 18:40:30.015   872  2120 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-13 18:40:30.020  2700  2750 D BluetoothAdapterState: Current state: ON, message: 23
08-13 18:40:30.020  2700  2750 D BluetoothAdapterProperties: Setting state to 13
,08-13 18:40:30.021  2700  2750 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-13 18:40:30.021  2700  2750 D BluetoothAdapterProperties: onBluetoothDisable()
08-13 18:40:30.022  2700  2750 I BluetoothAdapterState: Entering PendingCommandState
08-13 18:40:30.025  2700  2754 D BluetoothAdapterProperties: Scan Mode:20
08-13 18:40:30.025  2700  2750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-13 18:40:30.032  2700  2700 D HeadsetService: Received stop request...Stopping profile...
08-13 18:40:30.033  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:40:30.039  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:30.039  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:40:30.040  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.040  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:30.043  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:30.043  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:40:30.045  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:30.046  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:30.046  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-13 18:40:30.047  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:30.047  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:40:30.048  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:30.048  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:40:30.051  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:30.054  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:30.057  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:30.057   872   885 I ActivityManager: Start proc 4044:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-13 18:40:30.059  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-13 18:40:30.062   872   872 D BluetoothHeadset: Proxy object disconnected
08-13 18:40:30.062  1372  2027 D BluetoothHeadset: Proxy object disconnected
08-13 18:40:30.062  2700  2700 D BluetoothMapService: onReceive,
08-13 18:40:30.062  2700  2700 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-13 18:40:30.063  2700  2700 D BluetoothMapService: STATE_TURNING_OFF
,08-13 18:40:30.064  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:30.063  1925  2278 D BluetoothHeadset: Proxy object disconnected
,08-13 18:40:30.064   872   872 D BluetoothHeadset: Proxy object disconnected
,08-13 18:40:30.064   872   872 D BluetoothHeadset: Proxy object disconnected
,08-13 18:40:30.065   872  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-13 18:40:30.065   872  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-13 18:40:30.065   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-13 18:40:30.065   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-13 18:40:30.065  2700  2700 D A2dpService: Received stop request...Stopping profile...
08-13 18:40:30.066  2700  2873 D A2dpStateMachine: Exit Disconnected: -1
08-13 18:40:30.066  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:30.069   872   872 D BluetoothA2dp: Proxy object disconnected
08-13 18:40:30.070  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:30.072  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:30.072  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:30.072  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false,
08-13 18:40:30.072  2700  2700 D HidService: Received stop request...Stopping profile...
08-13 18:40:30.072  2700  2700 D HidService: Stopping Bluetooth HidService
,08-13 18:40:30.076   872  1316 E native  : do suspend true
08-13 18:40:30.078  2700  2700 D HealthService: Received stop request...Stopping profile...
,08-13 18:40:30.078  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-13 18:40:30.078  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-13 18:40:30.078  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-13 18:40:30.079  1372  1372 D HidProfile: Bluetooth service disconnected
,08-13 18:40:30.079  2700  2700 D PanService: Received stop request...Stopping profile...
08-13 18:40:30.080  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-13 18:40:30.080  1372  1372 D PanProfile: Bluetooth service disconnected
08-13 18:40:30.081  2700  2700 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-13 18:40:30.081  2700  2700 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-13 18:40:30.081  2700  2754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-13 18:40:30.081  2700  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:30.081  2700  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:30.081  2700  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:30.081  2700  2754 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-13 18:40:30.082  2700  2700 D BluetoothMapService: MAP Service closeService in
08-13 18:40:30.082  2700  2700 D BluetoothMapMasInstance0: MAP Service shutdown
,08-13 18:40:30.082  2700  2700 D ObexServerSockets0: shutdown(block = true)
08-13 18:40:30.082  2700  2700 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-13 18:40:30.082  2700  2886 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-13 18:40:30.083  2700  2885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-13 18:40:30.083  2700  2865 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-13 18:40:30.083  2700  2700 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-13 18:40:30.084  2700  2700 I BtOppRfcommListener: stopping Accept Thread
08-13 18:40:30.084  2700  3502 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-13 18:40:30.084  2700  3502 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-13 18:40:30.087   872  1845 D DhcpClient: Clearing IP address
08-13 18:40:30.088   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-13 18:40:30.089  2700  2700 D BluetoothMapService: Received stop request...Stopping profile...
08-13 18:40:30.089  2700  2700 D BluetoothMapService: stop()
08-13 18:40:30.090  2700  2700 D BluetoothMapAppObserver: deinitObservers()
,08-13 18:40:30.090  2700  2700 D BluetoothMapAppObserver: removeReceiver()
08-13 18:40:30.091  1372  1372 D BluetoothMap: Proxy object disconnected
08-13 18:40:30.091  1372  1372 D MapProfile: Bluetooth service disconnected
08-13 18:40:30.092  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:30.092  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:30.092  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:30.092  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:30.092   372   870 D CommandListener: Setting iface cfg
,08-13 18:40:30.094  2700  2754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-13 18:40:30.094  2700  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:30.094  2700  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:30.095  2700  2838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-13 18:40:30.095  2700  2838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-13 18:40:30.095  2700  2838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-13 18:40:30.095  2700  2838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-13 18:40:30.095   872  1859 D DhcpClient: Receive thread stopped
,08-13 18:40:30.102  1530  2203 V NativeCrypto: Read error: ssl=0x9b75c000: I/O error during system call, Connection timed out
,08-13 18:40:30.104   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-13 18:40:30.104  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:30.104  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:30.104  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:30.104   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-13 18:40:30.104  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:30.104   872  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
08-13 18:40:30.105  2700  2700 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-13 18:40:30.105  2700  2754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-13 18:40:30.105  2700  2700 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-13 18:40:30.105  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:30.105  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:30.105  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:30.105  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:30.105   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-13 18:40:30.105  2700  2700 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-13 18:40:30.105   872  1316 E native  : do suspend true
08-13 18:40:30.106  2700  2754 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-13 18:40:30.106  2700  2700 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-13 18:40:30.106  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:30.106  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:30.106  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:30.106  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:40:30.108  2700  2700 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-13 18:40:30.108  2700  2700 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-13 18:40:30.110   395   395 E Parcel  : Reading a NULL string not supported here.
08-13 18:40:30.112  2700  2700 D BluetoothMapService: MAP Service closeService in
08-13 18:40:30.112  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:30.112  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:30.112  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:40:30.112  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:30.113  1530  2203 V NativeCrypto: SSL shutdown failed: ssl=0x9b75c000: I/O error during system call, Broken pipe
08-13 18:40:30.113  2700  2750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-13 18:40:30.113  2700  2750 D BluetoothAdapterProperties: Setting state to 15
08-13 18:40:30.113  2700  2750 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-13 18:40:30.113  2700  2750 I BluetoothAdapterState: Entering BleOnState
08-13 18:40:30.113  1925  2311 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-13 18:40:30.114  2700  2700 D BluetoothMapService: cleanup()
08-13 18:40:30.114  2700  2700 D BluetoothMapService: MAP Service closeService in
08-13 18:40:30.114   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-13 18:40:30.114  1372  2027 D BluetoothPan: onBluetoothStateChange on: false
08-13 18:40:30.115   872  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-13 18:40:30.115  1372  1400 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-13 18:40:30.115  1372  1399 D BluetoothMap: onBluetoothStateChange: up=false
,08-13 18:40:30.116  1372  2027 D BluetoothPbap: onBluetoothStateChange: up=false
08-13 18:40:30.118   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:30.118  1372  1397 D BluetoothA2dp: onBluetoothStateChange: up=false
08-13 18:40:30.119   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:30.119   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:30.119  1372  1399 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:30.120  2700  2750 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-13 18:40:30.120  2700  2750 D BluetoothAdapterProperties: Setting state to 16
08-13 18:40:30.120  2700  2750 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-13 18:40:30.120  2700  2750 D BluetoothAdapterProperties: onBleDisable
08-13 18:40:30.120  2700  2750 I BluetoothAdapterState: Entering PendingCommandState
,08-13 18:40:30.121  2700  2751 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-13 18:40:30.122  2700  2754 D BluetoothAdapterProperties: Scan Mode:20
08-13 18:40:30.122  2700  2838 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-13 18:40:30.122  2700  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:30.124  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:30.124  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:30.125  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:30.125  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:30.126  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:30.127  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:30.127  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.127  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:30.129  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:30.129  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:30.130  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.130  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:30.132  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:30.133  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:30.134  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:30.151   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:40:30.157  4044  4044 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-13 18:40:30.175  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-13 18:40:30.181  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-13 18:40:30.181   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-13 18:40:30.181   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-13 18:40:30.182   872  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-13 18:40:30.182   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:40:30.186   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fef365f:true
,08-13 18:40:30.195   872   883 I ActivityManager: Start proc 4061:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-13 18:40:30.197   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-13 18:40:30.200   872   889 D Tethering: MasterInitialState.processMessage what=3
08-13 18:40:30.202  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:30.204  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:30.205  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:30.206  3445  3445 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ca1a4e3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-13 18:40:30.209  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-13 18:40:30.213   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-13 18:40:30.216  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:30.216  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:30.217  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.217  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:30.218  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:30.218  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:30.219  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.219  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:30.220   872  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-13 18:40:30.220  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: ,false
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:30.220  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:30.221  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:30.221  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:30.228  2205  2350 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-13 18:40:30.236  4044  4044 D LocalBluetoothProfileManager: Adding local MAP profile
,08-13 18:40:30.239  4044  4044 D BluetoothMap: Create BluetoothMap proxy object
,08-13 18:40:30.247  4061  4061 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-13 18:40:30.248  4044  4044 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-13 18:40:30.257  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-13 18:40:30.265   872   882 I ActivityManager: Killing 3091:com.google.android.talk/u0a61 (adj 15): empty #17
,08-13 18:40:30.266   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-13 18:40:30.323  2700  2754 I bt_hci  : shut_down
,08-13 18:40:30.324  2700  2758 D bt_hwcfg: hw_epilog_process
,08-13 18:40:30.325  2700  2758 I bt_vendor: low_power_mode_cb
,08-13 18:40:30.352  2700  2758 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-13 18:40:30.352  2700  2758 I bt_vendor: epilog_cb
,08-13 18:40:30.353  2700  2758 I bt_hci  : epilog_finished_callback
,08-13 18:40:30.363  2700  2754 I bt_hci_h4: hal_close
,08-13 18:40:30.364  2700  2754 I bt_userial_vendor: device fd = 51 close,
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.File.exists(File.java:361)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.e.b(PG:170)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.k.d(PG:583)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.e.b(PG:170)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.File.exists(File.java:361)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.425  4061  4061 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.io.File.exists(File.java:361)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.425  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:40:30.426  4061  4061 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:40:30.426  4061  4061 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-13 18:40:30.429  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-13 18:40:30.437  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-13 18:40:30.448  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-13 18:40:30.482   872  2122 I ActivityManager: Start proc 4096:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-13 18:40:30.485   872  2122 I ActivityManager: Killing 3445:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-13 18:40:30.553  2700  2751 D bt_stack_manager: event_shut_down_stack finished.
,08-13 18:40:30.554  2700  2750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-13 18:40:30.556  2700  2700 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-13 18:40:30.557  2700  2750 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-13 18:40:30.557  2700  2700 D BtGatt.GattService: Received stop request...Stopping profile...
08-13 18:40:30.557  2700  2700 D BtGatt.GattService: stop()
,08-13 18:40:30.557  2700  2700 D BtGatt.AdvertiseManager: advertise clients cleared
,08-13 18:40:30.559  2700  2700 V BluetoothAdapterState: isTurningOff()=false
08-13 18:40:30.559  2700  2700 V BluetoothAdapterState: isTurningOn()=false
,08-13 18:40:30.559  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:40:30.559  2700  2700 V BluetoothAdapterState: isBleTurningOff()=true
,08-13 18:40:30.560  2700  2750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-13 18:40:30.560  2700  2750 D BluetoothAdapterProperties: Setting state to 10
,08-13 18:40:30.561  2700  2750 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-13 18:40:30.562  2700  2750 I BluetoothAdapterState: Entering OffState
,08-13 18:40:30.562   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-13 18:40:30.565  4096  4096 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-13 18:40:30.580  2700  2700 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-13 18:40:30.580  2700  2700 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-13 18:40:30.580  2700  2700 I BluetoothServiceJni: cleanupNative: return from cleanup,
,08-13 18:40:30.581  2700  2751 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-13 18:40:30.585  2700  2751 D bt_stack_manager: event_clean_up_stack finished.
,08-13 18:40:30.586  2700  2700 I art     : System.exit called, status: 0
,08-13 18:40:30.586  2700  2700 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-13 18:40:30.663   872  2122 I ActivityManager: Process com.android.bluetooth (pid 2700) has died
,08-13 18:40:30.725  4061  4084 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-13 18:40:30.842   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ffe655:true
,08-13 18:40:30.870  4096  4116 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-13 18:40:30.870  4096  4116 I Babel_SMS: MmsConfig.loadMmsSettings
08-13 18:40:30.871  4096  4116 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-13 18:40:30.871  4096  4116 I Babel_SMS: MmsConfig.loadFromDatabase
,08-13 18:40:30.904  4096  4116 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-13 18:40:30.904  4096  4116 I Babel_SMS: MmsConfig.loadFromResources
,08-13 18:40:30.907  4096  4116 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-13 18:40:30.911  4096  4116 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-13 18:40:30.931  4096  4096 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-13 18:40:30.933  4096  4096 I Babel_Crash: startup - clean
,08-13 18:40:30.965  4096  4096 I Babel_telephony: TeleModule.launchCompleted
,08-13 18:40:30.981   872  3803 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-13 18:40:30.992  4096  4096 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-13 18:40:30.999  4096  4096 W Babel   : BAM#gBA: invalid account id: -1
,08-13 18:40:30.999  4096  4096 W Babel   : BAM#gBA: invalid account id: -1
,08-13 18:40:30.999  4096  4096 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-13 18:40:31.003   872  1386 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-13 18:40:31.005  4096  4121 I Babel   : deleted: false for 0
,08-13 18:40:31.041  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-13 18:40:31.045  1756  1756 D SystemUpdateService: onCreate
,08-13 18:40:31.051  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-13 18:40:31.071  1756  4123 I SystemUpdateService: active receiver: enabled
,08-13 18:40:31.085  1756  4123 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-13 18:40:31.087  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-13 18:40:31.088  1756  4123 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-13 18:40:31.088  1756  4123 I SystemUpdateService: now status is 0 (complete)
08-13 18:40:31.088  1756  4123 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-13 18:40:31.089  1756  4123 I SystemUpdateService: file has been verified
,08-13 18:40:31.089  1756  4123 I SystemUpdateService: OTA package size = 12249756
,08-13 18:40:31.093  1756  2416 I iu.UploadsManager: num queued entries: 0
,08-13 18:40:31.093  1756  2416 I iu.UploadsManager: num updated entries: 0
,08-13 18:40:31.096  1756  2416 I iu.SyncManager: NEXT; no task
,08-13 18:40:31.097  1756  4123 I SystemUpdateService: showing system update notification
,08-13 18:40:31.105  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-13 18:40:31.106  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-13 18:40:31.118  4096  4096 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-13 18:40:31.121   872  1527 I ActivityManager: Start proc 4125:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-13 18:40:31.124  1756  1756 D SystemUpdateService: onDestroy
,08-13 18:40:31.172  4096  4096 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-13 18:40:31.180  4125  4125 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-13 18:40:31.184  1863  2868 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-13 18:40:31.184  1863  2868 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-13 18:40:31.187  4096  4096 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-13 18:40:31.188  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE,
,08-13 18:40:31.191  4096  4096 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-13 18:40:31.198  4096  4096 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-13 18:40:31.211  4125  4125 D SprintDMHelper: simOperator: 
08-13 18:40:31.211  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-13 18:40:31.221  4096  4096 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-13 18:40:31.251   872  3150 I ActivityManager: Start proc 4137:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-13 18:40:31.256  1530  1530 I ConfigService: onCreate
,08-13 18:40:31.258   872  1955 I ActivityManager: Killing 3514:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-13 18:40:31.331  4096  4096 I vclib   : onServiceConnected
,08-13 18:40:31.457   872  1386 I ActivityManager: Start proc 4153:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-13 18:40:31.460  4096  4152 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-13 18:40:31.464   872  2122 I ActivityManager: Killing 1689:android.process.acore/u0a5 (adj 15): empty #17
,08-13 18:40:31.520  4153  4153 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-13 18:40:31.571  4153  4153 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-13 18:40:31.571  4153  4153 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-13 18:40:31.571  4153  4153 I GAv4    :   adb logcat -s GAv4
,08-13 18:40:31.591  4153  4153 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-13 18:40:31.597  4153  4153 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-13 18:40:31.634  4153  4170 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-13 18:40:31.749  4153  4153 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-13 18:40:31.786  4153  4153 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-13 18:40:31.796  4153  4153 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6472-6478)
,08-13 18:40:31.796  4153  4153 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-13 18:40:31.803  4153  4153 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b58cd3}
,08-13 18:40:31.804  4153  4153 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-13 18:40:31.804  4153  4153 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-13 18:40:31.810  4153  4153 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-13 18:40:31.811  4153  4153 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-13 18:40:31.830  4153  4153 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-13 18:40:31.843  4153  4153 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-13 18:40:31.843  4153  4153 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-13 18:40:31.843  4153  4153 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-13 18:40:31.843  4153  4153 I Adreno  : Build Date                       : 10/20/15
08-13 18:40:31.843  4153  4153 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-13 18:40:31.843  4153  4153 I Adreno  : Local Branch                     : M14
08-13 18:40:31.843  4153  4153 I Adreno  : Remote Branch                    : 
08-13 18:40:31.843  4153  4153 I Adreno  : Remote Branch                    : 
08-13 18:40:31.843  4153  4153 I Adreno  : Reconstruct Branch               : 
,08-13 18:40:31.896  4153  4153 I NSApplication: Starting up...
,08-13 18:40:31.911  4153  4199 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-13 18:40:31.942   872  1966 I ActivityManager: Start proc 4204:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-13 18:40:31.944   872  1966 I ActivityManager: Killing 3714:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-13 18:40:32.045  4204  4204 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-13 18:40:32.286   872  1386 I ActivityManager: Killing 3729:com.android.musicfx/u0a18 (adj 15): empty #17
,08-13 18:40:32.368   872  1905 I ActivityManager: Start proc 4218:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-13 18:40:32.450  4218  4218 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-13 18:40:32.513  4218  4218 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-13 18:40:32.539   872  1905 I ActivityManager: Killing 2252:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-13 18:40:35.049   872  1955 D WifiService: setWifiEnabled: true pid=3984, uid=10000
08-13 18:40:35.049   872  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-13 18:40:35.060   872  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-13 18:40:35.070  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:35.070  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:35.071  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:35.071  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:35.074  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:35.075  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:35.075  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:35.075  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:35.077  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:35.078  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:35.078  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:35.078  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:35.084   872  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-13 18:40:35.085   872  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-13 18:40:35.086   872  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-13 18:40:35.086   872  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-13 18:40:35.087   872  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-13 18:40:35.087   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-13 18:40:35.087   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-13 18:40:35.102   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-13 18:40:35.103   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-13 18:40:35.107   372   870 D CommandListener: Setting iface cfg
,08-13 18:40:35.115   872  1316 E native  : do suspend true
08-13 18:40:35.115   872  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-13 18:40:35.115   872  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-13 18:40:35.126   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-13 18:40:35.145   872  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-13 18:40:35.146   872  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-13 18:40:35.887   872  3150 I ActivityManager: Killing 3677:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-13 18:40:36.407  1530  1530 I ConfigService: onDestroy
,08-13 18:40:36.492   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-13 18:40:36.542   872  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.44 rxSuccessRate=17.31 delta 1000 -> 994
,08-13 18:40:36.543   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-13 18:40:36.543   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-13 18:40:36.558   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-13 18:40:36.603   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-13 18:40:36.604  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-13 18:40:37.022  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-13 18:40:37.062  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-13 18:40:37.063  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-13 18:40:37.070   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-13 18:40:37.090   872  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-13 18:40:37.091   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-13 18:40:37.091   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-13 18:40:37.116   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-13 18:40:37.130   372   870 D CommandListener: Setting iface cfg
,08-13 18:40:37.131   872  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-13 18:40:37.137   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-13 18:40:37.170   872  4255 D DhcpClient: Receive thread started
,08-13 18:40:37.250   872  1316 E native  : do suspend false
,08-13 18:40:37.272   872  1845 D DhcpClient: Broadcasting DHCPDISCOVER
,08-13 18:40:37.284   872  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172439, domain null
,08-13 18:40:37.285   872  1845 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172439 seconds
08-13 18:40:37.286   872  1845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-13 18:40:37.298   872  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-13 18:40:37.298   872  1845 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-13 18:40:37.300   372   870 D CommandListener: Setting iface cfg
,08-13 18:40:37.305   872  1845 D DhcpClient: Scheduling renewal in 86399s
,08-13 18:40:37.309   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-13 18:40:37.312   872  1316 E native  : do suspend true
,08-13 18:40:37.331   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-13 18:40:37.334   872  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-13 18:40:37.335   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-13 18:40:37.338   872  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-13 18:40:37.353   872  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-13 18:40:37.410   872  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-13 18:40:37.411   872  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-13 18:40:37.413   872  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-13 18:40:37.416   872  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-13 18:40:37.419   872  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-13 18:40:37.440   872  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-13 18:40:37.453   872  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-13 18:40:37.453   872  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-13 18:40:37.454   872  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-13 18:40:37.454   872  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-13 18:40:37.454   872  1318 D ConnectivityService:    accepting network in place of null
08-13 18:40:37.454   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-13 18:40:37.455   872  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-13 18:40:37.465   872  4254 D NetlinkSocketObserver: NeighborEvent{elapsedMs=382147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-13 18:40:37.503   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:40:37.533   872  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:80e::200e
,08-13 18:40:37.539   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:40:37.546   872  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-13 18:40:37.547   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:40:37.554   872  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-13 18:40:37.555   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-13 18:40:37.569  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:37.570  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:40:37.570  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:37.570  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:40:37.573  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:37.574  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:40:37.574  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:37.574  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:40:37.578  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:40:37.579  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-13 18:40:37.579  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:37.579  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:40:37.584  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-13 18:40:37.589  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-13 18:40:37.598  1756  1756 D SystemUpdateService: onCreate
,08-13 18:40:37.607  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-13 18:40:37.612   872  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 13 Aug 2016 16:40:37 GMT], X-Android-Received-Millis=[1471106437611], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471106437581]}
,08-13 18:40:37.616   872  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-13 18:40:37.616   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-13 18:40:37.616   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-13 18:40:37.617   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-13 18:40:37.634  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-13 18:40:37.640  1756  2416 I iu.UploadsManager: num queued entries: 0
,08-13 18:40:37.647  1756  4265 I SystemUpdateService: active receiver: enabled
,08-13 18:40:37.649  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-13 18:40:37.650  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-13 18:40:37.653  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:40:37.658  1756  4269 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-13 18:40:37.658  1756  4269 W BaseAppContext: Using Auth Proxy for data requests.
08-13 18:40:37.659  1756  4269 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-13 18:40:37.662  4125  4125 D SprintDMHelper: simOperator: 
,08-13 18:40:37.662  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-13 18:40:37.667  1756  2416 I iu.UploadsManager: num updated entries: 0
,08-13 18:40:37.668  1756  2416 I iu.SyncManager: NEXT; no task
08-13 18:40:37.669  1756  4265 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-13 18:40:37.677  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:40:37.685  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:40:37.692  1756  4265 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-13 18:40:37.692  1756  4265 I SystemUpdateService: now status is 0 (complete)
,08-13 18:40:37.697  1756  4265 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-13 18:40:37.697  1756  4265 I SystemUpdateService: file has been verified
,08-13 18:40:37.702  1756  4265 I SystemUpdateService: OTA package size = 12249756
,08-13 18:40:37.750  1756  4265 I SystemUpdateService: showing system update notification
,08-13 18:40:37.804  1756  1756 D SystemUpdateService: onDestroy
,08-13 18:40:37.811  1530  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-13 18:40:37.812  1530  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-13 18:40:37.812  1530  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
08-13 18:40:37.812  1530  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-13 18:40:37.814  4096  4273 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-13 18:40:37.832  1756  4269 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-13 18:40:38.546   872  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-13 18:40:40.055   872   882 D WifiService: setWifiEnabled: false pid=3984, uid=10000
,08-13 18:40:40.055   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-13 18:40:40.091  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-13 18:40:40.098   872  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-13 18:40:40.098   872  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-13 18:40:40.098   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-13 18:40:40.098   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-13 18:40:40.112   872  1316 E native  : do suspend true
,08-13 18:40:40.126   872  1845 D DhcpClient: Clearing IP address
,08-13 18:40:40.126   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-13 18:40:40.133  1530  4278 V NativeCrypto: Read error: ssl=0x9afcb600: I/O error during system call, Connection timed out
,08-13 18:40:40.136  1530  4278 V NativeCrypto: SSL shutdown failed: ssl=0x9afcb600: I/O error during system call, Broken pipe
,08-13 18:40:40.137   372   870 D CommandListener: Setting iface cfg
,08-13 18:40:40.140   872  4255 D DhcpClient: Receive thread stopped
,08-13 18:40:40.145   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-13 18:40:40.145   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-13 18:40:40.153   395   395 E Parcel  : Reading a NULL string not supported here.
,08-13 18:40:40.154   872  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
08-13 18:40:40.156   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-13 18:40:40.156   872  1316 E native  : do suspend true
,08-13 18:40:40.168   872  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-13 18:40:40.219   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:40:40.277   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:40:40.278   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-13 18:40:40.279   872  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-13 18:40:40.280   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:40:40.284   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-13 18:40:40.296  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-13 18:40:40.301  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:40.302  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:40.302  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.302  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:40.303  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:40.303  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:40.303  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.303  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:40.304  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:40.304  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:40.304  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.304  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:40.307   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-13 18:40:40.313  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-13 18:40:40.319  1756  1756 D SystemUpdateService: onCreate
,08-13 18:40:40.325   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-13 18:40:40.327  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-13 18:40:40.327  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:40.328  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:40.328  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:40.328  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:40.329  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:40.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:40.329  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.329  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:40.330  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:40.330  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:40.330  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:40.330  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:40.330   872  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-13 18:40:40.332  2205  2350 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-13 18:40:40.342  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-13 18:40:40.346  1756  2416 I iu.UploadsManager: num queued entries: 0
,08-13 18:40:40.347  1756  2416 I iu.UploadsManager: num updated entries: 0
,08-13 18:40:40.348  1756  4290 I SystemUpdateService: active receiver: enabled
,08-13 18:40:40.350  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-13 18:40:40.351  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-13 18:40:40.353  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:40:40.357  4125  4125 D SprintDMHelper: simOperator: 
,08-13 18:40:40.357  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-13 18:40:40.368  1756  4290 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-13 18:40:40.387  4096  4294 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-13 18:40:40.388   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-13 18:40:40.390  1756  2416 I iu.SyncManager: NEXT; no task
,08-13 18:40:40.396  1756  4290 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-13 18:40:40.396  1756  4290 I SystemUpdateService: now status is 0 (complete)
,08-13 18:40:40.396  1756  4290 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-13 18:40:40.396  1756  4290 I SystemUpdateService: file has been verified
08-13 18:40:40.399  1756  4290 I SystemUpdateService: OTA package size = 12249756
,08-13 18:40:40.404  1756  4290 I SystemUpdateService: showing system update notification
,08-13 18:40:40.415  1756  1756 D SystemUpdateService: onDestroy
,08-13 18:40:45.115   872   889 I ActivityManager: Start proc 4299:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-13 18:40:45.254  4299  4299 D AdapterServiceConfig: Adding HeadsetService
,08-13 18:40:45.255  4299  4299 D AdapterServiceConfig: Adding A2dpService
08-13 18:40:45.255  4299  4299 D AdapterServiceConfig: Adding HidService
,08-13 18:40:45.255  4299  4299 D AdapterServiceConfig: Adding HealthService
08-13 18:40:45.255  4299  4299 D AdapterServiceConfig: Adding PanService
,08-13 18:40:45.256  4299  4299 D AdapterServiceConfig: Adding GattService
08-13 18:40:45.256  4299  4299 D AdapterServiceConfig: Adding BluetoothMapService
,08-13 18:40:45.273  4299  4299 D BluetoothAdapterState: make() - Creating AdapterState
,08-13 18:40:45.273   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c7d6c73:true
,08-13 18:40:45.278  4299  4299 I bt_bluedroid: init
,08-13 18:40:45.279  4299  4311 I BluetoothAdapterState: Entering OffState
,08-13 18:40:45.284  4299  4312 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-13 18:40:45.285  4299  4312 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-13 18:40:45.285  4299  4312 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-13 18:40:45.285  4299  4312 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-13 18:40:45.287  4299  4299 I bt_bluedroid: get_profile_interface socket
,08-13 18:40:45.290  4299  4299 I bt_bluedroid: get_profile_interface sdp
08-13 18:40:45.293  4299  4309 I bt_bluedroid: config_hci_snoop_log
,08-13 18:40:45.295  4299  4315 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-13 18:40:45.296   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-13 18:40:45.300  4299  4315 D BluetoothAdapterProperties: Name is: Nexus 6
,08-13 18:40:45.308  4299  4311 D BluetoothAdapterState: Current state: OFF, message: 0
,08-13 18:40:45.308  4299  4311 D BluetoothAdapterProperties: Setting state to 14
,08-13 18:40:45.309  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-13 18:40:45.313  4299  4311 D BluetoothBondStateMachine: make
,08-13 18:40:45.317  4299  4316 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-13 18:40:45.324  4299  4311 I BluetoothAdapterState: Entering PendingCommandState
,08-13 18:40:45.328  4299  4299 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-13 18:40:45.336  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:40:45.339  4299  4299 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-13 18:40:45.341  4299  4299 D BtGatt.GattService: Received start request. Starting profile...
,08-13 18:40:45.341  4299  4299 D BtGatt.GattService: start()
,08-13 18:40:45.341  4299  4299 I bt_bluedroid: get_profile_interface gatt
,08-13 18:40:45.344  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
08-13 18:40:45.345  4299  4299 D BtGatt.AdvertiseManager: advertise manager created
,08-13 18:40:45.357  4299  4299 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:40:45.357  4299  4299 V BluetoothAdapterState: isTurningOn()=false
,08-13 18:40:45.357  4299  4299 V BluetoothAdapterState: isBleTurningOn()=true
08-13 18:40:45.357  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:40:45.358  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-13 18:40:45.359  4299  4311 I bt_bluedroid: enable
,08-13 18:40:45.359  4299  4312 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-13 18:40:45.360  4299  4312 I bt_hci  : start_up
,08-13 18:40:45.382  4299  4312 I bt_vendor: alloc value 0xb3a8b189
,08-13 18:40:45.382  4299  4312 I bt_vendor: init
08-13 18:40:45.382  4299  4312 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-13 18:40:45.383  4299  4312 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-13 18:40:45.458   872  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-13 18:40:45.495  4299  4312 D bt_hci  : start_up starting async portion
,08-13 18:40:45.496  4299  4319 I bt_hci  : event_finish_startup
,08-13 18:40:45.496  4299  4319 I bt_hci_h4: hal_open
,08-13 18:40:45.497  4299  4319 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-13 18:40:45.510  4299  4319 I bt_userial_vendor: device fd = 51 open
,08-13 18:40:45.535  4299  4319 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-13 18:40:45.567  4299  4319 D bt_hwcfg: Chipset BCM4354A2
,08-13 18:40:45.567  4299  4319 D bt_hwcfg: Target name = [BCM4354A2]
,08-13 18:40:45.568  4299  4319 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-13 18:40:46.225  4299  4319 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-13 18:40:46.226  4299  4319 D bt_hwcfg: Settlement delay -- 100 ms
,08-13 18:40:46.227  4299  4319 I bt_hwcfg: Setting fw settlement delay to 100 
,08-13 18:40:46.344  4299  4319 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-13 18:40:46.345  4299  4319 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-13 18:40:46.374  4299  4319 I bt_hwcfg: vendor lib fwcfg completed
,08-13 18:40:46.374  4299  4319 I bt_vendor: firmware callback
08-13 18:40:46.374  4299  4319 I bt_hci  : firmware_config_callback
,08-13 18:40:46.387  4299  4321 I bt_btu  : btu_task pending for preload complete event
,08-13 18:40:46.387  4299  4321 I bt_btu_task: Bluetooth chip preload is complete
,08-13 18:40:46.387  4299  4321 I bt_btu  : btu_task received preload complete event
,08-13 18:40:46.395  4299  4321 I         : BTE_InitTraceLevels -- TRC_HCI
,08-13 18:40:46.395  4299  4321 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-13 18:40:46.396  4299  4321 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-13 18:40:46.396  4299  4321 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-13 18:40:46.396  4299  4321 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-13 18:40:46.396  4299  4321 I         : BTE_InitTraceLevels -- TRC_A2D
,08-13 18:40:46.397  4299  4321 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-13 18:40:46.397  4299  4321 I         : BTE_InitTraceLevels -- TRC_BTM
08-13 18:40:46.397  4299  4321 I         : BTE_InitTraceLevels -- TRC_GAP
08-13 18:40:46.397  4299  4321 I         : BTE_InitTraceLevels -- TRC_PAN
08-13 18:40:46.397  4299  4321 I         : BTE_InitTraceLevels -- TRC_SDP
08-13 18:40:46.398  4299  4321 I         : BTE_InitTraceLevels -- TRC_GATT
08-13 18:40:46.398  4299  4321 I         : BTE_InitTraceLevels -- TRC_SMP
08-13 18:40:46.398  4299  4321 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-13 18:40:46.398  4299  4321 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-13 18:40:46.525  4299  4321 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a08d9d
,08-13 18:40:46.526  4299  4321 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a08d9d 
,08-13 18:40:46.551  4299  4315 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-13 18:40:46.552  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-13 18:40:46.553  4299  4315 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-13 18:40:46.556  4299  4315 D BluetoothAdapterProperties: Name is: Nexus 6
,08-13 18:40:46.559  4299  4315 D BluetoothAdapterProperties: Scan Mode:20
,08-13 18:40:46.559  4299  4315 D BluetoothAdapterProperties: Discoverable Timeout:120
08-13 18:40:46.559  4299  4315 D bt_hci  : do_postload posting postload work item
08-13 18:40:46.560  4299  4319 I bt_hci  : event_postload
,08-13 18:40:46.560  4299  4319 I bt_vendor: sco_config_cb
,08-13 18:40:46.560  4299  4319 I bt_hci  : sco_config_callback postload finished.
,08-13 18:40:46.564  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:46.566  4299  4315 D bt_bte_conf: Device ID record 1 : primary
,08-13 18:40:46.567  4299  4315 D bt_bte_conf:   vendorId            = 000f
,08-13 18:40:46.567  4299  4315 D bt_bte_conf:   vendorIdSource      = 0001
,08-13 18:40:46.567  4299  4315 D bt_bte_conf:   product             = 1200
,08-13 18:40:46.567  4299  4315 D bt_bte_conf:   version             = 1436
,08-13 18:40:46.568  4299  4315 D bt_bte_conf:   clientExecutableURL = 
,08-13 18:40:46.568  4299  4315 D bt_bte_conf:   serviceDescription  = 
,08-13 18:40:46.568  4299  4315 D bt_bte_conf:   documentationURL    = 
08-13 18:40:46.568  4299  4315 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-13 18:40:46.569  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.569  4299  4312 D bt_stack_manager: event_start_up_stack finished
,08-13 18:40:46.572  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-13 18:40:46.572  4299  4311 D BluetoothAdapterProperties: Setting state to 15
08-13 18:40:46.573  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-13 18:40:46.573  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.574  4299  4311 I BluetoothAdapterState: Entering BleOnState
,08-13 18:40:46.579  4299  4311 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-13 18:40:46.580  4299  4311 D BluetoothAdapterProperties: Setting state to 11
08-13 18:40:46.580  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-13 18:40:46.584  4299  4319 I bt_vendor: low_power_mode_cb
08-13 18:40:46.590  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:40:46.593  4299  4299 D HeadsetService: Received start request. Starting profile...
,08-13 18:40:46.596  4299  4299 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-13 18:40:46.597  4299  4299 D HeadsetStateMachine: make
08-13 18:40:46.606  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.609  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.609  4299  4311 I BluetoothAdapterState: Entering PendingCommandState,
08-13 18:40:46.609  4299  4299 D HeadsetStateMachine: max_hf_connections = 1
08-13 18:40:46.610  4299  4299 I bt_bluedroid: get_profile_interface handsfree
08-13 18:40:46.610  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-13 18:40:46.610  4299  4315 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-13 18:40:46.611  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.613  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
08-13 18:40:46.613  4299  4299 D A2dpService: Received start request. Starting profile...
,08-13 18:40:46.614  4299  4299 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-13 18:40:46.615  4299  4299 I bt_bluedroid: get_profile_interface avrcp
,08-13 18:40:46.621  4299  4299 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-13 18:40:46.621  4299  4299 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-13 18:40:46.621  4299  4299 D A2dpStateMachine: make
,08-13 18:40:46.623  4299  4299 I bt_bluedroid: get_profile_interface a2dp
08-13 18:40:46.623  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-13 18:40:46.625  4299  4330 D A2dpStateMachine: Enter Disconnected: -2
,08-13 18:40:46.625  4299  4299 I BluetoothHidServiceJni: classInitNative: succeeds
,08-13 18:40:46.626  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:40:46.627  4299  4299 D HidService: Received start request. Starting profile...
08-13 18:40:46.627  4044  4044 D BluetoothInputDevice: Proxy object connected
,08-13 18:40:46.627  4299  4299 I bt_bluedroid: get_profile_interface hidhost
08-13 18:40:46.628  4299  4315 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ea3e5
08-13 18:40:46.628  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-13 18:40:46.628  4299  4299 D HidService: setHidService(): set to: null
08-13 18:40:46.628  4044  4044 D HidProfile: Bluetooth service connected
08-13 18:40:46.629  4299  4299 I BluetoothHealthServiceJni: classInitNative: succeeds
08-13 18:40:46.629  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1,
,08-13 18:40:46.632  4299  4299 D HealthService: Received start request. Starting profile...
,08-13 18:40:46.633  4299  4299 I bt_bluedroid: get_profile_interface health
,08-13 18:40:46.634  4299  4299 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-13 18:40:46.635  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:40:46.636  4044  4044 D BluetoothPan: BluetoothPAN Proxy object connected
08-13 18:40:46.636  4299  4299 D PanService: Received start request. Starting profile...
08-13 18:40:46.636  4299  4299 D BluetoothPanServiceJni: initializeNative(L110): pan
08-13 18:40:46.636  4299  4299 I bt_bluedroid: get_profile_interface pan
08-13 18:40:46.636  4299  4315 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-13 18:40:46.637  4044  4044 D PanProfile: Bluetooth service connected
,08-13 18:40:46.639  4299  4299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:40:46.640  4044  4044 D BluetoothMap: Proxy object connected
,08-13 18:40:46.641  4044  4044 D MapProfile: Bluetooth service connected
08-13 18:40:46.641  4299  4299 D BluetoothMapService: Received start request. Starting profile...
08-13 18:40:46.641  4299  4299 D BluetoothMapService: start()
08-13 18:40:46.641  4044  4044 D BluetoothMap: getConnectedDevices()
08-13 18:40:46.641  4044  4044 D BluetoothMap: Bluetooth is Not enabled
,08-13 18:40:46.644  4299  4299 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-13 18:40:46.645  4299  4299 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-13 18:40:46.645  4299  4299 D BluetoothMapAppObserver: createReceiver()
,08-13 18:40:46.647  4299  4299 D BluetoothMapAppObserver: initObservers()
,08-13 18:40:46.647  4299  4299 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-13 18:40:46.654  4299  4299 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:40:46.654  4299  4299 V BluetoothAdapterState: isTurningOn()=true
08-13 18:40:46.654  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:46.654  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:40:46.657  4299  4327 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isTurningOff()=false
08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isTurningOn()=true
08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isTurningOn()=true
08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:46.658  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isTurningOn()=true
08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isTurningOff()=false,
08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isTurningOn()=true
08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:40:46.659  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:40:46.660  4299  4299 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:40:46.660  4299  4299 V BluetoothAdapterState: isTurningOn()=true
,08-13 18:40:46.660  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:46.660  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:40:46.660  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-13 18:40:46.660  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-13 18:40:46.660  4299  4311 D BluetoothAdapterProperties: ScanMode =  20
,08-13 18:40:46.660  4299  4311 D BluetoothAdapterProperties: State =  11
,08-13 18:40:46.661  4299  4311 D BluetoothAdapterProperties: Setting state to 12
,08-13 18:40:46.661  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-13 18:40:46.662  4299  4311 I BluetoothAdapterState: Entering OnState
,08-13 18:40:46.663  4044  4054 D BluetoothMap: onBluetoothStateChange: up=true
,08-13 18:40:46.663  1925  2311 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-13 18:40:46.664  4299  4315 D BluetoothAdapterProperties: Scan Mode:21
08-13 18:40:46.664  4299  4315 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-13 18:40:46.664   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-13 18:40:46.667  1372  1397 D BluetoothPan: onBluetoothStateChange on: true
,08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:46.668  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:46.668   872   872 D BluetoothA2dp: Proxy object connected
,08-13 18:40:46.670  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-13 18:40:46.670  1372  1372 D PanProfile: Bluetooth service connected
08-13 18:40:46.670  1372  2027 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-13 18:40:46.671  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:46.672  1372  1372 D BluetoothInputDevice: Proxy object connected
08-13 18:40:46.672  1372  1372 D HidProfile: Bluetooth service connected
,08-13 18:40:46.672  1372  1399 D BluetoothMap: onBluetoothStateChange: up=true
,08-13 18:40:46.675  4299  4299 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:46.675  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:46.676  4299  4299 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-13 18:40:46.676  1372  2027 D BluetoothPbap: onBluetoothStateChange: up=true
,08-13 18:40:46.677  1372  1372 D BluetoothMap: Proxy object connected
,08-13 18:40:46.677  1372  1372 D MapProfile: Bluetooth service connected
,08-13 18:40:46.677  1372  1372 D BluetoothMap: getConnectedDevices()
08-13 18:40:46.679  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:46.680   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-13 18:40:46.680  4299  4299 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-13 18:40:46.680  1372  1397 D BluetoothA2dp: onBluetoothStateChange: up=true
08-13 18:40:46.683  1372  1372 D BluetoothA2dp: Proxy object connected
,08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:46.683  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:46.684   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:40:46.684   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:40:46.685  4044  4055 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-13 18:40:46.686  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:46.686  4299  4299 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:40:46.686  4044  4056 D BluetoothPan: onBluetoothStateChange on: true
08-13 18:40:46.686  1372  1399 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:40:46.687  4044  4054 D BluetoothPbap: onBluetoothStateChange: up=true
,08-13 18:40:46.688  4299  4299 D ObexServerSockets: Succeed to create listening sockets 
,08-13 18:40:46.688  4299  4299 D ObexServerSockets0: startAccept()
08-13 18:40:46.688  4299  4299 D ObexServerSockets0: prepareForNewConnect()
08-13 18:40:46.690  4299  4299 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-13 18:40:46.690  4299  4299 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-13 18:40:46.691   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-13 18:40:46.692  4299  4299 D BluetoothMapService: onReceive
08-13 18:40:46.692  4299  4299 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-13 18:40:46.692  4299  4299 D BluetoothMapService: STATE_ON
08-13 18:40:46.693  4299  4337 D ObexServerSockets0: Accepting socket connection...
,08-13 18:40:46.693  4299  4336 D ObexServerSockets0: Accepting socket connection...
08-13 18:40:46.693  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.694  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.694  4044  4044 D LocalBluetoothProfileManager: Adding local A2DP profile
08-13 18:40:46.695  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:46.698  4044  4044 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-13 18:40:46.704  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-13 18:40:46.706  4044  4044 D BluetoothA2dp: Proxy object connected
,08-13 18:40:46.711  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-13 18:40:46.715  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-13 18:40:46.718  1372  1372 D BluetoothPbap: Proxy object connected
,08-13 18:40:46.718  1372  1372 D PbapServerProfile: Bluetooth service connected
08-13 18:40:46.718  4299  4299 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-13 18:40:46.719  4299  4299 D ObexServerSockets0: prepareForNewConnect()
08-13 18:40:46.719  4044  4044 D BluetoothPbap: Proxy object connected
,08-13 18:40:46.719  4044  4044 D PbapServerProfile: Bluetooth service connected
,08-13 18:40:46.726  4299  4342 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:40:46.741  4299  4346 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:40:46.743  4299  4346 I BtOppRfcommListener: Accept thread started.
,08-13 18:40:46.765   872   872 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.765  1372  1399 D BluetoothHeadset: Proxy object connected
08-13 18:40:46.765  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-13 18:40:46.766  1925  1949 D BluetoothHeadset: Proxy object connected
08-13 18:40:46.766   872   872 D BluetoothHeadset: Proxy object connected
08-13 18:40:46.766   872   872 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.780   872   889 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.784   872   889 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.785   872   889 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.787  1372  2027 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.788  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-13 18:40:46.801  4044  4054 D BluetoothHeadset: Proxy object connected
,08-13 18:40:46.804  4044  4044 D HeadsetProfile: Bluetooth service connected
,08-13 18:40:50.075  4299  4311 D BluetoothAdapterState: Current state: ON, message: 23
,08-13 18:40:50.075  4299  4311 D BluetoothAdapterProperties: Setting state to 13
08-13 18:40:50.076  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-13 18:40:50.078  4299  4311 D BluetoothAdapterProperties: onBluetoothDisable()
,08-13 18:40:50.079  4299  4311 I BluetoothAdapterState: Entering PendingCommandState
,08-13 18:40:50.094  4299  4299 D BluetoothMapService: onReceive
,08-13 18:40:50.094  4299  4299 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-13 18:40:50.095  4299  4299 D BluetoothMapService: STATE_TURNING_OFF
08-13 18:40:50.096  4299  4299 D BluetoothMapService: MAP Service closeService in
08-13 18:40:50.096  4299  4299 D BluetoothMapMasInstance0: MAP Service shutdown
08-13 18:40:50.096  4299  4299 D ObexServerSockets0: shutdown(block = true)
,08-13 18:40:50.097  4299  4336 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-13 18:40:50.098  4299  4299 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-13 18:40:50.099  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-13 18:40:50.099  4299  4337 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:50.099  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:50.101  4299  4323 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-13 18:40:50.102  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:50.102  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:40:50.103  4299  4299 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-13 18:40:50.103  4299  4299 I BtOppRfcommListener: stopping Accept Thread
08-13 18:40:50.104  4299  4315 D BluetoothAdapterProperties: Scan Mode:20
08-13 18:40:50.105  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-13 18:40:50.105  4299  4346 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-13 18:40:50.105  4299  4346 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-13 18:40:50.107  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-13 18:40:50.110  4299  4299 D HeadsetService: Received stop request...Stopping profile...
,08-13 18:40:50.111  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:50.111  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:40:50.113  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:50.113  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:50.113   872   872 D BluetoothHeadset: Proxy object disconnected
,08-13 18:40:50.115  1372  2027 D BluetoothHeadset: Proxy object disconnected
08-13 18:40:50.116  1925  2278 D BluetoothHeadset: Proxy object disconnected
08-13 18:40:50.116  4044  4056 D BluetoothHeadset: Proxy object disconnected
,08-13 18:40:50.116  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:40:50.116  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:40:50.116   872   872 D BluetoothHeadset: Proxy object disconnected
,08-13 18:40:50.117   872   872 D BluetoothHeadset: Proxy object disconnected
08-13 18:40:50.117  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-13 18:40:50.117  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-13 18:40:50.119  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:50.120  4299  4299 V BluetoothAdapterState: isTurningOff()=true
,08-13 18:40:50.120  4299  4299 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:50.120  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:50.121  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:40:50.122  4299  4299 D A2dpService: Received stop request...Stopping profile...
08-13 18:40:50.122  4299  4330 D A2dpStateMachine: Exit Disconnected: -1
08-13 18:40:50.124  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:50.125   872   872 D BluetoothA2dp: Proxy object disconnected
08-13 18:40:50.126  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:50.127  4299  4299 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-13 18:40:50.127  4299  4299 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-13 18:40:50.128  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-13 18:40:50.128  4299  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:50.128  4299  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:50.128  4299  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:50.128  4299  4315 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-13 18:40:50.131  4299  4299 D HidService: Received stop request...Stopping profile...
08-13 18:40:50.132  4299  4299 D HidService: Stopping Bluetooth HidService
08-13 18:40:50.132  1372  1372 D HeadsetProfile: Bluetooth service disconnected
,08-13 18:40:50.133  4299  4299 D HealthService: Received stop request...Stopping profile...
08-13 18:40:50.133  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-13 18:40:50.134  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-13 18:40:50.134  1372  1372 D HidProfile: Bluetooth service disconnected
,08-13 18:40:50.135  4299  4299 D PanService: Received stop request...Stopping profile...
08-13 18:40:50.135  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-13 18:40:50.135  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-13 18:40:50.136  1372  1372 D PanProfile: Bluetooth service disconnected
08-13 18:40:50.136  4299  4299 V BluetoothAdapterState: isTurningOff()=true
,08-13 18:40:50.136  4299  4299 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:50.136  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:50.136  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false,
08-13 18:40:50.137  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-13 18:40:50.137  4299  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:50.137  4299  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-13 18:40:50.138  4299  4321 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-13 18:40:50.138  4299  4321 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-13 18:40:50.138  4299  4321 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-13 18:40:50.138  4299  4321 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-13 18:40:50.138  4299  4299 D BluetoothMapService: Received stop request...Stopping profile...
08-13 18:40:50.138  4299  4299 D BluetoothMapService: stop()
08-13 18:40:50.138  4299  4299 D BluetoothMapAppObserver: deinitObservers()
08-13 18:40:50.139  4299  4299 D BluetoothMapAppObserver: removeReceiver()
,08-13 18:40:50.140  1372  1372 D BluetoothMap: Proxy object disconnected
,08-13 18:40:50.140  1372  1372 D MapProfile: Bluetooth service disconnected
08-13 18:40:50.142  1372  1372 D BluetoothPbap: Proxy object disconnected
08-13 18:40:50.142  1372  1372 D PbapServerProfile: Bluetooth service disconnected
08-13 18:40:50.142  4299  4299 V BluetoothAdapterState: isTurningOff()=true
,08-13 18:40:50.143  4299  4299 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:50.143  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:50.143  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:50.143  4299  4299 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-13 18:40:50.143  4299  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-13 18:40:50.143  4044  4044 D DockEventReceiver: finishStartingService: stopping service,
,08-13 18:40:50.144  4299  4299 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-13 18:40:50.144  4299  4299 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:50.144  4299  4299 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:50.144  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:40:50.144  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:50.144  4299  4299 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-13 18:40:50.144  4299  4315 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-13 18:40:50.145  4044  4044 D HeadsetProfile: Bluetooth service disconnected
08-13 18:40:50.145  4299  4299 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-13 18:40:50.145  4299  4299 V BluetoothAdapterState: isTurningOff()=true
,08-13 18:40:50.145  4299  4299 V BluetoothAdapterState: isTurningOn()=false
08-13 18:40:50.145  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:50.145  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:50.145  4044  4044 D BluetoothA2dp: Proxy object disconnected
,08-13 18:40:50.145  4299  4299 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-13 18:40:50.146  4299  4299 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-13 18:40:50.146  4044  4044 D BluetoothInputDevice: Proxy object disconnected
08-13 18:40:50.147  4044  4044 D HidProfile: Bluetooth service disconnected
08-13 18:40:50.147  4299  4299 D BluetoothMapService: MAP Service closeService in
08-13 18:40:50.147  4299  4299 V BluetoothAdapterState: isTurningOff()=true
08-13 18:40:50.147  4299  4299 V BluetoothAdapterState: isTurningOn()=false,
08-13 18:40:50.147  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:40:50.147  4299  4299 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:40:50.148  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-13 18:40:50.148  4299  4311 D BluetoothAdapterProperties: Setting state to 15
08-13 18:40:50.148  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-13 18:40:50.148  4299  4311 I BluetoothAdapterState: Entering BleOnState
08-13 18:40:50.148  4299  4299 D BluetoothMapService: cleanup()
08-13 18:40:50.148  4299  4299 D BluetoothMapService: MAP Service closeService in
,08-13 18:40:50.150  4044  4054 D BluetoothMap: onBluetoothStateChange: up=false
08-13 18:40:50.151  1925  1947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:50.152   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-13 18:40:50.152  1372  1399 D BluetoothPan: onBluetoothStateChange on: false
08-13 18:40:50.155  4044  4044 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-13 18:40:50.155  4044  4044 D PanProfile: Bluetooth service disconnected
08-13 18:40:50.156  1372  2027 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-13 18:40:50.156  4044  4044 D BluetoothPbap: Proxy object disconnected
08-13 18:40:50.156  4044  4044 D PbapServerProfile: Bluetooth service disconnected
08-13 18:40:50.157  4044  4056 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-13 18:40:50.157  1372  1400 D BluetoothMap: onBluetoothStateChange: up=false
08-13 18:40:50.159  4044  4056 D BluetoothA2dp: onBluetoothStateChange: up=false
08-13 18:40:50.159  1372  1397 D BluetoothPbap: onBluetoothStateChange: up=false
,08-13 18:40:50.159   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:50.160  1372  1399 D BluetoothA2dp: onBluetoothStateChange: up=false
08-13 18:40:50.160   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:50.160   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:50.160  4044  4054 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-13 18:40:50.161  4044  4055 D BluetoothPan: onBluetoothStateChange on: false
,08-13 18:40:50.161  1372  2027 D BluetoothHeadset: onBluetoothStateChange: up=false
08-13 18:40:50.162  4044  4056 D BluetoothPbap: onBluetoothStateChange: up=false
08-13 18:40:50.163  4299  4311 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-13 18:40:50.163  4299  4311 D BluetoothAdapterProperties: Setting state to 16
08-13 18:40:50.163  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-13 18:40:50.164  4299  4311 D BluetoothAdapterProperties: onBleDisable
08-13 18:40:50.164  4299  4311 I BluetoothAdapterState: Entering PendingCommandState
08-13 18:40:50.164  4299  4312 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-13 18:40:50.165  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:50.165  4299  4321 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-13 18:40:50.165  4299  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-13 18:40:50.167  4299  4315 D BluetoothAdapterProperties: Scan Mode:20
08-13 18:40:50.167  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:50.168  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:50.169  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:50.170  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-13 18:40:50.170  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:40:50.171  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:40:50.176  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-13 18:40:50.184  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-13 18:40:50.370  4299  4315 I bt_hci  : shut_down,
08-13 18:40:50.371  4299  4319 D bt_hwcfg: hw_epilog_process
,08-13 18:40:50.373  4299  4319 I bt_vendor: low_power_mode_cb
,08-13 18:40:50.392  4299  4319 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-13 18:40:50.393  4299  4319 I bt_vendor: epilog_cb
08-13 18:40:50.393  4299  4319 I bt_hci  : epilog_finished_callback
,08-13 18:40:50.405  4299  4315 I bt_hci_h4: hal_close
,08-13 18:40:50.407  4299  4315 I bt_userial_vendor: device fd = 51 close
,08-13 18:40:50.532  4299  4312 D bt_stack_manager: event_shut_down_stack finished.
,08-13 18:40:50.533  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-13 18:40:50.542  4299  4311 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-13 18:40:50.542  4299  4299 D BtGatt.DebugUtils: handleDebugAction() action=null
08-13 18:40:50.544  4299  4299 D BtGatt.GattService: Received stop request...Stopping profile...
,08-13 18:40:50.544  4299  4299 D BtGatt.GattService: stop()
08-13 18:40:50.545  4299  4299 D BtGatt.AdvertiseManager: advertise clients cleared
,08-13 18:40:50.550  4299  4299 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:40:50.550  4299  4299 V BluetoothAdapterState: isTurningOn()=false
,08-13 18:40:50.550  4299  4299 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:40:50.551  4299  4299 V BluetoothAdapterState: isBleTurningOff()=true
08-13 18:40:50.552  4299  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-13 18:40:50.552  4299  4311 D BluetoothAdapterProperties: Setting state to 10
,08-13 18:40:50.552  4299  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-13 18:40:50.554  4299  4311 I BluetoothAdapterState: Entering OffState
08-13 18:40:50.556   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-13 18:40:50.588  4299  4299 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-13 18:40:50.588  4299  4299 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-13 18:40:50.589  4299  4312 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-13 18:40:50.595  4299  4299 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-13 18:40:50.598  4299  4312 D bt_stack_manager: event_clean_up_stack finished.
,08-13 18:40:50.601  4299  4299 I art     : System.exit called, status: 0
,08-13 18:40:50.601  4299  4299 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-13 18:40:50.670   872  1905 I ActivityManager: Process com.android.bluetooth (pid 4299) has died
,08-13 18:40:55.071  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
,08-13 18:40:55.072  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:00.077  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:00.078  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d3c8fc removed from the list
08-13 18:41:00.078  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:00.078  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:00.079  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:00.081  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:41:00.082  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4191dda added. We now have 4 listener(s)
,08-13 18:41:00.082  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-13 18:41:00.084  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:00.084  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4191dda removed from the list
08-13 18:41:00.085  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:00.085  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:41:00.085  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:00.087  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:41:00.088  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@666520b added. We now have 4 listener(s)
08-13 18:41:00.088  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:41:02.096  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:02.147   872   889 I ActivityManager: Start proc 4359:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-13 18:41:02.278  4359  4359 D AdapterServiceConfig: Adding HeadsetService
,08-13 18:41:02.279  4359  4359 D AdapterServiceConfig: Adding A2dpService
08-13 18:41:02.279  4359  4359 D AdapterServiceConfig: Adding HidService
08-13 18:41:02.279  4359  4359 D AdapterServiceConfig: Adding HealthService
08-13 18:41:02.279  4359  4359 D AdapterServiceConfig: Adding PanService
08-13 18:41:02.279  4359  4359 D AdapterServiceConfig: Adding GattService
08-13 18:41:02.279  4359  4359 D AdapterServiceConfig: Adding BluetoothMapService
,08-13 18:41:02.292  4359  4359 D BluetoothAdapterState: make() - Creating AdapterState
08-13 18:41:02.292   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@81f384:true
,08-13 18:41:02.297  4359  4359 I bt_bluedroid: init
,08-13 18:41:02.298  4359  4371 I BluetoothAdapterState: Entering OffState
,08-13 18:41:02.300  4359  4372 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-13 18:41:02.300  4359  4372 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-13 18:41:02.300  4359  4372 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-13 18:41:02.300  4359  4372 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-13 18:41:02.304  4359  4359 I bt_bluedroid: get_profile_interface socket
,08-13 18:41:02.309  4359  4375 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-13 18:41:02.312  4359  4359 I bt_bluedroid: get_profile_interface sdp
08-13 18:41:02.314  4359  4375 D BluetoothAdapterProperties: Name is: Nexus 6
,08-13 18:41:02.318  4359  4370 I bt_bluedroid: config_hci_snoop_log
,08-13 18:41:02.320   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-13 18:41:02.326  4359  4371 D BluetoothAdapterState: Current state: OFF, message: 0
,08-13 18:41:02.326  4359  4371 D BluetoothAdapterProperties: Setting state to 14
08-13 18:41:02.326  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-13 18:41:02.327  4359  4371 D BluetoothBondStateMachine: make
,08-13 18:41:02.331  4359  4376 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-13 18:41:02.333  4359  4371 I BluetoothAdapterState: Entering PendingCommandState
,08-13 18:41:02.335  4359  4359 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-13 18:41:02.337  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
08-13 18:41:02.338  4359  4359 D BtGatt.DebugUtils: handleDebugAction() action=null
08-13 18:41:02.338  4359  4359 D BtGatt.GattService: Received start request. Starting profile...
08-13 18:41:02.338  4359  4359 D BtGatt.GattService: start()
08-13 18:41:02.338  4359  4359 I bt_bluedroid: get_profile_interface gatt
,08-13 18:41:02.339  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
08-13 18:41:02.339  4359  4359 D BtGatt.AdvertiseManager: advertise manager created
,08-13 18:41:02.344  4359  4359 V BluetoothAdapterState: isTurningOff()=false
08-13 18:41:02.344  4359  4359 V BluetoothAdapterState: isTurningOn()=false
08-13 18:41:02.344  4359  4359 V BluetoothAdapterState: isBleTurningOn()=true
,08-13 18:41:02.345  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:41:02.345  4359  4371 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-13 18:41:02.345  4359  4371 I bt_bluedroid: enable
08-13 18:41:02.345  4359  4372 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-13 18:41:02.346  4359  4372 I bt_hci  : start_up
,08-13 18:41:02.351  4359  4372 I bt_vendor: alloc value 0xb3a8b189
08-13 18:41:02.351  4359  4372 I bt_vendor: init
08-13 18:41:02.352  4359  4372 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-13 18:41:02.352  4359  4372 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-13 18:41:02.459  4359  4372 D bt_hci  : start_up starting async portion
,08-13 18:41:02.460  4359  4379 I bt_hci  : event_finish_startup
08-13 18:41:02.460  4359  4379 I bt_hci_h4: hal_open
08-13 18:41:02.460  4359  4379 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-13 18:41:02.470  4359  4379 I bt_userial_vendor: device fd = 51 open
,08-13 18:41:02.503  4359  4379 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-13 18:41:02.534  4359  4379 D bt_hwcfg: Chipset BCM4354A2
,08-13 18:41:02.534  4359  4379 D bt_hwcfg: Target name = [BCM4354A2]
08-13 18:41:02.535  4359  4379 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-13 18:41:03.400  4359  4379 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-13 18:41:03.401  4359  4379 D bt_hwcfg: Settlement delay -- 100 ms
08-13 18:41:03.402  4359  4379 I bt_hwcfg: Setting fw settlement delay to 100 
,08-13 18:41:03.518  4359  4379 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-13 18:41:03.520  4359  4379 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-13 18:41:03.549  4359  4379 I bt_hwcfg: vendor lib fwcfg completed
,08-13 18:41:03.549  4359  4379 I bt_vendor: firmware callback
08-13 18:41:03.549  4359  4379 I bt_hci  : firmware_config_callback
,08-13 18:41:03.562  4359  4381 I bt_btu  : btu_task pending for preload complete event
,08-13 18:41:03.562  4359  4381 I bt_btu_task: Bluetooth chip preload is complete
08-13 18:41:03.563  4359  4381 I bt_btu  : btu_task received preload complete event
,08-13 18:41:03.573  4359  4381 I         : BTE_InitTraceLevels -- TRC_HCI
,08-13 18:41:03.573  4359  4381 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-13 18:41:03.573  4359  4381 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-13 18:41:03.574  4359  4381 I         : BTE_InitTraceLevels -- TRC_AVDT
08-13 18:41:03.574  4359  4381 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-13 18:41:03.574  4359  4381 I         : BTE_InitTraceLevels -- TRC_A2D
08-13 18:41:03.575  4359  4381 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-13 18:41:03.575  4359  4381 I         : BTE_InitTraceLevels -- TRC_BTM
08-13 18:41:03.575  4359  4381 I         : BTE_InitTraceLevels -- TRC_GAP
08-13 18:41:03.575  4359  4381 I         : BTE_InitTraceLevels -- TRC_PAN
,08-13 18:41:03.576  4359  4381 I         : BTE_InitTraceLevels -- TRC_SDP
08-13 18:41:03.576  4359  4381 I         : BTE_InitTraceLevels -- TRC_GATT
08-13 18:41:03.576  4359  4381 I         : BTE_InitTraceLevels -- TRC_SMP
,08-13 18:41:03.576  4359  4381 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-13 18:41:03.577  4359  4381 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-13 18:41:03.712  4359  4381 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a08d9d
,08-13 18:41:03.713  4359  4381 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a08d9d 
,08-13 18:41:03.725  4359  4375 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-13 18:41:03.726  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-13 18:41:03.728  4359  4375 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-13 18:41:03.734  4359  4375 D BluetoothAdapterProperties: Name is: Nexus 6
,08-13 18:41:03.736  4359  4375 D BluetoothAdapterProperties: Scan Mode:20
,08-13 18:41:03.737  4359  4375 D BluetoothAdapterProperties: Discoverable Timeout:120
08-13 18:41:03.737  4359  4375 D bt_hci  : do_postload posting postload work item
08-13 18:41:03.738  4359  4379 I bt_hci  : event_postload
08-13 18:41:03.738  4359  4379 I bt_vendor: sco_config_cb
,08-13 18:41:03.738  4359  4379 I bt_hci  : sco_config_callback postload finished.
08-13 18:41:03.739  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:03.740  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:03.741  4359  4375 D bt_bte_conf: Device ID record 1 : primary
,08-13 18:41:03.741  4359  4375 D bt_bte_conf:   vendorId            = 000f
08-13 18:41:03.741  4359  4375 D bt_bte_conf:   vendorIdSource      = 0001
08-13 18:41:03.741  4359  4375 D bt_bte_conf:   product             = 1200
08-13 18:41:03.741  4359  4375 D bt_bte_conf:   version             = 1436
08-13 18:41:03.742  4359  4375 D bt_bte_conf:   clientExecutableURL = 
08-13 18:41:03.742  4359  4375 D bt_bte_conf:   serviceDescription  = 
08-13 18:41:03.742  4359  4375 D bt_bte_conf:   documentationURL    = 
,08-13 18:41:03.742  4359  4375 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-13 18:41:03.743  4359  4372 D bt_stack_manager: event_start_up_stack finished
08-13 18:41:03.743  4359  4371 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-13 18:41:03.744  4359  4371 D BluetoothAdapterProperties: Setting state to 15
,08-13 18:41:03.744  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-13 18:41:03.745  4359  4371 I BluetoothAdapterState: Entering BleOnState
,08-13 18:41:03.747  4359  4379 I bt_vendor: low_power_mode_cb
,08-13 18:41:03.749  4359  4371 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-13 18:41:03.749  4359  4371 D BluetoothAdapterProperties: Setting state to 11
,08-13 18:41:03.749  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-13 18:41:03.755  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:41:03.757  4359  4359 D HeadsetService: Received start request. Starting profile...
08-13 18:41:03.760  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:03.762  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:03.767  4359  4359 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-13 18:41:03.768  4359  4359 D HeadsetStateMachine: make
,08-13 18:41:03.770  4359  4371 I BluetoothAdapterState: Entering PendingCommandState
,08-13 18:41:03.777  4359  4359 D HeadsetStateMachine: max_hf_connections = 1
,08-13 18:41:03.777  4359  4359 I bt_bluedroid: get_profile_interface handsfree
08-13 18:41:03.777  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-13 18:41:03.777  4359  4375 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-13 18:41:03.782  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:41:03.783  4359  4359 D A2dpService: Received start request. Starting profile...
,08-13 18:41:03.784  4359  4359 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-13 18:41:03.784  4359  4359 I bt_bluedroid: get_profile_interface avrcp
,08-13 18:41:03.793  4359  4359 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-13 18:41:03.794  4359  4359 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-13 18:41:03.794  4359  4359 D A2dpStateMachine: make
,08-13 18:41:03.795  4359  4359 I bt_bluedroid: get_profile_interface a2dp
08-13 18:41:03.796  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-13 18:41:03.799  4359  4390 D A2dpStateMachine: Enter Disconnected: -2
,08-13 18:41:03.800  4359  4359 I BluetoothHidServiceJni: classInitNative: succeeds
,08-13 18:41:03.801  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:41:03.802  4359  4359 D HidService: Received start request. Starting profile...
08-13 18:41:03.802  4359  4359 I bt_bluedroid: get_profile_interface hidhost
08-13 18:41:03.802  4359  4359 D HidService: setHidService(): set to: null
,08-13 18:41:03.802  4359  4375 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ea3e5
08-13 18:41:03.803  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-13 18:41:03.803  4359  4359 I BluetoothHealthServiceJni: classInitNative: succeeds
08-13 18:41:03.804  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:41:03.805  4359  4359 D HealthService: Received start request. Starting profile...
,08-13 18:41:03.806  4359  4359 I bt_bluedroid: get_profile_interface health
08-13 18:41:03.807  4359  4359 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-13 18:41:03.808  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
,08-13 18:41:03.808  4359  4359 D PanService: Received start request. Starting profile...
08-13 18:41:03.808  4359  4359 D BluetoothPanServiceJni: initializeNative(L110): pan
08-13 18:41:03.809  4359  4359 I bt_bluedroid: get_profile_interface pan
08-13 18:41:03.809  4359  4375 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-13 18:41:03.815  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-13 18:41:03.816  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
08-13 18:41:03.816  4359  4359 D BluetoothMapService: Received start request. Starting profile...
08-13 18:41:03.816  4359  4359 D BluetoothMapService: start()
,08-13 18:41:03.819  4359  4359 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-13 18:41:03.820  4359  4359 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-13 18:41:03.820  4359  4359 D BluetoothMapAppObserver: createReceiver()
,08-13 18:41:03.821  4359  4359 D BluetoothMapAppObserver: initObservers()
08-13 18:41:03.822  4359  4359 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-13 18:41:03.829  4359  4359 V BluetoothAdapterState: isTurningOff()=false
08-13 18:41:03.830  4359  4359 V BluetoothAdapterState: isTurningOn()=true
,08-13 18:41:03.830  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:41:03.830  4359  4388 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-13 18:41:03.830  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isTurningOn()=true
08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isTurningOff()=false
08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isTurningOn()=true
08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:41:03.832  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:41:03.833  4359  4359 V BluetoothAdapterState: isTurningOff()=false
08-13 18:41:03.833  4359  4359 V BluetoothAdapterState: isTurningOn()=true
08-13 18:41:03.833  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:41:03.833  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:41:03.833  4359  4359 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:41:03.834  4359  4359 V BluetoothAdapterState: isTurningOn()=true
08-13 18:41:03.834  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
,08-13 18:41:03.834  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,08-13 18:41:03.835  4359  4359 V BluetoothAdapterState: isTurningOff()=false
,08-13 18:41:03.836  4359  4359 V BluetoothAdapterState: isTurningOn()=true
08-13 18:41:03.836  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
08-13 18:41:03.836  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
08-13 18:41:03.836  4359  4371 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-13 18:41:03.836  4359  4371 D BluetoothAdapterProperties: ScanMode =  20
08-13 18:41:03.836  4359  4371 D BluetoothAdapterProperties: State =  11
08-13 18:41:03.838  4359  4375 D BluetoothAdapterProperties: Scan Mode:21
08-13 18:41:03.838  4359  4375 D BluetoothAdapterProperties: Discoverable Timeout:120
08-13 18:41:03.839  4359  4371 D BluetoothAdapterProperties: Setting state to 12
,08-13 18:41:03.839  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-13 18:41:03.839  4044  4056 D BluetoothMap: onBluetoothStateChange: up=true
08-13 18:41:03.840  4359  4371 I BluetoothAdapterState: Entering OnState
,08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:41:03.843  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-13 18:41:03.844  1925  2278 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:41:03.844   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-13 18:41:03.845  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:41:03.845  1372  1400 D BluetoothPan: onBluetoothStateChange on: true
,08-13 18:41:03.846   872   872 D BluetoothA2dp: Proxy object connected
,08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:41:03.849  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:41:03.849  4359  4359 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-13 18:41:03.849  1372  1397 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-13 18:41:03.850  4359  4359 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-13 18:41:03.851  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:41:03.852  4044  4055 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:41:03.852  4359  4359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:41:03.853  1372  1399 D BluetoothMap: onBluetoothStateChange: up=true
08-13 18:41:03.855  4359  4359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-13 18:41:03.856  4044  4056 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-13 18:41:03.856  1372  1372 D BluetoothMap: Proxy object connected
08-13 18:41:03.856  1372  1372 D MapProfile: Bluetooth service connected
08-13 18:41:03.856  1372  1372 D BluetoothMap: getConnectedDevices()
08-13 18:41:03.857  4359  4359 D ObexServerSockets: Succeed to create listening sockets 
08-13 18:41:03.857  4359  4359 D ObexServerSockets0: startAccept()
08-13 18:41:03.857  4359  4359 D ObexServerSockets0: prepareForNewConnect()
,08-13 18:41:03.858  1372  1400 D BluetoothPbap: onBluetoothStateChange: up=true
08-13 18:41:03.859   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:41:03.859  4359  4359 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-13 18:41:03.860  1372  1397 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-13 18:41:03.860  4359  4359 D BluetoothSdpJni: SDP Create record success - handle: 0
08-13 18:41:03.861  4359  4396 D ObexServerSockets0: Accepting socket connection...
,08-13 18:41:03.862  4359  4397 D ObexServerSockets0: Accepting socket connection...
,08-13 18:41:03.862  1372  1372 D BluetoothA2dp: Proxy object connected
08-13 18:41:03.862   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:41:03.862   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-13 18:41:03.863  4044  4055 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-13 18:41:03.864  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
,08-13 18:41:03.864  1372  1372 D PanProfile: Bluetooth service connected
08-13 18:41:03.864  1372  1372 D BluetoothInputDevice: Proxy object connected
08-13 18:41:03.864  1372  1372 D HidProfile: Bluetooth service connected
08-13 18:41:03.865  4044  4056 D BluetoothPan: onBluetoothStateChange on: true
,08-13 18:41:03.867  1372  1399 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-13 18:41:03.868  4044  4055 D BluetoothPbap: onBluetoothStateChange: up=true
,08-13 18:41:03.870  4044  4044 D BluetoothMap: Proxy object connected
,08-13 18:41:03.870  4044  4044 D MapProfile: Bluetooth service connected
,08-13 18:41:03.870  4044  4044 D BluetoothMap: getConnectedDevices()
,08-13 18:41:03.870   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-13 18:41:03.872  4359  4359 D BluetoothMapService: onReceive
08-13 18:41:03.872  4359  4359 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-13 18:41:03.872  4359  4359 D BluetoothMapService: STATE_ON
08-13 18:41:03.873  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:03.874  4044  4044 D BluetoothA2dp: Proxy object connected
,08-13 18:41:03.874  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:03.876  4044  4044 D BluetoothInputDevice: Proxy object connected
08-13 18:41:03.876  4044  4044 D HidProfile: Bluetooth service connected
08-13 18:41:03.878  4044  4044 D BluetoothPan: BluetoothPAN Proxy object connected
08-13 18:41:03.878  4044  4044 D PanProfile: Bluetooth service connected
,08-13 18:41:03.883  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-13 18:41:03.896  1530  1530 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-13 18:41:03.897  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-13 18:41:03.905  1372  1372 D BluetoothPbap: Proxy object connected
,08-13 18:41:03.905  4044  4044 D BluetoothPbap: Proxy object connected
08-13 18:41:03.905  4044  4044 D PbapServerProfile: Bluetooth service connected
08-13 18:41:03.905  4359  4359 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-13 18:41:03.905  4359  4359 D ObexServerSockets0: prepareForNewConnect()
08-13 18:41:03.905  1372  1372 D PbapServerProfile: Bluetooth service connected
,08-13 18:41:03.917  4359  4402 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:41:03.942  4359  4406 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:41:03.945  4359  4406 I BtOppRfcommListener: Accept thread started.
,08-13 18:41:03.947   872   872 D BluetoothHeadset: Proxy object connected
,08-13 18:41:03.948  1372  1399 D BluetoothHeadset: Proxy object connected
08-13 18:41:03.949  1925  1947 D BluetoothHeadset: Proxy object connected
08-13 18:41:03.948  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-13 18:41:03.949  4044  4056 D BluetoothHeadset: Proxy object connected
,08-13 18:41:03.949   872   872 D BluetoothHeadset: Proxy object connected
08-13 18:41:03.949  4044  4044 D HeadsetProfile: Bluetooth service connected
08-13 18:41:03.949   872   872 D BluetoothHeadset: Proxy object connected
,08-13 18:41:03.953  4044  4055 D BluetoothHeadset: Proxy object connected
08-13 18:41:03.953  4044  4044 D HeadsetProfile: Bluetooth service connected
,08-13 18:41:03.960   872   889 D BluetoothHeadset: Proxy object connected
,08-13 18:41:03.961   872   889 D BluetoothHeadset: Proxy object connected
,08-13 18:41:03.961   872   889 D BluetoothHeadset: Proxy object connected
,08-13 18:41:03.968  1372  1397 D BluetoothHeadset: Proxy object connected
08-13 18:41:03.968  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:41:04.109  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:41:04.115  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:41:04.117  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:04.118  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@666520b removed from the list
08-13 18:41:04.119  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
,08-13 18:41:04.119  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:04.120  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:04.125  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-13 18:41:04.125  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61278e8 added. We now have 4 listener(s)
,08-13 18:41:04.125  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:41:04.132   872  2002 D WifiService: setWifiEnabled: false pid=3984, uid=10000
,08-13 18:41:04.133   872  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-13 18:41:04.143  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:04.144   872  3150 D WifiService: setWifiEnabled: true pid=3984, uid=10000
,08-13 18:41:04.145   872  3150 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-13 18:41:04.158   872  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:41:04.175  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:41:04.182  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:41:04.190  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:41:04.192   872  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-13 18:41:04.193   872  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-13 18:41:04.194   872  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-13 18:41:04.195   872  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-13 18:41:04.195   872  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-13 18:41:04.195   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-13 18:41:04.195   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-13 18:41:04.197  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:41:04.207   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-13 18:41:04.207   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-13 18:41:04.209   372   870 D CommandListener: Setting iface cfg
,08-13 18:41:04.259   872  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-13 18:41:04.259   872  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-13 18:41:04.266   872  1316 E native  : do suspend true
,08-13 18:41:04.280   872  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-13 18:41:04.281   872  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-13 18:41:04.290   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-13 18:41:05.688   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-13 18:41:05.831   872  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.31 rxSuccessRate=18.81 delta 1000 -> 994
,08-13 18:41:05.834   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-13 18:41:05.835   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-13 18:41:05.858   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-13 18:41:05.923   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-13 18:41:05.925  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-13 18:41:06.162  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-13 18:41:06.168  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-13 18:41:06.170  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:06.170  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61278e8 removed from the list
08-13 18:41:06.171  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:06.171  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:41:06.171  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:06.355  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-13 18:41:06.393  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-13 18:41:06.395  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-13 18:41:06.401   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-13 18:41:06.414   872  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-13 18:41:06.414   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-13 18:41:06.414   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-13 18:41:06.436   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-13 18:41:06.452   372   870 D CommandListener: Setting iface cfg
,08-13 18:41:06.454   872  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,08-13 18:41:06.463   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-13 18:41:06.489   872  4416 D DhcpClient: Receive thread started
,08-13 18:41:06.575   872  1316 E native  : do suspend false
,08-13 18:41:06.595   872  1845 D DhcpClient: Broadcasting DHCPDISCOVER
,08-13 18:41:06.608   872  4416 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172771, domain null
,08-13 18:41:06.609   872  1845 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172771 seconds
,08-13 18:41:06.613   872  1845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-13 18:41:06.628   872  4416 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-13 18:41:06.629   872  1845 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-13 18:41:06.634   372   870 D CommandListener: Setting iface cfg
,08-13 18:41:06.645   872  1845 D DhcpClient: Scheduling renewal in 86399s
,08-13 18:41:06.646   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[],
,08-13 18:41:06.652   872  1316 E native  : do suspend true
,08-13 18:41:06.676   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-13 18:41:06.679   872  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-13 18:41:06.681   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-13 18:41:06.685   872  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-13 18:41:06.693   872  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-13 18:41:06.762   872  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-13 18:41:06.763   872  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-13 18:41:06.766   872  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-13 18:41:06.769   872  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-13 18:41:06.772   872  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-13 18:41:06.788   872  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-13 18:41:06.793   872  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-13 18:41:06.793   872  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-13 18:41:06.793   872  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-13 18:41:06.793   872  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-13 18:41:06.793   872  1318 D ConnectivityService:    accepting network in place of null
08-13 18:41:06.794   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-13 18:41:06.794   872  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-13 18:41:06.807   872  4415 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411489, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-13 18:41:06.845   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:41:06.876   872  4414 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.206,2a00:1450:4001:811::200e
,08-13 18:41:06.882   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-13 18:41:06.890   872  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-13 18:41:06.890   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:41:06.897   872  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-13 18:41:06.899   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:06.917  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-13 18:41:06.921  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:06.926  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:41:06.928  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:41:06.930  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-13 18:41:06.941  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-13 18:41:06.945   872  4414 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 13 Aug 2016 16:41:06 GMT], X-Android-Received-Millis=[1471106466944], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471106466921]}
,08-13 18:41:06.947  1756  1756 D SystemUpdateService: onCreate
,08-13 18:41:06.948   872  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-13 18:41:06.948   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-13 18:41:06.948   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-13 18:41:06.949   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-13 18:41:06.953  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-13 18:41:06.972  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-13 18:41:06.981  1756  4426 I SystemUpdateService: active receiver: enabled
,08-13 18:41:06.984  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-13 18:41:06.985  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-13 18:41:06.987  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-13 18:41:06.994  1756  4428 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-13 18:41:06.994  1756  4428 W BaseAppContext: Using Auth Proxy for data requests.
,08-13 18:41:06.994  4125  4125 D SprintDMHelper: simOperator: 
,08-13 18:41:06.994  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-13 18:41:06.995  1756  4428 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-13 18:41:06.998  1756  2416 I iu.UploadsManager: num queued entries: 0
,08-13 18:41:07.015  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:41:07.025  1530  1530 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-13 18:41:07.030  1756  2416 I iu.UploadsManager: num updated entries: 0
,08-13 18:41:07.037  1756  4426 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-13 18:41:07.053  1756  2416 I iu.SyncManager: NEXT; no task
,08-13 18:41:07.062  1756  4426 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-13 18:41:07.062  1756  4426 I SystemUpdateService: now status is 0 (complete)
08-13 18:41:07.062  1756  4426 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-13 18:41:07.062  1756  4426 I SystemUpdateService: file has been verified
,08-13 18:41:07.063  1756  4426 I SystemUpdateService: OTA package size = 12249756
,08-13 18:41:07.075  1756  4426 I SystemUpdateService: showing system update notification
,08-13 18:41:07.089  1530  1546 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-13 18:41:07.089  1530  1546 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-13 18:41:07.090  1530  1546 I GLSUser : [GLSUser] Extracting token using key: Auth
08-13 18:41:07.090  1530  1546 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-13 18:41:07.109  1756  4428 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-13 18:41:07.114  1756  1756 D SystemUpdateService: onDestroy
,08-13 18:41:07.826  4096  4431 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-13 18:41:07.889   872  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-13 18:41:11.183  3984  4437 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-13 18:41:11.184  3984  4437 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-13 18:41:14.192  3984  4438 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-13 18:41:14.193  3984  4437 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-13 18:41:14.193  3984  4438 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-13 18:41:14.193  3984  4437 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-13 18:41:14.194  3984  4437 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-13 18:41:14.194  3984  4438 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-13 18:41:14.196  3984  4438 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-13 18:41:14.196  3984  4437 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-13 18:41:14.198  3984  4437 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-13 18:41:14.200  3984  4438 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-13 18:41:14.206  3984  4441 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: OutgoingSocketThread/Sender)
08-13 18:41:14.207  3984  4442 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: OutgoingSocketThread/Receiver)
,08-13 18:41:14.209  3984  4440 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: IncomingSocketThread/Sender)
08-13 18:41:14.209  3984  4442 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 421, thread name: OutgoingSocketThread/Receiver)
08-13 18:41:14.210  3984  4442 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-13 18:41:14.210  3984  4442 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 421, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-13 18:41:14.212  3984  4443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: IncomingSocketThread/Receiver)
,08-13 18:41:14.213  3984  4443 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 420, thread name: IncomingSocketThread/Receiver)
08-13 18:41:14.214  3984  4443 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-13 18:41:14.214  3984  4443 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-13 18:41:14.800   872  1318 D ConnectivityService: handlePromptUnvalidated 102
,08-13 18:41:22.192  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-13 18:41:22.194  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-13 18:41:22.202  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9282add Bundle[{}]
,08-13 18:41:22.203  3984  4031 I io.jxcore.node.LifeCycleMonitor: start: OK
08-13 18:41:22.204  3984  4031 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-13 18:41:22.206  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-13 18:41:22.209  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-13 18:41:22.210  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-13 18:41:22.210  3984  4031 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-13 18:41:32.230  3984  4031 I System.out: Running OutgoingSocketThread
,08-13 18:41:32.235  3984  4446 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-13 18:41:32.235  3984  4446 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-13 18:41:35.243  3984  4447 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-13 18:41:35.243  3984  4447 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-13 18:41:35.244  3984  4446 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-13 18:41:35.244  3984  4447 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-13 18:41:35.244  3984  4446 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-13 18:41:35.245  3984  4446 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-13 18:41:35.245  3984  4447 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-13 18:41:35.246  3984  4446 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-13 18:41:35.248  3984  4447 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-13 18:41:35.252  3984  4449 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Sender)
,08-13 18:41:35.255  3984  4446 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-13 18:41:35.257  3984  4450 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Sender)
,08-13 18:41:35.259  3984  4451 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Receiver)
08-13 18:41:35.261  3984  4451 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: IncomingSocketThread/Receiver)
,08-13 18:41:35.261  3984  4451 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-13 18:41:35.261  3984  4452 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Receiver)
08-13 18:41:35.261  3984  4451 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-13 18:41:35.262  3984  4452 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: OutgoingSocketThread/Receiver)
,08-13 18:41:35.263  3984  4452 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-13 18:41:35.264  3984  4452 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-13 18:41:43.246  3984  4031 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-13 18:41:43.248  3984  4031 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-13 18:41:43.249  3984  4031 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 443)
,08-13 18:41:48.259  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-13 18:41:48.259  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2245b01 added. We now have 3 listener(s)
,08-13 18:41:48.267  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-13 18:41:48.267  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:41:48.268  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:41:48.268  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:41:48.269  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb3da6 added. We now have 4 listener(s)
08-13 18:41:48.269  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:41:48.271  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-13 18:41:48.281  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:48.294  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:41:48.299  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:41:48.300  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:41:48.301  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:41:48.301  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:41:48.302  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:41:48.302  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-13 18:41:48.302  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:48.303  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:41:48.303  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:48.303  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-13 18:41:48.303  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2245b01 removed from the list
08-13 18:41:48.303  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:48.305  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb3da6 removed from the list
,08-13 18:41:48.306  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:48.307  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:48.308  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:48.310  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:48.310  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:48.313  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:41:48.313  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:48.313  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:48.313  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb3da6 not in the list
08-13 18:41:48.313  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:41:48.313  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:48.314  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:48.314  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:41:48.314  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:48.314  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb3da6 not in the list
08-13 18:41:48.314  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:48.315  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:41:48.315  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:48.315  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2245b01 not in the list
08-13 18:41:48.315  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-13 18:41:48.316  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0a3b94 added. We now have 3 listener(s)
08-13 18:41:48.317  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-13 18:41:48.318  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:41:48.318  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:41:48.318  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:41:48.318  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faa63d added. We now have 4 listener(s)
08-13 18:41:48.318  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-13 18:41:48.318  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-13 18:41:48.321  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:48.328  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:41:48.330  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:48.331  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-13 18:41:48.331  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:41:48.331  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-13 18:41:48.331  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-13 18:41:48.331  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:41:48.331  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-13 18:41:48.333  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:48.338  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-13 18:41:48.338  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-13 18:41:48.339  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:48.343  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-13 18:41:48.344  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-13 18:41:48.344  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-13 18:41:48.349  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-13 18:41:48.349  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-13 18:41:48.349  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-13 18:41:48.350  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:41:48.353  4359  4369 D BtGatt.GattService: registerClient() - UUID=d973b860-60a8-4069-8b48-e905637b7acc
,08-13 18:41:48.355  4359  4375 D BtGatt.GattService: onClientRegistered() - UUID=d973b860-60a8-4069-8b48-e905637b7acc, clientIf=5
,08-13 18:41:48.356  3984  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-13 18:41:48.358  4359  4370 D BtGatt.GattService: start scan with filters
,08-13 18:41:48.362  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-13 18:41:48.362  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-13 18:41:48.362  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-13 18:41:48.363  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-13 18:41:48.363  4359  4378 D BtGatt.ScanManager: handling starting scan
,08-13 18:41:48.366  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-13 18:41:48.366  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-13 18:41:48.366  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-13 18:41:48.367  4359  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b4d5a1
08-13 18:41:48.368  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-13 18:41:48.373  3984  4031 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-13 18:41:48.373  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-13 18:41:48.373  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-13 18:41:48.373  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:48.373  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-13 18:41:48.373  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-13 18:41:48.373  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-13 18:41:48.374  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-13 18:41:48.374  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-13 18:41:48.374  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-13 18:41:48.374  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-13 18:41:48.375  3984  4031 D BluetoothAdapter: STATE_ON
08-13 18:41:48.376  4359  4369 D BtGatt.GattService: stopScan() - queue size =1
,08-13 18:41:48.378  4359  4395 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-13 18:41:48.379  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-13 18:41:48.379  4359  4375 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-13 18:41:48.379  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-13 18:41:48.379  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:41:48.379  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-13 18:41:48.379  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-13 18:41:48.379  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-13 18:41:48.380  4359  4378 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-13 18:41:48.381  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:41:48.381  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-13 18:41:48.381  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-13 18:41:48.381  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-13 18:41:48.381  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-13 18:41:48.386  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-13 18:41:48.386  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:41:48.387  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-13 18:41:48.390  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-13 18:41:48.390  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:41:48.391  4359  4378 D BtGatt.ScanManager: Starting BLE batch scan
08-13 18:41:48.391  4359  4378 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-13 18:41:48.405  4359  4375 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-13 18:41:48.405  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:48.412  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-13 18:41:48.413  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:48.421  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-13 18:41:48.422  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:48.422  4359  4378 D BtGatt.ScanManager: stopping BLe Batch
,08-13 18:41:48.431  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-13 18:41:48.431  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:41:48.432  4359  4378 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:41:48.448  4359  4375 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-13 18:41:48.449  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:48.888  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-13 18:41:48.888  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:41:48.889  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:41:51.388  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-13 18:41:51.389  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:41:51.389  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:41:51.390  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:51.390  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:51.390  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:41:51.391  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-13 18:41:51.391  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0a3b94 removed from the list
08-13 18:41:51.392  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:51.392  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faa63d removed from the list
08-13 18:41:51.392  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:51.392  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:51.395  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:51.395  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:51.398  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:41:51.399  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:51.399  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:51.399  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faa63d not in the list
,08-13 18:41:51.400  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:51.400  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:51.403  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:51.403  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:41:51.403  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:51.404  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faa63d not in the list
08-13 18:41:51.404  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-13 18:41:51.404  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:51.405  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:51.405  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0a3b94 not in the list
08-13 18:41:51.407  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-13 18:41:51.408  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a825b7e added. We now have 3 listener(s)
,08-13 18:41:51.412  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-13 18:41:51.413  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:41:51.413  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:41:51.413  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-13 18:41:51.413  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d588df added. We now have 4 listener(s)
08-13 18:41:51.413  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-13 18:41:51.414  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-13 18:41:51.417  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:51.423  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:41:51.426  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:41:51.426  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-13 18:41:51.426  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-13 18:41:51.427  3984  4031 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-13 18:41:51.427  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-13 18:41:51.428  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-13 18:41:51.428  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-13 18:41:51.428  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-13 18:41:51.428  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:51.432  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-13 18:41:51.433  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-13 18:41:51.433  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:51.433  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-13 18:41:51.434  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-13 18:41:51.434  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-13 18:41:51.434  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-13 18:41:51.434  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-13 18:41:51.436  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:51.436  3984  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-13 18:41:51.441  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-13 18:41:51.441  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-13 18:41:51.442  3984  4457 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-13 18:41:51.447  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-13 18:41:51.448  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-13 18:41:51.448  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-13 18:41:51.449  3984  4457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-13 18:41:51.450  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-13 18:41:51.450  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-13 18:41:51.451  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-13 18:41:51.452  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-13 18:41:51.452  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-13 18:41:51.452  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-13 18:41:51.453  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:41:51.455  4359  4387 D BtGatt.GattService: registerClient() - UUID=0ab9cfa9-7f23-4105-afe8-aa91f88772f0
,08-13 18:41:51.456  4359  4375 D BtGatt.GattService: onClientRegistered() - UUID=0ab9cfa9-7f23-4105-afe8-aa91f88772f0, clientIf=5
08-13 18:41:51.456  3984  3995 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-13 18:41:51.458  4359  4377 D BtGatt.AdvertiseManager: message : 0
,08-13 18:41:51.460  4359  4377 D BtGatt.AdvertiseManager: starting multi advertising
,08-13 18:41:51.469  4359  4375 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-13 18:41:51.476  4359  4375 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-13 18:41:51.477  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-13 18:41:51.478  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-13 18:41:51.480  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-13 18:41:51.482  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-13 18:41:51.483  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-13 18:41:51.483  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-13 18:41:51.483  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-13 18:41:51.483  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-13 18:41:51.483  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-13 18:41:51.487  3984  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-13 18:41:51.487  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-13 18:41:51.988  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-13 18:41:51.989  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-13 18:41:51.989  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:41:54.484  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-13 18:41:54.485  3984  4031 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:41:54.486  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:41:54.487  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-13 18:41:54.487  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-13 18:41:54.487  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-13 18:41:54.488  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-13 18:41:54.488  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-13 18:41:54.489  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-13 18:41:54.489  3984  4457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-13 18:41:54.489  3984  4031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-13 18:41:54.489  3984  4457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-13 18:41:54.490  3984  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-13 18:41:54.490  3984  4457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-13 18:41:54.490  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-13 18:41:54.491  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-13 18:41:54.491  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-13 18:41:54.491  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-13 18:41:54.491  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-13 18:41:54.494  3984  4031 D BluetoothAdapter: STATE_ON
08-13 18:41:54.494  3984  4031 D BluetoothLeScanner: could not find callback wrapper
08-13 18:41:54.495  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-13 18:41:54.495  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-13 18:41:54.497  4359  4377 D BtGatt.AdvertiseManager: message : 1
08-13 18:41:54.499  4359  4377 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-13 18:41:54.508  4359  4375 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-13 18:41:54.508  4359  4375 D BtGatt.GattService: Client app is not null!
,08-13 18:41:54.510  4359  4370 D BtGatt.GattService: unregisterClient() - clientIf=5
08-13 18:41:54.511  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-13 18:41:54.511  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-13 18:41:54.511  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-13 18:41:54.512  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-13 18:41:54.512  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-13 18:41:54.514  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:41:54.514  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-13 18:41:54.515  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-13 18:41:54.515  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-13 18:41:54.518  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:41:54.518  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-13 18:41:54.519  3984  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-13 18:41:54.519  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:41:54.519  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-13 18:41:54.520  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:41:54.520  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:54.520  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:54.521  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:41:54.521  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-13 18:41:54.521  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a825b7e removed from the list
08-13 18:41:54.521  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:54.522  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d588df removed from the list
08-13 18:41:54.522  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
,08-13 18:41:54.522  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:54.523  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:54.524  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:54.526  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:41:54.526  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-13 18:41:54.526  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:54.526  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d588df not in the list
08-13 18:41:54.526  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:54.526  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:54.528  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:54.528  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:41:54.528  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:54.529  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d588df not in the list
08-13 18:41:54.529  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:54.529  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:54.529  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:54.530  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a825b7e not in the list
08-13 18:41:54.532  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-13 18:41:54.532  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@249ec18 added. We now have 3 listener(s)
08-13 18:41:54.538  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-13 18:41:54.538  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:41:54.538  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:41:54.539  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:41:54.539  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f90671 added. We now have 4 listener(s)
08-13 18:41:54.539  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-13 18:41:54.541  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-13 18:41:54.546  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:54.554  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-13 18:41:54.557  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:41:54.557  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:41:54.557  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:41:54.557  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-13 18:41:54.557  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-13 18:41:54.557  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:54.557  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-13 18:41:54.561  3984  4031 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-13 18:41:54.562  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-13 18:41:54.562  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:54.567  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-13 18:41:54.567  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-13 18:41:54.568  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-13 18:41:54.569  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-13 18:41:54.574  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-13 18:41:54.574  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-13 18:41:54.574  3984  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-13 18:41:54.575  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:41:54.579  4359  4387 D BtGatt.GattService: registerClient() - UUID=f642deb3-211e-44d1-9abc-4d87b9b117b2
,08-13 18:41:54.580  4359  4375 D BtGatt.GattService: onClientRegistered() - UUID=f642deb3-211e-44d1-9abc-4d87b9b117b2, clientIf=5
08-13 18:41:54.581  3984  3994 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-13 18:41:54.581  4359  4370 D BtGatt.GattService: start scan with filters
,08-13 18:41:54.585  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-13 18:41:54.586  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-13 18:41:54.586  4359  4378 D BtGatt.ScanManager: handling starting scan
08-13 18:41:54.586  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-13 18:41:54.586  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-13 18:41:54.592  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-13 18:41:54.593  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-13 18:41:54.593  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-13 18:41:54.597  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-13 18:41:54.600  4359  4375 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-13 18:41:54.600  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:54.600  4359  4378 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-13 18:41:54.614  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-13 18:41:54.615  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:54.615  4359  4378 D BtGatt.ScanManager: Starting BLE batch scan
,08-13 18:41:54.615  4359  4378 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-13 18:41:54.644  4359  4375 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-13 18:41:54.644  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:54.665  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-13 18:41:54.665  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:55.021  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-13 18:41:55.093  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-13 18:41:55.093  3984  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:41:55.094  3984  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-13 18:41:56.167  4359  4359 D BtGatt.ScanManager: awakened up at time 460849
,08-13 18:41:56.171  4359  4378 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:41:56.219  4359  4375 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-13 18:41:56.220  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:41:56.221  4359  4375 D BtGatt.GattService: current time is 460903217950
,08-13 18:41:56.223  4359  4375 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-13 18:41:56.232  4359  4375 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-13 18:41:56.236  4359  4375 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-13 18:41:56.237  4359  4375 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-13 18:41:56.238  4359  4375 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-13 18:41:56.239  4359  4375 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-13 18:41:57.610  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:41:57.610  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-13 18:41:57.611  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-13 18:41:57.611  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-13 18:41:57.611  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-13 18:41:57.612  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-13 18:41:57.612  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-13 18:41:57.612  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-13 18:41:57.613  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-13 18:41:57.613  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-13 18:41:57.614  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-13 18:41:57.616  3984  4031 D BluetoothAdapter: STATE_ON
,08-13 18:41:57.619  4359  4398 D BtGatt.GattService: stopScan() - queue size =1
08-13 18:41:57.622  4359  4387 D BtGatt.GattService: unregisterClient() - clientIf=5
08-13 18:41:57.623  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-13 18:41:57.623  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-13 18:41:57.623  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-13 18:41:57.623  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-13 18:41:57.623  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-13 18:41:57.625  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:41:57.626  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-13 18:41:57.626  3984  4031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-13 18:41:57.626  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-13 18:41:57.626  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:41:57.628  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:57.628  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.629  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:41:57.629  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-13 18:41:57.629  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@249ec18 removed from the list
08-13 18:41:57.629  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:41:57.629  4359  4359 D BtGatt.ScanManager: awakened up at time 462312
08-13 18:41:57.632  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:57.632  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f90671 removed from the list
08-13 18:41:57.632  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:57.634  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.632  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-13 18:41:57.635  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-13 18:41:57.635  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.635  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.636  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:41:57.636  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:57.636  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-13 18:41:57.636  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f90671 not in the list
08-13 18:41:57.636  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.637  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.638  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:57.638  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-13 18:41:57.638  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:57.638  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f90671 not in the list
08-13 18:41:57.638  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:57.639  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.639  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.639  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@249ec18 not in the list
08-13 18:41:57.639  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-13 18:41:57.640  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:41:57.640  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-13 18:41:57.640  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e1e7e2 added. We now have 3 listener(s)
08-13 18:41:57.640  4359  4378 D BtGatt.ScanManager: stopping BLe Batch
08-13 18:41:57.642  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-13 18:41:57.642  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-13 18:41:57.642  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-13 18:41:57.644  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-13 18:41:57.644  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa2c773 added. We now have 4 listener(s)
08-13 18:41:57.644  3984  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-13 18:41:57.645  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-13 18:41:57.649  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-13 18:41:57.656  3984  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-13 18:41:57.656  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-13 18:41:57.656  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-13 18:41:57.657  4359  4378 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-13 18:41:57.660  3984  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-13 18:41:57.660  3984  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-13 18:41:57.663  3984  4031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-13 18:41:57.663  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-13 18:41:57.663  3984  4031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-13 18:41:57.663  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-13 18:41:57.663  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.664  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-13 18:41:57.664  3984  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-13 18:41:57.664  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:57.664  3984  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e1e7e2 removed from the list,
08-13 18:41:57.664  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:57.665  3984  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa2c773 removed from the list
08-13 18:41:57.666  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-13 18:41:57.667  3984  4031 D io.jxcore.node.ConnectivityMonitor: stop
08-13 18:41:57.667  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.668  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.669  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.669  4359  4375 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-13 18:41:57.669  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-13 18:41:57.670  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-13 18:41:57.671  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:57.671  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:57.671  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa2c773 not in the list
08-13 18:41:57.671  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-13 18:41:57.671  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-13 18:41:57.673  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-13 18:41:57.673  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-13 18:41:57.673  3984  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-13 18:41:57.673  3984  4031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa2c773 not in the list
08-13 18:41:57.674  3984  4031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-13 18:41:57.674  3984  4031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-13 18:41:57.674  3984  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-13 18:41:57.674  3984  4031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e1e7e2 not in the list
,08-13 18:41:58.136  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-13 18:42:02.678  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-13 18:42:02.678  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-13 18:42:02.679  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-13 18:42:02.679  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-13 18:42:02.680  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-13 18:42:02.680  3984  4031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-13 18:42:09.706  3984  4458 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
,08-13 18:42:11.704  3984  4031 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 452
08-13 18:42:11.705  3984  4031 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 452, name: My test thread name)
,08-13 18:42:11.710  3984  4459 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: My test thread name)
,08-13 18:42:11.711  3984  4459 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 453, thread name: My test thread name)
08-13 18:42:11.712  3984  4459 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 453, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-13 18:42:11.716  3984  4031 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-13 18:42:11.724  3984  4460 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: My test thread name)
,08-13 18:42:11.725  3984  4460 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 457, thread name: My test thread name): Test exception.
08-13 18:42:11.726  3984  4460 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-13 18:42:11.734  3984  4031 I jxcore-log: Total number of executed tests:  82
08-13 18:42:11.734  3984  4031 I jxcore-log: 
,08-13 18:42:11.734  3984  4031 I jxcore-log: Number of passed tests:  82
08-13 18:42:11.734  3984  4031 I jxcore-log: 
08-13 18:42:11.735  3984  4031 I jxcore-log: Number of failed tests:  0
08-13 18:42:11.735  3984  4031 I jxcore-log: 
,08-13 18:42:11.736  3984  4031 I jxcore-log: Number of ignored tests:  0
08-13 18:42:11.736  3984  4031 I jxcore-log: 
08-13 18:42:11.738  3984  4031 I jxcore-log: Total duration:  142353
08-13 18:42:11.738  3984  4031 I jxcore-log: 
08-13 18:42:11.739  3984  4031 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-13 18:42:11.739  3984  4031 I jxcore-log: 
,08-13 18:42:11.751  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.751  3984  4031 I jxcore-log: 
,08-13 18:42:11.764  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.764  3984  4031 I jxcore-log: 
,08-13 18:42:11.769  3984  3984 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-13 18:42:11.769  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.769  3984  4031 I jxcore-log: 
,08-13 18:42:11.773  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.773  3984  4031 I jxcore-log: 
,08-13 18:42:11.777  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-13 18:42:11.777  3984  4031 I jxcore-log: 
,08-13 18:42:11.782  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-13 18:42:11.782  3984  4031 I jxcore-log: 
,08-13 18:42:11.789  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.789  3984  4031 I jxcore-log: 
,08-13 18:42:11.795  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.795  3984  4031 I jxcore-log: 
,08-13 18:42:11.796  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-13 18:42:11.796  3984  4031 I jxcore-log: 
,08-13 18:42:11.797  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-13 18:42:11.797  3984  4031 I jxcore-log: 
08-13 18:42:11.797  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-13 18:42:11.797  3984  4031 I jxcore-log: 
08-13 18:42:11.798  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.798  3984  4031 I jxcore-log: 
,08-13 18:42:11.799  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.799  3984  4031 I jxcore-log: 
08-13 18:42:11.800  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.800  3984  4031 I jxcore-log: 
,08-13 18:42:11.801  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.801  3984  4031 I jxcore-log: 
08-13 18:42:11.802  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.802  3984  4031 I jxcore-log: 
,08-13 18:42:11.803  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.803  3984  4031 I jxcore-log: 
08-13 18:42:11.803  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.803  3984  4031 I jxcore-log: 
08-13 18:42:11.804  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.804  3984  4031 I jxcore-log: 
,08-13 18:42:11.805  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.805  3984  4031 I jxcore-log: 
08-13 18:42:11.806  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.806  3984  4031 I jxcore-log: 
,08-13 18:42:11.807  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.807  3984  4031 I jxcore-log: 
08-13 18:42:11.807  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.807  3984  4031 I jxcore-log: 
,08-13 18:42:11.808  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.808  3984  4031 I jxcore-log: 
08-13 18:42:11.809  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.809  3984  4031 I jxcore-log: 
,08-13 18:42:11.810  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.810  3984  4031 I jxcore-log: 
08-13 18:42:11.811  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.811  3984  4031 I jxcore-log: 
,08-13 18:42:11.811  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.811  3984  4031 I jxcore-log: 
08-13 18:42:11.812  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.812  3984  4031 I jxcore-log: 
08-13 18:42:11.813  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.813  3984  4031 I jxcore-log: 
08-13 18:42:11.814  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.814  3984  4031 I jxcore-log: 
08-13 18:42:11.814  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.814  3984  4031 I jxcore-log: 
,08-13 18:42:11.816  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.816  3984  4031 I jxcore-log: 
,08-13 18:42:11.816  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.816  3984  4031 I jxcore-log: 
,08-13 18:42:11.817  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.817  3984  4031 I jxcore-log: 
,08-13 18:42:11.818  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.818  3984  4031 I jxcore-log: 
,08-13 18:42:11.819  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.819  3984  4031 I jxcore-log: 
08-13 18:42:11.820  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.820  3984  4031 I jxcore-log: 
,08-13 18:42:11.821  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.821  3984  4031 I jxcore-log: 
08-13 18:42:11.821  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.821  3984  4031 I jxcore-log: 
,08-13 18:42:11.822  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-13 18:42:11.822  3984  4031 I jxcore-log: 
,08-13 18:42:11.823  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.823  3984  4031 I jxcore-log: 
,08-13 18:42:11.824  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.824  3984  4031 I jxcore-log: 
,08-13 18:42:11.825  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-13 18:42:11.825  3984  4031 I jxcore-log: 
,08-13 18:42:11.825  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.825  3984  4031 I jxcore-log: 
,08-13 18:42:11.826  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.826  3984  4031 I jxcore-log: 
,08-13 18:42:11.827  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.827  3984  4031 I jxcore-log: 
08-13 18:42:11.828  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.828  3984  4031 I jxcore-log: 
,08-13 18:42:11.829  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-13 18:42:11.829  3984  4031 I jxcore-log: 
,08-13 18:42:11.829  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.829  3984  4031 I jxcore-log: 
08-13 18:42:11.830  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-13 18:42:11.830  3984  4031 I jxcore-log: 
08-13 18:42:11.831  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.831  3984  4031 I jxcore-log: 
,08-13 18:42:11.832  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-13 18:42:11.832  3984  4031 I jxcore-log: 
08-13 18:42:11.832  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-13 18:42:11.832  3984  4031 I jxcore-log: 
08-13 18:42:11.833  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-13 18:42:11.833  3984  4031 I jxcore-log: 
08-13 18:42:11.835  3984  4031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-13 18:42:11.835  3984  4031 I jxcore-log: 
,08-13 18:42:11.926  3984  4458 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-13 18:42:12.349  4461  4461 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-13 18:42:12.353  4461  4461 D AndroidRuntime: CheckJNI is OFF
,08-13 18:42:12.390  4461  4461 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-13 18:42:12.430  4461  4461 I Radio-JNI: register_android_hardware_Radio DONE
,08-13 18:42:12.452  4461  4461 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-13 18:42:12.466   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-13 18:42:12.466   872   885 I ActivityManager: Killing 3984:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-13 18:42:12.569   872  1386 I WindowState: WIN DEATH: Window{a9164a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-13 18:42:12.569   872  1317 D WifiService: Client connection lost with reason: 4
,08-13 18:42:12.571   872   883 D GraphicsStats: Buffer count: 2
,08-13 18:42:12.583   872   897 W PackageSettings: Skipping PackageSetting{1f60eca com.example.hello/10273} due to missing metadata
,08-13 18:42:12.624   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-13 18:42:12.624   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-13 18:42:12.625   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-13 18:42:12.625   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-13 18:42:12.625   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:42:12.625   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:42:12.625   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-13 18:42:12.625   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-13 18:42:12.626   872   885 I ActivityManager:   Force finishing activity ActivityRecord{d581faf u0 com.test.thalitest/.MainActivity t2}
,08-13 18:42:12.633   872   897 I art     : Starting a blocking GC Explicit
,08-13 18:42:12.646   872  2120 W ActivityManager: Spurious death for ProcessRecord{2cf3f79 0:com.test.thalitest/u0a0}, curProc for 3984: null
,08-13 18:42:12.688   872   897 I art     : Explicit concurrent mark sweep GC freed 54340(3MB) AllocSpace objects, 10(272KB) LOS objects, 33% free, 29MB/43MB, paused 763us total 53.365ms
,08-13 18:42:12.732   872   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-13 18:42:12.733  4461  4461 I art     : System.exit called, status: 0
08-13 18:42:12.734  4461  4461 I AndroidRuntime: VM exiting with result code 0.
,08-13 18:42:12.788   872   897 I ActivityManager: Start proc 4473:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-13 18:42:12.793   872   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-13 18:42:12.812   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-13 18:42:12.818  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
08-13 18:42:12.824  4359  4359 D BluetoothMapAppObserver: onReceive
08-13 18:42:12.824  4359  4359 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-13 18:42:12.833   872  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-13 18:42:12.837  2205  2324 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-13 18:42:12.845  1863  4487 I Keyboard.Facilitator.DecoderInitializer: run()
08-13 18:42:12.848  3700  3700 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-13 18:42:12.872  1863  4487 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-13 18:42:12.872  1863  4487 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-13 18:42:12.872  1863  4487 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-13 18:42:12.872  1863  4487 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-13 18:42:12.872  1863  4487 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-13 18:42:12.873  1863  4487 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-13 18:42:12.874  1863  4487 I Decoder : createOrResetDecoder
,08-13 18:42:12.893   872   883 I ActivityManager: Start proc 4490:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-13 18:42:12.903   872  1314 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-13 18:42:12.906   872   883 I ActivityManager: Killing 3752:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-13 18:42:12.911  1925  1925 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-13 18:42:12.912   872  2122 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3984 uid 10000
08-13 18:42:12.922  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-13 18:42:12.928   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-13 18:42:12.965  1938  1996 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-13 18:42:12.968   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-13 18:42:12.969   872   884 E PackageManager: Failed to write settings, restoring backup
08-13 18:42:12.969   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-13 18:42:12.969   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-13 18:42:12.969   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-13 18:42:12.969   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-13 18:42:12.969   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-13 18:42:12.969   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:42:12.969   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:42:12.969   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-13 18:42:12.970  1530  1530 I ConfigService: onCreate
,08-13 18:42:12.974   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-13 18:42:12.974   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-13 18:42:12.974   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-13 18:42:12.974   872   885 E DropBoxManagerService: 	... 13 more
,08-13 18:42:12.981   872  1905 I ActivityManager: Start proc 4503:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-13 18:42:12.982  1938  1996 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-13 18:42:12.982  1938  1996 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-13 18:42:12.982  1938  1996 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:42:12.982  1938  1996 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-13 18:42:12.984   872  2122 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-13 18:42:12.988   872  4508 E DropBoxManagerService: Can't write: system_app_crash
08-13 18:42:12.988   872  4508 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-13 18:42:12.988   872  4508 E DropBoxManagerService: 	... 5 more
,08-13 18:42:12.989  1938  1996 I Process : Sending signal. PID: 1938 SIG: 9
,08-13 18:42:13.008  1530  4502 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-13 18:42:13.008  1530  4502 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-13 18:42:13.011  4490  4490 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-13 18:42:13.014  1530  4502 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-13 18:42:13.016  1530  4502 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-13 18:42:13.042  1863  4487 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-13 18:42:13.066  1863  4487 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-13 18:42:13.068  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-13 18:42:13.068  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-13 18:42:13.070  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-13 18:42:13.071  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-13 18:42:13.072  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-13 18:42:13.072  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-13 18:42:13.075   872   882 D GraphicsStats: Buffer count: 1
08-13 18:42:13.075   872  1955 I WindowState: WIN DEATH: Window{ddcf9d8 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-13 18:42:13.085   872  2122 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1938) has died
08-13 18:42:13.086   872  2122 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-13 18:42:13.088   872  2122 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-13 18:42:13.091  1863  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-13 18:42:13.091  1863  4487 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-13 18:42:13.092  1863  4487 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-13 18:42:13.094  1863  4487 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-13 18:42:13.094  1863  4487 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-13 18:42:13.094  1863  4487 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-13 18:42:13.110   872   885 I ActivityManager: Start proc 4521:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-13 18:42:13.139  4490  4490 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-13 18:42:13.154  4521  4521 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:42:13.154  4521  4521 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-13 18:42:13.154  4521  4521 D AndroidRuntime: Shutting down VM
,08-13 18:42:13.157   872  1955 I ActivityManager: Start proc 4535:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-13 18:42:13.159  4490  4540 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-13 18:42:13.164  4521  4521 E AndroidRuntime: FATAL EXCEPTION: main
08-13 18:42:13.164  4521  4521 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4521
08-13 18:42:13.164  4521  4521 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-13 18:42:13.164  4521  4521 E AndroidRuntime: 	... 10 more
08-13 18:42:13.167   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-13 18:42:13.168  4521  4521 I Process : Sending signal. PID: 4521 SIG: 9
08-13 18:42:13.168   872  4546 E DropBoxManagerService: Can't write: system_app_crash
08-13 18:42:13.168   872  4546 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-13 18:42:13.168   872  4546 E DropBoxManagerService: 	... 5 more
,08-13 18:42:13.188  1756  4534 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-13 18:42:13.190  1756  4534 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-13 18:42:13.196  1756  4534 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-13 18:42:13.197  1756  4534 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-13 18:42:13.198   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4521) has died
,08-13 18:42:13.199   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-13 18:42:13.210  4535  4535 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-13 18:42:13.212   872   885 I ActivityManager: Start proc 4549:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-13 18:42:13.221   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
