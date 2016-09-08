#### Test 82912030aff0b78_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 15:22:12.499  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 15:22:12.500  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:22:12.537  1505  3633 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 15:22:12.537  1505  3633 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:22:12.538  1505  3633 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:22:12.538  1505  3633 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 15:22:12.563  3008  3848 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 15:22:12.563  3008  3848 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at blb.a(PG:3937)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at czp.a(PG:18188)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:22:12.563  3008  3848 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	... 12 more
09-08 15:22:12.563  3008  3848 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at fal.a(PG:38)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:22:12.563  3008  3848 E HttpOperation: 	... 14 more
09-08 15:22:12.607  1505  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 15:22:12.607  1505  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:22:12.607  1505  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:22:12.607  1505  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 15:22:12.620  3008  3848 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 15:22:12.620  3008  3848 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at hec.a(PG:42)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at hee.a(PG:102)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at czr.a(PG:65)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at kka.a(PG:108)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at czp.a(PG:19176)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:22:12.620  3008  3848 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	... 15 more
09-08 15:22:12.620  3008  3848 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at fal.a(PG:38)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:22:12.620  3008  3848 E HttpOperation: 	... 17 more
09-08 15:22:12.621  3008  3848 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 15:22:12.621  3008  3848 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at hec.a(PG:42)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at hee.a(PG:102)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at czr.a(PG:65)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at kka.a(PG:108)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	... 15 more
09-08 15:22:12.621  3008  3848 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at fal.a(PG:38)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 15:22:12.621  3008  3848 E ExperimentLoader: 	... 17 more
09-08 15:22:12.722   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 281689, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
09-08 15:22:13.135  3849  3849 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 15:22:13.139  3849  3849 D AndroidRuntime: CheckJNI is OFF
09-08 15:22:13.174  3849  3849 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 15:22:13.221  3849  3849 I Radio-JNI: register_android_hardware_Radio DONE
09-08 15:22:13.240  3849  3849 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 15:22:13.244   874  2274 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 15:22:13.309   874  2274 I ActivityManager: Start proc 3859:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 15:22:13.319  3849  3849 D AndroidRuntime: Shutting down VM
09-08 15:22:13.434  3859  3859 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 15:22:13.472  3859  3859 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 15:22:13.485  3859  3859 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 760-766)
09-08 15:22:13.485  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 15:22:13.506  3859  3859 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {43da4b7}
09-08 15:22:13.507  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 15:22:13.507  3859  3859 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 15:22:13.514  3859  3859 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 15:22:13.516  3859  3859 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 15:22:13.560  3859  3859 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 15:22:13.582  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 15:22:13.583  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 15:22:13.583  3859  3859 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 15:22:13.583  3859  3859 I Adreno  : Build Date                       : 10/20/15
09-08 15:22:13.583  3859  3859 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 15:22:13.583  3859  3859 I Adreno  : Local Branch                     : M14
09-08 15:22:13.583  3859  3859 I Adreno  : Remote Branch                    : 
09-08 15:22:13.583  3859  3859 I Adreno  : Remote Branch                    : 
09-08 15:22:13.583  3859  3859 I Adreno  : Reconstruct Branch               : 
,09-08 15:22:13.671   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48b17e:true
,09-08 15:22:13.743  3859  3859 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 15:22:13.764  3859  3859 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 15:22:13.852   874   887 W ActivityManager: Activity pause timeout for ActivityRecord{21d500b u0 com.test.thalitest/.MainActivity t4}
,09-08 15:22:13.865  3859  3896 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 15:22:13.885  3859  3883 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 15:22:13.953  3859  3896 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 15:22:14.012   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +661ms (total +746ms)
,09-08 15:22:14.020  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-08 15:22:14.121  3859  3859 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3859
,09-08 15:22:14.270  3859  3859 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 15:22:14.579  3859  3898 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1695614672
,09-08 15:22:14.611  3859  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 15:22:14.611  3859  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 15:22:14.611  3859  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 15:22:14.611  3859  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 15:22:14.611  3859  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 15:22:14.612  3859  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6564d5a added. We now have 1 listener(s)
,09-08 15:22:14.633  3859  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-08 15:22:14.634  3859  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 15:22:14.635  3859  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 15:22:14.635  3859  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE,
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 15:22:14.640  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 15:22:14.641  3859  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c8f081 added. We now have 1 listener(s)
09-08 15:22:14.641  3859  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:22:14.645   874  1318 D WifiService: New client listening to asynchronous messages
09-08 15:22:14.646  3859  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 15:22:14.646  3859  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 15:22:14.646  3859  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 15:22:14.646  3859  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 15:22:14.646  3859  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 15:22:14.650  3859  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:22:14.651  3859  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 15:22:14.659  3859  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:14.659  3859  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:22:14.660  3859  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 15:22:14.660  3859  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 15:22:14.663  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:22:14.663  3859  3898 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 15:22:14.665  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:14.700  3859  3859 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 15:22:15.864  3859  3905 W jxcore-log: Initializing JXcore engine
,09-08 15:22:15.864  3859  3905 W jxcore-log: JXcore engine is ready
,09-08 15:22:15.900  3905  3905 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 15:22:15.900  3905  3905 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11515]" dev="sockfs" ino=11515 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-08 15:22:15.900  3905  3905 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 15:22:15.900  3905  3905 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[29467]" dev="sockfs" ino=29467 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 15:22:15.915  3859  3905 W jxcore-log: Starting JXcore engine
,09-08 15:22:15.998  3859  3905 W jxcore-log: Platform android
09-08 15:22:15.998  3859  3905 W jxcore-log: 
,09-08 15:22:15.998  3859  3905 W jxcore-log: Process ARCH arm
09-08 15:22:15.998  3859  3905 W jxcore-log: 
,09-08 15:22:16.200  3859  3905 I jxcore-log: JXcore Cordova bridge is ready!
09-08 15:22:16.200  3859  3905 I jxcore-log: 
,09-08 15:22:16.200  3859  3905 W jxcore-log: JXcore engine is started
,09-08 15:22:16.210  3859  3898 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 15:22:16.215  3859  3859 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 15:22:27.569   874  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:22:30.132  3859  3905 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 15:22:30.132  3859  3905 I jxcore-log: 
,09-08 15:22:30.135  3859  3905 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 15:22:30.135  3859  3905 I jxcore-log: 
,09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:30.149  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:22:30.158  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:22:30.163  3859  3905 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 15:22:30.163  3859  3905 I jxcore-log: 
,09-08 15:22:30.171  3859  3905 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 15:22:30.171  3859  3905 I jxcore-log: 
,09-08 15:22:30.551  3859  3905 I jxcore-log: Running unit tests
09-08 15:22:30.551  3859  3905 I jxcore-log: 
,09-08 15:22:30.552  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 15:22:30.552  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b09da added. We now have 2 listener(s)
09-08 15:22:30.553  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 15:22:30.553  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 15:22:30.553  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 15:22:30.553  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:22:30.553  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cfce0b added. We now have 2 listener(s)
09-08 15:22:30.553  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 15:22:30.556  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 15:22:30.565  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:30.577  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:22:30.583  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:22:30.584  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 15:22:30.585  3859  3905 D executeNativeTests: Running unit tests
,09-08 15:22:30.597  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:30.605  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:30.670  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 15:22:30.671  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 added. We now have 3 listener(s)
09-08 15:22:30.672  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 15:22:30.672  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 15:22:30.672  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 15:22:30.672  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 15:22:30.672  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 added. We now have 3 listener(s)
09-08 15:22:30.672  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 15:22:30.673  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 15:22:30.676  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:30.690  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:22:30.695  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:22:30.695  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 15:22:30.697  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 15:22:30.699  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 15:22:30.699  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 15:22:30.699  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 15:22:30.701  3859  3905 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 15:22:30.702  3859  3905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 15:22:30.702  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 15:22:30.702  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 15:22:30.702  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 15:22:30.702  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 15:22:30.702  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:30.703  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:30.703  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:30.703  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:30.703  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.703  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:22:30.703  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 15:22:30.703  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 removed from the list
09-08 15:22:30.704  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:30.704  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 removed from the list
09-08 15:22:30.705  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:30.706  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:30.706  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.707  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.707  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.709  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:30.709  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:30.709  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:30.709  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:30.711  3859  3905 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 15:22:30.711  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:30.711  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:30.711  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:30.711  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:30.712  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.712  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.712  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:30.712  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:30.712  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:30.721  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:22:30.722  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:22:30.722  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.722  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.722  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.722  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:30.726  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:30.726  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:30.726  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:30.726  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:30.732  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 15:22:30.732  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 15:22:30.733  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 15:22:30.734  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 15:22:30.734  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:30.735  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:30.735  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:30.735  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:30.735  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.735  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.735  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:30.735  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:30.735  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:30.735  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:30.735  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.735  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.735  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:30.735  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:30.738  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:30.738  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:30.738  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:30.739  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:30.741  3859  3905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 15:22:30.744  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:30.752  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:22:30.756  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:30.756  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 15:22:30.756  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 15:22:30.756  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 15:22:30.756  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 15:22:30.756  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 15:22:30.756  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 15:22:30.760  3859  3905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 15:22:30.760  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 15:22:30.760  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:22:30.770  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:22:30.770  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 15:22:30.772  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 15:22:30.773  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 15:22:30.776  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 15:22:30.780  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 15:22:30.780  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 15:22:30.781  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 15:22:30.781  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 15:22:30.784  3859  3905 D BluetoothAdapter: STATE_ON
09-08 15:22:30.795  2713  2724 D BtGatt.GattService: registerClient() - UUID=721d0228-702f-4ac2-814c-fce35aa4c7a7
09-08 15:22:30.796  2713  2772 D BtGatt.GattService: onClientRegistered() - UUID=721d0228-702f-4ac2-814c-fce35aa4c7a7, clientIf=5
09-08 15:22:30.797  3859  3870 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 15:22:30.799  2713  2904 D BtGatt.GattService: start scan with filters
09-08 15:22:30.807  2713  2785 D BtGatt.ScanManager: handling starting scan
09-08 15:22:30.807  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 15:22:30.808  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 15:22:30.808  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 15:22:30.809  2713  2785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:22:30.809  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 15:22:30.827  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:22:30.829  2713  2772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 15:22:30.829  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:30.830  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:22:30.832  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 15:22:30.831  2713  2785 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 15:22:30.837  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 15:22:30.850  2713  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 15:22:30.850  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:30.850  2713  2785 D BtGatt.ScanManager: Starting BLE batch scan
09-08 15:22:30.851  2713  2785 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 15:22:30.856  3859  3905 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 15:22:30.861  2713  2772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 15:22:30.861  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:30.868  2713  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 15:22:30.868  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:31.333  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 15:22:31.334  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 15:22:31.334  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 15:22:32.376  2713  2713 D BtGatt.ScanManager: awakened up at time 329657
,09-08 15:22:32.381  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:32.431  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
09-08 15:22:32.431  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:32.432  2713  2772 D BtGatt.GattService: current time is 329713507702
,09-08 15:22:32.434  2713  2772 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -84, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 35, 97, 126, -92, 22, -56, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -90, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -104, 14, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 107, 58, 19, -9, 93, -60, 1, 0, -84, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:32.439  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:32.442  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 15:22:32.443  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 15:22:32.444  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 15:22:32.445  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 15:22:32.446  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
09-08 15:22:32.447  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 15:22:32.448  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 15:22:32.449  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:33.934  2713  2713 D BtGatt.ScanManager: awakened up at time 331216
,09-08 15:22:33.939  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:34.002  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-08 15:22:34.003  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:34.003  2713  2772 D BtGatt.GattService: current time is 331284889953
,09-08 15:22:34.006  2713  2772 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -82, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 81, 34, 97, 112, -14, -5, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -91, 12, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 107, 58, 19, -9, 93, -60, 1, 0, -82, 1, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:34.006  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 15:22:34.006  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 15:22:34.007  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
09-08 15:22:34.007  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 15:22:34.007  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 15:22:34.007  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 15:22:34.007  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 15:22:34.007  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:35.507  2713  2713 D BtGatt.ScanManager: awakened up at time 332788
,09-08 15:22:35.509  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:35.542  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 15:22:35.542  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:35.543  2713  2772 D BtGatt.GattService: current time is 332824437167
09-08 15:22:35.543  2713  2772 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -83, 19, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 85, -113, -37, 31, -33, 8, 0, -128, -93, 21, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0]
09-08 15:22:35.544  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:35.545  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
,09-08 15:22:35.866  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:35.867  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:35.867  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 15:22:35.867  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:35.868  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 15:22:35.868  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 15:22:35.868  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 15:22:35.869  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 15:22:35.869  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 15:22:35.871  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 15:22:35.871  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 15:22:35.873  3859  3905 D BluetoothAdapter: STATE_ON
09-08 15:22:35.876  2713  2923 D BtGatt.GattService: stopScan() - queue size =1
,09-08 15:22:35.878  2713  2724 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 15:22:35.880  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 15:22:35.880  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 15:22:35.880  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 15:22:35.880  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 15:22:35.881  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 15:22:35.884  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 15:22:35.885  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 15:22:35.886  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 15:22:35.886  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 15:22:35.888  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:22:35.892  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 15:22:35.892  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:22:35.892  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 15:22:35.892  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:22:35.893  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:35.893  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 15:22:35.894  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:35.894  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:35.894  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:35.895  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:35.895  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:35.903  2713  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 15:22:35.904  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:35.904  2713  2785 D BtGatt.ScanManager: stopping BLe Batch
,09-08 15:22:35.918  2713  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 15:22:35.918  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:35.918  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:35.934  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 15:22:35.934  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:36.394  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 15:22:40.897  3859  3905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 15:22:40.904  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:40.918  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:22:40.925  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:22:40.926  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 15:22:40.926  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 15:22:40.927  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 15:22:40.927  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 15:22:40.927  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:22:40.928  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 15:22:40.934  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:22:40.942  3859  3905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 15:22:40.942  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 15:22:40.943  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:40.956  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 15:22:40.959  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 15:22:40.959  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 15:22:40.969  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 15:22:40.969  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 15:22:40.969  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 15:22:40.971  3859  3905 D BluetoothAdapter: STATE_ON
,09-08 15:22:40.978  2713  2725 D BtGatt.GattService: registerClient() - UUID=6f184689-b74e-435d-a3b4-0545be051ed7
,09-08 15:22:40.979  2713  2772 D BtGatt.GattService: onClientRegistered() - UUID=6f184689-b74e-435d-a3b4-0545be051ed7, clientIf=5
,09-08 15:22:40.980  3859  3870 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 15:22:40.980  2713  2923 D BtGatt.GattService: start scan with filters
,09-08 15:22:40.988  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 15:22:40.988  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 15:22:40.988  2713  2785 D BtGatt.ScanManager: handling starting scan
,09-08 15:22:40.989  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 15:22:40.989  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 15:22:41.000  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:22:41.001  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:22:41.002  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 15:22:41.004  2713  2772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 15:22:41.004  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:41.005  2713  2785 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 15:22:41.008  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 15:22:41.018  3859  3905 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 15:22:41.021  2713  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 15:22:41.022  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:41.022  2713  2785 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 15:22:41.022  2713  2785 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 15:22:41.024  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:41.024  3859  3905 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 15:22:41.024  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:41.024  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 15:22:41.025  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:41.025  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 15:22:41.025  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 15:22:41.025  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 15:22:41.026  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 15:22:41.026  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 15:22:41.026  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 15:22:41.026  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 15:22:41.028  3859  3905 D BluetoothAdapter: STATE_ON
09-08 15:22:41.029  2713  2725 D BtGatt.GattService: stopScan() - queue size =1
,09-08 15:22:41.031  2713  2923 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 15:22:41.032  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 15:22:41.033  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 15:22:41.033  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 15:22:41.033  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 15:22:41.035  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 15:22:41.038  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 15:22:41.038  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 15:22:41.038  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 15:22:41.038  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 15:22:41.039  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:22:41.040  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:22:41.040  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 15:22:41.040  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 15:22:41.040  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:41.040  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:41.040  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:22:41.040  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:41.041  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:41.041  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:41.041  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:41.041  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:41.041  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:41.041  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:41.042  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:41.042  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:41.042  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:41.042  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:41.043  3859  3905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 15:22:41.045  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 15:22:41.046  2713  2772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 15:22:41.046  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:22:41.051  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:22:41.053  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 15:22:41.054  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 15:22:41.055  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 15:22:41.056  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 15:22:41.056  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 15:22:41.056  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 15:22:41.056  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-08 15:22:41.057  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:41.060  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:22:41.062  2713  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 15:22:41.062  3859  3905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 15:22:41.062  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:41.062  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 15:22:41.066  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 15:22:41.067  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 15:22:41.067  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 15:22:41.070  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 15:22:41.071  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 15:22:41.071  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 15:22:41.071  3859  3905 D BluetoothAdapter: STATE_ON
,09-08 15:22:41.073  2713  2923 D BtGatt.GattService: registerClient() - UUID=df1a1886-5283-48aa-a01c-5e8bc83acccb
,09-08 15:22:41.074  2713  2772 D BtGatt.GattService: onClientRegistered() - UUID=df1a1886-5283-48aa-a01c-5e8bc83acccb, clientIf=5
09-08 15:22:41.074  3859  3870 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 15:22:41.075  2713  2724 D BtGatt.GattService: start scan with filters
,09-08 15:22:41.078  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 15:22:41.078  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 15:22:41.078  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 15:22:41.078  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 15:22:41.079  2713  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 15:22:41.079  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:41.079  2713  2785 D BtGatt.ScanManager: stopping BLe Batch
,09-08 15:22:41.081  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:22:41.081  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 15:22:41.081  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:22:41.082  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 15:22:41.084  3859  3905 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 15:22:41.093  2713  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 15:22:41.093  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:41.093  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:41.104  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 15:22:41.104  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:41.104  2713  2772 D BtGatt.GattService: current time is 338386349421
09-08 15:22:41.105  2713  2772 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -84, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:41.105  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 15:22:41.106  2713  2785 D BtGatt.ScanManager: handling starting scan
,09-08 15:22:41.114  2713  2772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 15:22:41.114  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:41.114  2713  2785 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 15:22:41.120  2713  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 15:22:41.121  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:41.121  2713  2785 D BtGatt.ScanManager: Starting BLE batch scan
09-08 15:22:41.121  2713  2785 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 15:22:41.132  2713  2772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 15:22:41.132  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:41.140  2713  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 15:22:41.140  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:41.583  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-08 15:22:41.583  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 15:22:41.583  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 15:22:42.645  2713  2713 D BtGatt.ScanManager: awakened up at time 339926
,09-08 15:22:42.647  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:42.707  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-08 15:22:42.707  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:22:42.707  2713  2772 D BtGatt.GattService: current time is 339989150676
,09-08 15:22:42.708  2713  2772 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -83, 28, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 81, 34, 97, 112, -14, -5, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -95, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -102, 0, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0]
,09-08 15:22:42.710  2713  2772 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:22:42.713  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 15:22:42.714  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 15:22:42.716  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 15:22:42.716  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 15:22:42.717  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 15:22:42.718  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 15:22:42.719  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
,09-08 15:22:43.729   874  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=341010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:22:44.210  2713  2713 D BtGatt.ScanManager: awakened up at time 341491
,09-08 15:22:44.213  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:44.258  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 15:22:44.259  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:44.259  2713  2772 D BtGatt.GattService: current time is 341541003117
,09-08 15:22:44.260  2713  2772 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -86, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -94, 9, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -66, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 15:22:44.261  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 15:22:44.262  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 15:22:44.262  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-08 15:22:44.263  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 15:22:44.264  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 15:22:44.265  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 15:22:44.266  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 15:22:44.580  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:22:44.591  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:22:44.594  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:22:44.655  1505  1964 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 15:22:44.656  1505  1964 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-08 15:22:44.656  1505  1964 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:22:44.657  1505  1964 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:22:44.697  1505  1964 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 15:22:44.697  1505  1964 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 15:22:44.697  1505  1964 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 15:22:44.697  1505  1964 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 15:22:44.697  1505  1964 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 15:22:44.697  1505  1964 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 15:22:44.697  1505  1964 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 15:22:44.713  3541  3572 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 15:22:44.713  3541  3572 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 15:22:44.713  3541  3572 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 15:22:44.713  3541  3572 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 15:22:44.713  3541  3572 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 15:22:44.713  3541  3572 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 15:22:44.713  3541  3572 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 15:22:45.762  2713  2713 D BtGatt.ScanManager: awakened up at time 343043
,09-08 15:22:45.764  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:45.793  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 15:22:45.794  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:45.794  2713  2772 D BtGatt.GattService: current time is 343076163508
09-08 15:22:45.795  2713  2772 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -92, 29, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -83, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 15:22:45.796  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-08 15:22:45.797  2713  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 15:22:46.085  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:46.085  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:46.086  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 15:22:46.086  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:46.086  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 15:22:46.087  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 15:22:46.087  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 15:22:46.087  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 15:22:46.088  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 15:22:46.089  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 15:22:46.090  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 15:22:46.092  3859  3905 D BluetoothAdapter: STATE_ON
09-08 15:22:46.094  2713  2923 D BtGatt.GattService: stopScan() - queue size =1
,09-08 15:22:46.097  2713  2724 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 15:22:46.099  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 15:22:46.099  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 15:22:46.099  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 15:22:46.100  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 15:22:46.101  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 15:22:46.105  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 15:22:46.106  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 15:22:46.106  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 15:22:46.106  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 15:22:46.108  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:22:46.111  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 15:22:46.112  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:22:46.112  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 15:22:46.117  2713  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 15:22:46.117  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:46.117  2713  2785 D BtGatt.ScanManager: stopping BLe Batch
,09-08 15:22:46.127  2713  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 15:22:46.127  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:46.128  2713  2785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:22:46.139  2713  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 15:22:46.139  2713  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:22:46.613  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 15:22:46.613  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:46.614  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 15:22:49.623   874  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=346903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:22:51.114  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:51.114  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.114  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:51.116  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:22:51.116  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.119  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:22:51.120  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.120  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.120  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.120  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.121  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.123  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.123  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.126  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:51.126  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 15:22:51.127  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.127  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.129  3859  3905 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 15:22:51.131  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:51.132  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:51.132  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:51.133  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.133  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.133  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.134  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.134  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.134  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.134  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.134  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.135  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.135  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.135  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.138  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:51.138  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.138  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.138  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.141  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 15:22:51.142  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:51.142  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:51.142  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:51.143  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.143  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.143  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.143  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.144  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:51.144  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.144  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.144  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.145  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.145  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.145  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.147  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:51.148  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.148  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.148  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.150  3859  3905 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-08 15:22:51.151  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:51.151  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:51.151  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:51.152  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.152  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.152  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.152  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.153  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:51.153  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.153  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.153  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.154  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.154  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.154  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.157  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:51.157  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.157  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.157  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.159  3859  3905 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-08 15:22:51.159  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:51.160  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.160  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:51.160  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.160  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.161  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.161  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
,09-08 15:22:51.161  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.162  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.162  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.162  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.163  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.163  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.163  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.165  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:51.165  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.165  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.166  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.167  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 15:22:51.167  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 15:22:51.168  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 15:22:51.168  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 15:22:51.168  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 15:22:51.168  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 15:22:51.169  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 15:22:51.169  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 15:22:51.169  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 15:22:51.169  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:51.170  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.170  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:51.170  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.170  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.170  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.171  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.171  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:51.171  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.171  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.171  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.172  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.172  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.172  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.174  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:51.174  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.175  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.175  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.176  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 15:22:51.177  3859  3905 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 15:22:51.177  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 15:22:51.184  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 15:22:51.184  3859  3905 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 15:22:51.184  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 15:22:51.184  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 15:22:51.185  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-08 15:22:51.186  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 15:22:51.187  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 15:22:51.187  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 15:22:51.188  3859  3905 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 15:22:51.188  3859  3905 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 15:22:51.188  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 15:22:51.188  3859  3905 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 15:22:51.188  3859  3905 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 15:22:51.188  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 15:22:51.188  3859  3905 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 15:22:51.188  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 15:22:51.191  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 15:22:51.192  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-08 15:22:51.193  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 15:22:51.193  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 15:22:51.193  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-08 15:22:51.194  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 15:22:51.194  3859  3905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 15:22:51.195  3859  3905 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 15:22:51.195  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:51.195  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
09-08 15:22:51.195  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.196  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:51.196  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.196  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.196  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.196  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 15:22:51.197  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.197  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.197  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.197  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.197  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.197  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.197  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.197  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.198  3859  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
,09-08 15:22:51.199  3859  3910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 15:22:51.200  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:51.200  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 15:22:51.200  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.200  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.201  3859  3905 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-08 15:22:51.202  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:51.202  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.202  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:51.202  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:22:51.202  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.202  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.202  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.202  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.202  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.203  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.203  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.203  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.203  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.203  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.204  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:51.204  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.204  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.204  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:51.205  3859  3905 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 15:22:51.206  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:51.206  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.206  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:51.206  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.206  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.206  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.207  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.207  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.207  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.207  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.207  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:51.207  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.207  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.207  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.209  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:51.209  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.209  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.210  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.210  3859  3905 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 15:22:51.210  3859  3905 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-08 15:22:51.211  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 15:22:51.211  3859  3905 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 15:22:51.211  3859  3905 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 15:22:51.211  3859  3905 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 15:22:51.211  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 15:22:51.211  3859  3905 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 15:22:51.211  3859  3905 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 15:22:51.211  3859  3905 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 15:22:51.211  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 15:22:51.212  3859  3905 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 15:22:51.212  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:51.212  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:51.212  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:51.212  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.212  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.212  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.212  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.212  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.212  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.213  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.213  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.213  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:51.213  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.213  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.214  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:51.215  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:51.215  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.215  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.216  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:51.216  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.217  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:51.217  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:51.217  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:51.217  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:51.217  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:51.217  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:51.218  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.219  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:56.219  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.219  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:22:56.220  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.220  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.220  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:56.221  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:56.221  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:56.221  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:56.222  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:56.222  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:56.222  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.223  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:56.223  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.223  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.224  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:22:56.224  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.224  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.224  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:56.225  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.228  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:22:56.229  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:56.229  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.229  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.234  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 15:22:56.236  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 15:22:56.237  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 15:22:56.238  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 15:22:56.238  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 15:22:56.239  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 15:22:56.239  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 15:22:56.239  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 15:22:56.239  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:56.239  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 15:22:56.239  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 15:22:56.239  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 15:22:56.239  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.239  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 15:22:56.240  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:56.240  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:56.240  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 15:22:56.240  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 15:22:56.242  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 15:22:56.242  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 15:22:56.242  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.242  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.243  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 15:22:56.244  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:56.244  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:56.244  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:22:56.245  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:56.245  3859  3912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 15:22:56.245  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:22:56.245  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:56.245  3859  3912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 15:22:56.245  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:56.245  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:22:56.245  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.245  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:56.245  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.245  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.245  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 15:22:56.246  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:22:56.246  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.246  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.246  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.246  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.246  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 15:22:56.248  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:56.248  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 15:22:56.248  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.248  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.250  3859  3905 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-08 15:22:56.250  3859  3905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 15:22:56.250  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 15:22:56.250  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 15:22:56.250  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 15:22:56.250  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:22:56.250  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:22:56.251  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:56.251  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:56.251  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.251  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.251  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
,09-08 15:22:56.251  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.251  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:56.251  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:22:56.251  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.251  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.251  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.252  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.253  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:56.253  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 15:22:56.253  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.253  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.261  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:56.261  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:56.261  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:56.262  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:22:56.263  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:56.263  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.263  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:56.263  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:56.264  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.264  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:22:56.264  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.264  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.265  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:22:56.265  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.267  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:56.267  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:56.267  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:56.267  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:56.270  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:22:56.270  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:22:56.270  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 15:22:56.271  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:22:56.272  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.272  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.272  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883e271 not in the list
09-08 15:22:56.272  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:22:56.272  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
09-08 15:22:56.272  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:22:56.272  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.272  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:22:56.272  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:22:56.273  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:22:56.273  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:22:56.274  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:22:56.274  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:22:56.274  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0856 not in the list
,09-08 15:22:56.275  3859  3905 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-08 15:22:56.275  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 15:22:56.275  3859  3905 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 15:22:56.275  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 15:22:56.275  3859  3905 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 15:22:56.275  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 15:22:56.278  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 15:22:56.278  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-08 15:22:56.279  3859  3905 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 15:22:56.279  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-08 15:22:56.280  3859  3905 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 15:22:56.280  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 15:22:56.280  3859  3905 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 15:22:56.280  3859  3905 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 15:22:56.280  3859  3905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-08 15:22:56.281  3859  3905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 15:22:56.281  3859  3905 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 15:22:56.281  3859  3905 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-08 15:22:56.281  3859  3905 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 15:22:56.281  3859  3905 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 15:22:56.282  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:22:56.283  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e245748 added. We now have 3 listener(s)
09-08 15:22:56.283  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:22:56.284  3859  3905 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 15:22:56.285   874  1397 D WifiService: setWifiEnabled: true pid=3859, uid=10000
09-08 15:22:56.285   874  1397 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 15:22:56.332  2713  2897 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 15:22:56.333  2713  2900 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 15:22:56.334  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
,09-08 15:22:56.746  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 15:23:01.169   874  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=358450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:23:01.292  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 15:23:01.292  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c149e1 added. We now have 4 listener(s)
09-08 15:23:01.293  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:23:01.309  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:23:01.310  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c149e1 removed from the list
09-08 15:23:01.310  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:23:01.310  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:01.311  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:01.313  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:23:01.313  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d53306 added. We now have 4 listener(s)
09-08 15:23:01.313  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:23:01.317  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:23:01.318  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d53306 removed from the list
09-08 15:23:01.318  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:23:01.318  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:01.319  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:01.321  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:23:01.321  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f6bdc7 added. We now have 4 listener(s)
,09-08 15:23:01.322  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:23:01.329   874  2038 D WifiService: setWifiEnabled: false pid=3859, uid=10000
,09-08 15:23:01.329   874  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 15:23:01.343  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:23:01.344  2713  2767 D BluetoothAdapterState: Current state: ON, message: 23
09-08 15:23:01.344  2713  2767 D BluetoothAdapterProperties: Setting state to 13
09-08 15:23:01.345  2713  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 15:23:01.346  2713  2767 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 15:23:01.348  2713  2767 I BluetoothAdapterState: Entering PendingCommandState
,09-08 15:23:01.357  2713  2713 D BluetoothMapService: onReceive
,09-08 15:23:01.357  2713  2713 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 15:23:01.358  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.358  2713  2713 D BluetoothMapService: STATE_TURNING_OFF
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:01.358  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
09-08 15:23:01.358  2713  2713 D BluetoothMapService: MAP Service closeService in
09-08 15:23:01.358  2713  2713 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 15:23:01.359  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.359  2713  2713 D ObexServerSockets0: shutdown(block = true)
,09-08 15:23:01.359  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:01.359  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 15:23:01.360  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 15:23:01.360  2713  2925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 15:23:01.360  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 15:23:01.361  2713  2924 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 15:23:01.362  2713  2900 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 15:23:01.362  2713  2713 I BtOppRfcommListener: stopping Accept Thread,
09-08 15:23:01.362  2713  3491 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 15:23:01.363  2713  3491 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 15:23:01.366  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:01.369  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:01.373  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 15:23:01.373  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:01.373  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:23:01.374  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.374  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:01.375   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 15:23:01.375   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 15:23:01.375   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 15:23:01.375   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 15:23:01.382   874   887 I ActivityManager: Start proc 3916:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 15:23:01.382  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:01.382  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:23:01.383  2713  2772 D BluetoothAdapterProperties: Scan Mode:20
,09-08 15:23:01.383  2713  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 15:23:01.384  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:01.384  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:01.386  2713  2713 D HeadsetService: Received stop request...Stopping profile...
09-08 15:23:01.389   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:01.389   874   874 D BluetoothHeadset: Proxy object disconnected
,09-08 15:23:01.389   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:01.389  1993  2075 D BluetoothHeadset: Proxy object disconnected
,09-08 15:23:01.390  2713  2713 D A2dpService: Received stop request...Stopping profile...
09-08 15:23:01.390  1371  1384 D BluetoothHeadset: Proxy object disconnected
,09-08 15:23:01.390  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:01.390  1371  1371 D HeadsetProfile: Bluetooth service disconnected
09-08 15:23:01.390  2713  2918 D A2dpStateMachine: Exit Disconnected: -1
09-08 15:23:01.392   874  1315 E native  : do suspend true
,09-08 15:23:01.392   874   874 D BluetoothA2dp: Proxy object disconnected
,09-08 15:23:01.392  1371  1371 D BluetoothA2dp: Proxy object disconnected
09-08 15:23:01.393  2713  2713 D HidService: Received stop request...Stopping profile...
09-08 15:23:01.393  2713  2713 D HidService: Stopping Bluetooth HidService
09-08 15:23:01.394  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:01.394  1371  1371 D BluetoothInputDevice: Proxy object disconnected
,09-08 15:23:01.394  1371  1371 D HidProfile: Bluetooth service disconnected
,09-08 15:23:01.395  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:01.395  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.395  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:01.395  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:01.397  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:01.399  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 15:23:01.399  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 15:23:01.399  2713  2772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 15:23:01.399  2713  2897 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:01.399  2713  2897 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:01.399  2713  2897 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:01.399  2713  2713 D HealthService: Received stop request...Stopping profile...
09-08 15:23:01.400  2713  2772 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 15:23:01.402  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:01.402  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.402  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 15:23:01.402  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:01.404  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:01.406  2713  2772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 15:23:01.406  2713  2897 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 15:23:01.406  2713  2897 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 15:23:01.406  2713  2897 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 15:23:01.406  2713  2897 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 15:23:01.406  2713  2897 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 15:23:01.406  2713  2713 D PanService: Received stop request...Stopping profile...
,09-08 15:23:01.406  2713  2897 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 15:23:01.407  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 15:23:01.407   874  2081 D DhcpClient: Clearing IP address
,09-08 15:23:01.407  1371  1371 D PanProfile: Bluetooth service disconnected
,09-08 15:23:01.407   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 15:23:01.408  2713  2713 V BluetoothAdapterState: isTurningOff()=true
,09-08 15:23:01.408  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.409  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:01.409  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:01.409  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 15:23:01.410  2713  2772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 15:23:01.410  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 15:23:01.410  2713  2713 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 15:23:01.410  2713  2713 D BluetoothMapService: stop()
09-08 15:23:01.411  2713  2713 D BluetoothMapAppObserver: deinitObservers()
09-08 15:23:01.411  2713  2713 D BluetoothMapAppObserver: removeReceiver()
09-08 15:23:01.412  1505  3482 V NativeCrypto: Read error: ssl=0x9b724c00: I/O error during system call, Connection timed out
09-08 15:23:01.413  1371  1371 D BluetoothMap: Proxy object disconnected
09-08 15:23:01.413  1371  1371 D MapProfile: Bluetooth service disconnected
,09-08 15:23:01.413  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:01.413  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.413  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:01.413  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:01.413  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 15:23:01.413  1505  3482 V NativeCrypto: SSL shutdown failed: ssl=0x9b724c00: I/O error during system call, Broken pipe
09-08 15:23:01.414  2713  2772 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 15:23:01.414  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 15:23:01.415  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:01.415  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.415  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:01.415  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:01.415  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 15:23:01.415  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 15:23:01.415   372   872 D CommandListener: Setting iface cfg
09-08 15:23:01.416  2713  2713 D BluetoothMapService: MAP Service closeService in
09-08 15:23:01.416  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:01.416  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.416  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:01.416  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:01.416  2713  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 15:23:01.417  2713  2767 D BluetoothAdapterProperties: Setting state to 15
09-08 15:23:01.417   874  2089 D DhcpClient: Receive thread stopped
09-08 15:23:01.417  2713  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 15:23:01.417  2713  2767 I BluetoothAdapterState: Entering BleOnState
09-08 15:23:01.417  2713  2713 D BluetoothMapService: cleanup()
09-08 15:23:01.417  2713  2713 D BluetoothMapService: MAP Service closeService in
,09-08 15:23:01.418  1371  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 15:23:01.419  1371  1732 D BluetoothMap: onBluetoothStateChange: up=false
09-08 15:23:01.419   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 15:23:01.420   874  2039 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-08 15:23:01.420   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 15:23:01.420   874  2062 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-08 15:23:01.420   874  1315 E native  : do suspend true
09-08 15:23:01.421   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 15:23:01.421   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 15:23:01.422   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 15:23:01.422  1371  1732 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 15:23:01.424  1371  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 15:23:01.424   395   395 E Parcel  : Reading a NULL string not supported here.
09-08 15:23:01.425  1993  2012 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:01.425   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:01.425   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 15:23:01.425   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 15:23:01.425  1371  1732 D BluetoothPan: onBluetoothStateChange on: false
09-08 15:23:01.426  1371  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:01.427   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 15:23:01.427  2713  2767 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 15:23:01.427  2713  2767 D BluetoothAdapterProperties: Setting state to 16
09-08 15:23:01.427  2713  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 15:23:01.428  2713  2767 D BluetoothAdapterProperties: onBleDisable
09-08 15:23:01.428  2713  2767 I BluetoothAdapterState: Entering PendingCommandState
09-08 15:23:01.428  2713  2768 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 15:23:01.428   874  2062 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-08 15:23:01.430  2713  2772 D BluetoothAdapterProperties: Scan Mode:20
09-08 15:23:01.430  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.430  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:23:01.431  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.431  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:01.432  2713  2897 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 15:23:01.432  2713  2897 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:01.433  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.433  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:23:01.433  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple adver,tisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.433  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:01.435  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.435  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:01.435  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.435  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:01.437  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.437  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:01.439  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.439  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:01.440  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No rel,evant state changes
09-08 15:23:01.460   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 15:23:01.463  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-08 15:23:01.473  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 15:23:01.477   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dfbf1bb:true
09-08 15:23:01.479  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 15:23:01.484   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 15:23:01.484   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-08 15:23:01.485   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 15:23:01.485   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 15:23:01.492   874  2039 I ActivityManager: Start proc 3934:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 15:23:01.495   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 15:23:01.496   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 15:23:01.497  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:01.498  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:01.499  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:01.500  3421  3421 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bec8b8b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-08 15:23:01.513   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 15:23:01.515  1862  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 15:23:01.516   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 15:23:01.516  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:01.517  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.517  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:01.519  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.519  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:01.519  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.519  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:01.521  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:01.521  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:01.521  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:01.521  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:01.522  3916  3916 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 15:23:01.525  3916  3916 D BluetoothMap: Create BluetoothMap proxy object
,09-08 15:23:01.538  3916  3916 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 15:23:01.540  3934  3934 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 15:23:01.550  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-08 15:23:01.556   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 15:23:01.556   874  2039 I ActivityManager: Killing 3243:com.google.android.gm/u0a78 (adj 15): empty #17
,09-08 15:23:01.557   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 15:23:01.633  2713  2772 I bt_hci  : shut_down
,09-08 15:23:01.634  2713  2789 D bt_hwcfg: hw_epilog_process
,09-08 15:23:01.634  2713  2789 I bt_vendor: low_power_mode_cb
,09-08 15:23:01.654  2713  2789 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 15:23:01.654  2713  2789 I bt_vendor: epilog_cb
,09-08 15:23:01.654  2713  2789 I bt_hci  : epilog_finished_callback
,09-08 15:23:01.661  2713  2772 I bt_hci_h4: hal_close
,09-08 15:23:01.662  2713  2772 I bt_userial_vendor: device fd = 51 close
,09-08 15:23:01.707  3934  3934 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 15:23:01.707  3934  3934 D StrictMode: 	,at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.707  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.708  3934  3934 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.708  3934  3934 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.708  3934  3934 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.708  3934  3934 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.708  3934  3934 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.708  3934  3934 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.708  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.709  3934  3934 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:23:01.709  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 15:23:01.716  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 15:23:01.727  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 15:23:01.742  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-08 15:23:01.744  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 15:23:01.750  1698  1698 D SystemUpdateService: onCreate
,09-08 15:23:01.752  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 15:23:01.764  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 15:23:01.771  1698  2522 I iu.UploadsManager: num queued entries: 0
,09-08 15:23:01.771  1698  2522 I iu.UploadsManager: num updated entries: 0
,09-08 15:23:01.772  1698  2522 I iu.SyncManager: NEXT; no task
,09-08 15:23:01.773  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 15:23:01.775  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 15:23:01.779  1698  3968 I SystemUpdateService: active receiver: enabled
,09-08 15:23:01.794  1698  3968 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 15:23:01.803  1698  3968 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 15:23:01.803  1698  3968 I SystemUpdateService: now status is 0 (complete)
,09-08 15:23:01.803  1698  3968 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 15:23:01.803  1698  3968 I SystemUpdateService: file has been verified
,09-08 15:23:01.804  1698  3968 I SystemUpdateService: OTA package size = 12249756
,09-08 15:23:01.806   874  2036 I ActivityManager: Start proc 3971:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 15:23:01.814  1698  3968 I SystemUpdateService: showing system update notification
,09-08 15:23:01.814  2713  2768 D bt_stack_manager: event_shut_down_stack finished.
09-08 15:23:01.814  2713  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 15:23:01.816  2713  2713 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 15:23:01.817  2713  2767 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-08 15:23:01.817  2713  2713 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 15:23:01.817  2713  2713 D BtGatt.GattService: stop()
09-08 15:23:01.823  2713  2713 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 15:23:01.824  2713  2713 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:01.824  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:01.824  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 15:23:01.824  2713  2713 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 15:23:01.825  2713  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 15:23:01.825  2713  2767 D BluetoothAdapterProperties: Setting state to 10
09-08 15:23:01.825  2713  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 15:23:01.826  2713  2767 I BluetoothAdapterState: Entering OffState
09-08 15:23:01.826   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 15:23:01.837  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 15:23:01.837  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 15:23:01.837  2713  2713 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 15:23:01.838  2713  2768 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-08 15:23:01.839  2713  2768 D bt_stack_manager: event_clean_up_stack finished.
,09-08 15:23:01.844  2713  2713 I art     : System.exit called, status: 0
,09-08 15:23:01.844  2713  2713 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 15:23:01.868  3971  3971 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 15:23:01.870  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 15:23:01.888  3971  3971 D SprintDMHelper: simOperator: 
,09-08 15:23:01.888  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-08 15:23:01.888   874  1397 I ActivityManager: Process com.android.bluetooth (pid 2713) has died
,09-08 15:23:01.893  1698  1698 D SystemUpdateService: onDestroy
,09-08 15:23:01.908   874  1518 I ActivityManager: Start proc 3984:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 15:23:01.909   874  1518 I ActivityManager: Killing 3421:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 15:23:01.975   874  2272 I ActivityManager: Killing 2792:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 15:23:02.000  3934  3960 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 15:23:02.013   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d419aa:true
,09-08 15:23:02.199   874  1518 I ActivityManager: Start proc 4001:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 15:23:02.202  3109  4000 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 15:23:02.235  4001  4001 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 15:23:02.297  4001  4001 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 15:23:02.297  4001  4001 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 15:23:02.297  4001  4001 I GAv4    :   adb logcat -s GAv4
,09-08 15:23:02.311  4001  4001 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 15:23:02.317  4001  4001 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 15:23:02.342  4001  4018 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 15:23:02.460  4001  4001 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 15:23:02.506  4001  4001 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 15:23:02.516  4001  4001 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9793-9797)
09-08 15:23:02.516  4001  4001 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 15:23:02.530  4001  4001 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {afb6d7b}
09-08 15:23:02.531  4001  4001 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 15:23:02.531  4001  4001 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 15:23:02.541  4001  4001 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 15:23:02.543  4001  4001 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 15:23:02.559  4001  4001 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 15:23:02.575  4001  4001 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 15:23:02.575  4001  4001 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 15:23:02.575  4001  4001 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 15:23:02.575  4001  4001 I Adreno  : Build Date                       : 10/20/15
09-08 15:23:02.575  4001  4001 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 15:23:02.575  4001  4001 I Adreno  : Local Branch                     : M14
09-08 15:23:02.575  4001  4001 I Adreno  : Remote Branch                    : 
09-08 15:23:02.575  4001  4001 I Adreno  : Remote Branch                    : 
09-08 15:23:02.575  4001  4001 I Adreno  : Reconstruct Branch               : 
,09-08 15:23:02.638  4001  4001 I NSApplication: Starting up...
,09-08 15:23:02.646  4001  4047 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 15:23:02.682   874  2272 I ActivityManager: Start proc 4052:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 15:23:02.686   874  2272 I ActivityManager: Killing 1714:android.process.acore/u0a5 (adj 15): empty #17
,09-08 15:23:02.749  4052  4052 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 15:23:02.929   874  2041 I ActivityManager: Killing 3655:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 15:23:03.022   874  2029 I ActivityManager: Start proc 4066:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 15:23:03.090  4066  4066 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 15:23:03.132  4066  4066 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 15:23:03.181   874  2273 I ActivityManager: Killing 3671:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 15:23:06.362   874  1929 D WifiService: setWifiEnabled: true pid=3859, uid=10000
09-08 15:23:06.362   874  1929 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 15:23:06.373   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-08 15:23:06.380  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:06.380  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 15:23:06.381  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:06.381  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:06.396  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:06.397  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:06.397  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:06.397  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:06.403  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:06.403  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:06.403  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 15:23:06.404  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:06.416   874  1315 D WifiConfigStore: loaded 0 passpoint configs
09-08 15:23:06.417   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 15:23:06.418   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 15:23:06.419   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 15:23:06.420   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 15:23:06.420   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 15:23:06.420   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 15:23:06.440   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 15:23:06.440   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 15:23:06.441   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:06.448   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 15:23:06.448   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 15:23:06.450   874  1315 E native  : do suspend true
,09-08 15:23:06.460   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 15:23:06.461   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 15:23:06.463   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 15:23:07.255   874  1704 I ActivityManager: Killing 3449:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 15:23:07.750   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 15:23:07.823   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=15.31 delta 1000 -> 994
,09-08 15:23:07.825   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 15:23:07.825   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 15:23:07.838   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 15:23:07.903   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 15:23:07.906  1432  1432 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 15:23:08.347  1432  1432 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 15:23:08.389  1432  1432 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 15:23:08.392  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 15:23:08.400   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 15:23:08.411   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 15:23:08.412   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 15:23:08.412   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 15:23:08.426   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 15:23:08.437   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:08.438   874  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 15:23:08.445   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 15:23:08.476   874  4103 D DhcpClient: Receive thread started
,09-08 15:23:08.569   874  1315 E native  : do suspend false
,09-08 15:23:08.595   874  2081 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 15:23:08.609   874  4103 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172457, domain null
,09-08 15:23:08.610   874  2081 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172457 seconds
,09-08 15:23:08.614   874  2081 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 15:23:08.628   874  4103 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 15:23:08.629   874  2081 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 15:23:08.637   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:08.648   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 15:23:08.648   874  2081 D DhcpClient: Scheduling renewal in 86399s
,09-08 15:23:08.651   874  1315 E native  : do suspend true
,09-08 15:23:08.680   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 15:23:08.684   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 15:23:08.685   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 15:23:08.687   874  1319 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 15:23:08.702   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 15:23:08.765   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 15:23:08.765   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-08 15:23:08.767   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 15:23:08.769   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 15:23:08.770   874  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 15:23:08.781   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 15:23:08.787   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 15:23:08.787   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 15:23:08.788   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 15:23:08.788   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 15:23:08.788   874  1319 D ConnectivityService:    accepting network in place of null
09-08 15:23:08.788   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 15:23:08.789   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 15:23:08.810   874  4102 D NetlinkSocketObserver: NeighborEvent{elapsedMs=366091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:23:08.869   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 15:23:08.885   874  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-08 15:23:08.904   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 15:23:08.914   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 15:23:08.915   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 15:23:08.922   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 15:23:08.927   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 15:23:08.938  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:08.939  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:23:08.939  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:08.939  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:08.946  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:08.947  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:23:08.947  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:08.947  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:08.949  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:08.950  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 15:23:08.950  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:08.950  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:08.956  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 15:23:08.966  1698  1698 D SystemUpdateService: onCreate
,09-08 15:23:08.970  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 15:23:08.974   874  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 13:23:08 GMT], X-Android-Received-Millis=[1473340988973], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473340988940]}
,09-08 15:23:08.975   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 15:23:08.976   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 15:23:08.976   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 15:23:08.977   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 15:23:08.996  1698  4114 I SystemUpdateService: active receiver: enabled
,09-08 15:23:09.000  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 15:23:09.010  1698  2522 I iu.UploadsManager: num queued entries: 0
,09-08 15:23:09.010  1698  2522 I iu.UploadsManager: num updated entries: 0
,09-08 15:23:09.011  1698  2522 I iu.SyncManager: NEXT; no task
,09-08 15:23:09.013  1698  4114 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 15:23:09.014  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 15:23:09.015  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 15:23:09.017  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 15:23:09.026  1698  4118 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 15:23:09.026  1698  4118 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 15:23:09.027  1698  4118 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 15:23:09.030  3971  3971 D SprintDMHelper: simOperator: 
09-08 15:23:09.030  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 15:23:09.045  1698  4114 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 15:23:09.045  1698  4114 I SystemUpdateService: now status is 0 (complete)
09-08 15:23:09.045  1698  4114 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 15:23:09.045  1698  4114 I SystemUpdateService: file has been verified
,09-08 15:23:09.045  1698  4114 I SystemUpdateService: OTA package size = 12249756
,09-08 15:23:09.047  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:23:09.053  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:23:09.078  1698  4114 I SystemUpdateService: showing system update notification
,09-08 15:23:09.115  1698  1698 D SystemUpdateService: onDestroy
,09-08 15:23:09.151  3109  4122 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 15:23:09.162  1505  3086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 15:23:09.163  1505  3086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 15:23:09.163  1505  3086 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:23:09.163  1505  3086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:23:09.181  1698  4118 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-08 15:23:09.914   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 15:23:11.368   874  2000 D WifiService: setWifiEnabled: false pid=3859, uid=10000
,09-08 15:23:11.368   874  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 15:23:11.406  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 15:23:11.418   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 15:23:11.418   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 15:23:11.419   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 15:23:11.419   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 15:23:11.451   874  1315 E native  : do suspend true
,09-08 15:23:11.466   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 15:23:11.466   874  2081 D DhcpClient: Clearing IP address
,09-08 15:23:11.470   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:11.476  1505  4128 V NativeCrypto: Read error: ssl=0x9a661200: I/O error during system call, Connection timed out
,09-08 15:23:11.480  1505  4128 V NativeCrypto: SSL shutdown failed: ssl=0x9a661200: I/O error during system call, Broken pipe
,09-08 15:23:11.487   874  4103 D DhcpClient: Receive thread stopped
09-08 15:23:11.488   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 15:23:11.488   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 15:23:11.489   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 15:23:11.490   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 15:23:11.490   874  1315 E native  : do suspend true
,09-08 15:23:11.497   395   395 E Parcel  : Reading a NULL string not supported here.
09-08 15:23:11.503   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 15:23:11.537   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 15:23:11.576   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 15:23:11.577   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-08 15:23:11.578   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 15:23:11.578   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 15:23:11.580   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 15:23:11.586  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:11.586  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:11.586  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:11.586  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:11.586   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 15:23:11.588  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:11.588  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:11.588  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:11.589  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:11.590  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:11.590  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 15:23:11.590  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.590  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:11.609   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 15:23:11.610  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:11.610  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:11.610  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.610  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:11.611  1862  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 15:23:11.612  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:11.612  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:11.612  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.612  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:11.613   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 15:23:11.614  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:2,3:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:11.614  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:11.614  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:11.614  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:11.635  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 15:23:11.640  1698  1698 D SystemUpdateService: onCreate
09-08 15:23:11.645  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 15:23:11.661  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 15:23:11.669   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 15:23:11.668  1698  4138 I SystemUpdateService: active receiver: enabled
,09-08 15:23:11.673  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 15:23:11.674  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 15:23:11.677  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 15:23:11.684  3971  3971 D SprintDMHelper: simOperator: 
,09-08 15:23:11.684  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 15:23:11.691  1698  2522 I iu.UploadsManager: num queued entries: 0
,09-08 15:23:11.692  1698  2522 I iu.UploadsManager: num updated entries: 0
,09-08 15:23:11.701  1698  4138 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 15:23:11.704  3109  4141 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 15:23:11.707  1698  2522 I iu.SyncManager: NEXT; no task
,09-08 15:23:11.707  1698  4138 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 15:23:11.707  1698  4138 I SystemUpdateService: now status is 0 (complete)
09-08 15:23:11.707  1698  4138 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 15:23:11.709  1698  4138 I SystemUpdateService: file has been verified
09-08 15:23:11.710  1698  4138 I SystemUpdateService: OTA package size = 12249756
,09-08 15:23:11.732  1698  4138 I SystemUpdateService: showing system update notification
,09-08 15:23:11.763  1698  1698 D SystemUpdateService: onDestroy
,09-08 15:23:14.061  1902  1948 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 15:23:14.061  1902  1948 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 15:23:14.097  1505  1505 I ConfigService: onCreate
,09-08 15:23:16.425   874   891 I ActivityManager: Start proc 4147:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 15:23:16.569  4147  4147 D AdapterServiceConfig: Adding HeadsetService
,09-08 15:23:16.570  4147  4147 D AdapterServiceConfig: Adding A2dpService
,09-08 15:23:16.570  4147  4147 D AdapterServiceConfig: Adding HidService
,09-08 15:23:16.571  4147  4147 D AdapterServiceConfig: Adding HealthService
09-08 15:23:16.572  4147  4147 D AdapterServiceConfig: Adding PanService
09-08 15:23:16.572  4147  4147 D AdapterServiceConfig: Adding GattService
,09-08 15:23:16.573  4147  4147 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 15:23:16.601   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53605b1:true
09-08 15:23:16.602  4147  4147 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 15:23:16.609  4147  4147 I bt_bluedroid: init
,09-08 15:23:16.609  4147  4159 I BluetoothAdapterState: Entering OffState
,09-08 15:23:16.614  4147  4160 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 15:23:16.615  4147  4160 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 15:23:16.615  4147  4160 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 15:23:16.615  4147  4160 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 15:23:16.617  4147  4147 I bt_bluedroid: get_profile_interface socket
,09-08 15:23:16.619  4147  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 15:23:16.620  4147  4147 I bt_bluedroid: get_profile_interface sdp
09-08 15:23:16.622  4147  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 15:23:16.624  4147  4158 I bt_bluedroid: config_hci_snoop_log
,09-08 15:23:16.627   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 15:23:16.637  4147  4159 D BluetoothAdapterState: Current state: OFF, message: 0,
09-08 15:23:16.638  4147  4159 D BluetoothAdapterProperties: Setting state to 14
,09-08 15:23:16.639  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 15:23:16.644  4147  4159 D BluetoothBondStateMachine: make
,09-08 15:23:16.648  4147  4164 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 15:23:16.656  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
,09-08 15:23:16.657  4147  4147 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 15:23:16.666  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:16.668  4147  4147 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 15:23:16.669  4147  4147 D BtGatt.GattService: Received start request. Starting profile...
09-08 15:23:16.670  4147  4147 D BtGatt.GattService: start()
,09-08 15:23:16.670  4147  4147 I bt_bluedroid: get_profile_interface gatt
,09-08 15:23:16.672  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:16.673  4147  4147 D BtGatt.AdvertiseManager: advertise manager created
,09-08 15:23:16.684  4147  4147 V BluetoothAdapterState: isTurningOff()=false
,09-08 15:23:16.684  4147  4147 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:16.684  4147  4147 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 15:23:16.684  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:16.685  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 15:23:16.686  4147  4159 I bt_bluedroid: enable
09-08 15:23:16.686  4147  4160 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 15:23:16.687  4147  4160 I bt_hci  : start_up
,09-08 15:23:16.708  4147  4160 I bt_vendor: alloc value 0xb3a0a189
,09-08 15:23:16.709  4147  4160 I bt_vendor: init
09-08 15:23:16.709  4147  4160 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 15:23:16.709  4147  4160 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 15:23:16.794   874  1319 D ConnectivityService: handlePromptUnvalidated 101
,09-08 15:23:16.820  4147  4160 D bt_hci  : start_up starting async portion
,09-08 15:23:16.821  4147  4167 I bt_hci  : event_finish_startup
,09-08 15:23:16.822  4147  4167 I bt_hci_h4: hal_open
,09-08 15:23:16.822  4147  4167 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 15:23:16.832  4147  4167 I bt_userial_vendor: device fd = 51 open
,09-08 15:23:16.860  4147  4167 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 15:23:16.892  4147  4167 D bt_hwcfg: Chipset BCM4354A2
,09-08 15:23:16.892  4147  4167 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 15:23:16.893  4147  4167 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 15:23:17.549  4147  4167 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 15:23:17.550  4147  4167 D bt_hwcfg: Settlement delay -- 100 ms
09-08 15:23:17.550  4147  4167 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 15:23:17.667  4147  4167 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 15:23:17.668  4147  4167 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 15:23:17.699  4147  4167 I bt_hwcfg: vendor lib fwcfg completed
,09-08 15:23:17.699  4147  4167 I bt_vendor: firmware callback
09-08 15:23:17.699  4147  4167 I bt_hci  : firmware_config_callback
,09-08 15:23:17.711  4147  4171 I bt_btu  : btu_task pending for preload complete event
,09-08 15:23:17.711  4147  4171 I bt_btu_task: Bluetooth chip preload is complete,
,09-08 15:23:17.711  4147  4171 I bt_btu  : btu_task received preload complete event
,09-08 15:23:17.722  4147  4171 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 15:23:17.723  4147  4171 I         : BTE_InitTraceLevels -- TRC_L2CAP,
09-08 15:23:17.723  4147  4171 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 15:23:17.723  4147  4171 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 15:23:17.724  4147  4171 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 15:23:17.724  4147  4171 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 15:23:17.724  4147  4171 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 15:23:17.724  4147  4171 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 15:23:17.724  4147  4171 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 15:23:17.725  4147  4171 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 15:23:17.725  4147  4171 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 15:23:17.725  4147  4171 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 15:23:17.726  4147  4171 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 15:23:17.726  4147  4171 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 15:23:17.726  4147  4171 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 15:23:17.859  4147  4171 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3987d9d
,09-08 15:23:17.859  4147  4171 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3987d9d 
,09-08 15:23:17.869  4147  4163 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 15:23:17.870  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 15:23:17.871  4147  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 15:23:17.874  4147  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 15:23:17.879  4147  4163 D BluetoothAdapterProperties: Scan Mode:20
,09-08 15:23:17.880  4147  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 15:23:17.881  4147  4163 D bt_hci  : do_postload posting postload work item
,09-08 15:23:17.882  4147  4167 I bt_hci  : event_postload
,09-08 15:23:17.882  4147  4167 I bt_vendor: sco_config_cb
,09-08 15:23:17.882  4147  4167 I bt_hci  : sco_config_callback postload finished.,
,09-08 15:23:17.884  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:17.887  4147  4163 D bt_bte_conf: Device ID record 1 : primary
,09-08 15:23:17.888  4147  4163 D bt_bte_conf:   vendorId            = 000f
,09-08 15:23:17.888  4147  4163 D bt_bte_conf:   vendorIdSource      = 0001
09-08 15:23:17.889  4147  4163 D bt_bte_conf:   product             = 1200
09-08 15:23:17.889  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:17.889  4147  4163 D bt_bte_conf:   version             = 1436
09-08 15:23:17.889  4147  4163 D bt_bte_conf:   clientExecutableURL = 
09-08 15:23:17.890  4147  4163 D bt_bte_conf:   serviceDescription  = ,
09-08 15:23:17.890  4147  4163 D bt_bte_conf:   documentationURL    = 
09-08 15:23:17.890  4147  4163 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 15:23:17.891  4147  4160 D bt_stack_manager: event_start_up_stack finished
09-08 15:23:17.892  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 15:23:17.893  4147  4167 I bt_vendor: low_power_mode_cb
,09-08 15:23:17.893  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:17.893  4147  4159 D BluetoothAdapterProperties: Setting state to 15
09-08 15:23:17.893  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 15:23:17.897  4147  4159 I BluetoothAdapterState: Entering BleOnState
,09-08 15:23:17.900  4147  4159 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 15:23:17.901  4147  4159 D BluetoothAdapterProperties: Setting state to 11
09-08 15:23:17.901  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 15:23:17.906  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:17.907  4147  4147 D HeadsetService: Received start request. Starting profile...
09-08 15:23:17.911  4147  4147 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 15:23:17.911  4147  4147 D HeadsetStateMachine: make
09-08 15:23:17.918  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:17.920  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
09-08 15:23:17.922  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:17.923  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:17.925  4147  4147 D HeadsetStateMachine: max_hf_connections = 1
09-08 15:23:17.925  4147  4147 I bt_bluedroid: get_profile_interface handsfree
09-08 15:23:17.925  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 15:23:17.926  4147  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index 1024
,09-08 15:23:17.930  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:17.931  4147  4147 D A2dpService: Received start request. Starting profile...
,09-08 15:23:17.931  4147  4147 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 15:23:17.932  4147  4147 I bt_bluedroid: get_profile_interface avrcp
,09-08 15:23:17.938  4147  4147 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 15:23:17.938  4147  4147 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 15:23:17.939  4147  4147 D A2dpStateMachine: make
,09-08 15:23:17.940  4147  4147 I bt_bluedroid: get_profile_interface a2dp
,09-08 15:23:17.941  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 15:23:17.943  4147  4182 D A2dpStateMachine: Enter Disconnected: -2
,09-08 15:23:17.943  4147  4147 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 15:23:17.944  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:17.946  3916  3916 D BluetoothInputDevice: Proxy object connected
,09-08 15:23:17.946  4147  4147 D HidService: Received start request. Starting profile...
,09-08 15:23:17.946  4147  4147 I bt_bluedroid: get_profile_interface hidhost
09-08 15:23:17.946  4147  4147 D HidService: setHidService(): set to: null
,09-08 15:23:17.946  4147  4163 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39693e5
09-08 15:23:17.947  4147  4147 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 15:23:17.947  3916  3916 D HidProfile: Bluetooth service connected
09-08 15:23:17.947  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 15:23:17.947  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:17.948  4147  4147 D HealthService: Received start request. Starting profile...
09-08 15:23:17.950  4147  4147 I bt_bluedroid: get_profile_interface health
09-08 15:23:17.951  4147  4147 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 15:23:17.951  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:17.953  3916  3916 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 15:23:17.953  4147  4147 D PanService: Received start request. Starting profile...
09-08 15:23:17.953  4147  4147 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 15:23:17.953  4147  4147 I bt_bluedroid: get_profile_interface pan
09-08 15:23:17.953  3916  3916 D PanProfile: Bluetooth service connected
09-08 15:23:17.954  4147  4163 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 15:23:17.956  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:17.958  3916  3916 D BluetoothMap: Proxy object connected
,09-08 15:23:17.958  4147  4147 D BluetoothMapService: Received start request. Starting profile...
09-08 15:23:17.958  4147  4147 D BluetoothMapService: start()
,09-08 15:23:17.959  3916  3916 D MapProfile: Bluetooth service connected
,09-08 15:23:17.959  3916  3916 D BluetoothMap: getConnectedDevices()
09-08 15:23:17.960  3916  3916 D BluetoothMap: Bluetooth is Not enabled
09-08 15:23:17.960  4147  4147 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-08 15:23:17.961  4147  4147 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 15:23:17.961  4147  4147 D BluetoothMapAppObserver: createReceiver()
,09-08 15:23:17.962  4147  4147 D BluetoothMapAppObserver: initObservers()
09-08 15:23:17.962  4147  4147 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 15:23:17.972  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 15:23:17.973  4147  4178 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 15:23:17.973  4147  4147 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:17.973  4147  4147 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:17.973  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:17.974  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:17.975  4147  4147 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:17.975  4147  4147 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:17.975  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:17.975  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:17.976  4147  4147 V BluetoothAdapterState: isTurningOff()=false
,09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:17.977  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:17.977  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 15:23:17.978  4147  4159 D BluetoothAdapterProperties: ScanMode =  20
09-08 15:23:17.978  4147  4159 D BluetoothAdapterProperties: State =  11
09-08 15:23:17.979  4147  4163 D BluetoothAdapterProperties: Scan Mode:21
09-08 15:23:17.980  4147  4159 D BluetoothAdapterProperties: Setting state to 12
09-08 15:23:17.980  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 15:23:17.980  4147  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 15:23:17.980  4147  4159 I BluetoothAdapterState: Entering OnState
09-08 15:23:17.980  3916  3930 D BluetoothMap: onBluetoothStateChange: up=true
09-08 15:23:17.981  1371  1732 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 15:23:17.984  1371  1385 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 15:23:17.984  1371  1371 D BluetoothA2dp: Proxy object connected
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:17.985  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:17.987   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 15:23:17.987  1371  1371 D BluetoothMap: Proxy object connected
09-08 15:23:17.987  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:17.987  1371  1371 D MapProfile: Bluetooth service connected
09-08 15:23:17.987  3916  3928 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 15:23:17.987  1371  1371 D BluetoothMap: getConnectedDevices()
,09-08 15:23:17.988   874   874 D BluetoothA2dp: Proxy object connected
09-08 15:23:17.990  4147  4147 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 15:23:17.991  3916  3930 D BluetoothPan: onBluetoothStateChange on: true
09-08 15:23:17.992  4147  4147 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 15:23:17.992  3916  3928 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:17.993  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:17.994  1371  1732 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 15:23:17.995  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:17.995  4147  4147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 15:23:17.996  1371  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 15:23:17.997  4147  4147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 15:23:17.999  4147  4147 D ObexServerSockets: Succeed to create listening sockets 
,09-08 15:23:17.999  4147  4147 D ObexServerSockets0: startAccept()
09-08 15:23:17.999  4147  4147 D ObexServerSockets0: prepareForNewConnect()
,09-08 15:23:17.999  1371  1371 D BluetoothInputDevice: Proxy object connected
,09-08 15:23:17.999  1371  1371 D HidProfile: Bluetooth service connected
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:17.999  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:18.001  4147  4147 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 15:23:18.001  4147  4147 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 15:23:18.002  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:18.002  4147  4187 D ObexServerSockets0: Accepting socket connection...
09-08 15:23:18.002  4147  4188 D ObexServerSockets0: Accepting socket connection...
09-08 15:23:18.002  1993  3532 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:18.002   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:18.002   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:18.003   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 15:23:18.003  1371  1732 D BluetoothPan: onBluetoothStateChange on: true
09-08 15:23:18.004  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 15:23:18.004  1371  1371 D PanProfile: Bluetooth service connected
09-08 15:23:18.005  1371  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:18.007  4147  4147 D BluetoothMapService: onReceive
,09-08 15:23:18.007  4147  4147 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 15:23:18.007  4147  4147 D BluetoothMapService: STATE_ON
09-08 15:23:18.007   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 15:23:18.009  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:18.010  3916  3916 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 15:23:18.010  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:18.012  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:18.015  3916  3916 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 15:23:18.020  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 15:23:18.023  3916  3916 D BluetoothA2dp: Proxy object connected
,09-08 15:23:18.027  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 15:23:18.033  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-08 15:23:18.037  1371  1371 D BluetoothPbap: Proxy object connected
,09-08 15:23:18.037  1371  1371 D PbapServerProfile: Bluetooth service connected
09-08 15:23:18.038  3916  3916 D BluetoothPbap: Proxy object connected
09-08 15:23:18.038  4147  4147 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 15:23:18.038  4147  4147 D ObexServerSockets0: prepareForNewConnect()
09-08 15:23:18.039  3916  3916 D PbapServerProfile: Bluetooth service connected
,09-08 15:23:18.048  4147  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 15:23:18.063  4147  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 15:23:18.065  4147  4196 I BtOppRfcommListener: Accept thread started.
,09-08 15:23:18.105   874   874 D BluetoothHeadset: Proxy object connected
,09-08 15:23:18.105   874   874 D BluetoothHeadset: Proxy object connected
09-08 15:23:18.105   874   874 D BluetoothHeadset: Proxy object connected
09-08 15:23:18.105  1371  1385 D BluetoothHeadset: Proxy object connected
,09-08 15:23:18.106  1371  1371 D HeadsetProfile: Bluetooth service connected
09-08 15:23:18.107  1993  2075 D BluetoothHeadset: Proxy object connected
09-08 15:23:18.107  1371  1732 D BluetoothHeadset: Proxy object connected
,09-08 15:23:18.110  1371  1371 D HeadsetProfile: Bluetooth service connected
,09-08 15:23:18.119  3916  3930 D BluetoothHeadset: Proxy object connected
,09-08 15:23:18.121  3916  3916 D HeadsetProfile: Bluetooth service connected
,09-08 15:23:19.170  1505  1505 I ConfigService: onDestroy
,09-08 15:23:21.387  4147  4159 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 15:23:21.388  4147  4159 D BluetoothAdapterProperties: Setting state to 13
,09-08 15:23:21.388  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 15:23:21.390  4147  4159 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 15:23:21.394  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
,09-08 15:23:21.403  4147  4147 D BluetoothMapService: onReceive
,09-08 15:23:21.404  4147  4147 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 15:23:21.404  4147  4147 D BluetoothMapService: STATE_TURNING_OFF
,09-08 15:23:21.405  4147  4147 D BluetoothMapService: MAP Service closeService in
,09-08 15:23:21.405  4147  4147 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 15:23:21.406  4147  4147 D ObexServerSockets0: shutdown(block = true)
09-08 15:23:21.406  4147  4187 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 15:23:21.411  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:21.411  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:21.412  4147  4147 D ObexServerSockets0: shutdown called from another thread - interrupt().,
09-08 15:23:21.413  4147  4188 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 15:23:21.414  4147  4163 D BluetoothAdapterProperties: Scan Mode:20
09-08 15:23:21.416  4147  4174 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 15:23:21.416  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 15:23:21.417  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:21.416  4147  4147 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 15:23:21.417  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-08 15:23:21.417  4147  4147 I BtOppRfcommListener: stopping Accept Thread
09-08 15:23:21.418  4147  4196 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 15:23:21.420  4147  4196 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 15:23:21.420  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:21.421  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:21.422  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:21.422  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:21.422  4147  4147 D HeadsetService: Received stop request...Stopping profile...
,09-08 15:23:21.423   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:21.424  3916  3930 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:21.424   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:21.424   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:21.424  4147  4147 D A2dpService: Received stop request...Stopping profile...
09-08 15:23:21.425  1993  2006 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:21.425  4147  4182 D A2dpStateMachine: Exit Disconnected: -1
,09-08 15:23:21.426  1371  1384 D BluetoothHeadset: Proxy object disconnected
09-08 15:23:21.426   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 15:23:21.427  4147  4147 D HidService: Received stop request...Stopping profile...
09-08 15:23:21.427  4147  4147 D HidService: Stopping Bluetooth HidService
09-08 15:23:21.428  4147  4147 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:21.428  4147  4147 V BluetoothAdapterState: isTurningOn()=false
,09-08 15:23:21.429  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.429  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:21.429  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:21.429  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:21.430  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 15:23:21.430  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 15:23:21.430  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:21.432  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:21.433  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:21.434  4147  4147 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:21.434  4147  4147 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:21.434  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.434  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:21.434  3916  3916 D HeadsetProfile: Bluetooth service disconnected
09-08 15:23:21.434  4147  4147 D HealthService: Received stop request...Stopping profile...
09-08 15:23:21.435  3916  3916 D BluetoothA2dp: Proxy object disconnected
,09-08 15:23:21.436  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:21.436  3916  3916 D BluetoothInputDevice: Proxy object disconnected
09-08 15:23:21.436  3916  3916 D HidProfile: Bluetooth service disconnected
09-08 15:23:21.437  4147  4147 D PanService: Received stop request...Stopping profile...
09-08 15:23:21.439  4147  4147 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 15:23:21.439  1371  1371 D HeadsetProfile: Bluetooth service disconnected
09-08 15:23:21.439  4147  4147 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 15:23:21.440  4147  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:21.439  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 15:23:21.440  4147  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 15:23:21.440  4147  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:21.440  4147  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 15:23:21.440  1371  1371 D BluetoothA2dp: Proxy object disconnected
,09-08 15:23:21.440  1371  1371 D BluetoothInputDevice: Proxy object disconnected
09-08 15:23:21.440  1371  1371 D HidProfile: Bluetooth service disconnected
09-08 15:23:21.441  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 15:23:21.441  1371  1371 D PanProfile: Bluetooth service disconnected
09-08 15:23:21.441  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 15:23:21.441  4147  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:21.441  4147  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 15:23:21.441  4147  4171 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 15:23:21.441  4147  4171 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 15:23:21.441  4147  4147 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:21.441  4147  4171 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 15:23:21.441  4147  4147 V BluetoothAdapterState: isTurningOn()=false
,09-08 15:23:21.441  4147  4171 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 15:23:21.441  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.441  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:21.442  4147  4147 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 15:23:21.442  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 15:23:21.442  4147  4147 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 15:23:21.443  4147  4147 D BluetoothMapService: Received stop request...Stopping profile...
09-08 15:23:21.443  4147  4147 D BluetoothMapService: stop()
09-08 15:23:21.444  3916  3916 D DockEventReceiver: finishStartingService: stopping service
09-08 15:23:21.444  4147  4147 D BluetoothMapAppObserver: deinitObservers()
09-08 15:23:21.445  4147  4147 D BluetoothMapAppObserver: removeReceiver()
09-08 15:23:21.446  4147  4147 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:21.446  4147  4147 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:21.446  1371  1371 D BluetoothMap: Proxy object disconnected
,09-08 15:23:21.446  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.446  1371  1371 D MapProfile: Bluetooth service disconnected
09-08 15:23:21.446  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:21.446  3916  3916 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 15:23:21.446  3916  3916 D PanProfile: Bluetooth service disconnected
09-08 15:23:21.448  4147  4147 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 15:23:21.448  4147  4163 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 15:23:21.448  4147  4147 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 15:23:21.449  4147  4147 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:21.449  4147  4147 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:21.449  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.449  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:21.449  4147  4147 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 15:23:21.449  4147  4147 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 15:23:21.451  4147  4147 D BluetoothMapService: MAP Service closeService in
,09-08 15:23:21.451  4147  4147 V BluetoothAdapterState: isTurningOff()=true
09-08 15:23:21.451  4147  4147 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:21.451  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.451  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:21.451  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 15:23:21.452  4147  4159 D BluetoothAdapterProperties: Setting state to 15
09-08 15:23:21.452  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 15:23:21.452  3916  3930 D BluetoothMap: onBluetoothStateChange: up=false
09-08 15:23:21.453  4147  4147 D BluetoothMapService: cleanup()
09-08 15:23:21.453  4147  4147 D BluetoothMapService: MAP Service closeService in
09-08 15:23:21.453  4147  4159 I BluetoothAdapterState: Entering BleOnState
09-08 15:23:21.454  1371  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 15:23:21.454  1371  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-08 15:23:21.455  1371  1371 D BluetoothPbap: Proxy object disconnected
,09-08 15:23:21.455  1371  1371 D PbapServerProfile: Bluetooth service disconnected
09-08 15:23:21.457   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 15:23:21.457  3916  3930 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 15:23:21.458  3916  3928 D BluetoothPan: onBluetoothStateChange on: false
09-08 15:23:21.458  3916  3930 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 15:23:21.459  3916  3928 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 15:23:21.459  1371  1732 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 15:23:21.460  1371  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 15:23:21.460  1993  2012 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:21.461   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:21.461   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 15:23:21.461   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:21.461  1371  1384 D BluetoothPan: onBluetoothStateChange on: false
09-08 15:23:21.462  3916  3930 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:21.462  1371  1732 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 15:23:21.462  4147  4159 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 15:23:21.462  4147  4159 D BluetoothAdapterProperties: Setting state to 16
09-08 15:23:21.462  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-08 15:23:21.463  4147  4159 D BluetoothAdapterProperties: onBleDisable
09-08 15:23:21.463  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
09-08 15:23:21.464  4147  4160 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 15:23:21.464  4147  4171 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 15:23:21.464  4147  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 15:23:21.465  4147  4163 D BluetoothAdapterProperties: Scan Mode:20
,09-08 15:23:21.466  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:21.467  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:21.467  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 15:23:21.468  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:21.470  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:21.471  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:21.472  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:21.478  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 15:23:21.481  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 15:23:21.484  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-08 15:23:21.669  4147  4163 I bt_hci  : shut_down
09-08 15:23:21.670  4147  4167 D bt_hwcfg: hw_epilog_process
,09-08 15:23:21.680  4147  4167 I bt_vendor: low_power_mode_cb
,09-08 15:23:21.704  4147  4167 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 15:23:21.705  4147  4167 I bt_vendor: epilog_cb
09-08 15:23:21.705  4147  4167 I bt_hci  : epilog_finished_callback
,09-08 15:23:21.713  4147  4163 I bt_hci_h4: hal_close
,09-08 15:23:21.714  4147  4163 I bt_userial_vendor: device fd = 51 close
,09-08 15:23:21.842  4147  4160 D bt_stack_manager: event_shut_down_stack finished.
,09-08 15:23:21.843  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 15:23:21.850  4147  4147 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 15:23:21.850  4147  4159 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 15:23:21.851  4147  4147 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 15:23:21.852  4147  4147 D BtGatt.GattService: stop()
,09-08 15:23:21.852  4147  4147 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 15:23:21.860  4147  4147 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:21.861  4147  4147 V BluetoothAdapterState: isTurningOn()=false
,09-08 15:23:21.861  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:21.861  4147  4147 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 15:23:21.862  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 15:23:21.863  4147  4159 D BluetoothAdapterProperties: Setting state to 10
,09-08 15:23:21.863  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 15:23:21.864  4147  4159 I BluetoothAdapterState: Entering OffState
09-08 15:23:21.866   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 15:23:21.889  4147  4147 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 15:23:21.889  4147  4147 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 15:23:21.890  4147  4160 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 15:23:21.892  4147  4160 D bt_stack_manager: event_clean_up_stack finished.
09-08 15:23:21.892  4147  4147 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 15:23:21.894  4147  4147 I art     : System.exit called, status: 0
,09-08 15:23:21.894  4147  4147 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 15:23:21.949   874  2272 I ActivityManager: Process com.android.bluetooth (pid 4147) has died
,09-08 15:23:26.385  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:23:26.385  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:26.391  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:23:26.391  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f6bdc7 removed from the list
,09-08 15:23:26.391  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:23:26.392  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:23:26.392  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:26.396  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 15:23:26.397  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@127a31d added. We now have 4 listener(s)
09-08 15:23:26.398  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:23:26.400  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:23:26.400  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@127a31d removed from the list
,09-08 15:23:26.400  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:23:26.401  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:26.401  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:23:26.404  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:23:26.404  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7017992 added. We now have 4 listener(s)
09-08 15:23:26.405  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:23:31.420  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:31.460   874   891 I ActivityManager: Start proc 4209:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 15:23:31.604  4209  4209 D AdapterServiceConfig: Adding HeadsetService
,09-08 15:23:31.605  4209  4209 D AdapterServiceConfig: Adding A2dpService
,09-08 15:23:31.605  4209  4209 D AdapterServiceConfig: Adding HidService
09-08 15:23:31.605  4209  4209 D AdapterServiceConfig: Adding HealthService
09-08 15:23:31.605  4209  4209 D AdapterServiceConfig: Adding PanService
09-08 15:23:31.605  4209  4209 D AdapterServiceConfig: Adding GattService
09-08 15:23:31.606  4209  4209 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 15:23:31.620  4209  4209 D BluetoothAdapterState: make() - Creating AdapterState
09-08 15:23:31.620   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60c028a:true
,09-08 15:23:31.626  4209  4209 I bt_bluedroid: init
,09-08 15:23:31.627  4209  4221 I BluetoothAdapterState: Entering OffState
,09-08 15:23:31.634  4209  4222 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 15:23:31.634  4209  4222 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 15:23:31.634  4209  4222 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 15:23:31.635  4209  4222 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 15:23:31.638  4209  4209 I bt_bluedroid: get_profile_interface socket
,09-08 15:23:31.642  4209  4225 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 15:23:31.644  4209  4225 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 15:23:31.644  4209  4209 I bt_bluedroid: get_profile_interface sdp
,09-08 15:23:31.651  4209  4220 I bt_bluedroid: config_hci_snoop_log
,09-08 15:23:31.656   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 15:23:31.671  4209  4221 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 15:23:31.671  4209  4221 D BluetoothAdapterProperties: Setting state to 14
,09-08 15:23:31.672  4209  4221 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 15:23:31.676  4209  4221 D BluetoothBondStateMachine: make
,09-08 15:23:31.685  4209  4226 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 15:23:31.696  4209  4221 I BluetoothAdapterState: Entering PendingCommandState
,09-08 15:23:31.699  4209  4209 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 15:23:31.709  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:31.711  4209  4209 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 15:23:31.713  4209  4209 D BtGatt.GattService: Received start request. Starting profile...
,09-08 15:23:31.713  4209  4209 D BtGatt.GattService: start()
09-08 15:23:31.714  4209  4209 I bt_bluedroid: get_profile_interface gatt
,09-08 15:23:31.717  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:31.717  4209  4209 D BtGatt.AdvertiseManager: advertise manager created
,09-08 15:23:31.737  4209  4209 V BluetoothAdapterState: isTurningOff()=false
,09-08 15:23:31.737  4209  4209 V BluetoothAdapterState: isTurningOn()=false
09-08 15:23:31.737  4209  4209 V BluetoothAdapterState: isBleTurningOn()=true
09-08 15:23:31.738  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:31.739  4209  4221 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 15:23:31.741  4209  4221 I bt_bluedroid: enable
09-08 15:23:31.741  4209  4222 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 15:23:31.743  4209  4222 I bt_hci  : start_up
,09-08 15:23:31.771  4209  4222 I bt_vendor: alloc value 0xb3a0a189
09-08 15:23:31.772  4209  4222 I bt_vendor: init
09-08 15:23:31.772  4209  4222 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 15:23:31.772  4209  4222 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 15:23:31.879  4209  4222 D bt_hci  : start_up starting async portion
09-08 15:23:31.880  4209  4229 I bt_hci  : event_finish_startup
09-08 15:23:31.880  4209  4229 I bt_hci_h4: hal_open
,09-08 15:23:31.880  4209  4229 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 15:23:31.890  4209  4229 I bt_userial_vendor: device fd = 51 open
,09-08 15:23:31.924  4209  4229 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 15:23:31.956  4209  4229 D bt_hwcfg: Chipset BCM4354A2
09-08 15:23:31.956  4209  4229 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 15:23:31.957  4209  4229 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 15:23:32.802  4209  4229 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 15:23:32.804  4209  4229 D bt_hwcfg: Settlement delay -- 100 ms
09-08 15:23:32.805  4209  4229 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 15:23:32.923  4209  4229 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 15:23:32.925  4209  4229 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 15:23:32.952  4209  4229 I bt_hwcfg: vendor lib fwcfg completed
09-08 15:23:32.952  4209  4229 I bt_vendor: firmware callback
,09-08 15:23:32.952  4209  4229 I bt_hci  : firmware_config_callback
,09-08 15:23:32.965  4209  4231 I bt_btu  : btu_task pending for preload complete event
,09-08 15:23:32.966  4209  4231 I bt_btu_task: Bluetooth chip preload is complete
,09-08 15:23:32.966  4209  4231 I bt_btu  : btu_task received preload complete event
,09-08 15:23:32.976  4209  4231 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 15:23:32.976  4209  4231 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 15:23:32.976  4209  4231 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 15:23:32.977  4209  4231 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 15:23:32.977  4209  4231 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 15:23:32.977  4209  4231 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 15:23:32.977  4209  4231 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 15:23:32.978  4209  4231 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 15:23:32.978  4209  4231 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 15:23:32.978  4209  4231 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 15:23:32.978  4209  4231 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 15:23:32.979  4209  4231 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 15:23:32.979  4209  4231 I         : BTE_InitTraceLevels -- TRC_SMP,
09-08 15:23:32.979  4209  4231 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 15:23:32.979  4209  4231 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 15:23:33.121  4209  4231 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3987d9d
,09-08 15:23:33.122  4209  4231 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3987d9d 
,09-08 15:23:33.147  4209  4225 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-08 15:23:33.150  4209  4225 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 15:23:33.151  4209  4225 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 15:23:33.154  4209  4225 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 15:23:33.157  4209  4225 D BluetoothAdapterProperties: Scan Mode:20
,09-08 15:23:33.158  4209  4225 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 15:23:33.158  4209  4225 D bt_hci  : do_postload posting postload work item
,09-08 15:23:33.159  4209  4229 I bt_hci  : event_postload
,09-08 15:23:33.159  4209  4229 I bt_vendor: sco_config_cb
09-08 15:23:33.159  4209  4229 I bt_hci  : sco_config_callback postload finished.
,09-08 15:23:33.161  4209  4225 D bt_bte_conf: Device ID record 1 : primary
09-08 15:23:33.162  4209  4225 D bt_bte_conf:   vendorId            = 000f
09-08 15:23:33.162  4209  4225 D bt_bte_conf:   vendorIdSource      = 0001
09-08 15:23:33.162  4209  4225 D bt_bte_conf:   product             = 1200
,09-08 15:23:33.162  4209  4225 D bt_bte_conf:   version             = 1436
09-08 15:23:33.162  4209  4225 D bt_bte_conf:   clientExecutableURL = 
09-08 15:23:33.163  4209  4225 D bt_bte_conf:   serviceDescription  = 
09-08 15:23:33.163  4209  4225 D bt_bte_conf:   documentationURL    = 
09-08 15:23:33.163  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:33.163  4209  4225 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 15:23:33.164  4209  4222 D bt_stack_manager: event_start_up_stack finished
,09-08 15:23:33.166  4209  4229 I bt_vendor: low_power_mode_cb
09-08 15:23:33.166  4209  4221 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 15:23:33.168  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:33.169  4209  4221 D BluetoothAdapterProperties: Setting state to 15
09-08 15:23:33.169  4209  4221 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 15:23:33.170  4209  4221 I BluetoothAdapterState: Entering BleOnState
,09-08 15:23:33.176  4209  4221 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 15:23:33.176  4209  4221 D BluetoothAdapterProperties: Setting state to 11
,09-08 15:23:33.176  4209  4221 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 15:23:33.184  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:33.188  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:33.190  4209  4209 D HeadsetService: Received start request. Starting profile...
,09-08 15:23:33.190  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:33.193  4209  4209 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 15:23:33.193  4209  4209 D HeadsetStateMachine: make
,09-08 15:23:33.196  4209  4221 I BluetoothAdapterState: Entering PendingCommandState
,09-08 15:23:33.205  4209  4209 D HeadsetStateMachine: max_hf_connections = 1
,09-08 15:23:33.205  4209  4209 I bt_bluedroid: get_profile_interface handsfree
09-08 15:23:33.206  4209  4225 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 15:23:33.206  4209  4225 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 15:23:33.212  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:33.212  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 15:23:33.213  4209  4209 D A2dpService: Received start request. Starting profile...
,09-08 15:23:33.216  4209  4209 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 15:23:33.216  4209  4209 I bt_bluedroid: get_profile_interface avrcp
,09-08 15:23:33.223  4209  4209 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 15:23:33.224  4209  4209 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 15:23:33.224  4209  4209 D A2dpStateMachine: make
,09-08 15:23:33.225  4209  4209 I bt_bluedroid: get_profile_interface a2dp
,09-08 15:23:33.226  4209  4225 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-08 15:23:33.227  4209  4241 D A2dpStateMachine: Enter Disconnected: -2
09-08 15:23:33.228  4209  4209 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 15:23:33.229  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:33.229  4209  4209 D HidService: Received start request. Starting profile...
09-08 15:23:33.229  4209  4209 I bt_bluedroid: get_profile_interface hidhost
09-08 15:23:33.230  4209  4225 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39693e5
09-08 15:23:33.230  4209  4225 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 15:23:33.230  4209  4209 D HidService: setHidService(): set to: null
09-08 15:23:33.230  4209  4209 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 15:23:33.231  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:33.232  4209  4209 D HealthService: Received start request. Starting profile...
,09-08 15:23:33.236  4209  4209 I bt_bluedroid: get_profile_interface health
09-08 15:23:33.236  4209  4209 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 15:23:33.237  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:33.238  4209  4209 D PanService: Received start request. Starting profile...
,09-08 15:23:33.238  4209  4209 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 15:23:33.238  4209  4209 I bt_bluedroid: get_profile_interface pan
,09-08 15:23:33.240  4209  4225 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 15:23:33.241  4209  4209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
09-08 15:23:33.241  4209  4209 D BluetoothMapService: Received start request. Starting profile...
09-08 15:23:33.242  4209  4209 D BluetoothMapService: start()
,09-08 15:23:33.244  4209  4209 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 15:23:33.245  4209  4209 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 15:23:33.245  4209  4209 D BluetoothMapAppObserver: createReceiver()
,09-08 15:23:33.246  4209  4209 D BluetoothMapAppObserver: initObservers()
09-08 15:23:33.246  4209  4209 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 15:23:33.253  4209  4239 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 15:23:33.254  4209  4209 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:33.254  4209  4209 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:33.254  4209  4209 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:33.254  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:33.257  4209  4209 V BluetoothAdapterState: isTurningOff()=false
,09-08 15:23:33.257  4209  4209 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:33.257  4209  4209 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 15:23:33.257  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:33.257  4209  4209 V BluetoothAdapterState: isTurningOff()=false
,09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isTurningOn()=true
,09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isTurningOff()=false
,09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:33.258  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 15:23:33.259  4209  4209 V BluetoothAdapterState: isTurningOff()=false
09-08 15:23:33.259  4209  4209 V BluetoothAdapterState: isTurningOn()=true
09-08 15:23:33.259  4209  4209 V BluetoothAdapterState: isBleTurningOn()=false
09-08 15:23:33.259  4209  4209 V BluetoothAdapterState: isBleTurningOff()=false
09-08 15:23:33.259  4209  4221 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 15:23:33.260  4209  4221 D BluetoothAdapterProperties: ScanMode =  20
09-08 15:23:33.260  4209  4221 D BluetoothAdapterProperties: State =  11
09-08 15:23:33.261  4209  4225 D BluetoothAdapterProperties: Scan Mode:21
09-08 15:23:33.261  4209  4225 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 15:23:33.262  4209  4221 D BluetoothAdapterProperties: Setting state to 12
09-08 15:23:33.262  4209  4221 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 15:23:33.263  3916  3928 D BluetoothMap: onBluetoothStateChange: up=true
09-08 15:23:33.263  4209  4221 I BluetoothAdapterState: Entering OnState
09-08 15:23:33.265  1371  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 15:23:33.266  3916  3916 D BluetoothMap: Proxy object connected
09-08 15:23:33.266  3916  3916 D MapProfile: Bluetooth service connected
09-08 15:23:33.266  3916  3916 D BluetoothMap: getConnectedDevices()
,09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:33.268  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 15:23:33.268  1371  1384 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 15:23:33.268  1371  1371 D BluetoothA2dp: Proxy object connected
,09-08 15:23:33.270  1371  1371 D BluetoothMap: Proxy object connected
09-08 15:23:33.270  1371  1371 D MapProfile: Bluetooth service connected
09-08 15:23:33.270  1371  1371 D BluetoothMap: getConnectedDevices()
09-08 15:23:33.270   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 15:23:33.271  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:33.271   874   874 D BluetoothA2dp: Proxy object connected
09-08 15:23:33.272  4209  4209 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 15:23:33.272  4209  4209 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 15:23:33.274  3916  3928 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 15:23:33.275  3916  3930 D BluetoothPan: onBluetoothStateChange on: true
09-08 15:23:33.276  4209  4209 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 15:23:33.277  3916  3928 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:33.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 15:23:33.279  3916  3930 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 15:23:33.279  4209  4209 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 15:23:33.280  3916  3916 D BluetoothA2dp: Proxy object connected
09-08 15:23:33.280  1371  1385 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 15:23:33.281  4209  4209 D ObexServerSockets: Succeed to create listening sockets 
09-08 15:23:33.281  4209  4209 D ObexServerSockets0: startAccept()
09-08 15:23:33.281  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:33.281  4209  4209 D ObexServerSockets0: prepareForNewConnect()
09-08 15:23:33.281  1371  1732 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 15:23:33.284  1993  2012 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:33.284   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:33.284   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:33.285   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:33.285  4209  4248 D ObexServerSockets0: Accepting socket connection...
09-08 15:23:33.285  1371  1384 D BluetoothPan: onBluetoothStateChange on: true
,09-08 15:23:33.285  4209  4209 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 15:23:33.285  4209  4209 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 15:23:33.286  4209  4249 D ObexServerSockets0: Accepting socket connection...
09-08 15:23:33.288  3916  3928 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 15:23:33.288  1371  1371 D BluetoothInputDevice: Proxy object connected
09-08 15:23:33.288  1371  1371 D HidProfile: Bluetooth service connected
09-08 15:23:33.289  3916  3916 D BluetoothInputDevice: Proxy object connected
09-08 15:23:33.289  3916  3916 D HidProfile: Bluetooth service connected
,09-08 15:23:33.289  1371  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 15:23:33.290  3916  3916 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 15:23:33.290  3916  3916 D PanProfile: Bluetooth service connected
09-08 15:23:33.291  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 15:23:33.291   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 15:23:33.291  1371  1371 D PanProfile: Bluetooth service connected
09-08 15:23:33.292  4209  4209 D BluetoothMapService: onReceive
09-08 15:23:33.292  4209  4209 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 15:23:33.292  4209  4209 D BluetoothMapService: STATE_ON
,09-08 15:23:33.294  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:33.297  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:33.298  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 15:23:33.305  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 15:23:33.306  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-08 15:23:33.316  3916  3916 D BluetoothPbap: Proxy object connected
,09-08 15:23:33.316  3916  3916 D PbapServerProfile: Bluetooth service connected
,09-08 15:23:33.319  1371  1371 D BluetoothPbap: Proxy object connected
,09-08 15:23:33.319  1371  1371 D PbapServerProfile: Bluetooth service connected
,09-08 15:23:33.322  4209  4209 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 15:23:33.322  4209  4209 D ObexServerSockets0: prepareForNewConnect()
,09-08 15:23:33.326  4209  4253 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 15:23:33.340  4209  4257 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 15:23:33.342  4209  4257 I BtOppRfcommListener: Accept thread started.
,09-08 15:23:33.387   874   874 D BluetoothHeadset: Proxy object connected
,09-08 15:23:33.388  3916  4247 D BluetoothHeadset: Proxy object connected
09-08 15:23:33.388  3916  3916 D HeadsetProfile: Bluetooth service connected
,09-08 15:23:33.389   874   874 D BluetoothHeadset: Proxy object connected
09-08 15:23:33.389  3916  3930 D BluetoothHeadset: Proxy object connected
09-08 15:23:33.389   874   874 D BluetoothHeadset: Proxy object connected
,09-08 15:23:33.390  1371  1732 D BluetoothHeadset: Proxy object connected
09-08 15:23:33.390  1993  3532 D BluetoothHeadset: Proxy object connected
09-08 15:23:33.390  1371  1371 D HeadsetProfile: Bluetooth service connected
,09-08 15:23:33.391  1371  1385 D BluetoothHeadset: Proxy object connected
09-08 15:23:33.392  3916  3916 D HeadsetProfile: Bluetooth service connected
,09-08 15:23:33.392  1371  1371 D HeadsetProfile: Bluetooth service connected
,09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:36.439  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 15:23:36.447  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:36.448  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:23:36.449  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7017992 removed from the list
,09-08 15:23:36.449  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:23:36.449  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:36.450  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:23:36.452  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 15:23:36.453  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7976f63 added. We now have 4 listener(s)
09-08 15:23:36.453  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:23:36.457   874  2036 D WifiService: setWifiEnabled: false pid=3859, uid=10000
,09-08 15:23:36.458   874  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 15:23:41.472  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:41.473   874  1929 D WifiService: setWifiEnabled: true pid=3859, uid=10000
,09-08 15:23:41.473   874  1929 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 15:23:41.484   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:41.508  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 15:23:41.511  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 15:23:41.516  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 15:23:41.517   874  1315 D WifiConfigStore: loaded 0 passpoint configs
09-08 15:23:41.518   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 15:23:41.518   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 15:23:41.519  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 15:23:41.519   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 15:23:41.519   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 15:23:41.520   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 15:23:41.520   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 15:23:41.534   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 15:23:41.534   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 15:23:41.536   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:41.587   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-08 15:23:41.588   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 15:23:41.594   874  1315 E native  : do suspend true
,09-08 15:23:41.619   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 15:23:41.631   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-08 15:23:41.632   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 15:23:42.921   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 15:23:43.067   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.06 rxSuccessRate=16.75 delta 1000 -> 994
,09-08 15:23:43.068   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 15:23:43.068   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 15:23:43.084   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 15:23:43.155   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 15:23:43.161  1432  1432 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 15:23:43.915  1432  1432 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 15:23:43.960  1432  1432 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 15:23:43.961  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 15:23:43.964   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 15:23:43.977   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 15:23:43.977   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 15:23:43.978   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 15:23:43.996   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 15:23:44.009   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:44.012   874  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 15:23:44.024   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 15:23:44.036   874  4267 D DhcpClient: Receive thread started
,09-08 15:23:44.130   874  1315 E native  : do suspend false
,09-08 15:23:44.156   874  2081 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 15:23:44.177   874  4267 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-08 15:23:44.179   874  2081 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-08 15:23:44.182   874  2081 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 15:23:44.201   874  4267 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 15:23:44.203   874  2081 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 15:23:44.207   372   872 D CommandListener: Setting iface cfg
,09-08 15:23:44.219   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 15:23:44.220   874  2081 D DhcpClient: Scheduling renewal in 86399s
,09-08 15:23:44.221   874  1315 E native  : do suspend true
,09-08 15:23:44.260   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 15:23:44.263   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 15:23:44.265   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 15:23:44.270   874  1319 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 15:23:44.283   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 15:23:44.323   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 15:23:44.323   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 15:23:44.325   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 15:23:44.326   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 15:23:44.329   874  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 15:23:44.345   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 15:23:44.357   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-08 15:23:44.357   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-08 15:23:44.358   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 15:23:44.358   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 15:23:44.358   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-08 15:23:44.358   874  1319 D ConnectivityService:    accepting network in place of null
,09-08 15:23:44.359   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 15:23:44.387   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 15:23:44.415   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 15:23:44.419   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 15:23:44.420   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 15:23:44.421   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 15:23:44.423   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 15:23:44.437   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=401718, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:44.448  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:23:44.451  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:44.454  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:44.455  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:23:44.457  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:44.463  1698  1698 D SystemUpdateService: onCreate
,09-08 15:23:44.466  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 15:23:44.489  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 15:23:44.489  1698  4276 I SystemUpdateService: active receiver: enabled
,09-08 15:23:44.502  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 15:23:44.503  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 15:23:44.505  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 15:23:44.511  1698  4278 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 15:23:44.511  1698  4278 W BaseAppContext: Using Auth Proxy for data requests.
09-08 15:23:44.512  3971  3971 D SprintDMHelper: simOperator: 
09-08 15:23:44.512  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 15:23:44.516  1698  4278 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 15:23:44.531   874  4265 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.206,2a00:1450:4001:818::200e
,09-08 15:23:44.533  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:23:44.535  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:23:44.537  1698  2522 I iu.UploadsManager: num queued entries: 0
,09-08 15:23:44.545  1698  2522 I iu.UploadsManager: num updated entries: 0
,09-08 15:23:44.548  1698  4276 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 15:23:44.559  1698  2522 I iu.SyncManager: NEXT; no task
,09-08 15:23:44.562  1698  4276 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 15:23:44.562  1698  4276 I SystemUpdateService: now status is 0 (complete)
09-08 15:23:44.562  1698  4276 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 15:23:44.562  1698  4276 I SystemUpdateService: file has been verified
,09-08 15:23:44.566  1698  4276 I SystemUpdateService: OTA package size = 12249756
,09-08 15:23:44.578  1698  4276 I SystemUpdateService: showing system update notification
,09-08 15:23:44.609  1505  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 15:23:44.609  1505  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 15:23:44.609  1505  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 15:23:44.620  1505  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:23:44.635   874  4265 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 13:23:44 GMT], X-Android-Received-Millis=[1473341024634], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473341024576]}
,09-08 15:23:44.638   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 15:23:44.638   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 15:23:44.639   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 15:23:44.644   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 15:23:44.656  1698  1698 D SystemUpdateService: onDestroy
,09-08 15:23:44.663  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:23:44.663  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:23:44.664  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:23:44.664  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:23:44.678  3008  4286 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 15:23:44.678  3008  4286 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jcs.i(PG:143),
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at blb.a(PG:3937)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at czp.a(PG:18188)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at czp.a(PG:9087)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:23:44.678  3008  4286 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	... 12 more
09-08 15:23:44.678  3008  4286 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at fal.a(PG:38)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:23:44.678  3008  4286 E HttpOperation: 	... 14 more
,09-08 15:23:44.687  3109  4284 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
,09-08 15:23:44.686  1698  4278 E MDM     : [180] SitrepService.a: Error sending sitrep.
,09-08 15:23:44.946  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:23:44.946  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 15:23:44.947  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 15:23:44.947  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:23:44.963  3008  4295 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 15:23:44.963  3008  4295 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at blb.a(PG:3937)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at czp.a(PG:18188)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:23:44.963  3008  4295 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	... 12 more
09-08 15:23:44.963  3008  4295 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at fal.a(PG:38)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:23:44.963  3008  4295 E HttpOperation: 	... 14 more
,09-08 15:23:45.005  1505  2095 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:23:45.005  1505  2095 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 15:23:45.005  1505  2095 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:23:45.005  1505  2095 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:23:45.019  3008  4295 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 15:23:45.019  3008  4295 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at hec.a(PG:42)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at hee.a(PG:102)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at czr.a(PG:65)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at kka.a(PG:108)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at czp.a(PG:19176)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:23:45.019  3008  4295 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	... 15 more
09-08 15:23:45.019  3008  4295 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at fal.a(PG:38)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:23:45.019  3008  4295 E HttpOperation: 	... 17 more
,09-08 15:23:45.019  3008  4295 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 15:23:45.019  3008  4295 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at hec.a(PG:42)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at hee.a(PG:102)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at czr.a(PG:65)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at kka.a(PG:108)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	... 15 more
09-08 15:23:45.019  3008  4295 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at fal.a(PG:38)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 15:23:45.019  3008  4295 E ExperimentLoader: 	... 17 more
,09-08 15:23:45.153   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 310011, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:23:45.421   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:46.501  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:23:46.508  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:46.509  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:23:46.510  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7976f63 removed from the list
,09-08 15:23:46.510  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:23:46.510  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:46.511  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:46.523  3859  4296 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 15:23:46.523  3859  4296 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 15:23:49.530  3859  4297 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 15:23:49.531  3859  4296 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 15:23:49.532  3859  4297 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 15:23:49.532  3859  4296 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 15:23:49.533  3859  4297 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 15:23:49.533  3859  4296 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 15:23:49.534  3859  4297 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 15:23:49.536  3859  4296 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 15:23:49.539  3859  4297 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 15:23:49.540  3859  4299 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: IncomingSocketThread/Sender)
,09-08 15:23:49.540  3859  4296 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 15:23:49.546  3859  4300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 416, name: OutgoingSocketThread/Sender)
,09-08 15:23:49.549  3859  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: IncomingSocketThread/Receiver)
09-08 15:23:49.550  3859  4301 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 418, thread name: IncomingSocketThread/Receiver)
09-08 15:23:49.551  3859  4301 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 15:23:49.551  3859  4301 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 418, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 15:23:49.551  3859  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: OutgoingSocketThread/Receiver)
09-08 15:23:49.553  3859  4302 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: OutgoingSocketThread/Receiver)
09-08 15:23:49.553  3859  4302 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 15:23:49.554  3859  4302 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 15:23:52.365   874  1319 D ConnectivityService: handlePromptUnvalidated 102
,09-08 15:23:52.530  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 15:23:52.533  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 15:23:52.541  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@556cf45 Bundle[{}]
,09-08 15:23:52.541  3859  3905 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 15:23:52.542  3859  3905 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 15:23:52.542  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 15:23:52.543  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 15:23:52.543  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 15:23:52.544  3859  3905 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 15:23:52.548  3859  3905 I System.out: Running OutgoingSocketThread
09-08 15:23:52.551  3859  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 15:23:52.552  3859  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 15:23:55.560  3859  4305 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 15:23:55.561  3859  4305 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 15:23:55.561  3859  4304 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 15:23:55.562  3859  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 15:23:55.562  3859  4304 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 15:23:55.562  3859  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 15:23:55.563  3859  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 15:23:55.564  3859  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 15:23:55.567  3859  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Sender)
,09-08 15:23:55.569  3859  4305 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 15:23:55.572  3859  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: OutgoingSocketThread/Sender)
,09-08 15:23:55.574  3859  4304 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 15:23:55.577  3859  4309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Receiver)
,09-08 15:23:55.579  3859  4309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: IncomingSocketThread/Receiver)
,09-08 15:23:55.579  3859  4309 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 15:23:55.580  3859  4309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 15:23:55.582  3859  4310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Receiver)
,09-08 15:23:55.584  3859  4310 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: OutgoingSocketThread/Receiver)
09-08 15:23:55.585  3859  4310 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 15:23:55.585  3859  4310 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 15:23:58.563  3859  3905 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 440)
,09-08 15:23:58.565  3859  3905 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 15:23:58.566  3859  3905 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,09-08 15:23:58.571  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 15:23:58.571  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fcc760 added. We now have 3 listener(s)
,09-08 15:23:58.573  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 15:23:58.574  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 15:23:58.574  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 15:23:58.574  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:23:58.574  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca05419 added. We now have 4 listener(s)
09-08 15:23:58.574  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 15:23:58.575  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 15:23:58.583  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:58.597  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:23:58.603  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:58.604  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 15:23:58.606  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:23:58.606  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:23:58.606  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:23:58.607  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:23:58.608  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:58.609  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 15:23:58.609  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 15:23:58.609  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fcc760 removed from the list
09-08 15:23:58.610  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:23:58.610  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca05419 removed from the list
,09-08 15:23:58.611  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:58.611  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 15:23:58.611  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:23:58.612  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:58.612  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:58.616  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:23:58.617  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 15:23:58.617  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:23:58.617  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca05419 not in the list
09-08 15:23:58.617  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:58.617  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:23:58.618  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:58.620  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:23:58.620  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:23:58.620  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:23:58.620  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca05419 not in the list
09-08 15:23:58.620  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:23:58.620  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:23:58.621  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:23:58.621  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fcc760 not in the list
09-08 15:23:58.621  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 15:23:58.622  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e079ebf added. We now have 3 listener(s)
09-08 15:23:58.623  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 15:23:58.624  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 15:23:58.624  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 15:23:58.624  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:23:58.624  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f98c added. We now have 4 listener(s)
09-08 15:23:58.624  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 15:23:58.625  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 15:23:58.629  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:23:58.640  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:23:58.647  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:23:58.647  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 15:23:58.648  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 15:23:58.648  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 15:23:58.649  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 15:23:58.649  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:23:58.649  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 15:23:58.654  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 15:23:58.659  3859  3905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 15:23:58.659  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:23:58.660  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 15:23:58.674  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 15:23:58.677  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 15:23:58.677  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 15:23:58.690  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 15:23:58.690  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 15:23:58.691  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 15:23:58.693  3859  3905 D BluetoothAdapter: STATE_ON
,09-08 15:23:58.704  4209  4238 D BtGatt.GattService: registerClient() - UUID=426b783d-376a-4259-b109-0109f0ba488e
,09-08 15:23:58.706  4209  4225 D BtGatt.GattService: onClientRegistered() - UUID=426b783d-376a-4259-b109-0109f0ba488e, clientIf=5
,09-08 15:23:58.710  3859  3869 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 15:23:58.713  4209  4220 D BtGatt.GattService: start scan with filters
,09-08 15:23:58.726  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 15:23:58.726  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 15:23:58.726  4209  4228 D BtGatt.ScanManager: handling starting scan
09-08 15:23:58.727  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 15:23:58.727  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 15:23:58.732  4209  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7528389
,09-08 15:23:58.739  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:23:58.740  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 15:23:58.740  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 15:23:58.746  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 15:23:58.750  4209  4225 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 15:23:58.751  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:23:58.753  4209  4228 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 15:23:58.757  3859  3905 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 15:23:58.757  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 15:23:58.758  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 15:23:58.758  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:23:58.758  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 15:23:58.759  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 15:23:58.759  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 15:23:58.759  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 15:23:58.759  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 15:23:58.760  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 15:23:58.760  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 15:23:58.762  3859  3905 D BluetoothAdapter: STATE_ON
,09-08 15:23:58.764  4209  4238 D BtGatt.GattService: stopScan() - queue size =1
,09-08 15:23:58.766  4209  4220 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 15:23:58.767  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 15:23:58.767  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 15:23:58.767  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 15:23:58.768  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 15:23:58.768  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 15:23:58.770  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 15:23:58.771  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 15:23:58.771  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 15:23:58.771  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 15:23:58.771  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 15:23:58.771  4209  4225 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 15:23:58.772  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:23:58.773  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:23:58.773  4209  4228 D BtGatt.ScanManager: Starting BLE batch scan
09-08 15:23:58.773  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 15:23:58.773  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 15:23:58.773  4209  4228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 15:23:58.790  4209  4225 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 15:23:58.790  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:23:58.797  4209  4225 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 15:23:58.797  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:23:58.813  4209  4225 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 15:23:58.814  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 15:23:58.814  4209  4228 D BtGatt.ScanManager: stopping BLe Batch
,09-08 15:23:58.828  4209  4225 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 15:23:58.829  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:23:58.829  4209  4228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 15:23:58.852  4209  4225 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 15:23:58.853  4209  4225 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 15:23:58.854  4209  4225 D BtGatt.GattService: current time is 416135385838
,09-08 15:23:58.854  4209  4225 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -84, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:23:58.858  4209  4225 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 15:23:59.274  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 15:23:59.275  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 15:23:59.275  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 15:24:01.083   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418363, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:24:01.774  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 15:24:01.774  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:24:01.774  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 15:24:01.775  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:24:01.775  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:24:01.776  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 15:24:01.776  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 15:24:01.776  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e079ebf removed from the list
09-08 15:24:01.777  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 15:24:01.777  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f98c removed from the list
09-08 15:24:01.777  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:24:01.777  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:24:01.779  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:24:01.779  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:24:01.783  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:24:01.783  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:24:01.783  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:24:01.784  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f98c not in the list
09-08 15:24:01.784  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 15:24:01.784  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:24:01.788  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:24:01.788  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:24:01.788  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:24:01.789  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f98c not in the list
09-08 15:24:01.789  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:24:01.789  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:24:01.789  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:24:01.790  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e079ebf not in the list
09-08 15:24:01.792  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 15:24:01.793  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79f6d51 added. We now have 3 listener(s)
,09-08 15:24:01.799  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 15:24:01.799  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 15:24:01.799  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 15:24:01.800  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:24:01.800  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd669b6 added. We now have 4 listener(s)
09-08 15:24:01.800  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:24:01.802  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 15:24:01.808  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 15:24:01.818  3859  3905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 15:24:01.822  3859  3905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 15:24:01.823  3859  3905 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 15:24:01.823  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 15:24:01.825  3859  3905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 15:24:01.825  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 15:24:01.829  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:24:01.829  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 15:24:01.829  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 15:24:01.829  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 15:24:01.830  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:24:01.831  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 15:24:01.832  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 15:24:01.833  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 15:24:01.833  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 15:24:01.833  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-08 15:24:01.834  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:24:01.834  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 15:24:01.838  3859  4311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 15:24:01.840  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 15:24:01.840  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 15:24:01.844  3859  4311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 15:24:01.846  3859  3905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 15:24:01.847  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 15:24:01.858  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 15:24:01.859  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 15:24:01.859  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 15:24:01.864  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 15:24:01.865  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 15:24:01.865  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-08 15:24:01.868  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 15:24:01.868  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 15:24:01.868  3859  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 15:24:01.870  3859  3905 D BluetoothAdapter: STATE_ON
,09-08 15:24:01.876  4209  4246 D BtGatt.GattService: registerClient() - UUID=58a2ba86-c0e0-4e33-9fb3-c44f8fe7827d
,09-08 15:24:01.877  4209  4225 D BtGatt.GattService: onClientRegistered() - UUID=58a2ba86-c0e0-4e33-9fb3-c44f8fe7827d, clientIf=5
09-08 15:24:01.878  3859  3870 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 15:24:01.884  4209  4227 D BtGatt.AdvertiseManager: message : 0
,09-08 15:24:01.890  4209  4227 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 15:24:01.911  4209  4225 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 15:24:01.929  4209  4225 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 15:24:01.932  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 15:24:01.933  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 15:24:01.939  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 15:24:01.943  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 15:24:01.944  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 15:24:01.944  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 15:24:01.944  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 15:24:01.945  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 15:24:01.945  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 15:24:01.948  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 15:24:01.953  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 15:24:01.953  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 15:24:02.454  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 15:24:02.455  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 15:24:02.455  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 15:24:04.950  3859  3905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 15:24:04.950  3859  3905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 15:24:04.951  3859  3905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 15:24:04.951  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 15:24:04.952  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 15:24:04.952  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 15:24:04.954  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 15:24:04.954  3859  4311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 15:24:04.954  3859  3905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 15:24:04.954  3859  4311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 15:24:04.955  3859  4311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 15:24:04.955  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 15:24:04.955  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 15:24:04.955  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 15:24:04.955  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 15:24:04.956  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 15:24:04.956  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 15:24:04.959  3859  3905 D BluetoothAdapter: STATE_ON
09-08 15:24:04.959  3859  3905 D BluetoothLeScanner: could not find callback wrapper
,09-08 15:24:04.960  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 15:24:04.961  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 15:24:04.963  4209  4227 D BtGatt.AdvertiseManager: message : 1
09-08 15:24:04.964  4209  4227 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 15:24:04.972  4209  4225 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 15:24:04.973  4209  4225 D BtGatt.GattService: Client app is not null!
,09-08 15:24:04.974  4209  4246 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 15:24:04.976  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 15:24:04.976  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 15:24:04.976  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 15:24:04.977  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 15:24:04.977  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 15:24:04.979  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 15:24:04.979  3859  3905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 15:24:04.980  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 15:24:04.981  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:24:04.985  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 15:24:04.985  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 15:24:04.985  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 15:24:04.985  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:24:04.985  3859  3859 D AndroidRuntime: Shutting down VM
09-08 15:24:04.985  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 15:24:04.986  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 15:24:04.986  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79f6d51 removed from the list
09-08 15:24:04.986  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
--------- beginning of crash
09-08 15:24:04.986  3859  3859 E AndroidRuntime: FATAL EXCEPTION: main
09-08 15:24:04.986  3859  3859 E AndroidRuntime: Process: com.test.thalitest, PID: 3859
09-08 15:24:04.986  3859  3859 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:24:04.986  3859  3859 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 15:24:04.987  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd669b6 removed from the list
,09-08 15:24:04.987  3859  3905 D io.jxcore.node.ConnectivityMonitor: stop
09-08 15:24:04.987  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:24:04.989  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:24:04.989  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 15:24:04.990  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 15:24:04.991  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:24:04.991  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:24:04.991  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd669b6 not in the list
09-08 15:24:04.991  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:24:04.991  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:24:04.992   874  2029 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-08 15:24:04.995  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 15:24:04.995  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 15:24:04.995  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 15:24:04.995  3859  3905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd669b6 not in the list
09-08 15:24:04.995  3859  3905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 15:24:04.995  3859  3905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 15:24:04.995  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 15:24:04.995  3859  3905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79f6d51 not in the list
09-08 15:24:04.996  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 15:24:04.996  3859  3905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef2f753 added. We now have 3 listener(s)
,09-08 15:24:04.998  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 15:24:04.998  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 15:24:04.998  3859  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 15:24:04.999  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 15:24:04.999  3859  3905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@200c890 added. We now have 4 listener(s)
09-08 15:24:04.999   874  2029 I ActivityManager: Killing 3693:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-08 15:24:05.000  3859  3905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 15:24:05.008  3859  3905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 15:24:05.052  3859  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 15:24:05.052   874   887 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{82dc8 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{625cfba 3859 com.test.thalitest/10000/u0 remote:87c58e5}: process crashing
,09-08 15:24:05.052   874   887 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{21e9e61 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{625cfba 3859 com.test.thalitest/10000/u0 remote:87c58e5}: process crashing
,09-08 15:24:05.058  3859  3859 I Process : Sending signal. PID: 3859 SIG: 9
,09-08 15:24:05.140   874   884 D GraphicsStats: Buffer count: 2
,09-08 15:24:05.141   874  1397 I WindowState: WIN DEATH: Window{c2762e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 15:24:05.141   874  1318 D WifiService: Client connection lost with reason: 4
,09-08 15:24:05.166   874   884 I ActivityManager: Process com.test.thalitest (pid 3859) has died
,09-08 15:24:05.212   874  2041 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3859 uid 10000
,09-08 15:24:05.213  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-08 15:24:17.514  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:24:17.518  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:24:17.568  1505  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:24:17.568  1505  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:24:17.568  1505  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:24:17.569  1505  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:24:17.605  3008  4316 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 15:24:17.605  3008  4316 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at blb.a(PG:3937)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at czp.a(PG:18188)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:24:17.605  3008  4316 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	... 12 more
09-08 15:24:17.605  3008  4316 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at fal.a(PG:38)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:24:17.605  3008  4316 E HttpOperation: 	... 14 more
,09-08 15:24:17.670  1505  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:24:17.670  1505  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:24:17.670  1505  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:24:17.670  1505  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:24:17.707  3008  4316 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 15:24:17.707  3008  4316 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at hec.a(PG:42)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at hee.a(PG:102)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at czr.a(PG:65)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at kka.a(PG:108)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at czp.a(PG:19176)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:24:17.707  3008  4316 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	... 15 more
09-08 15:24:17.707  3008  4316 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at fal.a(PG:38)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:24:17.707  3008  4316 E HttpOperation: 	... 17 more
,09-08 15:24:17.707  3008  4316 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 15:24:17.707  3008  4316 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at hec.a(PG:42)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at hee.a(PG:102)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at czr.a(PG:65)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at kka.a(PG:108)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	... 15 more
09-08 15:24:17.707  3008  4316 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at fal.a(PG:38)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 15:24:17.707  3008  4316 E ExperimentLoader: 	... 17 more
,09-08 15:24:17.924   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 434470, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:25:05.255  1902  1948 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 15:25:05.255  1902  1948 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 15:25:05.292  1505  1505 I ConfigService: onCreate
,09-08 15:25:09.454  3033  4321 V KeepSync: Connecting to GoogleApiClient
09-08 15:25:09.455   874  2274 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 15:25:09.512  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:25:09.516  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:25:09.548  1505  3633 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 15:25:09.548  1505  3633 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 15:25:09.548  1505  3633 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:25:09.548  1505  3633 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:25:09.571  1698  4322 V BaseAuthAsyncOperation: access token request failed
,09-08 15:25:09.572  3033  4321 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 15:25:09.632  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 15:25:09.632  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 15:25:09.632  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:25:09.632  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:25:09.654  3033  4321 E KeepSync: IOException
09-08 15:25:09.654  3033  4321 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 15:25:09.654  3033  4321 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 15:25:09.654  3033  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 15:25:09.654  3033  4321 E KeepSync: 	... 10 more
,09-08 15:25:09.654  3033  4321 W KeepSync: Sync result 2
,09-08 15:25:09.661   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 486630, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:25:10.363  1505  1505 I ConfigService: onDestroy
,09-08 15:25:40.190  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:25:40.193  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:25:40.220  1505  2095 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:25:40.220  1505  2095 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:25:40.220  1505  2095 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 15:25:40.220  1505  2095 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:25:40.245  3008  4325 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 15:25:40.245  3008  4325 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at blb.a(PG:3937)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at czp.a(PG:18188)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:25:40.245  3008  4325 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	... 12 more
09-08 15:25:40.245  3008  4325 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at fal.a(PG:38)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:25:40.245  3008  4325 E HttpOperation: 	... 14 more
,09-08 15:25:40.293  1505  3088 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 15:25:40.293  1505  3088 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 15:25:40.293  1505  3088 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 15:25:40.293  1505  3088 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:25:40.319  3008  4325 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 15:25:40.319  3008  4325 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jdm.a(PG:82)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jcs.o(PG:406)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jcn.a(PG:1379)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jcs.i(PG:143)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at hec.a(PG:42)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at hee.a(PG:102)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at czr.a(PG:65)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at kka.a(PG:108)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	,at czp.a(PG:19176)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at czp.a(PG:9081)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at czq.run(PG:1686)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:25:40.319  3008  4325 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jdj.a(PG:4091)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jdj.a(PG:1125)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jdm.a(PG:77)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	... 15 more
09-08 15:25:40.319  3008  4325 E HttpOperation: Caused by: faj: BadAuthentication
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at fal.a(PG:38)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	at jdj.a(PG:4089)
09-08 15:25:40.319  3008  4325 E HttpOperation: 	... 17 more
09-08 15:25:40.319  3008  4325 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 15:25:40.319  3008  4325 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at hec.a(PG:42)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at hee.a(PG:102)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at czr.a(PG:65)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at kka.a(PG:108)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	... 15 more
09-08 15:25:40.319  3008  4325 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at fal.a(PG:38)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 15:25:40.319  3008  4325 E ExperimentLoader: 	... 17 more
,09-08 15:25:40.491   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 499278, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:25:40.542  3033  4327 V KeepSync: Connecting to GoogleApiClient
,09-08 15:25:40.542   874  1518 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 15:25:40.596  1505  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
09-08 15:25:40.596  1505  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 15:25:40.596  1505  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:25:40.596  1505  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:25:40.614  1698  4328 V BaseAuthAsyncOperation: access token request failed
,09-08 15:25:40.615  3033  4327 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 15:25:40.659  1505  3633 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 15:25:40.659  1505  3633 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 15:25:40.659  1505  3633 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:25:40.659  1505  3633 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:25:40.673  3033  4327 E KeepSync: IOException
09-08 15:25:40.673  3033  4327 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 15:25:40.673  3033  4327 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 15:25:40.673  3033  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 15:25:40.673  3033  4327 E KeepSync: 	... 10 more
,09-08 15:25:40.674  3033  4327 W KeepSync: Sync result 2
,09-08 15:25:40.689   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 517634, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:25:44.716  1505  2207 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 15:26:10.835  3751  4330 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 15:26:10.872  3751  4331 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 15:26:10.884  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 15:26:10.886  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:10.924  1505  1964 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 15:26:10.924  1505  1964 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 15:26:10.924  1505  1964 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:26:10.924  1505  1964 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:26:10.953  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:10.957  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:10.991  1505  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 15:26:10.991  1505  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 15:26:10.991  1505  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:26:10.991  1505  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:26:11.004  3751  4331 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 15:26:11.004  3751  4330 E BooksSync: Soft error
09-08 15:26:11.004  3751  4330 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 15:26:11.004  3751  4330 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 15:26:11.005  3751  4330 E BooksSync: Sync error
09-08 15:26:11.005  3751  4330 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 15:26:11.005  3751  4330 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 15:26:11.005  3751  4330 I BooksSync: Finished books sync
,09-08 15:26:11.012   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 523389, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:26:42.190  3751  4334 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 15:26:42.220  3751  4335 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 15:26:42.235  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:42.242  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:42.265  3033  4333 V KeepSync: Connecting to GoogleApiClient
,09-08 15:26:42.266   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 15:26:42.279  1505  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 15:26:42.279  1505  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 15:26:42.279  1505  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 15:26:42.279  1505  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:26:42.366  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:42.375  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 15:26:42.445  1505  3086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 15:26:42.445  1505  3086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 15:26:42.445  1505  3086 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:26:42.446  1505  3086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:26:42.453  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 15:26:42.454  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 15:26:42.454  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:26:42.454  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:26:42.509  3751  4335 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 15:26:42.510  3751  4334 E BooksSync: Soft error
09-08 15:26:42.510  3751  4334 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 15:26:42.510  3751  4334 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 15:26:42.510  3751  4334 E BooksSync: Sync error
09-08 15:26:42.510  3751  4334 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 15:26:42.510  3751  4334 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 15:26:42.510  3751  4334 I BooksSync: Finished books sync
,09-08 15:26:42.515  1698  4336 V BaseAuthAsyncOperation: access token request failed
,09-08 15:26:42.517  3033  4333 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 15:26:42.547   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 579359, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:26:42.608  1505  1964 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 15:26:42.608  1505  1964 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 15:26:42.608  1505  1964 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 15:26:42.608  1505  1964 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 15:26:42.623  3033  4333 E KeepSync: IOException
09-08 15:26:42.623  3033  4333 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 15:26:42.623  3033  4333 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 15:26:42.623  3033  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 15:26:42.623  3033  4333 E KeepSync: 	... 10 more
,09-08 15:26:42.623  3033  4333 W KeepSync: Sync result 2
,09-08 15:26:42.648   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 579353, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 15:26:50.289   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:27:06.450   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=603731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:27:14.143   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=611424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:27:30.292   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=627573, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:27:49.904   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:28:06.023   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=663303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:28:42.545  1505  2207 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 15:28:49.649   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=706930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:29:05.811   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=723092, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:29:20.103   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=737384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:29:36.266   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=753546, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:29:50.449   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=767730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 15:30:06.611   874  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=783892, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:37:20.751   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-08 15:45:44.209  4391  4391 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 15:45:44.214  4391  4391 D AndroidRuntime: CheckJNI is OFF
09-08 15:45:44.249  4391  4391 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 15:45:44.290  4391  4391 I Radio-JNI: register_android_hardware_Radio DONE
09-08 15:45:44.310  4391  4391 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 15:45:44.320   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-08 15:45:44.427   874   897 W PackageSettings: Skipping PackageSetting{ad6ec12 com.example.hello/10273} due to missing metadata
09-08 15:45:44.454   874   897 I art     : Starting a blocking GC Explicit
09-08 15:45:44.506   874   897 I art     : Explicit concurrent mark sweep GC freed 69855(4MB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 29MB/43MB, paused 677us total 51.043ms
09-08 15:45:44.578   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 15:45:44.584  4391  4391 I art     : System.exit called, status: 0
09-08 15:45:44.584  4391  4391 I AndroidRuntime: VM exiting with result code 0.
09-08 15:45:44.585   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-08 15:45:44.614  4209  4209 D BluetoothMapAppObserver: onReceive
09-08 15:45:44.614  4209  4209 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 15:45:44.619  1902  1902 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 15:45:44.621   874  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 15:45:44.621  1862  2200 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 15:45:44.623  3641  3641 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-08 15:45:44.639  1902  4405 I Keyboard.Facilitator.DecoderInitializer: run()
09-08 15:45:44.644   874  2272 I ActivityManager: Start proc 4407:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 15:45:44.653  1902  4405 I Decoder : createOrResetDecoder
09-08 15:45:44.675  1993  1993 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-08 15:45:44.692  1505  1505 I ConfigService: onCreate
09-08 15:45:44.696  4407  4407 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-08 15:45:44.717   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 15:45:44.735  1902  4405 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-08 15:45:44.760  4407  4407 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 15:45:44.762  2007  2090 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-08 15:45:44.765  1902  4405 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-08 15:45:44.767   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 15:45:44.768   874   886 E PackageManager: Failed to write settings, restoring backup
09-08 15:45:44.768   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 15:45:44.768   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 15:45:44.768   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 15:45:44.768   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 15:45:44.768   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 15:45:44.768   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.768   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.768   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.767  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 15:45:44.768  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-08 15:45:44.771   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-08 15:45:44.771   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 15:45:44.771   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 15:45:44.771   874   887 E DropBoxManagerService: 	... 13 more
09-08 15:45:44.772  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 15:45:44.772  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 15:45:44.774  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 15:45:44.774  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 15:45:44.776  1902  4405 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 15:45:44.776  1902  4405 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 15:45:44.776  1902  4405 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 15:45:44.777  1902  4405 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 15:45:44.777  1902  4405 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 15:45:44.777  1902  4405 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-08 15:45:44.777   874  2273 I ActivityManager: Start proc 4426:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-08 15:45:44.777  2007  2090 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 15:45:44.777  2007  2090 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2007
09-08 15:45:44.777  2007  2090 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.777  2007  2090 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.779   874  2036 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 15:45:44.780   874  4432 E DropBoxManagerService: Can't write: system_app_crash
09-08 15:45:44.780   874  4432 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 15:45:44.780   874  4432 E DropBoxManagerService: 	... 5 more
09-08 15:45:44.783  2007  2090 I Process : Sending signal. PID: 2007 SIG: 9
09-08 15:45:44.799  4407  4440 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 15:45:44.804   874  1704 I ActivityManager: Start proc 4441:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-08 15:45:44.847  4441  4441 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-08 15:45:44.870  1505  1505 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 15:45:44.873  1505  1505 D AndroidRuntime: Shutting down VM
09-08 15:45:44.874  1505  1505 E AndroidRuntime: FATAL EXCEPTION: main
09-08 15:45:44.874  1505  1505 E AndroidRuntime: Process: com.google.process.gapps, PID: 1505
09-08 15:45:44.874  1505  1505 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 15:45:44.874  1505  1505 E AndroidRuntime: 	... 8 more
09-08 15:45:44.879   874  4457 E DropBoxManagerService: Can't write: system_app_crash
09-08 15:45:44.879   874  4457 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 15:45:44.879   874  4457 E DropBoxManagerService: 	... 5 more
09-08 15:45:44.881  1505  1505 I Process : Sending signal. PID: 1505 SIG: 9
09-08 15:45:44.883   874  1304 W InputDispatcher: channel 'd083067 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-08 15:45:44.883   874  1304 E InputDispatcher: channel 'd083067 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-08 15:45:44.884   874   885 I WindowState: WIN DEATH: Window{d083067 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 15:45:44.884   874  1397 D GraphicsStats: Buffer count: 1
09-08 15:45:44.884   874   885 W InputDispatcher: Attempted to unregister already unregistered input channel 'd083067 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-08 15:45:44.900   874  2000 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2007) has died
09-08 15:45:44.900   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 15:45:44.901   874  2000 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 15:45:44.918   874   887 I ActivityManager: Start proc 4459:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.939  4407  4423 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.939  4407  4423 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.950  1698  4469 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
09-08 15:45:44.950  1698  4469 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@737ef28
09-08 15:45:44.951   874  2038 I ActivityManager: Process com.google.process.gapps (pid 1505) early provider death
09-08 15:45:44.969  4407  4423 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:45:44.970  4459  4459 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 15:45:44.970  4459  4459 D AndroidRuntime: Shutting down VM
09-08 15:45:44.974   874  1318 D WifiService: Client connection lost with reason: 4
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.980  4407  4440 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 15:45:44.981  4407  4440 E AndroidRuntime: Process: android.process.acore, PID: 4407
09-08 15:45:44.981  4407  4440 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.981  4407  4440 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 15:45:44.982   874  2038 I ActivityManager: Process com.google.process.gapps (pid 1505) has died
09-08 15:45:44.982   874  2038 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-08 15:45:44.982   874  2038 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-08 15:45:44.983   874  2038 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-08 15:45:44.985  4407  4423 I Process : Sending signal. PID: 4407 SIG: 9
09-08 15:45:44.987   874  2029 W ActivityManager: Spurious death for ProcessRecord{e8b6571 0:com.google.process.gapps/u0a11}, curProc for 1505: null
09-08 15:45:44.991  4459  4459 E AndroidRuntime: FATAL EXCEPTION: main
09-08 15:45:44.991  4459  4459 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4459
09-08 15:45:44.991  4459  4459 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 15:45:44.991  4459  4459 E AndroidRuntime: 	... 10 more
09-08 15:45:44.991  1698  1698 W RocketImpressions: ClearcutLogger connection suspended: 1
09-08 15:45:44.994   874  4473 E DropBoxManagerService: Can't write: system_app_crash
09-08 15:45:44.994   874  4473 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 15:45:44.994   874  4473 E DropBoxManagerService: 	... 5 more
09-08 15:45:45.003   874  1928 I ActivityManager: Start proc 4474:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
09-08 15:45:45.007   874  2272 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 15:45:45.007  4459  4459 I Process : Sending signal. PID: 4459 SIG: 9
09-08 15:45:45.009   874  4483 E DropBoxManagerService: Can't write: system_app_crash
09-08 15:45:45.009   874  4483 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 15:45:45.009   874  4483 E DropBoxManagerService: 	... 5 more
09-08 15:45:45.025   874  2038 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4459) has died
09-08 15:45:45.027   874  2038 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 15:45:45.041   874   887 I ActivityManager: Start proc 4489:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 15:45:45.048  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 15:45:45.049  1698  1698 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-08 15:45:45.051  4474  4474 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-08 15:45:45.057  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 15:45:45.057  1698  1698 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-08 15:45:45.071   278   278 E lowmemorykiller: Error writing /proc/4407/oom_score_adj; errno=22
09-08 15:45:45.071   278   278 E lowmemorykiller: Error writing /proc/4407/oom_score_adj; errno=22
09-08 15:45:45.072  4474  4474 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-08 15:45:45.076  1698  4502 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 15:45:45.077  2066  4501 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:45:45.075  4474  4474 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 15:45:45.079  4474  4474 D AndroidRuntime: Shutting down VM
09-08 15:45:45.080  4474  4474 E AndroidRuntime: FATAL EXCEPTION: main
09-08 15:45:45.080  4474  4474 E AndroidRuntime: Process: com.google.process.gapps, PID: 4474
09-08 15:45:45.080  4474  4474 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 15:45:45.080  4474  4474 E AndroidRuntime: 	... 10 more

```
