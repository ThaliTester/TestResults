#### Test 82912030c90465a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 17:55:31.671  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:55:31.676  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 17:55:31.713  1522  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 17:55:31.713  1522  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 17:55:31.714  1522  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:55:31.714  1522  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 17:55:31.733  3547  3867 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 17:55:31.733  3547  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jdm.a(PG:82)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jcs.o(PG:406)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jcn.a(PG:1379)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jcs.i(PG:143)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at blb.a(PG:3937)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at czp.a(PG:18188)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at czp.a(PG:9081)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at czq.run(PG:1686)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:55:31.733  3547  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jdj.a(PG:4091)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jdj.a(PG:1125)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jdm.a(PG:77)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	... 12 more
09-08 17:55:31.733  3547  3867 E HttpOperation: Caused by: faj: BadAuthentication
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at fal.a(PG:38)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	at jdj.a(PG:4089)
09-08 17:55:31.733  3547  3867 E HttpOperation: 	... 14 more
09-08 17:55:31.787  1522  2317 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 17:55:31.787  1522  2317 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 17:55:31.787  1522  2317 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:55:31.787  1522  2317 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 17:55:31.812  3547  3867 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 17:55:31.812  3547  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jdm.a(PG:82)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jcs.o(PG:406)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jcn.a(PG:1379)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jcs.i(PG:143)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at hec.a(PG:42)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at hee.a(PG:102)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at czr.a(PG:65)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at kka.a(PG:108)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at czp.a(PG:19176)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at czp.a(PG:9081)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at czq.run(PG:1686)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:55:31.812  3547  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jdj.a(PG:4091)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jdj.a(PG:1125)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jdm.a(PG:77)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	... 15 more
09-08 17:55:31.812  3547  3867 E HttpOperation: Caused by: faj: BadAuthentication
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at fal.a(PG:38)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	at jdj.a(PG:4089)
09-08 17:55:31.812  3547  3867 E HttpOperation: 	... 17 more
09-08 17:55:31.813  3547  3867 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 17:55:31.813  3547  3867 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at hec.a(PG:42)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at hee.a(PG:102)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at czr.a(PG:65)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at kka.a(PG:108)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	... 15 more
09-08 17:55:31.813  3547  3867 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at fal.a(PG:38)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 17:55:31.813  3547  3867 E ExperimentLoader: 	... 17 more
09-08 17:55:31.939   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 289041, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
09-08 17:55:32.339  3868  3868 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 17:55:32.344  3868  3868 D AndroidRuntime: CheckJNI is OFF
09-08 17:55:32.388  3868  3868 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 17:55:32.439  3868  3868 I Radio-JNI: register_android_hardware_Radio DONE
09-08 17:55:32.460  3868  3868 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 17:55:32.468   873  1917 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 17:55:32.533   873  1917 I ActivityManager: Start proc 3878:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 17:55:32.539  3868  3868 D AndroidRuntime: Shutting down VM
09-08 17:55:32.658  3878  3878 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 17:55:32.684  3878  3878 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 17:55:32.691  3878  3878 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 318-320)
09-08 17:55:32.692  3878  3878 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 17:55:32.708  3878  3878 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ec14f6b}
09-08 17:55:32.709  3878  3878 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 17:55:32.709  3878  3878 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 17:55:32.715  3878  3878 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 17:55:32.716  3878  3878 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 17:55:32.737  3878  3878 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 17:55:32.748  3878  3878 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 17:55:32.748  3878  3878 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 17:55:32.748  3878  3878 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 17:55:32.748  3878  3878 I Adreno  : Build Date                       : 10/20/15
09-08 17:55:32.748  3878  3878 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 17:55:32.748  3878  3878 I Adreno  : Local Branch                     : M14
09-08 17:55:32.748  3878  3878 I Adreno  : Remote Branch                    : 
09-08 17:55:32.748  3878  3878 I Adreno  : Remote Branch                    : 
09-08 17:55:32.748  3878  3878 I Adreno  : Reconstruct Branch               : 
,09-08 17:55:32.827   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f2f1fa:true
,09-08 17:55:32.875  3878  3878 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 17:55:32.893  3878  3878 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 17:55:32.953  3878  3915 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 17:55:32.966  3878  3902 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 17:55:33.008  3878  3915 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 17:55:33.057   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +451ms (total +564ms)
,09-08 17:55:33.060  1870  1870 I Keyboard.Facilitator: onFinishInput()
,09-08 17:55:33.145  3878  3878 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3878
,09-08 17:55:33.333  3878  3878 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 17:55:33.483  3878  3917 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681917648
,09-08 17:55:33.493  3878  3917 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 17:55:33.493  3878  3917 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 17:55:33.493  3878  3917 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 17:55:33.493  3878  3917 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 17:55:33.493  3878  3917 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 17:55:33.493  3878  3917 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@335f71e added. We now have 1 listener(s)
,09-08 17:55:33.499  3878  3917 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 17:55:33.505  3878  3917 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:55:33.512  3878  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 17:55:33.513  3878  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 17:55:33.528  3878  3917 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74be815 added. We now have 1 listener(s)
09-08 17:55:33.528  3878  3917 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:55:33.532   873  1308 D WifiService: New client listening to asynchronous messages
,09-08 17:55:33.533  3878  3917 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:55:33.534  3878  3917 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 17:55:33.535  3878  3917 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 17:55:33.536  3878  3917 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 17:55:33.536  3878  3917 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 17:55:33.546  3878  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:55:33.546  3878  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 17:55:33.557  3878  3917 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:33.558  3878  3917 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:55:33.558  3878  3917 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 17:55:33.558  3878  3917 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:55:33.559  3878  3917 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 17:55:33.565  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:33.571  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:33.591  3878  3878 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 17:55:34.441  3878  3924 W jxcore-log: Initializing JXcore engine
09-08 17:55:34.441  3878  3924 W jxcore-log: JXcore engine is ready
,09-08 17:55:34.476  3924  3924 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-08 17:55:34.476  3924  3924 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10678]" dev="sockfs" ino=10678 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-08 17:55:34.476  3924  3924 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 17:55:34.476  3924  3924 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[29910]" dev="sockfs" ino=29910 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 17:55:34.508  3878  3924 W jxcore-log: Starting JXcore engine
,09-08 17:55:34.602  3878  3924 W jxcore-log: Platform android
09-08 17:55:34.602  3878  3924 W jxcore-log: 
,09-08 17:55:34.602  3878  3924 W jxcore-log: Process ARCH arm
09-08 17:55:34.602  3878  3924 W jxcore-log: 
,09-08 17:55:34.794  3878  3924 I jxcore-log: JXcore Cordova bridge is ready!
09-08 17:55:34.794  3878  3924 I jxcore-log: 
09-08 17:55:34.795  3878  3924 W jxcore-log: JXcore engine is started
,09-08 17:55:34.802  3878  3917 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 17:55:34.808  3878  3878 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 17:55:48.265  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 17:55:48.265  3878  3924 I jxcore-log: 
,09-08 17:55:48.269  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 17:55:48.269  3878  3924 I jxcore-log: 
,09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:48.281  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:55:48.286  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:55:48.292  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 17:55:48.292  3878  3924 I jxcore-log: 
,09-08 17:55:48.299  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 17:55:48.299  3878  3924 I jxcore-log: 
,09-08 17:55:48.662  3878  3924 I jxcore-log: Running unit tests
09-08 17:55:48.662  3878  3924 I jxcore-log: 
,09-08 17:55:48.662  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:55:48.662  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aacb9e added. We now have 2 listener(s)
,09-08 17:55:48.664  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:55:48.664  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 17:55:48.664  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:55:48.664  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:55:48.664  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f7067f added. We now have 2 listener(s)
,09-08 17:55:48.664  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:55:48.665  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:55:48.667  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:48.684  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:55:48.690  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:55:48.691  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:55:48.692  3878  3924 D executeNativeTests: Running unit tests
,09-08 17:55:48.696  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-08 17:55:48.702  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:48.788  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 17:55:48.788  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 added. We now have 3 listener(s)
,09-08 17:55:48.789  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:55:48.789  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 17:55:48.789  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:55:48.789  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:55:48.789  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a added. We now have 3 listener(s)
,09-08 17:55:48.789  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:55:48.790  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:55:48.798  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:48.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:55:48.825  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:55:48.826  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:55:48.828  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 17:55:48.830  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 17:55:48.830  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 17:55:48.830  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 17:55:48.831  3878  3924 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 17:55:48.832  3878  3924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 17:55:48.832  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 17:55:48.832  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 17:55:48.832  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 17:55:48.832  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 17:55:48.833  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:55:48.833  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:55:48.833  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:55:48.833  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:55:48.834  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:55:48.834  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.834  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:55:48.834  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:55:48.834  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 removed from the list
09-08 17:55:48.834  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:55:48.834  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a removed from the list
09-08 17:55:48.842  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:55:48.842  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:55:48.842  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:48.843  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.843  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:48.848  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:55:48.849  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:55:48.849  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:48.849  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:55:48.854  3878  3924 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 17:55:48.856  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:55:48.856  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:55:48.856  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:55:48.857  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:55:48.857  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:55:48.857  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:48.858  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:55:48.858  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:48.858  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:55:48.858  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:55:48.859  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.859  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:55:48.859  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.859  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:55:48.862  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:55:48.862  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:55:48.862  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:48.862  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 17:55:48.868  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 17:55:48.869  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 17:55:48.870  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 17:55:48.870  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 17:55:48.870  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 17:55:48.870  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 17:55:48.870  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-08 17:55:48.870  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:55:48.870  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:55:48.870  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:55:48.870  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:55:48.870  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.870  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:48.870  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:55:48.870  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:48.870  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:55:48.871  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:55:48.871  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.871  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:48.871  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:48.871  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:55:48.873  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:55:48.873  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:55:48.873  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:48.873  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:55:48.874  3878  3924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 17:55:48.875  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:48.883  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:55:48.888  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:55:48.888  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:55:48.889  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:55:48.889  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 17:55:48.889  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:55:48.889  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:55:48.889  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 17:55:48.891  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:48.894  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 17:55:48.894  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:55:48.895  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:48.903  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:55:48.906  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 17:55:48.907  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:55:48.911  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 17:55:48.917  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 17:55:48.918  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 17:55:48.918  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 17:55:48.921  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 17:55:48.923  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:55:48.929  2674  2829 D BtGatt.GattService: registerClient() - UUID=4fa8d477-79fb-45dd-b5cf-3d441e827b8a
,09-08 17:55:48.931  2674  2694 D BtGatt.GattService: onClientRegistered() - UUID=4fa8d477-79fb-45dd-b5cf-3d441e827b8a, clientIf=5
,09-08 17:55:48.932  3878  3889 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 17:55:48.933  2674  2684 D BtGatt.GattService: start scan with filters
,09-08 17:55:48.938  2674  2704 D BtGatt.ScanManager: handling starting scan
09-08 17:55:48.938  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 17:55:48.940  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:55:48.940  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 17:55:48.941  2674  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:55:48.940  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:55:48.945  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:55:48.946  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 17:55:48.946  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:55:48.948  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 17:55:48.952  3878  3924 I io.jxcore.node.ConnectionHelper: start: OK
09-08 17:55:48.955  2674  2694 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 17:55:48.955  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:48.956  2674  2704 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 17:55:48.969  2674  2694 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 17:55:48.969  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:48.970  2674  2704 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:55:48.970  2674  2704 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 17:55:48.991  2674  2694 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 17:55:48.991  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:49.004  2674  2694 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:55:49.004  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:49.447  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 17:55:49.447  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 17:55:49.448  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:55:50.509  2674  2674 D BtGatt.ScanManager: awakened up at time 308138,
09-08 17:55:50.511  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:55:50.562  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-08 17:55:50.563  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:50.564  2674  2694 D BtGatt.GattService: current time is 308193118353
,09-08 17:55:50.565  2674  2694 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -96, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -100, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -80, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 17:55:50.570  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 17:55:50.573  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-08 17:55:50.574  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-08 17:55:50.575  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 17:55:50.576  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-08 17:55:50.577  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 17:55:52.065  2674  2674 D BtGatt.ScanManager: awakened up at time 309694
,09-08 17:55:52.068  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:55:52.078  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:55:52.078  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:53.580  2674  2674 D BtGatt.ScanManager: awakened up at time 311209
,09-08 17:55:53.582  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:55:53.629  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 17:55:53.629  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:53.630  2674  2694 D BtGatt.GattService: current time is 311259437368
,09-08 17:55:53.632  2674  2694 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -86, 10, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -94, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -88, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 17:55:53.632  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 17:55:53.633  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 17:55:53.634  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:55:53.635  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-08 17:55:53.636  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:55:53.636  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 17:55:53.637  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 17:55:53.962  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:55:53.962  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:55:53.963  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 17:55:53.963  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:53.963  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 17:55:53.964  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:55:53.964  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:55:53.964  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:55:53.965  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:55:53.966  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:55:53.967  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 17:55:53.969  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:55:53.971  2674  2684 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:55:53.974  2674  2685 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:55:53.975  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 17:55:53.977  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 17:55:53.978  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 17:55:53.978  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 17:55:53.979  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 17:55:53.982  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:55:53.983  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:55:53.983  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 17:55:53.984  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 17:55:53.986  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:55:53.990  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:55:53.991  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:55:53.991  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:55:53.992  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:55:53.992  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:55:53.992  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:55:53.993  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:55:53.993  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:55:53.993  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:55:53.994  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:55:53.994  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:53.996  2674  2694 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 17:55:53.996  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:53.997  2674  2704 D BtGatt.ScanManager: stopping BLe Batch
,09-08 17:55:54.013  2674  2694 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:55:54.013  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:54.014  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:55:54.042  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 17:55:54.042  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:54.043  2674  2694 D BtGatt.GattService: current time is 311672061734
,09-08 17:55:54.043  2674  2694 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -85, 7, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -94, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:55:54.044  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 17:55:54.044  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 17:55:54.493  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:55:58.996  3878  3924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 17:55:59.002  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:59.016  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:55:59.023  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:55:59.023  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:55:59.026  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:55:59.026  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 17:55:59.027  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:55:59.027  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:55:59.027  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 17:55:59.032  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:59.040  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 17:55:59.040  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 17:55:59.040  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:59.054  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:55:59.056  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 17:55:59.057  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:55:59.069  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 17:55:59.070  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:55:59.070  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 17:55:59.072  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:55:59.079  2674  2684 D BtGatt.GattService: registerClient() - UUID=6adbe1d5-5702-4422-ad6e-9a6378e7be42
,09-08 17:55:59.081  2674  2694 D BtGatt.GattService: onClientRegistered() - UUID=6adbe1d5-5702-4422-ad6e-9a6378e7be42, clientIf=5
09-08 17:55:59.082  3878  3889 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 17:55:59.083  2674  2685 D BtGatt.GattService: start scan with filters
,09-08 17:55:59.092  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 17:55:59.092  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:55:59.092  2674  2704 D BtGatt.ScanManager: handling starting scan
09-08 17:55:59.093  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 17:55:59.093  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:55:59.102  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:55:59.103  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:55:59.104  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:55:59.110  2674  2694 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 17:55:59.111  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:59.112  2674  2704 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-08 17:55:59.113  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:55:59.124  3878  3924 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 17:55:59.133  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:55:59.133  3878  3924 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 17:55:59.134  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:55:59.135  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:55:59.135  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:59.135  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 17:55:59.136  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:55:59.136  2674  2694 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 17:55:59.136  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:55:59.136  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:59.136  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:55:59.136  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:55:59.137  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:55:59.137  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 17:55:59.137  2674  2704 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 17:55:59.137  2674  2704 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 17:55:59.141  3878  3924 D BluetoothAdapter: STATE_ON
09-08 17:55:59.143  2674  2685 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:55:59.147  2674  2829 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:55:59.148  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 17:55:59.149  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 17:55:59.151  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:55:59.152  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:55:59.152  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 17:55:59.155  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:55:59.155  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:55:59.156  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:55:59.156  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 17:55:59.157  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:55:59.159  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:55:59.160  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:55:59.160  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:55:59.163  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:55:59.163  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:59.163  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:55:59.164  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:55:59.164  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:59.165  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:55:59.165  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:55:59.165  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:59.166  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:55:59.166  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:55:59.169  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:55:59.169  2674  2694 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 17:55:59.170  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:59.169  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:55:59.171  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:55:59.171  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:55:59.173  3878  3924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 17:55:59.177  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:55:59.182  2674  2694 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:55:59.182  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:55:59.186  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:55:59.189  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:55:59.189  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:55:59.190  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:55:59.190  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 17:55:59.190  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 17:55:59.190  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:55:59.190  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 17:55:59.192  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:59.196  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 17:55:59.196  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 17:55:59.196  2674  2694 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 17:55:59.196  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:59.196  2674  2704 D BtGatt.ScanManager: stopping BLe Batch
09-08 17:55:59.197  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:55:59.202  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:55:59.203  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 17:55:59.203  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 17:55:59.203  2674  2694 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 17:55:59.204  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:59.204  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:55:59.207  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 17:55:59.208  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:55:59.208  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 17:55:59.209  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:55:59.211  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:55:59.211  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:59.218  2674  2829 D BtGatt.GattService: registerClient() - UUID=dafa3f19-9742-4f0b-8a15-30499352de7e
,09-08 17:55:59.218  2674  2694 D BtGatt.GattService: onClientRegistered() - UUID=dafa3f19-9742-4f0b-8a15-30499352de7e, clientIf=5
09-08 17:55:59.218  3878  3888 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 17:55:59.219  2674  2684 D BtGatt.GattService: start scan with filters
,09-08 17:55:59.223  2674  2704 D BtGatt.ScanManager: handling starting scan
,09-08 17:55:59.223  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 17:55:59.223  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:55:59.223  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 17:55:59.223  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:55:59.228  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:55:59.229  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:55:59.229  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:55:59.231  2674  2694 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 17:55:59.231  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:59.231  2674  2704 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-08 17:55:59.232  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:55:59.236  3878  3924 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 17:55:59.238  2674  2694 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 17:55:59.238  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:55:59.238  2674  2704 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:55:59.238  2674  2704 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 17:55:59.250  2674  2694 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 17:55:59.251  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:59.257  2674  2694 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:55:59.257  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:55:59.730  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 17:55:59.730  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:55:59.731  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:56:00.765  2674  2674 D BtGatt.ScanManager: awakened up at time 318394
09-08 17:56:00.770  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:56:00.813  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-08 17:56:00.813  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:56:00.813  2674  2694 D BtGatt.GattService: current time is 318442839229
,09-08 17:56:00.814  2674  2694 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -97, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -96, 11, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 17:56:00.815  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:56:00.816  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 17:56:00.817  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 17:56:00.817  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-08 17:56:00.818  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-08 17:56:00.819  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 17:56:00.820  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-08 17:56:02.028  2674  2674 D BtGatt.ScanManager: awakened up at time 319657
,09-08 17:56:02.031  3659  3928 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 17:56:02.032  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:56:02.049  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:56:02.049  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:56:02.067  3659  3929 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 17:56:02.077  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:02.082  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:02.120  1522  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 17:56:02.120  1522  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 17:56:02.121  1522  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:56:02.121  1522  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:56:02.168  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:02.173  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:02.210  1522  2317 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 17:56:02.210  1522  2317 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 17:56:02.210  1522  2317 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:56:02.210  1522  2317 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:56:02.241  3659  3929 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:56:02.242  3659  3928 E BooksSync: Soft error
09-08 17:56:02.242  3659  3928 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:56:02.242  3659  3928 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 17:56:02.242  3659  3928 E BooksSync: Sync error
09-08 17:56:02.242  3659  3928 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:56:02.242  3659  3928 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 17:56:02.243  3659  3928 I BooksSync: Finished books sync
,09-08 17:56:02.257   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 318734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:56:02.577  2674  2674 D BtGatt.ScanManager: awakened up at time 320206
,09-08 17:56:02.579  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:56:02.616  1741  3930 I EventLogService: Opted in for usage reporting
,09-08 17:56:02.618  1741  3930 I EventLogService: Aggregate from 1473348361495 (log), 1473348361495 (data)
,09-08 17:56:02.622  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 17:56:02.622  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:56:02.623  2674  2694 D BtGatt.GattService: current time is 320252066599
09-08 17:56:02.623  2674  2694 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -84, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0]
09-08 17:56:02.624  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 17:56:02.625  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
,09-08 17:56:02.679  1741  3930 W EventLogAggregator: Unknown tag: snet_gcore
09-08 17:56:02.679  1741  3930 W EventLogAggregator: Unknown tag: snet_launch_service
,09-08 17:56:02.725  1741  3930 I ServiceDumpSys: dumping service [account]
,09-08 17:56:03.126  2674  2674 D BtGatt.ScanManager: awakened up at time 320755
,09-08 17:56:03.128  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:56:03.168  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 17:56:03.169  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:56:03.169  2674  2694 D BtGatt.GattService: current time is 320798652330
09-08 17:56:03.170  2674  2694 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -88, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -85, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0]
09-08 17:56:03.171  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 17:56:03.172  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
,09-08 17:56:04.236  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:56:04.237  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:04.237  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:56:04.238  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:04.238  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 17:56:04.238  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:56:04.239  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:56:04.239  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:56:04.239  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 17:56:04.240  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:56:04.240  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 17:56:04.242  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:56:04.244  2674  2684 D BtGatt.GattService: stopScan() - queue size =1
09-08 17:56:04.246  2674  2685 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:56:04.248  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:56:04.248  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 17:56:04.248  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 17:56:04.249  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:56:04.249  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 17:56:04.253  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:56:04.253  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:56:04.253  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:56:04.254  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 17:56:04.255  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:56:04.258  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:56:04.259  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:56:04.259  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:56:04.259  2674  2674 D BtGatt.ScanManager: awakened up at time 321888
,09-08 17:56:04.261  2674  2694 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 17:56:04.261  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:56:04.261  2674  2704 D BtGatt.ScanManager: stopping BLe Batch
,09-08 17:56:04.275  2674  2694 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:56:04.275  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:56:04.276  2674  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:56:04.325  2674  2694 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 17:56:04.325  2674  2694 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:56:04.327  2674  2694 D BtGatt.GattService: current time is 321956145754
,09-08 17:56:04.328  2674  2694 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -90, 15, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -95, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-08 17:56:04.328  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-08 17:56:04.329  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 17:56:04.330  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:56:04.331  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 17:56:04.332  2674  2694 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-08 17:56:04.759  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:56:04.760  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:04.760  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:56:09.261  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.262  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:56:09.263  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:56:09.264  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:56:09.264  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.264  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:56:09.265  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
,09-08 17:56:09.265  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.265  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.266  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:56:09.266  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.268  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.268  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.272  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.272  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:56:09.272  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.273  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.275  3878  3924 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 17:56:09.277  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:56:09.277  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:09.278  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.278  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.278  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.279  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.279  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.279  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.280  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.280  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.280  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.280  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.281  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.281  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.284  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.285  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.285  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.285  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:56:09.289  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 17:56:09.289  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:56:09.289  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:09.289  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.290  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.290  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.290  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.290  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.290  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.291  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.291  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:56:09.291  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.291  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.291  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.291  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.294  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.295  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.295  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.295  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:56:09.296  3878  3924 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 17:56:09.297  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.297  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:56:09.297  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.297  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.298  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.298  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.298  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.298  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.298  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.299  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.299  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:09.299  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.299  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.299  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.302  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:56:09.302  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.302  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.302  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.303  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 17:56:09.303  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.303  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:09.303  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.304  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.304  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.304  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.304  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
,09-08 17:56:09.304  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.304  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.304  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.304  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.304  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.304  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.304  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.307  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.307  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.307  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.308  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:56:09.309  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 17:56:09.309  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:56:09.310  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:56:09.310  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 17:56:09.310  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:56:09.310  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:56:09.310  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 17:56:09.311  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 17:56:09.311  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:56:09.311  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.312  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:09.312  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.312  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:56:09.312  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.312  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.313  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.313  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.313  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.313  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.313  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.313  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.314  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.314  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.316  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.317  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:56:09.317  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.317  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:56:09.319  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 17:56:09.319  3878  3924 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 17:56:09.319  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 17:56:09.328  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 17:56:09.328  3878  3924 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-08 17:56:09.329  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 17:56:09.329  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 17:56:09.329  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 17:56:09.329  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 17:56:09.329  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 17:56:09.330  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 17:56:09.331  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 17:56:09.332  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 17:56:09.332  3878  3924 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 17:56:09.332  3878  3924 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-08 17:56:09.332  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:56:09.332  3878  3924 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 17:56:09.332  3878  3924 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 17:56:09.333  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:56:09.333  3878  3924 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 17:56:09.333  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-08 17:56:09.338  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 17:56:09.339  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 17:56:09.340  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 17:56:09.341  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 17:56:09.341  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 17:56:09.341  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 17:56:09.341  3878  3924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:56:09.341  3878  3924 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 17:56:09.342  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.342  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:56:09.342  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.343  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.343  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.343  3878  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
09-08 17:56:09.343  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.343  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 17:56:09.344  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.344  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.344  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.344  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.344  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.344  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.344  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:09.344  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.345  3878  3933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-08 17:56:09.346  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.347  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.347  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.347  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.348  3878  3924 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 17:56:09.348  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.348  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:56:09.348  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.348  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.349  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.349  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.349  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.349  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.349  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.349  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.349  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.349  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.349  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.349  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.350  3878  3932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 17:56:09.351  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.351  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.351  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.351  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.352  3878  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-08 17:56:09.352  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.353  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:09.353  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:09.353  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.353  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.353  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.353  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
,09-08 17:56:09.353  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.353  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.353  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.353  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:09.353  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.353  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.354  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.355  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.355  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:09.355  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.355  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.356  3878  3924 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 17:56:09.356  3878  3924 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 17:56:09.356  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 17:56:09.356  3878  3924 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-08 17:56:09.357  3878  3924 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 17:56:09.357  3878  3924 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 17:56:09.357  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 17:56:09.357  3878  3924 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 17:56:09.357  3878  3924 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 17:56:09.357  3878  3924 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 17:56:09.357  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 17:56:09.357  3878  3924 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 17:56:09.357  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:09.358  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:09.358  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:56:09.358  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.358  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.358  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.358  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.358  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.358  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.358  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.358  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.359  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.359  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.359  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.362  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:09.362  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:56:09.363  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.363  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:09.363  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:09.363  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.363  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:09.363  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:09.364  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:09.364  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
,09-08 17:56:09.364  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:09.364  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:09.364  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:09.942   873  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 17:56:14.365  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:56:14.365  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.366  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:14.366  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:14.366  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.367  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.367  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:14.368  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:56:14.368  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:56:14.369  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:56:14.369  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.370  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.370  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.370  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:56:14.371  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.371  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:14.371  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:14.372  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:14.372  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:14.372  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.378  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:14.378  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:14.378  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.379  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.386  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 17:56:14.386  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:56:14.388  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 17:56:14.389  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 17:56:14.389  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 17:56:14.389  3878  3878 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 17:56:14.389  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 17:56:14.389  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:56:14.390  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:56:14.390  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 17:56:14.390  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 17:56:14.390  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 17:56:14.390  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.390  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 17:56:14.391  3878  3878 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 17:56:14.391  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.391  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.391  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 17:56:14.391  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:56:14.391  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:56:14.391  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.391  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:14.393  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:56:14.393  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:56:14.393  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:56:14.394  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.394  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:56:14.393  3878  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 17:56:14.394  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:56:14.394  3878  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 17:56:14.394  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:56:14.394  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:14.395  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:14.395  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.395  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.395  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.395  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.395  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.395  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:14.395  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.395  3878  3878 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 17:56:14.395  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.396  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.396  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.397  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:14.397  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:14.398  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.398  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.400  3878  3924 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 17:56:14.400  3878  3924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 17:56:14.400  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 17:56:14.403  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:56:14.403  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:56:14.403  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:14.404  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:14.404  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:14.404  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:14.405  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.405  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.405  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.405  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.405  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.405  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:14.405  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.405  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.406  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.406  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:14.410  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:14.410  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:14.410  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.410  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.416  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:14.416  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:14.416  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:14.416  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:14.416  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.416  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.416  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.416  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.416  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.417  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:14.417  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.417  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.417  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.417  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.418  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:14.419  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:14.419  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.419  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.422  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:56:14.422  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:56:14.422  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:56:14.422  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:56:14.423  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.423  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.423  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acdf05 not in the list
09-08 17:56:14.423  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.424  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.424  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:14.424  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.425  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.425  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:14.425  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:14.427  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:56:14.427  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:56:14.427  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:14.427  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cab5a not in the list
09-08 17:56:14.428  3878  3924 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 17:56:14.428  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 17:56:14.428  3878  3924 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 17:56:14.429  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 17:56:14.429  3878  3924 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 17:56:14.429  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 17:56:14.431  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 17:56:14.431  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 17:56:14.433  3878  3924 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 17:56:14.433  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 17:56:14.433  3878  3924 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 17:56:14.433  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 17:56:14.433  3878  3924 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 17:56:14.433  3878  3924 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 17:56:14.434  3878  3924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 17:56:14.434  3878  3924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 17:56:14.435  3878  3924 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 17:56:14.435  3878  3924 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 17:56:14.435  3878  3924 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 17:56:14.435  3878  3924 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 17:56:14.436  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:56:14.436  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7873aac added. We now have 3 listener(s)
09-08 17:56:14.436  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:56:14.439  3878  3924 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 17:56:14.439   873   883 D WifiService: setWifiEnabled: true pid=3878, uid=10000
09-08 17:56:14.439   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:56:14.489  2674  2773 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-08 17:56:14.489  2674  2804 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-08 17:56:14.490  3878  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
,09-08 17:56:14.894  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:56:19.448  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:56:19.449  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57c9375 added. We now have 4 listener(s)
09-08 17:56:19.449  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:56:19.465  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:56:19.465  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57c9375 removed from the list
,09-08 17:56:19.465  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:19.466  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:19.466  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:19.472  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:56:19.473  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c769f0a added. We now have 4 listener(s)
09-08 17:56:19.473  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:56:19.476  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:56:19.477  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c769f0a removed from the list
09-08 17:56:19.477  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:19.477  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:19.478  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:19.480  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:56:19.480  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb2f37b added. We now have 4 listener(s)
09-08 17:56:19.481  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:56:19.487   873  2114 D WifiService: setWifiEnabled: false pid=3878, uid=10000
,09-08 17:56:19.488   873  2114 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:56:19.506  2674  2690 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 17:56:19.506  2674  2690 D BluetoothAdapterProperties: Setting state to 13
,09-08 17:56:19.506  2674  2690 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 17:56:19.509  2674  2690 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 17:56:19.517  2674  2690 I BluetoothAdapterState: Entering PendingCommandState
09-08 17:56:19.519  2674  2674 D BluetoothMapService: onReceive
09-08 17:56:19.519  2674  2674 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 17:56:19.520  2674  2674 D BluetoothMapService: STATE_TURNING_OFF
09-08 17:56:19.521  2674  2674 D BluetoothMapService: MAP Service closeService in
09-08 17:56:19.521  2674  2674 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 17:56:19.522  2674  2674 D ObexServerSockets0: shutdown(block = true)
,09-08 17:56:19.523  2674  2830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 17:56:19.529  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:56:19.529  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:56:19.510  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:56:19.529  2674  2804 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 17:56:19.530  2674  2831 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 17:56:19.531  2674  2674 I BtOppRfcommListener: stopping Accept Thread
09-08 17:56:19.531  2674  3430 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 17:56:19.531  2674  3430 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 17:56:19.534  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:56:19.534  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:56:19.535  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.535  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:19.535  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:56:19.538  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:19.540  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:19.543  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 17:56:19.544  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:56:19.544  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:56:19.545  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.545  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:19.545   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 17:56:19.545   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 17:56:19.545   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:56:19.546   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 17:56:19.550  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:56:19.550  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:56:19.550  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.551  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:19.553  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:19.556   873   886 I ActivityManager: Start proc 3939:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 17:56:19.557  2674  2694 D BluetoothAdapterProperties: Scan Mode:20
,09-08 17:56:19.557  2674  2690 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 17:56:19.560   873  1307 E native  : do suspend true
,09-08 17:56:19.562  2674  2674 D HeadsetService: Received stop request...Stopping profile...
,09-08 17:56:19.562  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:19.565  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:19.565   873   873 D BluetoothHeadset: Proxy object disconnected
,09-08 17:56:19.565  1933  1945 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:19.565   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:19.566  1364  1384 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:19.566  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,09-08 17:56:19.567  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:19.567  2674  2674 D A2dpService: Received stop request...Stopping profile...
09-08 17:56:19.568   873   873 D BluetoothHeadset: Proxy object disconnected
,09-08 17:56:19.568  2674  2810 D A2dpStateMachine: Exit Disconnected: -1
,09-08 17:56:19.569  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-08 17:56:19.570   873   873 D BluetoothA2dp: Proxy object disconnected
,09-08 17:56:19.570  2674  2674 V BluetoothAdapterState: isTurningOff()=true
,09-08 17:56:19.571  2674  2674 V BluetoothAdapterState: isTurningOn()=false,
09-08 17:56:19.571  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:19.571  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:19.572  2674  2674 D HidService: Received stop request...Stopping profile...,
09-08 17:56:19.572  2674  2674 D HidService: Stopping Bluetooth HidService
09-08 17:56:19.573  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-08 17:56:19.573  1364  1364 D HidProfile: Bluetooth service disconnected
09-08 17:56:19.574   873  1868 D DhcpClient: Clearing IP address
09-08 17:56:19.574   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-08 17:56:19.575  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 17:56:19.575  2674  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 17:56:19.575  2674  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:19.576  2674  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:19.577  2674  2694 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 17:56:19.578  2674  2694 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 17:56:19.578   372   871 D CommandListener: Setting iface cfg,
09-08 17:56:19.579  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 17:56:19.580  2674  2674 D HealthService: Received stop request...Stopping profile...
09-08 17:56:19.582   873  1880 D DhcpClient: Receive thread stopped
09-08 17:56:19.583   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 17:56:19.583   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-08 17:56:19.586   415   415 E Parcel  : Reading a NULL string not supported here.
,09-08 17:56:19.586   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 17:56:19.590  1522  2119 V NativeCrypto: Read error: ssl=0xaeb6ae00: I/O error during system call, Connection timed out
09-08 17:56:19.591   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 17:56:19.591   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:56:19.591   873  1307 E native  : do suspend true
,09-08 17:56:19.593  1522  2119 V NativeCrypto: SSL shutdown failed: ssl=0xaeb6ae00: I/O error during system call, Broken pipe
,09-08 17:56:19.593  2674  2674 D PanService: Received stop request...Stopping profile...
09-08 17:56:19.594  2674  2674 D BluetoothMapService: Received stop request...Stopping profile...
09-08 17:56:19.595  2674  2674 D BluetoothMapService: stop()
09-08 17:56:19.595  2674  2674 D BluetoothMapAppObserver: deinitObservers()
09-08 17:56:19.595  2674  2674 D BluetoothMapAppObserver: removeReceiver()
09-08 17:56:19.597  2674  2674 V BluetoothAdapterState: isTurningOff()=true
,09-08 17:56:19.597  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:19.597  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:19.597  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:19.598  2674  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:19.599  2674  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:19.600  2674  2694 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 17:56:19.600  2674  2773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:56:19.600  2674  2773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 17:56:19.600  2674  2773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:56:19.600  2674  2773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 17:56:19.600  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:19.600  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:19.601  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:19.601  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:19.601  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 17:56:19.601  2674  2694 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:56:19.603  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 17:56:19.603  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:19.603  2674  2674 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:56:19.604  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:19.604  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:19.604  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 17:56:19.604  2674  2694 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 17:56:19.605  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 17:56:19.605  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:19.605  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:19.605  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:19.605  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:19.606  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 17:56:19.606  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 17:56:19.607  2674  2674 D BluetoothMapService: MAP Service closeService in
09-08 17:56:19.607  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:19.607  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:19.607  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 17:56:19.607  1364  1364 D PanProfile: Bluetooth service disconnected
09-08 17:56:19.607  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:19.607  1364  1364 D BluetoothMap: Proxy object disconnected
09-08 17:56:19.607  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:19.607  1364  1364 D MapProfile: Bluetooth service disconnected
,09-08 17:56:19.607  2674  2690 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 17:56:19.607  2674  2690 D BluetoothAdapterProperties: Setting state to 15
09-08 17:56:19.607  2674  2674 D BluetoothMapService: cleanup()
09-08 17:56:19.607  2674  2690 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 17:56:19.607  2674  2674 D BluetoothMapService: MAP Service closeService in
09-08 17:56:19.608   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:19.608  1933  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:19.608  1364  1378 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 17:56:19.609  2674  2690 I BluetoothAdapterState: Entering BleOnState
09-08 17:56:19.610  1364  2229 D BluetoothPan: onBluetoothStateChange on: false
,09-08 17:56:19.610   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:19.610  1364  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-08 17:56:19.611   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:19.611   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:56:19.611  1364  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 17:56:19.612  1364  2229 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:19.612  1364  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:56:19.613  2674  2690 D BluetoothAdapterState: Current state: BLE ON, message: 20,
09-08 17:56:19.613  2674  2690 D BluetoothAdapterProperties: Setting state to 16
09-08 17:56:19.613  2674  2690 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 17:56:19.613  2674  2690 D BluetoothAdapterProperties: onBleDisable
09-08 17:56:19.613  2674  2690 I BluetoothAdapterState: Entering PendingCommandState
09-08 17:56:19.614  2674  2691 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 17:56:19.614  2674  2694 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:56:19.616  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:19.616  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:19.617  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.617  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:19.619  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:19.619  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:19.620  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.620  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:19.622  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:19.622  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:19.623  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:19.623  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:19.623   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:56:19.623  3939  3939 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 17:56:19.624  2674  2773 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 17:56:19.624  2674  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 17:56:19.625  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:19.626  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:19.628  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:19.635  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:56:19.641  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:19.644   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6959f8:true
,09-08 17:56:19.647   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 17:56:19.648   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-08 17:56:19.648   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 17:56:19.649   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:56:19.657   873  2111 I ActivityManager: Start proc 3955:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-08 17:56:19.661   873   890 D Tethering: MasterInitialState.processMessage what=3
09-08 17:56:19.663   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:56:19.663  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:19.665  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:19.666  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:19.678  3939  3939 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 17:56:19.682   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:56:19.684  2120  2324 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 17:56:19.684  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:19.684  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:19.685  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.685  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:19.685  3939  3939 D BluetoothMap: Create BluetoothMap proxy object
09-08 17:56:19.686   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 17:56:19.686  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:19.686  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:19.687  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.687  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:19.689  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:19.689  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:19.689  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:19.689  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:19.696  3939  3939 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-08 17:56:19.706   372   871 E Netd    : netlink response contains error (No such file or directory)
09-08 17:56:19.707   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 17:56:19.715  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 17:56:19.718  3939  3939 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:56:19.727   873  2113 I ActivityManager: Killing 2985:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 17:56:19.829  2674  2694 I bt_hci  : shut_down
09-08 17:56:19.830  2674  2709 D bt_hwcfg: hw_epilog_process
,09-08 17:56:19.841  2674  2709 I bt_vendor: low_power_mode_cb
,09-08 17:56:19.865  2674  2709 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 17:56:19.865  2674  2709 I bt_vendor: epilog_cb
09-08 17:56:19.865  2674  2709 I bt_hci  : epilog_finished_callback
,09-08 17:56:19.871  2674  2694 I bt_hci_h4: hal_close
,09-08 17:56:19.873  2674  2694 I bt_userial_vendor: device fd = 51 close
,09-08 17:56:19.989  3955  3955 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.989  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:56:19.990  3955  3955 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:56:19.990  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 17:56:20.023   873   883 I ActivityManager: Start proc 3990:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-08 17:56:20.024   873   883 I ActivityManager: Killing 3598:com.google.android.deskclock/u0a44 (adj 15): empty #17
,09-08 17:56:20.087  2674  2691 D bt_stack_manager: event_shut_down_stack finished.
09-08 17:56:20.087  2674  2690 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 17:56:20.089  2674  2690 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 17:56:20.089  2674  2674 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:56:20.090  2674  2674 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 17:56:20.090  2674  2674 D BtGatt.GattService: stop()
09-08 17:56:20.090  2674  2674 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 17:56:20.091  2674  2674 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:20.091  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:20.091  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:20.091  2674  2674 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 17:56:20.091  2674  2690 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 17:56:20.091  2674  2690 D BluetoothAdapterProperties: Setting state to 10
,09-08 17:56:20.092  2674  2690 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 17:56:20.092  2674  2690 I BluetoothAdapterState: Entering OffState
,09-08 17:56:20.093   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 17:56:20.103  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 17:56:20.103  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 17:56:20.103  2674  2674 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 17:56:20.104  2674  2691 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 17:56:20.107  2674  2691 D bt_stack_manager: event_clean_up_stack finished.
,09-08 17:56:20.117  3990  3990 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-08 17:56:20.119  2674  2674 I art     : System.exit called, status: 0
,09-08 17:56:20.119  2674  2674 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 17:56:20.191   873  2113 I ActivityManager: Process com.android.bluetooth (pid 2674) has died
,09-08 17:56:20.384  3990  4010 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-08 17:56:20.384  3990  4010 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 17:56:20.391  3990  4010 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 17:56:20.391  3990  4010 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 17:56:20.422  3990  4010 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-08 17:56:20.422  3990  4010 I Babel_SMS: MmsConfig.loadFromResources
,09-08 17:56:20.424  3990  4010 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 17:56:20.425  3990  4010 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 17:56:20.461  3990  3990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 17:56:20.463  3990  3990 I Babel_Crash: startup - clean
,09-08 17:56:20.489  3990  3990 I Babel_telephony: TeleModule.launchCompleted
,09-08 17:56:20.499   873  2114 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 17:56:20.503  3990  3990 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-08 17:56:20.517  3990  3990 W Babel   : BAM#gBA: invalid account id: -1
,09-08 17:56:20.517  3990  3990 W Babel   : BAM#gBA: invalid account id: -1
09-08 17:56:20.517  3990  3990 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-08 17:56:20.521  3990  4015 I Babel   : deleted: false for 0
,09-08 17:56:20.529   873  2113 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 17:56:20.541  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:56:20.569   873  2111 I ActivityManager: Start proc 4018:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-08 17:56:20.580  3939  3939 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:56:20.593  3955  3976 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 17:56:20.613  3990  3990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 17:56:20.693  3990  3990 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 17:56:20.707  3990  3990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 17:56:20.709  3990  3990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 17:56:20.725  3990  3990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 17:56:20.738  3990  3990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 17:56:20.757  3990  3990 I vclib   : onServiceConnected
,09-08 17:56:20.761  4018  4018 D AdapterServiceConfig: Adding HeadsetService
09-08 17:56:20.761  4018  4018 D AdapterServiceConfig: Adding A2dpService
09-08 17:56:20.761  4018  4018 D AdapterServiceConfig: Adding HidService
,09-08 17:56:20.761  4018  4018 D AdapterServiceConfig: Adding HealthService
09-08 17:56:20.762  4018  4018 D AdapterServiceConfig: Adding PanService
09-08 17:56:20.762  4018  4018 D AdapterServiceConfig: Adding GattService
09-08 17:56:20.762  4018  4018 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 17:56:20.773   873  1372 I ActivityManager: Killing 3616:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-08 17:56:20.810   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11bf0b3:true
,09-08 17:56:20.843  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:20.871  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:56:20.879  1741  1741 D SystemUpdateService: onCreate
,09-08 17:56:20.886  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:56:20.890  1741  4030 I SystemUpdateService: active receiver: enabled
,09-08 17:56:20.894  1741  4030 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:56:20.898  1741  4030 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 17:56:20.898  1741  4030 I SystemUpdateService: now status is 0 (complete)
09-08 17:56:20.898  1741  4030 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:56:20.898  1741  4030 I SystemUpdateService: file has been verified
09-08 17:56:20.899  1741  4030 I SystemUpdateService: OTA package size = 12249756
,09-08 17:56:20.904  1741  4030 I SystemUpdateService: showing system update notification
,09-08 17:56:20.905  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 17:56:20.910  1741  2434 I iu.UploadsManager: num queued entries: 0
,09-08 17:56:20.912  1741  2434 I iu.UploadsManager: num updated entries: 0
,09-08 17:56:20.914  1741  2434 I iu.SyncManager: NEXT; no task
,09-08 17:56:20.916  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 17:56:20.918  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:56:20.934   873  1372 I ActivityManager: Start proc 4032:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 17:56:20.936  1741  1741 D SystemUpdateService: onDestroy
,09-08 17:56:20.973  4032  4032 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 17:56:20.976  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:56:20.981  4032  4032 D SprintDMHelper: simOperator: 
09-08 17:56:20.981  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:56:21.004   873  1930 I ActivityManager: Start proc 4044:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 17:56:21.005   873  1930 I ActivityManager: Killing 3469:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 17:56:21.140   873  2094 I ActivityManager: Start proc 4059:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 17:56:21.144  3990  4058 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 17:56:21.148   873  2111 I ActivityManager: Killing 1689:android.process.acore/u0a5 (adj 15): empty #17
,09-08 17:56:21.224  4059  4059 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 17:56:21.288  4059  4059 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 17:56:21.288  4059  4059 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 17:56:21.288  4059  4059 I GAv4    :   adb logcat -s GAv4
,09-08 17:56:21.305  4059  4059 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 17:56:21.310  4059  4059 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 17:56:21.338  4059  4076 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 17:56:21.442  4059  4059 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 17:56:21.485  4059  4059 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 17:56:21.493  4059  4059 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9119-9122)
09-08 17:56:21.493  4059  4059 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 17:56:21.507  4059  4059 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b9372ef}
,09-08 17:56:21.508  4059  4059 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 17:56:21.508  4059  4059 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 17:56:21.517  4059  4059 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 17:56:21.519  4059  4059 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 17:56:21.531  4059  4059 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 17:56:21.543  4059  4059 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 17:56:21.543  4059  4059 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 17:56:21.543  4059  4059 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 17:56:21.543  4059  4059 I Adreno  : Build Date                       : 10/20/15
09-08 17:56:21.543  4059  4059 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 17:56:21.543  4059  4059 I Adreno  : Local Branch                     : M14
09-08 17:56:21.543  4059  4059 I Adreno  : Remote Branch                    : 
09-08 17:56:21.543  4059  4059 I Adreno  : Remote Branch                    : 
09-08 17:56:21.543  4059  4059 I Adreno  : Reconstruct Branch               : 
,09-08 17:56:21.608  4059  4059 I NSApplication: Starting up...
,09-08 17:56:21.617  4059  4105 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 17:56:21.648   873  1902 I ActivityManager: Start proc 4110:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 17:56:21.649   873  1902 I ActivityManager: Killing 3699:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 17:56:21.730  4110  4110 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 17:56:21.912   873  1917 I ActivityManager: Killing 3716:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 17:56:22.032   873  1902 I ActivityManager: Start proc 4124:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 17:56:22.078  4124  4124 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 17:56:22.128  4124  4124 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 17:56:22.148   873   883 I ActivityManager: Killing 2247:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 17:56:24.538   873  1547 D WifiService: setWifiEnabled: true pid=3878, uid=10000
09-08 17:56:24.538   873  1547 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:56:24.551   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-08 17:56:24.562  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:24.562  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:24.562  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:24.562  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:24.563  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:24.563  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:24.563  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:24.563  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:24.565  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:24.565  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:24.565  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:24.565  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:24.579  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:24.589  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:24.591  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:56:24.593   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-08 17:56:24.595   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 17:56:24.596   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 17:56:24.597   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 17:56:24.597   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 17:56:24.597   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 17:56:24.597   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 17:56:24.610   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-08 17:56:24.610   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:56:24.611   372   871 D CommandListener: Setting iface cfg
,09-08 17:56:24.618  1522  3805 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 17:56:24.619  1522  3805 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 17:56:24.619  1522  3805 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:56:24.619  1522  3805 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:56:24.620   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 17:56:24.620   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 17:56:24.621   873  1307 E native  : do suspend true
,09-08 17:56:24.630  1522  3805 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 17:56:24.630  1522  3805 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 17:56:24.630  1522  3805 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 17:56:24.630  1522  3805 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 17:56:24.630  1522  3805 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 17:56:24.630  1522  3805 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 17:56:24.630  1522  3805 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 17:56:24.633  3508  3539 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 17:56:24.633  3508  3539 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 17:56:24.633  3508  3539 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 17:56:24.633  3508  3539 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 17:56:24.633  3508  3539 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 17:56:24.633  3508  3539 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 17:56:24.633  3508  3539 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 17:56:24.635   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 17:56:24.635   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 17:56:24.636   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:56:25.447   873  2112 I ActivityManager: Killing 3737:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-08 17:56:25.936   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:56:25.988   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.88 rxSuccessRate=18.00 delta 1000 -> 994
,09-08 17:56:25.993   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 17:56:25.994   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:56:26.015   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 17:56:26.082   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 17:56:26.083  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 17:56:26.512  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 17:56:26.556  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 17:56:26.557  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 17:56:26.565   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:56:26.578   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:56:26.579   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 17:56:26.579   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:56:26.602   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:56:26.617   372   871 D CommandListener: Setting iface cfg
,09-08 17:56:26.618   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 17:56:26.630   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 17:56:26.665   873  4160 D DhcpClient: Receive thread started
,09-08 17:56:26.753   873  1307 E native  : do suspend false
,09-08 17:56:26.769   873  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 17:56:26.782   873  4160 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172478, domain null
,09-08 17:56:26.782   873  1868 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172478 seconds
,09-08 17:56:26.785   873  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 17:56:26.816   873  4160 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 17:56:26.817   873  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 17:56:26.821   372   871 D CommandListener: Setting iface cfg
,09-08 17:56:26.829   873  1868 D DhcpClient: Scheduling renewal in 86399s
,09-08 17:56:26.829   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 17:56:26.832   873  1307 E native  : do suspend true
,09-08 17:56:26.854   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 17:56:26.856   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 17:56:26.857   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 17:56:26.860   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 17:56:26.864   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 17:56:26.905   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 17:56:26.906   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 17:56:26.908   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 17:56:26.910   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 17:56:26.913   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 17:56:26.927   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 17:56:26.934   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-08 17:56:26.935   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 17:56:26.935   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 17:56:26.935   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 17:56:26.935   873  1309 D ConnectivityService:    accepting network in place of null
09-08 17:56:26.936   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:56:26.936   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:56:26.954   873  4159 D NetlinkSocketObserver: NeighborEvent{elapsedMs=344583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:56:26.970   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:56:27.007   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:56:27.013   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 17:56:27.014   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 17:56:27.015   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 17:56:27.019   873   890 D Tethering: MasterInitialState.processMessage what=3
09-08 17:56:27.032   873  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 17:56:27.032  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:56:27.035  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:56:27.036  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:27.038  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:27.043  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:56:27.043  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:56:27.044  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:27.044  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:56:27.050  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:56:27.050  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:56:27.050  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:27.050  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:56:27.055  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:56:27.058  1741  1741 D SystemUpdateService: onCreate
,09-08 17:56:27.061  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:56:27.081  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 17:56:27.085  1741  4169 I SystemUpdateService: active receiver: enabled
,09-08 17:56:27.088  1741  2434 I iu.UploadsManager: num queued entries: 0
,09-08 17:56:27.088  1741  2434 I iu.UploadsManager: num updated entries: 0
09-08 17:56:27.089  1741  2434 I iu.SyncManager: NEXT; no task
,09-08 17:56:27.091  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:56:27.092  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:56:27.094  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:56:27.098   873  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 15:56:27 GMT], X-Android-Received-Millis=[1473350187097], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473350187076]}
,09-08 17:56:27.098   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 17:56:27.098   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-08 17:56:27.099   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 17:56:27.099   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 17:56:27.110  1741  4171 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 17:56:27.110  1741  4171 W BaseAppContext: Using Auth Proxy for data requests.
09-08 17:56:27.111  4032  4032 D SprintDMHelper: simOperator: 
09-08 17:56:27.111  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:56:27.116  1741  4171 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 17:56:27.170  1741  4169 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:56:27.199  1741  4169 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 17:56:27.199  1741  4169 I SystemUpdateService: now status is 0 (complete)
09-08 17:56:27.199  1741  4169 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:56:27.199  1741  4169 I SystemUpdateService: file has been verified
09-08 17:56:27.200  1741  4169 I SystemUpdateService: OTA package size = 12249756
,09-08 17:56:27.211  1741  4169 I SystemUpdateService: showing system update notification
,09-08 17:56:27.240  1522  2382 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 17:56:27.240  1522  2382 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 17:56:27.240  1522  2382 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:56:27.240  1522  2382 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:56:27.250  1741  1741 D SystemUpdateService: onDestroy
,09-08 17:56:27.265  1741  4171 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-08 17:56:27.285  3990  4175 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 17:56:28.014   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 17:56:29.544   873  1953 D WifiService: setWifiEnabled: false pid=3878, uid=10000
,09-08 17:56:29.545   873  1953 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:56:29.584  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 17:56:29.592   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 17:56:29.593   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 17:56:29.594   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:56:29.594   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:56:29.626   873  1307 E native  : do suspend true
,09-08 17:56:29.642   873  1868 D DhcpClient: Clearing IP address
09-08 17:56:29.642   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-08 17:56:29.650  1522  4179 V NativeCrypto: Read error: ssl=0x9ad70600: I/O error during system call, Connection timed out
09-08 17:56:29.651   372   871 D CommandListener: Setting iface cfg
,09-08 17:56:29.652   873  4160 D DhcpClient: Receive thread stopped
,09-08 17:56:29.657   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 17:56:29.657   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 17:56:29.663  1522  4179 V NativeCrypto: SSL shutdown failed: ssl=0x9ad70600: I/O error during system call, Broken pipe
,09-08 17:56:29.663   415   415 E Parcel  : Reading a NULL string not supported here.
09-08 17:56:29.664   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 17:56:29.664   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 17:56:29.665   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:56:29.665   873  1307 E native  : do suspend true
,09-08 17:56:29.704   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:56:29.735   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:56:29.735   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-08 17:56:29.737   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 17:56:29.737   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:56:29.743   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:56:29.744   873   890 D Tethering: MasterInitialState.processMessage what=3
09-08 17:56:29.760  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:29.760  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:29.761  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:29.761  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:29.764  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:29.764  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:29.764  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.765  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:29.768  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:29.768  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:29.768  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.768  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:29.781   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:56:29.785  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:29.785  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:29.785  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.785  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:29.787  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:29.787  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:29.787  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.787  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:29.788  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:29.788  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:29.788  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:29.788  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:29.789  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:56:29.789   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 17:56:29.793  2120  2324 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 17:56:29.795  1741  1741 D SystemUpdateService: onCreate
,09-08 17:56:29.798  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:56:29.807  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 17:56:29.809  1741  2434 I iu.UploadsManager: num queued entries: 0
09-08 17:56:29.809  1741  2434 I iu.UploadsManager: num updated entries: 0
09-08 17:56:29.810  1741  2434 I iu.SyncManager: NEXT; no task
,09-08 17:56:29.814  1741  4191 I SystemUpdateService: active receiver: enabled
,09-08 17:56:29.815  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:56:29.817  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:56:29.819  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:56:29.822  4032  4032 D SprintDMHelper: simOperator: 
,09-08 17:56:29.822  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:56:29.826  1741  4191 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:56:29.828  1741  4191 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 17:56:29.828  1741  4191 I SystemUpdateService: now status is 0 (complete)
09-08 17:56:29.829  1741  4191 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 17:56:29.830  1741  4191 I SystemUpdateService: file has been verified
,09-08 17:56:29.830  1741  4191 I SystemUpdateService: OTA package size = 12249756
,09-08 17:56:29.835   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-08 17:56:29.836   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 17:56:29.842  3990  4194 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 17:56:29.848  1741  4191 I SystemUpdateService: showing system update notification
,09-08 17:56:29.872  1741  1741 D SystemUpdateService: onDestroy
,09-08 17:56:33.101  1870  1964 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-08 17:56:33.101  1870  1964 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 17:56:33.133  1522  1522 I ConfigService: onCreate
,09-08 17:56:34.599   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0596c0:true
,09-08 17:56:34.599  4018  4018 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 17:56:34.605  4018  4018 I bt_bluedroid: init
,09-08 17:56:34.605  4018  4200 I BluetoothAdapterState: Entering OffState
,09-08 17:56:34.613  4018  4201 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 17:56:34.613  4018  4201 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 17:56:34.613  4018  4201 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 17:56:34.614  4018  4201 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 17:56:34.618  4018  4018 I bt_bluedroid: get_profile_interface socket
,09-08 17:56:34.621  4018  4018 I bt_bluedroid: get_profile_interface sdp
,09-08 17:56:34.625  4018  4204 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:56:34.626  4018  4028 I bt_bluedroid: config_hci_snoop_log
09-08 17:56:34.627  4018  4204 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 17:56:34.629   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 17:56:34.639  4018  4200 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 17:56:34.640  4018  4200 D BluetoothAdapterProperties: Setting state to 14
09-08 17:56:34.640  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 17:56:34.646  4018  4200 D BluetoothBondStateMachine: make
,09-08 17:56:34.652  4018  4205 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 17:56:34.660  4018  4200 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:56:34.664  4018  4018 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 17:56:34.672  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:34.675  4018  4018 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:56:34.677  4018  4018 D BtGatt.GattService: Received start request. Starting profile...
,09-08 17:56:34.678  4018  4018 D BtGatt.GattService: start()
,09-08 17:56:34.678  4018  4018 I bt_bluedroid: get_profile_interface gatt
09-08 17:56:34.681  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:34.681  4018  4018 D BtGatt.AdvertiseManager: advertise manager created
,09-08 17:56:34.694  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:34.694  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:34.695  4018  4018 V BluetoothAdapterState: isBleTurningOn()=true
09-08 17:56:34.695  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:34.696  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 17:56:34.696  4018  4200 I bt_bluedroid: enable
09-08 17:56:34.697  4018  4201 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 17:56:34.699  4018  4201 I bt_hci  : start_up
,09-08 17:56:34.723  4018  4201 I bt_vendor: alloc value 0xb39a9189
,09-08 17:56:34.723  4018  4201 I bt_vendor: init
09-08 17:56:34.723  4018  4201 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 17:56:34.723  4018  4201 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 17:56:34.828  4018  4201 D bt_hci  : start_up starting async portion
,09-08 17:56:34.829  4018  4208 I bt_hci  : event_finish_startup
09-08 17:56:34.829  4018  4208 I bt_hci_h4: hal_open
09-08 17:56:34.830  4018  4208 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 17:56:34.837  4018  4208 I bt_userial_vendor: device fd = 51 open
,09-08 17:56:34.871  4018  4208 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:56:34.903  4018  4208 D bt_hwcfg: Chipset BCM4354A2
,09-08 17:56:34.904  4018  4208 D bt_hwcfg: Target name = [BCM4354A2]
09-08 17:56:34.904  4018  4208 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 17:56:34.939   873  1309 D ConnectivityService: handlePromptUnvalidated 101
,09-08 17:56:35.571  4018  4208 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 17:56:35.573  4018  4208 D bt_hwcfg: Settlement delay -- 100 ms
09-08 17:56:35.573  4018  4208 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 17:56:35.690  4018  4208 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:56:35.691  4018  4208 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 17:56:35.720  4018  4208 I bt_hwcfg: vendor lib fwcfg completed
,09-08 17:56:35.720  4018  4208 I bt_vendor: firmware callback
09-08 17:56:35.721  4018  4208 I bt_hci  : firmware_config_callback
,09-08 17:56:35.733  4018  4212 I bt_btu  : btu_task pending for preload complete event
,09-08 17:56:35.733  4018  4212 I bt_btu_task: Bluetooth chip preload is complete
09-08 17:56:35.733  4018  4212 I bt_btu  : btu_task received preload complete event
,09-08 17:56:35.745  4018  4212 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 17:56:35.745  4018  4212 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 17:56:35.745  4018  4212 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 17:56:35.745  4018  4212 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 17:56:35.746  4018  4212 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 17:56:35.746  4018  4212 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 17:56:35.746  4018  4212 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 17:56:35.747  4018  4212 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 17:56:35.747  4018  4212 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 17:56:35.748  4018  4212 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 17:56:35.748  4018  4212 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 17:56:35.748  4018  4212 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 17:56:35.749  4018  4212 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 17:56:35.749  4018  4212 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 17:56:35.749  4018  4212 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 17:56:35.884  4018  4212 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,09-08 17:56:35.885  4018  4212 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,09-08 17:56:35.896  4018  4204 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 17:56:35.897  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:56:35.898  4018  4204 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:56:35.901  4018  4204 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 17:56:35.904  4018  4204 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:56:35.904  4018  4204 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 17:56:35.905  4018  4204 D bt_hci  : do_postload posting postload work item
09-08 17:56:35.905  4018  4208 I bt_hci  : event_postload
,09-08 17:56:35.905  4018  4208 I bt_vendor: sco_config_cb
09-08 17:56:35.905  4018  4208 I bt_hci  : sco_config_callback postload finished.
,09-08 17:56:35.910  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:35.911  4018  4208 I bt_vendor: low_power_mode_cb
,09-08 17:56:35.912  4018  4204 D bt_bte_conf: Device ID record 1 : primary
09-08 17:56:35.912  4018  4204 D bt_bte_conf:   vendorId            = 000f
09-08 17:56:35.912  4018  4204 D bt_bte_conf:   vendorIdSource      = 0001
09-08 17:56:35.912  4018  4204 D bt_bte_conf:   product             = 1200
,09-08 17:56:35.912  4018  4204 D bt_bte_conf:   version             = 1436
09-08 17:56:35.913  4018  4204 D bt_bte_conf:   clientExecutableURL = 
09-08 17:56:35.913  4018  4204 D bt_bte_conf:   serviceDescription  = 
09-08 17:56:35.913  4018  4204 D bt_bte_conf:   documentationURL    = 
09-08 17:56:35.913  4018  4204 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 17:56:35.913  4018  4201 D bt_stack_manager: event_start_up_stack finished
09-08 17:56:35.914  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:35.915  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 17:56:35.915  4018  4200 D BluetoothAdapterProperties: Setting state to 15
09-08 17:56:35.916  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 17:56:35.917  4018  4200 I BluetoothAdapterState: Entering BleOnState
09-08 17:56:35.919  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:35.923  4018  4200 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 17:56:35.923  4018  4200 D BluetoothAdapterProperties: Setting state to 11
09-08 17:56:35.923  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 17:56:35.930  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:35.933  4018  4018 D HeadsetService: Received start request. Starting profile...
09-08 17:56:35.938  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:35.940  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:35.942  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:35.945  4018  4018 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 17:56:35.946  4018  4018 D HeadsetStateMachine: make
,09-08 17:56:35.950  4018  4200 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:56:35.955  4018  4018 D HeadsetStateMachine: max_hf_connections = 1
,09-08 17:56:35.955  4018  4018 I bt_bluedroid: get_profile_interface handsfree
,09-08 17:56:35.956  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 17:56:35.956  4018  4204 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 17:56:35.960  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:35.960  4018  4018 D A2dpService: Received start request. Starting profile...
09-08 17:56:35.961  4018  4018 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 17:56:35.961  4018  4018 I bt_bluedroid: get_profile_interface avrcp
,09-08 17:56:35.969  4018  4018 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 17:56:35.969  4018  4018 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-08 17:56:35.969  4018  4018 D A2dpStateMachine: make
,09-08 17:56:35.972  4018  4018 I bt_bluedroid: get_profile_interface a2dp
,09-08 17:56:35.972  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-08 17:56:35.974  4018  4222 D A2dpStateMachine: Enter Disconnected: -2
09-08 17:56:35.975  4018  4018 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 17:56:35.976  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:35.977  4018  4018 D HidService: Received start request. Starting profile...
09-08 17:56:35.977  3939  3939 D BluetoothInputDevice: Proxy object connected
09-08 17:56:35.977  4018  4018 I bt_bluedroid: get_profile_interface hidhost
09-08 17:56:35.977  4018  4018 D HidService: setHidService(): set to: null
09-08 17:56:35.978  4018  4204 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
09-08 17:56:35.978  4018  4018 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 17:56:35.978  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 17:56:35.978  3939  3939 D HidProfile: Bluetooth service connected
09-08 17:56:35.978  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:35.979  4018  4018 D HealthService: Received start request. Starting profile...
,09-08 17:56:35.981  4018  4018 I bt_bluedroid: get_profile_interface health
,09-08 17:56:35.982  4018  4018 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 17:56:35.983  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:35.986  4018  4018 D PanService: Received start request. Starting profile...
,09-08 17:56:35.986  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 17:56:35.986  4018  4018 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 17:56:35.986  4018  4018 I bt_bluedroid: get_profile_interface pan
09-08 17:56:35.987  4018  4204 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 17:56:35.988  3939  3939 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 17:56:35.988  3939  3939 D PanProfile: Bluetooth service connected
,09-08 17:56:35.991  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:35.992  3939  3939 D BluetoothMap: Proxy object connected
,09-08 17:56:35.993  4018  4018 D BluetoothMapService: Received start request. Starting profile...
09-08 17:56:35.993  4018  4018 D BluetoothMapService: start()
09-08 17:56:35.993  3939  3939 D MapProfile: Bluetooth service connected
,09-08 17:56:35.993  3939  3939 D BluetoothMap: getConnectedDevices()
09-08 17:56:35.994  3939  3939 D BluetoothMap: Bluetooth is Not enabled
,09-08 17:56:35.998  4018  4018 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 17:56:35.999  4018  4018 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 17:56:35.999  4018  4018 D BluetoothMapAppObserver: createReceiver()
,09-08 17:56:36.002  4018  4018 D BluetoothMapAppObserver: initObservers()
,09-08 17:56:36.002  4018  4018 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 17:56:36.015  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:36.015  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:36.015  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:36.015  4018  4220 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 17:56:36.015  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:36.016  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:56:36.017  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:36.018  4018  4018 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:36.018  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:36.018  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:36.018  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:36.018  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 17:56:36.018  4018  4200 D BluetoothAdapterProperties: ScanMode =  20
09-08 17:56:36.018  4018  4200 D BluetoothAdapterProperties: State =  11
,09-08 17:56:36.021  4018  4204 D BluetoothAdapterProperties: Scan Mode:21
,09-08 17:56:36.023  4018  4200 D BluetoothAdapterProperties: Setting state to 12
09-08 17:56:36.023  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:36.024  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 17:56:36.024  4018  4204 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 17:56:36.025  3939  3949 D BluetoothPan: onBluetoothStateChange on: true
09-08 17:56:36.025   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:36.025  1933  2076 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:36.025  4018  4200 I BluetoothAdapterState: Entering OnState
09-08 17:56:36.026  1364  1384 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:36.028  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:36.028  1364  2229 D BluetoothPan: onBluetoothStateChange on: true
,09-08 17:56:36.030  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 17:56:36.030  1364  1364 D PanProfile: Bluetooth service connected
,09-08 17:56:36.030   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:36.031  1364  2229 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 17:56:36.031  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:36.033  1364  1364 D BluetoothMap: Proxy object connected
09-08 17:56:36.033  3939  3950 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:56:36.033  1364  1364 D MapProfile: Bluetooth service connected
09-08 17:56:36.033  1364  1364 D BluetoothMap: getConnectedDevices()
09-08 17:56:36.034  4018  4018 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:56:36.034   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:36.034   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:56:36.035  4018  4018 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 17:56:36.035  1364  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 17:56:36.036  4018  4018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 17:56:36.038  3939  3949 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:36.038  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:36.038  1364  2229 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:36.038  1364  1364 D BluetoothInputDevice: Proxy object connected
09-08 17:56:36.038  1364  1364 D HidProfile: Bluetooth service connected
09-08 17:56:36.039  4018  4018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 17:56:36.039  1364  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:56:36.040  4018  4018 D ObexServerSockets: Succeed to create listening sockets 
09-08 17:56:36.040  4018  4018 D ObexServerSockets0: startAccept()
,09-08 17:56:36.040  4018  4018 D ObexServerSockets0: prepareForNewConnect()
09-08 17:56:36.041  3939  3950 D BluetoothMap: onBluetoothStateChange: up=true
09-08 17:56:36.041  4018  4018 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 17:56:36.041  4018  4018 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 17:56:36.042  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:36.043   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 17:56:36.046  4018  4018 D BluetoothMapService: onReceive
09-08 17:56:36.046  4018  4018 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 17:56:36.046  1364  1364 D BluetoothA2dp: Proxy object connected
09-08 17:56:36.046  4018  4018 D BluetoothMapService: STATE_ON
09-08 17:56:36.046   873   873 D BluetoothA2dp: Proxy object connected
09-08 17:56:36.047  4018  4227 D ObexServerSockets0: Accepting socket connection...
09-08 17:56:36.048  4018  4228 D ObexServerSockets0: Accepting socket connection...
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:36.048  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:36.051  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:36.052  3939  3939 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 17:56:36.055  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:36.057  3939  3939 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-08 17:56:36.058  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:36.065  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:56:36.067  4018  4018 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:56:36.067  4018  4018 D ObexServerSockets0: prepareForNewConnect()
,09-08 17:56:36.071  3939  3939 D BluetoothA2dp: Proxy object connected
,09-08 17:56:36.076  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:36.081  1364  1364 D BluetoothPbap: Proxy object connected
09-08 17:56:36.082  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-08 17:56:36.082  3939  3939 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:56:36.084  3939  3939 D BluetoothPbap: Proxy object connected
09-08 17:56:36.084  3939  3939 D PbapServerProfile: Bluetooth service connected
,09-08 17:56:36.094  4018  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:56:36.106  4018  4237 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:56:36.108  4018  4237 I BtOppRfcommListener: Accept thread started.
,09-08 17:56:36.128   873   873 D BluetoothHeadset: Proxy object connected
09-08 17:56:36.128  1933  1945 D BluetoothHeadset: Proxy object connected
,09-08 17:56:36.129   873   873 D BluetoothHeadset: Proxy object connected
09-08 17:56:36.129  1364  1384 D BluetoothHeadset: Proxy object connected
09-08 17:56:36.129  1364  1364 D HeadsetProfile: Bluetooth service connected
09-08 17:56:36.129   873   873 D BluetoothHeadset: Proxy object connected
,09-08 17:56:36.131   873   890 D BluetoothHeadset: Proxy object connected
,09-08 17:56:36.134   873   890 D BluetoothHeadset: Proxy object connected
,09-08 17:56:36.140  1364  2229 D BluetoothHeadset: Proxy object connected
09-08 17:56:36.140  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-08 17:56:36.162  3939  3950 D BluetoothHeadset: Proxy object connected
09-08 17:56:36.163  3939  3939 D HeadsetProfile: Bluetooth service connected
,09-08 17:56:38.203  1522  1522 I ConfigService: onDestroy
,09-08 17:56:39.563  4018  4200 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 17:56:39.564  4018  4200 D BluetoothAdapterProperties: Setting state to 13
09-08 17:56:39.564  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 17:56:39.567  4018  4200 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 17:56:39.573  4018  4200 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:56:39.580  4018  4018 D BluetoothMapService: onReceive
,09-08 17:56:39.580  4018  4018 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 17:56:39.581  4018  4018 D BluetoothMapService: STATE_TURNING_OFF
,09-08 17:56:39.581  4018  4018 D BluetoothMapService: MAP Service closeService in
09-08 17:56:39.582  4018  4018 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 17:56:39.582  4018  4018 D ObexServerSockets0: shutdown(block = true)
09-08 17:56:39.583  4018  4227 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 17:56:39.584  4018  4204 D BluetoothAdapterProperties: Scan Mode:20
,09-08 17:56:39.585  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 17:56:39.588  4018  4018 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:56:39.588  4018  4228 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 17:56:39.589  4018  4214 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 17:56:39.589  4018  4018 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:56:39.589  4018  4018 I BtOppRfcommListener: stopping Accept Thread
09-08 17:56:39.589  4018  4237 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 17:56:39.590  4018  4237 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 17:56:39.592  4018  4018 D HeadsetService: Received stop request...Stopping profile...
09-08 17:56:39.592  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:39.593  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:39.594   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:39.595  1933  1951 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:39.595   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:39.596  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:39.595  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:39.596  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:39.596  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:56:39.596  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:39.596  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:39.597  3939  3949 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:39.598  1364  2229 D BluetoothHeadset: Proxy object disconnected
,09-08 17:56:39.598   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 17:56:39.599  4018  4018 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 17:56:39.599  4018  4018 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 17:56:39.600  4018  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:39.600  4018  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:39.600  4018  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:39.601  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 17:56:39.601  4018  4018 D A2dpService: Received stop request...Stopping profile...
,09-08 17:56:39.601  4018  4204 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 17:56:39.601  4018  4222 D A2dpStateMachine: Exit Disconnected: -1
09-08 17:56:39.603  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:39.603  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:39.603  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:39.605   873   873 D BluetoothA2dp: Proxy object disconnected
09-08 17:56:39.606  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-08 17:56:39.608  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-08 17:56:39.608  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:39.608  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:39.608  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:39.608  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:56:39.608  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:39.609  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:39.609  4018  4018 D HidService: Received stop request...Stopping profile...
09-08 17:56:39.609  4018  4018 D HidService: Stopping Bluetooth HidService
09-08 17:56:39.613  3939  3939 D HeadsetProfile: Bluetooth service disconnected
09-08 17:56:39.613  3939  3939 D BluetoothA2dp: Proxy object disconnected
09-08 17:56:39.613  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:39.613  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:56:39.614  3878  3878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:56:39.614  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:39.616  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:39.618  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:39.619  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-08 17:56:39.619  1364  1364 D HidProfile: Bluetooth service disconnected
,09-08 17:56:39.619  4018  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:39.619  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:39.619  4018  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:39.619  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:39.619  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:39.619  4018  4212 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:56:39.619  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:39.619  4018  4212 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 17:56:39.619  4018  4212 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:56:39.619  4018  4212 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 17:56:39.620  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 17:56:39.620  4018  4018 D HealthService: Received stop request...Stopping profile...
09-08 17:56:39.621  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:39.623  4018  4018 D PanService: Received stop request...Stopping profile...
09-08 17:56:39.623  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:39.624  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 17:56:39.624  1364  1364 D PanProfile: Bluetooth service disconnected
09-08 17:56:39.625  4018  4018 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 17:56:39.625  4018  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:56:39.625  4018  4018 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 17:56:39.625  4018  4018 D BluetoothMapService: Received stop request...Stopping profile...
09-08 17:56:39.625  4018  4018 D BluetoothMapService: stop()
09-08 17:56:39.626  4018  4018 D BluetoothMapAppObserver: deinitObservers()
09-08 17:56:39.626  4018  4018 D BluetoothMapAppObserver: removeReceiver()
,09-08 17:56:39.628  1364  1364 D BluetoothMap: Proxy object disconnected
09-08 17:56:39.628  1364  1364 D MapProfile: Bluetooth service disconnected
09-08 17:56:39.629  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:39.629  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:39.629  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:39.629  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:39.629  4018  4018 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 17:56:39.629  4018  4204 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 17:56:39.629  3939  3939 D DockEventReceiver: finishStartingService: stopping service
09-08 17:56:39.630  4018  4018 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 17:56:39.631  3939  3939 D BluetoothInputDevice: Proxy object disconnected
09-08 17:56:39.631  3939  3939 D HidProfile: Bluetooth service disconnected
09-08 17:56:39.631  3939  3939 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 17:56:39.631  3939  3939 D PanProfile: Bluetooth service disconnected
09-08 17:56:39.632  3939  3939 D BluetoothMap: Proxy object disconnected
09-08 17:56:39.632  3939  3939 D MapProfile: Bluetooth service disconnected
,09-08 17:56:39.634  1364  1364 D BluetoothPbap: Proxy object disconnected
09-08 17:56:39.634  1364  1364 D PbapServerProfile: Bluetooth service disconnected
09-08 17:56:39.634  3939  3939 D BluetoothPbap: Proxy object disconnected
09-08 17:56:39.634  3939  3939 D PbapServerProfile: Bluetooth service disconnected
09-08 17:56:39.636  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:39.637  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:39.637  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:39.637  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:39.637  4018  4018 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 17:56:39.638  4018  4018 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 17:56:39.639  4018  4018 D BluetoothMapService: MAP Service closeService in
09-08 17:56:39.639  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-08 17:56:39.639  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:39.639  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:39.639  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:39.640  4018  4018 D BluetoothMapService: cleanup()
09-08 17:56:39.640  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 17:56:39.640  4018  4200 D BluetoothAdapterProperties: Setting state to 15
,09-08 17:56:39.640  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 17:56:39.640  4018  4018 D BluetoothMapService: MAP Service closeService in
,09-08 17:56:39.641  4018  4200 I BluetoothAdapterState: Entering BleOnState
09-08 17:56:39.644  3939  3950 D BluetoothPan: onBluetoothStateChange on: false
09-08 17:56:39.645  3939  3949 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:39.645   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:39.645  1933  2237 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:39.645  1364  1384 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 17:56:39.646  1364  2229 D BluetoothPan: onBluetoothStateChange on: false
09-08 17:56:39.646   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:39.647  1364  1378 D BluetoothMap: onBluetoothStateChange: up=false
09-08 17:56:39.647  3939  3950 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 17:56:39.650   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 17:56:39.650  3939  3949 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:56:39.651   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 17:56:39.651  1364  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 17:56:39.651  3939  3950 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 17:56:39.652  1364  2229 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:56:39.652  1364  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:56:39.653  3939  3949 D BluetoothMap: onBluetoothStateChange: up=false
09-08 17:56:39.654  4018  4200 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 17:56:39.654  4018  4200 D BluetoothAdapterProperties: Setting state to 16
09-08 17:56:39.654  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-08 17:56:39.654  4018  4200 D BluetoothAdapterProperties: onBleDisable
,09-08 17:56:39.656  4018  4200 I BluetoothAdapterState: Entering PendingCommandState
09-08 17:56:39.656  4018  4201 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 17:56:39.657  4018  4212 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 17:56:39.657  4018  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:56:39.657  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:39.658  4018  4204 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:56:39.658  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:39.660  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:39.661  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:56:39.662  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:39.663  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:39.664  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:39.667  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:39.671  3939  3939 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:56:39.861  4018  4204 I bt_hci  : shut_down
,09-08 17:56:39.862  4018  4208 D bt_hwcfg: hw_epilog_process
09-08 17:56:39.863  4018  4208 I bt_vendor: low_power_mode_cb
,09-08 17:56:39.888  4018  4208 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 17:56:39.888  4018  4208 I bt_vendor: epilog_cb
,09-08 17:56:39.889  4018  4208 I bt_hci  : epilog_finished_callback
,09-08 17:56:39.899  4018  4204 I bt_hci_h4: hal_close
,09-08 17:56:39.901  4018  4204 I bt_userial_vendor: device fd = 51 close
,09-08 17:56:40.028  4018  4201 D bt_stack_manager: event_shut_down_stack finished.
,09-08 17:56:40.029  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 17:56:40.036  4018  4018 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:56:40.036  4018  4200 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 17:56:40.037  4018  4018 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 17:56:40.038  4018  4018 D BtGatt.GattService: stop()
09-08 17:56:40.038  4018  4018 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 17:56:40.043  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:40.043  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-08 17:56:40.043  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:56:40.043  4018  4018 V BluetoothAdapterState: isBleTurningOff()=true
09-08 17:56:40.044  4018  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 17:56:40.045  4018  4200 D BluetoothAdapterProperties: Setting state to 10
09-08 17:56:40.045  4018  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 17:56:40.047  4018  4200 I BluetoothAdapterState: Entering OffState
09-08 17:56:40.048   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 17:56:40.073  4018  4018 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-08 17:56:40.073  4018  4018 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 17:56:40.074  4018  4018 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 17:56:40.075  4018  4201 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 17:56:40.078  4018  4201 D bt_stack_manager: event_clean_up_stack finished.
,09-08 17:56:40.080  4018  4018 I art     : System.exit called, status: 0
09-08 17:56:40.080  4018  4018 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 17:56:40.127   873  1917 I ActivityManager: Process com.android.bluetooth (pid 4018) has died
,09-08 17:56:44.560  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:56:44.561  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:44.565  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:56:44.566  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb2f37b removed from the list
09-08 17:56:44.566  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:56:44.567  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:44.567  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:56:44.570  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:56:44.570  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8ff1f1 added. We now have 4 listener(s)
,09-08 17:56:44.571  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:56:44.573  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:56:44.573  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8ff1f1 removed from the list
09-08 17:56:44.573  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:56:44.574  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:56:44.574  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:44.576  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:56:44.577  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@967a1d6 added. We now have 4 listener(s)
09-08 17:56:44.577  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:56:49.588  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:49.634   873   890 I ActivityManager: Start proc 4250:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 17:56:49.799  4250  4250 D AdapterServiceConfig: Adding HeadsetService
09-08 17:56:49.800  4250  4250 D AdapterServiceConfig: Adding A2dpService
09-08 17:56:49.800  4250  4250 D AdapterServiceConfig: Adding HidService
09-08 17:56:49.800  4250  4250 D AdapterServiceConfig: Adding HealthService
09-08 17:56:49.800  4250  4250 D AdapterServiceConfig: Adding PanService
09-08 17:56:49.800  4250  4250 D AdapterServiceConfig: Adding GattService
09-08 17:56:49.801  4250  4250 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 17:56:49.815  4250  4250 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 17:56:49.815   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b9a2bd:true
,09-08 17:56:49.821  4250  4250 I bt_bluedroid: init
,09-08 17:56:49.822  4250  4262 I BluetoothAdapterState: Entering OffState
,09-08 17:56:49.829  4250  4263 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 17:56:49.830  4250  4263 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 17:56:49.830  4250  4263 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 17:56:49.831  4250  4263 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 17:56:49.834  4250  4250 I bt_bluedroid: get_profile_interface socket
,09-08 17:56:49.836  4250  4250 I bt_bluedroid: get_profile_interface sdp
,09-08 17:56:49.838  4250  4266 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:56:49.847  4250  4261 I bt_bluedroid: config_hci_snoop_log
,09-08 17:56:49.847  4250  4266 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 17:56:49.850   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 17:56:49.865  4250  4262 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 17:56:49.866  4250  4262 D BluetoothAdapterProperties: Setting state to 14
09-08 17:56:49.866  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-08 17:56:49.871  4250  4262 D BluetoothBondStateMachine: make
,09-08 17:56:49.878  4250  4267 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 17:56:49.887  4250  4250 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 17:56:49.889  4250  4262 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:56:49.891  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:49.892  4250  4250 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:56:49.893  4250  4250 D BtGatt.GattService: Received start request. Starting profile...
,09-08 17:56:49.893  4250  4250 D BtGatt.GattService: start()
,09-08 17:56:49.893  4250  4250 I bt_bluedroid: get_profile_interface gatt
09-08 17:56:49.894  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:49.894  4250  4250 D BtGatt.AdvertiseManager: advertise manager created
,09-08 17:56:49.911  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:49.911  4250  4250 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:56:49.911  4250  4250 V BluetoothAdapterState: isBleTurningOn()=true
09-08 17:56:49.911  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:49.912  4250  4262 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 17:56:49.912  4250  4262 I bt_bluedroid: enable
09-08 17:56:49.912  4250  4263 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 17:56:49.913  4250  4263 I bt_hci  : start_up
,09-08 17:56:49.923  4250  4263 I bt_vendor: alloc value 0xb3a04189
09-08 17:56:49.923  4250  4263 I bt_vendor: init
09-08 17:56:49.923  4250  4263 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 17:56:49.923  4250  4263 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 17:56:50.029  4250  4263 D bt_hci  : start_up starting async portion
09-08 17:56:50.030  4250  4270 I bt_hci  : event_finish_startup
,09-08 17:56:50.030  4250  4270 I bt_hci_h4: hal_open
09-08 17:56:50.030  4250  4270 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 17:56:50.041  4250  4270 I bt_userial_vendor: device fd = 51 open
,09-08 17:56:50.073  4250  4270 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:56:50.104  4250  4270 D bt_hwcfg: Chipset BCM4354A2
,09-08 17:56:50.104  4250  4270 D bt_hwcfg: Target name = [BCM4354A2]
09-08 17:56:50.105  4250  4270 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 17:56:50.816  4250  4270 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 17:56:50.817  4250  4270 D bt_hwcfg: Settlement delay -- 100 ms
09-08 17:56:50.818  4250  4270 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 17:56:50.934  4250  4270 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:56:50.936  4250  4270 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 17:56:50.966  4250  4270 I bt_hwcfg: vendor lib fwcfg completed
,09-08 17:56:50.966  4250  4270 I bt_vendor: firmware callback
09-08 17:56:50.966  4250  4270 I bt_hci  : firmware_config_callback
,09-08 17:56:50.978  4250  4272 I bt_btu  : btu_task pending for preload complete event
,09-08 17:56:50.978  4250  4272 I bt_btu_task: Bluetooth chip preload is complete
09-08 17:56:50.979  4250  4272 I bt_btu  : btu_task received preload complete event
,09-08 17:56:50.990  4250  4272 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 17:56:50.990  4250  4272 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 17:56:50.991  4250  4272 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 17:56:50.991  4250  4272 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 17:56:50.991  4250  4272 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 17:56:50.992  4250  4272 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 17:56:50.992  4250  4272 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 17:56:50.992  4250  4272 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 17:56:50.992  4250  4272 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 17:56:50.993  4250  4272 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 17:56:50.993  4250  4272 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 17:56:50.993  4250  4272 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 17:56:50.993  4250  4272 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 17:56:50.994  4250  4272 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 17:56:50.994  4250  4272 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 17:56:51.131  4250  4272 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3981d9d
,09-08 17:56:51.132  4250  4272 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3981d9d 
,09-08 17:56:51.139  4250  4266 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 17:56:51.141  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:56:51.142  4250  4266 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:56:51.149  4250  4266 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 17:56:51.151  4250  4266 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:56:51.152  4250  4266 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 17:56:51.152  4250  4266 D bt_hci  : do_postload posting postload work item
09-08 17:56:51.152  4250  4270 I bt_hci  : event_postload
09-08 17:56:51.152  4250  4270 I bt_vendor: sco_config_cb
09-08 17:56:51.152  4250  4270 I bt_hci  : sco_config_callback postload finished.
09-08 17:56:51.153  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:51.155  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:51.156  4250  4266 D bt_bte_conf: Device ID record 1 : primary
09-08 17:56:51.156  4250  4266 D bt_bte_conf:   vendorId            = 000f
09-08 17:56:51.156  4250  4266 D bt_bte_conf:   vendorIdSource      = 0001
09-08 17:56:51.156  4250  4266 D bt_bte_conf:   product             = 1200
09-08 17:56:51.156  4250  4266 D bt_bte_conf:   version             = 1436
09-08 17:56:51.157  4250  4266 D bt_bte_conf:   clientExecutableURL = 
09-08 17:56:51.157  4250  4266 D bt_bte_conf:   serviceDescription  = 
09-08 17:56:51.157  4250  4266 D bt_bte_conf:   documentationURL    = 
09-08 17:56:51.157  4250  4266 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 17:56:51.157  4250  4270 I bt_vendor: low_power_mode_cb
09-08 17:56:51.158  4250  4263 D bt_stack_manager: event_start_up_stack finished
,09-08 17:56:51.158  4250  4262 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 17:56:51.159  4250  4262 D BluetoothAdapterProperties: Setting state to 15
09-08 17:56:51.159  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 17:56:51.160  4250  4262 I BluetoothAdapterState: Entering BleOnState
,09-08 17:56:51.164  4250  4262 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 17:56:51.165  4250  4262 D BluetoothAdapterProperties: Setting state to 11
,09-08 17:56:51.165  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 17:56:51.173  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:51.174  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:51.180  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:51.181  4250  4250 D HeadsetService: Received start request. Starting profile...
09-08 17:56:51.184  4250  4250 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 17:56:51.184  4250  4250 D HeadsetStateMachine: make
,09-08 17:56:51.192  4250  4262 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:56:51.196  4250  4250 D HeadsetStateMachine: max_hf_connections = 1
,09-08 17:56:51.196  4250  4250 I bt_bluedroid: get_profile_interface handsfree
09-08 17:56:51.196  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 17:56:51.197  4250  4266 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 17:56:51.202  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:51.203  4250  4250 D A2dpService: Received start request. Starting profile...
09-08 17:56:51.203  4250  4250 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 17:56:51.204  4250  4250 I bt_bluedroid: get_profile_interface avrcp
,09-08 17:56:51.210  4250  4250 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 17:56:51.210  4250  4250 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 17:56:51.210  4250  4250 D A2dpStateMachine: make
,09-08 17:56:51.214  4250  4250 I bt_bluedroid: get_profile_interface a2dp
,09-08 17:56:51.217  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 17:56:51.221  4250  4281 D A2dpStateMachine: Enter Disconnected: -2
,09-08 17:56:51.223  4250  4250 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 17:56:51.224  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:51.228  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:51.229  4250  4250 D HidService: Received start request. Starting profile...
,09-08 17:56:51.230  4250  4250 I bt_bluedroid: get_profile_interface hidhost
09-08 17:56:51.230  4250  4250 D HidService: setHidService(): set to: null
09-08 17:56:51.230  4250  4266 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39633e5
09-08 17:56:51.230  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 17:56:51.231  4250  4250 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 17:56:51.231  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:51.232  4250  4250 D HealthService: Received start request. Starting profile...
,09-08 17:56:51.236  4250  4250 I bt_bluedroid: get_profile_interface health
09-08 17:56:51.237  4250  4250 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 17:56:51.238  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
09-08 17:56:51.238  4250  4250 D PanService: Received start request. Starting profile...
09-08 17:56:51.238  4250  4250 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 17:56:51.239  4250  4250 I bt_bluedroid: get_profile_interface pan
09-08 17:56:51.239  4250  4266 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 17:56:51.244  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:56:51.246  4250  4250 D BluetoothMapService: Received start request. Starting profile...
09-08 17:56:51.246  4250  4250 D BluetoothMapService: start()
,09-08 17:56:51.249  4250  4250 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 17:56:51.250  4250  4250 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 17:56:51.250  4250  4250 D BluetoothMapAppObserver: createReceiver()
,09-08 17:56:51.252  4250  4250 D BluetoothMapAppObserver: initObservers()
09-08 17:56:51.252  4250  4250 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 17:56:51.259  4250  4278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 17:56:51.260  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:51.260  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:51.260  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:51.260  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:56:51.262  4250  4250 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:56:51.262  4250  4250 V BluetoothAdapterState: isTurningOn()=true
,09-08 17:56:51.262  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:51.262  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:51.264  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:56:51.265  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:56:51.265  4250  4262 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 17:56:51.265  4250  4262 D BluetoothAdapterProperties: ScanMode =  20
09-08 17:56:51.265  4250  4262 D BluetoothAdapterProperties: State =  11
,09-08 17:56:51.266  4250  4262 D BluetoothAdapterProperties: Setting state to 12
,09-08 17:56:51.266  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 17:56:51.268  3939  3949 D BluetoothPan: onBluetoothStateChange on: true
09-08 17:56:51.268  4250  4266 D BluetoothAdapterProperties: Scan Mode:21
09-08 17:56:51.268  4250  4266 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 17:56:51.270  3939  3950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:51.270  4250  4262 I BluetoothAdapterState: Entering OnState
09-08 17:56:51.271   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:51.271  1933  2237 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:51.272  1364  1378 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:51.272  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:51.273  1364  1384 D BluetoothPan: onBluetoothStateChange on: true
09-08 17:56:51.273  3939  3939 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 17:56:51.274  3939  3939 D PanProfile: Bluetooth service connected
,09-08 17:56:51.274  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:51.275  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 17:56:51.275   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:51.275  1364  1364 D PanProfile: Bluetooth service connected
09-08 17:56:51.276  1364  1378 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:51.277  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:51.278  3939  3949 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:56:51.278  1364  1364 D BluetoothMap: Proxy object connected
09-08 17:56:51.278  1364  1364 D MapProfile: Bluetooth service connected
09-08 17:56:51.278  1364  1364 D BluetoothMap: getConnectedDevices()
09-08 17:56:51.278  4250  4250 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:56:51.279  4250  4250 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 17:56:51.280   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 17:56:51.280  3939  3950 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:56:51.280  4250  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 17:56:51.280  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:51.282   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:56:51.282  1364  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 17:56:51.283  4250  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 17:56:51.284  3939  4286 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 17:56:51.284  4250  4250 D ObexServerSockets: Succeed to create listening sockets 
09-08 17:56:51.284  4250  4250 D ObexServerSockets0: startAccept()
,09-08 17:56:51.284  4250  4250 D ObexServerSockets0: prepareForNewConnect()
09-08 17:56:51.285  1364  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:56:51.286  1364  2229 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 17:56:51.287  4250  4250 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 17:56:51.287  4250  4250 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 17:56:51.288  4250  4287 D ObexServerSockets0: Accepting socket connection...
09-08 17:56:51.288  3939  3949 D BluetoothMap: onBluetoothStateChange: up=true
09-08 17:56:51.288   873   873 D BluetoothA2dp: Proxy object connected
09-08 17:56:51.288  1364  1364 D BluetoothA2dp: Proxy object connected
09-08 17:56:51.289  4250  4288 D ObexServerSockets0: Accepting socket connection...
09-08 17:56:51.290  3939  3939 D BluetoothA2dp: Proxy object connected
09-08 17:56:51.291  1364  1364 D BluetoothInputDevice: Proxy object connected
09-08 17:56:51.291  1364  1364 D HidProfile: Bluetooth service connected
,09-08 17:56:51.292  4250  4250 D BluetoothMapService: onReceive
,09-08 17:56:51.292  4250  4250 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 17:56:51.292  4250  4250 D BluetoothMapService: STATE_ON
09-08 17:56:51.293   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 17:56:51.293  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:56:51.294  3939  3939 D BluetoothInputDevice: Proxy object connected
09-08 17:56:51.294  3939  3939 D HidProfile: Bluetooth service connected
,09-08 17:56:51.296  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:51.297  3939  3939 D BluetoothMap: Proxy object connected
09-08 17:56:51.297  3939  3939 D MapProfile: Bluetooth service connected
,09-08 17:56:51.297  3939  3939 D BluetoothMap: getConnectedDevices()
,09-08 17:56:51.303  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:56:51.309  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:56:51.310  3939  3939 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:56:51.314  3939  3939 D BluetoothPbap: Proxy object connected
09-08 17:56:51.314  3939  3939 D PbapServerProfile: Bluetooth service connected
09-08 17:56:51.314  4250  4250 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:56:51.314  4250  4250 D ObexServerSockets0: prepareForNewConnect()
,09-08 17:56:51.318  1364  1364 D BluetoothPbap: Proxy object connected
09-08 17:56:51.318  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-08 17:56:51.324  4250  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:56:51.337  4250  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:56:51.338  4250  4298 I BtOppRfcommListener: Accept thread started.
,09-08 17:56:51.373   873   873 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.375   873   890 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.374  1933  2231 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.376   873   873 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.377  3939  4286 D BluetoothHeadset: Proxy object connected
09-08 17:56:51.378  3939  3939 D HeadsetProfile: Bluetooth service connected
,09-08 17:56:51.379  1364  2229 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.380  1364  1364 D HeadsetProfile: Bluetooth service connected
09-08 17:56:51.380   873   890 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.381   873   873 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.387  1364  1384 D BluetoothHeadset: Proxy object connected
,09-08 17:56:51.387  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:54.610  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:54.616  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:54.617  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:56:54.618  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@967a1d6 removed from the list
09-08 17:56:54.619  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:56:54.619  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:56:54.621  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:56:54.626  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:56:54.627  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f34c57 added. We now have 4 listener(s)
09-08 17:56:54.627  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:56:54.633   873  2114 D WifiService: setWifiEnabled: false pid=3878, uid=10000
,09-08 17:56:54.633   873  2114 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:56:59.646  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:56:59.647   873   883 D WifiService: setWifiEnabled: true pid=3878, uid=10000
09-08 17:56:59.648   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:56:59.666   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:59.679  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:59.682   873  1307 D WifiConfigStore: loaded 0 passpoint configs
09-08 17:56:59.683  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:56:59.684   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 17:56:59.684   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 17:56:59.688   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 17:56:59.689   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 17:56:59.690   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 17:56:59.691   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:56:59.692  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:56:59.698  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:56:59.707   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:56:59.707   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 17:56:59.710   372   871 D CommandListener: Setting iface cfg
,09-08 17:56:59.758   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 17:56:59.759   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 17:56:59.765   873  1307 E native  : do suspend true
,09-08 17:56:59.768   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 17:56:59.780   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 17:56:59.796   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:57:01.112   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:57:01.281   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.62 rxSuccessRate=19.69 delta 1000 -> 994
,09-08 17:57:01.282   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 17:57:01.282   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:57:01.300   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 17:57:01.374   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 17:57:01.380  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 17:57:01.820  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 17:57:01.863  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 17:57:01.865  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 17:57:01.869   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:57:01.881   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:57:01.882   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 17:57:01.882   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 17:57:01.908   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:57:01.927   372   871 D CommandListener: Setting iface cfg
09-08 17:57:01.929   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 17:57:01.936   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 17:57:01.949   873  4308 D DhcpClient: Receive thread started
,09-08 17:57:02.047   873  1307 E native  : do suspend false
,09-08 17:57:02.072   873  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 17:57:02.114   873  4308 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-08 17:57:02.115   873  1868 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-08 17:57:02.119   873  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 17:57:02.161   873  4308 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 17:57:02.163   873  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 17:57:02.169   372   871 D CommandListener: Setting iface cfg
,09-08 17:57:02.181   873  1868 D DhcpClient: Scheduling renewal in 86399s
,09-08 17:57:02.182   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 17:57:02.188   873  1307 E native  : do suspend true
,09-08 17:57:02.220   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 17:57:02.225   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 17:57:02.227   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 17:57:02.231   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 17:57:02.238   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 17:57:02.289   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 17:57:02.289   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 17:57:02.293   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 17:57:02.295   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 17:57:02.297   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 17:57:02.315   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 17:57:02.323   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 17:57:02.324   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 17:57:02.324   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 17:57:02.324   873  1309 D ConnectivityService:    accepting network in place of null
09-08 17:57:02.324   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 17:57:02.325   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:57:02.326   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:57:02.343   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379972, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:57:02.356   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:57:02.389   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:57:02.398   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 17:57:02.399   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:57:02.408   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 17:57:02.409   873   890 D Tethering: MasterInitialState.processMessage what=3
09-08 17:57:02.413   873  4306 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:02.427  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:57:02.430  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:02.436  3878  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:57:02.439  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 17:57:02.439  3878  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:02.446  1741  1741 D SystemUpdateService: onCreate
09-08 17:57:02.451  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:57:02.473  1741  4317 I SystemUpdateService: active receiver: enabled
,09-08 17:57:02.478  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-08 17:57:02.479   873  4306 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 15:57:02 GMT], X-Android-Received-Millis=[1473350222479], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473350222452]}
,09-08 17:57:02.483   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 17:57:02.483   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-08 17:57:02.484   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 17:57:02.485   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 17:57:02.490  1741  2434 I iu.UploadsManager: num queued entries: 0
,09-08 17:57:02.490  1741  2434 I iu.UploadsManager: num updated entries: 0
,09-08 17:57:02.493  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:57:02.494  1741  2434 I iu.SyncManager: NEXT; no task
,09-08 17:57:02.499  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:57:02.499  1741  4317 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:57:02.511  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:57:02.515  1741  4319 I MDM     : [186] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 17:57:02.515  1741  4319 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 17:57:02.521  1741  4319 V GoogleAuthProtoRequest: [186] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 17:57:02.522  1741  4317 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 17:57:02.522  1741  4317 I SystemUpdateService: now status is 0 (complete)
09-08 17:57:02.522  1741  4317 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:57:02.522  1741  4317 I SystemUpdateService: file has been verified
,09-08 17:57:02.526  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:57:02.527  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:57:02.529  4032  4032 D SprintDMHelper: simOperator: 
09-08 17:57:02.529  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:57:02.530  1741  4317 I SystemUpdateService: OTA package size = 12249756
,09-08 17:57:02.539  1741  4317 I SystemUpdateService: showing system update notification
,09-08 17:57:02.604  1741  1741 D SystemUpdateService: onDestroy
,09-08 17:57:02.615  1522  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 17:57:02.615  1522  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 17:57:02.615  1522  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:57:02.615  1522  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:57:02.631  1741  4319 E MDM     : [186] SitrepService.a: Error sending sitrep.
,09-08 17:57:02.680  3990  4323 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 17:57:03.398   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:04.677  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:57:04.684  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:04.685  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:04.686  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f34c57 removed from the list
09-08 17:57:04.686  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:57:04.686  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:04.686  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:04.699  3878  4329 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 17:57:04.699  3878  4329 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 17:57:07.706  3878  4330 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 17:57:07.707  3878  4329 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-08 17:57:07.708  3878  4330 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 17:57:07.708  3878  4329 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 17:57:07.710  3878  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:57:07.711  3878  4329 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:57:07.712  3878  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:57:07.714  3878  4329 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:57:07.716  3878  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
09-08 17:57:07.716  3878  4330 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 17:57:07.719  3878  4333 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
09-08 17:57:07.720  3878  4329 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 17:57:07.723  3878  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
,09-08 17:57:07.727  3878  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
,09-08 17:57:07.725  3878  4334 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
09-08 17:57:07.727  3878  4334 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 17:57:07.728  3878  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 17:57:07.729  3878  4335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
09-08 17:57:07.729  3878  4335 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 17:57:07.729  3878  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 17:57:10.333   873  1309 D ConnectivityService: handlePromptUnvalidated 102
,09-08 17:57:10.705  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 17:57:10.707  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 17:57:10.716  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@62b4199 Bundle[{}]
09-08 17:57:10.716  3878  3924 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 17:57:10.716  3878  3924 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 17:57:10.717  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 17:57:10.718  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 17:57:10.718  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 17:57:10.719  3878  3924 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 17:57:10.723  3878  3924 I System.out: Running OutgoingSocketThread
,09-08 17:57:10.726  3878  4336 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 17:57:10.727  3878  4336 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 17:57:13.736  3878  4337 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 17:57:13.736  3878  4337 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 17:57:13.737  3878  4337 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:57:13.737  3878  4336 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-08 17:57:13.737  3878  4336 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 17:57:13.738  3878  4337 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:57:13.738  3878  4336 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:57:13.742  3878  4339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
09-08 17:57:13.745  3878  4336 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:57:13.746  3878  4337 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 17:57:13.748  3878  4336 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 17:57:13.754  3878  4340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
,09-08 17:57:13.758  3878  4342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
,09-08 17:57:13.760  3878  4342 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
09-08 17:57:13.760  3878  4341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
09-08 17:57:13.760  3878  4342 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 17:57:13.761  3878  4342 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 17:57:13.761  3878  4341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
09-08 17:57:13.762  3878  4341 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 17:57:13.762  3878  4341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 17:57:16.739  3878  3924 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
09-08 17:57:16.741  3878  3924 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 17:57:16.741  3878  3924 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-08 17:57:16.747  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:57:16.747  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c243344 added. We now have 3 listener(s)
,09-08 17:57:16.749  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:57:16.749  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:57:16.749  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:57:16.749  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:57:16.749  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0bc2d added. We now have 4 listener(s)
09-08 17:57:16.750  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:57:16.750  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:57:16.754  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:16.764  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:57:16.768  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:16.769  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:57:16.769  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:57:16.769  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:57:16.769  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:57:16.769  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:16.769  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:16.770  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:57:16.770  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:57:16.770  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c243344 removed from the list
09-08 17:57:16.770  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:16.770  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0bc2d removed from the list
,09-08 17:57:16.776  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:16.776  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:57:16.776  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:16.777  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:16.778  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:16.782  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:16.782  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:16.784  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:57:16.784  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:16.784  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0bc2d not in the list
09-08 17:57:16.785  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:16.785  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:16.788  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:57:16.789  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:16.789  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:57:16.789  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0bc2d not in the list
09-08 17:57:16.789  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:16.789  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:16.790  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:16.790  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c243344 not in the list
,09-08 17:57:16.792  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:57:16.792  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7656f3 added. We now have 3 listener(s)
,09-08 17:57:16.798  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:57:16.798  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:57:16.799  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:57:16.799  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:57:16.799  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d33fb0 added. We now have 4 listener(s)
,09-08 17:57:16.800  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:57:16.801  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:57:16.807  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:16.821  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:57:16.829  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:16.829  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:57:16.830  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:57:16.831  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 17:57:16.831  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:57:16.831  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:57:16.831  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 17:57:16.837  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:57:16.840  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 17:57:16.840  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:57:16.845  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:57:16.852  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:57:16.854  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 17:57:16.855  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:57:16.867  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 17:57:16.867  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 17:57:16.867  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 17:57:16.870  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:57:16.879  4250  4261 D BtGatt.GattService: registerClient() - UUID=ae43ac5f-a6e0-4476-99a2-d2d85474b973
,09-08 17:57:16.882  4250  4266 D BtGatt.GattService: onClientRegistered() - UUID=ae43ac5f-a6e0-4476-99a2-d2d85474b973, clientIf=5
09-08 17:57:16.883  3878  3927 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 17:57:16.887  4250  4290 D BtGatt.GattService: start scan with filters
,09-08 17:57:16.899  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 17:57:16.899  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:57:16.899  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 17:57:16.899  4250  4269 D BtGatt.ScanManager: handling starting scan
09-08 17:57:16.900  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:57:16.906  4250  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f16b89d
,09-08 17:57:16.911  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:57:16.911  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:57:16.911  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:57:16.917  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:57:16.922  4250  4266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 17:57:16.922  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:57:16.923  4250  4269 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 17:57:16.928  3878  3924 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 17:57:16.929  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:57:16.929  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:57:16.929  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:16.929  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 17:57:16.930  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:57:16.930  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:57:16.930  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:57:16.930  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 17:57:16.932  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 17:57:16.933  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 17:57:16.936  3878  3924 D BluetoothAdapter: STATE_ON
09-08 17:57:16.936  4250  4290 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:57:16.945  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 17:57:16.945  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:57:16.945  4250  4269 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:57:16.945  4250  4269 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 17:57:16.946  4250  4289 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:57:16.948  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 17:57:16.948  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 17:57:16.949  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 17:57:16.949  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:57:16.949  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 17:57:16.953  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:57:16.954  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:57:16.954  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:57:16.954  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 17:57:16.955  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:57:16.959  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:57:16.959  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:57:16.959  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:57:16.960  4250  4266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 17:57:16.961  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:16.968  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 17:57:16.968  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:16.981  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 17:57:16.981  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:16.982  4250  4269 D BtGatt.ScanManager: stopping BLe Batch
,09-08 17:57:16.994  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:57:16.994  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:57:16.995  4250  4269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:57:17.010  4250  4266 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 17:57:17.010  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:17.461  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-08 17:57:17.461  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:57:17.462  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:57:19.960  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:57:19.961  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:57:19.961  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:57:19.962  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:19.962  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:57:19.962  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:57:19.963  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:57:19.963  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7656f3 removed from the list
09-08 17:57:19.963  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:57:19.964  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d33fb0 removed from the list
09-08 17:57:19.964  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:57:19.964  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:19.966  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:57:19.966  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:19.970  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:19.971  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:57:19.971  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:57:19.971  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d33fb0 not in the list
09-08 17:57:19.972  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:19.972  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:19.976  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:57:19.977  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:19.977  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:57:19.978  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d33fb0 not in the list
09-08 17:57:19.978  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:57:19.978  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:19.978  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:19.979  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7656f3 not in the list
,09-08 17:57:19.981  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:57:19.982  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89a43e5 added. We now have 3 listener(s)
,09-08 17:57:19.989  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:57:19.989  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 17:57:19.990  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:57:19.990  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:57:19.990  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cdeba added. We now have 4 listener(s)
,09-08 17:57:19.991  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:57:19.992  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:57:19.999  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:20.010  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:57:20.014  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:20.014  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:57:20.015  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 17:57:20.016  3878  3924 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 17:57:20.016  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-08 17:57:20.017  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 17:57:20.017  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 17:57:20.017  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 17:57:20.017  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:57:20.018  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 17:57:20.018  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 17:57:20.018  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 17:57:20.019  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 17:57:20.019  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 17:57:20.019  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:57:20.019  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 17:57:20.019  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:20.022  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 17:57:20.022  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:57:20.029  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 17:57:20.029  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:20.030  3878  3878 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 17:57:20.031  3878  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:57:20.032  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 17:57:20.032  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:57:20.034  3878  4344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 17:57:20.037  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 17:57:20.038  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:57:20.038  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-08 17:57:20.039  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 17:57:20.040  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 17:57:20.040  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 17:57:20.040  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:57:20.044  4250  4289 D BtGatt.GattService: registerClient() - UUID=5d26c394-38b9-4528-92ac-ee81c50c7b06
,09-08 17:57:20.044  4250  4266 D BtGatt.GattService: onClientRegistered() - UUID=5d26c394-38b9-4528-92ac-ee81c50c7b06, clientIf=5
09-08 17:57:20.045  3878  3888 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 17:57:20.047  4250  4268 D BtGatt.AdvertiseManager: message : 0
,09-08 17:57:20.051  4250  4268 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 17:57:20.060  4250  4266 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 17:57:20.071  4250  4266 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 17:57:20.074  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 17:57:20.074  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 17:57:20.076  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:57:20.080  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 17:57:20.081  3878  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 17:57:20.082  3878  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 17:57:20.083  3878  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 17:57:20.084  3878  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 17:57:20.085  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 17:57:20.085  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 17:57:20.089  3878  3878 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 17:57:20.089  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 17:57:20.591  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 17:57:20.591  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 17:57:20.591  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:57:23.086  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:57:23.087  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-08 17:57:23.088  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 17:57:23.088  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 17:57:23.088  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 17:57:23.088  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 17:57:23.090  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 17:57:23.090  3878  4344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-08 17:57:23.091  3878  4344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 17:57:23.091  3878  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 17:57:23.091  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:57:23.091  3878  3878 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 17:57:23.092  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:57:23.091  3878  4344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 17:57:23.092  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 17:57:23.092  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:57:23.093  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:57:23.095  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:57:23.095  3878  3924 D BluetoothLeScanner: could not find callback wrapper
09-08 17:57:23.096  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:57:23.096  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 17:57:23.098  4250  4268 D BtGatt.AdvertiseManager: message : 1
09-08 17:57:23.100  4250  4268 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 17:57:23.109  4250  4266 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 17:57:23.110  4250  4266 D BtGatt.GattService: Client app is not null!
,09-08 17:57:23.112  4250  4279 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:57:23.113  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 17:57:23.114  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 17:57:23.114  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 17:57:23.114  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 17:57:23.115  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 17:57:23.118  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:57:23.119  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:57:23.119  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 17:57:23.128  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:57:23.131  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:57:23.131  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:57:23.131  3878  3878 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 17:57:23.132  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:57:23.132  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:57:23.132  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:57:23.133  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:57:23.133  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:23.133  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:57:23.133  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:57:23.134  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89a43e5 removed from the list
,09-08 17:57:23.134  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:23.134  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cdeba removed from the list
09-08 17:57:23.135  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:57:23.135  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:23.136  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:23.136  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:23.137  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:23.138  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:57:23.138  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:23.138  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cdeba not in the list
09-08 17:57:23.138  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:57:23.138  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:23.139  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:57:23.139  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:23.139  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:23.139  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cdeba not in the list
09-08 17:57:23.139  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:23.139  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:23.139  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:23.140  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89a43e5 not in the list
09-08 17:57:23.140  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:57:23.140  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@509f947 added. We now have 3 listener(s)
,09-08 17:57:23.142  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:57:23.142  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:57:23.142  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:57:23.143  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:57:23.143  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31cf574 added. We now have 4 listener(s)
09-08 17:57:23.143  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:57:23.143  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 17:57:23.146  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:23.152  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:57:23.154  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:23.154  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:57:23.155  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:57:23.155  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 17:57:23.155  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 17:57:23.155  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:57:23.155  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 17:57:23.158  3878  3924 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 17:57:23.158  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:23.158  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:57:23.162  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:57:23.163  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 17:57:23.163  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 17:57:23.163  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:57:23.167  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 17:57:23.167  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:57:23.167  3878  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 17:57:23.168  3878  3924 D BluetoothAdapter: STATE_ON
,09-08 17:57:23.170  4250  4279 D BtGatt.GattService: registerClient() - UUID=42ca7270-ccd7-4674-acaa-96be51ebf4a1
09-08 17:57:23.171  4250  4266 D BtGatt.GattService: onClientRegistered() - UUID=42ca7270-ccd7-4674-acaa-96be51ebf4a1, clientIf=5
,09-08 17:57:23.172  3878  3927 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 17:57:23.172  4250  4290 D BtGatt.GattService: start scan with filters
,09-08 17:57:23.175  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 17:57:23.175  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:57:23.175  4250  4269 D BtGatt.ScanManager: handling starting scan
09-08 17:57:23.175  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 17:57:23.175  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:57:23.179  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:57:23.180  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:57:23.180  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 17:57:23.182  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:57:23.191  4250  4266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 17:57:23.191  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:57:23.192  4250  4269 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 17:57:23.206  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 17:57:23.206  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:57:23.206  4250  4269 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:57:23.206  4250  4269 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 17:57:23.222  4250  4266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 17:57:23.222  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:23.232  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:57:23.232  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:23.634  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:57:23.681  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 17:57:23.681  3878  3878 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:57:23.681  3878  3878 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:57:24.740  4250  4250 D BtGatt.ScanManager: awakened up at time 402369
,09-08 17:57:24.743  4250  4269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:57:24.783  4250  4266 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-08 17:57:24.783  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:24.784  4250  4266 D BtGatt.GattService: current time is 402413457180
09-08 17:57:24.786  4250  4266 D BtGatt.GattService: Batch record : [-99, 2, 46, 88, -40, 68, 1, -128, -35, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 85, -113, -37, 31, -33, 8, 0, -128, -107, 6, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0, 37, -47, 14, -113, 116, -46, 1, -128, -96, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 17:57:24.791  4250  4266 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-08 17:57:24.792  4250  4266 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
09-08 17:57:24.792  4250  4266 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 17:57:24.792  4250  4266 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 17:57:24.793  4250  4266 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:57:24.793  4250  4266 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:57:24.793  4250  4266 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 17:57:24.799  3878  3878 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,09-08 17:57:24.801  3878  3878 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-08 17:57:26.193  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:57:26.194  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:57:26.194  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:57:26.195  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.195  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 17:57:26.195  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:57:26.195  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:57:26.196  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:57:26.196  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:57:26.196  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:57:26.197  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 17:57:26.199  3878  3924 D BluetoothAdapter: STATE_ON
09-08 17:57:26.201  4250  4290 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:57:26.204  4250  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:57:26.205  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:57:26.205  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 17:57:26.205  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:57:26.206  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:57:26.206  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 17:57:26.210  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:57:26.211  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 17:57:26.213  3878  3924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:57:26.214  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 17:57:26.219  4250  4250 D BtGatt.ScanManager: awakened up at time 403848
,09-08 17:57:26.221  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:57:26.221  3878  3924 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-08 17:57:26.225  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:26.225  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:57:26.225  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.225  3878  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:57:26.225  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:57:26.226  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:57:26.226  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@509f947 removed from the list
,09-08 17:57:26.226  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:26.226  3878  3878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:57:26.227  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31cf574 removed from the list
09-08 17:57:26.227  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:57:26.228  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:26.229  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.230  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:26.233  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:26.233  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:57:26.233  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 17:57:26.234  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:26.234  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31cf574 not in the list
09-08 17:57:26.234  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:57:26.234  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:57:26.234  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:26.235  4250  4269 D BtGatt.ScanManager: stopping BLe Batch
09-08 17:57:26.237  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:57:26.238  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:26.238  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:26.238  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31cf574 not in the list
,09-08 17:57:26.238  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:26.239  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.239  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:26.239  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@509f947 not in the list
09-08 17:57:26.243  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 17:57:26.243  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c64465e added. We now have 3 listener(s)
09-08 17:57:26.246  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:57:26.247  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:57:26.247  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:57:26.247  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:57:26.247  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed6ca3f added. We now have 4 listener(s)
09-08 17:57:26.247  3878  3924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:57:26.248  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:57:26.250  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:57:26.251  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 17:57:26.251  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:26.252  4250  4269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:57:26.256  3878  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:57:26.258  3878  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:57:26.258  3878  3924 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:57:26.258  3878  3924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:57:26.259  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:57:26.259  3878  3924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:57:26.259  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:26.259  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.259  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:57:26.259  3878  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:57:26.259  3878  3924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c64465e removed from the list
09-08 17:57:26.259  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:26.259  3878  3924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed6ca3f removed from the list
09-08 17:57:26.259  4250  4266 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 17:57:26.259  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:57:26.261  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:26.261  3878  3924 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:57:26.261  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:26.262  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:57:26.262  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:57:26.263  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:57:26.263  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:57:26.263  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:26.263  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed6ca3f not in the list
09-08 17:57:26.263  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.263  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:26.264  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:57:26.264  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:57:26.265  3878  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:57:26.265  3878  3924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed6ca3f not in the list
09-08 17:57:26.265  3878  3924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:57:26.265  3878  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:57:26.265  3878  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:57:26.265  3878  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:57:26.265  3878  3924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c64465e not in the list
,09-08 17:57:26.266  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 17:57:26.266  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 17:57:26.266  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 17:57:26.266  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:57:26.266  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 17:57:26.267  3878  3924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:57:26.729  3878  3878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:57:28.283  3878  4347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-08 17:57:30.280  3878  3924 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 459
,09-08 17:57:30.280  3878  3924 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 459, name: My test thread name)
,09-08 17:57:30.287  3878  4348 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-08 17:57:30.288  3878  4348 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
09-08 17:57:30.288  3878  4348 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 17:57:30.292  3878  3924 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:57:30.302  3878  4349 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,09-08 17:57:30.303  3878  4349 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 464, thread name: My test thread name): Test exception.
09-08 17:57:30.303  3878  4349 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 17:57:30.310  3878  3924 I jxcore-log: Total number of executed tests:  82
09-08 17:57:30.310  3878  3924 I jxcore-log: 
,09-08 17:57:30.311  3878  3924 I jxcore-log: Number of passed tests:  82
09-08 17:57:30.311  3878  3924 I jxcore-log: 
09-08 17:57:30.312  3878  3924 I jxcore-log: Number of failed tests:  0
09-08 17:57:30.312  3878  3924 I jxcore-log: 
09-08 17:57:30.313  3878  3924 I jxcore-log: Number of ignored tests:  0
09-08 17:57:30.313  3878  3924 I jxcore-log: 
,09-08 17:57:30.313  3878  3924 I jxcore-log: Total duration:  101519
09-08 17:57:30.313  3878  3924 I jxcore-log: 
,09-08 17:57:30.323  3878  3924 I jxcore-log: Unit Test app is loaded
09-08 17:57:30.323  3878  3924 I jxcore-log: 
,09-08 17:57:30.331  3878  4347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-08 17:57:30.350  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.350  3878  3924 I jxcore-log: 
,09-08 17:57:30.355  3878  3878 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 17:57:30.361  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.361  3878  3924 I jxcore-log: 
,09-08 17:57:30.362  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.362  3878  3924 I jxcore-log: 
,09-08 17:57:30.363  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.363  3878  3924 I jxcore-log: 
,09-08 17:57:30.364  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 17:57:30.364  3878  3924 I jxcore-log: 
,09-08 17:57:30.366  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:57:30.366  3878  3924 I jxcore-log: 
09-08 17:57:30.368  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.368  3878  3924 I jxcore-log: 
,09-08 17:57:30.372  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.372  3878  3924 I jxcore-log: 
,09-08 17:57:30.373  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 17:57:30.373  3878  3924 I jxcore-log: 
09-08 17:57:30.374  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:57:30.374  3878  3924 I jxcore-log: 
,09-08 17:57:30.375  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:57:30.375  3878  3924 I jxcore-log: 
,09-08 17:57:30.376  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.376  3878  3924 I jxcore-log: 
09-08 17:57:30.377  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.377  3878  3924 I jxcore-log: 
,09-08 17:57:30.378  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.378  3878  3924 I jxcore-log: 
,09-08 17:57:30.379  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.379  3878  3924 I jxcore-log: 
09-08 17:57:30.380  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.380  3878  3924 I jxcore-log: 
09-08 17:57:30.381  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.381  3878  3924 I jxcore-log: 
,09-08 17:57:30.382  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.382  3878  3924 I jxcore-log: 
09-08 17:57:30.382  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.382  3878  3924 I jxcore-log: 
09-08 17:57:30.383  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.383  3878  3924 I jxcore-log: 
,09-08 17:57:30.384  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.384  3878  3924 I jxcore-log: 
09-08 17:57:30.385  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.385  3878  3924 I jxcore-log: 
,09-08 17:57:30.386  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.386  3878  3924 I jxcore-log: 
09-08 17:57:30.387  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.387  3878  3924 I jxcore-log: 
,09-08 17:57:30.387  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.387  3878  3924 I jxcore-log: 
,09-08 17:57:30.388  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.388  3878  3924 I jxcore-log: 
09-08 17:57:30.389  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.389  3878  3924 I jxcore-log: 
09-08 17:57:30.390  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.390  3878  3924 I jxcore-log: 
,09-08 17:57:30.390  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.390  3878  3924 I jxcore-log: 
09-08 17:57:30.391  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.391  3878  3924 I jxcore-log: 
,09-08 17:57:30.392  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.392  3878  3924 I jxcore-log: 
09-08 17:57:30.393  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.393  3878  3924 I jxcore-log: 
09-08 17:57:30.394  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.394  3878  3924 I jxcore-log: 
,09-08 17:57:30.394  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.394  3878  3924 I jxcore-log: 
09-08 17:57:30.395  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.395  3878  3924 I jxcore-log: 
09-08 17:57:30.396  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.396  3878  3924 I jxcore-log: 
,09-08 17:57:30.397  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.397  3878  3924 I jxcore-log: 
09-08 17:57:30.398  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.398  3878  3924 I jxcore-log: 
,09-08 17:57:30.399  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.399  3878  3924 I jxcore-log: 
09-08 17:57:30.399  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.399  3878  3924 I jxcore-log: 
09-08 17:57:30.400  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:57:30.400  3878  3924 I jxcore-log: 
,09-08 17:57:30.400  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.400  3878  3924 I jxcore-log: 
09-08 17:57:30.401  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 17:57:30.401  3878  3924 I jxcore-log: 
,09-08 17:57:30.401  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.401  3878  3924 I jxcore-log: 
,09-08 17:57:30.402  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.402  3878  3924 I jxcore-log: 
09-08 17:57:30.402  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.402  3878  3924 I jxcore-log: 
09-08 17:57:30.403  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.403  3878  3924 I jxcore-log: 
09-08 17:57:30.403  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.403  3878  3924 I jxcore-log: 
09-08 17:57:30.404  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:57:30.404  3878  3924 I jxcore-log: 
,09-08 17:57:30.404  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.404  3878  3924 I jxcore-log: 
,09-08 17:57:30.405  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 17:57:30.405  3878  3924 I jxcore-log: 
,09-08 17:57:30.405  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.405  3878  3924 I jxcore-log: 
09-08 17:57:30.406  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:57:30.406  3878  3924 I jxcore-log: 
09-08 17:57:30.407  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 17:57:30.407  3878  3924 I jxcore-log: 
,09-08 17:57:30.407  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 17:57:30.407  3878  3924 I jxcore-log: 
09-08 17:57:30.408  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:57:30.408  3878  3924 I jxcore-log: 
09-08 17:57:30.408  3878  3924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:57:30.408  3878  3924 I jxcore-log: 
09-08 17:57:30.412  3878  3924 I jxcore-log: My device name is: motorola-Nexus 6
09-08 17:57:30.412  3878  3924 I jxcore-log: 
,09-08 17:57:30.413  3878  3924 I jxcore-log: Running for WIFI network type
09-08 17:57:30.413  3878  3924 I jxcore-log: 
,09-08 17:57:32.862  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 17:57:32.862  3878  3924 I jxcore-log: 
,09-08 17:57:33.319  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 17:57:33.319  3878  3924 I jxcore-log: 
,09-08 17:57:33.352  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 17:57:33.352  3878  3924 I jxcore-log: 
,09-08 17:57:34.741  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 17:57:34.741  3878  3924 I jxcore-log: 
,09-08 17:57:34.986  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 17:57:34.986  3878  3924 I jxcore-log: 
,09-08 17:57:34.992  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 17:57:34.992  3878  3924 I jxcore-log: 
,09-08 17:57:34.998  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 17:57:34.998  3878  3924 I jxcore-log: 
,09-08 17:57:35.267  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 17:57:35.267  3878  3924 I jxcore-log: 
,09-08 17:57:35.284  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 17:57:35.284  3878  3924 I jxcore-log: 
,09-08 17:57:35.288  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 17:57:35.288  3878  3924 I jxcore-log: 
,09-08 17:57:36.004  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 17:57:36.004  3878  3924 I jxcore-log: 
,09-08 17:57:36.173  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 17:57:36.173  3878  3924 I jxcore-log: 
,09-08 17:57:36.509  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 17:57:36.509  3878  3924 I jxcore-log: 
,09-08 17:57:36.519  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 17:57:36.519  3878  3924 I jxcore-log: 
,09-08 17:57:36.527  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 17:57:36.527  3878  3924 I jxcore-log: 
,09-08 17:57:36.534  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 17:57:36.534  3878  3924 I jxcore-log: 
,09-08 17:57:36.575  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 17:57:36.575  3878  3924 I jxcore-log: 
,09-08 17:57:36.623  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 17:57:36.623  3878  3924 I jxcore-log: 
,09-08 17:57:36.630  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 17:57:36.630  3878  3924 I jxcore-log: 
,09-08 17:57:36.638  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 17:57:36.638  3878  3924 I jxcore-log: 
,09-08 17:57:36.658  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 17:57:36.658  3878  3924 I jxcore-log: 
,09-08 17:57:36.664  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 17:57:36.664  3878  3924 I jxcore-log: 
,09-08 17:57:36.670  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 17:57:36.670  3878  3924 I jxcore-log: 
,09-08 17:57:36.686  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 17:57:36.686  3878  3924 I jxcore-log: 
,09-08 17:57:36.713  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 17:57:36.713  3878  3924 I jxcore-log: 
,09-08 17:57:36.725  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 17:57:36.725  3878  3924 I jxcore-log: 
,09-08 17:57:36.739  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 17:57:36.739  3878  3924 I jxcore-log: 
,09-08 17:57:36.751  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 17:57:36.751  3878  3924 I jxcore-log: 
,09-08 17:57:36.767  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 17:57:36.767  3878  3924 I jxcore-log: 
,09-08 17:57:36.778  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 17:57:36.778  3878  3924 I jxcore-log: 
,09-08 17:57:36.783  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 17:57:36.783  3878  3924 I jxcore-log: 
,09-08 17:57:36.814  3878  3924 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 17:57:36.814  3878  3924 I jxcore-log: 
,09-08 17:57:36.826  3878  3924 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 17:57:36.828  3878  3924 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 17:57:36.828  3878  3924 I jxcore-log: 
,09-08 17:57:36.830  3878  3924 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-08 17:57:36.830  3878  3924 I jxcore-log: 
,09-08 17:57:36.830  3878  3924 I jxcore-log: ThaliTape :: Started ThaliTape
09-08 17:57:36.830  3878  3924 I jxcore-log: 
,09-08 17:57:36.836  3878  3924 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-08 17:57:36.836  3878  3924 I jxcore-log: 
,09-08 17:57:37.007  3878  3924 I jxcore-log: ThaliTape :: Connected to the test server
09-08 17:57:37.007  3878  3924 I jxcore-log: 
,09-08 17:59:08.997  3035  4362 V KeepSync: Connecting to GoogleApiClient
,09-08 17:59:08.998   873  1917 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 17:59:09.061  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:59:09.065  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:59:09.108  1522  2381 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 17:59:09.108  1522  2381 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 17:59:09.109  1522  2381 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:59:09.109  1522  2381 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:59:09.134  1741  4363 V BaseAuthAsyncOperation: access token request failed
,09-08 17:59:09.135  3035  4362 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 17:59:09.213  1522  2317 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 17:59:09.213  1522  2317 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 17:59:09.213  1522  2317 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:59:09.213  1522  2317 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:59:09.234  3035  4362 E KeepSync: IOException
09-08 17:59:09.234  3035  4362 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 17:59:09.234  3035  4362 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:59:09.234  3035  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 17:59:09.234  3035  4362 E KeepSync: 	... 10 more
09-08 17:59:09.234  3035  4362 W KeepSync: Sync result 2
,09-08 17:59:09.245   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 506363, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:59:41.190  3035  4365 V KeepSync: Connecting to GoogleApiClient
,09-08 17:59:41.191   873  2095 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 17:59:41.235  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:59:41.236  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:59:41.260  1522  2317 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 17:59:41.260  1522  2317 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 17:59:41.260  1522  2317 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:59:41.260  1522  2317 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:59:41.274  1741  4366 V BaseAuthAsyncOperation: access token request failed
,09-08 17:59:41.275  3035  4365 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 17:59:41.325  1522  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 17:59:41.325  1522  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 17:59:41.325  1522  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:59:41.325  1522  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:59:41.344  3035  4365 E KeepSync: IOException
09-08 17:59:41.344  3035  4365 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 17:59:41.344  3035  4365 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:59:41.344  3035  4365 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 17:59:41.344  3035  4365 E KeepSync: 	... 10 more
,09-08 17:59:41.344  3035  4365 W KeepSync: Sync result 2
,09-08 17:59:41.351   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 538748, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:00:11.507   873   873 I ActivityManager: Start proc 4368:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-08 18:00:11.651  4368  4368 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-08 18:00:11.681  4368  4368 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-08 18:00:11.681  4368  4368 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 18:00:11.681  4368  4368 I GAv4    :   adb logcat -s GAv4
,09-08 18:00:11.696  4368  4368 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:00:11.702  4368  4368 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:00:11.715  4368  4385 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:00:11.778  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:00:11.783  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:00:11.832  1522  2382 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:00:11.832  1522  2382 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:00:11.832  1522  2382 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:00:11.832  1522  2382 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:00:11.849  3547  4381 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 18:00:11.849  3547  4381 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at blb.a(PG:3937)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at czp.a(PG:18188)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:00:11.849  3547  4381 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	... 12 more
09-08 18:00:11.849  3547  4381 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at fal.a(PG:38)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:00:11.849  3547  4381 E HttpOperation: 	... 14 more
,09-08 18:00:11.887  1522  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:00:11.887  1522  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:00:11.887  1522  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:00:11.888  1522  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:00:11.902  3547  4381 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 18:00:11.902  3547  4381 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at hec.a(PG:42)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at hee.a(PG:102)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at czr.a(PG:65)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at kka.a(PG:108)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at czp.a(PG:19176)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:00:11.902  3547  4381 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	... 15 more
09-08 18:00:11.902  3547  4381 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at fal.a(PG:38)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:00:11.902  3547  4381 E HttpOperation: 	... 17 more
09-08 18:00:11.902  3547  4381 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 18:00:11.902  3547  4381 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at hec.a(PG:42)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at hee.a(PG:102)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at czr.a(PG:65)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at kka.a(PG:108)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	... 15 more
09-08 18:00:11.902  3547  4381 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at fal.a(PG:38)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 18:00:11.902  3547  4381 E ExperimentLoader: 	... 17 more
,09-08 18:00:12.061   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 547561, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:00:42.205  3659  4392 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 18:00:42.248  3659  4393 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 18:00:42.268  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:00:42.272  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:00:42.321  1522  2382 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 18:00:42.321  1522  2382 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 18:00:42.321  1522  2382 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:00:42.322  1522  2382 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:00:42.379  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:00:42.384  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:00:42.437  1522  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 18:00:42.437  1522  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 18:00:42.437  1522  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:00:42.438  1522  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:00:42.464  3659  4393 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 18:00:42.465  3659  4392 E BooksSync: Soft error
09-08 18:00:42.465  3659  4392 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:00:42.465  3659  4392 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 18:00:42.465  3659  4392 E BooksSync: Sync error
09-08 18:00:42.465  3659  4392 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:00:42.465  3659  4392 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 18:00:42.465  3659  4392 I BooksSync: Finished books sync
,09-08 18:00:42.477   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 576391, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:01:24.762  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:01:24.797  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:01:24.803  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:01:24.874   873   882 I art     : Background partial concurrent mark sweep GC freed 38234(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 942us total 106.361ms
,09-08 18:01:24.898  1522  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-08 18:01:24.898  1522  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-08 18:01:24.898  1522  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:01:24.898  1522  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:01:24.910  1522  2093 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 18:01:24.910  1522  2093 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 18:01:24.910  1522  2093 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 18:01:24.910  1522  2093 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 18:01:24.910  1522  2093 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 18:01:24.910  1522  2093 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 18:01:24.910  1522  2093 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 18:01:24.914  3508  3539 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 18:01:24.914  3508  3539 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 18:01:24.914  3508  3539 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 18:01:24.914  3508  3539 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 18:01:24.914  3508  3539 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 18:01:24.914  3508  3539 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 18:01:24.914  3508  3539 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 18:05:26.582   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=884210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:05:38.315   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=895944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:05:51.648   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:06:03.382   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=921010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:06:16.715   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=934343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:06:28.435   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:06:41.782   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=959410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:06:53.488   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=971117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:07:06.848   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=984476, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:07:18.555   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:07:31.915   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1009544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:07:43.621   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1021250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:07:56.982   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1034610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:08:08.675   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:08:22.022   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:08:33.742   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:08:47.115   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1084744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:08:58.822   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1096450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:09:12.182   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1109810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:09:23.888   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:09:37.222   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1134850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:09:48.942   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1146570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:10:02.262   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1159890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:10:14.009   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1171637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:10:17.555   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1175184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:10:39.075   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:10:42.608   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1200237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:11:00.704   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 18:11:04.141   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:11:11.488   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1229117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:11:32.995   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1250624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:11:36.595   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1254224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:11:58.129   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1275757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:12:01.661   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1279290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:12:23.208   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1300837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:12:26.755   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1304383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:12:48.288   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1325917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:12:51.835   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1329464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:13:13.355   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1350984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:13:16.901   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1354530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:13:38.421   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1376050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:13:41.955   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1379583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:14:03.489   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1401117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:14:07.022   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1404651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:14:28.555   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1426184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:14:32.101   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1429730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:14:53.622   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1451250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:14:57.154   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1454783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:15:18.688   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1476317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:15:23.681   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1481310, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:15:44.715   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1502344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:15:48.248   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1505877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:16:09.769   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1527397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:16:13.315   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1530944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:16:34.862   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1552490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:16:38.408   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1556036, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:16:59.928   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1577556, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:17:03.475   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1581103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:17:24.982   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1602611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:17:28.528   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1606157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:17:50.048   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1627677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:17:53.595   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1631223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:18:15.115   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1652744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:18:18.661   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1656290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:18:40.182   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1677811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:18:43.715   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1681343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-08 18:19:05.235   873  4307 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1702864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-08 18:19:06.560  4453  4453 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 18:19:06.565  4453  4453 D AndroidRuntime: CheckJNI is OFF
09-08 18:19:06.601  4453  4453 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 18:19:06.642  4453  4453 I Radio-JNI: register_android_hardware_Radio DONE
09-08 18:19:06.663  4453  4453 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 18:19:06.682   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-08 18:19:06.683   873   886 I ActivityManager: Killing 3878:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-08 18:19:06.797   873  1308 D WifiService: Client connection lost with reason: 4
09-08 18:19:06.801   873  1372 I WindowState: WIN DEATH: Window{cebcdaa u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 18:19:06.805   873  1953 D GraphicsStats: Buffer count: 2
09-08 18:19:06.819   873   896 W PackageSettings: Skipping PackageSetting{b484c56 com.example.hello/10273} due to missing metadata
09-08 18:19:06.850   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-08 18:19:06.851   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-08 18:19:06.851   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-08 18:19:06.851   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 18:19:06.851   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:06.851   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:06.851   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:06.851   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 18:19:06.851   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3f1d297 u0 com.test.thalitest/.MainActivity t4}
09-08 18:19:06.853   873   896 I art     : Starting a blocking GC Explicit
09-08 18:19:06.870   873  1917 W ActivityManager: Spurious death for ProcessRecord{34d72e4 0:com.test.thalitest/u0a0}, curProc for 3878: null
09-08 18:19:06.909   873   896 I art     : Explicit concurrent mark sweep GC freed 33472(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 793us total 55.325ms
09-08 18:19:06.930   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 18:19:06.933  4453  4453 I art     : System.exit called, status: 0
09-08 18:19:06.933  4453  4453 I AndroidRuntime: VM exiting with result code 0.
09-08 18:19:06.941   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-08 18:19:06.956   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-08 18:19:06.960  4250  4250 D BluetoothMapAppObserver: onReceive
09-08 18:19:06.960  4250  4250 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 18:19:06.973   873  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 18:19:06.973  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 18:19:06.973  2120  2297 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 18:19:06.979  3685  3685 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-08 18:19:06.994  1870  4467 I Keyboard.Facilitator.DecoderInitializer: run()
09-08 18:19:07.002   873  1930 I ActivityManager: Start proc 4470:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 18:19:07.017  1870  4467 I Decoder : createOrResetDecoder
09-08 18:19:07.027  1933  1933 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-08 18:19:07.046   873  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-08 18:19:07.049  1522  1522 I ConfigService: onCreate
09-08 18:19:07.053  4470  4470 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 18:19:07.064  1522  4482 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 18:19:07.064  1522  4482 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:19:07.065  1522  4482 W SQLiteOpenHelper: Opened config.db in read-only mode
09-08 18:19:07.078   873  1917 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3878 uid 10000
09-08 18:19:07.079  1870  1870 I Keyboard.Facilitator: onFinishInput()
09-08 18:19:07.079   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 18:19:07.086  1870  4467 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-08 18:19:07.100   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 18:19:07.101   873   885 E PackageManager: Failed to write settings, restoring backup
09-08 18:19:07.101   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 18:19:07.101   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 18:19:07.101   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 18:19:07.101   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 18:19:07.101   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 18:19:07.101   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.101   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.101   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.106   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-08 18:19:07.106   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 18:19:07.106   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:19:07.106   873   886 E DropBoxManagerService: 	... 13 more
09-08 18:19:07.114  1946  2028 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-08 18:19:07.119  1870  4467 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-08 18:19:07.121  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 18:19:07.121  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-08 18:19:07.122  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 18:19:07.122  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 18:19:07.123  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 18:19:07.123  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 18:19:07.123  1870  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 18:19:07.123  1870  4467 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 18:19:07.124  1870  4467 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 18:19:07.124  1870  4467 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 18:19:07.124  1870  4467 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 18:19:07.124  1870  4467 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-08 18:19:07.130   873  1547 I ActivityManager: Start proc 4486:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-08 18:19:07.131  1946  2028 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 18:19:07.131  1946  2028 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1946
09-08 18:19:07.131  1946  2028 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.131  1946  2028 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.133   873  1547 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 18:19:07.133   873  4492 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:19:07.133   873  4492 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:19:07.133   873  4492 E DropBoxManagerService: 	... 5 more
09-08 18:19:07.140  1946  2028 I Process : Sending signal. PID: 1946 SIG: 9
09-08 18:19:07.146  4470  4470 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 18:19:07.165   873  2112 I ActivityManager: Start proc 4502:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-08 18:19:07.171  4470  4501 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 18:19:07.201  4502  4502 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.215  4470  4484 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.216  4470  4484 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.218   873  1932 D GraphicsStats: Buffer count: 1
09-08 18:19:07.218   873  1930 I WindowState: WIN DEATH: Window{f92a61 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 18:19:07.229   873  1932 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1946) has died
09-08 18:19:07.230   873  1932 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 18:19:07.231   873  1932 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 18:19:07.236  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 18:19:07.240  1522  1522 D AndroidRuntime: Shutting down VM
09-08 18:19:07.241  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
09-08 18:19:07.241  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
09-08 18:19:07.241  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 18:19:07.241  1522  1522 E AndroidRuntime: 	... 8 more
09-08 18:19:07.247   873   886 I ActivityManager: Start proc 4518:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 18:19:07.252   873  4524 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:19:07.252   873  4524 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:19:07.252   873  4524 E DropBoxManagerService: 	... 5 more
09-08 18:19:07.252   873  1917 I ActivityManager: Killing 2011:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-08 18:19:07.288  4470  4484 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.293  4470  4501 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 18:19:07.293  4470  4501 E AndroidRuntime: Process: android.process.acore, PID: 4470
09-08 18:19:07.293  4470  4501 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.293  4470  4501 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:19:07.293  4470  4484 I Process : Sending signal. PID: 4470 SIG: 9
09-08 18:19:07.305   873  1308 D WifiService: Client connection lost with reason: 4
09-08 18:19:07.310  1522  1522 I Process : Sending signal. PID: 1522 SIG: 9
09-08 18:19:07.322   873  4531 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:19:07.322   873  4531 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:19:07.322   873  4531 E DropBoxManagerService: 	... 5 more
09-08 18:19:07.336   873  1930 I ActivityManager: Process android.process.acore (pid 4470) has died
09-08 18:19:07.336   873  1930 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:19:07.341  4518  4518 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:19:07.341  4518  4518 D AndroidRuntime: Shutting down VM
09-08 18:19:07.346  4518  4518 E AndroidRuntime: FATAL EXCEPTION: main
09-08 18:19:07.346  4518  4518 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4518
09-08 18:19:07.346  4518  4518 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 18:19:07.346  4518  4518 E AndroidRuntime: 	... 10 more
09-08 18:19:07.351   873  1917 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 18:19:07.351  4518  4518 I Process : Sending signal. PID: 4518 SIG: 9
09-08 18:19:07.358   873  4534 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:19:07.358   873  4534 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:19:07.358   873  4534 E DropBoxManagerService: 	... 5 more
09-08 18:19:07.406   873  1308 D WifiService: Client connection lost with reason: 4
09-08 18:19:07.408  1741  4533 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@693a6db
09-08 18:19:07.411   873  1930 I ActivityManager: Process com.google.process.gapps (pid 1522) has died
09-08 18:19:07.411   873  1930 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-08 18:19:07.411   873  1930 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-08 18:19:07.411   873  1930 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-08 18:19:07.420  1741  1741 W RocketImpressions: ClearcutLogger connection suspended: 1

```
